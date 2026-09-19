<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#iF2xL7c)" class="ox0t0tbyw"/><path fill="url(#iJex2Eb)" class="ox0t0tbyw"/><path fill="url(#i0x9rSc)" class="lzxh7zbhd"/><path fill="url(#iqijBdb)" class="lzxh7zbhd"/><path fill="url(#iTXvIeu)" class="lzxh7zbhd"/><path fill="url(#iIr2zNb)" class="lzxh7zbhd"/><path fill="url(#idCIDmb)" class="vzhel1b-t"/><path fill="url(#icbfzYc)" class="vzhel1b-t"/><path fill="url(#iYuCe2d)" class="vzhel1b-t"/><path fill="url(#iDWkYOd)" class="vzhel1b-t"/><g filter="url(#iO4BYNX)"><path fill="url(#iZ6dTnd)" class="vmc-iabjh"/></g><g filter="url(#iuM7ajb)"><path fill="url(#iBCBk6c)" class="ainf1jcmz"/></g><g filter="url(#indHymH)"><path fill="url(#ic5ISlz)" class="dgtwjnbll"/></g><path fill="url(#iYFpHob)" class="bew_bibae"/><path fill="url(#iuMA8qd)" class="bew_bibae"/><path fill="url(#i9zEBle)" class="bew_bibae"/><path fill="url(#iL0OQae)" class="bew_bibae"/><path fill="url(#iU0Zedb)" class="bew_bibae"/><path fill="url(#ikhTrkd)" class="mx_0g-cbx"/><path fill="url(#inx4RRc)" class="mx_0g-cbx"/><path fill="url(#iYC5CUv)" class="mx_0g-cbx"/><path fill="url(#isL6aLe)" class="mx_0g-cbx"/><path fill="url(#iKGtVBM)" class="ainf1jcmz"/><path fill="url(#iTZvVue)" class="lceri-vrq"/><path fill="url(#i5KOZnc)" class="lceri-vrq"/><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#iHXm6te)" class="l69inwbok"/><path fill="url(#i5xRXZd)" class="l69inwbok"/><path fill="url(#iJo4ysd)" class="gip5y3buk"/><path fill="url(#id6Igne)" class="gip5y3buk"/><path fill="url(#ixdtEFe)" class="wpy995b9j"/><path fill="url(#iF1k9Ki)" class="wpy995b9j"/><path fill="url(#ilUA1Ec)" class="wpy995b9j"/><g filter="url(#iofgAsb)"><rect class="b_wzmzbwq"/><rect fill="url(#in80oDb)" class="tkgx_8bnk"/><rect fill="url(#iEsINHM)" class="tkgx_8bnk"/><rect fill="url(#imH7Vqd)" class="tkgx_8bnk"/></g><path fill="url(#itN89Zb)" class="a124lcdye"/><path fill="url(#iWn83Lb)" class="a124lcdye"/><path fill="url(#i6aufrd)" class="a124lcdye"/><path fill="url(#iqwFqNS)" class="a124lcdye"/><path fill="url(#iiRMWBW)" class="j9vp7gz0m"/><path fill="url(#iYneMqd)" class="j68h5l-_g"/><g filter="url(#iIaDsQe)"><path fill="url(#itP5hod)" class="ps01v_b0r"/><path fill="url(#ilG6NNb)" class="ps01v_b0r"/><path fill="url(#ihjk7db)" class="ps01v_b0r"/><path fill="url(#i3LWoQy)" class="ps01v_b0r"/><path fill="url(#idQFoMe)" class="ps01v_b0r"/></g><g filter="url(#ieyYP4c)"><path stroke="url(#ijrhy7c)" class="ql-d_bcrc"/></g><g filter="url(#iIYMOJd)"><path stroke="url(#i3R3PTB)" class="sqxhjlnxl"/></g><g filter="url(#i214Jlj)"><path stroke="url(#ipEDq5h)" class="c7dra70nl"/></g><path fill="url(#ibunFje)" class="v9_hj434m"/><path fill="url(#ilQf9Sd)" class="vwrtm3bab"/><g filter="url(#iKAUJQc)"><path fill="url(#inLiIYc)" class="c42d7h-4y"/><path fill="url(#ikZ4kjb)" class="c42d7h-4y"/></g><path fill="url(#ikiyoFc)" class="c42d7h-4y"/><path fill="url(#ia9Qo0b)" class="c42d7h-4y"/><path fill="url(#iJ6TR9d)" class="c42d7h-4y"/><path fill="url(#iJkdvVb)" class="c42d7h-4y"/><path fill="url(#iOhlM9c)" class="c42d7h-4y"/><path fill="url(#iWSv8ej)" class="c42d7h-4y"/><path fill="url(#iWcbiod)" class="c42d7h-4y"/><path fill="url(#iJmvz9P)" class="c42d7h-4y"/><g filter="url(#iwnlEkb)"><path class="i9_cjmbyc"/></g><g filter="url(#iTl6Dtu)"><path class="rfr2_fezd"/><path fill="url(#iNcg7pe)" class="tjy_10b3v"/><path fill="url(#iVccZMd)" class="tjy_10b3v"/><path fill="url(#i234s9d)" class="tjy_10b3v"/><path fill="url(#iRyI8HJ)" class="tjy_10b3v"/><path fill="url(#i2ymSUb)" class="tjy_10b3v"/></g><path fill="url(#ilRJABT)" class="tjy_10b3v"/><path fill="url(#iYtDwMb)" class="tjy_10b3v"/><g filter="url(#iwa6Fpb)"><path stroke="url(#iH2DBsc)" class="rvpscutoq"/></g><path fill="url(#iYe9ved)" class="ht7we4nuf"/><g filter="url(#iDM27dc)"><path fill="url(#iGNocHb)" class="kg3a8mbgv"/></g><path fill="url(#iYygsOJ)" class="kg3a8mbgv"/><path fill="url(#ixRlW2d)" class="kg3a8mbgv"/><path fill="url(#ihRVnsb)" class="kg3a8mbgv"/><g filter="url(#iUxZj8d)"><path class="xegmtebyq"/></g><g filter="url(#iNdtP2N)"><path class="bt35atazq"/></g><g filter="url(#iyyyg4b)"><path class="ska238bfj"/><path fill="url(#iKdU1ze)" class="ybkft5ymj"/><path fill="url(#iJlDidb)" class="ybkft5ymj"/></g><g filter="url(#iYw5Oob)"><path class="z0a79nu3z"/><path fill="url(#in5X6Tb)" class="lznblxbsu"/><path fill="url(#ilCHCTc)" class="lznblxbsu"/><path fill="url(#iC6pjse)" class="lznblxbsu"/></g><path class="yae6yabyn"/><path fill="url(#iZE941c)" class="rrfjqqbzm"/><path class="wr4dwzv_v"/><g filter="url(#iXtBi5G)"><path class="isxfb77db"/><path fill="url(#iqTGPrb)" class="ix8mu0bhv"/></g><g filter="url(#irjRLqd)"><path fill="url(#iJzTwQd)" class="jr9hdpl0f"/></g><path class="vps9nrkuj"/><path fill="url(#iIUOmce)" class="o2winac2b"/><path class="b0maullyh"/><g filter="url(#i4TPgeb)"><path fill="url(#iaMsqcb)" class="sb62shdsk"/></g><g filter="url(#ifWd0pb)"><ellipse transform="rotate(-27.914 12.972 10.113)" class="sdqhb92yx"/><ellipse fill="url(#iWsRgQr)" transform="rotate(-27.914 12.972 10.113)" class="koptfs8yh"/></g><path fill="url(#izIYJad)" class="nba0bkbns"/><path fill="url(#iL0kqgq)" class="nba0bkbns"/><path fill="url(#iVTy0md)" class="nba0bkbns"/><path fill="url(#iYPdyxd)" class="nba0bkbns"/><path fill="url(#iB6Yl8c)" class="d-3i1p3tc"/><path fill="url(#iRgn2dd)" class="d-3i1p3tc"/><g filter="url(#isqFHHc)"><path fill="url(#iAJ2Z7b)" class="d0p0zob0j"/></g><g filter="url(#iham7Cd)"><path fill="url(#iwnmJqc)" class="ezl3pkbqn"/></g><g filter="url(#i2A5SPe)"><path class="jgjwlnbce"/></g><g filter="url(#icekiOM)"><path class="ff0j-tb6p"/></g><g filter="url(#i39ivfb)"><path class="zgxlrfbju"/></g><g filter="url(#iVmdWxb)" class="z4n2hhy8u"><path fill="url(#iwSp4qe)" class="xo2zgxulc"/></g><g filter="url(#iAMeTAb)"><path clip-rule="evenodd" class="lvrtecb2d"/></g><defs><radialGradient id="iF2xL7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.316)" gradientUnits="userSpaceOnUse"><stop class="e2ig5yb1x"/><stop offset="1" class="rsfdnufmx"/></radialGradient><radialGradient id="iJex2Eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.316)" gradientUnits="userSpaceOnUse"><stop class="eol9ugodk"/><stop offset="1" class="e080jybbb"/></radialGradient><radialGradient id="i0x9rSc" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.56)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="hy6proxed"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iIr2zNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.41)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="idCIDmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.285)" gradientUnits="userSpaceOnUse"><stop class="lj5m7ucmi"/><stop offset="1" class="d3a6h5dbs"/></radialGradient><radialGradient id="icbfzYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.535)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iBCBk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.91)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iYFpHob" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.69)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iuMA8qd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.307 -.255)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="i9zEBle" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 15.988)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="xpzhm0iru"/><stop offset="1" class="jqs3afbfy"/></radialGradient><radialGradient id="ikhTrkd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.112)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iYC5CUv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.968)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iKGtVBM" cx="0" cy="0" r="1" gradientTransform="matrix(-1 2.84375 -3.2172 -1.13131 12.552 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="fbqio7b7r"/><stop offset="1" class="txsyviqti"/></radialGradient><radialGradient id="iTZvVue" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.878)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iHXm6te" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92264 -3.14989 0 15.426 17.172)" gradientUnits="userSpaceOnUse"><stop class="e2y3mgbdj"/><stop offset="1" class="mwasdabrq"/></radialGradient><radialGradient id="i5xRXZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.45312 -1.20313 0 13.666 16.765)" gradientUnits="userSpaceOnUse"><stop class="ike3k_bbj"/><stop offset="1" class="ier_2sb9m"/></radialGradient><radialGradient id="iJo4ysd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03943 1.39355 -1.36898 -2.00347 27.808 23.62)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="id6Igne" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.466)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="ilUA1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.378)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="in80oDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.066)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iEsINHM" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.918)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="imH7Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.277)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iqwFqNS" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.222)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="ilG6NNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.292)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ihjk7db" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.587)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i3LWoQy" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.837)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="idQFoMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.188)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ibunFje" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.609 20.402)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="ilQf9Sd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.37 12.29)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="inLiIYc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.233 10.86)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ikZ4kjb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.268 7.974)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="ia9Qo0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.3808 -10.2528 0 15.985 4.989)" gradientUnits="userSpaceOnUse"><stop offset=".817" class="wc4twjb4s"/><stop offset=".998" class="otf1mnoto"/></radialGradient><radialGradient id="iJ6TR9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.873 9.546)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iJkdvVb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.376 -1.79)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iOhlM9c" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.242 6.221)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iWSv8ej" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 8.634 8.126)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iWcbiod" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.87 13.517)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iJmvz9P" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.21 10.364)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iVccZMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.892 12.361)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iRyI8HJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.008 11.792)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iYtDwMb" cx="0" cy="0" r="1" gradientTransform="rotate(136.341 5.625 8.927)scale(1.77237 2.55795)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="hyqj6b3ju"/><stop offset="1" class="hbuj5vb9g"/></radialGradient><radialGradient id="iYe9ved" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 14.935 14.483)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iYygsOJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 9.718 8.935)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="ixRlW2d" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.123 -3.886)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="ihRVnsb" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 10.814 -3.543)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iKdU1ze" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 15.68 3.668)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iJlDidb" cx="0" cy="0" r="1" gradientTransform="matrix(3.21817 -5.09544 5.64522 3.5654 9.995 7.61)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="in5X6Tb" cx="0" cy="0" r="1" gradientTransform="rotate(-38.837 17.5 -21.488)scale(4.51284 6.99393)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="ilCHCTc" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 18.06 7.482)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iC6pjse" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72413 -.30318 1.35036 17.196 5.661)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iZE941c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.608 10.209)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iqTGPrb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.21 .89)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIUOmce" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.244 10.209)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iWsRgQr" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.958 10.428)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iL0kqgq" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.043 9.957)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iVTy0md" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.404 10.502)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iYPdyxd" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.518 10.674)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iRgn2dd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 10.51 10.598)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iAJ2Z7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 10.511 10.6)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><linearGradient id="ivWcDIe" x1="8.23" x2="22.659" y1="15.296" y2="15.296" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqijBdb" x1="11.239" x2="11.239" y1="30.41" y2="29.097" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iTXvIeu" x1="15.177" x2="14.208" y1="29.097" y2="29.097" gradientUnits="userSpaceOnUse"><stop offset=".129" class="dx1e6jb0z"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iYuCe2d" x1="19.74" x2="19.74" y1="30.41" y2="29.097" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iDWkYOd" x1="15.802" x2="16.505" y1="27.972" y2="27.972" gradientUnits="userSpaceOnUse"><stop class="bx23o8bkx"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iZ6dTnd" x1="10.677" x2="12.896" y1="17.941" y2="24.628" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="ic5ISlz" x1="20.45" x2="18.099" y1="18.97" y2="23.671" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iL0OQae" x1="18.958" x2="17.552" y1="24.097" y2="22.597" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iU0Zedb" x1="17.146" x2="17.974" y1="18.878" y2="19.222" gradientUnits="userSpaceOnUse"><stop offset=".081" class="ea_0ewlyw"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="inx4RRc" x1="6.567" x2="6.567" y1="30.352" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="isL6aLe" x1="8.38" x2="7.935" y1="29.386" y2="29.384" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="i5KOZnc" x1="22.753" x2="23.162" y1="27.66" y2="27.644" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ixdtEFe" x1="23.825" x2="26.529" y1="20.847" y2="20.847" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iF1k9Ki" x1="26.529" x2="26.18" y1="20.831" y2="20.831" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="itN89Zb" x1="26.529" x2="25.177" y1="23.16" y2="23.16" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iWn83Lb" x1="26.529" x2="26.129" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="i6aufrd" x1="23.696" x2="24.227" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="iiRMWBW" x1="24.782" x2="23.892" y1="21.8" y2="21.8" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iYneMqd" x1="24.782" x2="23.892" y1="23.581" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="itP5hod" x1="27.165" x2="23.137" y1="28.05" y2="28.05" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="ijrhy7c" x1="23.754" x2="25.463" y1="26.068" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i3R3PTB" x1="23.676" x2="25.385" y1="27.373" y2="27.373" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ipEDq5h" x1="23.754" x2="25.463" y1="28.677" y2="28.677" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ikiyoFc" x1="20.583" x2="18.054" y1="12.545" y2="12.545" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iNcg7pe" x1="16.264" x2="15.426" y1="11.675" y2="11.71" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i234s9d" x1="15.426" x2="15.426" y1="12.815" y2="12.35" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="i2ymSUb" x1="15.426" x2="15.426" y1="10.11" y2="10.656" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="ilRJABT" x1="15.841" x2="15.841" y1="12.952" y2="12.76" gradientUnits="userSpaceOnUse"><stop class="ob6tdy6_n"/><stop offset="1" class="po7hb_xwu"/></linearGradient><linearGradient id="iH2DBsc" x1="14.224" x2="14.543" y1="14.244" y2="13.41" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iGNocHb" x1="22.278" x2="10.665" y1="5.197" y2="5.197" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iJzTwQd" x1="18.386" x2="18.072" y1="10.263" y2="10.456" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaMsqcb" x1="13.988" x2="13.674" y1="10.262" y2="10.456" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izIYJad" x1="21.862" x2="20.655" y1="10.024" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iB6Yl8c" x1="9.576" x2="11.034" y1="10.728" y2="10.601" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iwnmJqc" x1="20.879" x2="20.879" y1="9.715" y2="11.473" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="iwSp4qe" x1="10.917" x2="22.177" y1="9.727" y2="9.727" gradientUnits="userSpaceOnUse"><stop offset=".257" class="rpclz5w3y"/><stop offset=".917" class="pusr6ob-i"/></linearGradient><filter id="iO4BYNX" width="7.023" height="11.703" x="8.591" y="15.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".375"/></filter><filter id="iuM7ajb" width="5.673" height="10.453" x="9.475" y="15.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/></filter><filter id="indHymH" width="6.388" height="10.529" x="15.499" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".375"/></filter><filter id="iofgAsb" width="4.008" height=".781" x="23.173" y="18.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/></filter><filter id="iIaDsQe" width="4.468" height="5.556" x="23.137" y="24.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/></filter><filter id="ieyYP4c" width="2.097" height=".3" x="23.604" y="25.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".05"/></filter><filter id="iIYMOJd" width="2.097" height=".3" x="23.526" y="27.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".05"/></filter><filter id="i214Jlj" width="2.097" height=".3" x="23.604" y="28.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".05"/></filter><filter id="iKAUJQc" width="11.22" height="12.442" x="10.362" y="4.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2172" result="effect2_innerShadow_4002_2172"/></filter><filter id="iwnlEkb" width="3.747" height="4.9" x="13.41" y="9.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".5"/></filter><filter id="iTl6Dtu" width="2.277" height="3.3" x="14.287" y="9.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".1"/></filter><filter id="iwa6Fpb" width="3.718" height="1.573" x="13.566" y="13.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".05"/></filter><filter id="iDM27dc" width="12.873" height="8.357" x="8.989" y="1.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2172" result="effect2_innerShadow_4002_2172"/></filter><filter id="iUxZj8d" width="2.339" height="1.19" x="17.015" y="7.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/></filter><filter id="iNdtP2N" width="2.339" height="1.176" x="11.758" y="7.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/></filter><filter id="iyyyg4b" width="6.584" height="5.992" x="9.345" y="2.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/><feGaussianBlur result="effect2_foregroundBlur_4002_2172" stdDeviation=".125"/></filter><filter id="iYw5Oob" width="7.112" height="5.986" x="15.267" y="2.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/><feGaussianBlur result="effect2_foregroundBlur_4002_2172" stdDeviation=".125"/></filter><filter id="iXtBi5G" width=".787" height=".696" x="16.874" y="9.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".05"/></filter><filter id="irjRLqd" width=".891" height=".913" x="17.713" y="9.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".1"/></filter><filter id="i4TPgeb" width=".986" height="1.04" x="13.271" y="9.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".1"/></filter><filter id="ifWd0pb" width=".913" height=".705" x="12.516" y="9.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".05"/></filter><filter id="isqFHHc" width="1.329" height="2.379" x="9.345" y="9.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".125"/></filter><filter id="iham7Cd" width="1.806" height="2.758" x="19.976" y="9.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".25"/></filter><filter id="i2A5SPe" width="2.205" height=".96" x="11.777" y="7.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".075"/></filter><filter id="icekiOM" width="2.105" height=".86" x="17.144" y="7.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".075"/></filter><filter id="i39ivfb" width="5.367" height="3.046" x="16.442" y="3.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2172" stdDeviation=".375"/></filter><filter id="iVmdWxb" width="10.729" height="5.624" x="10.061" y="6.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/></filter><filter id="iAMeTAb" width="11.479" height="6.324" x="9.611" y="5.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.494118 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2172"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2172" result="effect2_innerShadow_4002_2172"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scientist-medium" /></template>
<style>
.a124lcdye {
  d: path("M26.529 21.222v4.172h-2.704v-4.172z");
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.ainf1jcmz {
  d: path("m9.608 17.112l-.13 1.733a.6.6 0 0 0 .493.636l.48.084a.15.15 0 0 1 .084.249l-.626.691a.5.5 0 0 0 .015.686L14.656 26a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.b_wzmzbwq {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.675px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.b0maullyh {
  fill: var(--svg-color--000, #000);
  d: path("M13.753 10.624a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.236");
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bew_bibae {
  d: path("m21.37 17.112l.132 1.733a.6.6 0 0 1-.494.636l-.48.084a.15.15 0 0 0-.085.249l.626.691a.5.5 0 0 1-.014.686L16.323 26a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.bt35atazq {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.015 7.915a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.bx23o8bkx {
  stop-color: var(--svg-color--b28598, #B28598);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c42d7h-4y {
  d: path("M10.6 13.624a3.916 3.916 0 0 0 3.886 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.117 3.69.239 5.556");
}

.c7dra70nl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.6h1.797");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.d-3i1p3tc {
  d: path("M10.381 8.996a1.62 1.62 0 0 0-1.392 1.598c0 .859.673 1.56 1.521 1.607a78 78 0 0 1-.129-3.205");
}

.d0p0zob0j {
  d: path("M10.34 9.66a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d3a6h5dbs {
  stop-color: var(--svg-color--ccb8e5, #CCB8E5);
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.dgtwjnbll {
  d: path("m21.02 18.142l.115 1.533a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.611a.44.44 0 0 1-.012.608l-4.188 4.254a.177.177 0 0 1-.303-.124v-2.991c0-.25.053-.497.155-.725l2.306-5.136c.822.265 1.599.64 2.31 1.111");
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dx1e6jb0z {
  stop-color: var(--svg-color--be9bb3, #BE9BB3);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e080jybbb {
  stop-color: var(--svg-color--ed5030, #ED5030);
  stop-opacity: 0;
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e2ig5yb1x {
  stop-color: var(--svg-color--e07221, #E07221);
}

.e2y3mgbdj {
  stop-color: var(--svg-color--905562, #905562);
}

.ea_0ewlyw {
  stop-color: var(--svg-color--c79f97, #C79F97);
}

.eol9ugodk {
  stop-color: var(--svg-color--ed5030, #ED5030);
}

.ezl3pkbqn {
  d: path("M20.476 11.473q.05-.879.094-1.758c.401.054.712.426.712.876c0 .484-.36.878-.806.882");
}

.fbqio7b7r {
  stop-color: var(--svg-color--a27d98, #A27D98);
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.ff0j-tb6p {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.024 8.14c-.257-.185-.898-.51-1.655-.382");
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gip5y3buk {
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbuj5vb9g {
  stop-color: var(--svg-color--835753, #835753);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.ht7we4nuf {
  d: path("M15.426 13.756c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.hy6proxed {
  stop-color: var(--svg-color--e1d2f9, #E1D2F9);
}

.hyqj6b3ju {
  stop-color: var(--svg-color--835753, #835753);
  stop-opacity: 0;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i9_cjmbyc {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.024 10.482l-.59 1.838c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.495-1.838c-.106-.407-.504-.407-.615 0");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ier_2sb9m {
  stop-color: var(--svg-color--8d5a53, #8D5A53);
  stop-opacity: 0;
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ike3k_bbj {
  stop-color: var(--svg-color--8d5a53, #8D5A53);
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.isxfb77db {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.544 9.92c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.ix8mu0bhv {
  d: path("M17.544 9.92c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j68h5l-_g {
  d: path("M23.825 23.816v-.469h.805a.234.234 0 1 1 0 .469z");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9vp7gz0m {
  d: path("M23.825 22.035v-.47h.805a.234.234 0 0 1 0 .47z");
}

.jgjwlnbce {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.053 8.195c.256-.185.897-.51 1.655-.382");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
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

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.kg3a8mbgv {
  d: path("M20.28 4.217c.515.177.976.536 1.268 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.189a1.7 1.7 0 0 0-.668-.269l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.031 1.537c-.254.037-.52.122-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.308.51.79.88 1.352 1.073");
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

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l69inwbok {
  d: path("M15.426 18.617a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.lceri-vrq {
  d: path("M22.753 29.988v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
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

.lvrtecb2d {
  fill: var(--svg-color--9f9ba5, #9F9BA5);
  fill-rule: evenodd;
  d: path("M9.761 9.169c.011-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04c-.022 1.568-1.339 2.918-2.907 2.974h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.066-.09-.076-.112-.076s-.067.01-.112.075a3.08 3.08 0 0 1-2.549 1.353A3.02 3.02 0 0 1 9.761 9.17zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.608.34l.001.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.382a2.41 2.41 0 0 0-2.407-2.432h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.lznblxbsu {
  d: path("m20.638 8.51l-.029-.63c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.051c1.745 1.138 1.44 3.189.521 4.155");
}

.lzxh7zbhd {
  d: path("M11.114 16.28a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.mwasdabrq {
  stop-color: var(--svg-color--7b483d, #7B483D);
}

.mx_0g-cbx {
  d: path("M8.226 29.988v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.nba0bkbns {
  d: path("M20.348 12.2q.1-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o2winac2b {
  d: path("M13.242 9.732a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.ob6tdy6_n {
  stop-color: var(--svg-color--915468, #915468);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.ox0t0tbyw {
  d: path("M15.466 15.348c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
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

.po7hb_xwu {
  stop-color: var(--svg-color--915468, #915468);
  stop-opacity: 0;
}

.ps01v_b0r {
  d: path("M23.137 25.313c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.pusr6ob-i {
  stop-color: var(--svg-color--97c1a5, #97C1A5);
  stop-opacity: 0.75;
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
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

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfr2_fezd {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.043 10.286l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rpclz5w3y {
  stop-color: var(--svg-color--679078, #679078);
}

.rrfjqqbzm {
  d: path("M17.61 9.732a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.rsfdnufmx {
  stop-color: var(--svg-color--b64118, #B64118);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.rvpscutoq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.075 13.361a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.002c-.39.203-.85.32-1.35.32c-.496 0-.961-.117-1.351-.32Z");
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sb62shdsk {
  d: path("M14.057 10.52c0-.29-.235-.481-.298-.54l-.288.28l.177.36z");
}

.sdqhb92yx {
  cx: 12.972px;
  cy: 10.113px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
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

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.ska238bfj {
  fill: var(--svg-color--533634, #533634);
  d: path("m15.658 5.244l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.781-1.614 1.28-1.96c.14-.097.26-.179.33-.252l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892V5.23z");
}

.sqxhjlnxl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.294h1.797");
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.tjy_10b3v {
  d: path("m15.043 10.286l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.531-1.838c-.114-.407-.645-.407-.765 0");
}

.tkgx_8bnk {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.675px;
  rx: 0.391px;
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.txsyviqti {
  stop-color: var(--svg-color--aa9fa6, #AA9FA6);
  stop-opacity: 0;
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v9_hj434m {
  d: path("M20.287 12.11c.335-.011.65-.125.905-.31v.932c0 .893-.532 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vmc-iabjh {
  d: path("m9.474 17.72l-.131 1.733a.6.6 0 0 0 .494.636l.479.085a.15.15 0 0 1 .085.248l-.626.691a.5.5 0 0 0 .014.687l4.733 4.808a.2.2 0 0 0 .342-.14v-3.38a2 2 0 0 0-.175-.82l-2.606-5.804a10.6 10.6 0 0 0-2.61 1.256");
}

.vps9nrkuj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.035 9.46c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
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

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wc4twjb4s {
  stop-color: var(--svg-color--a66f7b, #A66F7B);
  stop-opacity: 0;
}

.wpy995b9j {
  d: path("M23.825 19.456h2.703v5.938h-2.703z");
}

.wr4dwzv_v {
  fill: var(--svg-color--000, #000);
  d: path("M17.099 10.624a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.747h-.904a.46.46 0 0 1-.061-.236");
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xegmtebyq {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.159 8.024a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 1 0 .364-.418");
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

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.yae6yabyn {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.817 9.46c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ybkft5ymj {
  d: path("m15.658 5.244l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.781-1.614 1.28-1.96c.14-.097.26-.179.33-.252l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892V5.23z");
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z0a79nu3z {
  fill: var(--svg-color--563936, #563936);
  d: path("m20.638 8.51l-.029-.63c-.01-.764-.642-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.189 2.082.517 2.902 1.051c1.745 1.138 1.44 3.189.521 4.155");
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

.zgxlrfbju {
  fill: var(--svg-color--725050, #725050);
  d: path("M19.824 5.247h-2.137a.496.496 0 1 1 .08-.987c.554.088 1.29.211 1.783.333c1.115.277 1.423.82 1.509 1.206a1.55 1.55 0 0 0-1.235-.552");
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
