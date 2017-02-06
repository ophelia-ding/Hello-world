<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Dashboard</title>
	<!-- BEGIN GLOBAL MANDATORY STYLES -->
	<link rel="stylesheet" type="text/css" href="assets/global/plugins/font-awesome/css/font-awesome.min.css">
	<link rel="stylesheet" type="text/css" href="assets/global/plugins/bootstrap/css/bootstrap.min.css">
	<!-- END GLOBAL MANDATORY STYLES -->
	<!-- BEGIN THEME LAYOUT STYLES -->
	<link rel="stylesheet" type="text/css" href="assets//style/layout.css">
	<!-- END THEME LAYOUT STTLES -->
</head>
<body>
	<div class="page-header navbar navbar-fixed-top">
		<div class="page-header-inner">
			<div class="page-logo">
				<a href="index.html">
					<img src="assets/img/logo-default.png" alt="logo" class="">
				</a>
				<div class="menu-toggler">	
				</div>
			</div>
			<div class="page-action clearfloat">
				<div class="btn-group">
					<button type="button" class="btn dropdown-toggle" data-toggle="dropdown">
						<i class=" fa fa-plus"></i>
						<span class=""> New&nbsp;</span>
						<i class="fa fa-angle-down"></i>
					</button>
					<ul class="dropdown-menu" role="menu">
						<li>
							<a href="#"><i class="fa fa-files-o "></i> New Post</a>
						</li>
						<li>
							<a href="#"><i class="fa fa-tag"></i> New Comment</a>
						</li>
						<li>
							<a href="#"><i class="fa fa-share"></i>Share</a>
						</li>
						<li class="divider"></li>
						<li>
							<a href="#"><i class="fa fa-flag"></i>Comments
								<span class="badge badge-info">4</span>
							</a>
						</li>
						<li>
							<a href="#"><i class="fa fa-users"></i>Feedbacks
								<span class="badge badge-danger">2</span>
							</a>
						</li>
					</ul>
				</div>	

				<from class="search-form" anction="index.html" method="GET">
					<div class="input-group">
						<input type="text" name="query"  placeholder="search...">
						<span class="input-group-btn">
							<a href="javascript:;" class="btn submit">
								<i class="fa fa-search"></i>
							</a>
						</span>
					</div>
				</from>
			</div>
			<div class="page-top">
				<div class="top-menu">
					<ul class="nav">
						<li class="dropdown " id="header-notification-bar" >
							<a href="javascript:;" class="dropdown-toggle" data-toggle="dropdown" data-hover="dropdown" data-close-others="true">
								<i class="fa fa-bell"></i>
								<span class="badge">7</span>
							</a>
							<ul class="dropdown-menu">
								<li class="external">
									<h3><span>12 pending</span> notifications</h3>
									<a href="#">view all</a>
								</li>
								<li>
									<ul>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-plus"></i></span>New user registered.</span>
												<span>just now</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bolt"></i></span>Server #12 overloaded.</span>
												<span>10 mins</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bell-o"></i></span>Server #2 not responding.</span>
												<span>1 hours</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bullhorn"></i></span>Application error.</span>
												<span>2 days</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bolt"></i></span>Database overloaded 68%.</span>
												<span>4 days</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bolt"></i></span>A user IP blocked.</span>
												<span>4 days</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bell-o"></i></span>Storage Server #4 not responding dfdfdfd.</span>
												<span>9 days</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bullhorn"></i></span>System Error.</span>
												<span>5 days</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span class="details"><span><i class="fa fa-bolt"></i></span>Storage server failed.</span>
												<span>9 days</span>
											</a>
										</li>
									</ul>
								</li>
							</ul>
						</li>
						<li class="dropdown" id="header-inbox-bar">
							<a href="javascript:;" class="dropdown-toggle" data-toggle="dropdown" data-hover="dropdown" data-close-others="true">
								<i class="fa fa-envelope-open"></i>
								<span class="badge">3</span>
							</a>
							<ul class="dropdown-menu">
								<li class="external">
									<h3>You have<span class="bold">7 New</span> Messages</h3>
									<a href="#">view all</a>
								</li>
								<li>
									<ul>
										<li>
											<a href="#">
												<span><img src="assets/img/avatar2.jpg" alt=""></span>
													<span>
														<span>Lisa Wong</span>
														<span>Just Now</span>
													</span>
													<span>Vivamus sed auctor nibh congue nibh. auctor nibh auctor nibh...</span>
											</a></li>
										<li>
											<a href="#">
												<span><img src="assets/img/avatar3.jpg" alt=""></span>
													<span>
														<span>Richard Doe</span>
														<span>16 mins</span>
													</span>
													<span>Vivamus sed congue nibh auctor nibh congue nibh. auctor nibh auctor nibh...</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span><img src="assets/img/avatar1.jpg" alt=""></span>
													<span>
														<span>Bob Nilson</span>
														<span>2 hrs</span>
													</span>
													<span>Vivamus sed congue nibh auctor nibh congue nibh. auctor nibh auctor nibh...</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span><img src="assets/img/avatar2.jpg" alt=""></span>
													<span>
														<span>Lisa Wong</span>
														<span>40 mins</span>
													</span>
													<span>Vivamus sed congue nibh auctor nibh congue nibh. auctor nibh auctor nibh...</span>
											</a>
										</li>
										<li>
											<a href="#">
												<span><img src="assets/img/avatar1.jpg" alt=""></span>
													<span>
														<span>Richard Doe</span>
														<span>46 min</span>
													</span>
													<span>Vivamus sed congue nibh auctor nibh congue nibh. auctor nibh auctor nibh...</span>
											</a>
										</li>
									</ul>									
								</li>
							</ul>
						</li>
						<li class="dropdown" id="header-task-bar">
							<a href="javascript:;" class="dropdown-toggle" data-toggle="dropdown" data-hover="dropdown" data-close-others="true">
								<i class="fa fa-calendar"></i>
								<span class="badge">4</span>
							</a>
							<ul class="dropdown-menu">
								<li>
									<h3>You have<span class="bold">12 pending</span> tasks</h3>
									<a href="">view all</a>
								</li>
								<li>
									<ul>
										<li><a href="">
												<spn>
													<span>New release v1.2</span>
													<span>30%</span>
												</spn>
												<spn></spn>
											</a>
										</li>
										<li><a href="">
												<spn>
													<span>Application deployment</span>
													<span>65%</span>
												</spn>
												<spn></spn>
											</a>
										</li>
										<li><a href="">
												<spn>
													<span>Mobile app release</span>
													<span>98%</span>
												</spn>
												<spn></spn>
											</a>
										</li>
										<li><a href="">
												<spn>
													<span>Database migration</span>
													<span>10%</span>
												</spn>
												<spn></spn>
											</a>
										</li>
										<li><a href="">
												<spn>
													<span>Web server upgrade</span>
													<span>58%</span>
												</spn>
												<spn></spn>
											</a>
										</li>
										<li><a href="">
												<spn>
													<span>Mobile development</span>
													<span>85%</span>
												</spn>
												<spn></spn>
											</a>
										</li>
										<li><a href="">
												<spn>
													<span>New UI release</span>
													<span>38%</span>
												</spn>
												<spn></spn>
											</a>
										</li>
									</ul>
								</li>
							</ul>
						</li>
						<li class="dropdown" id="header-user-bar">
							<a href="javascript:;" class="dropdown-toggle" data-toggle="dropdown" data-hover="dropdown" data-close-others="true">
								<img src="assets/img/avatar3.jpg">
								<span>Nick</span>
								<i class="fa fa-angle-down"></i>
							</a>
							<ul class="dropdown-menu">
								<li>
									<a href="#">
										<span><i class="fa fa-user"></i></span>
										<span> My Profile</span>
									</a>
								</li>
								<li>
									<a href="#">
										<span><i class="fa fa-calendar"></i></span>
										<span>My Calendar</span>
									</a>
								</li>
								<li>
									<a href="#">
										<span><i class="fa fa-envelope-open"></i></span>
										<span>My Inbox</span><span class="badge">3</span>
									</a>
								</li>
								<li>
									<a href="#">
										<span><i class="fa fa-rocket"></i></span>
										<span>My Tasks</span><span class="badge">7</span>
									</a>
								</li>
								<li class="divider"></li>								
								<li>
									<a href="#">
										<span><i class="fa fa-lock"></i></span>
										<span>Lock Screen</span>
									</a>
								</li>
								<li>
									<a href="#">
										<span><i class="fa fa-key"></i></span>
										<span>Log Out</span>
									</a>
								</li>
							</ul>
						</li>
						<li class="dropdown">
							<span><i class="fa fa-sign-out"></i></span>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
	<div class="content"></div>
	<footer></footer>

	<!--[if lt IE 9]>
	<![endif]-->
	<!--BEGIN CORE PLUGINS -->
	<script type="text/javascript" src="assets/global/plugins/jquery.min.js"></script>
	<script type="text/javascript" src="assets/global/plugins/bootstrap/js/bootstrap.min.js"></script>
</body>
</html>
