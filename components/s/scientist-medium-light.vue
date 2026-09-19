<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#iF2xL7c)" class="ox0t0tbyw"/><path fill="url(#iJex2Eb)" class="ox0t0tbyw"/><path fill="url(#i0x9rSc)" class="lzxh7zbhd"/><path fill="url(#iqijBdb)" class="lzxh7zbhd"/><path fill="url(#iTXvIeu)" class="lzxh7zbhd"/><path fill="url(#iIr2zNb)" class="lzxh7zbhd"/><path fill="url(#idCIDmb)" class="vzhel1b-t"/><path fill="url(#icbfzYc)" class="vzhel1b-t"/><path fill="url(#iYuCe2d)" class="vzhel1b-t"/><path fill="url(#iDWkYOd)" class="vzhel1b-t"/><g filter="url(#i3Dhscb)"><path fill="url(#iPm6Z8c)" class="efonc5hef"/></g><g filter="url(#ijbizfd)"><path fill="url(#iBCBk6c)" class="afds29lll"/></g><g filter="url(#i48gICd)"><path fill="url(#ic5ISlz)" class="qioyo8boa"/></g><path fill="url(#iXMjlYd)" class="q__as4b2h"/><path fill="url(#iuMA8qd)" class="q__as4b2h"/><path fill="url(#i9zEBle)" class="q__as4b2h"/><path fill="url(#iL0OQae)" class="q__as4b2h"/><path fill="url(#iU0Zedb)" class="q__as4b2h"/><path fill="url(#ikhTrkd)" class="mx_0g-cbx"/><path fill="url(#iiUj10d)" class="mx_0g-cbx"/><path fill="url(#iYC5CUv)" class="mx_0g-cbx"/><path fill="url(#isL6aLe)" class="mx_0g-cbx"/><path fill="url(#iKGtVBM)" class="afds29lll"/><path fill="url(#iEtcdkc)" class="lceri-vrq"/><path fill="url(#i5KOZnc)" class="lceri-vrq"/><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#isyPAvc)" class="ftb0dac9p"/><path fill="url(#iwphR3p)" class="ftb0dac9p"/><path fill="url(#iYPzcfq)" class="gip5y3buk"/><path fill="url(#iBS77Ec)" class="gip5y3buk"/><path fill="url(#ixdtEFe)" class="a0q7e-rbb"/><path fill="url(#iIN33ps)" class="a0q7e-rbb"/><path fill="url(#ilUA1Ec)" class="a0q7e-rbb"/><g filter="url(#iAFWNjd)"><rect class="b_wzmzbwq"/><rect fill="url(#in80oDb)" class="tkgx_8bnk"/><rect fill="url(#iEsINHM)" class="tkgx_8bnk"/><rect fill="url(#imH7Vqd)" class="tkgx_8bnk"/></g><path fill="url(#itN89Zb)" class="a124lcdye"/><path fill="url(#iWn83Lb)" class="a124lcdye"/><path fill="url(#i6aufrd)" class="a124lcdye"/><path fill="url(#iqwFqNS)" class="a124lcdye"/><path fill="url(#iiRMWBW)" class="h-y9sqzgz"/><path fill="url(#iwOSsec)" class="j68h5l-_g"/><g filter="url(#icx4Vsc)"><path fill="url(#ik428Sp)" class="ryx370bez"/><path fill="url(#iIkJNju)" class="ryx370bez"/><path fill="url(#isMLOpc)" class="ryx370bez"/><path fill="url(#iEn9SWc)" class="ryx370bez"/><path fill="url(#iNrKlcd)" class="ryx370bez"/></g><g filter="url(#ise0xFe)"><path stroke="url(#iKnhXXV)" class="ql-d_bcrc"/></g><g filter="url(#iw0G27O)"><path stroke="url(#iqCe1KD)" class="dkh21gill"/></g><g filter="url(#ihq1w3b)"><path stroke="url(#iZYxbyI)" class="c7dra70nl"/></g><path fill="url(#iyNZ9Uc)" class="i-_q9txbo"/><path fill="url(#iKvQC2c)" class="vwrtm3bab"/><path fill="url(#iNUiQLb)" class="vwrtm3bab"/><path fill="url(#iKvQC2c)" class="vwrtm3bab"/><path fill="url(#iNUiQLb)" class="vwrtm3bab"/><g filter="url(#ik2P4Ld)"><path fill="url(#idqBiee)" class="yaf5ccsht"/></g><path fill="url(#iBbQY6b)" class="yaf5ccsht"/><path fill="url(#iFMUv2d)" class="yaf5ccsht"/><path fill="url(#i6VYgLL)" class="yaf5ccsht"/><path fill="url(#iyMNpzY)" class="yaf5ccsht"/><path fill="url(#iV9rdLe)" class="yaf5ccsht"/><path fill="url(#i2r0DZb)" class="yaf5ccsht"/><path fill="url(#ihw7jDe)" class="yaf5ccsht"/><path fill="url(#iFkePpD)" class="yaf5ccsht"/><g filter="url(#incrHIe)"><path class="kvxkb4k-i"/></g><g filter="url(#iqNhlSd)"><path fill="url(#iBnnCZM)" class="vkttrlbcf"/><path fill="url(#iWhUnSv)" class="vkttrlbcf"/><path fill="url(#idjBzIP)" class="vkttrlbcf"/><path fill="url(#ihh7MUc)" class="vkttrlbcf"/></g><g filter="url(#ilP6aLd)"><path stroke="url(#ioBsqDc)" class="o26echxgv"/></g><path fill="url(#imLFKpc)" class="ht7we4nuf"/><g filter="url(#iuWia7d)"><path fill="url(#ikPWaJe)" class="oxearsb0s"/><path fill="url(#iwzg9Je)" class="oxearsb0s"/><path fill="url(#i8dnfzc)" class="oxearsb0s"/><path fill="url(#i2CQOtP)" class="oxearsb0s"/><path fill="url(#iXsg5qb)" class="oxearsb0s"/></g><g filter="url(#i3JNwQb)"><path class="wmrb13bye"/></g><g filter="url(#iBwictb)"><path class="zaql8vbut"/></g><g filter="url(#iCp9Jdc)"><path fill="url(#iQFbAPd)" class="koh97ebar"/><path fill="url(#iiiLuRT)" class="koh97ebar"/></g><g filter="url(#iTJOePe)"><path fill="url(#iJsPHec)" class="eafq37b6z"/><path fill="url(#iWSkAkT)" class="eafq37b6z"/><path fill="url(#iHRRyMP)" class="eafq37b6z"/><path fill="url(#i6RkJGe)" class="eafq37b6z"/><path fill="url(#idP5uTb)" class="eafq37b6z"/><path fill="url(#ibxjeoE)" class="eafq37b6z"/></g><path class="yae6yabyn"/><path fill="url(#iZtOnGb)" class="a5tc3xwyp"/><path class="x6zej0-dg"/><g filter="url(#iv2Y2bd)"><path class="h9gt7l15p"/><path fill="url(#it28GHd)" class="y83_mxbbk"/></g><g filter="url(#ichp3ld)"><path fill="url(#iJzTwQd)" class="jr9hdpl0f"/></g><path class="gmjg4ccxy"/><path fill="url(#i98Kfde)" class="coxmzuo0a"/><path class="nzcw4eb0y"/><g filter="url(#iYlbxAe)"><path fill="url(#iasvD4d)" class="sc_pn_b9h"/></g><g filter="url(#iKSyfKe)"><ellipse transform="rotate(-27.914 12.972 10.113)" class="sdqhb92yx"/><ellipse fill="url(#ijRswUc)" transform="rotate(-27.914 12.972 10.113)" class="koptfs8yh"/></g><path fill="url(#i8FDZzz)" class="bo1avib2v"/><path fill="url(#iJXrOBd)" class="bo1avib2v"/><path fill="url(#ixc8yqb)" class="bo1avib2v"/><path fill="url(#i8d2rRc)" class="ualev6bga"/><path fill="url(#igV196P)" class="ualev6bga"/><g filter="url(#iMnh2kb)"><path class="wz4pmowzu"/></g><g filter="url(#iWdRrsd)"><path class="s1achebfe"/></g><g filter="url(#iqGoxrz)"><path class="d0l9e5bir"/></g><g filter="url(#iLlayvc)"><path class="dotkg_5jb"/></g><g filter="url(#iga9dAb)" class="z4n2hhy8u"><path fill="url(#it6BbSd)" class="xo2zgxulc"/></g><g filter="url(#iKOiKDd)"><path clip-rule="evenodd" class="oa6-9zbfy"/></g><defs><radialGradient id="iF2xL7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.316)" gradientUnits="userSpaceOnUse"><stop class="e2ig5yb1x"/><stop offset="1" class="rsfdnufmx"/></radialGradient><radialGradient id="iJex2Eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.316)" gradientUnits="userSpaceOnUse"><stop class="eol9ugodk"/><stop offset="1" class="e080jybbb"/></radialGradient><radialGradient id="i0x9rSc" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.56)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="hy6proxed"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iIr2zNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.41)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="idCIDmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.285)" gradientUnits="userSpaceOnUse"><stop class="lj5m7ucmi"/><stop offset="1" class="d3a6h5dbs"/></radialGradient><radialGradient id="icbfzYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.535)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iBCBk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.91)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iXMjlYd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.691)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iuMA8qd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.307 -.255)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="i9zEBle" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 15.988)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="xpzhm0iru"/><stop offset="1" class="jqs3afbfy"/></radialGradient><radialGradient id="ikhTrkd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.112)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iYC5CUv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.968)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iKGtVBM" cx="0" cy="0" r="1" gradientTransform="matrix(-1 2.84375 -3.2172 -1.13131 12.552 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="fbqio7b7r"/><stop offset="1" class="txsyviqti"/></radialGradient><radialGradient id="iEtcdkc" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.879)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="isyPAvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92264 -3.05629 0 15.426 17.172)" gradientUnits="userSpaceOnUse"><stop class="fdlwvrlzb"/><stop offset="1" class="otwtgescx"/></radialGradient><radialGradient id="iwphR3p" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.45312 -1.20313 0 13.666 16.765)" gradientUnits="userSpaceOnUse"><stop class="k0qhydbjb"/><stop offset="1" class="w3-o4ac4j"/></radialGradient><radialGradient id="iYPzcfq" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03943 1.39355 -1.36898 -2.00347 27.808 23.62)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="iBS77Ec" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.466)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="ilUA1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.378)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="in80oDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.066)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iEsINHM" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.918)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="imH7Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.277)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iqwFqNS" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.222)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iIkJNju" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.292)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="isMLOpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.587)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iEn9SWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.837)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iNrKlcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.188)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iyNZ9Uc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 20.885 11.635)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iKvQC2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 9.878 11.918)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iNUiQLb" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.463 12.058)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="idqBiee" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.233 10.86)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iFMUv2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.2204 -10.9481 0 15.864 4.689)" gradientUnits="userSpaceOnUse"><stop offset=".779" class="ibj3x4n2f"/><stop offset=".957" class="dpepzs4dm"/></radialGradient><radialGradient id="i6VYgLL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 17.873 9.74)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iyMNpzY" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.149 -1.455)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iV9rdLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 10.545 11.244)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="i2r0DZb" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 9.573 7.858)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="ihw7jDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.272 14.932)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="iFkePpD" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.384 5.478)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="ioBsqDc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.224 -5.128)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="imLFKpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.426 14.399)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iwzg9Je" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 10.196 9.278)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="i8dnfzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 20.286 9.278)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="i2CQOtP" cx="0" cy="0" r="1" gradientTransform="matrix(-3.2517 -1.24034 .66056 -1.73174 19.533 3)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="iXsg5qb" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 14.52 1.409)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="iQFbAPd" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.59 2.797)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iiiLuRT" cx="0" cy="0" r="1" gradientTransform="matrix(3.21817 -5.09544 5.64523 3.5654 9.995 7.61)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iJsPHec" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 19.046 4.011)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iWSkAkT" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 12.759 -1.611)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="iHRRyMP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 19.934 8.316)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="i6RkJGe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.22 3.895)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="idP5uTb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 18.878 3.77)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="ibxjeoE" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.552 7.147)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iZtOnGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 17.608 10.209)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="it28GHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.38 10.293)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i98Kfde" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.244 10.209)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ijRswUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 12.958 10.428)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJXrOBd" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.043 9.958)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ixc8yqb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.404 10.502)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="igV196P" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.64 4.918)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><linearGradient id="ivWcDIe" x1="8.23" x2="22.659" y1="15.296" y2="15.296" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqijBdb" x1="11.239" x2="11.239" y1="30.41" y2="29.097" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iTXvIeu" x1="15.177" x2="14.208" y1="29.097" y2="29.097" gradientUnits="userSpaceOnUse"><stop offset=".129" class="dx1e6jb0z"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iYuCe2d" x1="19.74" x2="19.74" y1="30.41" y2="29.097" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iDWkYOd" x1="15.802" x2="16.505" y1="27.972" y2="27.972" gradientUnits="userSpaceOnUse"><stop class="bx23o8bkx"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iPm6Z8c" x1="10.677" x2="12.896" y1="17.941" y2="24.629" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="ic5ISlz" x1="20.45" x2="18.099" y1="18.97" y2="23.671" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iL0OQae" x1="18.958" x2="17.552" y1="24.097" y2="22.597" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iU0Zedb" x1="17.146" x2="17.974" y1="18.878" y2="19.222" gradientUnits="userSpaceOnUse"><stop offset=".081" class="ea_0ewlyw"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="iiUj10d" x1="6.567" x2="6.567" y1="30.352" y2="29.218" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="isL6aLe" x1="8.38" x2="7.935" y1="29.386" y2="29.384" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="i5KOZnc" x1="22.753" x2="23.162" y1="27.66" y2="27.644" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ixdtEFe" x1="23.825" x2="26.529" y1="20.847" y2="20.847" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iIN33ps" x1="26.529" x2="26.18" y1="20.832" y2="20.832" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="itN89Zb" x1="26.529" x2="25.177" y1="23.16" y2="23.16" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iWn83Lb" x1="26.529" x2="26.129" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="i6aufrd" x1="23.696" x2="24.227" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="iiRMWBW" x1="24.782" x2="23.892" y1="21.8" y2="21.8" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iwOSsec" x1="24.782" x2="23.892" y1="23.582" y2="23.582" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="ik428Sp" x1="27.165" x2="23.137" y1="28.05" y2="28.05" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="id19t5fes"/></linearGradient><linearGradient id="iKnhXXV" x1="23.754" x2="25.463" y1="26.068" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iqCe1KD" x1="23.676" x2="25.385" y1="27.373" y2="27.373" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iZYxbyI" x1="23.754" x2="25.463" y1="28.677" y2="28.677" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iBbQY6b" x1="20.583" x2="16.23" y1="12.545" y2="12.545" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iBnnCZM" x1="15.426" x2="16.28" y1="11.842" y2="11.842" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iWhUnSv" x1="14.353" x2="15.427" y1="11.687" y2="11.746" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="idjBzIP" x1="15.426" x2="15.426" y1="12.241" y2="13.093" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="ihh7MUc" x1="15.426" x2="15.426" y1="9.993" y2="10.413" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ikPWaJe" x1="20.789" x2="10.665" y1="5.197" y2="5.197" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iJzTwQd" x1="18.386" x2="18.072" y1="10.263" y2="10.456" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iasvD4d" x1="13.988" x2="13.674" y1="10.263" y2="10.456" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8FDZzz" x1="21.862" x2="20.655" y1="10.024" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="i8d2rRc" x1="9.576" x2="11.034" y1="10.728" y2="10.601" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="it6BbSd" x1="10.588" x2="22.177" y1="9.727" y2="9.727" gradientUnits="userSpaceOnUse"><stop class="aetlj_buy"/><stop offset=".115" class="yl8r25bpm"/><stop offset=".257" class="yl8r25bpm"/><stop offset=".917" class="pusr6ob-i"/></linearGradient><filter id="i3Dhscb" width="7.023" height="11.703" x="8.591" y="15.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".375"/></filter><filter id="ijbizfd" width="5.673" height="10.453" x="9.475" y="15.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/></filter><filter id="i48gICd" width="6.388" height="10.529" x="15.499" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".375"/></filter><filter id="iAFWNjd" width="4.008" height=".781" x="23.173" y="18.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/></filter><filter id="icx4Vsc" width="4.468" height="5.556" x="23.137" y="24.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/></filter><filter id="ise0xFe" width="2.097" height=".3" x="23.604" y="25.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".05"/></filter><filter id="iw0G27O" width="2.097" height=".3" x="23.526" y="27.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".05"/></filter><filter id="ihq1w3b" width="2.097" height=".3" x="23.604" y="28.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".05"/></filter><filter id="ik2P4Ld" width="10.97" height="12.542" x="10.363" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2175" result="effect2_innerShadow_4002_2175"/></filter><filter id="incrHIe" width="3.754" height="4.824" x="13.28" y="9.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".5"/></filter><filter id="iqNhlSd" width="2.077" height="3.1" x="14.387" y="9.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".05"/></filter><filter id="ilP6aLd" width="3.718" height="1.573" x="13.566" y="13.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".05"/></filter><filter id="iuWia7d" width="12.873" height="8.357" x="8.989" y="1.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2175" result="effect2_innerShadow_4002_2175"/></filter><filter id="i3JNwQb" width="2.339" height="1.19" x="16.981" y="7.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/></filter><filter id="iBwictb" width="2.339" height="1.176" x="11.725" y="7.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/></filter><filter id="iCp9Jdc" width="6.584" height="5.992" x="9.345" y="2.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".125"/></filter><filter id="iTJOePe" width="6.362" height="5.736" x="15.267" y="3.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".125"/></filter><filter id="iv2Y2bd" width=".787" height=".696" x="16.874" y="9.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".05"/></filter><filter id="ichp3ld" width=".891" height=".913" x="17.713" y="9.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".1"/></filter><filter id="iYlbxAe" width=".986" height="1.04" x="13.271" y="9.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".1"/></filter><filter id="iKSyfKe" width=".913" height=".705" x="12.516" y="9.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".05"/></filter><filter id="iMnh2kb" width="1.329" height="2.379" x="9.393" y="9.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".125"/></filter><filter id="iWdRrsd" width="1.447" height="2.403" x="20.138" y="9.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".125"/></filter><filter id="iqGoxrz" width="2.105" height=".86" x="11.794" y="7.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".075"/></filter><filter id="iLlayvc" width="2.105" height=".867" x="17.073" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2175" stdDeviation=".075"/></filter><filter id="iga9dAb" width="10.729" height="5.624" x="10.061" y="6.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/></filter><filter id="iKOiKDd" width="11.479" height="6.324" x="9.611" y="5.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.494118 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2175"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2175" result="effect2_innerShadow_4002_2175"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scientist-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a0q7e-rbb {
  d: path("M23.825 19.457h2.703v5.938h-2.703z");
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a124lcdye {
  d: path("M26.529 21.222v4.172h-2.704v-4.172z");
}

