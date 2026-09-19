<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ia9Fodd)" class="mb0n-8q3d"/><path fill="url(#i6Sh1Yg)" class="mb0n-8q3d"/><path fill="url(#iesO6pd)" class="x2jlfyb6f"/><rect fill="url(#itxeAug)" class="vfhurybye"/><rect fill="url(#iAqO1Ab)" class="vfhurybye"/><g filter="url(#iWQYKOe)"><path fill="url(#i0a1JGe)" class="azawhbcxq"/><path fill="url(#ifHoYIy)" class="azawhbcxq"/><path fill="url(#ioeWaXb)" class="azawhbcxq"/></g><path fill="url(#iD2uKiu)" class="azawhbcxq"/><path fill="url(#iTvJqdb)" class="azawhbcxq"/><path fill="url(#iI1mUoc)" class="azawhbcxq"/><path fill="url(#ip8YHcc)" class="azawhbcxq"/><g filter="url(#i6OQRAb)"><path stroke="url(#iU66fOe)" class="tpfs9rb4e"/></g><path fill="url(#iLACyie)" class="fav2t547e"/><path class="ji621ab2s"/><path fill="url(#if48Yfe)" class="pwb1owbqd"/><g filter="url(#i0KdYcd)"><path class="wlivwtbej"/><path fill="url(#i3NJiQe)" class="aakem1mws"/><path fill="url(#i0u0yCd)" class="aakem1mws"/><path fill="url(#ipG4kse)" class="aakem1mws"/></g><rect fill="url(#iSsBPoc)" class="uiq6v0czi"/><rect fill="url(#iItog2i)" class="uiq6v0czi"/><rect fill="url(#iVwExup)" class="uiq6v0czi"/><rect fill="url(#iYQd5Pd)" class="uiq6v0czi"/><rect fill="url(#iw981vl)" transform="rotate(-17.452 5.516 21.469)" class="ppkjr9zdh"/><rect fill="url(#iNFV9Ib)" transform="rotate(-17.452 5.516 21.469)" class="ppkjr9zdh"/><rect fill="url(#iSNQUte)" transform="rotate(-17.452 5.516 21.469)" class="ppkjr9zdh"/><rect fill="url(#iKIiFUd)" transform="rotate(-17.452 5.516 21.469)" class="ppkjr9zdh"/><rect fill="url(#i9X3sWd)" transform="rotate(-30.06 2.878 22.868)" class="bgfu0vbvz"/><rect fill="url(#ihlYJDc)" transform="rotate(-30.06 2.878 22.868)" class="bgfu0vbvz"/><rect fill="url(#iPG81RC)" transform="rotate(-30.06 2.878 22.868)" class="bgfu0vbvz"/><rect fill="url(#iOApQwd)" transform="rotate(-30.06 2.878 22.868)" class="bgfu0vbvz"/><rect fill="url(#injl7gb)" transform="rotate(-32.714 1.35 25.317)" class="izapptm4m"/><rect fill="url(#iIYCapb)" transform="rotate(-32.714 1.35 25.317)" class="izapptm4m"/><rect fill="url(#ixbgxPd)" transform="rotate(-32.714 1.35 25.317)" class="izapptm4m"/><g filter="url(#i3EFDnb)"><path class="mpb4aacxt"/><path fill="url(#inLrOLe)" class="nuh0chd7n"/><path fill="url(#iW4bGzd)" class="nuh0chd7n"/><path fill="url(#iidg4se)" class="nuh0chd7n"/><path fill="url(#iCiwD5c)" class="nuh0chd7n"/><path fill="url(#i3SXiTd)" class="nuh0chd7n"/><path fill="url(#iXIb8xb)" class="nuh0chd7n"/></g><rect transform="matrix(-1 0 0 1 23.28 20.917)" class="fk_sd4b3f"/><rect fill="url(#i5cKy7J)" transform="matrix(-1 0 0 1 23.28 20.917)" class="lvqejss-o"/><rect fill="url(#iFbacFb)" transform="matrix(-1 0 0 1 23.28 20.917)" class="lvqejss-o"/><rect transform="scale(-1 1)rotate(-17.452 56.697 97.01)" class="l257jccgu"/><rect fill="url(#iAe9aMb)" transform="scale(-1 1)rotate(-17.452 56.697 97.01)" class="i7m2j00fs"/><rect fill="url(#i56EY8b)" transform="scale(-1 1)rotate(-17.452 56.697 97.01)" class="i7m2j00fs"/><rect transform="scale(-1 1)rotate(-30.061 28.02 65.66)" class="uvhjscb1o"/><rect fill="url(#iXxxUfc)" transform="scale(-1 1)rotate(-30.061 28.02 65.66)" class="gl17utj4l"/><rect fill="url(#iw4dd4c)" transform="scale(-1 1)rotate(-30.061 28.02 65.66)" class="gl17utj4l"/><rect fill="url(#ixP16ad)" transform="scale(-1 1)rotate(-32.714 27.803 64.872)" class="ij5lprb2c"/><rect fill="url(#iWnLhMc)" transform="scale(-1 1)rotate(-32.714 27.803 64.872)" class="ij5lprb2c"/><rect fill="url(#itioSUc)" transform="scale(-1 1)rotate(-32.714 27.803 64.872)" class="ij5lprb2c"/><path fill="url(#iZDmtFc)" class="a8ryvfbmd"/><path fill="url(#io8oDKw)" class="ftcaxw6ua"/><path stroke="url(#iQh37Ae)" class="enyqww8wr"/><path stroke="url(#iAAC7Zb)" class="jcyrp08ix"/><g filter="url(#inLz7TN)"><circle fill="url(#ihWpd9d)" class="yveiieo1a"/></g><circle fill="url(#iT6Vuyb)" class="s705ubb2m"/><circle class="z6xm9cbni"/><g filter="url(#iQPUl1d)"><circle fill="url(#i17EGDb)" transform="matrix(-1 0 0 1 18.74 13.677)" class="el7r9pbsw"/></g><circle fill="url(#i51g7Pd)" transform="matrix(-1 0 0 1 18.521 13.442)" class="y2c1oq0fx"/><circle fill="url(#iyg3sde)" transform="matrix(-1 0 0 1 18.521 13.442)" class="y2c1oq0fx"/><circle transform="matrix(-1 0 0 1 18.502 13.442)" class="m8bj1mb9s"/><g filter="url(#iUVTbQd)"><path fill="url(#ifUefte)" class="n9lie4b0a"/></g><g filter="url(#iFlVf5d)"><path fill="url(#ikpiexc)" class="rbf98joze"/></g><path class="kingbac4q"/><path fill="url(#iwR3gYb)" class="jpym9qrbx"/><path fill="url(#iKimyQc)" class="jpym9qrbx"/><path fill="url(#iGNi9ve)" class="jpym9qrbx"/><path fill="url(#iHUoHzb)" class="jpym9qrbx"/><path fill="url(#iX75csc)" class="jpym9qrbx"/><g filter="url(#ilSLTvc)"><path stroke="url(#i0ffxVM)" class="iieajnjfy"/></g><defs><radialGradient id="ia9Fodd" cx="0" cy="0" r="1" gradientTransform="rotate(100.841 7.301 11.315)scale(16.593 29.0245)" gradientUnits="userSpaceOnUse"><stop class="umebve3qj"/><stop offset="1" class="l17heo7fk"/></radialGradient><radialGradient id="i6Sh1Yg" cx="0" cy="0" r="1" gradientTransform="rotate(115.364 8.514 8.683)scale(4.66882 13.1888)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="opdni9jvk"/><stop offset="1" class="n_euk-b7u"/></radialGradient><radialGradient id="iesO6pd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5625 22.9424 0 16.038 29.897)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="udi_mfp4v"/><stop offset="1" class="rvq6gmb5w"/></radialGradient><radialGradient id="itxeAug" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.6875 -3.80398 0 16.017 20.585)" gradientUnits="userSpaceOnUse"><stop class="eb8sbmb8j"/><stop offset=".686" class="zgqvtpbpd"/></radialGradient><radialGradient id="iAqO1Ab" cx="0" cy="0" r="1" gradientTransform="matrix(.29157 4.32031 -2.99316 .202 15.726 21.186)" gradientUnits="userSpaceOnUse"><stop offset=".529" class="iv7v1nb3o"/><stop offset=".924" class="q53_zdbrw"/></radialGradient><radialGradient id="ifHoYIy" cx="0" cy="0" r="1" gradientTransform="matrix(-5.38562 0 0 -11.4062 21.986 15.241)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="e2nz_4b0g"/><stop offset="1" class="ulmooebvp"/></radialGradient><radialGradient id="ioeWaXb" cx="0" cy="0" r="1" gradientTransform="matrix(3.96875 0 0 10.1562 9.632 15.335)" gradientUnits="userSpaceOnUse"><stop offset=".449" class="nhd76xusb"/><stop offset="1" class="nzw280tix"/></radialGradient><radialGradient id="iTvJqdb" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 .6875 -3.37898 9.52257 9.757 10.928)" gradientUnits="userSpaceOnUse"><stop class="q9gxalg3c"/><stop offset="1" class="cxhprdb1z"/></radialGradient><radialGradient id="iI1mUoc" cx="0" cy="0" r="1" gradientTransform="rotate(-13.931 66.22 -36.591)scale(12.3314 28.1116)" gradientUnits="userSpaceOnUse"><stop offset=".809" class="mlx0qzhjk"/><stop offset=".98" class="acyq6gpiw"/></radialGradient><radialGradient id="ip8YHcc" cx="0" cy="0" r="1" gradientTransform="rotate(180 9.09 6.714)scale(2.28125)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="gb43dybux"/><stop offset="1" class="iq0niabpl"/></radialGradient><radialGradient id="iLACyie" cx="0" cy="0" r="1" gradientTransform="rotate(-81.193 18.078 1.31)scale(2.24522 3.5001)" gradientUnits="userSpaceOnUse"><stop class="nrrnwgb2j"/><stop offset="1" class="ju7pygbji"/></radialGradient><radialGradient id="if48Yfe" cx="0" cy="0" r="1" gradientTransform="matrix(.51562 -1.05469 2.4217 1.18394 15 18.217)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="hbx3qwnwa"/><stop offset=".929" class="g3i-1pbcq"/></radialGradient><radialGradient id="i3NJiQe" cx="0" cy="0" r="1" gradientTransform="rotate(73.968 -11.51 15.35)scale(6.46576 13.0703)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="bxi9tgmwe"/><stop offset="1" class="tn-w78xgx"/></radialGradient><radialGradient id="i0u0yCd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93323 -.03125 .0265 -1.639 14.244 27.178)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="gbny4_b4j"/><stop offset="1" class="glfls735f"/></radialGradient><radialGradient id="ipG4kse" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59378 3.81248 -2.48353 -1.68964 11.842 24.96)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="oxi0f3b2m"/><stop offset="1" class="vl_ql576y"/></radialGradient><radialGradient id="iSsBPoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6161 1.22861 0 10.293 23.533)" gradientUnits="userSpaceOnUse"><stop class="iw38491ye"/><stop offset="1" class="zl7ptbcaa"/></radialGradient><radialGradient id="iItog2i" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22395 0 0 -3.23423 10.681 23.298)" gradientUnits="userSpaceOnUse"><stop class="lxs7f3b1j"/><stop offset="1" class="u84zz4ukw"/></radialGradient><radialGradient id="iYQd5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.33793 2.79084 -2.2828 -.27641 10.117 21.818)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="ws-ofvbpp"/><stop offset="1" class="i2p625zaz"/></radialGradient><radialGradient id="iw981vl" cx="0" cy="0" r="1" gradientTransform="matrix(.20372 -3.21174 1.70613 .10822 6.079 24.683)" gradientUnits="userSpaceOnUse"><stop class="x9syn5bsf"/><stop offset="1" class="ippisxk_c"/></radialGradient><radialGradient id="iSNQUte" cx="0" cy="0" r="1" gradientTransform="matrix(-.02888 -2.796 1.23588 -.01277 7.45 24.663)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="got22lb_s"/><stop offset="1" class="m5racngae"/></radialGradient><radialGradient id="iKIiFUd" cx="0" cy="0" r="1" gradientTransform="matrix(.4982 -1.16022 3.58632 1.53998 5.806 25.128)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="yps5thqls"/><stop offset="1" class="aje_gtbfo"/></radialGradient><radialGradient id="i9X3sWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.52841 -2.3289 3.00123 1.96966 3.07 25.396)" gradientUnits="userSpaceOnUse"><stop class="lv9f4sbft"/><stop offset="1" class="gjthckb9a"/></radialGradient><radialGradient id="ihlYJDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.14765 -2.39628 1.0581 -.0652 4.413 26.1)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="p7xh8mbkr"/><stop offset="1" class="so0nfjs_n"/></radialGradient><radialGradient id="iPG81RC" cx="0" cy="0" r="1" gradientTransform="rotate(-48.526 30.563 10.128)scale(1.97399 4.7131)" gradientUnits="userSpaceOnUse"><stop class="o5pi4qbos"/><stop offset="1" class="mrh8oxbyb"/></radialGradient><radialGradient id="iOApQwd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4011 -3.5602 2.78505 1.09605 3.124 26.567)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="slfwwoboa"/><stop offset="1" class="htek_b-aw"/></radialGradient><radialGradient id="injl7gb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.353 12.242 12.83)scale(2.55343 1.41015)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="x4_rgjbgr"/><stop offset="1" class="kyxlbjczl"/></radialGradient><radialGradient id="iIYCapb" cx="0" cy="0" r="1" gradientTransform="matrix(.64228 -.85953 1.5214 1.13686 1.622 27.76)" gradientUnits="userSpaceOnUse"><stop class="o1u4v1x-w"/><stop offset="1" class="rrdpflbyy"/></radialGradient><radialGradient id="ixbgxPd" cx="0" cy="0" r="1" gradientTransform="matrix(.53113 1.91968 -1.32546 .36672 3.298 25.883)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="libnoft0w"/><stop offset="1" class="oi5b6vt4l"/></radialGradient><radialGradient id="inLrOLe" cx="0" cy="0" r="1" gradientTransform="rotate(106.149 4.435 20.728)scale(6.42022 13.0626)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="bxi9tgmwe"/><stop offset="1" class="tn-w78xgx"/></radialGradient><radialGradient id="iW4bGzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.93323 -.03101 .0261 1.62651 17.756 27.2)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="gbny4_b4j"/><stop offset="1" class="glfls735f"/></radialGradient><radialGradient id="iidg4se" cx="0" cy="0" r="1" gradientTransform="matrix(2.59376 3.78341 -2.47147 1.69434 20.159 24.997)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="oxi0f3b2m"/><stop offset="1" class="vl_ql576y"/></radialGradient><radialGradient id="iCiwD5c" cx="0" cy="0" r="1" gradientTransform="rotate(113.738 6.022 22.127)scale(2.83347 1.67501)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="qzo_nkzbd"/><stop offset="1" class="ht552mbaq"/></radialGradient><radialGradient id="i3SXiTd" cx="0" cy="0" r="1" gradientTransform="rotate(116.054 5.457 20.336)scale(3.13062 2.06753)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="jjhcfiagl"/><stop offset="1" class="d2h5kyjkp"/></radialGradient><radialGradient id="iXIb8xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.09375 -3.72984 0 23.545 23.429)" gradientUnits="userSpaceOnUse"><stop class="i-ilo59wi"/><stop offset="1" class="gew0dbs3i"/></radialGradient><radialGradient id="i5cKy7J" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.43452 -1.62962 0 .207 .257)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="iFbacFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.90968 -2.1392 0 .98 .862)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="iAe9aMb" cx="0" cy="0" r="1" gradientTransform="matrix(.07378 3.33306 -1.58148 .035 .381 .326)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="i56EY8b" cx="0" cy="0" r="1" gradientTransform="rotate(97.643 .058 .878)scale(2.7887 2.05026)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="iXxxUfc" cx="0" cy="0" r="1" gradientTransform="matrix(.07447 3.3649 -1.59659 .03534 .385 .33)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="iw4dd4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.74734 2.73501 -2.01078 -.54945 1.318 1.001)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="ixP16ad" cx="0" cy="0" r="1" gradientTransform="rotate(86.011 .058 .65)scale(2.14376 1.52149)" gradientUnits="userSpaceOnUse"><stop class="xq9watbjp"/><stop offset="1" class="ve2ow0b5f"/></radialGradient><radialGradient id="iWnLhMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.82612 .3373 -.5514 2.98514 .616 .826)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="sl7iwijia"/><stop offset="1" class="sce_y6bah"/></radialGradient><radialGradient id="itioSUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71567 1.75021 -2.23482 -.91383 1.038 .949)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="es563lbhm"/><stop offset=".926" class="rdi-wfxqd"/></radialGradient><radialGradient id="ihWpd9d" cx="0" cy="0" r="1" gradientTransform="rotate(69.179 -3.03 15.179)scale(3.15946)" gradientUnits="userSpaceOnUse"><stop class="ltf0tqb9y"/><stop offset="1" class="enitdihfo"/></radialGradient><radialGradient id="iT6Vuyb" cx="0" cy="0" r="1" gradientTransform="rotate(95.856 .824 12.83)scale(1.83772 1.80959)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="h50m5ib7f"/><stop offset="1" class="bng_m2b0t"/></radialGradient><radialGradient id="i17EGDb" cx="0" cy="0" r="1" gradientTransform="rotate(48.116 -1.842 1.568)scale(2.66802)" gradientUnits="userSpaceOnUse"><stop class="bw57fdcce"/><stop offset="1" class="hkndu6boi"/></radialGradient><radialGradient id="i51g7Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2461 1.67187 -1.6463 -.24233 1.645 1.426)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="ogpl8rbbb"/><stop offset="1" class="w0ry1tv8g"/></radialGradient><radialGradient id="ifUefte" cx="0" cy="0" r="1" gradientTransform="rotate(-179.479 10.194 6.48)scale(3.43734 3.6257)" gradientUnits="userSpaceOnUse"><stop class="k589lpbub"/><stop offset=".808" class="ebc1zfyja"/></radialGradient><radialGradient id="iwR3gYb" cx="0" cy="0" r="1" gradientTransform="rotate(-99.386 15.182 .897)scale(4.64024 3.52424)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="e-l33-bot"/><stop offset="1" class="nxovy29zu"/></radialGradient><radialGradient id="iHUoHzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04687 3.76333 0 16.054 16.725)" gradientUnits="userSpaceOnUse"><stop class="y7xy7bb_m"/><stop offset="1" class="xjomt31wk"/></radialGradient><radialGradient id="iX75csc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9375 -3.86566 0 16.017 13.928)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="p0u5ydomu"/><stop offset="1" class="woms0-bkw"/></radialGradient><radialGradient id="i0ffxVM" cx="0" cy="0" r="1" gradientTransform="rotate(116.934 8.035 9.118)scale(2.17322 4.07335)" gradientUnits="userSpaceOnUse"><stop class="ctgbwlbis"/><stop offset="1" class="embjs61jm"/></radialGradient><linearGradient id="i0a1JGe" x1="16.03" x2="16.03" y1="6.831" y2="21.475" gradientUnits="userSpaceOnUse"><stop offset=".124" class="dbiijrl4h"/><stop offset="1" class="icg-h_npp"/></linearGradient><linearGradient id="iD2uKiu" x1="16.036" x2="16.036" y1="21.71" y2="16.553" gradientUnits="userSpaceOnUse"><stop offset=".055" class="xtb7f1b8t"/><stop offset="1" class="f_4a2tb1d"/></linearGradient><linearGradient id="iU66fOe" x1="14.218" x2="14.757" y1="19.444" y2="17.694" gradientUnits="userSpaceOnUse"><stop class="hmiiesz4q"/><stop offset="1" class="yq3urh0vb"/></linearGradient><linearGradient id="iVwExup" x1="8.72" x2="9.342" y1="22.96" y2="22.944" gradientUnits="userSpaceOnUse"><stop class="zbdko4y_s"/><stop offset="1" class="d5osmbc_d"/></linearGradient><linearGradient id="iNFV9Ib" x1="5.347" x2="6.407" y1="23.666" y2="23.639" gradientUnits="userSpaceOnUse"><stop class="j614okoao"/><stop offset="1" class="l2cbxb5tg"/></linearGradient><linearGradient id="iZDmtFc" x1="9.382" x2="12.341" y1="15.462" y2="19.178" gradientUnits="userSpaceOnUse"><stop class="j516ynx1g"/><stop offset=".717" class="djuzlabni"/><stop offset="1" class="ong7-kbio"/></linearGradient><linearGradient id="io8oDKw" x1="21.991" x2="19.944" y1="15.71" y2="19.272" gradientUnits="userSpaceOnUse"><stop class="emw7xxb2n"/><stop offset=".689" class="qczal5bjq"/><stop offset="1" class="ltqercvec"/></linearGradient><linearGradient id="iQh37Ae" x1="12.895" x2="12.71" y1="11.479" y2="10.854" gradientUnits="userSpaceOnUse"><stop class="mfys3hj4f"/><stop offset=".615" class="qudy1_y1m"/></linearGradient><linearGradient id="iAAC7Zb" x1="19.21" x2="19.39" y1="11.487" y2="10.866" gradientUnits="userSpaceOnUse"><stop class="mfys3hj4f"/><stop offset=".615" class="qudy1_y1m"/></linearGradient><linearGradient id="iyg3sde" x1="1.549" x2="1.549" y1="1.191" y2="1.801" gradientUnits="userSpaceOnUse"><stop class="f4-a9nvel"/><stop offset="1" class="gyuwqf8co"/></linearGradient><linearGradient id="ikpiexc" x1="15.871" x2="15.871" y1="13.553" y2="16.928" gradientUnits="userSpaceOnUse"><stop class="odwb5qh_v"/><stop offset="1" class="mneke1b_s"/></linearGradient><linearGradient id="iKimyQc" x1="16.017" x2="16.017" y1="13.35" y2="14.694" gradientUnits="userSpaceOnUse"><stop class="p3hupxtfd"/><stop offset="1" class="bp9n2ccrq"/></linearGradient><linearGradient id="iGNi9ve" x1="14.903" x2="15.39" y1="15.585" y2="15.678" gradientUnits="userSpaceOnUse"><stop class="m7a_bec-v"/><stop offset="1" class="th_2jcizb"/></linearGradient><filter id="iWQYKOe" width="11.901" height="13.419" x="10.085" y="8.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.423529 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2133"/></filter><filter id="i6OQRAb" width="4.408" height="2.736" x="12.777" y="16.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2133" stdDeviation=".05"/></filter><filter id="i0KdYcd" width="11.828" height="8.938" x="2.666" y="20.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.486275 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2133"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.403922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2133" result="effect2_innerShadow_2_2133"/></filter><filter id="i3EFDnb" width="11.828" height="8.875" x="17.756" y="21.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.486275 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2133"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.403922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2133" result="effect2_innerShadow_2_2133"/></filter><filter id="inLz7TN" width="3.885" height="3.935" x="11.464" y="11.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.0784314 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2133"/></filter><filter id="iQPUl1d" width="3.785" height="3.885" x="16.847" y="11.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0784314 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2133"/></filter><filter id="iUVTbQd" width="3.799" height="1.588" x="16.891" y="11.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.517647 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2133"/></filter><filter id="iFlVf5d" width="3.027" height="4.175" x="14.357" y="13.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2133" stdDeviation=".2"/></filter><filter id="ilSLTvc" width="7.281" height="6.172" x="15.953" y="4.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2133" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-zombie" /></template>
<style>
.a8ryvfbmd {
  d: path("M10.098 15.917a6 6 0 0 1-.013-.395v-.06c.274.03.544.101.8.238c.357.19.67.499.923.96c.253.463.39 1.044.46 1.568c.072.527.08 1.017.067 1.312l-.45-.02a7.3 7.3 0 0 0-.062-1.231c-.068-.502-.195-1.02-.41-1.413c-.216-.395-.47-.635-.74-.78a1.7 1.7 0 0 0-.575-.18");
}

.aakem1mws {
  d: path("m3.423 27.499l-.757-.68l.703-1.953l.855.648a.1.1 0 0 0 .108.009l.154-.083l-.469-1.777l1.02-1.031l1.164 1.626a.1.1 0 0 0 .134.027l.166-.103l-.218-1.824l1.375-.648l.622 1.427a.226.226 0 0 0 .264.129a.25.25 0 0 0 .181-.231v-.737l1.956.013l.018 3.956c.001.196.092.38.246.5c.167.13.387.166.594.12c.759-.166 1.623-.119 2.048-.013c.422.137.657.451.657.854a.896.896 0 0 1-.896.896h-.62c-.71 0-.945.11-1.648.695c-.563.469-1.443.58-1.813.578H6.173c-1.015 0-1.312-.406-1.64-.773c-.263-.294-.85-1.206-1.11-1.625");
}

.acyq6gpiw {
  stop-color: var(--svg-color--274e5b, #274E5B);
}

.aje_gtbfo {
  stop-color: var(--svg-color--608c96, #608C96);
  stop-opacity: 0;
}

.azawhbcxq {
  d: path("M10.085 11.872c.017-.253.093-.71.237-1.014c.181-.383.779-.698 1.089-.861l.099-.053c.258-.14.758-.601.969-1.125c.168-.419.445-.55.562-.562c.574.789 1.645 2.148 4.008 2.148h3.047c.325-.01 1.059.042 1.39.336c.414.367.5 1.121.5 1.477v3.55a5.953 5.953 0 0 1-11.901-.246z");
}

.bgfu0vbvz {
  width: 1.995px;
  height: 3.756px;
  x: 2.878px;
  y: 22.868px;
  rx: 0.998px;
}

.bng_m2b0t {
  stop-color: var(--svg-color--ffaf5a, #FFAF5A);
}

.bp9n2ccrq {
  stop-color: var(--svg-color--709ca5, #709CA5);
  stop-opacity: 0;
}

.bw57fdcce {
  stop-color: var(--svg-color--493061, #493061);
}

.bxi9tgmwe {
  stop-color: var(--svg-color--2f5657, #2F5657);
}

.ctgbwlbis {
  stop-color: var(--svg-color--493959, #493959);
}

.cxhprdb1z {
  stop-color: var(--svg-color--2d4a61, #2D4A61);
  stop-opacity: 0;
}

.d2h5kyjkp {
  stop-color: var(--svg-color--547986, #547986);
  stop-opacity: 0;
}

.d5osmbc_d {
  stop-color: var(--svg-color--679684, #679684);
  stop-opacity: 0;
}

.dbiijrl4h {
  stop-color: var(--svg-color--76a1ac, #76A1AC);
}

.djuzlabni {
  stop-color: var(--svg-color--587b87, #587B87);
}

.e-l33-bot {
  stop-color: var(--svg-color--81beb9, #81BEB9);
}

.e2nz_4b0g {
  stop-color: var(--svg-color--6db3ae, #6DB3AE);
}

.eb8sbmb8j {
  stop-color: var(--svg-color--3e597e, #3E597E);
}

.ebc1zfyja {
  stop-color: var(--svg-color--7498a0, #7498A0);
}

.el7r9pbsw {
  r: 1.893px;
}

.embjs61jm {
  stop-color: var(--svg-color--493959, #493959);
  stop-opacity: 0;
}

.emw7xxb2n {
  stop-color: var(--svg-color--5a8194, #5A8194);
}

.enitdihfo {
  stop-color: var(--svg-color--3a2549, #3A2549);
}

.enyqww8wr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M11.8 11.538c.289-.209 1.082-.535 2.074-.34");
}

.es563lbhm {
  stop-color: var(--svg-color--4f7b7f, #4F7B7F);
  stop-opacity: 0;
}

.f_4a2tb1d {
  stop-color: var(--svg-color--6a94b4, #6A94B4);
  stop-opacity: 0;
}

.f4-a9nvel {
  stop-color: var(--svg-color--ffb770, #FFB770);
}

.fav2t547e {
  d: path("M12.977 18.174c0-.645.522-1.168 1.168-1.168h.503a2.336 2.336 0 0 1 2.336 2.336h-2.84a1.17 1.17 0 0 1-1.167-1.168");
}

.fk_sd4b3f {
  width: 1.961px;
  height: 3.691px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.98px;
}

.ft5dv1b6b {
  fill: none;
}

.ftcaxw6ua {
  d: path("M21.991 15.464v.058q0 .201-.013.398a1.7 1.7 0 0 0-.554.177c-.27.144-.524.384-.74.78c-.215.393-.342.91-.41 1.412a7 7 0 0 0-.063 1.23l-.45.021a7.7 7.7 0 0 1 .067-1.312c.071-.524.208-1.105.461-1.568c.253-.46.566-.77.923-.96c.25-.133.513-.205.78-.236");
}

.g3i-1pbcq {
  stop-color: var(--svg-color--e98f43, #E98F43);
}

.gb43dybux {
  stop-color: var(--svg-color--5d8d93, #5D8D93);
}

.gbny4_b4j {
  stop-color: var(--svg-color--74ada5, #74ADA5);
}

.gew0dbs3i {
  stop-color: var(--svg-color--527483, #527483);
  stop-opacity: 0;
}

.gjthckb9a {
  stop-color: var(--svg-color--6ca895, #6CA895);
}

.gl17utj4l {
  width: 1.995px;
  height: 3.756px;
  rx: 0.998px;
}

.glfls735f {
  stop-color: var(--svg-color--74ada5, #74ADA5);
  stop-opacity: 0;
}

.got22lb_s {
  stop-color: var(--svg-color--7cbcb2, #7CBCB2);
}

.gyuwqf8co {
  stop-color: var(--svg-color--ffb770, #FFB770);
  stop-opacity: 0;
}

.h50m5ib7f {
  stop-color: var(--svg-color--ffdf80, #FFDF80);
}

.hbx3qwnwa {
  stop-color: var(--svg-color--e98f43, #E98F43);
  stop-opacity: 0;
}

.hkndu6boi {
  stop-color: var(--svg-color--3d274c, #3D274C);
}

.hmiiesz4q {
  stop-color: var(--svg-color--6b8698, #6B8698);
}

.ht552mbaq {
  stop-color: var(--svg-color--476676, #476676);
  stop-opacity: 0;
}

.htek_b-aw {
  stop-color: var(--svg-color--72a292, #72A292);
}

.i-ilo59wi {
  stop-color: var(--svg-color--2f545a, #2F545A);
}

.i2p625zaz {
  stop-color: var(--svg-color--486686, #486686);
}

.i7m2j00fs {
  width: 1.976px;
  height: 3.721px;
  rx: 0.988px;
}

.icg-h_npp {
  stop-color: var(--svg-color--648896, #648896);
}

.iieajnjfy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.453 4.991c.468.052 1.815.394 3.453 1.344c2.047 1.187 2.547 2.453 2.828 3.828");
}

.ij5lprb2c {
  width: 1.988px;
  height: 2.636px;
  rx: 0.994px;
}

.ippisxk_c {
  stop-color: var(--svg-color--679f8d, #679F8D);
}

.iq0niabpl {
  stop-color: var(--svg-color--5d8d93, #5D8D93);
  stop-opacity: 0;
}

.iv7v1nb3o {
  stop-color: var(--svg-color--4f8387, #4F8387);
  stop-opacity: 0;
}

.iw38491ye {
  stop-color: var(--svg-color--74ad9d, #74AD9D);
}

.izapptm4m {
  width: 1.988px;
  height: 2.636px;
  x: 1.35px;
  y: 25.317px;
  rx: 0.994px;
}

.j516ynx1g {
  stop-color: var(--svg-color--537483, #537483);
}

.j614okoao {
  stop-color: var(--svg-color--407568, #407568);
}

.jcyrp08ix {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M20.32 11.546c-.29-.209-1.11-.532-2.102-.336");
}

.ji621ab2s {
  fill: var(--svg-color--fba65c, #FBA65C);
  d: path("M16.452 17.858h-2.097a.3.3 0 0 1-.3-.3v-.548l.09-.004h.503a2.33 2.33 0 0 1 1.804.852");
}

.jjhcfiagl {
  stop-color: var(--svg-color--355d5e, #355D5E);
}

.jpym9qrbx {
  d: path("M16.017 13.35a.51.51 0 0 0-.49.373l-.6 2.18a.65.65 0 0 0 .627.822h.926a.65.65 0 0 0 .627-.822l-.6-2.18a.51.51 0 0 0-.49-.373");
}

.ju7pygbji {
  stop-color: var(--svg-color--0d0512, #0D0512);
}

.k589lpbub {
  stop-color: var(--svg-color--79a7af, #79A7AF);
}

.kingbac4q {
  fill: var(--svg-color--5f8783, #5F8783);
  d: path("M16.017 13.35a.51.51 0 0 0-.49.373l-.6 2.18a.65.65 0 0 0 .627.822h.926a.65.65 0 0 0 .627-.822l-.6-2.18a.51.51 0 0 0-.49-.373");
}

.kyxlbjczl {
  stop-color: var(--svg-color--609180, #609180);
}

.l17heo7fk {
  stop-color: var(--svg-color--211429, #211429);
}

.l257jccgu {
  width: 1.976px;
  height: 3.721px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.988px;
}

.l2cbxb5tg {
  stop-color: var(--svg-color--6c9e8f, #6C9E8F);
  stop-opacity: 0;
}

.la3tbwntj {
  stop-color: var(--svg-color--7cc2b2, #7CC2B2);
  stop-opacity: 0;
}

.libnoft0w {
  stop-color: var(--svg-color--456a60, #456A60);
}

.ltf0tqb9y {
  stop-color: var(--svg-color--684d78, #684D78);
}

.ltqercvec {
  stop-color: var(--svg-color--568390, #568390);
  stop-opacity: 0;
}

.lv9f4sbft {
  stop-color: var(--svg-color--70a196, #70A196);
}

.lvqejss-o {
  width: 1.961px;
  height: 3.691px;
  rx: 0.98px;
}

.lxs7f3b1j {
  stop-color: var(--svg-color--7abfb2, #7ABFB2);
}

.m5racngae {
  stop-color: var(--svg-color--76b9a7, #76B9A7);
  stop-opacity: 0;
}

.m7a_bec-v {
  stop-color: var(--svg-color--547b7a, #547B7A);
}

.m8bj1mb9s {
  r: 0.623px;
  fill: var(--svg-color--9e1539, #9E1539);
}

.mb0n-8q3d {
  d: path("M8.399 9.116c.075-.912.604-1.578.859-1.797c-.192-.118-.526-.153-.781-.148a.63.63 0 0 1-.484-.186a.453.453 0 0 1-.005-.609c.557-.61 1.398-1.33 2.332-1.42c.96-.092 2.13.323 2.61.5c.473-.5 1.493-1.48 3.105-1.48c2.348.054 2.82 1.402 3.614 1.687c.968.305 1.867.371 2.878 1.266c1.75 1.64.973 3.242 1.63 4.054s1.265.594 1.882 1.219c1.06.967 1.202 2.343 1.129 3.285c-.024.311-.302.529-.614.514a.62.62 0 0 1-.392-.163c-.248-.23-.5-.462-.774-.653c-.104-.073-.246-.065-.326.034c-.45.554-.242 1.465-.085 1.881c.11.292.515 1.203-.375 3.047c-.713 1.475-3.047 2.23-4.125 2.422l-4.563-2.281l-4.133 2.203c-2.727-.323-3.793-1.508-4.343-2.516c-.075-.136-.19-.118-.25-.082a1 1 0 0 1-.393.132c-.144.016-.3.005-.415-.084a.47.47 0 0 1-.18-.31c-.217-1.769.328-2.244.742-2.82c.32-.582.414-.941.242-1.379c-.313-.937-.242-2.277.37-3.27c.69-1.113.75-1.905.845-3.046");
}

.mfys3hj4f {
  stop-color: var(--svg-color--241232, #241232);
}

.mlx0qzhjk {
  stop-color: var(--svg-color--66a9a4, #66A9A4);
  stop-opacity: 0;
}

.mneke1b_s {
  stop-color: var(--svg-color--57779e, #57779E);
}

.mpb4aacxt {
  fill: var(--svg-color--618c93, #618C93);
  d: path("m28.577 27.499l.757-.68l-.687-1.976l-.87.67a.1.1 0 0 1-.11.01l-.153-.083l.469-1.777l-1.036-1.008l-1.148 1.603a.1.1 0 0 1-.134.027l-.166-.103l.218-1.824l-1.406-.586l-.59 1.365a.226.226 0 0 1-.265.129a.24.24 0 0 1-.175-.225v-.737l-1.962.007l-.018 3.956a.64.64 0 0 1-.246.5a.72.72 0 0 1-.594.12c-.759-.166-1.623-.119-2.048-.013c-.422.137-.657.451-.657.854c0 .495.401.896.896.896h.62c.71 0 .945.11 1.648.695c.563.469 1.443.58 1.813.578h3.094c1.015 0 1.312-.406 1.64-.773c.263-.294.85-1.206 1.11-1.625");
}

.mrh8oxbyb {
  stop-color: var(--svg-color--5e8a91, #5E8A91);
  stop-opacity: 0;
}

.n_euk-b7u {
  stop-color: var(--svg-color--3c254a, #3C254A);
  stop-opacity: 0;
}

.n3i60zbwo {
  stop-color: var(--svg-color--4c6489, #4C6489);
}

.n9lie4b0a {
  d: path("M20.59 13.272h-3.7a1.893 1.893 0 0 1 3.7 0");
}

.nhd76xusb {
  stop-color: var(--svg-color--719ea0, #719EA0);
}

.nrrnwgb2j {
  stop-color: var(--svg-color--291632, #291632);
}

.nuh0chd7n {
  d: path("m28.577 27.499l.757-.68l-.687-1.976l-.87.67a.1.1 0 0 1-.11.01l-.153-.083l.469-1.777l-1.036-1.008l-1.148 1.603a.1.1 0 0 1-.134.027l-.166-.103l.218-1.824l-1.406-.586l-.59 1.365a.226.226 0 0 1-.265.129a.24.24 0 0 1-.175-.225v-.737l-1.962.007l-.018 3.956a.64.64 0 0 1-.246.5a.72.72 0 0 1-.594.12c-.759-.166-1.623-.119-2.048-.013c-.422.137-.657.451-.657.854c0 .495.401.896.896.896h.62c.71 0 .945.11 1.648.695c.563.469 1.443.58 1.813.578h3.094c1.015 0 1.312-.406 1.64-.773c.263-.294.85-1.206 1.11-1.625");
}

.nxovy29zu {
  stop-color: var(--svg-color--608884, #608884);
  stop-opacity: 0;
}

.nzw280tix {
  stop-color: var(--svg-color--6f9c9c, #6F9C9C);
  stop-opacity: 0;
}

.o1u4v1x-w {
  stop-color: var(--svg-color--576a91, #576A91);
}

.o39pnqg0i {
  stop-color: var(--svg-color--5c818e, #5C818E);
  stop-opacity: 0;
}

.o5pi4qbos {
  stop-color: var(--svg-color--4d678a, #4D678A);
}

.odwb5qh_v {
  stop-color: var(--svg-color--5c8a89, #5C8A89);
}

.ogpl8rbbb {
  stop-color: var(--svg-color--ffcf77, #FFCF77);
}

.oi5b6vt4l {
  stop-color: var(--svg-color--669688, #669688);
  stop-opacity: 0;
}

.ong7-kbio {
  stop-color: var(--svg-color--587b87, #587B87);
  stop-opacity: 0;
}

.opdni9jvk {
  stop-color: var(--svg-color--4b365e, #4B365E);
}

.oxi0f3b2m {
  stop-color: var(--svg-color--72b4aa, #72B4AA);
}

.p0u5ydomu {
  stop-color: var(--svg-color--60829e, #60829E);
  stop-opacity: 0;
}

.p3hupxtfd {
  stop-color: var(--svg-color--709ca5, #709CA5);
}

.p7xh8mbkr {
  stop-color: var(--svg-color--7eb7ae, #7EB7AE);
}

.ppkjr9zdh {
  width: 1.976px;
  height: 3.721px;
  x: 5.516px;
  y: 21.469px;
  rx: 0.988px;
}

.pwb1owbqd {
  d: path("M16.452 17.858h-2.097a.3.3 0 0 1-.3-.3v-.548l.09-.004h.503a2.33 2.33 0 0 1 1.804.852");
}

.q53_zdbrw {
  stop-color: var(--svg-color--54958b, #54958B);
}

.q9gxalg3c {
  stop-color: var(--svg-color--1b2e44, #1B2E44);
}

.qczal5bjq {
  stop-color: var(--svg-color--588292, #588292);
}

.qudy1_y1m {
  stop-color: var(--svg-color--311a3d, #311A3D);
}

.qzo_nkzbd {
  stop-color: var(--svg-color--476676, #476676);
}

.rbf98joze {
  d: path("M15.87 13.554a.51.51 0 0 0-.489.372l-.6 2.18a.65.65 0 0 0 .627.822h.926a.65.65 0 0 0 .627-.822l-.6-2.18a.51.51 0 0 0-.49-.373");
}

.rdi-wfxqd {
  stop-color: var(--svg-color--586590, #586590);
}

.rrdpflbyy {
  stop-color: var(--svg-color--588290, #588290);
  stop-opacity: 0;
}

.rvq6gmb5w {
  stop-color: var(--svg-color--070608, #070608);
}

.s705ubb2m {
  cx: 13.576px;
  cy: 13.442px;
  r: 1.549px;
}

.s9595bb6g {
  stop-color: var(--svg-color--7cc2b2, #7CC2B2);
}

.sce_y6bah {
  stop-color: var(--svg-color--396f65, #396F65);
}

.sl7iwijia {
  stop-color: var(--svg-color--396f65, #396F65);
  stop-opacity: 0;
}

.slfwwoboa {
  stop-color: var(--svg-color--6ba18f, #6BA18F);
  stop-opacity: 0;
}

.so0nfjs_n {
  stop-color: var(--svg-color--7eb7ae, #7EB7AE);
  stop-opacity: 0;
}

.th_2jcizb {
  stop-color: var(--svg-color--6c9b96, #6C9B96);
  stop-opacity: 0;
}

.tn-w78xgx {
  stop-color: var(--svg-color--619299, #619299);
  stop-opacity: 0;
}

.tpfs9rb4e {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.977 18.174c0-.645.522-1.168 1.168-1.168h.503a2.336 2.336 0 0 1 2.336 2.336h-2.84a1.17 1.17 0 0 1-1.167-1.168Z");
}

.u84zz4ukw {
  stop-color: var(--svg-color--7abfb2, #7ABFB2);
  stop-opacity: 0;
}

.udi_mfp4v {
  stop-color: var(--svg-color--351c47, #351C47);
}

.uiq6v0czi {
  width: 1.961px;
  height: 3.691px;
  x: 8.72px;
  y: 20.917px;
  rx: 0.98px;
}

.ulmooebvp {
  stop-color: var(--svg-color--6db3ae, #6DB3AE);
  stop-opacity: 0;
}

.umebve3qj {
  stop-color: var(--svg-color--341c3d, #341C3D);
}

.uvhjscb1o {
  width: 1.995px;
  height: 3.756px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.998px;
}

.ve2ow0b5f {
  stop-color: var(--svg-color--508f82, #508F82);
}

.vfhurybye {
  width: 4.969px;
  height: 6.172px;
  x: 13.533px;
  y: 18.1px;
  rx: 2.484px;
}

.vl_ql576y {
  stop-color: var(--svg-color--659ea4, #659EA4);
  stop-opacity: 0;
}

.w0ry1tv8g {
  stop-color: var(--svg-color--ffb45c, #FFB45C);
}

.wlivwtbej {
  fill: var(--svg-color--6a9da1, #6A9DA1);
  d: path("m3.423 27.499l-.757-.68l.703-1.953l.855.648a.1.1 0 0 0 .108.009l.154-.083l-.469-1.777l1.02-1.031l1.164 1.626a.1.1 0 0 0 .134.027l.166-.103l-.218-1.824l1.375-.648l.622 1.427a.226.226 0 0 0 .264.129a.25.25 0 0 0 .181-.231v-.737l1.956.013l.018 3.956c.001.196.092.38.246.5c.167.13.387.166.594.12c.759-.166 1.623-.119 2.048-.013c.422.137.657.451.657.854a.896.896 0 0 1-.896.896h-.62c-.71 0-.945.11-1.648.695c-.563.469-1.443.58-1.813.578H6.173c-1.015 0-1.312-.406-1.64-.773c-.263-.294-.85-1.206-1.11-1.625");
}

.woms0-bkw {
  stop-color: var(--svg-color--4d6999, #4D6999);
}

.ws-ofvbpp {
  stop-color: var(--svg-color--608d97, #608D97);
  stop-opacity: 0;
}

.x2jlfyb6f {
  d: path("m7.5 29.897l-2.077-3.596a11.99 11.99 0 0 1 10.187-5.654h1.375c3.966 0 7.483 1.925 9.668 4.89l-2.517 4.36z");
}

.x4_rgjbgr {
  stop-color: var(--svg-color--709d99, #709D99);
}

.x9syn5bsf {
  stop-color: var(--svg-color--6fa293, #6FA293);
}

.xjomt31wk {
  stop-color: var(--svg-color--6c8ea7, #6C8EA7);
  stop-opacity: 0;
}

.xq9watbjp {
  stop-color: var(--svg-color--7dc3b4, #7DC3B4);
}

.xtb7f1b8t {
  stop-color: var(--svg-color--5659a3, #5659A3);
}

.y2c1oq0fx {
  r: 1.549px;
}

.y7xy7bb_m {
  stop-color: var(--svg-color--526c9e, #526C9E);
}

.yps5thqls {
  stop-color: var(--svg-color--466082, #466082);
}

.yq3urh0vb {
  stop-color: var(--svg-color--6182a0, #6182A0);
}

.yveiieo1a {
  cx: 13.357px;
  cy: 13.677px;
  r: 1.893px;
}

.z6xm9cbni {
  cx: 13.595px;
  cy: 13.442px;
  r: 0.623px;
  fill: var(--svg-color--a01b3c, #A01B3C);
}

.zbdko4y_s {
  stop-color: var(--svg-color--3e6d60, #3E6D60);
}

.zgqvtpbpd {
  stop-color: var(--svg-color--4c7282, #4C7282);
}

.zl7ptbcaa {
  stop-color: var(--svg-color--629f8d, #629F8D);
}

</style>
