<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iwqOlZc)" class="bvt-nl_lh"/><circle fill="url(#iBBTOGb)" class="bvt-nl_lh"/><circle fill="url(#iJk4UTp)" class="a3xzsy0qb"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.997 16.678)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.997 16.678)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 24.395 23.881)" class="n5l_opbqq"/><path fill="url(#i6huoJe)" class="am98xqfgr"/><path fill="url(#iYmp1Id)" class="am98xqfgr"/><path fill="url(#iooXkpe)" class="am98xqfgr"/><path fill="url(#ijqTUTd)" class="orc6_jalb"/><path fill="url(#iYHChXb)" class="orc6_jalb"/><path class="ltd1pnb_k"/><path fill="url(#iQdoHWb)" class="n89hyfbom"/><path fill="url(#iHTVnse)" class="n89hyfbom"/><path fill="url(#iDgzvhe)" class="n89hyfbom"/><path fill="url(#isZctud)" class="n89hyfbom"/><path fill="url(#iXsSKqb)" class="n89hyfbom"/><path fill="url(#iBixcjM)" class="n89hyfbom"/><path class="kqbr7hbmw"/><path fill="url(#ivd9l0g)" class="lt3mxmj4h"/><path fill="url(#irLIHys)" class="lt3mxmj4h"/><path fill="url(#i73Hu0c)" class="lt3mxmj4h"/><g filter="url(#i98zqDb)"><path fill="url(#iQDHDWd)" class="bz1d_nb_f"/><path fill="url(#ij0uANR)" class="bz1d_nb_f"/><path fill="url(#iTBEGqd)" class="bz1d_nb_f"/></g><path class="k8jfyf_lo"/><g filter="url(#i3pWW7d)"><path class="ovr-t3yxx"/></g><path fill="url(#iDlFQYb)" class="impaz2sfr"/><path fill="url(#i9m08ue)" class="impaz2sfr"/><path fill="url(#iDCz5Mb)" class="f6smzebkc"/><path fill="url(#iAA3h3d)" class="kaf48_bxn"/><g filter="url(#ifrdBeb)"><path fill="url(#iPdowfb)" class="rzilvpbra"/></g><path fill="url(#i09jwyd)" class="rzilvpbra"/><path fill="url(#iZzRSbb)" class="rzilvpbra"/><path fill="url(#ixhJtBe)" class="rzilvpbra"/><path fill="url(#isnbJsb)" class="rzilvpbra"/><path fill="url(#iREV0dd)" class="rzilvpbra"/><path fill="url(#iMtU0Xd)" class="rzilvpbra"/><path fill="url(#i9ZRWXb)" class="rzilvpbra"/><g filter="url(#ieBxCfd)"><path class="n6xdn4yaw"/></g><g filter="url(#imwJGrb)"><path class="n3w7q4mjk"/><path fill="url(#in1OjRd)" class="nc-4r020u"/><path fill="url(#iPZYbTz)" class="nc-4r020u"/><path fill="url(#i9e3PJe)" class="nc-4r020u"/><path fill="url(#i07K4Nd)" class="nc-4r020u"/></g><g filter="url(#i8jwnCc)"><path stroke="url(#ihd2QTb)" class="tptc_3u7h"/></g><path fill="url(#iNDxS2b)" class="oe7t4pblk"/><g filter="url(#iEZX3Vd)"><path fill="url(#iv7wfhe)" class="ix1uklbee"/><path fill="url(#iT8Goyb)" class="ix1uklbee"/><path fill="url(#iv5Vhre)" class="ix1uklbee"/><path fill="url(#icRBk7g)" class="ix1uklbee"/><path fill="url(#iQvOTcH)" class="ix1uklbee"/></g><g filter="url(#ikN7bDd)"><path class="jtqufdciz"/></g><g filter="url(#iin5Zjc)"><path class="m3du_wb8k"/></g><g filter="url(#iC3biJd)"><path class="pngg7lbcs"/><path fill="url(#iFahPbb)" class="yp0_j3bzj"/><path fill="url(#ilQmOYb)" class="yp0_j3bzj"/></g><g filter="url(#ibP5Lxb)"><path class="x3nq2abto"/><path fill="url(#imRxJye)" class="biam9sxfh"/><path fill="url(#idM01Fb)" class="biam9sxfh"/><path fill="url(#iAQ9dab)" class="biam9sxfh"/></g><path class="o0l6_mb5d"/><path fill="url(#ivTd0ub)" class="a9bb9gb3o"/><path class="v5myhy--q"/><g filter="url(#i10YIed)"><path class="qai6kx0km"/><path fill="url(#iW3SXSV)" class="w0wa9coif"/></g><g filter="url(#iLh1BhH)"><path fill="url(#i1SQIKc)" class="kwvbtl-1n"/></g><path class="d4j06zbrm"/><path fill="url(#ip3EEDd)" class="p66qg5jpt"/><path class="nu1yrov3v"/><g filter="url(#ihGuCnd)"><path fill="url(#irGkrIc)" class="tl7m_rblj"/></g><g filter="url(#iftBF3b)"><ellipse transform="rotate(-27.914 14.07 10.494)" class="uby2uabyx"/><ellipse fill="url(#iBGEuqd)" transform="rotate(-27.914 14.07 10.494)" class="u-5_dfr8d"/></g><path fill="url(#i3i6hLd)" class="o_f_m1bbo"/><path fill="url(#ixQyPvd)" class="o_f_m1bbo"/><path fill="url(#iB8Mkxe)" class="o_f_m1bbo"/><path fill="url(#ia2JQyo)" class="o_f_m1bbo"/><path fill="url(#iWpg5Gd)" class="lylz1hbgs"/><path fill="url(#iTTsL5c)" class="lylz1hbgs"/><g filter="url(#iatncZb)"><path fill="url(#iZDUuCe)" class="f9gjh5ddq"/></g><g filter="url(#ibLDfcb)"><path fill="url(#iAOmXNd)" class="yegzzobzs"/></g><g filter="url(#ibQwx3b)"><path class="uqmxc1zfy"/></g><g filter="url(#iAypkWb)"><path class="j-wbwq5mz"/></g><defs><radialGradient id="iwqOlZc" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 7.548 17.842)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="iBBTOGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 9.266 18.342)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="iJk4UTp" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 11.131 19.781)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="i6huoJe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.766 23.092)" gradientUnits="userSpaceOnUse"><stop class="yf3t3eb5f"/><stop offset="1" class="a66gbwbzh"/></radialGradient><radialGradient id="ijqTUTd" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 7.088 22.832)" gradientUnits="userSpaceOnUse"><stop class="pbkzvtx_w"/><stop offset="1" class="ykdcls_lk"/></radialGradient><radialGradient id="iQdoHWb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 14.423 16.904)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="k3qin7bzy"/><stop offset="1" class="x3axlob0n"/></radialGradient><radialGradient id="iDgzvhe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 16.629 29.475)" gradientUnits="userSpaceOnUse"><stop class="z2ddyab4m"/><stop offset="1" class="cqgvl433q"/></radialGradient><radialGradient id="iXsSKqb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 17.017 28.092)" gradientUnits="userSpaceOnUse"><stop class="h3e5alaje"/><stop offset="1" class="u4bo2-o9a"/></radialGradient><radialGradient id="iBixcjM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 15.007 19.028)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="gyulks50m"/><stop offset="1" class="atms-xm-n"/></radialGradient><radialGradient id="irLIHys" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 18.173 18.842)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="k-y64ibbx"/><stop offset="1" class="pjzr3aclu"/></radialGradient><radialGradient id="i73Hu0c" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.65 18.781)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="bc2qs9bhj"/><stop offset="1" class="ktoycacxm"/></radialGradient><radialGradient id="ij0uANR" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.75 -2.19025 2.26847 13.829 17.717)" gradientUnits="userSpaceOnUse"><stop class="gsf6qr7kp"/><stop offset="1" class="cg_mp-zjf"/></radialGradient><radialGradient id="iTBEGqd" cx="0" cy="0" r="1" gradientTransform="rotate(92.228 .518 16.89)scale(2.71839 2.59628)" gradientUnits="userSpaceOnUse"><stop class="gs0xjnbiw"/><stop offset="1" class="r9e33mbdc"/></radialGradient><radialGradient id="iDlFQYb" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -4.492 14.946)scale(3.00702 1.36683)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="i9m08ue" cx="0" cy="0" r="1" gradientTransform="matrix(.1816 1.20893 -1.06048 .1593 11.748 12.384)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="iDCz5Mb" cx="0" cy="0" r="1" gradientTransform="matrix(.75836 2.0454 -2.42979 .90088 21.369 12.473)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iAA3h3d" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -37.05 40.443)scale(1.56749 4.83582)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="iPdowfb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.7584 0 0 -9.88904 19.4 11.52)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ihp80jh_m"/></radialGradient><radialGradient id="iZzRSbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01092 12.93155 -10.70883 -.83716 18.156 5.53)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="www4dfogh"/><stop offset="1" class="c0317ln8x"/></radialGradient><radialGradient id="ixhJtBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16306 1.43929 0 19.034 10.19)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="isnbJsb" cx="0" cy="0" r="1" gradientTransform="matrix(.00398 -1.1083 1.2061 .00433 14.226 10.236)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iREV0dd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.60483 .54318 -1.38755 -21.98105 20.032 12.52)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iMtU0Xd" cx="0" cy="0" r="1" gradientTransform="matrix(3.13812 -3.31975 1.21526 1.14877 11.018 7.138)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="i9ZRWXb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.68 8.6)scale(3.41214 2.817)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iPZYbTz" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24723 -.777 0 17.139 12.905)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iNDxS2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72997 2.93686 0 16.555 15.104)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iT8Goyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.54618 8.96788 0 11.259 8.59)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iv5Vhre" cx="0" cy="0" r="1" gradientTransform="matrix(.1155 -2.54473 4.50877 .20465 21.478 9.917)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="icRBk7g" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38905 -1.57129 1.1534 -1.75369 20.714 3.56)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iQvOTcH" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.08 14.946)scale(1.75273 4.0585)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iFahPbb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.22933 0 0 -.82739 16.812 4.235)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ilQmOYb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25943 -5.1607 5.71752 3.61112 11.055 8.228)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="imRxJye" cx="0" cy="0" r="1" gradientTransform="matrix(3.09757 0 0 1.2111 20.013 5.022)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="idM01Fb" cx="0" cy="0" r="1" gradientTransform="matrix(2.71304 -2.58487 4.73223 4.96689 19.223 8.098)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iAQ9dab" cx="0" cy="0" r="1" gradientTransform="matrix(3.28983 .38453 -.161 1.3774 18.325 6.603)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ivTd0ub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82171 -1.30703 0 18.765 10.591)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iW3SXSV" cx="0" cy="0" r="1" gradientTransform="matrix(-.23489 -.30269 .41673 -.32339 18.534 10.676)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ip3EEDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82176 -1.30709 0 14.345 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iBGEuqd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.35 -1.512)scale(.50048 .60158)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixQyPvd" cx="0" cy="0" r="1" gradientTransform="matrix(.6366 2.272 -2.16768 .60737 21.232 10.605)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iB8Mkxe" cx="0" cy="0" r="1" gradientTransform="matrix(.79788 -1.09496 .9178 .66878 21.597 11.157)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="ia2JQyo" cx="0" cy="0" r="1" gradientTransform="matrix(.59452 -1.57028 2.09812 .79436 21.713 11.331)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iTTsL5c" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 6.13 5.276)scale(1.64598 1.76689)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iZDUuCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.92822 .15935 -.19553 -1.13897 11.58 11.257)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><filter id="i98zqDb" width="6.906" height="10.938" x="12.963" y="17.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_791"/></filter><filter id="i3pWW7d" width="3.076" height="1.977" x="15.922" y="17.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".3"/></filter><filter id="ifrdBeb" width="11.351" height="12.7" x="11.427" y="5.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_791"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_791" result="effect2_innerShadow_4002_791"/></filter><filter id="ieBxCfd" width="3.769" height="4.937" x="14.527" y="9.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".5"/></filter><filter id="imwJGrb" width="2.301" height="3.337" x="15.516" y="10.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".1"/></filter><filter id="i8jwnCc" width="3.76" height="1.587" x="14.675" y="13.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".05"/></filter><filter id="iEZX3Vd" width="13.038" height="8.457" x="10.036" y="2.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_791"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_791" result="effect2_innerShadow_4002_791"/></filter><filter id="ikN7bDd" width="2.368" height="1.203" x="18.165" y="7.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_791"/></filter><filter id="iin5Zjc" width="2.368" height="1.188" x="12.841" y="7.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_791"/></filter><filter id="iC3biJd" width="6.812" height="6.062" x="10.4" y="3.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_791"/><feGaussianBlur result="effect2_foregroundBlur_4002_791" stdDeviation=".125"/></filter><filter id="ibP5Lxb" width="6.44" height="5.806" x="16.394" y="3.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".125"/></filter><filter id="i10YIed" width=".794" height=".703" x="18.023" y="10.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".05"/></filter><filter id="iLh1BhH" width=".898" height=".92" x="18.875" y="10.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".1"/></filter><filter id="ihGuCnd" width=".994" height="1.048" x="14.375" y="10.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".1"/></filter><filter id="iftBF3b" width=".922" height=".711" x="13.609" y="10.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".05"/></filter><filter id="iatncZb" width="1.34" height="2.403" x="10.4" y="10.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".125"/></filter><filter id="ibLDfcb" width="1.959" height="2.928" x="21.125" y="9.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".25"/></filter><filter id="ibQwx3b" width="2.426" height="1.166" x="12.764" y="7.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".125"/></filter><filter id="iAypkWb" width="2.426" height="1.166" x="18.11" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_791" stdDeviation=".125"/></filter><linearGradient id="iYmp1Id" x1="24.829" x2="24.86" y1="30.842" y2="27.186" gradientUnits="userSpaceOnUse"><stop offset=".078" class="npfrbd3jd"/><stop offset="1" class="w_5-rbc1a"/></linearGradient><linearGradient id="iooXkpe" x1="18.791" x2="20.143" y1="28.278" y2="28.664" gradientUnits="userSpaceOnUse"><stop class="p5jt_ib0l"/><stop offset="1" class="hw19_ybat"/></linearGradient><linearGradient id="iYHChXb" x1="14.329" x2="12.829" y1="29.248" y2="29.779" gradientUnits="userSpaceOnUse"><stop class="h65uoi6pi"/><stop offset="1" class="g04ogacjt"/></linearGradient><linearGradient id="iHTVnse" x1="12.985" x2="14.36" y1="27.904" y2="27.342" gradientUnits="userSpaceOnUse"><stop offset=".223" class="d05zivoho"/><stop offset="1" class="ue2ywxbfs"/></linearGradient><linearGradient id="isZctud" x1="16.298" x2="14.892" y1="30.686" y2="29.998" gradientUnits="userSpaceOnUse"><stop offset=".208" class="cu8bl7b6w"/><stop offset="1" class="bkwavzmor"/></linearGradient><linearGradient id="ivd9l0g" x1="16.673" x2="18.704" y1="25.342" y2="26.248" gradientUnits="userSpaceOnUse"><stop class="ego3-fbwo"/><stop offset="1" class="up5p4s41k"/></linearGradient><linearGradient id="iQDHDWd" x1="17.037" x2="17.037" y1="25.658" y2="16.132" gradientUnits="userSpaceOnUse"><stop class="qdcgkefpz"/><stop offset="1" class="v1nc78bgs"/></linearGradient><linearGradient id="i09jwyd" x1="21.779" x2="17.37" y1="13.226" y2="13.226" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="in1OjRd" x1="17.515" x2="16.666" y1="12.21" y2="12.246" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="i9e3PJe" x1="16.666" x2="16.666" y1="13.364" y2="12.893" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i07K4Nd" x1="16.666" x2="16.666" y1="10.494" y2="11.178" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="ihd2QTb" x1="15.338" x2="15.661" y1="14.947" y2="14.102" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="iv7wfhe" x1="23.495" x2="11.734" y1="5.784" y2="5.784" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="i1SQIKc" x1="19.553" x2="19.235" y1="10.646" y2="10.841" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irGkrIc" x1="15.099" x2="14.781" y1="10.646" y2="10.841" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3i6hLd" x1="23.074" x2="21.852" y1="10.673" y2="12.877" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iWpg5Gd" x1="10.631" x2="12.107" y1="11.386" y2="11.257" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iAOmXNd" x1="22.104" x2="22.104" y1="10.297" y2="12.225" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-steamy-room-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a3xzsy0qb {
  cx: 8.946px;
  cy: 23.881px;
  r: 6.305px;
}