.a5tc3xwyp {
  d: path("M17.61 9.732a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.aetlj_buy {
  stop-color: var(--svg-color--9cc4ac, #9CC4AC);
}

.afds29lll {
  d: path("m9.608 17.112l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.807a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.b_wzmzbwq {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.675px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bo1avib2v {
  d: path("M20.348 12.2q.1-1.596.184-3.19a1.61 1.61 0 0 1-.184 3.19");
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.bx23o8bkx {
  stop-color: var(--svg-color--b28598, #B28598);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c7dra70nl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.6h1.797");
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.coxmzuo0a {
  d: path("M13.242 9.732a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.d0l9e5bir {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.019 8.195c.257-.185.898-.509 1.655-.382");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d3a6h5dbs {
  stop-color: var(--svg-color--ccb8e5, #CCB8E5);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dkh21gill {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.295h1.797");
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dotkg_5jb {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M18.953 8.149c-.185-.274-.897-.509-1.655-.382");
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dpepzs4dm {
  stop-color: var(--svg-color--bd718f, #BD718F);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dx1e6jb0z {
  stop-color: var(--svg-color--be9bb3, #BE9BB3);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e080jybbb {
  stop-color: var(--svg-color--ed5030, #ED5030);
  stop-opacity: 0;
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e2ig5yb1x {
  stop-color: var(--svg-color--e07221, #E07221);
}

.ea_0ewlyw {
  stop-color: var(--svg-color--c79f97, #C79F97);
}

.eafq37b6z {
  d: path("m20.638 8.616l-.029-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.367c-.257-.97.67-1.713 1.655-1.522c.974.19 2.083.517 2.903 1.052c1.744 1.138 1.439 3.188.52 4.154");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.efonc5hef {
  d: path("m9.474 17.72l-.131 1.733a.6.6 0 0 0 .494.636l.479.085a.15.15 0 0 1 .085.248l-.626.692a.5.5 0 0 0 .014.686l4.733 4.808a.2.2 0 0 0 .342-.14v-3.38a2 2 0 0 0-.175-.82l-2.606-5.803c-.929.298-1.806.722-2.61 1.255");
}

.eol9ugodk {
  stop-color: var(--svg-color--ed5030, #ED5030);
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
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

.fbqio7b7r {
  stop-color: var(--svg-color--a27d98, #A27D98);
}

.fdlwvrlzb {
  stop-color: var(--svg-color--c0737b, #C0737B);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftb0dac9p {
  d: path("M15.426 18.618a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gip5y3buk {
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.gmjg4ccxy {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.035 9.46c-.653 0-1.205.45-1.355 1.059a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h-y9sqzgz {
  d: path("M23.825 22.035v-.469h.805a.234.234 0 0 1 0 .469z");
}

.h9gt7l15p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.544 9.92c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.136.388-.05");
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.ht7we4nuf {
  d: path("M15.426 13.756c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hy6proxed {
  stop-color: var(--svg-color--e1d2f9, #E1D2F9);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i-_q9txbo {
  d: path("M20.287 12.11c.335-.011.65-.125.905-.31v.932c0 .893-.533 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibj3x4n2f {
  stop-color: var(--svg-color--c7868b, #C7868B);
  stop-opacity: 0;
}

.id19t5fes {
  stop-color: var(--svg-color--c68b80, #C68B80);
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j68h5l-_g {
  d: path("M23.825 23.816v-.469h.805a.234.234 0 1 1 0 .469z");
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jqs3afbfy {
  stop-color: var(--svg-color--ece2e9, #ECE2E9);
  stop-opacity: 0;
}

.jr9hdpl0f {
  d: path("M18.405 10.507a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.k0qhydbjb {
  stop-color: var(--svg-color--cd8472, #CD8472);
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.koh97ebar {
  d: path("m15.658 5.244l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.781-1.613 1.28-1.959c.14-.098.26-.18.33-.253l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892V5.23z");
}

.koptfs8yh {
  cx: 12.972px;
  cy: 10.113px;
  rx: 0.39px;
  ry: 0.197px;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxkb4k-i {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m14.995 10.677l-.692 1.656c-.101.378.142.756.486.756h.735c.345 0 .588-.384.487-.756l-.497-1.839c-.106-.407-.408-.224-.52.183");
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lceri-vrq {
  d: path("M22.753 29.988v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj5m7ucmi {
  stop-color: var(--svg-color--bea0dc, #BEA0DC);
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lzxh7zbhd {
  d: path("M11.114 16.28a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mx_0g-cbx {
  d: path("M8.226 29.988v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nzcw4eb0y {
  fill: var(--svg-color--000, #000);
  d: path("M13.753 10.624a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.o26echxgv {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.075 13.361a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.272a.23.23 0 0 0-.27-.045h-.002c-.39.204-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oa6-9zbfy {
  fill: var(--svg-color--9f9ba5, #9F9BA5);
  fill-rule: evenodd;
  d: path("M9.761 9.17c.011-1.677 1.389-3.006 3.047-3.006h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.567-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.066-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352A3.02 3.02 0 0 1 9.761 9.17m.6.002a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.608.34l.001.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.otwtgescx {
  stop-color: var(--svg-color--a66955, #A66955);
}

.ox0t0tbyw {
  d: path("M15.466 15.348c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.oxearsb0s {
  d: path("M20.28 4.217a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.875v1.188a1.7 1.7 0 0 0-.668-.269l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.031 1.537c-.254.038-.52.122-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.308.51.79.88 1.352 1.073");
}

.p2mir8bpk {
  stop-color: var(--svg-color--d2b4ed, #D2B4ED);
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pusr6ob-i {
  stop-color: var(--svg-color--97c1a5, #97C1A5);
  stop-opacity: 0.75;
}

.q__as4b2h {
  d: path("m21.37 17.112l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687l-4.732 4.807a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qioyo8boa {
  d: path("m21.02 18.142l.115 1.533a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.611a.44.44 0 0 1-.012.608l-4.188 4.254a.177.177 0 0 1-.303-.124v-2.991c0-.25.053-.497.155-.725l2.306-5.136a9.4 9.4 0 0 1 2.31 1.112");
}

.ql-d_bcrc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.99h1.797");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rsfdnufmx {
  stop-color: var(--svg-color--b64118, #B64118);
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.ryx370bez {
  d: path("M23.137 25.313c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.406-.657");
}

.s1achebfe {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.388 11.55q.057-.953.11-1.904a.956.956 0 0 1-.11 1.903");
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.sc_pn_b9h {
  d: path("M14.057 10.52c0-.289-.235-.481-.298-.54l-.288.28l.177.36z");
}

.sdqhb92yx {
  cx: 12.972px;
  cy: 10.113px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sghpbcc-q {
  d: path("M15.466 15.298h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tkgx_8bnk {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.675px;
  rx: 0.391px;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.txsyviqti {
  stop-color: var(--svg-color--aa9fa6, #AA9FA6);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.ualev6bga {
  d: path("M10.372 9a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.vkttrlbcf {
  d: path("m15.043 10.299l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.vwrtm3bab {
  d: path("M10.564 12.11a1.64 1.64 0 0 1-.904-.31v.932c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.vzhel1b-t {
  d: path("M19.865 16.28a10.5 10.5 0 0 1 2.878 1.918v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w3-o4ac4j {
  stop-color: var(--svg-color--cd8472, #CD8472);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wmrb13bye {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.125 8.024a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.122-1.213-.057a.277.277 0 1 0 .067.55c.482-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 0 0 .364-.418");
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wz4pmowzu {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.388 9.662a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x6zej0-dg {
  fill: var(--svg-color--000, #000);
  d: path("M17.099 10.624c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.xo2zgxulc {
  d: path("M18.083 6.464h-5.275c-1.497 0-2.737 1.2-2.747 2.707a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xpzhm0iru {
  stop-color: var(--svg-color--cec5ca, #CEC5CA);
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y83_mxbbk {
  d: path("M17.544 9.92c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.359c.15-.113.325-.136.388-.05");
}

.yae6yabyn {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.817 9.46c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.yaf5ccsht {
  d: path("M10.6 13.624a3.916 3.916 0 0 0 3.887 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.556");
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yl8r25bpm {
  stop-color: var(--svg-color--77a78a, #77A78A);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zaql8vbut {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M11.981 7.915a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
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

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

</style>
