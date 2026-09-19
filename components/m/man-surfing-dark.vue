<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWonAzc)"><path class="jhlh1_3ek"/><path fill="url(#ijJnbEe)" class="vb809lo-e"/></g><path fill="url(#i6qhIMe)" class="vb809lo-e"/><path fill="url(#iMX3qoe)" class="vb809lo-e"/><path fill="url(#iojSsLc)" class="vb809lo-e"/><path fill="url(#ioT8ldb)" class="vb809lo-e"/><g filter="url(#iimMFpe)"><path class="siw2d1f7p"/><path fill="url(#izT5PGd)" class="i9-uutisp"/></g><path class="j83otbcan"/><path fill="url(#iI08NNb)" class="xtp47zbsj"/><path fill="url(#iPHWNcc)" class="u--ocwryb"/><path fill="url(#iJ67Gde)" class="sazwi3bdn"/><path fill="url(#il6NAWb)" class="sazwi3bdn"/><g filter="url(#iCb5gje)"><path fill="url(#inumkee)" class="qnmjgylyq"/><path fill="url(#ihJgNrc)" class="qnmjgylyq"/></g><g filter="url(#icE66Vb)"><circle fill="url(#iAisVdc)" class="s2ikxxbfc"/></g><g filter="url(#iLahw1N)"><circle fill="url(#iuX5Neb)" class="qv62lactv"/></g><g filter="url(#isZChfb)"><circle fill="url(#i9dRGae)" class="ae99og76i"/></g><rect fill="url(#ibU9Xsd)" transform="rotate(26.595 20.662 12.797)" class="i34rybopj"/><g filter="url(#iD5KqSI)"><path fill="url(#iNk77vd)" class="pekg0u7cp"/></g><path class="i5vej436q"/><g filter="url(#ifJ4nMd)"><path class="z71t5ubny"/><path fill="url(#i5B0lbe)" class="frgrxi9fy"/><path fill="url(#iyBWBJc)" class="frgrxi9fy"/></g><g filter="url(#i3FsZbe)"><path fill="url(#iw8OLic)" class="gwjr899hs"/><path fill="url(#ihSsHdd)" class="gwjr899hs"/><path fill="url(#iM2Fvfd)" class="gwjr899hs"/></g><path fill="url(#i9yN9Gd)" class="gwjr899hs"/><path fill="url(#iATB0jc)" class="xt887yc-y"/><path fill="url(#iHFY1pe)" class="xt887yc-y"/><path clip-rule="evenodd" class="wfnn4zbei"/><path fill="url(#imb9vQe)" clip-rule="evenodd" class="l89w7ttua"/><path clip-rule="evenodd" class="kp-2efbsj"/><path fill="url(#ibuw9Iv)" clip-rule="evenodd" class="x2d1t4xtf"/><path clip-rule="evenodd" class="o2riu6e9b"/><path fill="url(#igZGKic)" clip-rule="evenodd" class="ljni-v35c"/><path clip-rule="evenodd" class="herbgz03w"/><path fill="url(#ilme1mb)" clip-rule="evenodd" class="wc05b2bod"/><path class="ooocs2okn"/><path fill="url(#ihCsk4d)" class="uu4f6-byw"/><g filter="url(#iisCTNP)"><path fill="url(#iqofZec)" class="so3eyo06u"/></g><g filter="url(#iTGp0xd)"><path fill="url(#iAWuoxl)" class="olg-72bto"/></g><g filter="url(#i7Pryob)"><path stroke="url(#iMi4Dpc)" class="on9u00bey"/></g><g filter="url(#irHF64G)"><circle fill="url(#iPHytpd)" class="c85nnpbdi"/></g><g filter="url(#iMRewIb)"><circle fill="url(#iMmyond)" class="md-locuzc"/></g><g filter="url(#i7lefqd)"><circle fill="url(#iUf5y3q)" class="bflyorafd"/><circle fill="url(#ipEy1Ee)" class="bflyorafd"/></g><g filter="url(#ioOWPnc)"><circle class="zo0htm39v"/><circle fill="url(#iybOjmc)" class="xcdcq7biu"/><circle fill="url(#iPr0TWd)" class="xcdcq7biu"/></g><g filter="url(#iFu3iPT)"><path fill="url(#iXxsFrb)" class="raew06bbn"/><path fill="url(#imuzchd)" class="raew06bbn"/><path fill="url(#ic9XFoc)" class="raew06bbn"/><path fill="url(#i6iVbNe)" class="raew06bbn"/><path fill="url(#iTJFYfb)" class="raew06bbn"/><path fill="url(#ivLGqnc)" class="raew06bbn"/></g><g filter="url(#icj6ypb)"><path fill="url(#ix3wJMb)" class="ikuisnbzy"/></g><g filter="url(#iFpo1we)"><path class="agnv3q_5r"/><path fill="url(#i1itdzc)" class="m9t4-f_6h"/><path fill="url(#iGsk7ec)" class="m9t4-f_6h"/><path fill="url(#iQWwxyd)" class="m9t4-f_6h"/><path fill="url(#iyJtkbd)" class="m9t4-f_6h"/></g><g filter="url(#ir8ZIdc)"><path class="cat6cuzen"/></g><g filter="url(#ioEcZcd)"><path class="f4ne0bb3h"/><path fill="url(#i877fue)" class="xwg01lbun"/><path fill="url(#iWCfoyb)" class="xwg01lbun"/><path fill="url(#iuzlnbd)" class="xwg01lbun"/><path fill="url(#i82pIqd)" class="xwg01lbun"/></g><path stroke="url(#ij8Jmec)" class="okzrnob_x"/><g filter="url(#ibQ1jfc)"><path class="iehf4nbfv"/></g><g filter="url(#ihJav8d)"><path class="df1lq47cu"/></g><path class="sfnr8vh0d"/><path fill="url(#iha2SDe)" class="qpf-7tbbk"/><path class="p2jsddcqm"/><g filter="url(#iPRUjFe)"><path class="k6_me0blg"/><path fill="url(#iW1Uqxe)" class="fjwi8wb7i"/></g><g filter="url(#icNYaVc)"><path fill="url(#iwMmSjc)" class="ono7f8b6y"/></g><path class="s18l7_bne"/><path fill="url(#iLSWkrb)" class="mzrna-ble"/><path class="x-wvar5pp"/><g filter="url(#igQ1MNc)"><path fill="url(#i0s2zad)" class="cj_334bge"/></g><g filter="url(#i4yiWCe)"><ellipse transform="rotate(-27.914 12.829 5.705)" class="x0ye_xb8j"/><ellipse fill="url(#ibw7MCU)" transform="rotate(-27.914 12.829 5.705)" class="u2-yf8bkl"/></g><g filter="url(#i606cyi)"><path stroke="url(#iwyeLld)" class="bgy81xi6b"/></g><g filter="url(#ihVDuXK)"><path stroke="url(#iCALbub)" class="gxtql4gqb"/></g><g filter="url(#iu7JAsG)"><path stroke="url(#iFctdqd)" class="kkmm611rh"/></g><defs><radialGradient id="i6qhIMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.758)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="iojSsLc" cx="0" cy="0" r="1" gradientTransform="matrix(3.56253 -6.12498 3.8162 2.21965 22.203 21.914)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="ioT8ldb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.758)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="izT5PGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.17 25.196)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iI08NNb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.761 25.128)" gradientUnits="userSpaceOnUse"><stop class="ub7ea32uh"/><stop offset="1" class="w7mkf5ikd"/></radialGradient><radialGradient id="il6NAWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.46)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="ihJgNrc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.738 2.812)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iAisVdc" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.217 11.132)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iuX5Neb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.544)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i9dRGae" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.17 9.166)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="ibU9Xsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.096)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="vgekv3bdy"/><stop offset="1" class="r95brsblk"/></radialGradient><radialGradient id="iNk77vd" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.201 10.919)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="nbncwobqn"/><stop offset="1" class="na5vpgbch"/></radialGradient><radialGradient id="i5B0lbe" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.928 6.711)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="jioe1_9gu"/><stop offset="1" class="t5lf5ccyt"/></radialGradient><radialGradient id="iyBWBJc" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.34 10.547)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="fqeviqb2e"/><stop offset="1" class="to9zfdmjz"/></radialGradient><radialGradient id="ihSsHdd" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.414)" gradientUnits="userSpaceOnUse"><stop class="lj0l7tb9r"/><stop offset="1" class="zrzxj2epv"/></radialGradient><radialGradient id="iM2Fvfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.594)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="vgauzicqp"/><stop offset="1" class="r0iiaeguw"/></radialGradient><radialGradient id="i9yN9Gd" cx="0" cy="0" r="1" gradientTransform="matrix(1.38038 -.82813 3.08645 5.14471 17.339 21.226)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="t502ec3cr"/><stop offset="1" class="oipf0m4co"/></radialGradient><radialGradient id="iHFY1pe" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -.93464 2.0447 18.61 10.741)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="g99cn0bet"/><stop offset="1" class="gq1i90b_a"/><stop offset="1" class="airol1bay"/></radialGradient><radialGradient id="imb9vQe" cx="0" cy="0" r="1" gradientTransform="rotate(-164.074 4.362 6.434)scale(1.78035 1.88131)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="ibuw9Iv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6671 -.63637 .8491 -2.2244 6.355 14.392)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="igZGKic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6486 -.68743 .9779 -2.34523 6.177 14.934)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="kn6afsb3f"/><stop offset=".922" class="t7r9i6b3f"/></radialGradient><radialGradient id="ilme1mb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40308 -.60156 .87252 -2.03506 6.294 15.205)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="ihCsk4d" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.768)" gradientUnits="userSpaceOnUse"><stop class="bu3azkbir"/><stop offset="1" class="zga9nrbjv"/></radialGradient><radialGradient id="iqofZec" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.51 15.396)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iPHytpd" cx="0" cy="0" r="1" gradientTransform="matrix(.77665 0 0 1.35914 11.076 6.049)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ipEy1Ee" cx="0" cy="0" r="1" gradientTransform="matrix(.36587 -.26641 .30408 .4176 16.19 5.932)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iybOjmc" cx="0" cy="0" r="1" gradientTransform="matrix(.36347 -.66851 .39128 .21274 16.006 6.412)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iPr0TWd" cx="0" cy="0" r="1" gradientTransform="rotate(44.706 .657 22.508)scale(.16146 .20815)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ic9XFoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.14452 -4.26852 0 13.783 5.96)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="i6iVbNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57847 .71197 0 14.954 5.486)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iTJFYfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.61555 .7655 0 12.937 5.471)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="ivLGqnc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25737 -.30398 .1786 -.73878 15.805 8.775)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="i1itdzc" cx="0" cy="0" r="1" gradientTransform="matrix(.35309 -1.3085 .48524 .13094 15.839 4.232)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iGsk7ec" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -30.042 166.287)scale(1.69991 .91403)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iQWwxyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .74315 -1.15093 0 13.916 2.242)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iyJtkbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.36044 -.99696 1.5619 2.13135 11.062 5.26)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="i82pIqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08714 -.27997 0 14.06 6.76)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iha2SDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35813 -.56965 0 14.88 5.746)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iW1Uqxe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 8.806 -.727)scale(.16698 .22989)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLSWkrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35815 -.56968 0 12.948 5.746)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibw7MCU" cx="0" cy="0" r="1" gradientTransform="matrix(-.00341 -.2181 .26216 -.0041 12.822 5.844)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iWonAzc" width="23.977" height="13.398" x="6.016" y="16.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="iimMFpe" width="20.681" height="10.082" x="6.11" y="20.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".75"/></filter><filter id="iCb5gje" width="24.344" height="8.644" x="2.007" y="21.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="icE66Vb" width="2.686" height="2.686" x="24.571" y="13.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="iLahw1N" width="2.186" height="2.186" x="27.821" y="11.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="isZChfb" width="1.928" height="1.928" x="25.946" y="9.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="iD5KqSI" width="2.857" height="2.898" x="20.532" y="12.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.14902 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="ifJ4nMd" width="5.571" height="6.952" x="7.773" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="i3FsZbe" width="14.97" height="18.152" x="8.427" y="7.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.537255 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="iisCTNP" width="17.737" height="14.8" x="13.579" y="15.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation="1"/></filter><filter id="iTGp0xd" width="6.506" height="14.75" x="14.572" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".375"/></filter><filter id="i7Pryob" width="5.506" height="5.421" x="17.991" y="7.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".3"/></filter><filter id="irHF64G" width="1.678" height="1.478" x="11.076" y="5.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="iMRewIb" width="1.881" height="1.881" x="10.874" y="5.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".25"/></filter><filter id="i7lefqd" width="1.728" height="1.728" x="15.286" y="5.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="ioOWPnc" width="1.881" height="1.881" x="15.084" y="5.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".25"/></filter><filter id="iFu3iPT" width="4.591" height="5.373" x="11.633" y="3.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="icj6ypb" width="2.879" height="2.357" x="13.491" y="3.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".25"/></filter><filter id="iFpo1we" width="5.577" height="4.06" x="11.127" y="1.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="ir8ZIdc" width="2.279" height="2.687" x="12.671" y="5.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".375"/></filter><filter id="ioEcZcd" width="1.031" height="1.387" x="13.401" y="5.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".05"/></filter><filter id="ibQ1jfc" width="1.458" height="1.052" x="14.439" y="4.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="ihJav8d" width="1.458" height="1.052" x="12.161" y="4.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22993"/></filter><filter id="iPRUjFe" width=".459" height=".419" x="14.499" y="5.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".05"/></filter><filter id="icNYaVc" width=".617" height=".627" x="14.816" y="5.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".1"/></filter><filter id="igQ1MNc" width=".659" height=".683" x="12.85" y="5.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".1"/></filter><filter id="i4yiWCe" width=".515" height=".423" x="12.571" y="5.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".05"/></filter><filter id="i606cyi" width="1.667" height="1.04" x="14.226" y="4.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".15"/></filter><filter id="ihVDuXK" width="1.251" height=".615" x="12.141" y="4.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".075"/></filter><filter id="iu7JAsG" width=".864" height="1.421" x="11.421" y="3.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22993" stdDeviation=".125"/></filter><linearGradient id="ijJnbEe" x1="7.172" x2="16.735" y1="29.352" y2="29.352" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iMX3qoe" x1="16.86" x2="16.766" y1="30.258" y2="28.633" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="iPHWNcc" x1="21.172" x2="19.469" y1="21.914" y2="23" gradientUnits="userSpaceOnUse"><stop class="l20_z6baj"/><stop offset="1" class="spcerobbw"/></linearGradient><linearGradient id="iJ67Gde" x1="22.095" x2="23.329" y1="24.82" y2="26.102" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="inumkee" x1="5.891" x2="25.735" y1="29.227" y2="22.32" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="iw8OLic" x1="15.777" x2="15.777" y1="7.594" y2="25.555" gradientUnits="userSpaceOnUse"><stop class="nxcp0hivj"/><stop offset="1" class="p79aa0p9z"/></linearGradient><linearGradient id="iATB0jc" x1="23.651" x2="16.517" y1="12.49" y2="8.536" gradientUnits="userSpaceOnUse"><stop class="y60usm6nn"/><stop offset=".91" class="u6gia-bos"/></linearGradient><linearGradient id="iAWuoxl" x1="17.826" x2="20.269" y1="8.148" y2="21.384" gradientUnits="userSpaceOnUse"><stop class="yrtrc6n_d"/><stop offset="1" class="kkuk5w_fi"/></linearGradient><linearGradient id="iMi4Dpc" x1="22.438" x2="18.766" y1="11.867" y2="7.977" gradientUnits="userSpaceOnUse"><stop class="tgz_9qxcq"/><stop offset="1" class="zvqcq9hxr"/></linearGradient><linearGradient id="iMmyond" x1="11.814" x2="11.531" y1="6.172" y2="6.172" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iUf5y3q" x1="16.506" x2="16.143" y1="5.566" y2="6.688" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iXxsFrb" x1="15.702" x2="12.322" y1="6.221" y2="6.725" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="imuzchd" x1="11.528" x2="12.53" y1="7.414" y2="7.352" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="ix3wJMb" x1="14.34" x2="18.154" y1="4.726" y2="3.414" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="i877fue" x1="13.534" x2="13.949" y1="6.513" y2="6.513" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iWCfoyb" x1="14.331" x2="13.877" y1="6.656" y2="6.649" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iuzlnbd" x1="14.002" x2="14.002" y1="6.984" y2="6.731" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="ij8Jmec" x1="13.457" x2="13.649" y1="7.699" y2="7.395" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iwMmSjc" x1="15.224" x2="15.085" y1="5.771" y2="5.856" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0s2zad" x1="13.278" x2="13.139" y1="5.771" y2="5.856" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwyeLld" x1="15.23" x2="15.044" y1="4.824" y2="4.445" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iCALbub" x1="12.882" x2="12.357" y1="4.768" y2="4.548" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iFctdqd" x1="11.852" x2="11.852" y1="3.876" y2="4.828" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-surfing-dark" /></template>
<style>
.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ae99og76i {
  cx: 26.86px;
  cy: 10.715px;
  r: 0.914px;
}

.agnv3q_5r {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m16.048 3.182l.19.094a.87.87 0 0 1 .451.945l-.26 1.345c-.024.139-.116.232-.254.236h-.008s.024-.401.047-.637c.02-.192-.014-.25-.19-.425a.56.56 0 0 1-.166-.378v-.377a.255.255 0 0 0-.19-.237a7.3 7.3 0 0 0-1.732-.188a7.3 7.3 0 0 0-1.733.188a.23.23 0 0 0-.19.236v.378a.47.47 0 0 1-.166.378l-.072.07c-.095.071-.142.213-.142.331c.024.26.047.637.047.637h-.021a.28.28 0 0 1-.264-.236l-.26-1.345a.9.9 0 0 1 .474-.92l.19-.095c.119-.07.237-.165.356-.26l.427-.448a.87.87 0 0 1 .974-.142c.237.071.498.071.736 0c.356-.118.76-.023 1.044.236l.356.354a1 1 0 0 0 .356.26");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.bflyorafd {
  cx: 16.025px;
  cy: 6.049px;
  r: 0.739px;
}

.bgy81xi6b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.65 4.781c.19-.033.56-.024.817.176");
}

