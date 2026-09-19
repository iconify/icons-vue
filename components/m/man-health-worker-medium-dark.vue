<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIR19Oe)" class="ntxrs_b2h"/><path fill="url(#iCVQ2Tb)" class="ntxrs_b2h"/><path fill="url(#iUgxiwB)" class="ntxrs_b2h"/><path fill="url(#idpME7K)" class="ntxrs_b2h"/><path fill="url(#ivio66d)" class="ntxrs_b2h"/><path fill="url(#iuwuDoc)" class="ntxrs_b2h"/><path fill="url(#iie1dhs)" class="ntxrs_b2h"/><path fill="url(#iJ5My0d)" class="fl1040blo"/><path fill="url(#isoCxwS)" class="r-l1aq-vx"/><path fill="url(#iw75Wle)" class="oxs0fcpib"/><path fill="url(#igWgryc)" class="oxs0fcpib"/><path fill="url(#ixiOrTY)" class="oxs0fcpib"/><path fill="url(#ipLrCOc)" class="vi0vvftrl"/><path fill="url(#iSa0l3N)" class="vi0vvftrl"/><path fill="url(#iigM9Rs)" class="vi0vvftrl"/><path fill="url(#ioL9jTb)" class="mv7uucign"/><path fill="url(#iQEXRoc)" class="mv7uucign"/><path fill="url(#iJ5My0d)" class="fl1040blo"/><path fill="url(#isoCxwS)" class="r-l1aq-vx"/><g filter="url(#iXmZjNd)"><path class="w_cydibdd"/></g><g filter="url(#iUNT6Le)"><path fill="url(#ifQPe3b)" class="w9zjpbbcb"/></g><path fill="url(#i4gKT7d)" class="eaotqzbny"/><path fill="url(#iZofmIb)" class="eaotqzbny"/><path fill="url(#irfLs2d)" class="eaotqzbny"/><path fill="url(#iqAa76c)" class="eaotqzbny"/><path fill="url(#iYMzFLe)" class="eaotqzbny"/><path fill="url(#i4dI1jd)" class="eaotqzbny"/><path fill="url(#i4MjAQc)" class="qqmxx4b1u"/><path fill="url(#iUo0yCc)" class="qqmxx4b1u"/><path fill="url(#isa4LJC)" class="qqmxx4b1u"/><path fill="url(#iF0f1Fb)" class="qqmxx4b1u"/><path fill="url(#i5rNZSc)" class="qqmxx4b1u"/><path fill="url(#iJf7Y5U)" class="qqmxx4b1u"/><path fill="url(#iaSLm0b)" class="pxplwkbvh"/><path clip-rule="evenodd" class="je4jwdo_h"/><path fill="url(#i6KYgSt)" clip-rule="evenodd" class="c9wn-bc1q"/><path fill="url(#iALKHRv)" clip-rule="evenodd" class="c9wn-bc1q"/><path fill="url(#iDOT28c)" clip-rule="evenodd" class="c9wn-bc1q"/><path fill="url(#ipVmZZn)" clip-rule="evenodd" class="c9wn-bc1q"/><g filter="url(#iodmLIe)"><path class="iyopi887x"/></g><path fill="url(#i5gZcvd)" class="ykx4dnvge"/><g filter="url(#isPNwkc)"><path fill="url(#iQ7IpCc)" class="lfcxmiwtt"/></g><g filter="url(#iImPZOd)"><path fill="url(#iubAaIb)" clip-rule="evenodd" class="tk-u8dbnk"/></g><g filter="url(#iLJszNc)"><path class="kx7_1acah"/></g><path fill="url(#ijcSC5z)" clip-rule="evenodd" class="m4fya6kqh"/><path fill="url(#ii8clBd)" clip-rule="evenodd" class="m4fya6kqh"/><path fill="url(#iOvZ0Nc)" clip-rule="evenodd" class="f0odhmj8a"/><path fill="url(#iKvl8qC)" clip-rule="evenodd" class="f0odhmj8a"/><g filter="url(#ivVsFIe)"><circle fill="url(#iKWWZsy)" class="ovu0t9v6y"/></g><g filter="url(#i3DPCTc)"><circle fill="url(#iIE7uid)" class="l657egemo"/></g><g filter="url(#i8fMewb)"><circle fill="url(#ilsxzse)" class="uv__1ibad"/><circle fill="url(#iACziYc)" class="uv__1ibad"/></g><g filter="url(#iSAOuiR)"><circle class="hpo7-gvwu"/><circle fill="url(#iUY0bbH)" class="b157-nbsl"/><circle fill="url(#iDUKhsh)" class="b157-nbsl"/></g><g filter="url(#iUT2jNQ)"><path fill="url(#io5yDsU)" class="pjkntud0y"/><path fill="url(#iZMtPUg)" class="pjkntud0y"/><path fill="url(#iCQ0lkc)" class="pjkntud0y"/></g><path fill="url(#iPOzXTc)" class="sceds7b0r"/><path fill="url(#iG5lDHS)" class="sceds7b0r"/><path fill="url(#iCmCcxd)" class="sceds7b0r"/><path fill="url(#iGOYUmb)" class="sceds7b0r"/><path fill="url(#i20Nyye)" class="sceds7b0r"/><g filter="url(#ipPeCPb)"><path fill="url(#iS12b5d)" class="eus0k4_9u"/></g><g filter="url(#iAFpHPd)"><path class="dl0qaibbc"/><path fill="url(#iK7N8yd)" class="oj17yo5zz"/><path fill="url(#ivtdnJN)" class="oj17yo5zz"/><path fill="url(#iJ2yQUd)" class="oj17yo5zz"/><path fill="url(#iYRXWZb)" class="oj17yo5zz"/></g><g filter="url(#ixTVdRd)"><path class="h6iu31fiw"/></g><g filter="url(#ipsoQVy)"><path class="ng_yyqbhi"/><path fill="url(#iea40uc)" class="exilg7b0t"/><path fill="url(#illMLje)" class="exilg7b0t"/><path fill="url(#ipl96rc)" class="exilg7b0t"/><path fill="url(#ifmi48d)" class="exilg7b0t"/></g><path fill="url(#idAGMwc)" class="exilg7b0t"/><path stroke="url(#iDyowpe)" class="d703nhbhj"/><g filter="url(#iysO2me)"><path class="hiqcasbcj"/><path fill="url(#ik1udKb)" class="xjkn5whvs"/></g><g filter="url(#inaEVtd)"><path class="x6b8oabpr"/><path fill="url(#ijqDVle)" class="fhfka3b-p"/></g><path class="y5-eiu5xl"/><path fill="url(#ilxMnzO)" class="v4jtmyb8z"/><path class="n_twbcb5d"/><g filter="url(#ilJ8uxc)"><path class="qv-t6kd2g"/><path fill="url(#incftId)" class="f-r6hcbbh"/></g><g filter="url(#iWz4Fpc)"><path fill="url(#ivri9rb)" class="gkh2e5z9f"/></g><path class="ppgnquqsk"/><path fill="url(#i88kDac)" class="h-p4p5cqu"/><path class="ekt1k6qhx"/><g filter="url(#ii3aekd)"><path fill="url(#inuYW1m)" class="jr837yk7p"/></g><g filter="url(#iVII32b)"><ellipse transform="rotate(-27.914 13.494 9.893)" class="votd779ef"/><ellipse fill="url(#iwCZ0Mo)" transform="rotate(-27.914 13.494 9.893)" class="rffjydzfq"/></g><g filter="url(#iHhXxtY)"><path stroke="url(#iVbNuNb)" class="x2i1zj-5a"/></g><g filter="url(#iOs06pY)"><path stroke="url(#i8fe9Me)" class="q6um7wbeo"/></g><g filter="url(#i5oN6Fc)"><path stroke="url(#iXQsNiY)" class="h9z41eb5f"/></g><defs><radialGradient id="iIR19Oe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.22 23.89)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="ivio66d" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.158 8.155)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="iuwuDoc" cx="0" cy="0" r="1" gradientTransform="rotate(77.152 -6.29 23.559)scale(3.65398 4.0429)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="iie1dhs" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.992 29.96)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="iw75Wle" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.358 24.672)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="igWgryc" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.686 12.324)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="ipLrCOc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.256 21.922)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="iSa0l3N" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.569 20.297)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="ioL9jTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16.026 18.516)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="lc4rehg1n"/><stop offset="1" class="h1aoh3b9a"/></radialGradient><radialGradient id="iQEXRoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.39 30.453)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="stn4eib-z"/><stop offset="1" class="z99vy1qwj"/></radialGradient><radialGradient id="iqAa76c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.164 18.078)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iYMzFLe" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.472 26.52)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="i4dI1jd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.164 24.828)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="i4MjAQc" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.396 11.263)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="iUo0yCc" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.155 24.883)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="iF0f1Fb" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.326 19.453)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="i5rNZSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.124 18.282)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iJf7Y5U" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -16.974 24.234)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="iaSLm0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.72628 3.2225 0 16.01 18.68)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="w5eea1btf"/><stop offset=".577" class="jdrs_egbb"/><stop offset="1" class="cctilfb7f"/></radialGradient><radialGradient id="iALKHRv" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.53 16.344)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="iDOT28c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.608 20)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="ipVmZZn" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.841 12.182)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="i5gZcvd" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.178 18.053)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="iQ7IpCc" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.274 25.868)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="ii8clBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.155 23.532)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="iKWWZsy" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.528 10.671)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iACziYc" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 26.531 -27.2)scale(1.02361 1.16832)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iUY0bbH" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.68 11.493)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iDUKhsh" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.721 10.671)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iZMtPUg" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.3 9.398)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iCQ0lkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.738 9.532)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iCmCcxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8549 -12.0201 0 15.65 8.895)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="iGOYUmb" cx="0" cy="0" r="1" gradientTransform="rotate(-146.07 12.64 5.213)scale(2.07148 1.17905)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="i20Nyye" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.54454 .34491 1.64288 12.313 17.625)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iK7N8yd" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .38451 20.301 6.56)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="ivtdnJN" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.657 4.8)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iJ2yQUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.952 2.062)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iYRXWZb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.497 8.886)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="ifmi48d" cx="0" cy="0" r="1" gradientTransform="rotate(90 2 14.28)scale(.19709 .63318)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ik1udKb" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 18.397 8.585)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="ijqDVle" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.72 -3.572)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="ilxMnzO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.133 9.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="incftId" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.905 10.073)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i88kDac" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.766 9.988)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iwCZ0Mo" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.764 -1.53)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iCVQ2Tb" x1="23.335" x2="23.022" y1="24.571" y2="24.571" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iUgxiwB" x1="8.756" x2="9.092" y1="24.571" y2="24.571" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="idpME7K" x1="16.202" x2="16.202" y1="30.922" y2="29.11" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iJ5My0d" x1="8.841" x2="23.217" y1="15.399" y2="15.399" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="isoCxwS" x1="8.841" x2="23.217" y1="15.369" y2="15.369" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ixiOrTY" x1="7.02" x2="7.02" y1="30.735" y2="29.275" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iigM9Rs" x1="22.692" x2="23.47" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="ifQPe3b" x1="16.202" x2="23.827" y1="26.953" y2="19.36" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="i4gKT7d" x1="21.916" x2="16.8" y1="18.349" y2="23.867" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="iZofmIb" x1="20.07" x2="19.912" y1="15.63" y2="17.693" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="irfLs2d" x1="17.608" x2="18.764" y1="18.875" y2="19.36" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="isa4LJC" x1="12.296" x2="12.624" y1="23.172" y2="22.813" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="i6KYgSt" x1="20.335" x2="19.663" y1="23.641" y2="23.657" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="iubAaIb" x1="12.23" x2="12.23" y1="19.839" y2="28.422" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="ijcSC5z" x1="9.54" x2="10.434" y1="25.238" y2="25.238" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iOvZ0Nc" x1="13.913" x2="14.585" y1="25.248" y2="25.248" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iKvl8qC" x1="14.975" x2="14.733" y1="24.766" y2="24.766" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="iIE7uid" x1="11.199" x2="10.558" y1="10.95" y2="10.95" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="ilsxzse" x1="21.809" x2="20.99" y1="9.578" y2="12.117" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="io5yDsU" x1="19.991" x2="12.348" y1="11.061" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iPOzXTc" x1="10.551" x2="12.434" y1="13.759" y2="13.692" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iG5lDHS" x1="20.821" x2="19.764" y1="12.921" y2="12.82" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iS12b5d" x1="15.42" x2="23.572" y1="8.073" y2="5.154" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iea40uc" x1="15.087" x2="16.026" y1="11.72" y2="11.72" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="illMLje" x1="16.891" x2="15.864" y1="12.043" y2="12.029" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="ipl96rc" x1="16.146" x2="16.146" y1="12.786" y2="12.213" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="idAGMwc" x1="16.078" x2="16.078" y1="12.828" y2="12.661" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iDyowpe" x1="14.914" x2="15.349" y1="14.403" y2="13.715" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ivri9rb" x1="18.911" x2="18.597" y1="10.042" y2="10.236" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inuYW1m" x1="14.51" x2="14.196" y1="10.042" y2="10.236" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVbNuNb" x1="18.927" x2="18.506" y1="7.901" y2="7.041" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="i8fe9Me" x1="13.617" x2="12.427" y1="7.773" y2="7.274" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iXQsNiY" x1="11.285" x2="11.285" y1="5.756" y2="7.915" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><filter id="iXmZjNd" width="7.147" height="11.557" x="9.055" y="15.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".5"/></filter><filter id="iUNT6Le" width="7.147" height="11.557" x="15.949" y="15.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".5"/></filter><filter id="iodmLIe" width="3.699" height="3.699" x="17.02" y="23.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".375"/></filter><filter id="isPNwkc" width="1.42" height="1.42" x="18.991" y="24.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="iImPZOd" width="5.381" height="7.171" x="9.54" y="19.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="iLJszNc" width="5.3" height="6.89" x="9.606" y="19.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".15"/></filter><filter id="ivVsFIe" width="3.542" height="3.342" x="9.528" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="i3DPCTc" width="2.992" height="2.992" x="9.703" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".25"/></filter><filter id="i8fMewb" width="3.592" height="3.592" x="19.051" y="8.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="iSAOuiR" width="2.992" height="2.992" x="19.226" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".25"/></filter><filter id="iUT2jNQ" width="10.383" height="12.189" x="10.789" y="5.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="ipPeCPb" width="8.25" height="7.07" x="14.122" y="3.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation="1"/></filter><filter id="iAFpHPd" width="12.614" height="8.551" x="9.645" y="1.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="ixTVdRd" width="3.262" height="4.184" x="14.082" y="9.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".375"/></filter><filter id="ipsoQVy" width="2.379" height="3.184" x="14.762" y="9.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".125"/></filter><filter id="iysO2me" width="2.982" height="1.874" x="17.135" y="7.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="inaEVtd" width="2.982" height="1.874" x="11.982" y="7.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24149"/></filter><filter id="ilJ8uxc" width=".787" height=".697" x="17.398" y="9.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".05"/></filter><filter id="iWz4Fpc" width=".892" height=".914" x="18.239" y="9.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".1"/></filter><filter id="ii3aekd" width=".987" height="1.041" x="13.793" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".1"/></filter><filter id="iVII32b" width=".914" height=".705" x="13.037" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".05"/></filter><filter id="iHhXxtY" width="3.101" height="1.682" x="16.989" y="7.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".25"/></filter><filter id="iOs06pY" width="3.179" height="1.739" x="11.764" y="7.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".25"/></filter><filter id="i5oN6Fc" width="1.008" height="2.271" x="10.781" y="5.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24149" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-health-worker-medium-dark" /></template>
<style>
.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.b157-nbsl {
  cx: 20.722px;
  cy: 10.671px;
  r: 0.996px;
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.c9wn-bc1q {
  fill-rule: evenodd;
  d: path("M15.96 15.08a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 0 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.cctilfb7f {
  stop-color: var(--svg-color--3b2533, #3B2533);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d703nhbhj {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.589 13.43c.393.206.863.324 1.363.324c.505 0 .97-.118 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.989-.281l2.948.253m-2.948-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.253m3.21.028l-.042-.028m.042.028l-.042-.028m.042.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.339-1.585-.847m-.041.028l.041-.028m-.041.028l.041-.028");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dl0qaibbc {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.775 4.187l.43.214c.751.373 1.18 1.227 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.442c.044-.433-.032-.565-.43-.96c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.481-.322.748c.053.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.533l-.59-3.042c-.108-.855.321-1.709 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.015c.591-.533 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eaotqzbny {
  d: path("M16.675 21.651c-.262.516-.262.941-.262 1.306v2.99c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.754-.83a.23.23 0 0 1 .13-.38l.782-.14a.23.23 0 0 0 .189-.25l-.188-2.058a.25.25 0 0 0-.113-.187a10.5 10.5 0 0 0-2.425-1.134a.3.3 0 0 0-.04.08z");
}

.ekt1k6qhx {
  fill: var(--svg-color--000, #000);
  d: path("M14.275 10.404a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.eus0k4_9u {
  d: path("m19.92 5.041l-3.081 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.exilg7b0t {
  d: path("m15.57 10.385l-.533 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.f-r6hcbbh {
  d: path("M18.07 9.7c.063.085-.07.189-.221.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.135.388-.05");
}

.f0odhmj8a {
  fill-rule: evenodd;
  d: path("M14.921 23.69v2.47c0 .36-.29.65-.65.65h-.58v-.981h.249v-2.14z");
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fhfka3b-p {
  d: path("m12.175 7.949l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.211a2.83 2.83 0 0 1 1.494-.158a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
}

.fl1040blo {
  d: path("M16.38 15.37c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gkh2e5z9f {
  d: path("M18.93 10.286a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-p4p5cqu {
  d: path("M13.764 9.51a.893.893 0 0 0-.861 1.13h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.h1aoh3b9a {
  stop-color: var(--svg-color--0a4b92, #0A4B92);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.h6iu31fiw {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.676 10.549l-.82 1.701c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.499-1.701c-.107-.377-.283-.377-.395 0");
}

.h9z41eb5f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.415 5.855v.898c-.008.15-.07.482-.259.623");
}

.hiqcasbcj {
  fill: var(--svg-color--352827, #352827);
  d: path("M19.675 7.948h-.001l-.002-.002l-.005-.004l-.012-.01a2 2 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.84 2.84 0 0 0-1.494-.158a.534.534 0 0 0 .167 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .679-.825");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hpo7-gvwu {
  cx: 20.722px;
  cy: 10.671px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.iyopi887x {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.87 26.919a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.jdrs_egbb {
  stop-color: var(--svg-color--55383b, #55383B);
}

.je4jwdo_h {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M15.96 15.08a3.24 3.24 0 0 0-3.239 3.24v2.15h-.981v-2.15a4.22 4.22 0 0 1 8.441 0v7.12H19.2v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jr837yk7p {
  d: path("M14.58 10.299c0-.289-.235-.481-.299-.54l-.288.28l.177.361z");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kx7_1acah {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.216 26.253h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l657egemo {
  cx: 11.199px;
  cy: 10.671px;
  r: 0.996px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lc4rehg1n {
  stop-color: var(--svg-color--3272ac, #3272AC);
}

.lfcxmiwtt {
  d: path("M19.7 26.14a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m4fya6kqh {
  fill-rule: evenodd;
  d: path("M9.54 26.15v-2.47h.981v2.14h.25v.98h-.58a.65.65 0 0 1-.651-.65");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mv7uucign {
  d: path("M16.518 22.474c0-.04-.01-.203 0-.243l2.663-6.291c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.361c.01.03.054.05.054.09l.056 3.599h.01v3.97h.79v-3.97l.078-3.415z");
}

.n_twbcb5d {
  fill: var(--svg-color--000, #000);
  d: path("M17.623 10.404a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.ng_yyqbhi {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.57 10.385l-.533 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.7c-.114-.378-.646-.378-.765 0");
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.ntxrs_b2h {
  d: path("M16.012 15.37c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38V18.18a10.54 10.54 0 0 0-7.17-2.81");
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oj17yo5zz {
  d: path("m20.775 4.187l.43.214c.751.373 1.18 1.227 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.442c.044-.433-.032-.565-.43-.96c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534v.854c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.481-.322.748c.053.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.533l-.59-3.042c-.108-.855.321-1.709 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.015c.591-.533 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.053 2.363.534l.805.8c.215.268.483.428.805.588");
}

.ovu0t9v6y {
  cx: 11.199px;
  cy: 10.671px;
  r: 1.671px;
}

.oxs0fcpib {
  d: path("m5.952 22.73l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67V18.21a10.56 10.56 0 0 0-2.85 4.52");
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pjkntud0y {
  d: path("m10.847 10.058l.05.001s-.054-.854-.108-1.441c0-.267.107-.587.322-.748l.161-.16c.268-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534v.854c0 .32.16.64.376.854c.502.352.47.546.43.961c-.055.534-.108 1.442-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.214 3.005H14.37c-1.714 0-3.053-1.234-3.213-3.005z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppgnquqsk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.557 9.239c-.654 0-1.206.45-1.357 1.06a.274.274 0 0 0 .269.34H14.7a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.373-1.128");
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pxplwkbvh {
  d: path("M16.01 18.68a2.1 2.1 0 0 1-2.1-2.1V15.2h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.q6um7wbeo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.39 8.323c.327-.29 1.042-.594 1.928-.453");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qqmxx4b1u {
  d: path("M15.396 21.651c.262.516.262.941.262 1.306v2.99c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.118-.13.05-.35-.13-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.058a.25.25 0 0 1 .113-.187a10.5 10.5 0 0 1 2.426-1.134a.3.3 0 0 1 .04.08z");
}

.qv-t6kd2g {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.07 9.7c.063.085-.07.189-.221.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.16-.359c.15-.113.325-.135.388-.05");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-l1aq-vx {
  d: path("M16.05 15.37h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rffjydzfq {
  cx: 13.494px;
  cy: 9.893px;
  rx: 0.39px;
  ry: 0.197px;
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.sceds7b0r {
  d: path("M10.789 8.618c0-.267.107-.587.322-.748l.161-.16c.268-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534v.854c0 .32.16.64.376.854c.502.352.47.546.43.961c-.055.534-.108 1.442-.108 1.442h.018l-.266 3.962c-.16 1.77-1.553 3.005-3.214 3.005H14.37c-1.714 0-3.053-1.234-3.213-3.005c-.14-1.819-.201-3.642-.367-5.457");
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.stn4eib-z {
  stop-color: var(--svg-color--3865b8, #3865B8);
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.tk-u8dbnk {
  fill-rule: evenodd;
  d: path("M12.23 20.82a1.71 1.71 0 0 0-1.709 1.71v3.299h.67a.49.49 0 1 1 0 .981h-1a.65.65 0 0 1-.651-.65v-3.63a2.69 2.69 0 0 1 5.381 0v3.63c0 .36-.29.65-.65.65h-.93a.49.49 0 0 1 0-.981h.599v-3.3a1.71 1.71 0 0 0-1.71-1.709");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uv__1ibad {
  cx: 20.722px;
  cy: 10.671px;
  r: 1.671px;
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v4jtmyb8z {
  d: path("M18.135 9.51a.893.893 0 0 1 .86 1.13H17.27a.897.897 0 0 1 .865-1.129");
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.vi0vvftrl {
  d: path("M26.852 27.93c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.votd779ef {
  cx: 13.494px;
  cy: 9.893px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_cydibdd {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.232 20.114l.732.13a.213.213 0 0 1 .121.352l-.705.77a.216.216 0 0 0 .01.296l4.506 4.599c.111.111.306.037.306-.12v-3.33c0-.036-.01-.064-.019-.101l-2.54-5.888a.15.15 0 0 0-.037-.065a9.7 9.7 0 0 0-2.365 1.122l-.185 2.003a.214.214 0 0 0 .176.232");
}

.w_l8deb9l {
  stop-color: var(--svg-color--746992, #746992);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.w5eea1btf {
  stop-color: var(--svg-color--5b3747, #5B3747);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w9zjpbbcb {
  d: path("m21.919 20.114l-.733.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.009.296l-4.506 4.599c-.111.111-.306.037-.306-.12v-3.33c0-.036.01-.064.019-.101l2.54-5.888a.15.15 0 0 1 .037-.065c.844.27 1.641.65 2.365 1.122l.185 2.003a.214.214 0 0 1-.176.232");
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.x2i1zj-5a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.614 7.804c.43-.076 1.27-.054 1.851.398");
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x6b8oabpr {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.175 7.949l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.211a2.83 2.83 0 0 1 1.494-.158a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xjkn5whvs {
  d: path("M19.675 7.948h-.001l-.002-.002l-.005-.004l-.012-.01a2 2 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.84 2.84 0 0 0-1.494-.158a.534.534 0 0 0 .167 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .679-.825");
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y5-eiu5xl {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.342 9.239c.653 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ykx4dnvge {
  d: path("M19.7 26.69a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z99vy1qwj {
  stop-color: var(--svg-color--3865b8, #3865B8);
  stop-opacity: 0;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

</style>
