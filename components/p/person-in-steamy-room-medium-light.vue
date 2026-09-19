<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOokUYv)" class="r_bcr-ntk"/><circle fill="url(#ig6gRjd)" class="r_bcr-ntk"/><circle fill="url(#ifqCFkS)" class="iksuiqrgf"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.368)" class="n5l_opbqq"/><path fill="url(#i4UUWGe)" class="w8e9izb-y"/><path fill="url(#iFqMHgd)" class="w8e9izb-y"/><path fill="url(#iS6d3Rd)" class="w8e9izb-y"/><path fill="url(#i7GTaad)" class="rgs-6fbpw"/><path fill="url(#iU0xveW)" class="rgs-6fbpw"/><path class="lr6p412xr"/><path fill="url(#iJvbFZb)" class="gt-y46nru"/><path fill="url(#iMrfvye)" class="gt-y46nru"/><path fill="url(#ip742Bh)" class="gt-y46nru"/><path fill="url(#izyBClb)" class="gt-y46nru"/><path fill="url(#irX7roe)" class="gt-y46nru"/><path fill="url(#iB984Kc)" class="gt-y46nru"/><path class="dk0gm-byq"/><path fill="url(#i1Dor5L)" class="s6ufut5ul"/><path fill="url(#iv6Yn7W)" class="s6ufut5ul"/><path fill="url(#i4wIgAd)" class="s6ufut5ul"/><g filter="url(#iQKmOfb)"><path fill="url(#iXlD41c)" class="uygoe8bue"/><path fill="url(#in8duDK)" class="uygoe8bue"/><path fill="url(#iMP6DMe)" class="uygoe8bue"/></g><path class="wkmk90b2p"/><g filter="url(#ihpzEtd)"><path class="ujd1vybxb"/></g><path fill="url(#iWhVkOd)" class="gl1a3jbde"/><path fill="url(#ifrvEib)" class="zyxtmxbvw"/><path fill="url(#ixu4V6b)" class="zyxtmxbvw"/><path fill="url(#ifrvEib)" class="zyxtmxbvw"/><path fill="url(#ixu4V6b)" class="zyxtmxbvw"/><g filter="url(#i66C6Bd)"><path fill="url(#ioPdvrd)" class="epaghdc0t"/></g><path fill="url(#i2fMWZu)" class="epaghdc0t"/><path fill="url(#iPJwwxA)" class="epaghdc0t"/><path fill="url(#iRm9SBc)" class="epaghdc0t"/><path fill="url(#iFdOlsc)" class="epaghdc0t"/><path fill="url(#i0CKjub)" class="epaghdc0t"/><path fill="url(#iIWW3ZU)" class="epaghdc0t"/><path fill="url(#iiRWLld)" class="epaghdc0t"/><path fill="url(#icg4wlb)" class="epaghdc0t"/><g filter="url(#imU5wSb)"><path class="pn5dqxymu"/></g><g filter="url(#i87CSDb)"><path fill="url(#if0zMxd)" class="tgex-ob-h"/><path fill="url(#ir20vcc)" class="tgex-ob-h"/><path fill="url(#ifyuZEc)" class="tgex-ob-h"/><path fill="url(#iWYcCYc)" class="tgex-ob-h"/></g><g filter="url(#iLPLj9c)"><path stroke="url(#i9ucG4S)" class="frx447u6y"/></g><path fill="url(#iASE7ve)" class="y299lcb5j"/><g filter="url(#iIJAx0d)"><path fill="url(#iLROv1b)" class="l9w39y8hl"/><path fill="url(#igyohLd)" class="l9w39y8hl"/><path fill="url(#iX3CyoQ)" class="l9w39y8hl"/><path fill="url(#iXbiEZC)" class="l9w39y8hl"/><path fill="url(#ihFFFCL)" class="l9w39y8hl"/></g><g filter="url(#iGPB5Jd)"><path class="o63xdtqyc"/></g><g filter="url(#izfmnAe)"><path class="he3r7fbsu"/></g><g filter="url(#ijrzBbe)"><path fill="url(#iMWPfse)" class="hz9o0k8yr"/><path fill="url(#iJRlnYd)" class="hz9o0k8yr"/></g><g filter="url(#iMNSUwe)"><path fill="url(#iBB6oyc)" class="m-ngl022d"/><path fill="url(#iTK1W0Z)" class="m-ngl022d"/><path fill="url(#iamgC9c)" class="m-ngl022d"/><path fill="url(#iAmaqjb)" class="m-ngl022d"/><path fill="url(#iRZbIsc)" class="m-ngl022d"/><path fill="url(#iNlk91d)" class="m-ngl022d"/></g><path class="i8o1iacxv"/><path fill="url(#iM7Wwve)" class="f7fam02nn"/><path class="rt8f9chvu"/><g filter="url(#iWGI4Mv)"><path class="uwipchbui"/><path fill="url(#iryRCtd)" class="jne7u7bpd"/></g><g filter="url(#iXxlmEe)"><path fill="url(#i5BynNe)" class="g_p71fu0k"/></g><path class="rl6zs7yhb"/><path fill="url(#iUNDeFb)" class="qdnqv10ox"/><path class="ai_-89uyo"/><g filter="url(#i1P5Syb)"><path fill="url(#iWsLcyv)" class="uny96bcfc"/></g><g filter="url(#i8PAV7r)"><ellipse transform="rotate(-27.914 13.4 9.981)" class="hrqpq4_5o"/><ellipse fill="url(#iB7g49P)" transform="rotate(-27.914 13.4 9.981)" class="a57mrebnw"/></g><path fill="url(#iJCpusc)" class="ofax10bwa"/><path fill="url(#iwf7xmo)" class="ofax10bwa"/><path fill="url(#i3tApCc)" class="ofax10bwa"/><path fill="url(#ix0Qjlc)" class="mz-slk5ug"/><path fill="url(#iFXOjFd)" class="mz-slk5ug"/><g filter="url(#iWuLygm)"><path class="j67khjb2r"/></g><g filter="url(#iRrGz4N)"><path class="pc5jlhn5w"/></g><g filter="url(#iNPaBad)"><path class="m8q5t-o2a"/></g><g filter="url(#ieAprue)"><path class="oiscfh1gb"/></g><defs><radialGradient id="iOokUYv" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.33)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="ig6gRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.83)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="ifqCFkS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.268)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="i4UUWGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.58)" gradientUnits="userSpaceOnUse"><stop class="yf3t3eb5f"/><stop offset="1" class="a66gbwbzh"/></radialGradient><radialGradient id="i7GTaad" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.32)" gradientUnits="userSpaceOnUse"><stop class="pbkzvtx_w"/><stop offset="1" class="ykdcls_lk"/></radialGradient><radialGradient id="iJvbFZb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="k3qin7bzy"/><stop offset="1" class="x3axlob0n"/></radialGradient><radialGradient id="ip742Bh" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.962)" gradientUnits="userSpaceOnUse"><stop class="z2ddyab4m"/><stop offset="1" class="cqgvl433q"/></radialGradient><radialGradient id="irX7roe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.58)" gradientUnits="userSpaceOnUse"><stop class="h3e5alaje"/><stop offset="1" class="u4bo2-o9a"/></radialGradient><radialGradient id="iB984Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.515)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="gyulks50m"/><stop offset="1" class="atms-xm-n"/></radialGradient><radialGradient id="iv6Yn7W" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="k-y64ibbx"/><stop offset="1" class="pjzr3aclu"/></radialGradient><radialGradient id="i4wIgAd" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.49 18.294)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="bc2qs9bhj"/><stop offset="1" class="ktoycacxm"/></radialGradient><radialGradient id="in8duDK" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.75 -2.19025 2.26847 13.158 17.204)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="ps_f7cbop"/><stop offset="1" class="dggv0hbyd"/></radialGradient><radialGradient id="iMP6DMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01211 -.76307 0 16.64 16.221)" gradientUnits="userSpaceOnUse"><stop class="nxgp0pbvn"/><stop offset="1" class="qc1uy5bzw"/><stop offset="1" class="qc1uy5bzw"/></radialGradient><radialGradient id="iWhVkOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61715 3.57976 -4.25248 -.73313 21.413 11.792)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="ifrvEib" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -4.422 14.16)scale(3.00702 1.36683)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="ixu4V6b" cx="0" cy="0" r="1" gradientTransform="matrix(.1816 1.20893 -1.06048 .1593 11.077 11.871)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="ioPdvrd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.29484 0 0 -9.36652 18.728 11.006)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iPJwwxA" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15764 13.12916 -10.87252 -.95866 17.486 5.017)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="dqi7sbofo"/><stop offset="1" class="qz-t25gyz"/></radialGradient><radialGradient id="iRm9SBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.35809 1.68063 0 18.363 9.872)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iFdOlsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0588 -1.11753 1.21615 -.064 13.617 9.733)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i0CKjub" cx="0" cy="0" r="1" gradientTransform="matrix(1.22228 0 0 6.21257 10.941 11.396)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iIWW3ZU" cx="0" cy="0" r="1" gradientTransform="rotate(-54.413 12.727 -5.7)scale(4.55073 1.03075)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iiRWLld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.44452 -10.37418 11.42754 -2.69272 15.728 15.13)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="icg4wlb" cx="0" cy="0" r="1" gradientTransform="matrix(2.07108 .72997 -.4379 1.24243 17.867 5.556)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i9ucG4S" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.607 -5.413)scale(.71919 2.09289)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iASE7ve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72997 2.93686 0 15.885 14.59)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="igyohLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.6792 6.51882 0 10.588 9.404)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iX3CyoQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.6792 6.51882 0 20.807 9.404)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iXbiEZC" cx="0" cy="0" r="1" gradientTransform="matrix(-3.29336 -1.25623 .66903 -1.75393 20.043 3.047)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ihFFFCL" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.202 14.09)scale(1.75274 4.05851)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iMWPfse" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8557 1.39118 -.3872 -1.07313 16.141 2.895)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iJRlnYd" cx="0" cy="0" r="1" gradientTransform="matrix(3.2594 -5.16073 5.71756 3.61109 10.384 7.716)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iBB6oyc" cx="0" cy="0" r="1" gradientTransform="matrix(3.42917 .81109 -.45362 1.91782 19.552 4.07)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iTK1W0Z" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.055 -1.703)scale(4.33668 2.41853)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iamgC9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32412 -2.23051 1.59762 -.9484 20.45 8.43)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iAmaqjb" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 10.136 3.203)scale(4.99782 5.40284)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iRZbIsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11884 .38865 -1.77684 -.5433 19.382 3.825)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iNlk91d" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.79 7.32)scale(4.30594 11.1038)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iM7Wwve" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82172 -1.30703 0 18.094 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iryRCtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23489 -.3027 .41673 -.32338 17.863 10.163)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUNDeFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82176 -1.3071 0 13.675 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iB7g49P" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.762 -1.438)scale(.50048 .60159)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwf7xmo" cx="0" cy="0" r="1" gradientTransform="matrix(.6366 2.27202 -2.16769 .60737 20.561 10.092)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="i3tApCc" cx="0" cy="0" r="1" gradientTransform="matrix(.79788 -1.09496 .9178 .66878 20.926 10.644)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iFXOjFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69648 -.2481 .2439 -1.66779 10.906 10.744)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="iQKmOfb" width="6.906" height="10.938" x="12.293" y="16.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.458824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_788"/></filter><filter id="ihpzEtd" width="3.076" height="1.977" x="15.252" y="17.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".3"/></filter><filter id="i66C6Bd" width="11.101" height="12.7" x="10.756" y="4.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_788"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_788" result="effect2_innerShadow_4002_788"/></filter><filter id="imU5wSb" width="3.777" height="4.86" x="13.724" y="9.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".5"/></filter><filter id="i87CSDb" width="2.101" height="3.137" x="14.834" y="9.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".05"/></filter><filter id="iLPLj9c" width="3.76" height="1.587" x="14.005" y="13.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".05"/></filter><filter id="iIJAx0d" width="13.038" height="8.457" x="9.365" y="1.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_788"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_788" result="effect2_innerShadow_4002_788"/></filter><filter id="iGPB5Jd" width="2.368" height="1.203" x="17.494" y="7.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_788"/></filter><filter id="izfmnAe" width="2.368" height="1.188" x="12.17" y="7.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_788"/></filter><filter id="ijrzBbe" width="6.662" height="6.062" x="9.729" y="2.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".125"/></filter><filter id="iMNSUwe" width="6.44" height="5.806" x="15.723" y="3.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".125"/></filter><filter id="iWGI4Mv" width=".794" height=".703" x="17.352" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".05"/></filter><filter id="iXxlmEe" width=".898" height=".92" x="18.204" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".1"/></filter><filter id="i1P5Syb" width=".994" height="1.048" x="13.704" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".1"/></filter><filter id="i8PAV7r" width=".922" height=".711" x="12.939" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".05"/></filter><filter id="iWuLygm" width="1.34" height="2.403" x="9.778" y="9.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".125"/></filter><filter id="iRrGz4N" width="1.459" height="2.428" x="20.66" y="9.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".125"/></filter><filter id="iNPaBad" width="2.426" height="1.166" x="12.093" y="7.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".125"/></filter><filter id="ieAprue" width="2.426" height="1.166" x="17.439" y="7.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_788" stdDeviation=".125"/></filter><linearGradient id="iFqMHgd" x1="24.158" x2="24.189" y1="30.329" y2="26.673" gradientUnits="userSpaceOnUse"><stop offset=".078" class="npfrbd3jd"/><stop offset="1" class="w_5-rbc1a"/></linearGradient><linearGradient id="iS6d3Rd" x1="18.12" x2="19.472" y1="27.765" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="p5jt_ib0l"/><stop offset="1" class="hw19_ybat"/></linearGradient><linearGradient id="iU0xveW" x1="13.658" x2="12.158" y1="28.736" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="h65uoi6pi"/><stop offset="1" class="g04ogacjt"/></linearGradient><linearGradient id="iMrfvye" x1="12.315" x2="13.69" y1="27.392" y2="26.829" gradientUnits="userSpaceOnUse"><stop offset=".223" class="d05zivoho"/><stop offset="1" class="ue2ywxbfs"/></linearGradient><linearGradient id="izyBClb" x1="15.627" x2="14.221" y1="30.173" y2="29.486" gradientUnits="userSpaceOnUse"><stop offset=".208" class="cu8bl7b6w"/><stop offset="1" class="bkwavzmor"/></linearGradient><linearGradient id="i1Dor5L" x1="16.002" x2="18.033" y1="24.829" y2="25.736" gradientUnits="userSpaceOnUse"><stop class="ego3-fbwo"/><stop offset="1" class="up5p4s41k"/></linearGradient><linearGradient id="iXlD41c" x1="16.366" x2="16.366" y1="25.145" y2="15.619" gradientUnits="userSpaceOnUse"><stop class="kqw3-db6l"/><stop offset="1" class="mnloc2nlg"/></linearGradient><linearGradient id="i2fMWZu" x1="21.108" x2="16.699" y1="12.713" y2="12.713" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="if0zMxd" x1="15.884" x2="16.75" y1="11.846" y2="11.846" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="ir20vcc" x1="14.798" x2="15.886" y1="11.688" y2="11.748" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ifyuZEc" x1="15.884" x2="15.884" y1="12.249" y2="13.112" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iWYcCYc" x1="15.884" x2="15.884" y1="9.973" y2="10.398" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iLROv1b" x1="21.317" x2="11.063" y1="5.271" y2="5.271" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="i5BynNe" x1="18.882" x2="18.564" y1="10.133" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWsLcyv" x1="14.428" x2="14.11" y1="10.133" y2="10.329" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJCpusc" x1="22.403" x2="21.181" y1="10.16" y2="12.364" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ix0Qjlc" x1="9.96" x2="11.437" y1="10.873" y2="10.744" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-steamy-room-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a57mrebnw {
  cx: 13.4px;
  cy: 9.981px;
  rx: 0.395px;
  ry: 0.2px;
}

