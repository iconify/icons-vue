<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iEmIkEb)" class="trnyvebve"/><path fill="url(#i3dBLoe)" class="trnyvebve"/><path fill="url(#iApeS9c)" class="ea6rlsbmk"/><path fill="url(#i0mfUMb)" class="ea6rlsbmk"/><path fill="url(#iJLr1eb)" class="ea6rlsbmk"/><path fill="url(#ir6TqBc)" class="ea6rlsbmk"/><path fill="url(#i4yIhuc)" class="f4g52x70m"/><path fill="url(#iGZHoxe)" class="f4g52x70m"/><path fill="url(#iMyTWsd)" class="f4g52x70m"/><path fill="url(#i5faMwc)" class="f4g52x70m"/><path fill="url(#inSZ5nb)" class="k1s5p0meo"/><path fill="url(#iMmPgee)" class="k1s5p0meo"/><path fill="url(#iABINwb)" class="k1s5p0meo"/><path fill="url(#iTPBf6y)" class="k1s5p0meo"/><path fill="url(#i159Cib)" class="mqyc56bzr"/><path fill="url(#iu87lzb)" class="mqyc56bzr"/><path fill="url(#iqyyBTb)" class="mqyc56bzr"/><circle class="njefkxbrx"/><circle fill="url(#iZFvrcd)" class="eb2k4iasx"/><circle class="b5z7mkyzl"/><g filter="url(#i3du35c)"><circle stroke="url(#ifxvBQd)" class="stqou83fh"/></g><g filter="url(#iq1gxLc)"><circle class="s3y4tbcur"/></g><circle fill="url(#iD1BuRY)" class="dh2jdtb9d"/><circle fill="url(#ifrSNpc)" class="dh2jdtb9d"/><path fill="url(#iuTsZnd)" class="u2n69ebqm"/><path fill="url(#iUw7VYc)" class="u2n69ebqm"/><path fill="url(#ibCfXcc)" class="u2n69ebqm"/><path fill="url(#ieIyGvb)" class="u2n69ebqm"/><path fill="url(#ikukHQL)" class="hpm95_b1p"/><path fill="url(#iTgkGMO)" class="hpm95_b1p"/><path fill="url(#ijYRCwd)" class="hpm95_b1p"/><path fill="url(#i87kadd)" class="t9xqfgc_k"/><path fill="url(#i2uZdxa)" class="t9xqfgc_k"/><path fill="url(#iWEWDRb)" class="t9xqfgc_k"/><path fill="url(#izVvYOb)" class="t9xqfgc_k"/><path fill="url(#icc5V1O)" class="t9xqfgc_k"/><path fill="url(#iVZXwqb)" class="t9xqfgc_k"/><path fill="url(#iPRCMEh)" class="t9xqfgc_k"/><path fill="url(#i2igVLb)" class="t9xqfgc_k"/><path fill="url(#i7iOeId)" class="t9xqfgc_k"/><path fill="url(#iTBu5Pe)" class="t9xqfgc_k"/><path fill="url(#ilj0Yid)" class="t9xqfgc_k"/><path class="tdgvllrbh"/><g filter="url(#iEMQF9d)"><path class="v07hdybbe"/></g><path clip-rule="evenodd" class="zmgjjlm1s"/><path fill="url(#ibDb5sd)" clip-rule="evenodd" class="xqjhmh8hm"/><path fill="url(#iJdYvlc)" clip-rule="evenodd" class="xqjhmh8hm"/><path fill="url(#iNJDabd)" clip-rule="evenodd" class="xqjhmh8hm"/><path class="z_biw6z0g"/><path fill="url(#iuXnyue)" class="i7o2o8bdr"/><path fill="url(#iGyEgvd)" class="i7o2o8bdr"/><path fill="url(#iqJZkjb)" class="i7o2o8bdr"/><path class="fmxe3ab-w"/><path fill="url(#i2tVn0b)" class="pfasl56_a"/><path class="l1b9wvbzv"/><g filter="url(#i7j24kc)"><path class="vy-uslaxh"/><path fill="url(#iiZQFPb)" class="f061qyjug"/></g><g filter="url(#irPHglc)"><path fill="url(#iQygOgd)" class="kw_vqvbhy"/></g><path class="wct_loblq"/><path fill="url(#ic6ptLd)" class="xj4-9nbvp"/><path class="kjtm3tcoy"/><g filter="url(#iZ4BFje)"><path fill="url(#iXBrW6w)" class="jq423obxr"/></g><g filter="url(#i7BcMke)"><ellipse transform="rotate(-27.914 13.557 11.568)" class="q0who510j"/><ellipse fill="url(#iD6jUeb)" transform="rotate(-27.914 13.557 11.568)" class="kr5338s6y"/></g><path fill="url(#iIPc1ne)" class="svutatbwq"/><path fill="url(#iq0M65b)" class="h7xy51bpg"/><path fill="url(#iis2yHd)" class="h7xy51bpg"/><path fill="url(#i232Kab)" class="h7xy51bpg"/><g filter="url(#iFqK6tc)"><path class="dkkxdobef"/><path fill="url(#iirIS1Y)" class="iolr40bhr"/><path fill="url(#isVL8Le)" class="iolr40bhr"/></g><g filter="url(#idgyMke)"><path class="g-9xmacti"/><path fill="url(#iifiQEU)" class="c0pcnf4_n"/><path fill="url(#ikpSaPe)" class="c0pcnf4_n"/></g><g filter="url(#iLPdVXc)"><path fill="url(#iqpAyje)" class="k4qqcx3ou"/><path fill="url(#iAujv8j)" class="k4qqcx3ou"/><path fill="url(#iMwseab)" class="k4qqcx3ou"/><path fill="url(#iLQognb)" class="k4qqcx3ou"/><path fill="url(#ivDRXUb)" class="k4qqcx3ou"/><path fill="url(#iEszd0b)" class="k4qqcx3ou"/></g><g filter="url(#iOVQ4hc)"><path class="iho6cn03s"/><path fill="url(#i85eS2T)" class="r6ott85bo"/><path fill="url(#ikLfCiR)" class="r6ott85bo"/></g><circle fill="url(#ixuYlke)" class="y2wq2jfrv"/><circle fill="url(#iwFvckb)" class="y2wq2jfrv"/><circle fill="url(#isQ21vc)" class="y2wq2jfrv"/><g filter="url(#iuPQbIb)"><circle fill="url(#i0qAXWN)" class="c5r0seiaf"/></g><g filter="url(#iwTixxc)"><circle class="ienazldja"/></g><circle fill="url(#iM3UZ9d)" class="pwxpg1bqp"/><circle fill="url(#iwAwJJc)" class="pwxpg1bqp"/><circle fill="url(#iLALpxl)" class="pwxpg1bqp"/><g filter="url(#iqWW8Lc)"><circle fill="url(#iHZVSey)" class="d9rl3ibjd"/></g><path class="u1xkznw_o"/><path stroke="url(#iffAh3X)" class="t-2gknhfu"/><g filter="url(#ijgwnze)"><path stroke="url(#is2iUek)" class="nb4aj8bat"/></g><path class="ez-bvlbil"/><path stroke="url(#iiuESHc)" class="tg7a7ybhf"/><g filter="url(#ikAmPRN)"><path stroke="url(#iFayE0d)" class="ooxbjdbjj"/></g><g filter="url(#ifUdxrd)"><path fill="url(#iGinVOb)" class="jf68hbbdo"/></g><g filter="url(#ifbJd4d)"><path stroke="url(#i0zDYsH)" class="xtuvoccjf"/></g><g filter="url(#iGxlUce)"><path stroke="url(#i80ytOe)" class="awaqui8yh"/></g><g filter="url(#ipKUjMd)"><path stroke="url(#immnVRd)" class="xnlf7sxhg"/></g><g filter="url(#iVx2Upe)"><path fill="url(#iJYmmOA)" class="w0-52cb4r"/></g><g filter="url(#ir7RkVb)"><path stroke="url(#is5NXRc)" class="mn1sb5qma"/></g><defs><radialGradient id="i3dBLoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.71875 -11.2218 0 16 17.596)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="qd3se0rgm"/><stop offset="1" class="psoka_i3g"/></radialGradient><radialGradient id="iApeS9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9687 8.83796 0 20.969 30.002)" gradientUnits="userSpaceOnUse"><stop class="d6etg3bpc"/><stop offset="1" class="uog-6pbgl"/></radialGradient><radialGradient id="i0mfUMb" cx="0" cy="0" r="1" gradientTransform="rotate(10.696 -88.607 109.315)scale(2.86223 15.7837)" gradientUnits="userSpaceOnUse"><stop class="map_82oik"/><stop offset="1" class="uqkn5mb7k"/></radialGradient><radialGradient id="iJLr1eb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84766 0 0 -9.64948 23.191 24.564)" gradientUnits="userSpaceOnUse"><stop class="l67zujbpu"/><stop offset="1" class="qmocns3dh"/></radialGradient><radialGradient id="i4yIhuc" cx="0" cy="0" r="1" gradientTransform="scale(4.9375 9.90625)rotate(90 .193 2.42)" gradientUnits="userSpaceOnUse"><stop class="xwh8wibwz"/><stop offset="1" class="siaktr89d"/></radialGradient><radialGradient id="iGZHoxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.125 -4.52157 0 13.063 18.064)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="anu_zib6b"/><stop offset="1" class="taq6oxbgc"/></radialGradient><radialGradient id="iMyTWsd" cx="0" cy="0" r="1" gradientTransform="matrix(1.00662 0 0 16.7858 8.79 27.658)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="ly4uss71n"/><stop offset="1" class="qh85l6bny"/></radialGradient><radialGradient id="i5faMwc" cx="0" cy="0" r="1" gradientTransform="matrix(.2461 0 0 20 8.758 30.002)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="d8bqj1ipj"/><stop offset=".952" class="vakzibr9s"/></radialGradient><radialGradient id="inSZ5nb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1593 -7.03125 2.71701 -.06156 13.765 30.002)" gradientUnits="userSpaceOnUse"><stop class="s8c_m8bxy"/><stop offset="1" class="wcd2kxb8c"/></radialGradient><radialGradient id="iMmPgee" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.29688 -.41239 0 14.504 21.846)" gradientUnits="userSpaceOnUse"><stop class="bxakbpbnw"/><stop offset="1" class="t3whbcbgf"/></radialGradient><radialGradient id="iABINwb" cx="0" cy="0" r="1" gradientTransform="matrix(.39844 2.85937 -1.80706 .2518 14.504 18.252)" gradientUnits="userSpaceOnUse"><stop class="tc-f31rjo"/><stop offset="1" class="d2nhlv10m"/></radialGradient><radialGradient id="iTPBf6y" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.45312 -.5039 0 14.504 18.142)" gradientUnits="userSpaceOnUse"><stop class="e56d7dbep"/><stop offset="1" class="zg82anb2t"/></radialGradient><radialGradient id="i159Cib" cx="0" cy="0" r="1" gradientTransform="matrix(.1593 -7.03125 2.71701 .06156 18.216 30.002)" gradientUnits="userSpaceOnUse"><stop class="s8c_m8bxy"/><stop offset="1" class="wcd2kxb8c"/></radialGradient><radialGradient id="iu87lzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39845 2.85937 -1.1846 -.16507 17.477 18.252)" gradientUnits="userSpaceOnUse"><stop class="al2ofbkms"/><stop offset="1" class="gqq2qjbta"/></radialGradient><radialGradient id="iqyyBTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -.38818 0 18.955 18.158)" gradientUnits="userSpaceOnUse"><stop class="bxakbpbnw"/><stop offset="1" class="t3whbcbgf"/></radialGradient><radialGradient id="iZFvrcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69727 0 0 -2.50195 11.307 12.316)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="fv-ihab3v"/><stop offset=".963" class="bjqztpblz"/></radialGradient><radialGradient id="ifxvBQd" cx="0" cy="0" r="1" gradientTransform="rotate(90.994 5.306 16.069)scale(2.85777)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="bytoh5baj"/><stop offset="1" class="r-_dztb_u"/></radialGradient><radialGradient id="iD1BuRY" cx="0" cy="0" r="1" gradientTransform="rotate(104.287 6.206 14.162)scale(1.29796)" gradientUnits="userSpaceOnUse"><stop class="g_3452bjf"/><stop offset="1" class="smkgpnmwb"/></radialGradient><radialGradient id="ifrSNpc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.467 23.633 -15.923)scale(.84075)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="p7g3dw-1h"/><stop offset="1" class="roh0t4blo"/></radialGradient><radialGradient id="iuTsZnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.25 3.82218 0 8.79 30.002)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="qo5hjkb1l"/><stop offset=".918" class="rnd-2g3zm"/></radialGradient><radialGradient id="iUw7VYc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.84375 0 0 -11.0312 8.624 30)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="xw_ma5b4i"/><stop offset="1" class="bzngqmzdt"/></radialGradient><radialGradient id="ibCfXcc" cx="0" cy="0" r="1" gradientTransform="rotate(107.068 -2.82 13.01)scale(3.96604 2.57642)" gradientUnits="userSpaceOnUse"><stop class="z-39yxbny"/><stop offset="1" class="n1fah1bul"/></radialGradient><radialGradient id="ieIyGvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.57812 .20957 0 8.595 30.002)" gradientUnits="userSpaceOnUse"><stop offset=".277" class="im-luab0p"/><stop offset="1" class="mc5wqkbfu"/></radialGradient><radialGradient id="ikukHQL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4958 2.84375 0 24.156 30.002)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="avhg4lb0o"/><stop offset=".968" class="jsgqqxbkh"/></radialGradient><radialGradient id="iTgkGMO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.375 1.1122 0 23.191 30.002)" gradientUnits="userSpaceOnUse"><stop class="p1vewccqc"/><stop offset="1" class="aqq8mk3_r"/></radialGradient><radialGradient id="i2uZdxa" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65628 4.12498 -4.73895 -4.2005 20.013 8.783)" gradientUnits="userSpaceOnUse"><stop class="ixj5j0baq"/><stop offset="1" class="p2n_dxhua"/></radialGradient><radialGradient id="iWEWDRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.12459 -2.04566 0 16.013 9.436)" gradientUnits="userSpaceOnUse"><stop class="yh-cclb6t"/><stop offset="1" class="b-l24bb-g"/></radialGradient><radialGradient id="icc5V1O" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.78125 3.71875 0 16.013 17.69)" gradientUnits="userSpaceOnUse"><stop class="z4v0x3b_g"/><stop offset="1" class="cz7bliorf"/></radialGradient><radialGradient id="iVZXwqb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.15625 .31532 4.66668 11.076 14.533)" gradientUnits="userSpaceOnUse"><stop class="t6no494do"/><stop offset="1" class="fnjtcybdo"/></radialGradient><radialGradient id="iPRCMEh" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 -1.9375 2.12863 1.8883 17.888 14.095)" gradientUnits="userSpaceOnUse"><stop class="v88qtuq-u"/><stop offset="1" class="p6mty9ksx"/></radialGradient><radialGradient id="i2igVLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -1.74208 0 18.232 12.502)" gradientUnits="userSpaceOnUse"><stop class="r3498vbtj"/><stop offset="1" class="n138fdcmg"/></radialGradient><radialGradient id="i7iOeId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.09375 1.05125 0 18.357 11.283)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="ug2gt2fgn"/><stop offset="1" class="qigaxib2s"/></radialGradient><radialGradient id="iTBu5Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.9375 1.35938 0 13.763 11.158)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="fch6pdrab"/><stop offset="1" class="kw4y66bon"/></radialGradient><radialGradient id="ilj0Yid" cx="0" cy="0" r="1" gradientTransform="matrix(-.42608 -.79298 .40588 -.21809 14.666 11.448)" gradientUnits="userSpaceOnUse"><stop class="g805ubc5j"/><stop offset="1" class="lqfwre7_m"/></radialGradient><radialGradient id="ibDb5sd" cx="0" cy="0" r="1" gradientTransform="rotate(35.681 -13.1 27.063)scale(8.73313 8.14368)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="q2fs03b0k"/><stop offset=".986" class="sdhsm3bgh"/></radialGradient><radialGradient id="iJdYvlc" cx="0" cy="0" r="1" gradientTransform="matrix(5.43854 .21875 -.71079 17.67151 16.012 12.97)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="joy0wpakq"/><stop offset=".969" class="ltmlwr2nq"/></radialGradient><radialGradient id="iNJDabd" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 .38281 -.34172 -.1883 16.31 17.08)" gradientUnits="userSpaceOnUse"><stop class="krhw_kbxt"/><stop offset="1" class="xhm3b5b7k"/></radialGradient><radialGradient id="iuXnyue" cx="0" cy="0" r="1" gradientTransform="matrix(-.75872 .1308 -.5608 -3.25275 16.71 13.41)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="yzq2kjbif"/><stop offset="1" class="e075dnzer"/></radialGradient><radialGradient id="iGyEgvd" cx="0" cy="0" r="1" gradientTransform="matrix(.63025 -2.32464 .3024 .08198 15.104 14.25)" gradientUnits="userSpaceOnUse"><stop class="h8duf1bxd"/><stop offset="1" class="z645iqbrw"/></radialGradient><radialGradient id="i2tVn0b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04682 .84371 -1.1771 -1.46046 18.523 11.424)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="pwx7w1tsv"/><stop offset="1" class="mra-g7bul"/></radialGradient><radialGradient id="iiZQFPb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.967 11.747)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic6ptLd" cx="0" cy="0" r="1" gradientTransform="rotate(141.132 5.063 8.21)scale(1.34457 1.87586)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="pwx7w1tsv"/><stop offset="1" class="mra-g7bul"/></radialGradient><radialGradient id="iD6jUeb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.62 -.724)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIPc1ne" cx="0" cy="0" r="1" gradientTransform="rotate(73.05 6.709 15.672)scale(3.26122 8.44989)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="ip_2iibnh"/><stop offset=".788" class="nuif9xlfl"/></radialGradient><radialGradient id="iq0M65b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.2467 -2.13922 2.57176 -5.10538 15.973 5.81)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="fxrx-4bfz"/><stop offset="1" class="brqql5k0f"/></radialGradient><radialGradient id="iis2yHd" cx="0" cy="0" r="1" gradientTransform="rotate(111.386 7.296 7.96)scale(2.43353 .67945)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="vae8lub_a"/><stop offset="1" class="ienfcucyk"/></radialGradient><radialGradient id="i232Kab" cx="0" cy="0" r="1" gradientTransform="rotate(106.314 5.138 8.745)scale(1.35388 1.09058)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="nlravgt3v"/><stop offset="1" class="v42cqkcto"/></radialGradient><radialGradient id="iirIS1Y" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25183 -4.83301 0 18.524 6.984)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="c9i57_blc"/><stop offset="1" class="asi2gqd3l"/></radialGradient><radialGradient id="isVL8Le" cx="0" cy="0" r="1" gradientTransform="matrix(.91114 1.21222 -.79438 .59708 20.656 9.788)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="o6mdblbao"/><stop offset="1" class="cc1xhab3r"/></radialGradient><radialGradient id="iifiQEU" cx="0" cy="0" r="1" gradientTransform="rotate(83.758 7.61 12.482)scale(1.02019 3.10225)" gradientUnits="userSpaceOnUse"><stop class="ktvc3wz9h"/><stop offset="1" class="y1d9sby0q"/></radialGradient><radialGradient id="ikpSaPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4834 -2.04412 2.67128 -1.93852 22.369 5.716)" gradientUnits="userSpaceOnUse"><stop class="z78gnj88j"/><stop offset="1" class="z8hbz1_-a"/></radialGradient><radialGradient id="iAujv8j" cx="0" cy="0" r="1" gradientTransform="matrix(2.42443 -1.9966 1.51918 1.84472 10.918 10.744)" gradientUnits="userSpaceOnUse"><stop offset=".49" class="fu5mseals"/><stop offset="1" class="tk0vr1ber"/></radialGradient><radialGradient id="iMwseab" cx="0" cy="0" r="1" gradientTransform="matrix(1.77476 2.91564 -2.50952 1.52755 15.466 6.781)" gradientUnits="userSpaceOnUse"><stop class="lur1dknhn"/><stop offset="1" class="jhrkx66zx"/></radialGradient><radialGradient id="iLQognb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6163 1.64797 -1.2279 -1.2043 19.174 4.88)" gradientUnits="userSpaceOnUse"><stop class="nrnnc-biv"/><stop offset="1" class="ay6dvtg4c"/></radialGradient><radialGradient id="ivDRXUb" cx="0" cy="0" r="1" gradientTransform="matrix(6.9373 -.33277 .32637 6.80389 11.87 5.197)" gradientUnits="userSpaceOnUse"><stop offset=".982" class="e_7vtac5q"/><stop offset=".993" class="y5-px1btw"/></radialGradient><radialGradient id="iEszd0b" cx="0" cy="0" r="1" gradientTransform="rotate(109.239 5.415 8.815)scale(1.25035 1.63222)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="za5enxahd"/><stop offset="1" class="oe-uqrbal"/></radialGradient><radialGradient id="i85eS2T" cx="0" cy="0" r="1" gradientTransform="matrix(.91906 1.20504 -3.92207 2.99128 10.713 3.989)" gradientUnits="userSpaceOnUse"><stop class="mqk1vcctk"/><stop offset="1" class="hvho19_je"/></radialGradient><radialGradient id="ikLfCiR" cx="0" cy="0" r="1" gradientTransform="matrix(4.24671 -1.26918 .55124 1.84446 9.983 6.716)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="u6ggrwbro"/><stop offset="1" class="cv2bxebia"/></radialGradient><radialGradient id="ixuYlke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60042 2.50367 -2.40264 -1.53584 16.94 4.971)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="yem538otj"/><stop offset="1" class="h33d0vgtb"/></radialGradient><radialGradient id="iwFvckb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1392 -2.36995 0 15.9 5.7)" gradientUnits="userSpaceOnUse"><stop offset=".785" class="joaz6acnx"/><stop offset="1" class="vno_7t63q"/></radialGradient><radialGradient id="isQ21vc" cx="0" cy="0" r="1" gradientTransform="rotate(150.336 7.13 5.204)scale(1.55688 2.09767)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="aj22pcbyb"/><stop offset="1" class="wz6bzjb_t"/></radialGradient><radialGradient id="i0qAXWN" cx="0" cy="0" r="1" gradientTransform="rotate(122.588 6.97 7.177)scale(2.48735 2.38697)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="iv7gqubaa"/><stop offset="1" class="vg6jezb7s"/></radialGradient><radialGradient id="iM3UZ9d" cx="0" cy="0" r="1" gradientTransform="rotate(133.112 6.906 6.475)scale(1.02019)" gradientUnits="userSpaceOnUse"><stop class="x2nz94bxt"/><stop offset="1" class="pl3efkh-l"/></radialGradient><radialGradient id="iwAwJJc" cx="0" cy="0" r="1" gradientTransform="matrix(.11686 -.83785 1.47716 .20603 15.783 7.035)" gradientUnits="userSpaceOnUse"><stop class="sof8zwbsb"/><stop offset="1" class="cwth_ve7b"/></radialGradient><radialGradient id="iLALpxl" cx="0" cy="0" r="1" gradientTransform="matrix(-.79824 .29513 -.4107 -1.11078 15.899 6.197)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="wci1pqi0w"/><stop offset="1" class="d6o1iwbzc"/></radialGradient><radialGradient id="iffAh3X" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 .0625 -.0865 .99485 11.935 10.158)" gradientUnits="userSpaceOnUse"><stop offset=".075" class="hx7_zcbyj"/><stop offset=".869" class="vsyg2xbej"/></radialGradient><radialGradient id="iiuESHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 0 0 -1.68121 18.857 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".665" class="w93bbibjj"/><stop offset="1" class="qpv__2bfz"/></radialGradient><radialGradient id="iJYmmOA" cx="0" cy="0" r="1" gradientTransform="rotate(107.526 1.516 14.502)scale(.93398 .61264)" gradientUnits="userSpaceOnUse"><stop offset=".376" class="orxnp6m5o"/><stop offset="1" class="k0v0o9b8w"/></radialGradient><filter id="i3du35c" width="3.377" height="3.377" x="18.985" y="10.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".1"/></filter><filter id="iq1gxLc" width="1.99" height="1.99" x="10.148" y="11.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".1"/></filter><filter id="iEMQF9d" width="2.271" height="3.351" x="14.758" y="11.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".25"/></filter><filter id="i7j24kc" width=".787" height=".697" x="17.461" y="11.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".05"/></filter><filter id="irPHglc" width=".892" height=".914" x="18.302" y="11.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".1"/></filter><filter id="iZ4BFje" width=".987" height="1.041" x="13.855" y="11.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".1"/></filter><filter id="i7BcMke" width=".914" height=".705" x="13.1" y="11.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".05"/></filter><filter id="iFqK6tc" width="6.508" height="3.764" x="15.574" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.4 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2372"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.298039 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2372" result="effect2_innerShadow_2_2372"/></filter><filter id="idgyMke" width="3.665" height="2.869" x="18.704" y="3.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.396078 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2372"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.156863 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2372" result="effect2_innerShadow_2_2372"/></filter><filter id="iLPdVXc" width="9.216" height="7.121" x="9.69" y="3.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.160784 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2372"/></filter><filter id="iOVQ4hc" width="5.816" height="3.144" x="9.597" y="3.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.113725 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2372"/></filter><filter id="iuPQbIb" width="2.724" height="2.724" x="14.538" y="4.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".05"/></filter><filter id="iwTixxc" width="1.876" height="1.876" x="14.887" y="5.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".05"/></filter><filter id="iqWW8Lc" width="1.345" height="1.345" x="15.228" y="5.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".05"/></filter><filter id="ijgwnze" width="2.473" height="1.206" x="12.177" y="9.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".125"/></filter><filter id="ikAmPRN" width="2.621" height="1.243" x="17.377" y="9.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".125"/></filter><filter id="ifUdxrd" width="4.272" height="10.561" x="10.588" y="8.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".15"/></filter><filter id="ifbJd4d" width="2.407" height="2.447" x="18.278" y="15.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".075"/></filter><filter id="iGxlUce" width=".838" height="2.509" x="13.115" y="15.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".075"/></filter><filter id="ipKUjMd" width=".98" height=".539" x="16.297" y="17.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".075"/></filter><filter id="iVx2Upe" width=".914" height="1.237" x="15.129" y="17.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".075"/></filter><filter id="ir7RkVb" width="2.17" height="1.064" x="16.379" y="14.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2372" stdDeviation=".075"/></filter><linearGradient id="iEmIkEb" x1="16" x2="16" y1="16.83" y2="30.002" gradientUnits="userSpaceOnUse"><stop offset=".665" class="c78jw65ce"/><stop offset="1" class="yqin9d1eu"/></linearGradient><linearGradient id="ir6TqBc" x1="23.191" x2="23.059" y1="26.959" y2="26.959" gradientUnits="userSpaceOnUse"><stop class="tw_ou6-wu"/><stop offset="1" class="woyxclbuf"/></linearGradient><linearGradient id="ijYRCwd" x1="25.563" x2="27" y1="30.408" y2="25.314" gradientUnits="userSpaceOnUse"><stop class="bda624niz"/><stop offset="1" class="v8mqcsb1j"/></linearGradient><linearGradient id="i87kadd" x1="16.013" x2="16.013" y1="9.158" y2="18.533" gradientUnits="userSpaceOnUse"><stop class="k1oe0ccuv"/><stop offset="1" class="ovw9dsbem"/></linearGradient><linearGradient id="izVvYOb" x1="16.013" x2="16.013" y1="9.314" y2="8.377" gradientUnits="userSpaceOnUse"><stop class="kjck-pb8b"/><stop offset="1" class="qyswnibef"/></linearGradient><linearGradient id="iqJZkjb" x1="16.203" x2="16.203" y1="14.703" y2="14.002" gradientUnits="userSpaceOnUse"><stop offset=".123" class="g8hsjbmmz"/><stop offset="1" class="i7wpi6bfc"/></linearGradient><linearGradient id="iQygOgd" x1="18.935" x2="18.678" y1="11.725" y2="11.89" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXBrW6w" x1="14.573" x2="14.259" y1="11.718" y2="11.911" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqpAyje" x1="17.97" x2="9.952" y1="4.976" y2="10.66" gradientUnits="userSpaceOnUse"><stop class="xiq09ubck"/><stop offset="1" class="z1vah_bkx"/></linearGradient><linearGradient id="iHZVSey" x1="15.9" x2="15.9" y1="5.906" y2="6.77" gradientUnits="userSpaceOnUse"><stop class="pln90ra2q"/><stop offset="1" class="v3r7tab1y"/></linearGradient><linearGradient id="is2iUek" x1="14.169" x2="12.512" y1="9.642" y2="10.085" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></linearGradient><linearGradient id="iFayE0d" x1="19.373" x2="18.029" y1="10.103" y2="9.759" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></linearGradient><linearGradient id="iGinVOb" x1="11.107" x2="14.888" y1="10.252" y2="18.955" gradientUnits="userSpaceOnUse"><stop offset=".757" class="w4h8bubsi"/><stop offset="1" class="t7u3qkefj"/></linearGradient><linearGradient id="i0zDYsH" x1="18.888" x2="20.826" y1="17.76" y2="15.447" gradientUnits="userSpaceOnUse"><stop offset=".468" class="w6tooobqh"/><stop offset="1" class="ptzte1bwx"/></linearGradient><linearGradient id="i80ytOe" x1="13.406" x2="14.362" y1="17.783" y2="17.539" gradientUnits="userSpaceOnUse"><stop offset=".468" class="w6tooobqh"/><stop offset="1" class="ptzte1bwx"/></linearGradient><linearGradient id="immnVRd" x1="16.626" x2="16.694" y1="18.021" y2="17.712" gradientUnits="userSpaceOnUse"><stop offset=".468" class="w6tooobqh"/><stop offset="1" class="ptzte1bwx"/></linearGradient><linearGradient id="is5NXRc" x1="18.091" x2="17.123" y1="15.119" y2="16.254" gradientUnits="userSpaceOnUse"><stop offset=".267" class="w6tooobqh"/><stop offset=".747" class="ptzte1bwx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-genie" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.aj22pcbyb {
  stop-color: var(--svg-color--ffbc6e, #FFBC6E);
  stop-opacity: 0;
}

.al2ofbkms {
  stop-color: var(--svg-color--99943c, #99943C);
}

.anu_zib6b {
  stop-color: var(--svg-color--952238, #952238);
}

.aqq8mk3_r {
  stop-color: var(--svg-color--3cc2ff, #3CC2FF);
  stop-opacity: 0;
}

.asi2gqd3l {
  stop-color: var(--svg-color--ff5875, #FF5875);
  stop-opacity: 0;
}

.avhg4lb0o {
  stop-color: var(--svg-color--63e0ff, #63E0FF);
}

.awaqui8yh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.752 15.674c-.026.052-.078.24-.078.578v1.039c0 .14-.072.436-.36.492");
}

.ay6dvtg4c {
  stop-color: var(--svg-color--ff636d, #FF636D);
  stop-opacity: 0;
}

.b-l24bb-g {
  stop-color: var(--svg-color--3da1e6, #3DA1E6);
  stop-opacity: 0;
}

.b5z7mkyzl {
  cx: 20.674px;
  cy: 12.316px;
  r: 1.697px;
  fill: var(--svg-color--18b4ff, #18B4FF);
}

.bda624niz {
  stop-color: var(--svg-color--56cdff, #56CDFF);
}

.bjqztpblz {
  stop-color: var(--svg-color--71c3ff, #71C3FF);
}

.brqql5k0f {
  stop-color: var(--svg-color--ff6b79, #FF6B79);
}

.bxakbpbnw {
  stop-color: var(--svg-color--fedd3a, #FEDD3A);
}

.bytoh5baj {
  stop-color: var(--svg-color--5ac0ff, #5AC0FF);
}

.bzngqmzdt {
  stop-color: var(--svg-color--62bceb, #62BCEB);
}

.c0pcnf4_n {
  d: path("M18.8 4.979c1.064.003 2.722.348 3.567 1.343l.002.02c-.147-1.656-1.461-2.653-3.098-2.67h-.567c.078.379.119.83.096 1.307");
}

.c5r0seiaf {
  cx: 15.9px;
  cy: 6.197px;
  r: 1.262px;
}

.c78jw65ce {
  stop-color: var(--svg-color--42c2ff, #42C2FF);
}

.c9i57_blc {
  stop-color: var(--svg-color--ff5875, #FF5875);
}

.cc1xhab3r {
  stop-color: var(--svg-color--8c4277, #8C4277);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cv2bxebia {
  stop-color: var(--svg-color--fd6772, #FD6772);
  stop-opacity: 0;
}

.cwth_ve7b {
  stop-color: var(--svg-color--e21a67, #E21A67);
  stop-opacity: 0;
}

.cz7bliorf {
  stop-color: var(--svg-color--31a8ff, #31A8FF);
  stop-opacity: 0;
}

.d2nhlv10m {
  stop-color: var(--svg-color--9a9338, #9A9338);
  stop-opacity: 0;
}

.d6etg3bpc {
  stop-color: var(--svg-color--ff4472, #FF4472);
}

.d6o1iwbzc {
  stop-color: var(--svg-color--f8606c, #F8606C);
}

.d8bqj1ipj {
  stop-color: var(--svg-color--b6396a, #B6396A);
}

.d9rl3ibjd {
  cx: 15.9px;
  cy: 6.197px;
  r: 0.572px;
}

.dh2jdtb9d {
  cx: 20.807px;
  cy: 12.316px;
  r: 0.795px;
}

.dkkxdobef {
  fill: var(--svg-color--ff3565, #FF3565);
  d: path("M21.976 9.705c.03-.463-.045-.948-.322-1.372c-.622-.952-2.306-1.154-2.82-1.154h-1.276l-1.834 1.35h3.846c.582 0 1.008.218 1.248.515c.43.464.465.923.465 1.598c.186-.09.267-.198.387-.362q.186-.258.306-.575");
}

.e_7vtac5q {
  stop-color: var(--svg-color--ff5b5e, #FF5B5E);
  stop-opacity: 0;
}

.e075dnzer {
  stop-color: var(--svg-color--68d2ff, #68D2FF);
  stop-opacity: 0;
}

.e56d7dbep {
  stop-color: var(--svg-color--7c7e3d, #7C7E3D);
}

.ea6rlsbmk {
  d: path("M23.191 19.506v10.496h-5.714V16.928a10.96 10.96 0 0 1 5.714 2.578");
}

.eb2k4iasx {
  cx: 11.307px;
  cy: 12.316px;
  r: 1.697px;
}

.ez-bvlbil {
  stroke: var(--svg-color--271b20, #271B20);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M19.474 10.22c-.234-.192-.824-.539-1.723-.437");
}

.f061qyjug {
  d: path("M18.132 11.375c.063.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.f4g52x70m {
  d: path("M14.504 16.93v13.072H8.789v-10.48a10.96 10.96 0 0 1 5.715-2.591");
}

.fch6pdrab {
  stop-color: var(--svg-color--2fa7f3, #2FA7F3);
}

.fmxe3ab-w {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.405 10.914c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34H17.26a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.373-1.129");
}

.fnjtcybdo {
  stop-color: var(--svg-color--6bc8ff, #6BC8FF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu5mseals {
  stop-color: var(--svg-color--cb2c70, #CB2C70);
}

.fv-ihab3v {
  stop-color: var(--svg-color--33adf7, #33ADF7);
  stop-opacity: 0;
}

.fxrx-4bfz {
  stop-color: var(--svg-color--fc2b32, #FC2B32);
}

.g_3452bjf {
  stop-color: var(--svg-color--4abaff, #4ABAFF);
}

.g-9xmacti {
  fill: var(--svg-color--ff4449, #FF4449);
  d: path("M18.8 4.979c1.064.003 2.722.348 3.567 1.343l.002.02c-.147-1.656-1.461-2.653-3.098-2.67h-.567c.078.379.119.83.096 1.307");
}

.g805ubc5j {
  stop-color: var(--svg-color--62c2ff, #62C2FF);
}

.g8hsjbmmz {
  stop-color: var(--svg-color--30b0ff, #30B0FF);
}

.gqq2qjbta {
  stop-color: var(--svg-color--cabb36, #CABB36);
  stop-opacity: 0;
}

.h33d0vgtb {
  stop-color: var(--svg-color--e57241, #E57241);
}

.h7xy51bpg {
  d: path("M18.704 3.672h-6.058c-1.784.019-2.964.958-3.059 3.216c.051.839.156 2.115.286 2.563c.141.49.468.867.86 1.209c0-.33-.058-.915.107-1.277a1.5 1.5 0 0 1 1.386-.855h4.097c2.431-.784 2.685-3.375 2.38-4.856");
}

.h8duf1bxd {
  stop-color: var(--svg-color--5ec2ff, #5EC2FF);
}

.hpm95_b1p {
  d: path("M23.191 30.002V19.506A10.98 10.98 0 0 1 27 27.83v2.172z");
}

.hvho19_je {
  stop-color: var(--svg-color--da5d60, #DA5D60);
  stop-opacity: 0;
}

.hx7_zcbyj {
  stop-color: var(--svg-color--565253, #565253);
}

.i7o2o8bdr {
  d: path("m15.613 12.22l-.48 1.81c-.109.366.1.673.47.673h.786c.37 0 .602-.34.494-.7l-.531-1.783c-.114-.394-.62-.394-.739 0");
}

.i7wpi6bfc {
  stop-color: var(--svg-color--30b0ff, #30B0FF);
  stop-opacity: 0;
}

.ienazldja {
  cx: 15.825px;
  cy: 6.269px;
  r: 0.838px;
  fill: var(--svg-color--df6631, #DF6631);
}

.ienfcucyk {
  stop-color: var(--svg-color--ff5458, #FF5458);
  stop-opacity: 0;
}

.iho6cn03s {
  fill: var(--svg-color--f1252d, #F1252D);
  d: path("M9.597 6.716c.27-.301.784-.74 1.266-.929c.82-.27 2.523-.463 4.02-.515c.252-.112.625-.59.507-1.6h-2.744c-1.738.019-2.902.91-3.05 3.044");
}

.im-luab0p {
  stop-color: var(--svg-color--5bc5ff, #5BC5FF);
}

.iolr40bhr {
  d: path("M21.976 9.705c.03-.463-.045-.948-.322-1.372c-.622-.952-2.306-1.154-2.82-1.154h-1.276l-1.834 1.35h3.846c.582 0 1.008.218 1.248.515c.43.464.465.923.465 1.598c.186-.09.267-.198.387-.362q.186-.258.306-.575");
}

.ip_2iibnh {
  stop-color: var(--svg-color--ff666e, #FF666E);
}

.iv7gqubaa {
  stop-color: var(--svg-color--ffb53f, #FFB53F);
}

.ixj5j0baq {
  stop-color: var(--svg-color--59c0fe, #59C0FE);
}

.jf68hbbdo {
  d: path("M10.888 10.33c0-.825.297-1.149.5-1.336c-.117 2.336-.07 6.708.625 7.836c.68 1.101 1.524.992 2.024 1.07l.523 1.055c-.922-.031-2.406-.414-3.016-1.664c-.687-1.586-.656-5.93-.656-6.961");
}

.jhrkx66zx {
  stop-color: var(--svg-color--e51d5e, #E51D5E);
  stop-opacity: 0;
}

.joaz6acnx {
  stop-color: var(--svg-color--cf634e, #CF634E);
  stop-opacity: 0;
}

.joy0wpakq {
  stop-color: var(--svg-color--4d5058, #4D5058);
  stop-opacity: 0;
}

.jq423obxr {
  d: path("M14.642 11.975c0-.29-.234-.482-.298-.54l-.289.28l.178.361z");
}

.jsgqqxbkh {
  stop-color: var(--svg-color--57cfff, #57CFFF);
}

.k0v0o9b8w {
  stop-color: var(--svg-color--3e3e3f, #3E3E3F);
  stop-opacity: 0;
}

.k1oe0ccuv {
  stop-color: var(--svg-color--41acf2, #41ACF2);
}

.k1s5p0meo {
  d: path("M13.026 30.002V17.214q.721-.197 1.478-.294v13.082z");
}

.k4qqcx3ou {
  d: path("M15.568 6.909c1.413-.858 1.577-2.445 1.475-3.233h1.66c.285 1.387.081 3.746-1.94 4.685c-.284.132-.6.172-.912.172h-3.626q-.094 0-.181.01c-.633.066-.95.469-1.117.834c-.181.398-.191 1.011-.191 1.32c-.389-.34-.722-.753-.864-1.24c-.069-.24-.131-.719-.182-1.24c.248-.23.523-.455.783-.61c.818-.552 2.504-.717 3.217-.698z");
}

.kjck-pb8b {
  stop-color: var(--svg-color--46b0f5, #46B0F5);
  stop-opacity: 0;
}

.kjtm3tcoy {
  fill: var(--svg-color--000, #000);
  d: path("M14.338 12.08a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.kr5338s6y {
  cx: 13.557px;
  cy: 11.568px;
  rx: 0.39px;
  ry: 0.197px;
}

.krhw_kbxt {
  stop-color: var(--svg-color--494849, #494849);
}

.ktvc3wz9h {
  stop-color: var(--svg-color--df6b6d, #DF6B6D);
}

.kw_vqvbhy {
  d: path("M18.993 11.962a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.kw4y66bon {
  stop-color: var(--svg-color--2fa7f3, #2FA7F3);
  stop-opacity: 0;
}

.l1b9wvbzv {
  fill: var(--svg-color--000, #000);
  d: path("M17.686 12.08a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.061-.236");
}

.l67zujbpu {
  stop-color: var(--svg-color--ff636e, #FF636E);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqfwre7_m {
  stop-color: var(--svg-color--62c2ff, #62C2FF);
  stop-opacity: 0;
}

.ltmlwr2nq {
  stop-color: var(--svg-color--4d5058, #4D5058);
}

.lur1dknhn {
  stop-color: var(--svg-color--e51d5e, #E51D5E);
}

.ly4uss71n {
  stop-color: var(--svg-color--f15172, #F15172);
}

.map_82oik {
  stop-color: var(--svg-color--d61e37, #D61E37);
}

.mc5wqkbfu {
  stop-color: var(--svg-color--5bc5ff, #5BC5FF);
  stop-opacity: 0;
}

.mn1sb5qma {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.529 14.94h.976c.269.02.813.191.844.71");
}

.mqk1vcctk {
  stop-color: var(--svg-color--da5d60, #DA5D60);
}

.mqyc56bzr {
  d: path("M18.955 30.002V17.214q-.721-.197-1.478-.294v13.082z");
}

.mra-g7bul {
  stop-color: var(--svg-color--7c544c, #7C544C);
}

.n138fdcmg {
  stop-color: var(--svg-color--4cd1ff, #4CD1FF);
  stop-opacity: 0;
}

.n1fah1bul {
  stop-color: var(--svg-color--5bb9ea, #5BB9EA);
  stop-opacity: 0;
}

.nb4aj8bat {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.552 10.142c.235-.192.825-.539 1.723-.437");
}

.njefkxbrx {
  cx: 11.307px;
  cy: 12.316px;
  r: 1.697px;
  fill: var(--svg-color--2eaaf2, #2EAAF2);
}

.nlravgt3v {
  stop-color: var(--svg-color--cf3142, #CF3142);
}

.nrnnc-biv {
  stop-color: var(--svg-color--ff636d, #FF636D);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o6mdblbao {
  stop-color: var(--svg-color--8c4277, #8C4277);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe-uqrbal {
  stop-color: var(--svg-color--cf344c, #CF344C);
  stop-opacity: 0;
}

.ooxbjdbjj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.623 10.142c-.235-.192-.973-.578-1.872-.476");
}

.orxnp6m5o {
  stop-color: var(--svg-color--3e3e3f, #3E3E3F);
}

.ovw9dsbem {
  stop-color: var(--svg-color--68c6ff, #68C6FF);
}

.p1vewccqc {
  stop-color: var(--svg-color--3cc2ff, #3CC2FF);
}

.p2n_dxhua {
  stop-color: var(--svg-color--59c0fe, #59C0FE);
  stop-opacity: 0;
}

.p6mty9ksx {
  stop-color: var(--svg-color--52d2ff, #52D2FF);
  stop-opacity: 0;
}

.p7g3dw-1h {
  stop-color: var(--svg-color--57beff, #57BEFF);
  stop-opacity: 0;
}

.pfasl56_a {
  d: path("M18.197 11.186a.893.893 0 0 1 .861 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl3efkh-l {
  stop-color: var(--svg-color--e92b2e, #E92B2E);
}

.pln90ra2q {
  stop-color: var(--svg-color--f43243, #F43243);
}

.psoka_i3g {
  stop-color: var(--svg-color--0f8dff, #0F8DFF);
  stop-opacity: 0;
}

.ptzte1bwx {
  stop-color: var(--svg-color--4b4949, #4B4949);
  stop-opacity: 0;
}

.pwx7w1tsv {
  stop-color: var(--svg-color--865f52, #865F52);
}

.pwxpg1bqp {
  cx: 15.9px;
  cy: 6.197px;
  r: 0.838px;
}

.q0who510j {
  cx: 13.557px;
  cy: 11.568px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.q2fs03b0k {
  stop-color: var(--svg-color--423c3e, #423C3E);
  stop-opacity: 0;
}

.qd3se0rgm {
  stop-color: var(--svg-color--0f8dff, #0F8DFF);
}

.qh85l6bny {
  stop-color: var(--svg-color--f05163, #F05163);
  stop-opacity: 0;
}

.qigaxib2s {
  stop-color: var(--svg-color--30b7ff, #30B7FF);
  stop-opacity: 0;
}

.qmocns3dh {
  stop-color: var(--svg-color--ff636e, #FF636E);
  stop-opacity: 0;
}

.qo5hjkb1l {
  stop-color: var(--svg-color--39beff, #39BEFF);
}

.qpv__2bfz {
  stop-color: var(--svg-color--3c3c42, #3C3C42);
}

.qyswnibef {
  stop-color: var(--svg-color--0681c2, #0681C2);
}

.r-_dztb_u {
  stop-color: var(--svg-color--5ac0ff, #5AC0FF);
  stop-opacity: 0;
}

.r3498vbtj {
  stop-color: var(--svg-color--4cd1ff, #4CD1FF);
}

.r6ott85bo {
  d: path("M9.597 6.716c.27-.301.784-.74 1.266-.929c.82-.27 2.523-.463 4.02-.515c.252-.112.625-.59.507-1.6h-2.744c-1.738.019-2.902.91-3.05 3.044");
}

.rnd-2g3zm {
  stop-color: var(--svg-color--75d9ff, #75D9FF);
}

.roh0t4blo {
  stop-color: var(--svg-color--57beff, #57BEFF);
}

.s3y4tbcur {
  cx: 11.143px;
  cy: 12.316px;
  r: 0.795px;
  fill: var(--svg-color--2ea9f4, #2EA9F4);
}

.s8c_m8bxy {
  stop-color: var(--svg-color--ff9a38, #FF9A38);
}

.sdhsm3bgh {
  stop-color: var(--svg-color--423c3e, #423C3E);
}

.siaktr89d {
  stop-color: var(--svg-color--fc2c61, #FC2C61);
}

.smkgpnmwb {
  stop-color: var(--svg-color--3db5ff, #3DB5FF);
}

.sof8zwbsb {
  stop-color: var(--svg-color--e21a67, #E21A67);
}

.stqou83fh {
  cx: 20.674px;
  cy: 12.316px;
  r: 1.389px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.svutatbwq {
  d: path("M22.367 6.322c-1.022-1.203-3.231-1.455-4.144-1.303L16.116 6.19l-.41 2.337h3.864c.582 0 1.008.22 1.248.515c.43.466.515.954.515 1.54c.178-.087.217-.139.337-.303c.528-.725.607-1.797.705-3.392a4 4 0 0 0-.008-.566");
}

.t-2gknhfu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M12.552 10.22c.235-.192.825-.539 1.723-.437");
}

.t3whbcbgf {
  stop-color: var(--svg-color--fedd3a, #FEDD3A);
  stop-opacity: 0;
}

.t6no494do {
  stop-color: var(--svg-color--6bc8ff, #6BC8FF);
}

.t7u3qkefj {
  stop-color: var(--svg-color--545253, #545253);
  stop-opacity: 0;
}

.t9xqfgc_k {
  d: path("M10.827 9.026c-.182 1.71-.075 3.853.086 5.843c.205 2.532.733 3.653 2.704 4.09c1.443.32 3.35.32 4.793 0c1.97-.437 2.498-1.558 2.703-4.09c.161-1.99.268-4.132.087-5.843c-.215-.65-1.038-.844-1.443-.813H12.27c-.404-.031-1.228.163-1.442.813");
}

.taq6oxbgc {
  stop-color: var(--svg-color--da2730, #DA2730);
  stop-opacity: 0;
}

.tc-f31rjo {
  stop-color: var(--svg-color--747741, #747741);
}

.tdgvllrbh {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M13.99 15.15a1.991 1.991 0 0 0 3.81 0z");
}

.tg7a7ybhf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M19.474 10.22c-.234-.192-.824-.539-1.723-.437");
}

.tk0vr1ber {
  stop-color: var(--svg-color--cb2c70, #CB2C70);
  stop-opacity: 0;
}

.trnyvebve {
  d: path("M5 27.83c0-6.075 4.925-11 11-11s11 4.925 11 11v2.172H5z");
}

.tw_ou6-wu {
  stop-color: var(--svg-color--f83c69, #F83C69);
}

.u1xkznw_o {
  stroke: var(--svg-color--271b20, #271B20);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-95px, 0.95px);
  d: path("M12.552 10.22c.235-.192.825-.539 1.723-.437");
}

.u2n69ebqm {
  d: path("M8.79 19.523v10.479H5V27.83c0-3.317 1.468-6.29 3.79-8.307");
}

.u6ggrwbro {
  stop-color: var(--svg-color--fd6772, #FD6772);
}

.ug2gt2fgn {
  stop-color: var(--svg-color--30b7ff, #30B7FF);
}

.uog-6pbgl {
  stop-color: var(--svg-color--f63b44, #F63B44);
}

.uqkn5mb7k {
  stop-color: var(--svg-color--f93e4d, #F93E4D);
  stop-opacity: 0;
}

.v07hdybbe {
  fill: var(--svg-color--169de8, #169DE8);
  d: path("m15.616 12.476l-.338 1.532c-.076.31.07.57.33.57h.555c.26 0 .424-.288.347-.593l-.374-1.51c-.08-.332-.436-.332-.52 0");
}

.v3r7tab1y {
  stop-color: var(--svg-color--fc3364, #FC3364);
}

.v42cqkcto {
  stop-color: var(--svg-color--cf3142, #CF3142);
  stop-opacity: 0;
}

.v88qtuq-u {
  stop-color: var(--svg-color--52d2ff, #52D2FF);
}

.v8mqcsb1j {
  stop-color: var(--svg-color--56cdff, #56CDFF);
  stop-opacity: 0;
}

.vae8lub_a {
  stop-color: var(--svg-color--ff5458, #FF5458);
}

.vakzibr9s {
  stop-color: var(--svg-color--e24371, #E24371);
  stop-opacity: 0;
}

.vg6jezb7s {
  stop-color: var(--svg-color--ff8c3f, #FF8C3F);
}

.vno_7t63q {
  stop-color: var(--svg-color--cf634e, #CF634E);
}

.vsyg2xbej {
  stop-color: var(--svg-color--565253, #565253);
  stop-opacity: 0;
}

.vy-uslaxh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  d: path("M18.132 11.375c.063.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358s.325-.136.389-.051");
}

.w0-52cb4r {
  d: path("M15.689 17.576c0 .325-.274.396-.41.39c.199.32.594.313.613-.03c.016-.276-.129-.563-.203-.673z");
}

.w4h8bubsi {
  stop-color: var(--svg-color--545253, #545253);
}

.w6tooobqh {
  stop-color: var(--svg-color--4b4949, #4B4949);
}

.w93bbibjj {
  stop-color: var(--svg-color--3c3c42, #3C3C42);
  stop-opacity: 0;
}

.wcd2kxb8c {
  stop-color: var(--svg-color--fad43b, #FAD43B);
}

.wci1pqi0w {
  stop-color: var(--svg-color--f8606c, #F8606C);
  stop-opacity: 0;
}

.wct_loblq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.62 10.914c-.654 0-1.206.45-1.357 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.woyxclbuf {
  stop-color: var(--svg-color--f83c69, #F83C69);
  stop-opacity: 0;
}

.wz6bzjb_t {
  stop-color: var(--svg-color--ffbc6e, #FFBC6E);
}

.x2nz94bxt {
  stop-color: var(--svg-color--ff5c61, #FF5C61);
}

.xhm3b5b7k {
  stop-color: var(--svg-color--494849, #494849);
  stop-opacity: 0;
}

.xiq09ubck {
  stop-color: var(--svg-color--ff363d, #FF363D);
}

.xj4-9nbvp {
  d: path("M13.826 11.186a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.xnlf7sxhg {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.494 17.85c.02.057.108.171.293.171h.34");
}

.xqjhmh8hm {
  fill-rule: evenodd;
  d: path("M11.869 15.729c-.371-2.278-.321-5.65-.253-7.42c-.335.116-.665.34-.79.717c-.18 1.71-.074 3.853.087 5.844c.205 2.53.733 3.652 2.704 4.09c.708.157 1.528.237 2.35.24h.046c.824-.003 1.686-.076 2.394-.233c1.971-.437 2.5-1.558 2.704-4.09c.161-1.99.268-4.132.087-5.843c-.125-.378-.455-.602-.79-.717c.069 1.769.119 5.141-.252 7.42c-.229 1.155-.845 1.606-1.251 1.752c-.156.056-.292-.074-.292-.24v-1.043c0-.868-.313-1.5-1.336-1.5l-1.31-.008h-1.22c-1.023 0-1.335.633-1.335 1.5v1.043c0 .166-.137.296-.293.24c-.406-.146-1.022-.597-1.25-1.752m4.097-.148h-1.085c-.178.005-.532.135-.532.617v1.156c-.008.148.061.445.399.445h.535c.08.003.27-.07.27-.32v-.186a.47.47 0 1 1 .94 0v.186c0 .25.19.323.27.32l.514.008c.337 0 .406-.297.398-.445v-1.156c0-.482-.354-.612-.531-.618z");
}

.xtuvoccjf {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.466 17.54c.125.15.238.213.407.22c.21.007 1.21-.239 1.613-2.086");
}

.xw_ma5b4i {
  stop-color: var(--svg-color--62bceb, #62BCEB);
  stop-opacity: 0;
}

.xwh8wibwz {
  stop-color: var(--svg-color--f02c36, #F02C36);
}

.y1d9sby0q {
  stop-color: var(--svg-color--df6b6d, #DF6B6D);
  stop-opacity: 0;
}

.y2wq2jfrv {
  cx: 15.9px;
  cy: 6.197px;
  r: 1.507px;
}

.y5-px1btw {
  stop-color: var(--svg-color--ff5b5e, #FF5B5E);
}

.yem538otj {
  stop-color: var(--svg-color--ffdd4f, #FFDD4F);
}

.yh-cclb6t {
  stop-color: var(--svg-color--3da1e6, #3DA1E6);
}

.yqin9d1eu {
  stop-color: var(--svg-color--41c0ff, #41C0FF);
}

.yzq2kjbif {
  stop-color: var(--svg-color--68d2ff, #68D2FF);
}

.z_biw6z0g {
  fill: var(--svg-color--35beff, #35BEFF);
  d: path("m15.613 12.22l-.48 1.81c-.109.366.1.673.47.673h.786c.37 0 .602-.34.494-.7l-.531-1.783c-.114-.394-.62-.394-.739 0");
}

.z-39yxbny {
  stop-color: var(--svg-color--5bb9ea, #5BB9EA);
}

.z1vah_bkx {
  stop-color: var(--svg-color--ff6d85, #FF6D85);
}

.z4v0x3b_g {
  stop-color: var(--svg-color--31a8ff, #31A8FF);
}

.z645iqbrw {
  stop-color: var(--svg-color--5ec2ff, #5EC2FF);
  stop-opacity: 0;
}

.z78gnj88j {
  stop-color: var(--svg-color--ff5b66, #FF5B66);
}

.z8hbz1_-a {
  stop-color: var(--svg-color--ff5b66, #FF5B66);
  stop-opacity: 0;
}

.za5enxahd {
  stop-color: var(--svg-color--cf344c, #CF344C);
}

.zg82anb2t {
  stop-color: var(--svg-color--b4a43e, #B4A43E);
  stop-opacity: 0;
}

.zmgjjlm1s {
  fill: var(--svg-color--201228, #201228);
  fill-rule: evenodd;
  d: path("M11.869 15.729c-.371-2.278-.321-5.65-.253-7.42c-.335.116-.665.34-.79.717c-.18 1.71-.074 3.853.087 5.844c.205 2.53.733 3.652 2.704 4.09c.708.157 1.528.237 2.35.24h.046c.824-.003 1.686-.076 2.394-.233c1.971-.437 2.5-1.558 2.704-4.09c.161-1.99.268-4.132.087-5.843c-.125-.378-.455-.602-.79-.717c.069 1.769.119 5.141-.252 7.42c-.229 1.155-.845 1.606-1.251 1.752c-.156.056-.292-.074-.292-.24v-1.043c0-.868-.313-1.5-1.336-1.5l-1.31-.008h-1.22c-1.023 0-1.335.633-1.335 1.5v1.043c0 .166-.137.296-.293.24c-.406-.146-1.022-.597-1.25-1.752m4.097-.148h-1.085c-.178.005-.532.135-.532.617v1.156c-.008.148.061.445.399.445h.535c.08.003.27-.07.27-.32v-.186a.47.47 0 1 1 .94 0v.186c0 .25.19.323.27.32l.514.008c.337 0 .406-.297.398-.445v-1.156c0-.482-.354-.612-.531-.618z");
}

</style>