.a66gbwbzh {
  stop-color: var(--svg-color--f65c3e, #F65C3E);
}

.a9bb9gb3o {
  d: path("M18.767 10.108a.904.904 0 0 1 .871 1.142h-1.746a.907.907 0 0 1 .875-1.142");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.am98xqfgr {
  d: path("M27.618 30.451c0-7.96-4.617-9.875-5.375-10.382L17.196 30.45z");
}

.atms-xm-n {
  stop-color: var(--svg-color--9e2625, #9E2625);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc2qs9bhj {
  stop-color: var(--svg-color--ff7347, #FF7347);
}

.biam9sxfh {
  d: path("m21.835 9.14l-.03-.64c-.01-.773-.65-1.41-1.423-1.443h-1.418c-.9 0-1.722-.492-2.151-1.276c0 0-.063-.146-.127-.394c-.251-.972.675-1.713 1.66-1.524c.991.19 2.125.524 2.961 1.07c1.767 1.152 1.458 3.229.528 4.207");
}

.bkwavzmor {
  stop-color: var(--svg-color--dd5022, #DD5022);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bvt-nl_lh {
  cx: 11.345px;
  cy: 16.678px;
  r: 4.086px;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bz1d_nb_f {
  d: path("M14.68 17.03h4v.887c.011.175.046.374.153.53a.8.8 0 0 0 .445.332l.465.165c.076.067.22.478.04.984c-.182.505-2.044 5.51-3.095 8.02v.019l-.004-.01l-.004.01v-.02c-1.052-2.509-3.186-7.514-3.367-8.019c-.181-.506-.075-.87 0-.937l.68-.192c.219-.062.374-.14.515-.348c.114-.165.159-.389.172-.572z");
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c0317ln8x {
  stop-color: var(--svg-color--c9747e, #C9747E);
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cg_mp-zjf {
  stop-color: var(--svg-color--df9981, #DF9981);
  stop-opacity: 0;
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

.d4j06zbrm {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.134 9.833c-.662 0-1.22.456-1.373 1.072a.278.278 0 0 0 .271.345h2.26a.233.233 0 0 0 .23-.275a1.42 1.42 0 0 0-1.388-1.142");
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.ego3-fbwo {
  stop-color: var(--svg-color--ce3b1b, #CE3B1B);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f6smzebkc {
  d: path("M21.479 12.785c.34-.011.657-.126.916-.313v.943a2.2 2.2 0 0 1-1.358 2.045q.259-.552.35-1.195z");
}

.f9gjh5ddq {
  d: path("M11.405 10.305a.968.968 0 0 0 .084 1.904a79 79 0 0 1-.084-1.904");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g04ogacjt {
  stop-color: var(--svg-color--d63c26, #D63C26);
  stop-opacity: 0;
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gs0xjnbiw {
  stop-color: var(--svg-color--f0af9e, #F0AF9E);
}

.gsf6qr7kp {
  stop-color: var(--svg-color--c3705c, #C3705C);
}

.gyulks50m {
  stop-color: var(--svg-color--9e2625, #9E2625);
}

.h3e5alaje {
  stop-color: var(--svg-color--c03005, #C03005);
}

.h65uoi6pi {
  stop-color: var(--svg-color--d63c26, #D63C26);
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hw19_ybat {
  stop-color: var(--svg-color--e04438, #E04438);
  stop-opacity: 0;
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ihp80jh_m {
  stop-color: var(--svg-color--d89d91, #D89D91);
}

.impaz2sfr {
  d: path("M11.632 12.785a1.66 1.66 0 0 1-.917-.313v.943a2.2 2.2 0 0 0 1.358 2.045a4.1 4.1 0 0 1-.35-1.195z");
}

.ix1uklbee {
  d: path("M21.472 4.791c.521.18.989.543 1.284 1.065a2.4 2.4 0 0 1-.107 2.558a1.6 1.6 0 0 0-.274.886v1.203a1.8 1.8 0 0 0-.676-.271l.08-1.627a1.47 1.47 0 0 0-1.397-1.45h-1.418a2.45 2.45 0 0 1-2.24-1.462a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.422l.031 1.557a1.7 1.7 0 0 0-.73.268V9.3a1.6 1.6 0 0 0-.273-.886a2.42 2.42 0 0 1-.145-2.477c.295-.56.773-.95 1.316-1.14a2.7 2.7 0 0 0 1.402-1.125a2.355 2.355 0 0 1 2.928-.924c.386.169.821.169 1.208 0c.285-.119.596-.19.924-.19c.854 0 1.6.462 2.014 1.147c.312.516.8.89 1.37 1.086");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j-wbwq5mz {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.162 8.627c-.26-.187-.91-.515-1.677-.386");
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jtqufdciz {
  fill: var(--svg-color--202020, #202020);
  d: path("M20.336 8.501a1.9 1.9 0 0 0-.696-.417c-.309-.097-.694-.123-1.228-.057a.28.28 0 0 0 .068.557c.487-.06.786-.028.99.036c.202.064.338.166.497.305a.28.28 0 0 0 .369-.424");
}

.k-y64ibbx {
  stop-color: var(--svg-color--99201f, #99201F);
}

.k3qin7bzy {
  stop-color: var(--svg-color--b22307, #B22307);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k8jfyf_lo {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M2.641 24.53h3.297a5.94 5.94 0 0 1 5.938 5.937H2.64zm28.059 0h-3.297a5.94 5.94 0 0 0-5.937 5.937H30.7z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.kaf48_bxn {
  d: path("M11.632 12.785a1.66 1.66 0 0 1-.916-.313v.943a2.2 2.2 0 0 0 1.358 2.045a4.1 4.1 0 0 1-.35-1.195z");
}

.kqbr7hbmw {
  fill: var(--svg-color--ec551b, #EC551B);
  d: path("M22.49 17.866c-.64-1.313-1.82-1.75-2.594-1.75h-2.609v2.875h2.469c.169.303.003.85-.102 1.085l-3.938 10.391h3.176c1.067-2.583 2.995-7.817 3.382-8.742c.42-1.004.81-2.477.216-3.86");
}

.ktoycacxm {
  stop-color: var(--svg-color--f6682e, #F6682E);
  stop-opacity: 0;
}

.kwvbtl-1n {
  d: path("M19.573 10.893a.85.85 0 0 0-.235-.469l-.263.289l.119.231z");
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lt3mxmj4h {
  d: path("M22.49 17.866c-.64-1.313-1.82-1.75-2.594-1.75h-2.609v2.875h2.469c.169.303.003.85-.102 1.085l-3.938 10.391h3.176c1.067-2.583 2.995-7.817 3.382-8.742c.42-1.004.81-2.477.216-3.86");
}

.ltd1pnb_k {
  fill: var(--svg-color--ed561d, #ED561D);
  d: path("M10.571 17.866c.64-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.085l4.317 10.391h-3.176c-1.068-2.583-3.293-7.817-3.68-8.742c-.42-1.004-.89-2.477-.297-3.86");
}

.lylz1hbgs {
  d: path("M11.446 9.636a1.64 1.64 0 0 0-1.41 1.614c0 .87.682 1.58 1.54 1.627a79 79 0 0 1-.13-3.241");
}

.m3du_wb8k {
  fill: var(--svg-color--202020, #202020);
  d: path("M13.1 8.39a2.8 2.8 0 0 1 1.761-.364a.28.28 0 1 1-.067.558a2.25 2.25 0 0 0-1.405.289a1 1 0 0 0-.093.06l-.002.002a.28.28 0 0 1-.344-.444z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n3w7q4mjk {
  fill: var(--svg-color--efb9a2, #EFB9A2);
  d: path("m16.279 10.803l-.538 1.862c-.11.383.154.766.527.766h.796c.374 0 .638-.389.528-.766l-.538-1.862c-.116-.412-.654-.412-.775 0");
}

.n5l_opbqq {
  r: 6.305px;
}

.n6xdn4yaw {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m16.149 10.988l-.599 1.862c-.102.383.143.766.49.766h.742c.348 0 .593-.389.49-.766l-.5-1.862c-.108-.412-.51-.412-.623 0");
}

.n89hyfbom {
  d: path("M10.571 17.866c.64-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.085l4.317 10.391h-3.176c-1.068-2.583-3.293-7.817-3.68-8.742c-.42-1.004-.89-2.477-.297-3.86");
}

.nc-4r020u {
  d: path("m16.279 10.803l-.538 1.862c-.11.383.154.766.527.766h.796c.374 0 .638-.389.528-.766l-.538-1.862c-.116-.412-.654-.412-.775 0");
}

.npfrbd3jd {
  stop-color: var(--svg-color--dd3537, #DD3537);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.nu1yrov3v {
  fill: var(--svg-color--000, #000);
  d: path("M14.86 11.012a.516.516 0 0 0-.517-.518a.516.516 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.238");
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o_f_m1bbo {
  d: path("M21.54 12.877q.102-1.616.187-3.232a1.63 1.63 0 0 1-.187 3.232");
}

.o0l6_mb5d {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.977 9.833c.661 0 1.22.456 1.372 1.072a.278.278 0 0 1-.271.345h-2.26a.233.233 0 0 1-.23-.275a1.416 1.416 0 0 1 1.389-1.142");
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe7t4pblk {
  d: path("M16.555 14.453c-.514 0-.997-.121-1.403-.333c-.139-.07-.288.086-.2.212c.339.514.93.856 1.603.856c.674 0 1.265-.342 1.604-.856c.087-.131-.062-.283-.2-.212a3 3 0 0 1-1.404.333");
}

.orc6_jalb {
  d: path("M5.766 30.451c0-7.96 4.618-9.875 5.375-10.382l5.047 10.382z");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ovr-t3yxx {
  stroke: var(--svg-color--fcc4b2, #FCC4B2);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.823 18.85c.19.027.71.033 1.275-.163");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p5jt_ib0l {
  stop-color: var(--svg-color--e04438, #E04438);
}

.p66qg5jpt {
  d: path("M14.343 10.108a.904.904 0 0 0-.87 1.142h1.745a1 1 0 0 0 .033-.238a.91.91 0 0 0-.908-.904");
}

.pbkzvtx_w {
  stop-color: var(--svg-color--e06d3d, #E06D3D);
}

.pjzr3aclu {
  stop-color: var(--svg-color--d03d1c, #D03D1C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pngg7lbcs {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.79 5.831l-.066-.138a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.422v.28c-.344-.263-.777-.816-.777-1.71c0-1.086.791-1.635 1.297-1.985c.142-.098.262-.181.334-.256l.101-.106c.354-.376.985-1.045 2.087-1.337a5.5 5.5 0 0 1 1.537-.167c.473.012.806.42.806.893v1.515z");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.qai6kx0km {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.7 10.299c.065.086-.07.191-.222.306c-.153.114-.267.194-.331.108c-.065-.086.007-.248.16-.363s.33-.137.394-.051");
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qdcgkefpz {
  stop-color: var(--svg-color--f1b6a2, #F1B6A2);
}

.qnar36wle {
  r: 4.086px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.r9e33mbdc {
  stop-color: var(--svg-color--e7a08d, #E7A08D);
  stop-opacity: 0;
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rzilvpbra {
  d: path("M11.669 14.32a3.966 3.966 0 0 0 3.935 3.449h1.91a3.966 3.966 0 0 0 3.936-3.45c.12-1.908.24-3.808.329-5.715a1.47 1.47 0 0 0-1.397-1.45h-1.418c-.967 0-1.843-.57-2.24-1.461a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.422c0 1.885.118 3.739.242 5.628");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tl7m_rblj {
  d: path("M15.17 10.906c0-.293-.239-.487-.303-.546l-.292.282l.18.366z");
}

.tptc_3u7h {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.187 14.054c.395.205.866.324 1.368.324c.508 0 .974-.119 1.369-.325a.23.23 0 0 1 .274.045a.215.215 0 0 1 .023.275m-3.034-.32l2.972.279m-2.972-.279a.23.23 0 0 0-.274.047a.214.214 0 0 0-.024.274m.298-.32l-.235.278m3.27.041l-.063-.041m.062.041l-.062-.041m.062.041c-.352.535-.966.89-1.666.89a2 2 0 0 1-1.665-.89m3.269-.041c-.34.514-.93.856-1.604.856a1.92 1.92 0 0 1-1.603-.856m-.062.042l.062-.042m-.062.042l-.001-.001l.063-.041");
}

.u-5_dfr8d {
  cx: 14.07px;
  cy: 10.494px;
  rx: 0.395px;
  ry: 0.2px;
}

.u4bo2-o9a {
  stop-color: var(--svg-color--d84f1a, #D84F1A);
  stop-opacity: 0;
}

.uby2uabyx {
  cx: 14.07px;
  cy: 10.494px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.ue2ywxbfs {
  stop-color: var(--svg-color--e45c36, #E45C36);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.up5p4s41k {
  stop-color: var(--svg-color--e64812, #E64812);
  stop-opacity: 0;
}

.uqmxc1zfy {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.139 8.674c.26-.187.909-.515 1.676-.386");
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v1nc78bgs {
  stop-color: var(--svg-color--fabfa6, #FABFA6);
}

.v5myhy--q {
  fill: var(--svg-color--000, #000);
  d: path("M18.25 11.012c0-.288.23-.518.517-.518a.515.515 0 0 1 .46.756h-.916a.47.47 0 0 1-.061-.238");
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w_5-rbc1a {
  stop-color: var(--svg-color--dd3537, #DD3537);
  stop-opacity: 0;
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w0wa9coif {
  d: path("M18.7 10.299c.065.086-.07.191-.222.306c-.153.114-.267.194-.331.108c-.065-.086.007-.248.16-.363s.33-.137.394-.051");
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.www4dfogh {
  stop-color: var(--svg-color--d69b93, #D69B93);
  stop-opacity: 0;
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x3axlob0n {
  stop-color: var(--svg-color--e24c14, #E24C14);
  stop-opacity: 0;
}

.x3nq2abto {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.835 9.14l-.03-.64c-.01-.773-.65-1.41-1.423-1.443h-1.418c-.9 0-1.722-.492-2.151-1.276c0 0-.063-.146-.127-.394c-.251-.972.675-1.713 1.66-1.524c.991.19 2.125.524 2.961 1.07c1.767 1.152 1.458 3.229.528 4.207");
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yegzzobzs {
  d: path("M21.625 12.225q.06-.964.112-1.928a.968.968 0 0 1-.112 1.928");
}

.yf3t3eb5f {
  stop-color: var(--svg-color--ff8244, #FF8244);
}

.ykdcls_lk {
  stop-color: var(--svg-color--dd3d3d, #DD3D3D);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yp0_j3bzj {
  d: path("m16.79 5.831l-.066-.138a.67.67 0 0 0-.623-.424h-1.29c-1.869 0-3.384 1.532-3.384 3.422v.28c-.344-.263-.777-.816-.777-1.71c0-1.086.791-1.635 1.297-1.985c.142-.098.262-.181.334-.256l.101-.106c.354-.376.985-1.045 2.087-1.337a5.5 5.5 0 0 1 1.537-.167c.473.012.806.42.806.893v1.515z");
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z2ddyab4m {
  stop-color: var(--svg-color--f47246, #F47246);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