.a66gbwbzh {
  stop-color: var(--svg-color--f65c3e, #F65C3E);
}

.ai_-89uyo {
  fill: var(--svg-color--000, #000);
  d: path("M14.19 10.499a.516.516 0 0 0-.518-.518a.516.516 0 0 0-.46.756h.917a.5.5 0 0 0 .061-.238");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.atms-xm-n {
  stop-color: var(--svg-color--9e2625, #9E2625);
  stop-opacity: 0;
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.bc2qs9bhj {
  stop-color: var(--svg-color--ff7347, #FF7347);
}

.bkwavzmor {
  stop-color: var(--svg-color--dd5022, #DD5022);
  stop-opacity: 0;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqgvl433q {
  stop-color: var(--svg-color--f47246, #F47246);
  stop-opacity: 0;
}

.cu8bl7b6w {
  stop-color: var(--svg-color--dd5022, #DD5022);
}

.d05zivoho {
  stop-color: var(--svg-color--e45c36, #E45C36);
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.dggv0hbyd {
  stop-color: var(--svg-color--c38266, #C38266);
  stop-opacity: 0;
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dk0gm-byq {
  fill: var(--svg-color--ec551b, #EC551B);
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.ego3-fbwo {
  stop-color: var(--svg-color--ce3b1b, #CE3B1B);
}

.epaghdc0t {
  d: path("M10.998 13.807a3.966 3.966 0 0 0 3.935 3.45h1.91a3.966 3.966 0 0 0 3.936-3.45c.12-1.908.24-3.808.329-5.715a1.47 1.47 0 0 0-1.397-1.45h-1.418a2.45 2.45 0 0 1-2.24-1.462a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.423c0 1.884.118 3.738.242 5.628");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f7fam02nn {
  d: path("M18.097 9.595a.904.904 0 0 1 .87 1.142h-1.746a.907.907 0 0 1 .875-1.142");
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.frx447u6y {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.516 13.54c.395.207.866.325 1.369.325c.507 0 .973-.118 1.368-.324a.23.23 0 0 1 .274.044c.065.068.09.177.024.275m-3.035-.32l2.972.279m-2.972-.278a.23.23 0 0 0-.274.047a.214.214 0 0 0-.023.273m.297-.32l-.235.278m3.27.041l-.063-.041m.063.041l-.063-.041m.063.041c-.353.535-.967.89-1.666.89a2 2 0 0 1-1.666-.889m3.27-.042a1.92 1.92 0 0 1-1.604.857a1.92 1.92 0 0 1-1.604-.857m-.062.042l.062-.042m-.062.042l.062-.042");
}

.ft5dv1b6b {
  fill: none;
}

.g_p71fu0k {
  d: path("M18.902 10.38a.85.85 0 0 0-.235-.469l-.263.29l.119.23z");
}

.g04ogacjt {
  stop-color: var(--svg-color--d63c26, #D63C26);
  stop-opacity: 0;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gl1a3jbde {
  d: path("M20.808 12.272c.34-.01.657-.126.916-.312v.943a2.2 2.2 0 0 1-1.358 2.044q.26-.552.35-1.195z");
}

.gt-y46nru {
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gyulks50m {
  stop-color: var(--svg-color--9e2625, #9E2625);
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h3e5alaje {
  stop-color: var(--svg-color--c03005, #C03005);
}

.h65uoi6pi {
  stop-color: var(--svg-color--d63c26, #D63C26);
}

.he3r7fbsu {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.43 7.878a2.8 2.8 0 0 1 1.761-.364a.281.281 0 0 1-.068.558a2.25 2.25 0 0 0-1.404.288a1 1 0 0 0-.093.06l-.003.003a.28.28 0 0 1-.344-.444z");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hrqpq4_5o {
  cx: 13.4px;
  cy: 9.981px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.hw19_ybat {
  stop-color: var(--svg-color--e04438, #E04438);
  stop-opacity: 0;
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.hz9o0k8yr {
  d: path("m16.12 5.319l-.067-.139a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.423v.278c-.344-.262-.777-.814-.777-1.709c0-1.086.792-1.634 1.297-1.984c.142-.1.262-.182.335-.257l.1-.106c.354-.375.985-1.044 2.087-1.337a5.5 5.5 0 0 1 1.537-.167c.473.013.806.42.806.894v1.514z");
}

.i8o1iacxv {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.306 9.32c.662 0 1.22.456 1.372 1.072a.278.278 0 0 1-.27.345h-2.26a.233.233 0 0 1-.23-.275a1.416 1.416 0 0 1 1.388-1.142");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.iksuiqrgf {
  cx: 8.275px;
  cy: 23.368px;
  r: 6.305px;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j67khjb2r {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.783 9.793a.968.968 0 0 0 .084 1.904a79 79 0 0 1-.084-1.904");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jne7u7bpd {
  d: path("M18.03 9.786c.064.086-.07.191-.223.306s-.267.195-.331.109c-.065-.087.007-.25.16-.364s.33-.137.394-.05");
}

.k-y64ibbx {
  stop-color: var(--svg-color--99201f, #99201F);
}

.k3qin7bzy {
  stop-color: var(--svg-color--b22307, #B22307);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kqw3-db6l {
  stop-color: var(--svg-color--dea48a, #DEA48A);
}

.ktoycacxm {
  stop-color: var(--svg-color--f6682e, #F6682E);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.l9w39y8hl {
  d: path("M20.801 4.278c.521.18.989.544 1.284 1.065a2.4 2.4 0 0 1-.107 2.559a1.6 1.6 0 0 0-.274.885V9.99a1.8 1.8 0 0 0-.676-.271l.08-1.627a1.47 1.47 0 0 0-1.397-1.45h-1.418a2.45 2.45 0 0 1-2.24-1.462a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.423l.031 1.557a1.7 1.7 0 0 0-.73.267V8.787a1.6 1.6 0 0 0-.273-.885a2.42 2.42 0 0 1-.145-2.477a2.37 2.37 0 0 1 1.316-1.141a2.7 2.7 0 0 0 1.402-1.125a2.355 2.355 0 0 1 2.928-.923a1.5 1.5 0 0 0 1.208 0c.285-.12.597-.19.924-.19c.854 0 1.6.461 2.015 1.146c.311.516.8.89 1.37 1.086");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lr6p412xr {
  fill: var(--svg-color--ed561d, #ED561D);
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m-ngl022d {
  d: path("m21.164 8.734l-.03-.64c-.01-.772-.65-1.41-1.423-1.443h-1.418c-.9 0-1.721-.492-2.151-1.276c0 0-.063-.146-.127-.394c-.251-.971.675-1.713 1.66-1.524c.991.19 2.125.524 2.962 1.07c1.766 1.152 1.457 3.229.527 4.207");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m8q5t-o2a {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.468 8.161c.26-.186.909-.515 1.676-.386");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mnloc2nlg {
  stop-color: var(--svg-color--e6ae8a, #E6AE8A);
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mz-slk5ug {
  d: path("M10.766 9.124a1.63 1.63 0 0 0 .14 3.24a79 79 0 0 1-.14-3.24");
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n5l_opbqq {
  r: 6.305px;
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.npfrbd3jd {
  stop-color: var(--svg-color--dd3537, #DD3537);
}

.nxgp0pbvn {
  stop-color: var(--svg-color--e2aa93, #E2AA93);
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.o63xdtqyc {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.665 7.988a1.9 1.9 0 0 0-.696-.416c-.308-.097-.694-.123-1.228-.058a.281.281 0 0 0 .068.558c.488-.06.786-.029.991.036c.201.063.337.165.496.304a.28.28 0 0 0 .37-.424");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofax10bwa {
  d: path("M20.87 12.364q.1-1.616.186-3.232a1.63 1.63 0 0 1-.187 3.232");
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oiscfh1gb {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.491 8.114c-.26-.186-.91-.515-1.676-.386");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.p5jt_ib0l {
  stop-color: var(--svg-color--e04438, #E04438);
}

.pbkzvtx_w {
  stop-color: var(--svg-color--e06d3d, #E06D3D);
}

.pc5jlhn5w {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.91 11.705q.059-.964.112-1.928a.968.968 0 0 1-.112 1.928");
}

.pjzr3aclu {
  stop-color: var(--svg-color--d03d1c, #D03D1C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn5dqxymu {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.448 10.666l-.7 1.677c-.103.383.143.765.492.765h.744c.35 0 .596-.388.493-.765l-.503-1.862c-.108-.413-.413-.228-.526.185");
}

.ps_f7cbop {
  stop-color: var(--svg-color--ab5e45, #AB5E45);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qc1uy5bzw {
  stop-color: var(--svg-color--e2aa93, #E2AA93);
  stop-opacity: 0;
}

.qdnqv10ox {
  d: path("M13.673 9.595a.904.904 0 0 0-.872 1.142h1.747a1 1 0 0 0 .033-.238a.91.91 0 0 0-.909-.904");
}

.qnar36wle {
  r: 4.086px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz-t25gyz {
  stop-color: var(--svg-color--b36e91, #B36E91);
}

.r_bcr-ntk {
  cx: 10.674px;
  cy: 16.165px;
  r: 4.086px;
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.rgs-6fbpw {
  d: path("M5.096 29.939c0-7.961 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rl6zs7yhb {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.463 9.32c-.662 0-1.22.456-1.372 1.072a.278.278 0 0 0 .27.345h2.26a.233.233 0 0 0 .23-.275a1.42 1.42 0 0 0-1.388-1.142");
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rt8f9chvu {
  fill: var(--svg-color--000, #000);
  d: path("M17.579 10.5c0-.289.23-.519.517-.519a.516.516 0 0 1 .46.756h-.916a.47.47 0 0 1-.061-.238");
}

.s6ufut5ul {
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tgex-ob-h {
  d: path("m15.497 10.283l-.538 1.861c-.11.383.154.766.527.766h.796c.374 0 .638-.389.528-.766l-.538-1.861c-.116-.413-.654-.413-.775 0");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u4bo2-o9a {
  stop-color: var(--svg-color--d84f1a, #D84F1A);
  stop-opacity: 0;
}

.ue2ywxbfs {
  stop-color: var(--svg-color--e45c36, #E45C36);
  stop-opacity: 0;
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.ujd1vybxb {
  stroke: var(--svg-color--e7b39a, #E7B39A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.152 18.338c.19.027.71.032 1.275-.163");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uny96bcfc {
  d: path("M14.498 10.393c0-.292-.237-.487-.302-.546l-.292.283l.18.366z");
}

.up5p4s41k {
  stop-color: var(--svg-color--e64812, #E64812);
  stop-opacity: 0;
}

.uwipchbui {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.03 9.786c.064.086-.07.191-.223.306s-.267.195-.331.109c-.065-.087.007-.25.16-.364s.33-.137.394-.05");
}

.uygoe8bue {
  d: path("M14.01 16.517h4v.887c.01.175.045.374.152.53a.8.8 0 0 0 .445.333l.465.164c.076.068.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.02l-.005-.01q0 .004-.004.01v-.02c-1.052-2.51-3.186-7.515-3.366-8.02c-.182-.506-.076-.87 0-.937l.68-.192c.218-.062.373-.14.515-.347c.113-.166.158-.39.172-.572z");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w_5-rbc1a {
  stop-color: var(--svg-color--dd3537, #DD3537);
  stop-opacity: 0;
}

.w8e9izb-y {
  d: path("M26.947 29.939c0-7.961-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wkmk90b2p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 24.017h3.298a5.94 5.94 0 0 1 5.937 5.937H1.971zm28.06 0h-3.298a5.94 5.94 0 0 0-5.937 5.937h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x3axlob0n {
  stop-color: var(--svg-color--e24c14, #E24C14);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y299lcb5j {
  d: path("M15.885 13.94c-.514 0-.998-.121-1.404-.333c-.138-.07-.287.086-.2.212c.34.514.93.857 1.604.857c.673 0 1.264-.343 1.603-.857c.088-.131-.061-.282-.2-.212a3 3 0 0 1-1.403.333");
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.yf3t3eb5f {
  stop-color: var(--svg-color--ff8244, #FF8244);
}

.ykdcls_lk {
  stop-color: var(--svg-color--dd3d3d, #DD3D3D);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z2ddyab4m {
  stop-color: var(--svg-color--f47246, #F47246);
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zyxtmxbvw {
  d: path("M10.96 12.272a1.66 1.66 0 0 1-.915-.312v.943a2.2 2.2 0 0 0 1.358 2.044a4.1 4.1 0 0 1-.35-1.195z");
}

</style>
