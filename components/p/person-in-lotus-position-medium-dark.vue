<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNrF2pe)" clip-rule="evenodd" class="v-p5omnxm"/><path fill="url(#ix6Xttz)" clip-rule="evenodd" class="bqwscm-5z"/><g filter="url(#iVbe7hc)"><path fill="url(#ivX4G9d)" class="mxe5l-b8x"/><path fill="url(#iW4x3Ab)" class="mxe5l-b8x"/></g><path fill="url(#iO85Ioe)" class="qwmps2bvc"/><path fill="url(#izxZxRc)" class="qwmps2bvc"/><g filter="url(#iVnZpee)"><path class="prclsku2r"/></g><path fill="url(#iKiCzZd)" class="qqq97ebkd"/><path fill="url(#iiFEQcd)" class="qqq97ebkd"/><path fill="url(#iGN0Srd)" class="m8zsuwtqz"/><path fill="url(#iP9bEab)" class="m8zsuwtqz"/><path fill="url(#in4YxlZ)" class="m8zsuwtqz"/><path fill="url(#iTnKCnb)" class="gqrdhsbjl"/><path fill="url(#iTckrTb)" class="gqrdhsbjl"/><path fill="url(#iGhyBvb)" class="gqrdhsbjl"/><path class="k35fcl5jt"/><path fill="url(#iNKaK5d)" class="ndxr44g2h"/><path fill="url(#iTC8V9c)" class="ndxr44g2h"/><path fill="url(#i4WsjBd)" class="ndxr44g2h"/><g filter="url(#i6g5Yqe)"><path class="vw15ly9ml"/><path fill="url(#iAYljWY)" class="vvb767b_n"/><path fill="url(#iMoTuoe)" class="vvb767b_n"/><path fill="url(#ihu4IkG)" class="vvb767b_n"/></g><g filter="url(#i9gRnWb)"><path fill="url(#ivci6pe)" class="ha61p4glz"/></g><path fill="url(#iIcBume)" class="xm_vkhc8e"/><path fill="url(#iiQ7ZOd)" class="xm_vkhc8e"/><g filter="url(#icWJqHd)"><path fill="url(#iFbbife)" class="d56lu3b4e"/><path fill="url(#iNNdesb)" class="d56lu3b4e"/></g><path fill="url(#i0wzcic)" class="d56lu3b4e"/><path clip-rule="evenodd" class="u-pnczexz"/><path fill="url(#ipqwM0h)" clip-rule="evenodd" class="vptm73pei"/><path clip-rule="evenodd" class="oredwtbaj"/><path fill="url(#iGxWiQw)" clip-rule="evenodd" class="r5pwk0gbc"/><path clip-rule="evenodd" class="nem74_0hw"/><path fill="url(#iV88ard)" clip-rule="evenodd" class="w--l981bs"/><path clip-rule="evenodd" class="wvfqsebhh"/><path fill="url(#iAErS6w)" clip-rule="evenodd" class="jch7h-fqu"/><path clip-rule="evenodd" class="c-kta4btk"/><path fill="url(#iRwZ5Qd)" clip-rule="evenodd" class="mriigjb_g"/><path clip-rule="evenodd" class="byz--3v8z"/><path fill="url(#iEo7Sbb)" clip-rule="evenodd" class="fdw6rbsah"/><path clip-rule="evenodd" class="zzugnabyz"/><path fill="url(#iRd1jFB)" clip-rule="evenodd" class="op0wkpb0r"/><path fill="url(#iLudReb)" clip-rule="evenodd" class="g3wgqm9be"/><path fill="url(#i7ZjFzd)" clip-rule="evenodd" class="g3wgqm9be"/><g filter="url(#i41n0Me)"><path class="bkc562icz"/></g><g filter="url(#izyJQad)"><path class="fiey0bcyc"/></g><g filter="url(#iPfQ0me)"><path class="y0wx1bb9h"/></g><g filter="url(#iuJz29d)"><path class="myrevfu1h"/></g><g filter="url(#iBn3fDd)"><path class="oi55gf_3k"/></g><g filter="url(#iGpBfNe)"><path class="ihpyawbfq"/></g><g filter="url(#icLLKAe)"><path class="tmp_5wbql"/></g><g filter="url(#idgZ2Od)"><path class="dd12ftb5w"/></g><path fill="url(#inUVzXk)" class="pmsjr6bsi"/><path fill="url(#iWSJeUb)" class="w8k55npif"/><g filter="url(#iGGAacb)"><path fill="url(#io0IM5c)" class="bun-84bgj"/><path fill="url(#iTtdmGc)" class="bun-84bgj"/></g><path fill="url(#iRGZLAe)" class="bun-84bgj"/><path fill="url(#iKJ93Tb)" class="bun-84bgj"/><path fill="url(#iq4MsOc)" class="bun-84bgj"/><path fill="url(#i0SEgue)" class="bun-84bgj"/><path fill="url(#iAm5MLc)" class="bun-84bgj"/><path fill="url(#iTKecuc)" class="bun-84bgj"/><path fill="url(#iZbI1Gc)" class="bun-84bgj"/><g filter="url(#igWvHRc)"><path class="gr43_ybyw"/></g><g filter="url(#imeucUd)"><path class="vluiwtbzo"/><path fill="url(#ibFk03c)" class="vfp6t-bnj"/><path fill="url(#iQ9JGee)" class="vfp6t-bnj"/><path fill="url(#iGQRCod)" class="vfp6t-bnj"/><path fill="url(#iW9Fx0k)" class="vfp6t-bnj"/><path fill="url(#ioyYwJb)" class="vfp6t-bnj"/></g><g filter="url(#icCLXid)"><path stroke="url(#itD0KDd)" class="wcudicc8v"/></g><path fill="url(#ifvknHl)" class="d81s04x-l"/><g filter="url(#ii8bMrd)"><path fill="url(#ig0nNrb)" class="mjkj73b5h"/><path fill="url(#ia9B3ut)" class="mjkj73b5h"/><path fill="url(#iDMJM3d)" class="mjkj73b5h"/><path fill="url(#iidInHd)" class="mjkj73b5h"/><path fill="url(#i0gThAg)" class="mjkj73b5h"/></g><g filter="url(#i7GAeRc)"><path class="c-7pebb-m"/></g><g filter="url(#io77QLc)"><path class="tnfgwhb4m"/></g><g filter="url(#iirT9sa)"><path class="wanqdut6i"/><path fill="url(#iVUdv4d)" class="ydii2-bnu"/><path fill="url(#iUf8mdc)" class="ydii2-bnu"/></g><g filter="url(#irsokMb)"><path class="m8cdiqb3d"/><path fill="url(#inXA87R)" class="t732gtbqr"/><path fill="url(#i2IIQ6c)" class="t732gtbqr"/></g><path fill="url(#iZeViGB)" class="boim9zblr"/><path fill="url(#i7WSl6b)" class="boim9zblr"/><path fill="url(#ifTgkQL)" class="boim9zblr"/><path fill="url(#i7EOwhe)" class="boim9zblr"/><path fill="url(#iVH4Nke)" class="re30_lbge"/><path fill="url(#iACXwwc)" class="re30_lbge"/><g filter="url(#ieIEYeb)"><path fill="url(#ie7VQCb)" class="feh68vkoh"/></g><g filter="url(#iQYYvAN)"><path fill="url(#iNYyDFc)" class="v8y7chbrq"/></g><g filter="url(#idHxiTd)"><path class="pzxl94bxb"/></g><g filter="url(#iePKK6L)"><path class="so-8g63-v"/></g><g filter="url(#i8bIkdc)"><path class="gk2trybti"/></g><path class="yxzw7xq0l"/><g filter="url(#i1h0K8c)"><path class="uog8y2bhk"/></g><path class="yoczqccrz"/><g filter="url(#irWiCIe)"><path class="pt3c3xs4k"/></g><defs><radialGradient id="iNrF2pe" cx="0" cy="0" r="1" gradientTransform="rotate(109.231 -5.354 13.087)scale(.71158 1.43628)" gradientUnits="userSpaceOnUse"><stop class="e8kivk_8j"/><stop offset="1" class="el8j_lmyj"/></radialGradient><radialGradient id="ix6Xttz" cx="0" cy="0" r="1" gradientTransform="matrix(.23438 .67187 -1.35614 .47307 26.835 22.453)" gradientUnits="userSpaceOnUse"><stop class="e8kivk_8j"/><stop offset="1" class="el8j_lmyj"/></radialGradient><radialGradient id="ivX4G9d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.10352 0 0 -6.94644 26.355 25.187)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="hhctjoo7s"/><stop offset="1" class="uuwoulbxc"/></radialGradient><radialGradient id="iW4x3Ab" cx="0" cy="0" r="1" gradientTransform="rotate(63.783 -6.868 31.62)scale(1.72425 1.82152)" gradientUnits="userSpaceOnUse"><stop class="sg0n-eqag"/><stop offset="1" class="r65q887vt"/></radialGradient><radialGradient id="iO85Ioe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 .71875 -.52498 1.8945 9.876 28.531)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="qww_2wbks"/><stop offset="1" class="ojtt1ubdv"/></radialGradient><radialGradient id="izxZxRc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 -.59375 1.5068 -6.10651 12.06 29.172)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="k7blc57pd"/><stop offset="1" class="gn_p8e8sd"/></radialGradient><radialGradient id="iKiCzZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .21875 -.60896 -2.43587 21.294 25.864)" gradientUnits="userSpaceOnUse"><stop class="qux0lkedt"/><stop offset="1" class="uxc3_1big"/></radialGradient><radialGradient id="iiFEQcd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 -.7705 1.76305 5.29137 5.576 25.74)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q7352-9kv"/><stop offset="1" class="arw8-l5dn"/></radialGradient><radialGradient id="iGN0Srd" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 0 0 1.90625 19.533 23.094)" gradientUnits="userSpaceOnUse"><stop class="g06b8fbvn"/><stop offset="1" class="q05jf29-x"/></radialGradient><radialGradient id="iTnKCnb" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 0 0 1.91303 8.607 22.82)" gradientUnits="userSpaceOnUse"><stop class="hxe1-qbdv"/><stop offset="1" class="gvgzd5bho"/></radialGradient><radialGradient id="iTC8V9c" cx="0" cy="0" r="1" gradientTransform="matrix(3.44922 -3.1199 1.05784 1.1695 7.157 23.495)" gradientUnits="userSpaceOnUse"><stop class="osj_oacvf"/><stop offset="1" class="m_3-9ebgy"/></radialGradient><radialGradient id="i4WsjBd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.61326 3.09376 -1.04179 -.54325 12.24 20)" gradientUnits="userSpaceOnUse"><stop class="o0g94xb_k"/><stop offset="1" class="lfzrz9u2y"/></radialGradient><radialGradient id="iMoTuoe" cx="0" cy="0" r="1" gradientTransform="rotate(-142.496 17.237 7.531)scale(1.69385 2.1643)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="to3b9rbvd"/><stop offset="1" class="d10de8bzv"/></radialGradient><radialGradient id="ihu4IkG" cx="0" cy="0" r="1" gradientTransform="matrix(4.85545 9.53121 -4.36739 2.22486 21.47 13.094)" gradientUnits="userSpaceOnUse"><stop class="lgzeshbhm"/><stop offset="1" class="b1hmbi0gc"/></radialGradient><radialGradient id="ivci6pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 4.03125 -8.3959 -1.43187 18.439 21.094)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ai9-2ku0o"/><stop offset=".925" class="gsv8efolz"/></radialGradient><radialGradient id="iIcBume" cx="0" cy="0" r="1" gradientTransform="rotate(-128.1 12.068 2.398)scale(3.49455 5.00001)" gradientUnits="userSpaceOnUse"><stop class="e2jk3lbzi"/><stop offset="1" class="l1gvkpboh"/></radialGradient><radialGradient id="iiQ7ZOd" cx="0" cy="0" r="1" gradientTransform="rotate(108.939 3.732 10.238)scale(3.36993 3.80066)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="rgcbzi4wz"/><stop offset="1" class="es0ucmbxo"/></radialGradient><radialGradient id="iFbbife" cx="0" cy="0" r="1" gradientTransform="matrix(.5 8.04173 -7.73502 .48093 17.689 13.281)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ydcxvabaw"/><stop offset="1" class="hekp_gbnf"/></radialGradient><radialGradient id="iNNdesb" cx="0" cy="0" r="1" gradientTransform="rotate(141.869 7.577 10.752)scale(10.274 13.0752)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="ksocwfbza"/><stop offset="1" class="ecaf6kbqo"/></radialGradient><radialGradient id="i0wzcic" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 2.0625 -5.62896 10.23446 11.627 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="bmu4g5dxl"/><stop offset="1" class="z321yabtz"/></radialGradient><radialGradient id="ipqwM0h" cx="0" cy="0" r="1" gradientTransform="matrix(.11328 .6422 -3.96388 .69921 4.51 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="whcdqwb8b"/><stop offset=".958" class="e575psbmi"/></radialGradient><radialGradient id="iGxWiQw" cx="0" cy="0" r="1" gradientTransform="matrix(-.11328 .6422 -3.96388 -.69922 27.49 23.047)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="iV88ard" cx="0" cy="0" r="1" gradientTransform="matrix(.12686 .83746 -4.47454 .67782 4.517 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="whcdqwb8b"/><stop offset=".958" class="e575psbmi"/></radialGradient><radialGradient id="iAErS6w" cx="0" cy="0" r="1" gradientTransform="matrix(-.12686 .83746 -4.47454 -.67782 27.483 23.672)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="iRwZ5Qd" cx="0" cy="0" r="1" gradientTransform="matrix(.11226 .95131 -3.99486 .47143 5 24.226)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="whcdqwb8b"/><stop offset=".958" class="e575psbmi"/></radialGradient><radialGradient id="iEo7Sbb" cx="0" cy="0" r="1" gradientTransform="rotate(96.73 2.732 24.113)scale(.95791 4.02259)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="iRd1jFB" cx="0" cy="0" r="1" gradientTransform="matrix(.10014 1.0686 -3.5818 .33567 5.935 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="r1i2lobcl"/><stop offset="1" class="x4fpn9o2k"/></radialGradient><radialGradient id="i7ZjFzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10014 1.0686 -3.5818 -.33567 26.065 24.411)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="w84n4ouwr"/><stop offset="1" class="oyrzqh62n"/></radialGradient><radialGradient id="inUVzXk" cx="0" cy="0" r="1" gradientTransform="matrix(.47081 1.26984 -1.50846 .55929 19.021 8.379)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iWSJeUb" cx="0" cy="0" r="1" gradientTransform="matrix(.92837 .29179 -.90017 2.86404 12.225 8.687)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="io0IM5c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28715 0 0 -5.81494 17.798 7.787)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iTtdmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09606 1.81274 -1.49656 -.90489 17.558 4.656)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iKJ93Tb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72206 .89354 0 17.571 6.961)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iq4MsOc" cx="0" cy="0" r="1" gradientTransform="matrix(.00247 -.68806 .74877 .00269 14.586 6.99)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="i0SEgue" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 8.963 4.49)scale(5.35271 13.6735)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iAm5MLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.1289 -1.83381 .54168 .62884 11.762 6.068)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iTKecuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.14755 1.57033 -.62773 -.05898 19.519 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iZbI1Gc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.79144 -8.18638 0 16.062 4.875)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="d-a125qte"/><stop offset="1" class="rl1b_tbez"/></radialGradient><radialGradient id="iQ9JGee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .15349 -.48239 0 16.325 8.642)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iW9Fx0k" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 7.295 5.932)scale(1.0522 1.69097)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ifvknHl" cx="0" cy="0" r="1" gradientTransform="matrix(1.37198 -.6745 2.7137 5.51982 15.723 10.065)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ia9B3ut" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.20155 5.56747 0 12.75 5.966)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iDMJM3d" cx="0" cy="0" r="1" gradientTransform="matrix(.0717 -1.57982 2.79915 .12705 19.089 6.792)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iidInHd" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 9.733 -1.364)scale(1.77522 1.3031)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="i0gThAg" cx="0" cy="0" r="1" gradientTransform="rotate(60.726 6.158 14.12)scale(.86371 1.99995)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iVUdv4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38402 0 0 -.51366 16.192 3.265)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iUf8mdc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02351 -3.2039 3.54958 2.24184 12.618 5.744)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="inXA87R" cx="0" cy="0" r="1" gradientTransform="matrix(1.68432 -1.60475 2.93788 3.08355 17.688 5.663)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="i2IIQ6c" cx="0" cy="0" r="1" gradientTransform="matrix(2.0424 .23873 -.09995 .85512 17.132 4.735)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i7WSl6b" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 4.708 16.095)scale(1.46484 1.39757)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="ifTgkQL" cx="0" cy="0" r="1" gradientTransform="matrix(.49534 -.67977 .56979 .41519 19.163 7.562)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i7EOwhe" cx="0" cy="0" r="1" gradientTransform="matrix(.3691 -.97487 1.30256 .49316 19.235 7.67)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iACXwwc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04267 0 0 -1.16429 12.942 7.622)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="ie7VQCb" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 6.146 4.363)scale(.58469 .59949)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iVbe7hc" width="9.729" height="6.156" x="17.627" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.282353 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23988" result="effect2_innerShadow_3987_23988"/></filter><filter id="iVnZpee" width="17.213" height="7.995" x="5.751" y="21.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.270588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.282353 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23988" result="effect2_innerShadow_3987_23988"/></filter><filter id="i6g5Yqe" width="7.621" height="12.797" x="19.836" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.188235 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/></filter><filter id="i9gRnWb" width="8.502" height="3.19" x="11.869" y="21.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.247059 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/></filter><filter id="icWJqHd" width="8.289" height="10.271" x="11.888" y="11.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.423529 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/></filter><filter id="i41n0Me" width="1.684" height="1.255" x="5.351" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="izyJQad" width="1.684" height="1.255" x="24.965" y="24.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="iPfQ0me" width="2.04" height="1.095" x="4.237" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="iuJz29d" width="2.04" height="1.095" x="25.723" y="23.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="iBn3fDd" width="2.223" height=".888" x="3.593" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="iGpBfNe" width="2.223" height=".888" x="26.184" y="23.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="icLLKAe" width="2.031" height=".566" x="3.653" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="idgZ2Od" width="2.031" height=".566" x="26.317" y="22.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="iGGAacb" width="7.426" height="7.96" x="12.849" y="3.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23988" result="effect2_innerShadow_3987_23988"/></filter><filter id="igWvHRc" width="3.098" height="3.823" x="14.394" y="6.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".5"/></filter><filter id="imeucUd" width="1.38" height="2.023" x="15.342" y="7.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".05"/></filter><filter id="icCLXid" width="2.524" height="1.175" x="14.77" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".05"/></filter><filter id="ii8bMrd" width="8.094" height="5.44" x="11.985" y="1.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23988" result="effect2_innerShadow_3987_23988"/></filter><filter id="i7GAeRc" width="1.508" height=".823" x="17.032" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/></filter><filter id="io77QLc" width="1.508" height=".813" x="13.727" y="5.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/></filter><filter id="iirT9sa" width="4.126" height="3.749" x="12.216" y="2.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23988"/><feGaussianBlur result="effect2_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="irsokMb" width="3.857" height="3.515" x="16.042" y="2.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="ieIEYeb" width="1.021" height="1.682" x="12.116" y="6.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".125"/></filter><filter id="iQYYvAN" width="1.595" height="2.197" x="18.641" y="6.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".25"/></filter><filter id="idHxiTd" width="1.441" height=".658" x="13.711" y="5.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="iePKK6L" width="1.441" height=".658" x="17.031" y="5.533" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".075"/></filter><filter id="i8bIkdc" width="2.868" height="1.447" x="16.807" y="3.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".125"/></filter><filter id="i1h0K8c" width="1.628" height=".644" x="13.82" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".05"/></filter><filter id="irWiCIe" width="1.628" height=".644" x="16.609" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23988" stdDeviation=".05"/></filter><linearGradient id="iP9bEab" x1="21.525" x2="21.525" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="y69ibv-do"/><stop offset="1" class="yw5dd8t_v"/></linearGradient><linearGradient id="in4YxlZ" x1="18.658" x2="19.892" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="h3px5kbzs"/><stop offset="1" class="gjk5l0f7i"/></linearGradient><linearGradient id="iTckrTb" x1="10.822" x2="10.822" y1="21.031" y2="22.187" gradientUnits="userSpaceOnUse"><stop class="x3bti8ber"/><stop offset="1" class="hbhny8bey"/></linearGradient><linearGradient id="iGhyBvb" x1="13.689" x2="12.455" y1="24.315" y2="24.719" gradientUnits="userSpaceOnUse"><stop offset=".106" class="x3bti8ber"/><stop offset="1" class="hbhny8bey"/></linearGradient><linearGradient id="iNKaK5d" x1="12.24" x2="10.033" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="jq5vnpb6e"/><stop offset="1" class="wa0r83b7o"/></linearGradient><linearGradient id="iAYljWY" x1="19.835" x2="22.042" y1="20.637" y2="20.446" gradientUnits="userSpaceOnUse"><stop offset=".184" class="psa8qnbsw"/><stop offset="1" class="piww_ebpc"/></linearGradient><linearGradient id="iLudReb" x1="26.794" x2="24.919" y1="25.145" y2="24.052" gradientUnits="userSpaceOnUse"><stop class="uj_eajbrd"/><stop offset="1" class="v4t97l5et"/></linearGradient><linearGradient id="iRGZLAe" x1="19.275" x2="17.685" y1="8.846" y2="8.846" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ibFk03c" x1="16.559" x2="16.032" y1="8.211" y2="8.233" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iGQRCod" x1="16.032" x2="16.032" y1="8.927" y2="8.635" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="ioyYwJb" x1="16.032" x2="16.032" y1="7.226" y2="7.57" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="itD0KDd" x1="15.277" x2="15.477" y1="9.915" y2="9.39" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ig0nNrb" x1="20.341" x2="13.039" y1="4.226" y2="4.226" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iZeViGB" x1="20.08" x2="19.321" y1="7.261" y2="8.63" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iVH4Nke" x1="12.354" x2="13.271" y1="7.704" y2="7.624" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iNYyDFc" x1="19.438" x2="19.438" y1="7.021" y2="8.218" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-lotus-position-medium-dark" /></template>
<style>
.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ai9-2ku0o {
  stop-color: var(--svg-color--9f96a7, #9F96A7);
}

.arw8-l5dn {
  stop-color: var(--svg-color--875f5a, #875F5A);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b1hmbi0gc {
  stop-color: var(--svg-color--9a766b, #9A766B);
  stop-opacity: 0;
}

.bkc562icz {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.576 25.055a15 15 0 0 0 1.234-.805");
}

.bmu4g5dxl {
  stop-color: var(--svg-color--c56d32, #C56D32);
}

.boim9zblr {
  d: path("M19.127 8.63q.064-1.004.117-2.007a1.012 1.012 0 0 1-.117 2.007");
}

.bqwscm-5z {
  fill-rule: evenodd;
  d: path("M25.316 22.957a.5.5 0 0 0 .5.5c.632 0 1.257-.193 1.5-.268l.04-.012a.5.5 0 0 0-.292-.957l-.03.01c-.246.075-.743.227-1.218.227a.5.5 0 0 0-.5.5");
}

.bun-84bgj {
  d: path("M12.999 9.525a2.46 2.46 0 0 0 2.443 2.142h1.186a2.46 2.46 0 0 0 2.443-2.142c.074-1.184.149-2.364.204-3.548a.91.91 0 0 0-.867-.9h-.88c-.6 0-1.144-.354-1.391-.907a.42.42 0 0 0-.387-.263h-.8c-1.16 0-2.101.95-2.101 2.124c0 1.17.073 2.321.15 3.494");
}

.byz--3v8z {
  fill: var(--svg-color--7d4d41, #7D4D41);
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 0 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-7pebb-m {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M18.38 5.913a1.2 1.2 0 0 0-.433-.259c-.191-.06-.43-.076-.762-.035a.175.175 0 0 0 .042.346c.303-.037.488-.018.616.022c.124.04.209.103.308.189a.174.174 0 1 0 .229-.263");
}

.c-kta4btk {
  fill: var(--svg-color--856054, #856054);
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 0 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.d-a125qte {
  stop-color: var(--svg-color--7f4d58, #7F4D58);
  stop-opacity: 0;
}

.d10de8bzv {
  stop-color: var(--svg-color--83574a, #83574A);
  stop-opacity: 0;
}

.d56lu3b4e {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724a6.5 6.5 0 0 0-1.27.896v9.276h8.289v-9.276c-.198-.2-.662-.559-1.285-.894");
}

.d81s04x-l {
  d: path("M16.032 9.608c-.319 0-.619-.075-.87-.207c-.087-.043-.18.054-.125.132c.21.319.577.532.995.532s.785-.213.996-.532c.054-.082-.038-.175-.125-.132a1.9 1.9 0 0 1-.87.207");
}

.dd12ftb5w {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.122 23.265c-.398 0-.893.047-1.58-.109");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e2jk3lbzi {
  stop-color: var(--svg-color--97746b, #97746B);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e575psbmi {
  stop-color: var(--svg-color--80504e, #80504E);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.e8kivk_8j {
  stop-color: var(--svg-color--825a4a, #825A4A);
}

.ecaf6kbqo {
  stop-color: var(--svg-color--cc3a05, #CC3A05);
}

.el8j_lmyj {
  stop-color: var(--svg-color--835a4d, #835A4D);
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.es0ucmbxo {
  stop-color: var(--svg-color--704e43, #704E43);
  stop-opacity: 0;
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdw6rbsah {
  fill-rule: evenodd;
  d: path("M25.902 23.947a.4.4 0 0 0 .043.564c.34.29.628.456.903.549c.254.086.478.101.655.114l.037.002a.4.4 0 0 0 .057-.798l-.018-.001a1.8 1.8 0 0 1-.474-.075c-.156-.052-.357-.158-.64-.4a.4.4 0 0 0-.564.045");
}

.feh68vkoh {
  d: path("M12.835 7.033a.601.601 0 0 0 .052 1.182q-.033-.591-.052-1.182");
}

.fiey0bcyc {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M26.424 25.055a15 15 0 0 1-1.234-.805");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.g06b8fbvn {
  stop-color: var(--svg-color--6a4e48, #6A4E48);
}

.g3wgqm9be {
  fill-rule: evenodd;
  d: path("M25.182 24.172c-.14.17-.272.303-.101.443a5.8 5.8 0 0 0 1.193.783l.072.037a.4.4 0 0 0 .367-.711l-.074-.038a5 5 0 0 1-1.051-.69c-.17-.14-.266.005-.406.176");
}

.gjk5l0f7i {
  stop-color: var(--svg-color--593440, #593440);
  stop-opacity: 0;
}

.gk2trybti {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M18.669 4.228h-1.308a.303.303 0 1 1 .048-.605c.34.054.79.13 1.092.205c.683.169.871.501.924.738a.95.95 0 0 0-.756-.338");
}

.gn_p8e8sd {
  stop-color: var(--svg-color--926c6a, #926C6A);
}

.gqrdhsbjl {
  d: path("M13.83 21.323H7.814v2.692c2.531.352 6.016.297 6.016.297z");
}

.gr43_ybyw {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.78 7.46l-.371 1.156c-.064.238.088.476.304.476h.46c.216 0 .368-.242.305-.476l-.311-1.156c-.067-.256-.317-.256-.387 0");
}

.gsv8efolz {
  stop-color: var(--svg-color--6e6773, #6E6773);
}

.gvgzd5bho {
  stop-color: var(--svg-color--603b3a, #603B3A);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h3px5kbzs {
  stop-color: var(--svg-color--593440, #593440);
}

.ha61p4glz {
  d: path("m13.447 24.312l-1.578-2.99h8.301l-1.551 2.99z");
}

.hbhny8bey {
  stop-color: var(--svg-color--4e2b29, #4E2B29);
  stop-opacity: 0;
}

.hekp_gbnf {
  stop-color: var(--svg-color--f74d05, #F74D05);
}

.hhctjoo7s {
  stop-color: var(--svg-color--815e58, #815E58);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hxe1-qbdv {
  stop-color: var(--svg-color--80645d, #80645D);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ihpyawbfq {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M28.182 24.015a3.8 3.8 0 0 1-1.773-.437");
}

.jch7h-fqu {
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.jq5vnpb6e {
  stop-color: var(--svg-color--652e27, #652E27);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k35fcl5jt {
  fill: var(--svg-color--7f5344, #7F5344);
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k7blc57pd {
  stop-color: var(--svg-color--926c6a, #926C6A);
  stop-opacity: 0;
}

.ksocwfbza {
  stop-color: var(--svg-color--ee5422, #EE5422);
  stop-opacity: 0;
}

.l1gvkpboh {
  stop-color: var(--svg-color--7b5449, #7B5449);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lfzrz9u2y {
  stop-color: var(--svg-color--4f1d19, #4F1D19);
  stop-opacity: 0;
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lgzeshbhm {
  stop-color: var(--svg-color--9a766b, #9A766B);
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_3-9ebgy {
  stop-color: var(--svg-color--8e6757, #8E6757);
  stop-opacity: 0;
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m8cdiqb3d {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m19.31 6.31l-.018-.397a.924.924 0 0 0-.884-.897h-.88a1.52 1.52 0 0 1-1.336-.792s.453-1.3 1.2-1.11c.527.134 1.09.338 1.532.627c1.097.715.963 1.961.386 2.569");
}

.m8zsuwtqz {
  d: path("M18.517 21.323h6.016v2.692c-2.532.352-6.016.297-6.016.297z");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mjkj73b5h {
  d: path("M19.085 3.61c.323.111.614.337.797.66a1.49 1.49 0 0 1-.067 1.59a1 1 0 0 0-.17.549v.747a1.1 1.1 0 0 0-.42-.169l.05-1.01a.91.91 0 0 0-.867-.9h-.88c-.6 0-1.144-.354-1.391-.907a.42.42 0 0 0-.387-.264h-.8c-1.16 0-2.101.952-2.101 2.125l.019.967c-.16.023-.327.077-.453.166v-.755a1 1 0 0 0-.17-.55a1.5 1.5 0 0 1-.09-1.538c.184-.347.48-.59.817-.708c.36-.128.667-.37.87-.698a1.46 1.46 0 0 1 1.818-.573a.94.94 0 0 0 .75 0a1.46 1.46 0 0 1 1.824.594c.194.32.497.552.851.674");
}

.mriigjb_g {
  fill-rule: evenodd;
  d: path("M6.099 23.947a.4.4 0 0 1-.044.564c-.34.29-.628.456-.903.549c-.254.086-.478.101-.655.114l-.037.002a.4.4 0 0 1-.057-.798l.018-.001c.19-.014.32-.023.475-.075s.356-.158.639-.4a.4.4 0 0 1 .564.045");
}

.mxe5l-b8x {
  d: path("M17.627 27.937h4.244c2.93 0 4.28-1.916 4.484-2.828l-2.531-2.328l-3.62 1.422l-2.578.11z");
}

.myrevfu1h {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.538 24.746c-.41-.066-1.204-.313-1.59-.645");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.ndxr44g2h {
  d: path("M9.755 16.08c.22-1.858 1.605-3.58 2.152-4.041l.332.315v7.276c-.25.652-.719 1.33-1.125 1.652c0 0-.867.814-4.171 3.304c-1.325-.185-2.095-1.094-2.074-1.703c.875-.5 3.37-2.969 4.011-3.606c.537-.535.64-1.215.875-3.197");
}

.nem74_0hw {
  fill: var(--svg-color--856054, #856054);
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.o0g94xb_k {
  stop-color: var(--svg-color--4f1d19, #4F1D19);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.oi55gf_3k {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.818 24.015a3.8 3.8 0 0 0 1.773-.437");
}

.ojtt1ubdv {
  stop-color: var(--svg-color--764060, #764060);
}

.op0wkpb0r {
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

.oredwtbaj {
  fill: var(--svg-color--7d4d41, #7D4D41);
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136q.082-.003.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.osj_oacvf {
  stop-color: var(--svg-color--9a766d, #9A766D);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oyrzqh62n {
  stop-color: var(--svg-color--6f423d, #6F423D);
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.piww_ebpc {
  stop-color: var(--svg-color--672b23, #672B23);
  stop-opacity: 0;
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pmsjr6bsi {
  d: path("M19.089 8.573c.21-.007.408-.079.569-.194v.585c0 .561-.335 1.062-.843 1.27q.161-.344.217-.743z");
}

.prclsku2r {
  fill: var(--svg-color--8b604f, #8B604F);
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.psa8qnbsw {
  stop-color: var(--svg-color--672b23, #672B23);
}

.pt3c3xs4k {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pzxl94bxb {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.911 6.02c.162-.116.565-.32 1.04-.24");
}

.q05jf29-x {
  stop-color: var(--svg-color--5b3938, #5B3938);
}

.q7352-9kv {
  stop-color: var(--svg-color--9f776f, #9F776F);
}

.qqq97ebkd {
  d: path("M10.236 27.937c-2.93 0-4.281-1.916-4.485-2.828l2.532-2.328l3.453 1.445l8.18.086a1 1 0 0 1 .944.67c.407 1.171.96 2.765 1.032 3.002c.11.36.25 1.453-.875 1.766c-.78.216-1.523-.938-2.11-1.813z");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qux0lkedt {
  stop-color: var(--svg-color--98736d, #98736D);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qwmps2bvc {
  d: path("M13.22 24.312h-1.429a1 1 0 0 0-.943.67c-.408 1.171-.96 2.765-1.032 3.002c-.11.36-.25 1.453.875 1.766c.757.21 1.48-.871 2.057-1.735l.052-.078h.42z");
}

.qww_2wbks {
  stop-color: var(--svg-color--804c5e, #804C5E);
}

.r1i2lobcl {
  stop-color: var(--svg-color--844e66, #844E66);
  stop-opacity: 0;
}

.r5pwk0gbc {
  fill-rule: evenodd;
  d: path("M26.304 23.047a.4.4 0 0 0 .265.5c.536.163 1.099.145 1.367.136q.082-.003.124-.002a.4.4 0 1 0 .018-.8q-.104-.002-.23.003c-.286.007-.656.017-1.045-.102a.4.4 0 0 0-.5.265");
}

.r65q887vt {
  stop-color: var(--svg-color--714a44, #714A44);
  stop-opacity: 0;
}

.re30_lbge {
  d: path("M12.86 6.615a1.012 1.012 0 0 0 .08 2.015a49 49 0 0 1-.08-2.015");
}

.rgcbzi4wz {
  stop-color: var(--svg-color--613b31, #613B31);
}

.rl1b_tbez {
  stop-color: var(--svg-color--754146, #754146);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sg0n-eqag {
  stop-color: var(--svg-color--5c322e, #5C322E);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.so-8g63-v {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18.272 5.991a1.46 1.46 0 0 0-1.041-.24");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t732gtbqr {
  d: path("m19.31 6.31l-.018-.397a.924.924 0 0 0-.884-.897h-.88a1.52 1.52 0 0 1-1.336-.792s.453-1.3 1.2-1.11c.527.134 1.09.338 1.532.627c1.097.715.963 1.961.386 2.569");
}

.tmp_5wbql {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M3.878 23.265c.398 0 .893.047 1.58-.109");
}

.tnfgwhb4m {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M13.888 5.845a1.74 1.74 0 0 1 1.093-.226a.174.174 0 1 1-.042.346a1.4 1.4 0 0 0-.92.209l-.01.007l-.002.002a.174.174 0 0 1-.213-.276z");
}

.to3b9rbvd {
  stop-color: var(--svg-color--9a756c, #9A756C);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.u-pnczexz {
  fill: var(--svg-color--856054, #856054);
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136q-.082-.003-.124-.002a.4.4 0 1 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.uj_eajbrd {
  stop-color: var(--svg-color--7d4d41, #7D4D41);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uog8y2bhk {
  stroke: var(--svg-color--2c2c2c, #2C2C2C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.uuwoulbxc {
  stop-color: var(--svg-color--7e544c, #7E544C);
}

.uxc3_1big {
  stop-color: var(--svg-color--98736d, #98736D);
  stop-opacity: 0;
}

.v-p5omnxm {
  fill-rule: evenodd;
  d: path("M6.76 22.957a.5.5 0 0 1-.5.5c-.632 0-1.257-.193-1.501-.268l-.04-.012a.5.5 0 0 1 .293-.957l.029.01c.246.075.743.227 1.219.227a.5.5 0 0 1 .5.5");
}

.v4t97l5et {
  stop-color: var(--svg-color--65362f, #65362F);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.v8y7chbrq {
  d: path("M19.14 8.218q.037-.598.07-1.197a.6.6 0 0 1-.07 1.197");
}

.vfp6t-bnj {
  d: path("m15.792 7.337l-.335 1.156c-.068.238.096.476.328.476h.494c.232 0 .396-.242.328-.476l-.334-1.156c-.072-.256-.406-.256-.481 0");
}

.vluiwtbzo {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.792 7.337l-.335 1.156c-.068.238.096.476.328.476h.494c.232 0 .396-.242.328-.476l-.334-1.156c-.072-.256-.406-.256-.481 0");
}

.vptm73pei {
  fill-rule: evenodd;
  d: path("M5.697 23.047a.4.4 0 0 1-.266.5c-.536.163-1.099.145-1.367.136q-.082-.003-.124-.002a.4.4 0 1 1-.018-.8q.104-.002.23.003c.286.007.656.017 1.045-.102a.4.4 0 0 1 .5.265");
}

.vvb767b_n {
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.vw15ly9ml {
  fill: var(--svg-color--824c3e, #824C3E);
  d: path("M22.32 16.08c-.22-1.858-1.605-3.58-2.152-4.041l-.332.315v7.276c.25.652.719 1.33 1.125 1.652c0 0 .867.814 4.172 3.304c1.325-.185 2.094-1.094 2.073-1.703c-.874-.5-3.37-2.969-4.01-3.606c-.538-.535-.641-1.215-.876-3.197");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w--l981bs {
  fill-rule: evenodd;
  d: path("M5.825 23.525a.4.4 0 0 1-.18.536a4.4 4.4 0 0 1-1.823.448a.4.4 0 0 1 0-.8a3.6 3.6 0 0 0 1.466-.364a.4.4 0 0 1 .537.18");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w84n4ouwr {
  stop-color: var(--svg-color--6f423d, #6F423D);
  stop-opacity: 0;
}

.w8k55npif {
  d: path("M12.976 8.573a1.03 1.03 0 0 1-.57-.194v.585c0 .561.335 1.062.844 1.27a2.6 2.6 0 0 1-.218-.743z");
}

.wa0r83b7o {
  stop-color: var(--svg-color--652e27, #652E27);
  stop-opacity: 0;
}

.wanqdut6i {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.179 4.256l-.042-.086a.42.42 0 0 0-.387-.263h-.8c-1.16 0-2.101.95-2.101 2.124v.173c-.214-.162-.483-.506-.483-1.061c0-.674.492-1.015.805-1.232a1.4 1.4 0 0 0 .208-.16q.03-.029.063-.065c.22-.233.611-.648 1.295-.83c.22-.058.442-.088.647-.1c.472-.025.808.386.808.859v.632z");
}

.wcudicc8v {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.196 9.335c.24.126.529.198.836.198c.31 0 .596-.072.837-.198a.17.17 0 0 1 .203.033c.049.05.067.133.018.206m-1.894-.24l1.832.199m-1.832-.198a.17.17 0 0 0-.204.035a.16.16 0 0 0-.018.205m.222-.24l-.16.198m2.054.041l-.062-.041m.062.041l-.062-.041m.062.041c-.224.34-.614.566-1.058.566c-.443 0-.833-.226-1.057-.565m2.053-.042a1.19 1.19 0 0 1-.996.532a1.19 1.19 0 0 1-.995-.532m-.062.042l.062-.042m-.062.042l.062-.042");
}

.whcdqwb8b {
  stop-color: var(--svg-color--80504e, #80504E);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wvfqsebhh {
  fill: var(--svg-color--7d4d41, #7D4D41);
  fill-rule: evenodd;
  d: path("M26.175 23.525a.4.4 0 0 0 .18.536a4.4 4.4 0 0 0 1.823.448a.4.4 0 0 0 0-.8a3.6 3.6 0 0 1-1.466-.364a.4.4 0 0 0-.537.18");
}

.x3bti8ber {
  stop-color: var(--svg-color--4e2b29, #4E2B29);
}

.x4fpn9o2k {
  stop-color: var(--svg-color--844e66, #844E66);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xm_vkhc8e {
  d: path("M18.892 11.153v.722a2.5 2.5 0 0 1-2.5 2.5h-.734a2.5 2.5 0 0 1-2.5-2.5v-.724c.763-.416 1.77-.784 2.914-.784c1.05 0 2.055.375 2.82.786");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y0wx1bb9h {
  stroke: var(--svg-color--916e68, #916E68);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M4.462 24.746c.41-.066 1.204-.313 1.59-.645");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y69ibv-do {
  stop-color: var(--svg-color--552b23, #552B23);
}

.ydcxvabaw {
  stop-color: var(--svg-color--ff7d3c, #FF7D3C);
}

.ydii2-bnu {
  d: path("m16.179 4.256l-.042-.086a.42.42 0 0 0-.387-.263h-.8c-1.16 0-2.101.95-2.101 2.124v.173c-.214-.162-.483-.506-.483-1.061c0-.674.492-1.015.805-1.232a1.4 1.4 0 0 0 .208-.16q.03-.029.063-.065c.22-.233.611-.648 1.295-.83c.22-.058.442-.088.647-.1c.472-.025.808.386.808.859v.632z");
}

.yoczqccrz {
  stroke: var(--svg-color--070506, #070506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M16.76 7.303a.81.81 0 0 0 .671.344c.297 0 .591-.23.656-.344");
}

.yw5dd8t_v {
  stop-color: var(--svg-color--552b23, #552B23);
  stop-opacity: 0;
}

.yxzw7xq0l {
  stroke: var(--svg-color--070506, #070506);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M13.97 7.303a.81.81 0 0 0 .672.344c.297 0 .591-.23.656-.344");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z321yabtz {
  stop-color: var(--svg-color--d3612e, #D3612E);
  stop-opacity: 0;
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zzugnabyz {
  fill: var(--svg-color--865f53, #865F53);
  fill-rule: evenodd;
  d: path("M6.818 24.172c.14.17.272.303.101.443a5.8 5.8 0 0 1-1.193.783l-.072.037a.4.4 0 0 1-.367-.711l.074-.038a5 5 0 0 0 1.051-.69c.17-.14.266.005.406.176");
}

</style>