.bu3azkbir {
  stop-color: var(--svg-color--61504f, #61504F);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c85nnpbdi {
  cx: 11.814px;
  cy: 6.049px;
  r: 0.739px;
}

.cat6cuzen {
  fill: var(--svg-color--332024, #332024);
  d: path("m13.794 5.995l-.363.752c-.045.155.063.31.216.31h.326c.153 0 .261-.158.216-.31l-.22-.752c-.048-.167-.126-.167-.175 0");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.cj_334bge {
  d: path("M13.309 5.884c0-.127-.104-.212-.132-.238l-.127.123l.078.16z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.df1lq47cu {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.246 4.845l.001-.001l.002-.002l.006-.004l.068-.048a1.25 1.25 0 0 1 .846-.163a.236.236 0 1 1-.073.467a.78.78 0 0 0-.522.097l-.024.016l-.004.003a.236.236 0 0 1-.3-.365");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.f4ne0bb3h {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m13.747 5.923l-.235.752a.24.24 0 0 0 .23.31h.348a.24.24 0 0 0 .23-.31l-.235-.752c-.05-.167-.286-.167-.338 0");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fjwi8wb7i {
  d: path("M14.851 5.62c.028.037-.03.083-.097.133s-.116.085-.144.047c-.028-.037.003-.108.07-.158c.066-.05.143-.06.171-.022");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fqeviqb2e {
  stop-color: var(--svg-color--1154b9, #1154B9);
}

.frgrxi9fy {
  d: path("M10.684 11.684c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g99cn0bet {
  stop-color: var(--svg-color--2965ce, #2965CE);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gq1i90b_a {
  stop-color: var(--svg-color--2965ce, #2965CE);
  stop-opacity: 0;
}

.gwjr899hs {
  d: path("M12.759 11.64c-.432-1.715.169-3.16.507-3.484l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.799 1.589 3.592a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.274-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.512 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.191 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.825-2.562-3.988c-.062-.165-.23-.532-.574-.532c-.275 0-.59.352-.809.73l-4.667 7.138a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.085c-.03-.13-.218-.711-.585-2.172");
}

.gxtql4gqb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.34 5.01c.145-.127.46-.262.851-.2");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.herbgz03w {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.611 14.932a.375.375 0 1 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 0 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.i34rybopj {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.797px;
  rx: 0.299px;
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i5vej436q {
  fill: var(--svg-color--4c3531, #4C3531);
  d: path("M7.602 12.764h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.i9-uutisp {
  d: path("M21.985 27.32L7.61 28.82c4.687-2.24 11.938-4.406 14.375-6.187c1.826-1.334 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.iehf4nbfv {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m15.562 4.845l-.002-.001l-.002-.002l-.005-.004l-.068-.048a1.25 1.25 0 0 0-.846-.163a.236.236 0 1 0 .073.467a.78.78 0 0 1 .522.097l.024.016l.004.003a.236.236 0 0 0 .3-.365");
}

.ikuisnbzy {
  d: path("m15.67 3.56l-1.362.454a.463.463 0 0 0 .208.899l1.354-.182z");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j83otbcan {
  fill: var(--svg-color--4e3732, #4E3732);
  d: path("m7.305 27.336l1.172-2.39l1.766.304v1.04z");
}

.jhlh1_3ek {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.736H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jioe1_9gu {
  stop-color: var(--svg-color--5391be, #5391BE);
}

.k6_me0blg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M14.851 5.62c.028.037-.03.083-.097.133s-.116.085-.144.047c-.028-.037.003-.108.07-.158c.066-.05.143-.06.171-.022");
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kkmm611rh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.91 3.92v.396c-.004.065-.032.212-.114.274");
}

.kkuk5w_fi {
  stop-color: var(--svg-color--6096e0, #6096E0);
}

.kn6afsb3f {
  stop-color: var(--svg-color--58443e, #58443E);
  stop-opacity: 0;
}

.kp-2efbsj {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.404 14.127s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l20_z6baj {
  stop-color: var(--svg-color--695857, #695857);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l89w7ttua {
  fill-rule: evenodd;
  d: path("M7.127 13.531c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 1 1-.216.718");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj0l7tb9r {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
}

.ljni-v35c {
  fill-rule: evenodd;
  d: path("M5.25 14.655q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a.7.7 0 0 0-.095.105");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m9t4-f_6h {
  d: path("m16.048 3.182l.19.094a.87.87 0 0 1 .451.945l-.26 1.345c-.024.139-.116.232-.254.236h-.008s.024-.401.047-.637c.02-.192-.014-.25-.19-.425a.56.56 0 0 1-.166-.378v-.377a.255.255 0 0 0-.19-.237a7.3 7.3 0 0 0-1.732-.188a7.3 7.3 0 0 0-1.733.188a.23.23 0 0 0-.19.236v.378a.47.47 0 0 1-.166.378l-.072.07c-.095.071-.142.213-.142.331c.024.26.047.637.047.637h-.021a.28.28 0 0 1-.264-.236l-.26-1.345a.9.9 0 0 1 .474-.92l.19-.095c.119-.07.237-.165.356-.26l.427-.448a.87.87 0 0 1 .974-.142c.237.071.498.071.736 0c.356-.118.76-.023 1.044.236l.356.354a1 1 0 0 0 .356.26");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md-locuzc {
  cx: 11.814px;
  cy: 6.049px;
  r: 0.44px;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mzrna-ble {
  d: path("M12.947 5.536a.394.394 0 0 0-.38.498h.762a.397.397 0 0 0-.381-.498");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.na5vpgbch {
  stop-color: var(--svg-color--4b3234, #4B3234);
}

.nbncwobqn {
  stop-color: var(--svg-color--6b5957, #6B5957);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nxcp0hivj {
  stop-color: var(--svg-color--3794e2, #3794E2);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o2riu6e9b {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.25 14.655q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a.7.7 0 0 0-.095.105");
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.oipf0m4co {
  stop-color: var(--svg-color--4861ab, #4861AB);
  stop-opacity: 0;
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.okzrnob_x {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.326 7.244c.17.089.373.14.59.14c.219 0 .42-.051.59-.14a.12.12 0 0 1 .14.023a.11.11 0 0 1 .012.142m-1.332-.165l1.29.137m-1.29-.137a.12.12 0 0 0-.14.024a.11.11 0 0 0-.012.141m.152-.165l-.11.137m1.442.028l-.042-.028m.042.028l-.042-.028m.042.028a.89.89 0 0 1-.742.397a.89.89 0 0 1-.742-.397m1.442-.028a.84.84 0 0 1-.7.375a.84.84 0 0 1-.7-.375m-.042.028l.041-.028m-.041.028l.041-.028");
}

.olg-72bto {
  d: path("M16.782 13.438c-.65-1.28-1.166-3.185-1.443-4.424a.714.714 0 0 1 .588-.856c.447-.074.855.272.91.723c.205 1.698.95 3.373 1.445 4.682c.578 1.53.312 1.062.234 3.515c-.057 1.782 1.266 3.25 1.813 4.11l-.407.21c-.609-.828-2.203-2.945-2.203-4.851c0-1.791.063-1.14-.937-3.11");
}

.on9u00bey {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.273c1.209-.02 3.782.829 4.104 4");
}

.ono7f8b6y {
  d: path("M15.233 5.879a.37.37 0 0 0-.103-.205l-.115.126l.052.101z");
}

.ooocs2okn {
  fill: var(--svg-color--4c3531, #4C3531);
  d: path("M6.126 14.875c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.p2jsddcqm {
  fill: var(--svg-color--000, #000);
  d: path("M14.655 5.93c0-.125.1-.225.226-.225a.225.225 0 0 1 .2.33h-.4a.2.2 0 0 1-.026-.105");
}

.p79aa0p9z {
  stop-color: var(--svg-color--3066bf, #3066BF);
}

.pekg0u7cp {
  d: path("M20.68 13.837c.256-.588.373-1.22.399-1.462l2.047.024c.046.268-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.02a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.042c-.098-.082-.219-.175.031-.746");
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qnmjgylyq {
  d: path("M24.458 21.25L2.29 28.939a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.1 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.002c.094-.25.047-1.03-.5-1.453c-.437-.337-1.105-.185-1.355-.07");
}

.qpf-7tbbk {
  d: path("M14.88 5.536a.394.394 0 0 1 .38.498h-.761a.395.395 0 0 1 .381-.498");
}

.qv62lactv {
  cx: 28.864px;
  cy: 12.801px;
  r: 1.043px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0iiaeguw {
  stop-color: var(--svg-color--3168c8, #3168C8);
  stop-opacity: 0;
}

.r95brsblk {
  stop-color: var(--svg-color--3a1c21, #3A1C21);
}

.raew06bbn {
  d: path("M11.659 5.778h.022s-.024-.377-.048-.637c0-.118.048-.26.143-.33l.07-.071a.47.47 0 0 0 .167-.378v-.378a.23.23 0 0 1 .19-.236c.285-.07.878-.188 1.733-.188c.854 0 1.448.118 1.733.188c.095.024.19.118.19.236v.378c0 .142.071.283.166.378c.222.155.208.241.19.425c-.024.236-.048.637-.048.637h.008l-.117 1.752c-.071.783-.687 1.329-1.421 1.329h-1.42c-.759 0-1.35-.546-1.422-1.33z");
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.s18l7_bne {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.857 5.416a.62.62 0 0 0-.6.468c-.02.077.04.15.119.15h.987a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.606-.498");
}

.s2ikxxbfc {
  cx: 25.864px;
  cy: 14.75px;
  r: 1.293px;
}

.sazwi3bdn {
  d: path("m23.469 25.315l-.422-1.143l-2.351.536l2.225 1.099a.396.396 0 0 0 .547-.492");
}

.sfnr8vh0d {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.973 5.416c.288 0 .533.199.599.468a.12.12 0 0 1-.118.15h-.988a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .607-.498");
}

.siw2d1f7p {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("M21.985 27.32L7.61 28.82c4.687-2.24 11.938-4.406 14.375-6.187c1.826-1.334 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.so3eyo06u {
  d: path("M26.485 24.32c.981-2.278.626-3.887.055-5.013c-.474-.936-.003-1.662 1.018-1.421c.737.174 1.364.694 1.54 1.43c.721 3.026-.313 6.182-3.582 7.817c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.723 10.906-4.282");
}

.spcerobbw {
  stop-color: var(--svg-color--371f23, #371F23);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t502ec3cr {
  stop-color: var(--svg-color--4861ab, #4861AB);
}

.t5lf5ccyt {
  stop-color: var(--svg-color--5391be, #5391BE);
  stop-opacity: 0;
}

.t7r9i6b3f {
  stop-color: var(--svg-color--58443e, #58443E);
}

.tgz_9qxcq {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
}

.to9zfdmjz {
  stop-color: var(--svg-color--1154b9, #1154B9);
  stop-opacity: 0;
}

.u--ocwryb {
  d: path("M19.837 23a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.u2-yf8bkl {
  cx: 12.829px;
  cy: 5.705px;
  rx: 0.172px;
  ry: 0.087px;
}

.u6gia-bos {
  stop-color: var(--svg-color--418dd5, #418DD5);
}

.ub7ea32uh {
  stop-color: var(--svg-color--635351, #635351);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uu4f6-byw {
  d: path("M6.126 14.875c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.vb809lo-e {
  d: path("M19.75 29.736H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.vgauzicqp {
  stop-color: var(--svg-color--3168c8, #3168C8);
}

.vgekv3bdy {
  stop-color: var(--svg-color--3e2828, #3E2828);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w7mkf5ikd {
  stop-color: var(--svg-color--635351, #635351);
  stop-opacity: 0;
}

.wc05b2bod {
  fill-rule: evenodd;
  d: path("M5.611 14.932a.375.375 0 1 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 0 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.wfnn4zbei {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M7.127 13.531c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 1 1-.216.718");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.x-wvar5pp {
  fill: var(--svg-color--000, #000);
  d: path("M13.173 5.93c0-.125-.1-.225-.225-.225a.225.225 0 0 0-.2.33h.399a.2.2 0 0 0 .026-.105");
}

.x0ye_xb8j {
  cx: 12.829px;
  cy: 5.705px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.x2d1t4xtf {
  fill-rule: evenodd;
  d: path("M5.404 14.127s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xcdcq7biu {
  cx: 16.025px;
  cy: 6.049px;
  r: 0.44px;
}

.xt887yc-y {
  d: path("M17.568 10.265a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.545-1.589-3.592c-1.381-1.07-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.671");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xtp47zbsj {
  d: path("m7.305 27.336l1.172-2.39l1.766.304v1.04z");
}

.xwg01lbun {
  d: path("m13.747 5.923l-.235.752a.24.24 0 0 0 .23.31h.348a.24.24 0 0 0 .23-.31l-.235-.752c-.05-.167-.286-.167-.338 0");
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y60usm6nn {
  stop-color: var(--svg-color--46a5ef, #46A5EF);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yrtrc6n_d {
  stop-color: var(--svg-color--54acfa, #54ACFA);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z71t5ubny {
  fill: var(--svg-color--3086d6, #3086D6);
  d: path("M10.684 11.684c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zga9nrbjv {
  stop-color: var(--svg-color--61504f, #61504F);
  stop-opacity: 0;
}

.zo0htm39v {
  cx: 16.025px;
  cy: 6.049px;
  r: 0.44px;
  fill: var(--svg-color--463133, #463133);
}

.zrzxj2epv {
  stop-color: var(--svg-color--2b68b8, #2B68B8);
  stop-opacity: 0;
}

.zvqcq9hxr {
  stop-color: var(--svg-color--57b4fd, #57B4FD);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
