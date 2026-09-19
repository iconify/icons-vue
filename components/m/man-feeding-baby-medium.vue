<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idhdsEd)" class="e51eb6qzh"/><path fill="url(#iYkbLie)" class="e51eb6qzh"/><path fill="url(#ivVaRcd)" class="dtudatb7d"/><g filter="url(#i0wlvjd)"><circle fill="url(#i5X7Tpe)" transform="rotate(-10.728 10.137 12.066)" class="iru0tbbju"/></g><circle fill="url(#iXn50HR)" transform="rotate(-10.728 10.137 12.066)" class="iru0tbbju"/><g filter="url(#iDZLMmd)"><circle fill="url(#i1DVNLc)" transform="rotate(-10.728 10.137 12.066)" class="wim31z7yq"/></g><g filter="url(#ivfm56b)"><circle fill="url(#iSMXire)" transform="rotate(-10.728 19.484 10.295)" class="fma061b8e"/><circle fill="url(#iu97zLZ)" transform="rotate(-10.728 19.484 10.295)" class="fma061b8e"/></g><g filter="url(#i2r9CNd)"><circle transform="rotate(-10.728 19.484 10.295)" class="h_bxsubqd"/><circle fill="url(#iJL0yPJ)" transform="rotate(-10.728 19.484 10.295)" class="f9f3jjb-s"/><circle fill="url(#iP8EKub)" transform="rotate(-10.728 19.484 10.295)" class="f9f3jjb-s"/></g><g filter="url(#ixoT9Rc)"><path fill="url(#ixkKEzc)" class="a88h5w2vu"/></g><path fill="url(#i69vLtc)" class="v17f562it"/><path fill="url(#igJyDhz)" class="v17f562it"/><path fill="url(#iOCEnrc)" class="v17f562it"/><path fill="url(#iOoCjWb)" class="v17f562it"/><g filter="url(#ipBeB4d)"><path fill="url(#itYShGb)" class="sgrbhr_bq"/></g><g filter="url(#iEQfKrE)"><path class="mfcdzgb4q"/><path fill="url(#i0LTIGd)" class="jolg9_bkv"/><path fill="url(#iTxytxe)" class="jolg9_bkv"/><path fill="url(#ipIEoMb)" class="jolg9_bkv"/><path fill="url(#iABlgAA)" class="jolg9_bkv"/></g><g filter="url(#iyobnto)"><path class="t5b4e7bmk"/></g><g filter="url(#i8Zab0c)"><path class="az9s3iblk"/><path fill="url(#ivqIndb)" class="for3btbgg"/><path fill="url(#i24OAGc)" class="for3btbgg"/><path fill="url(#iuTgFWc)" class="for3btbgg"/><path fill="url(#iiHPwne)" class="for3btbgg"/></g><path stroke="url(#ifbVUoc)" class="kccq35knn"/><g filter="url(#ijIoGFd)"><path stroke="url(#ibKIrbd)" class="x6zzk8bpa"/></g><g filter="url(#iPdXyXd)"><circle fill="url(#i5NoJ7r)" class="ovlo7obkk"/></g><g filter="url(#imiFWUX)"><circle fill="url(#ix9iZyc)" class="k_7jpkz4l"/></g><path fill="url(#iEBBqcc)" class="b8rb0zbvs"/><path fill="url(#isU58Yc)" class="b5xjt6rtn"/><g filter="url(#idA8rdc)"><path stroke="url(#i5oi7vc)" class="til6_4oea"/><path stroke="url(#irHbkpb)" class="til6_4oea"/></g><g filter="url(#iuQsbMb)"><path stroke="url(#iBO9GvS)" class="jixboebdn"/><path stroke="url(#ig11XEb)" class="jixboebdn"/></g><path class="cwvt06b3m"/><path fill="url(#iL9Nf2d)" class="uk34k6bil"/><path fill="url(#i91MaRE)" class="uk34k6bil"/><path fill="url(#iQuvdlb)" class="uk34k6bil"/><path fill="url(#iaytNec)" class="uk34k6bil"/><path fill="url(#iwtaVUu)" class="uk34k6bil"/><path fill="url(#ie2ZFpe)" class="uk34k6bil"/><path fill="url(#ixricsd)" class="uk34k6bil"/><g filter="url(#i69dYee)"><path fill="url(#iedMseH)" class="kjgiqjnlu"/><path fill="url(#ij15hLe)" class="kjgiqjnlu"/><path fill="url(#iDNZMEe)" class="kjgiqjnlu"/></g><path fill="url(#ipw5Sdw)" class="zkvq0m5wd"/><g filter="url(#iU3E0Pc)"><path fill="url(#i3Yofob)" class="vyqsbmsyn"/><path fill="url(#ijzWyNc)" class="vyqsbmsyn"/></g><g filter="url(#ipaYced)"><path class="v9mdoebvs"/><path fill="url(#izX5xEc)" class="nhmfgyb6x"/><path fill="url(#iPIV1Ld)" class="nhmfgyb6x"/><path fill="url(#i72GhBb)" class="nhmfgyb6x"/><path fill="url(#iM4S7Zb)" class="nhmfgyb6x"/></g><path fill="url(#ijxAh2b)" class="yjz1ee62l"/><path fill="url(#iSIPNJb)" class="yjz1ee62l"/><path fill="url(#inj5b6d)" class="wei-v7l1n"/><path fill="url(#iXhfffc)" class="wei-v7l1n"/><path fill="url(#iLfxpzb)" class="hjgvw704i"/><path fill="url(#iR3luzD)" class="hjgvw704i"/><path fill="url(#iViMgbb)" class="hjgvw704i"/><path fill="url(#ixOti7c)" class="ay43mzb3j"/><path fill="url(#iQe9TIe)" class="zd0icacwz"/><path fill="url(#ijBHPbe)" class="e8q57tdwp"/><path fill="url(#i5WEx5c)" class="e8q57tdwp"/><path fill="url(#i3nbNJc)" class="e8q57tdwp"/><g filter="url(#iNxV9jc)"><path stroke="url(#ic5m6Jd)" class="iptxl7erp"/></g><path fill="url(#irsoSFd)" class="vxoft6bnf"/><path fill="url(#i4rbk0c)" class="vxoft6bnf"/><path fill="url(#iJYtZiT)" class="dzgmndnzj"/><g filter="url(#iAXEHuh)"><path fill="url(#iKu94Cd)" class="q2xxmqg3l"/><path fill="url(#ixUp2qd)" class="q2xxmqg3l"/><path fill="url(#iUnPaAv)" class="q2xxmqg3l"/></g><path fill="url(#iLl4K2c)" class="eoakhf8zk"/><path fill="url(#i1nzvqe)" class="eoakhf8zk"/><path fill="url(#iEBqBxb)" class="eoakhf8zk"/><path fill="url(#iD6FfDP)" class="eoakhf8zk"/><path class="l8xde2evc"/><path fill="url(#iVM0txc)" class="khc9l3o8l"/><path fill="url(#idof3nd)" class="khc9l3o8l"/><path class="mrinjyb1n"/><path fill="url(#ibAfnnd)" class="m4rdexttc"/><path fill="url(#ioNPm4b)" class="m4rdexttc"/><path fill="url(#i1tHvAS)" class="m4rdexttc"/><path fill="url(#iDQTvrd)" class="apljh2pna"/><path fill="url(#ieoMMmd)" class="apljh2pna"/><path fill="url(#iKueQ0c)" class="apljh2pna"/><path fill="url(#iGQTDHb)" class="apljh2pna"/><path fill="url(#iDIENAb)" class="p6x9rgwlv"/><path fill="url(#iARYyCc)" class="p6x9rgwlv"/><path fill="url(#iS0DBrd)" class="p6x9rgwlv"/><path fill="url(#izjqFTl)" class="p6x9rgwlv"/><path fill="url(#ixoBZnb)" class="p6x9rgwlv"/><path fill="url(#iIDnPEb)" class="l6ho0nlqb"/><path fill="url(#i9tb3bb)" class="l6ho0nlqb"/><path fill="url(#icyhOoe)" class="l6ho0nlqb"/><path fill="url(#iBS0iNU)" class="l6ho0nlqb"/><g filter="url(#iw1E4Nd)"><path stroke="url(#iUyg6gb)" class="ovpcbfu_s"/></g><g filter="url(#iiIS5bb)" class="mc2zb0bvp"><path class="vm_fbm43o"/></g><g filter="url(#ivFwx7p)" class="mc2zb0bvp"><path class="qfv_ricti"/></g><g filter="url(#iwjOboL)"><path class="l_kpycb-m"/><path fill="url(#icYiIrD)" class="op_kowm7h"/></g><g filter="url(#idxUaOd)"><path class="srzdpleqn"/><path fill="url(#i0C6Rsc)" class="twftfj8ae"/></g><g filter="url(#iVb5yEd)"><path stroke="url(#i6eUkPd)" class="wzpmqq7rw"/></g><g filter="url(#i9VdhLd)"><path stroke="url(#iMUua1d)" class="cmp53oboj"/></g><defs><radialGradient id="iYkbLie" cx="0" cy="0" r="1" gradientTransform="rotate(63.107 -6.079 21.723)scale(2.97834 5.11643)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="hb881329x"/><stop offset="1" class="ma7f6291s"/></radialGradient><radialGradient id="i5X7Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 8.468 12.066)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iXn50HR" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.645 4.228)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iu97zLZ" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 19.856 10.03)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iJL0yPJ" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.442 11.116)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iP8EKub" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.776 28.837)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="ixkKEzc" cx="0" cy="0" r="1" gradientTransform="rotate(166.757 8.914 6.892)scale(7.82967 12.2916)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="zqkd_uy_g"/><stop offset="1" class="s9ppkbwdl"/></radialGradient><radialGradient id="iOCEnrc" cx="0" cy="0" r="1" gradientTransform="rotate(104.459 4.137 11.389)scale(7.74685 16.5756)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="ffy2btltn"/><stop offset="1" class="enevnvbxl"/></radialGradient><radialGradient id="i0LTIGd" cx="0" cy="0" r="1" gradientTransform="matrix(.23348 -3.0532 1.13222 .08658 18.306 6.34)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iTxytxe" cx="0" cy="0" r="1" gradientTransform="rotate(-5.47 59.638 -168.818)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="ipIEoMb" cx="0" cy="0" r="1" gradientTransform="matrix(.31255 1.64968 -2.5549 .48405 13.201 2.733)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iABlgAA" cx="0" cy="0" r="1" gradientTransform="rotate(-46.963 16.303 -4.047)scale(3.81067 5.97006)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iiHPwne" cx="0" cy="0" r="1" gradientTransform="rotate(79.272 .045 15.659)scale(.19688 .63255)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="i5NoJ7r" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.237 -4.51)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="za84p3bvp"/><stop offset=".876" class="ce24i9mgs"/></radialGradient><radialGradient id="ix9iZyc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.932 -8.646)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l9fq7mbnb"/><stop offset=".535" class="lsc-rb3tr"/></radialGradient><radialGradient id="iEBBqcc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .3557 2.1855 11.307 11.594)" gradientUnits="userSpaceOnUse"><stop class="c60wuxbym"/><stop offset="1" class="u0tz8ubiy"/></radialGradient><radialGradient id="isU58Yc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 15.937 10.784)" gradientUnits="userSpaceOnUse"><stop class="c60wuxbym"/><stop offset="1" class="u0tz8ubiy"/></radialGradient><radialGradient id="irHbkpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.479 11.229)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="f34_pj_2t"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="x-g1cc54o"/></radialGradient><radialGradient id="ig11XEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.109 10.42)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="f34_pj_2t"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="x-g1cc54o"/></radialGradient><radialGradient id="iQuvdlb" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 .78125 -.62684 2.50735 8.236 21.381)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="wla505bqs"/><stop offset="1" class="rvju2rlnj"/></radialGradient><radialGradient id="iaytNec" cx="0" cy="0" r="1" gradientTransform="rotate(129.369 -1.274 11.582)scale(2.35689 2.29948)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="eb47hsvqu"/><stop offset="1" class="jqpapdb1m"/></radialGradient><radialGradient id="iwtaVUu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 2.01874 -6.68469 8.598 30.44)" gradientUnits="userSpaceOnUse"><stop class="hk7wqt7lq"/><stop offset="1" class="g3kr4nmzl"/></radialGradient><radialGradient id="ixricsd" cx="0" cy="0" r="1" gradientTransform="matrix(1.82811 2.45314 -3.10932 2.3171 8.845 21.381)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t1ofhibdm"/><stop offset="1" class="imlvuhvwp"/></radialGradient><radialGradient id="iedMseH" cx="0" cy="0" r="1" gradientTransform="rotate(109.107 -.509 18.64)scale(6.34981 4.72781)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="ij15hLe" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.957 10.365)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iDNZMEe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 26.159)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="ipw5Sdw" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.271 23.27)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="i3Yofob" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.03 12.942)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="ijzWyNc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.94)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="izX5xEc" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.554 40.652)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="mu_dstxav"/><stop offset="1" class="vr5bp_bxf"/></radialGradient><radialGradient id="iPIV1Ld" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 30.44)" gradientUnits="userSpaceOnUse"><stop class="vc2ezub_b"/><stop offset="1" class="pdof6qbxo"/></radialGradient><radialGradient id="iM4S7Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.265 29.377)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="h5yda4bml"/><stop offset="1" class="xmthgnb3w"/></radialGradient><radialGradient id="ijxAh2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.70313 -.62842 0 19.627 28.63)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="hdo03nb1p"/><stop offset="1" class="b26wppbkf"/></radialGradient><radialGradient id="iXhfffc" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.81 14.975)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="s231-6bjz"/><stop offset="1" class="s6qjzwjgb"/></radialGradient><radialGradient id="iLfxpzb" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.765 20.314)" gradientUnits="userSpaceOnUse"><stop class="ol95frboa"/><stop offset="1" class="i5qbulbys"/></radialGradient><radialGradient id="iR3luzD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.287)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="py7fiqzvo"/><stop offset="1" class="rkoscyb2g"/></radialGradient><radialGradient id="iViMgbb" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.925)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yassptbsb"/><stop offset="1" class="g6isq_a6x"/></radialGradient><radialGradient id="i3nbNJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.916)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="ic5m6Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.456)" gradientUnits="userSpaceOnUse"><stop class="rihdlqb3v"/><stop offset="1" class="x7yh0i-6p"/></radialGradient><radialGradient id="i4rbk0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.256)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="ixUp2qd" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.62 34.475)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="i1nzvqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 18.902)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="i9r9kkbqw"/><stop offset="1" class="e16i7e3de"/></radialGradient><radialGradient id="iEBqBxb" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.177 11.948)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="e7zd_qbyg"/><stop offset="1" class="sv2l0pbpa"/></radialGradient><radialGradient id="iD6FfDP" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16051 9.01 21.08)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="b1nef-bor"/><stop offset="1" class="jcycylcex"/></radialGradient><radialGradient id="iVM0txc" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 17.965)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="lp7kx4bze"/><stop offset="1" class="hbjsfnbqm"/></radialGradient><radialGradient id="idof3nd" cx="0" cy="0" r="1" gradientTransform="matrix(.82031 .17968 -.24565 1.1215 9.814 16.55)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="jwxh3bbfb"/><stop offset="1" class="r6a-j5bnt"/></radialGradient><radialGradient id="ibAfnnd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.474 2.505)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="kyubtxb-o"/><stop offset="1" class="a0y-a0b2f"/></radialGradient><radialGradient id="ioNPm4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.815 17.962)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="vhb97r3hm"/><stop offset="1" class="m9i-5tkbo"/></radialGradient><radialGradient id="i1tHvAS" cx="0" cy="0" r="1" gradientTransform="matrix(.61328 .25 -.50554 1.24016 9.53 17.41)" gradientUnits="userSpaceOnUse"><stop class="xaxho9f-m"/><stop offset="1" class="g_ars-u5d"/></radialGradient><radialGradient id="iDQTvrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.143 19.214)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="bkr4sabrv"/><stop offset="1" class="vy_5_bh0s"/></radialGradient><radialGradient id="ieoMMmd" cx="0" cy="0" r="1" gradientTransform="matrix(1.85937 1.375 -.35309 .47747 11.69 19.464)" gradientUnits="userSpaceOnUse"><stop class="or_kejb-o"/><stop offset="1" class="a-of3kbjs"/></radialGradient><radialGradient id="iKueQ0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.062 19.237)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="eh5j-nbpx"/><stop offset="1" class="ih66ipb5v"/></radialGradient><radialGradient id="iGQTDHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0304 -.54867 .96509 1.81241 8.94 19.292)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="esfed8bwd"/><stop offset="1" class="n24z6jbtl"/></radialGradient><radialGradient id="iDIENAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.869 21.91)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="wi_pdjbvv"/><stop offset="1" class="g5ydalx2k"/></radialGradient><radialGradient id="iARYyCc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.767 20.464)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="y2mfwqgbt"/><stop offset="1" class="wo3blnxxa"/></radialGradient><radialGradient id="iS0DBrd" cx="0" cy="0" r="1" gradientTransform="rotate(102.218 -3.136 14.322)scale(2.03036 4.87917)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d-e4mcb8q"/><stop offset=".962" class="cts2nkbix"/></radialGradient><radialGradient id="izjqFTl" cx="0" cy="0" r="1" gradientTransform="matrix(.61483 -.19518 .6509 2.0503 7.801 20.934)" gradientUnits="userSpaceOnUse"><stop class="l_gp-_bkz"/><stop offset="1" class="j9v-nnbxs"/></radialGradient><radialGradient id="ixoBZnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 -1.92189 3.39221 -2.75786 9.83 22.01)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="u_sc2wgtl"/><stop offset="1" class="iwejj4bye"/></radialGradient><radialGradient id="i9tb3bb" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .865 16.019)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="icyhOoe" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .746 16.494)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iBS0iNU" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.344 10.511)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iUyg6gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.256)" gradientUnits="userSpaceOnUse"><stop class="zxch6_gap"/><stop offset="1" class="upwmevb9h"/></radialGradient><radialGradient id="icYiIrD" cx="0" cy="0" r="1" gradientTransform="rotate(-90.929 12.677 -3.932)scale(.61215 1.81098)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i0C6Rsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00991 -.61207 1.81085 -.02933 11.757 9.638)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><linearGradient id="idhdsEd" x1="19.224" x2="12.336" y1="19.045" y2="30.722" gradientUnits="userSpaceOnUse"><stop class="hvtvasx8l"/><stop offset="1" class="sdatcx1hi"/></linearGradient><linearGradient id="ivVaRcd" x1="15.685" x2="17.218" y1="17.675" y2="18.659" gradientUnits="userSpaceOnUse"><stop offset=".177" class="knaq39gfo"/><stop offset="1" class="rg1hkl93k"/></linearGradient><linearGradient id="i1DVNLc" x1="10.137" x2="9.497" y1="12.344" y2="12.344" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iSMXire" x1="20.57" x2="19.751" y1="9.204" y2="11.74" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="i69vLtc" x1="10.075" x2="11.911" y1="15.217" y2="14.801" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="igJyDhz" x1="20.054" x2="18.943" y1="12.47" y2="12.582" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iOoCjWb" x1="16.217" x2="16.029" y1="17.76" y2="16.885" gradientUnits="userSpaceOnUse"><stop class="a_pg3k-gs"/><stop offset="1" class="y5do4obbu"/></linearGradient><linearGradient id="itYShGb" x1="13.797" x2="21.255" y1="8.731" y2="4.351" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="ivqIndb" x1="14.148" x2="15.07" y1="12.373" y2="12.198" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="i24OAGc" x1="15.979" x2="14.969" y1="12.354" y2="12.531" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iuTgFWc" x1="15.386" x2="15.28" y1="13.222" y2="12.659" gradientUnits="userSpaceOnUse"><stop class="gqla_qb6z"/><stop offset="1" class="sfnao1bat"/></linearGradient><linearGradient id="ifbVUoc" x1="14.477" x2="14.776" y1="15.039" y2="14.282" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ibKIrbd" x1="9.308" x2="9.709" y1="7.227" y2="9.346" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><linearGradient id="i5oi7vc" x1="11.4" x2="13.682" y1="11.636" y2="11.791" gradientUnits="userSpaceOnUse"><stop class="qfjvbh23z"/><stop offset="1" class="xpe1rlbew"/></linearGradient><linearGradient id="iBO9GvS" x1="16.031" x2="18.312" y1="10.828" y2="10.983" gradientUnits="userSpaceOnUse"><stop class="qfjvbh23z"/><stop offset="1" class="xpe1rlbew"/></linearGradient><linearGradient id="iL9Nf2d" x1="9.109" x2="3.64" y1="26.753" y2="25.284" gradientUnits="userSpaceOnUse"><stop class="ena81bblx"/><stop offset="1" class="hjax-mb0n"/></linearGradient><linearGradient id="i91MaRE" x1="3.515" x2="5.486" y1="26.378" y2="26.944" gradientUnits="userSpaceOnUse"><stop class="eyx6dtigb"/><stop offset="1" class="uels9hbwx"/></linearGradient><linearGradient id="ie2ZFpe" x1="9.229" x2="8.837" y1="28.771" y2="28.646" gradientUnits="userSpaceOnUse"><stop class="hkmz0xbqe"/><stop offset="1" class="s03vqlghs"/></linearGradient><linearGradient id="i72GhBb" x1="18.227" x2="17.566" y1="26.715" y2="27.61" gradientUnits="userSpaceOnUse"><stop offset=".175" class="d9x2ylwjm"/><stop offset="1" class="ow_pc7b8u"/></linearGradient><linearGradient id="iSIPNJb" x1="19.523" x2="19.437" y1="27.003" y2="27.511" gradientUnits="userSpaceOnUse"><stop class="byw39cbfh"/><stop offset="1" class="uvoxmwj8v"/></linearGradient><linearGradient id="inj5b6d" x1="26.546" x2="26.984" y1="27.221" y2="30.94" gradientUnits="userSpaceOnUse"><stop class="gf4r80b0w"/><stop offset="1" class="jd4hd8b4a"/></linearGradient><linearGradient id="ixOti7c" x1="11.144" x2="10.997" y1="22.513" y2="19.87" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iQe9TIe" x1="12.351" x2="11.964" y1="20.704" y2="18.722" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="ijBHPbe" x1="16.078" x2="15.296" y1="18.503" y2="21.489" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="i5WEx5c" x1="15.205" x2="15.428" y1="21.709" y2="20.818" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="irsoSFd" x1="14.952" x2="13.827" y1="17.738" y2="22.066" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="iJYtZiT" x1="15.265" x2="14.156" y1="18.112" y2="17.753" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iKu94Cd" x1="14.453" x2="13.223" y1="17.628" y2="22.378" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iUnPaAv" x1="12.549" x2="12.768" y1="21.444" y2="20.365" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iLl4K2c" x1="8.421" x2="8.964" y1="17.128" y2="21.628" gradientUnits="userSpaceOnUse"><stop class="a79moebrw"/><stop offset="1" class="hkuv0zb-z"/></linearGradient><linearGradient id="iIDnPEb" x1="16.521" x2="15.937" y1="19.003" y2="21.503" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="i6eUkPd" x1="17.201" x2="16.628" y1="7.953" y2="7.188" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iMUua1d" x1="11.972" x2="10.71" y1="8.771" y2="8.503" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><filter id="i0wlvjd" width="3.539" height="3.339" x="8.468" y="10.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="iDZLMmd" width="2.99" height="2.99" x="8.642" y="10.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".25"/></filter><filter id="ivfm56b" width="3.589" height="3.589" x="17.814" y="8.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="i2r9CNd" width="2.99" height="2.99" x="17.989" y="8.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".25"/></filter><filter id="ixoT9Rc" width="10.872" height="12.657" x="9.334" y="5.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="ipBeB4d" width="8.307" height="7.542" x="12.28" y="2.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation="1"/></filter><filter id="iEQfKrE" width="12.443" height="9.546" x="7.747" y="1.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="iyobnto" width="3.248" height="4.243" x="13.266" y="10.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".375"/></filter><filter id="i8Zab0c" width="2.362" height="3.225" x="13.914" y="10.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".125"/></filter><filter id="ijIoGFd" width=".926" height="2.291" x="9.078" y="6.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".125"/></filter><filter id="iPdXyXd" width="3.987" height="3.987" x="10.4" y="8.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".325"/></filter><filter id="imiFWUX" width="3.987" height="3.987" x="14.989" y="7.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".325"/></filter><filter id="idA8rdc" width="2.323" height=".964" x="11.305" y="11.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".05"/></filter><filter id="iuQsbMb" width="2.323" height=".964" x="15.935" y="10.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".05"/></filter><filter id="i69dYee" width="11.192" height="8.359" x="11.466" y="22.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="iU3E0Pc" width="7.407" height="8.444" x="19.048" y="19.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="ipaYced" width="8.208" height="4.667" x="12.416" y="25.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.419608 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="iNxV9jc" width="3.456" height="1.701" x="7.381" y="22.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".1"/></filter><filter id="iAXEHuh" width="4.309" height="4.662" x="11.043" y="16.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="iw1E4Nd" width="3.647" height="2.753" x="6.263" y="19.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".05"/></filter><filter id="iiIS5bb" width="2.634" height="2.141" x="16.374" y="26.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".125"/></filter><filter id="ivFwx7p" width="4.536" height="1" x="12.746" y="29.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".15"/></filter><filter id="iwjOboL" width="3.02" height="1.668" x="15.454" y="7.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="idxUaOd" width="2.881" height="2.146" x="10.467" y="7.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3540"/></filter><filter id="iVb5yEd" width="3.141" height="1.458" x="15.269" y="7.315" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".25"/></filter><filter id="i9VdhLd" width="3.059" height="2.053" x="10.244" y="8.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3540" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-feeding-baby-medium" /></template>
<style>
.a_pg3k-gs {
  stop-color: var(--svg-color--685973, #685973);
}

.a-of3kbjs {
  stop-color: var(--svg-color--a87f6c, #A87F6C);
  stop-opacity: 0;
}

.a0y-a0b2f {
  stop-color: var(--svg-color--8d5c59, #8D5C59);
  stop-opacity: 0;
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a79moebrw {
  stop-color: var(--svg-color--8e705c, #8E705C);
}

.a88h5w2vu {
  d: path("m9.678 11.53l.048-.008s-.211-.829-.373-1.395c-.05-.262-.004-.597.177-.794l.128-.187c.224-.26.27-.594.21-.908L9.71 7.4a.52.52 0 0 1 .323-.604c.602-.277 1.87-.789 3.767-1.148c1.897-.36 3.264-.347 3.927-.31c.22.013.47.182.52.444l.16.839c.059.314.276.598.527.768c.559.252.564.448.6.863c.047.534.163 1.435.163 1.435l.018-.004l.475 3.939c.172 1.768-.965 3.239-2.595 3.548l-3.154.597c-1.682.319-3.226-.644-3.713-2.352z");
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.apljh2pna {
  d: path("M8.521 18.92a.28.28 0 0 1 .133-.269c.981-.69 2.005-.305 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.961.043 1.316c-.276.298-.751.241-.93.149l-2.097-1.313c-.055-.312-.235-.562-.48-.636c-.247-.075-.403-.133-.415-.328");
}

.ay43mzb3j {
  d: path("m11.845 21.04l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.az9s3iblk {
  fill: var(--svg-color--9e7764, #9E7764);
  d: path("m14.373 10.973l-.205 1.768a.54.54 0 0 0 .641.59l.773-.146a.54.54 0 0 0 .38-.784l-.838-1.57c-.181-.35-.703-.25-.75.142");
}

.b1nef-bor {
  stop-color: var(--svg-color--94596d, #94596D);
}

.b26wppbkf {
  stop-color: var(--svg-color--286ad9, #286AD9);
}

.b5xjt6rtn {
  d: path("M16.043 10.55c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.b8rb0zbvs {
  d: path("M11.413 11.36c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bkr4sabrv {
  stop-color: var(--svg-color--ac866d, #AC866D);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.byw39cbfh {
  stop-color: var(--svg-color--0e6996, #0E6996);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c60wuxbym {
  stop-color: var(--svg-color--3a1f28, #3A1F28);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.ce24i9mgs {
  stop-color: var(--svg-color--865a57, #865A57);
}

.cmp53oboj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.869 9.54c.267-.345.913-.777 1.809-.804");
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cts2nkbix {
  stop-color: var(--svg-color--935067, #935067);
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cwvt06b3m {
  fill: var(--svg-color--58b2ec, #58B2EC);
  d: path("m29.145 25.78l-4.94-6.05l-3.16 8.57z");
}

.d-e4mcb8q {
  stop-color: var(--svg-color--935067, #935067);
  stop-opacity: 0;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d9x2ylwjm {
  stop-color: var(--svg-color--b99477, #B99477);
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dtudatb7d {
  d: path("M15.685 18.97c1.06 0 1.91-.86 1.91-1.91V14.8a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dzgmndnzj {
  d: path("m14.826 17.538l-2.636-.734l-1.073 3.895l2.6.734c.408.11.755-.065.85-.394l.78-2.703c.123-.392-.164-.694-.521-.798");
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e16i7e3de {
  stop-color: var(--svg-color--6f3928, #6F3928);
}

.e51eb6qzh {
  d: path("M7.155 30.44c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e7zd_qbyg {
  stop-color: var(--svg-color--ab8870, #AB8870);
}

.e8q57tdwp {
  d: path("m15.53 18.306l.554.159a.15.15 0 0 1 .103.186l-.784 2.73a.15.15 0 0 1-.185.102l-.555-.16z");
}

.eb47hsvqu {
  stop-color: var(--svg-color--2170a2, #2170A2);
}

.eh5j-nbpx {
  stop-color: var(--svg-color--87624f, #87624F);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.ena81bblx {
  stop-color: var(--svg-color--2f71f9, #2F71F9);
}

.enevnvbxl {
  stop-color: var(--svg-color--765968, #765968);
}

.eoakhf8zk {
  d: path("M8.13 17.683c1.032-1.086 1.92-1.37 2.32-1.375l.798.867l-.93 3.515c-.18.316-.564.996-.695 1.153c-.164.195-.735.63-1.766.238c-.888-.337-1.15-.898-1.176-1.148c.234-1.168.65-2.358 1.45-3.25");
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.esfed8bwd {
  stop-color: var(--svg-color--947260, #947260);
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.eyx6dtigb {
  stop-color: var(--svg-color--4e83c4, #4E83C4);
}

.f34_pj_2t {
  stop-color: var(--svg-color--503a3b, #503A3B);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f9f3jjb-s {
  cx: 19.484px;
  cy: 10.295px;
  r: 0.995px;
}

.ffy2btltn {
  stop-color: var(--svg-color--856659, #856659);
  stop-opacity: 0;
}

.fma061b8e {
  cx: 19.484px;
  cy: 10.295px;
  r: 1.669px;
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.for3btbgg {
  d: path("m14.373 10.973l-.205 1.768a.54.54 0 0 0 .641.59l.773-.146a.54.54 0 0 0 .38-.784l-.838-1.57c-.181-.35-.703-.25-.75.142");
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g_ars-u5d {
  stop-color: var(--svg-color--997963, #997963);
  stop-opacity: 0;
}

.g3kr4nmzl {
  stop-color: var(--svg-color--317ff4, #317FF4);
  stop-opacity: 0;
}

.g5ydalx2k {
  stop-color: var(--svg-color--ba9374, #BA9374);
}

.g6isq_a6x {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
  stop-opacity: 0;
}

.gf4r80b0w {
  stop-color: var(--svg-color--27a9f1, #27A9F1);
}

.gqla_qb6z {
  stop-color: var(--svg-color--8a5e61, #8A5E61);
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.h_bxsubqd {
  cx: 19.484px;
  cy: 10.295px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.h5yda4bml {
  stop-color: var(--svg-color--814c4e, #814C4E);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hb881329x {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
}

.hbjsfnbqm {
  stop-color: var(--svg-color--936e63, #936E63);
  stop-opacity: 0;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hdo03nb1p {
  stop-color: var(--svg-color--2176c7, #2176C7);
}

.hjax-mb0n {
  stop-color: var(--svg-color--246bda, #246BDA);
}

.hjgvw704i {
  d: path("M10.214 22.127c-.284.88-1.448 1.292-2.6.92c-1.152-.371-1.793-1.177-1.573-2.265c.18-.889.883-1.75 2.738-1.24c1.153.371 1.719 1.705 1.435 2.585");
}

.hk7wqt7lq {
  stop-color: var(--svg-color--5289f2, #5289F2);
}

.hkmz0xbqe {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
}

.hkuv0zb-z {
  stop-color: var(--svg-color--8e685c, #8E685C);
}

.hvtvasx8l {
  stop-color: var(--svg-color--2ba6ec, #2BA6EC);
}

.i5qbulbys {
  stop-color: var(--svg-color--1f70cf, #1F70CF);
}

.i9r9kkbqw {
  stop-color: var(--svg-color--91576c, #91576C);
  stop-opacity: 0;
}

.ih66ipb5v {
  stop-color: var(--svg-color--87624f, #87624F);
  stop-opacity: 0;
}

.imlvuhvwp {
  stop-color: var(--svg-color--2e71f4, #2E71F4);
  stop-opacity: 0;
}

.iptxl7erp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.472c.579.14 1.92.172 2.657-.828");
}

.iru0tbbju {
  cx: 10.137px;
  cy: 12.066px;
  r: 1.669px;
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.iwejj4bye {
  stop-color: var(--svg-color--937160, #937160);
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.j9v-nnbxs {
  stop-color: var(--svg-color--8e655d, #8E655D);
  stop-opacity: 0;
}

.jcycylcex {
  stop-color: var(--svg-color--945c6f, #945C6F);
  stop-opacity: 0;
}

.jd4hd8b4a {
  stop-color: var(--svg-color--297eff, #297EFF);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jixboebdn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.085 10.82c.151.14.548.37 1.063.273c.562-.107.888-.459.96-.64");
}

.jolg9_bkv {
  d: path("m18.33 3.922l.462.13c.807.226 1.387.985 1.398 1.906l-.014 3.096c.007.318-.158.565-.462.63l-.018.004s-.116-.9-.163-1.435c-.038-.433-.137-.55-.6-.863c-.25-.17-.468-.454-.528-.769l-.159-.838c-.05-.262-.3-.432-.52-.444c-.663-.037-2.03-.05-3.927.31s-3.165.87-3.767 1.148a.52.52 0 0 0-.323.604l.16.838c.059.314.013.649-.21.908l-.13.187c-.18.197-.226.532-.176.794c.162.566.373 1.395.373 1.395l-.048.007a.63.63 0 0 1-.684-.412L7.85 8.242c-.264-.819-.002-1.737.667-2.244l.382-.29a8 8 0 0 0 .68-.725l.76-1.176c.481-.633 1.295-.95 2.102-.723a2.94 2.94 0 0 0 1.633-.31c.741-.412 1.677-.372 2.418.085l.94.636c.26.222.553.33.9.427");
}

.jqpapdb1m {
  stop-color: var(--svg-color--2374a5, #2374A5);
  stop-opacity: 0;
}

.jwxh3bbfb {
  stop-color: var(--svg-color--987763, #987763);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_7jpkz4l {
  cx: 16.983px;
  cy: 9.962px;
  r: 1.344px;
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.kccq35knn {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.977 14.145a.2.2 0 0 0-.23.086a.19.19 0 0 0 .024.239a1.94 1.94 0 0 0 1.758.55a1.94 1.94 0 0 0 1.434-1.155a.19.19 0 0 0-.065-.233a.2.2 0 0 0-.244.005a2.94 2.94 0 0 1-1.279.571c-.49.093-.973.065-1.398-.063Z");
}

.khc9l3o8l {
  d: path("M10.1 16.901c.355.125.48.331.515.454l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.025c-.586-.015-.793.434-.348.59");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kjgiqjnlu {
  d: path("M21.835 24.46c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.knaq39gfo {
  stop-color: var(--svg-color--70525f, #70525F);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.kyubtxb-o {
  stop-color: var(--svg-color--8d5c59, #8D5C59);
}

.l_gp-_bkz {
  stop-color: var(--svg-color--8e655d, #8E655D);
}

.l_kpycb-m {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m17.95 7.818l-.002-.001l-.002-.001l-.005-.003l-.013-.007a2 2 0 0 0-.172-.077a2.6 2.6 0 0 0-.452-.129a2.83 2.83 0 0 0-1.496.123a.534.534 0 1 0 .36 1.004c.379-.135.706-.123.935-.079a1.5 1.5 0 0 1 .325.101l.009.005a.534.534 0 0 0 .513-.936");
}

.l6ho0nlqb {
  d: path("m15.454 21.206l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.033l.315.084a.484.484 0 0 0 .253-.936l-.304-.082a.13.13 0 0 1-.097-.109l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.l8xde2evc {
  fill: var(--svg-color--a37e69, #A37E69);
  d: path("M10.1 16.901c.355.125.48.331.515.454l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.025c-.586-.015-.793.434-.348.59");
}

.l9fq7mbnb {
  stop-color: var(--svg-color--c29579, #C29579);
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lp7kx4bze {
  stop-color: var(--svg-color--936e63, #936E63);
}

.lsc-rb3tr {
  stop-color: var(--svg-color--ae806d, #AE806D);
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m4rdexttc {
  d: path("M9.67 17.823c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.m9i-5tkbo {
  stop-color: var(--svg-color--a6816a, #A6816A);
  stop-opacity: 0;
}

.ma7f6291s {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mfcdzgb4q {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m18.33 3.922l.462.13c.807.226 1.387.985 1.398 1.906l-.014 3.096c.007.318-.158.565-.462.63l-.018.004s-.116-.9-.163-1.435c-.038-.433-.137-.55-.6-.863c-.25-.17-.468-.454-.528-.769l-.159-.838c-.05-.262-.3-.432-.52-.444c-.663-.037-2.03-.05-3.927.31s-3.165.87-3.767 1.148a.52.52 0 0 0-.323.604l.16.838c.059.314.013.649-.21.908l-.13.187c-.18.197-.226.532-.176.794c.162.566.373 1.395.373 1.395l-.048.007a.63.63 0 0 1-.684-.412L7.85 8.242c-.264-.819-.002-1.737.667-2.244l.382-.29a8 8 0 0 0 .68-.725l.76-1.176c.481-.633 1.295-.95 2.102-.723a2.94 2.94 0 0 0 1.633-.31c.741-.412 1.677-.372 2.418.085l.94.636c.26.222.553.33.9.427");
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mrinjyb1n {
  fill: var(--svg-color--a8836a, #A8836A);
  d: path("M9.67 17.823c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.mu_dstxav {
  stop-color: var(--svg-color--905d66, #905D66);
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n24z6jbtl {
  stop-color: var(--svg-color--8f6d5d, #8F6D5D);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.nhmfgyb6x {
  d: path("M17.18 26.122a.937.937 0 0 0-1.12 1.498l.93.801a.1.1 0 0 1-.062.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.ol95frboa {
  stop-color: var(--svg-color--277aa9, #277AA9);
}

.op_kowm7h {
  d: path("m17.95 7.818l-.002-.001l-.002-.001l-.005-.003l-.013-.007a2 2 0 0 0-.172-.077a2.6 2.6 0 0 0-.452-.129a2.83 2.83 0 0 0-1.496.123a.534.534 0 1 0 .36 1.004c.379-.135.706-.123.935-.079a1.5 1.5 0 0 1 .325.101l.009.005a.534.534 0 0 0 .513-.936");
}

.or_kejb-o {
  stop-color: var(--svg-color--c29c8a, #C29C8A);
}

.ovlo7obkk {
  cx: 12.394px;
  cy: 10.69px;
  r: 1.344px;
}

.ovpcbfu_s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.19c-.206.433-.319 1.449.875 2.055s1.992.149 2.242-.156");
}

.ow_pc7b8u {
  stop-color: var(--svg-color--b99477, #B99477);
  stop-opacity: 0;
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p6x9rgwlv {
  d: path("M8.857 21.37c-.315.22-.723.21-.906-.11c-.392-.947.72-1.579 1.5-1.597c1.167-.027 1.75.629 1.937 1.121s.227 1.477-.672 1.54c-.804.055-.847-.5-.98-.743c-.133-.242-.594-.41-.88-.211");
}

.pdof6qbxo {
  stop-color: var(--svg-color--98567e, #98567E);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.py7fiqzvo {
  stop-color: var(--svg-color--052e6b, #052E6B);
}

.q2xxmqg3l {
  d: path("m12.167 16.905l2.635.735c.357.104.645.406.521.797l-.779 2.703c-.095.33-.442.505-.851.394l-2.6-.734z");
}

.qfjvbh23z {
  stop-color: var(--svg-color--513a3b, #513A3B);
}

.qfv_ricti {
  stroke: var(--svg-color--ba8c83, #BA8C83);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.536h3.536");
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r6a-j5bnt {
  stop-color: var(--svg-color--987763, #987763);
  stop-opacity: 0;
}

.rg1hkl93k {
  stop-color: var(--svg-color--9d867e, #9D867E);
}

.rihdlqb3v {
  stop-color: var(--svg-color--429ce6, #429CE6);
}

.rkoscyb2g {
  stop-color: var(--svg-color--124ea0, #124EA0);
  stop-opacity: 0;
}

.rvju2rlnj {
  stop-color: var(--svg-color--1972ba, #1972BA);
  stop-opacity: 0;
}

.s03vqlghs {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
  stop-opacity: 0;
}

.s231-6bjz {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
}

.s6qjzwjgb {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
  stop-opacity: 0;
}

.s9ppkbwdl {
  stop-color: var(--svg-color--876658, #876658);
}

.sdatcx1hi {
  stop-color: var(--svg-color--1577e2, #1577E2);
}

.sfnao1bat {
  stop-color: var(--svg-color--8a5e61, #8A5E61);
  stop-opacity: 0;
}

.sgrbhr_bq {
  d: path("m17.649 4.919l-2.832 1.58a1.047 1.047 0 0 0 .84 1.909l2.93-.972z");
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.srzdpleqn {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m10.588 9.213l.002-.003l.004-.004l.01-.012l.03-.033q.038-.04.102-.101c.086-.08.21-.183.373-.285a2.83 2.83 0 0 1 1.437-.434a.534.534 0 1 1 .033 1.067a1.77 1.77 0 0 0-.9.269a1.5 1.5 0 0 0-.265.212l-.006.008a.534.534 0 0 1-.82-.683");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.sv2l0pbpa {
  stop-color: var(--svg-color--8f715e, #8F715E);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t1ofhibdm {
  stop-color: var(--svg-color--3395d2, #3395D2);
}

.t5b4e7bmk {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m14.509 11.114l-.49 1.822c-.035.362.27.66.61.596l.724-.137c.34-.064.513-.459.35-.778l-.807-1.577c-.175-.35-.348-.317-.387.074");
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.til6_4oea {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.455 11.627c.151.14.548.37 1.063.273c.562-.106.888-.458.96-.64");
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.twftfj8ae {
  d: path("m10.588 9.213l.002-.003l.004-.004l.01-.012l.03-.033q.038-.04.102-.101c.086-.08.21-.183.373-.285a2.83 2.83 0 0 1 1.437-.434a.534.534 0 1 1 .033 1.067a1.77 1.77 0 0 0-.9.269a1.5 1.5 0 0 0-.265.212l-.006.008a.534.534 0 0 1-.82-.683");
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u_sc2wgtl {
  stop-color: var(--svg-color--937160, #937160);
  stop-opacity: 0;
}

.u0tz8ubiy {
  stop-color: var(--svg-color--3d2727, #3D2727);
}

.uels9hbwx {
  stop-color: var(--svg-color--5082c1, #5082C1);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.uk34k6bil {
  d: path("m2.201 30.44l2.93-9.156c.351-1.414 2.07-2.103 3.65-1.613s2.49 2.332 2.006 3.692L8.571 30.44z");
}

.upwmevb9h {
  stop-color: var(--svg-color--377dcb, #377DCB);
  stop-opacity: 0;
}

.uvoxmwj8v {
  stop-color: var(--svg-color--0e6996, #0E6996);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v17f562it {
  d: path("M9.353 10.127c-.05-.262-.004-.597.177-.794l.128-.187c.224-.26.27-.594.21-.908L9.71 7.4a.52.52 0 0 1 .323-.604c.602-.277 1.87-.789 3.767-1.148c1.897-.36 3.264-.347 3.927-.31c.22.013.47.182.52.444l.16.839c.059.314.276.598.527.768c.559.252.564.448.6.863c.047.534.163 1.435.163 1.435l.018-.004l.475 3.939c.172 1.768-.965 3.239-2.595 3.548l-3.154.597c-1.682.319-3.226-.644-3.713-2.352c-.475-1.76-.874-3.537-1.374-5.288");
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v9mdoebvs {
  fill: var(--svg-color--a77671, #A77671);
  d: path("M17.18 26.122a.937.937 0 0 0-1.12 1.498l.93.801a.1.1 0 0 1-.062.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.vc2ezub_b {
  stop-color: var(--svg-color--98567e, #98567E);
}

.vhb97r3hm {
  stop-color: var(--svg-color--c7a28d, #C7A28D);
}

.vm_fbm43o {
  stroke: var(--svg-color--c19885, #C19885);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.73l1.634 1.141");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vr5bp_bxf {
  stop-color: var(--svg-color--905d66, #905D66);
  stop-opacity: 0;
}

.vxoft6bnf {
  d: path("m11.939 16.475l3.172.884c.43.125.744.558.627.96l-.9 3.085c-.115.396-.532.607-1.024.474l-3.129-.883z");
}

.vy_5_bh0s {
  stop-color: var(--svg-color--966464, #966464);
}

.vyqsbmsyn {
  d: path("M21.575 24.38a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wei-v7l1n {
  d: path("M20.615 26.217c1.598-.23 4.567-.808 6.543-1.27c1.522-.262 2.64 1.204 2.64 2.782c0 1.371-1.022 2.236-1.746 2.618a.86.86 0 0 1-.403.093h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.wi_pdjbvv {
  stop-color: var(--svg-color--935b6e, #935B6E);
}

.wim31z7yq {
  cx: 10.137px;
  cy: 12.066px;
  r: 0.995px;
}

.wla505bqs {
  stop-color: var(--svg-color--1972ba, #1972BA);
}

.wo3blnxxa {
  stop-color: var(--svg-color--c7a08d, #C7A08D);
  stop-opacity: 0;
}

.wzpmqq7rw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.894 8.102c.409-.154 1.237-.289 1.891.047");
}

.x-g1cc54o {
  stop-color: var(--svg-color--503a3b, #503A3B);
  stop-opacity: 0;
}

.x6zzk8bpa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m9.453 7.3l.167.881c.02.148.02.486-.138.66");
}

.x7yh0i-6p {
  stop-color: var(--svg-color--429ce6, #429CE6);
  stop-opacity: 0;
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xaxho9f-m {
  stop-color: var(--svg-color--997963, #997963);
}

.xmthgnb3w {
  stop-color: var(--svg-color--814c4e, #814C4E);
  stop-opacity: 0;
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xpe1rlbew {
  stop-color: var(--svg-color--513a3b, #513A3B);
  stop-opacity: 0;
}

.y2mfwqgbt {
  stop-color: var(--svg-color--c7a08d, #C7A08D);
}

.y5do4obbu {
  stop-color: var(--svg-color--826365, #826365);
  stop-opacity: 0;
}

.yassptbsb {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
}

.yjz1ee62l {
  d: path("M18.998 27.223a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.za84p3bvp {
  stop-color: var(--svg-color--956f60, #956F60);
}

.zd0icacwz {
  d: path("M10.565 19.01c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.zkvq0m5wd {
  d: path("M23.695 27.57a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.zqkd_uy_g {
  stop-color: var(--svg-color--c4997d, #C4997D);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zxch6_gap {
  stop-color: var(--svg-color--377dcb, #377DCB);
}

</style>
