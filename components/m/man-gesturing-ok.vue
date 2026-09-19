<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iZjoYCO)" class="lfs2u60yo"/><g filter="url(#iYBDpBb)"><circle fill="url(#iIojTCb)" class="rv76ab9nb"/></g><g filter="url(#ihttspc)"><circle fill="url(#iqQJZRb)" class="uoe471bev"/><circle fill="url(#ifhzZcb)" class="uoe471bev"/></g><g filter="url(#iINOlCb)"><circle class="b4ahfq94n"/><circle fill="url(#it2ljAc)" class="cuodmbbdm"/><circle fill="url(#ivubI4b)" class="cuodmbbdm"/></g><g filter="url(#imXmUnv)"><path class="fitoduswx"/><path fill="url(#iDA47ic)" class="v20flvb2j"/></g><path fill="url(#iY4x29d)" class="v20flvb2j"/><path fill="url(#iPWfIRc)" class="v20flvb2j"/><path fill="url(#ivlUagb)" class="v20flvb2j"/><path fill="url(#isHOZIM)" class="v20flvb2j"/><path fill="url(#ighSP8c)" class="v20flvb2j"/><path fill="url(#i7os8Tq)" class="v20flvb2j"/><path fill="url(#i1ryfob)" class="wto9l9a4f"/><path fill="url(#io8R0nc)" class="wto9l9a4f"/><path fill="url(#iupWyyd)" class="wto9l9a4f"/><path fill="url(#irAwi8d)" class="wto9l9a4f"/><path fill="url(#iW1Iv5t)" class="wto9l9a4f"/><path fill="url(#inh7lSc)" class="wto9l9a4f"/><path fill="url(#i8JJXrd)" class="wto9l9a4f"/><path fill="url(#imuAEBe)" class="wto9l9a4f"/><path fill="url(#iSqBlke)" class="wto9l9a4f"/><g filter="url(#ieXgleR)"><path fill="url(#iqPrsTK)" class="x_mri4gas"/></g><rect fill="url(#iR54Amd)" class="iuxb-78iw"/><path fill="url(#iowh0VF)" class="cnra-b9fz"/><path fill="url(#iML6fpb)" class="cnra-b9fz"/><path fill="url(#il7hV8c)" class="cnra-b9fz"/><path fill="url(#i0RWDxe)" class="cnra-b9fz"/><path fill="url(#iIo2zHb)" class="cnra-b9fz"/><g filter="url(#iD0Stee)"><path class="p_o6dfb9w"/></g><g filter="url(#iCOCjsd)"><path class="mvnp_pgek"/><path fill="url(#inwDYNd)" class="xcqgndb6i"/><path fill="url(#itCyPfb)" class="xcqgndb6i"/><path fill="url(#i1XNMAc)" class="xcqgndb6i"/></g><path fill="url(#i1mqNGb)" class="xcqgndb6i"/><path stroke="url(#ivtktwc)" class="o5icwosnl"/><g filter="url(#iAtni9c)"><path class="g0vudnb0k"/></g><g filter="url(#iQ5U17c)"><path class="zj7lbebqq"/></g><path class="d4zidbblk"/><path fill="url(#irVN0Gd)" class="t-ktlac1b"/><path class="ika6d7bkd"/><g filter="url(#irGGK0b)"><path class="h_6ff8bxv"/><path fill="url(#i3tZITd)" class="x_40w6btz"/></g><g filter="url(#itRJh5b)"><path fill="url(#iLck86q)" class="x9izhgbdw"/></g><path class="rsx-ctbax"/><path fill="url(#iYZBl7j)" class="jd0-bebnt"/><path class="dpb_v5byd"/><g filter="url(#iqWuULc)"><path fill="url(#iRL5dac)" class="zavl09b9d"/></g><g filter="url(#i17PyHb)"><ellipse transform="rotate(-27.914 13.335 14.533)" class="x2c9x2qad"/><ellipse fill="url(#ifvQyNc)" transform="rotate(-27.914 13.335 14.533)" class="inpos_bqx"/></g><g filter="url(#iTm9Jqb)"><path stroke="url(#idGljHG)" class="t9ptdgkkz"/></g><g filter="url(#imrD4rl)"><path stroke="url(#iM74HMe)" class="fo7hckbjn"/></g><path fill="url(#i2QzoZV)" class="ggskh2bzm"/><path fill="url(#i2vOWDd)" class="ggskh2bzm"/><path fill="url(#i4Z432d)" class="dw85flb0t"/><path fill="url(#i3nxMBb)" class="dw85flb0t"/><path fill="url(#i4Wqgqq)" class="r_9_ioa3h"/><path fill="url(#iRneNPQ)" class="r_9_ioa3h"/><path fill="url(#id2DEKf)" class="eim_mrbrv"/><path fill="url(#i1XP0UM)" class="eim_mrbrv"/><path class="ku49b-vhj"/><path stroke="url(#i51hlve)" class="djebsbcjo"/><path stroke="url(#i1aFbGc)" class="djebsbcjo"/><path stroke="url(#itsaBkb)" class="djebsbcjo"/><path stroke="url(#iHLLHMc)" class="w930jqbym"/><path stroke="url(#iWSDh8d)" class="w930jqbym"/><path stroke="url(#ihu6wOc)" class="w930jqbym"/><path class="qvv7abcya"/><path stroke="url(#iffKTvb)" class="odw-ccxrl"/><path stroke="url(#i40gqKc)" class="odw-ccxrl"/><path stroke="url(#iTHEkfI)" class="odw-ccxrl"/><path stroke="url(#is3o6Ae)" class="lc0lwfbjp"/><path stroke="url(#iNJWaIe)" class="lc0lwfbjp"/><path stroke="url(#iiCywtb)" class="lc0lwfbjp"/><path stroke="url(#iVpEied)" class="zw6cmm23y"/><path class="u8isk7i_t"/><path stroke="url(#iWADMid)" class="zw6cmm23y"/><path stroke="url(#iR1m3gl)" class="zw6cmm23y"/><path stroke="url(#iHxEwAc)" class="zw6cmm23y"/><path stroke="url(#i9rKsIc)" class="abd3-ibar"/><path stroke="url(#ivYPo2q)" class="abd3-ibar"/><path stroke="url(#izkjZie)" class="abd3-ibar"/><path class="ccza6hbch"/><path stroke="url(#ilqQnze)" class="hockzyb4d"/><path stroke="url(#iWDKx4M)" class="hockzyb4d"/><path stroke="url(#iDxJFhb)" class="lgc2wbcpd"/><path stroke="url(#i73gwKd)" class="lgc2wbcpd"/><path stroke="url(#iLwuUHe)" class="lgc2wbcpd"/><path fill="url(#ip6NOWc)" class="eim_mrbrv"/><path fill="url(#idIjZGc)" class="r_9_ioa3h"/><g filter="url(#i8m7V4b)"><path fill="url(#iOz6e2d)" class="rl4irpj3j"/></g><g filter="url(#ipTxhcb)"><path stroke="url(#ipBmWWm)" class="id0lipbed"/></g><defs><radialGradient id="iZjoYCO" cx="0" cy="0" r="1" gradientTransform="matrix(1.89764 0 0 3.32088 9.051 15.374)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ifhzZcb" cx="0" cy="0" r="1" gradientTransform="matrix(.89397 -.65095 .74297 1.02034 21.546 15.088)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="it2ljAc" cx="0" cy="0" r="1" gradientTransform="matrix(.88808 -1.63343 .95605 .5198 21.099 16.262)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ivubI4b" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -8.12 33.395)scale(.39452 .50858)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iDA47ic" cx="0" cy="0" r="1" gradientTransform="rotate(106.579 6.006 10.367)scale(4.27132 5.24326)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ynwn_jvcf"/><stop offset="1" class="dinze7bnd"/></radialGradient><radialGradient id="iY4x29d" cx="0" cy="0" r="1" gradientTransform="matrix(-.34376 2.1875 -3.99586 -.62795 17.813 5.507)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="ko0o1_b8c"/><stop offset="1" class="pvukj8myk"/></radialGradient><radialGradient id="iPWfIRc" cx="0" cy="0" r="1" gradientTransform="rotate(49.591 -3.334 15.412)scale(1.51852 3.40245)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="ugzll41et"/><stop offset="1" class="e_5ge1lqa"/></radialGradient><radialGradient id="isHOZIM" cx="0" cy="0" r="1" gradientTransform="matrix(6.4157 -4.5625 6.3081 8.87031 15.99 13.194)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="z1wn--b1i"/><stop offset=".918" class="p0khwib2k"/></radialGradient><radialGradient id="ighSP8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71926 -1.98672 2.9901 -2.58755 11.389 13.36)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="fg6kre1tq"/><stop offset=".722" class="qii05trgv"/></radialGradient><radialGradient id="i7os8Tq" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 -2.26563 .80844 -.0223 11.125 11.46)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="uknzep49t"/><stop offset="1" class="h34c9lb5f"/></radialGradient><radialGradient id="io8R0nc" cx="0" cy="0" r="1" gradientTransform="matrix(8.8125 0 0 9.43494 11 29.99)" gradientUnits="userSpaceOnUse"><stop class="q920b5bgt"/><stop offset="1" class="hmv6xsb8e"/></radialGradient><radialGradient id="iupWyyd" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 -8.62501 6.82131 4.1521 23.375 24.35)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="bawjzlb6r"/><stop offset="1" class="ati7d-krq"/></radialGradient><radialGradient id="irAwi8d" cx="0" cy="0" r="1" gradientTransform="matrix(3 0 0 4.4849 7.5 29.99)" gradientUnits="userSpaceOnUse"><stop class="qe_-3ab1e"/><stop offset="1" class="chsdmobsg"/></radialGradient><radialGradient id="iW1Iv5t" cx="0" cy="0" r="1" gradientTransform="matrix(.87505 5.5 -7.00176 1.11398 15.126 19.538)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gwwxrtb_v"/><stop offset="1" class="ssq48xbfd"/></radialGradient><radialGradient id="inh7lSc" cx="0" cy="0" r="1" gradientTransform="rotate(118.413 2.335 6.065)scale(1.08366 3.24985)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="zpk636z_v"/><stop offset="1" class="mtfxop-pk"/></radialGradient><radialGradient id="i8JJXrd" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 0 0 28.1734 1.625 13.788)" gradientUnits="userSpaceOnUse"><stop class="sg9fyvxai"/><stop offset="1" class="r0adxvbzx"/></radialGradient><radialGradient id="imuAEBe" cx="0" cy="0" r="1" gradientTransform="matrix(7.00002 10.68753 -3.8615 2.52917 25.625 5.913)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="t4nmlm7ht"/><stop offset="1" class="q4q53m76f"/></radialGradient><radialGradient id="iSqBlke" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 .84375 -2.45037 1.58819 23.657 6.476)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="ubeq2y34d"/><stop offset="1" class="r7flkhbpm"/></radialGradient><radialGradient id="iqPrsTK" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.593)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="xli568bjl"/><stop offset="1" class="dvyuy-plf"/></radialGradient><radialGradient id="iR54Amd" cx="0" cy="0" r="1" gradientTransform="rotate(-129.643 14.383 8.104)scale(3.73397 4.5453)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="zkbq2obgs"/><stop offset="1" class="b621vv9ir"/></radialGradient><radialGradient id="iowh0VF" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.098 -8.21429 0 19.26 10.228)" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="x2e45tbep"/></radialGradient><radialGradient id="il7hV8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.11461 9.89535 -11.34384 -.13139 16.585 12.979)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="h2gb-kbck"/><stop offset=".945" class="jcypb8b9t"/></radialGradient><radialGradient id="i0RWDxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41342 1.7396 0 18.527 14)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iIo2zHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.50403 1.87039 0 13.599 13.963)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="irVN0Gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .97664 -1.15561 0 18.347 14.997)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i3tZITd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25073 -.3231 .44483 -.3452 18.1 14.727)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYZBl7j" cx="0" cy="0" r="1" gradientTransform="matrix(0 .97669 -1.15567 0 13.629 14.997)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ifvQyNc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.98 .88)scale(.53422 .64216)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i2QzoZV" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="dp3nzmbzl"/><stop offset="1" class="wkrt2mblo"/></radialGradient><radialGradient id="i2vOWDd" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="i0f64nbug"/><stop offset="1" class="ucmtgi-2a"/></radialGradient><radialGradient id="i4Z432d" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 11.276 6.464)scale(2.64024 1.85707)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="xr5reebcs"/><stop offset="1" class="z9wcvylbn"/></radialGradient><radialGradient id="i3nxMBb" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.402 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="zi5l5kj0o"/><stop offset="1" class="mcuv6-nuk"/></radialGradient><radialGradient id="i4Wqgqq" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="fhunrr5ci"/><stop offset="1" class="as1blab4r"/></radialGradient><radialGradient id="iRneNPQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.078 2.829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="kwxb4ppbb"/><stop offset="1" class="hj20s6zvr"/></radialGradient><radialGradient id="id2DEKf" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.46 4.389)" gradientUnits="userSpaceOnUse"><stop class="x278nyb7a"/><stop offset=".469" class="bakx-_beg"/></radialGradient><radialGradient id="i1XP0UM" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="nc8kb9b6x"/><stop offset="1" class="xn68z7b1j"/></radialGradient><radialGradient id="i51hlve" cx="0" cy="0" r="1" gradientTransform="rotate(-107.313 7.85 -2.96)scale(1.33912 9.90691)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="itsaBkb" cx="0" cy="0" r="1" gradientTransform="rotate(45.373 5.591 13.928)scale(4.51976 4.41679)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="ihu6wOc" cx="0" cy="0" r="1" gradientTransform="rotate(96.905 7.712 9.344)scale(.37774 1.72952)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="iffKTvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.20247 -1.22554 7.88755 -1.30309 14.119 4.127)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iTHEkfI" cx="0" cy="0" r="1" gradientTransform="matrix(2.1943 3.64127 -3.57342 2.15341 13.307 1.077)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="iiCywtb" cx="0" cy="0" r="1" gradientTransform="rotate(90.318 6.676 10.203)scale(.52757 2.91495)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="iVpEied" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 -.90625 8.05091 -1.87395 13.97 4.444)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iWADMid" cx="0" cy="0" r="1" gradientTransform="matrix(-.04687 -.85937 7.6275 -.41603 14.001 4.552)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iHxEwAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89062 2.59375 -2.74078 1.9978 13.251 2.584)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="izkjZie" cx="0" cy="0" r="1" gradientTransform="matrix(.03906 .35156 -1.87014 .2078 17.485 4.686)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="ilqQnze" cx="0" cy="0" r="1" gradientTransform="matrix(-.16967 -1.41407 6.69427 -.80322 13.556 6.114)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iLwuUHe" cx="0" cy="0" r="1" gradientTransform="matrix(.03693 .64802 -1.4536 .08285 17.954 6.087)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="ip6NOWc" cx="0" cy="0" r="1" gradientTransform="rotate(104.241 9.588 9.809)scale(4.3577 15.5483)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="bfp_ecc-c"/><stop offset=".936" class="d9wzjmbdf"/></radialGradient><radialGradient id="idIjZGc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="a7d-k3bmr"/><stop offset="1" class="q3wz7tzyo"/></radialGradient><radialGradient id="iOz6e2d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53124 -8.125 5.12798 -2.85982 9.094 24.881)" gradientUnits="userSpaceOnUse"><stop class="x034jqb5d"/><stop offset="1" class="rpjijqwhi"/></radialGradient><linearGradient id="iIojTCb" x1="10.856" x2="10.164" y1="15.675" y2="15.675" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iqQJZRb" x1="22.319" x2="21.433" y1="14.194" y2="16.936" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="ivlUagb" x1="9.177" x2="11.75" y1="13.007" y2="12.569" gradientUnits="userSpaceOnUse"><stop offset=".026" class="c15gytbkr"/><stop offset="1" class="x52mdu0xg"/></linearGradient><linearGradient id="i1ryfob" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="b9v5e-b3e"/><stop offset="1" class="t_qwphcjx"/></linearGradient><linearGradient id="iML6fpb" x1="10.156" x2="12.656" y1="18.71" y2="18.384" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="inwDYNd" x1="15.056" x2="16.071" y1="16.508" y2="16.508" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="itCyPfb" x1="17.005" x2="15.896" y1="16.857" y2="16.841" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="i1XNMAc" x1="16.201" x2="16.201" y1="17.66" y2="17.04" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i1mqNGb" x1="16.127" x2="16.127" y1="17.705" y2="17.524" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="ivtktwc" x1="15.223" x2="15.682" y1="19.475" y2="18.569" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iLck86q" x1="19.188" x2="18.849" y1="14.695" y2="14.904" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRL5dac" x1="14.433" x2="14.094" y1="14.695" y2="14.904" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idGljHG" x1="19.205" x2="18.75" y1="12.381" y2="11.453" gradientUnits="userSpaceOnUse"><stop class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient><linearGradient id="iM74HMe" x1="13.603" x2="12.676" y1="12.355" y2="11.75" gradientUnits="userSpaceOnUse"><stop offset=".456" class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient><linearGradient id="i1aFbGc" x1="10.522" x2="12.654" y1="3.629" y2="2.265" gradientUnits="userSpaceOnUse"><stop offset=".249" class="la4rvxbid"/><stop offset="1" class="j0gi-81kw"/></linearGradient><linearGradient id="iHLLHMc" x1="18.298" x2="21.642" y1="2.397" y2="3.186" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="iWSDh8d" x1="17.251" x2="18.704" y1="2.444" y2="2.588" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="i40gqKc" x1="12.267" x2="14.049" y1="3.897" y2="3.055" gradientUnits="userSpaceOnUse"><stop offset=".224" class="xw2qhwj5i"/><stop offset="1" class="qg4fklbdo"/></linearGradient><linearGradient id="is3o6Ae" x1="17.183" x2="20.001" y1="3.104" y2="3.444" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="iNJWaIe" x1="16.173" x2="17.798" y1="3.49" y2="3.297" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="iR1m3gl" x1="12.228" x2="13.705" y1="4.523" y2="3.638" gradientUnits="userSpaceOnUse"><stop offset=".249" class="qc6cxsufz"/><stop offset="1" class="qg4fklbdo"/></linearGradient><linearGradient id="i9rKsIc" x1="17.421" x2="19.358" y1="4.093" y2="4.487" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="ivYPo2q" x1="16.298" x2="17.789" y1="4.834" y2="3.798" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="iWDKx4M" x1="11.892" x2="13.626" y1="5.787" y2="5.254" gradientUnits="userSpaceOnUse"><stop offset=".249" class="la4rvxbid"/><stop offset="1" class="j0gi-81kw"/></linearGradient><linearGradient id="iDxJFhb" x1="17.894" x2="19.781" y1="4.994" y2="5.191" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="i73gwKd" x1="16.831" x2="18.687" y1="6.36" y2="5.699" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="ipBmWWm" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="tuzqszfby"/><stop offset="1" class="ljv2-xbix"/></linearGradient><filter id="iYBDpBb" width="3.152" height="3.152" x="9.281" y="13.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".25"/></filter><filter id="ihttspc" width="3.861" height="3.861" x="19.338" y="13.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3715"/></filter><filter id="iINOlCb" width="3.152" height="3.152" x="19.568" y="13.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".25"/></filter><filter id="imXmUnv" width="13.627" height="8.898" x="9.177" y="5.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.533333 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3715"/></filter><filter id="ieXgleR" width="15.688" height="8.156" x="9.357" y="22.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".375"/></filter><filter id="iD0Stee" width="3.403" height="4.399" x="14.03" y="14.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".375"/></filter><filter id="iCOCjsd" width="2.53" height="3.399" x="14.726" y="14.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".125"/></filter><filter id="iAtni9c" width="3.202" height="1.993" x="17.269" y="11.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3715"/></filter><filter id="iQ5U17c" width="3.202" height="1.993" x="11.702" y="11.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3715"/></filter><filter id="irGGK0b" width=".834" height=".737" x="17.561" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".05"/></filter><filter id="itRJh5b" width=".931" height=".955" x="18.477" y="14.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".1"/></filter><filter id="iqWuULc" width="1.034" height="1.092" x="13.674" y="14.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".1"/></filter><filter id="i17PyHb" width=".971" height=".745" x="12.85" y="14.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".05"/></filter><filter id="iTm9Jqb" width="3.5" height="1.966" x="17.036" y="11.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".25"/></filter><filter id="imrD4rl" width="3.584" height="2.028" x="11.392" y="11.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".25"/></filter><filter id="i8m7V4b" width="9.632" height="11.909" x="1.844" y="15.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".25"/></filter><filter id="ipTxhcb" width="4.094" height="4.656" x="7.923" y="22.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3715" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-ok" /></template>
<style>
.a7d-k3bmr {
  stop-color: var(--svg-color--f59522, #F59522);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.as1blab4r {
  stop-color: var(--svg-color--f4bc2d, #F4BC2D);
}

.ati7d-krq {
  stop-color: var(--svg-color--298dff, #298DFF);
  stop-opacity: 0;
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b4ahfq94n {
  cx: 21.144px;
  cy: 15.374px;
  r: 1.076px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.b621vv9ir {
  stop-color: var(--svg-color--bd6e02, #BD6E02);
}

.b9v5e-b3e {
  stop-color: var(--svg-color--3ca8ff, #3CA8FF);
}

.bakx-_beg {
  stop-color: var(--svg-color--ffc53a, #FFC53A);
}

.bawjzlb6r {
  stop-color: var(--svg-color--298dff, #298DFF);
}

.bcebw6bhr {
  stop-color: var(--svg-color--eca107, #ECA107);
}

.bf57i6byh {
  stop-color: var(--svg-color--ffd843, #FFD843);
  stop-opacity: 0;
}

.bfp_ecc-c {
  stop-color: var(--svg-color--eb8b05, #EB8B05);
  stop-opacity: 0;
}

.c15gytbkr {
  stop-color: var(--svg-color--b37f43, #B37F43);
}

.c5ffxnbso {
  stop-color: var(--svg-color--ffdd45, #FFDD45);
}

.ccza6hbch {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.chsdmobsg {
  stop-color: var(--svg-color--499efa, #499EFA);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnra-b9fz {
  d: path("m10.476 14.711l.053.002s-.058-.922-.116-1.557c0-.288.116-.634.348-.807l.174-.173c.29-.231.406-.577.406-.923v-.923c0-.288.174-.519.464-.577c.696-.173 2.146-.461 4.234-.461s3.538.288 4.234.461c.233.058.465.289.465.577v.923c0 .346.174.692.406.923c.542.38.509.59.464 1.038c-.059.576-.117 1.557-.117 1.557h.02l-.287 4.28c-.174 1.914-1.678 3.247-3.472 3.247h-3.471c-1.852 0-3.299-1.333-3.472-3.247z");
}

.cuodmbbdm {
  cx: 21.144px;
  cy: 15.374px;
  r: 1.076px;
}

.d4zidbblk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.573 13.827a1.51 1.51 0 0 1 1.464 1.145a.296.296 0 0 1-.29.368h-2.411a.25.25 0 0 1-.246-.294a1.51 1.51 0 0 1 1.483-1.219");
}

.d9wzjmbdf {
  stop-color: var(--svg-color--eb8b05, #EB8B05);
}

.dinze7bnd {
  stop-color: var(--svg-color--ffd331, #FFD331);
  stop-opacity: 0;
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.dp3nzmbzl {
  stop-color: var(--svg-color--2d99fd, #2D99FD);
}

.dpb_v5byd {
  fill: var(--svg-color--000, #000);
  d: path("M14.18 15.086a.55.55 0 0 0-.553-.553a.55.55 0 0 0-.492.807h.978a.55.55 0 0 0 .066-.254");
}

.dvyuy-plf {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
  stop-opacity: 0;
}

.dw85flb0t {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.156-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.e_5ge1lqa {
  stop-color: var(--svg-color--d48e1e, #D48E1E);
  stop-opacity: 0;
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.fg6kre1tq {
  stop-color: var(--svg-color--c35b0b, #C35B0B);
}

.fhunrr5ci {
  stop-color: var(--svg-color--ffd234, #FFD234);
}

.fitoduswx {
  fill: var(--svg-color--f0991f, #F0991F);
  d: path("m21.202 8.37l.463.23c.813.404 1.277 1.326 1.103 2.307l-.638 3.287c-.057.34-.282.568-.619.577h-.02s.058-.98.117-1.557c.047-.469-.035-.612-.465-1.038c-.232-.231-.405-.577-.405-.923v-.923c0-.288-.232-.519-.465-.577c-.696-.173-2.146-.461-4.234-.461s-3.538.288-4.234.461a.56.56 0 0 0-.464.577v.923c0 .346-.116.692-.406.923l-.174.173c-.232.173-.348.519-.348.807c.058.634.116 1.557.116 1.557q-.027 0-.053-.002a.685.685 0 0 1-.643-.574l-.638-3.288c-.116-.923.348-1.845 1.16-2.25l.464-.23c.29-.173.58-.403.87-.634l1.044-1.096c.638-.577 1.566-.75 2.378-.346a3.2 3.2 0 0 0 1.798 0c.87-.288 1.856-.058 2.552.577l.87.865c.233.288.523.461.87.634");
}

.fo7hckbjn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M12.142 12.837c.354-.313 1.126-.642 2.084-.49");
}

.ft5dv1b6b {
  fill: none;
}

.g0vudnb0k {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m20.013 12.433l-.002-.001l-.002-.002l-.004-.004l-.013-.01a2 2 0 0 0-.168-.117a3 3 0 0 0-.454-.227a3.06 3.06 0 0 0-1.614-.171a.577.577 0 0 0 .18 1.14a1.9 1.9 0 0 1 1.01.104a1.7 1.7 0 0 1 .325.172l.008.007a.577.577 0 0 0 .734-.891");
}

.ggskh2bzm {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.156 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gwwxrtb_v {
  stop-color: var(--svg-color--1d5894, #1D5894);
}

.h_6ff8bxv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.278 14.325c.069.092-.075.204-.238.326c-.164.122-.285.208-.354.116c-.068-.092.008-.265.172-.387c.163-.123.351-.147.42-.055");
}

.h2gb-kbck {
  stop-color: var(--svg-color--fa9b3b, #FA9B3B);
  stop-opacity: 0;
}

.h34c9lb5f {
  stop-color: var(--svg-color--ffa92a, #FFA92A);
  stop-opacity: 0;
}

.hd06z0qdg {
  stop-color: var(--svg-color--d5a136, #D5A136);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hj20s6zvr {
  stop-color: var(--svg-color--d1a345, #D1A345);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hmv6xsb8e {
  stop-color: var(--svg-color--2691ff, #2691FF);
  stop-opacity: 0;
}

.hockzyb4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hsn8dgk7l {
  stop-color: var(--svg-color--eca107, #ECA107);
  stop-opacity: 0;
}

.i0f64nbug {
  stop-color: var(--svg-color--49abff, #49ABFF);
}

.id0lipbed {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.ika6d7bkd {
  fill: var(--svg-color--000, #000);
  d: path("M17.796 15.086a.55.55 0 0 1 .553-.553a.55.55 0 0 1 .491.807h-.978a.5.5 0 0 1-.066-.254");
}

.inpos_bqx {
  cx: 13.335px;
  cy: 14.533px;
  rx: 0.421px;
  ry: 0.213px;
}

.itvn9lbuv {
  stop-color: var(--svg-color--ffc53a, #FFC53A);
  stop-opacity: 0;
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.j0gi-81kw {
  stop-color: var(--svg-color--fbc831, #FBC831);
  stop-opacity: 0;
}

.jcypb8b9t {
  stop-color: var(--svg-color--cd7f3f, #CD7F3F);
}

.jd0-bebnt {
  d: path("M13.627 14.12a.965.965 0 0 0-.93 1.22h1.864a1 1 0 0 0 .035-.254a.97.97 0 0 0-.97-.965");
}

.jh81_obba {
  stop-color: var(--svg-color--d29e3b, #D29E3B);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.ko0o1_b8c {
  stop-color: var(--svg-color--cf8228, #CF8228);
}

.ku49b-vhj {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.kwxb4ppbb {
  stop-color: var(--svg-color--d1a345, #D1A345);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.la4rvxbid {
  stop-color: var(--svg-color--fbc831, #FBC831);
}

.lc0lwfbjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.608c-.43-.11-2.375-.477-3.255-.266");
}

.lfs2u60yo {
  cx: 10.856px;
  cy: 15.374px;
  r: 1.805px;
}

.lgc2wbcpd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljv2-xbix {
  stop-color: var(--svg-color--3b95f9, #3B95F9);
  stop-opacity: 0;
}

.m5wur4bob {
  stop-color: var(--svg-color--d29e3b, #D29E3B);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mcuv6-nuk {
  stop-color: var(--svg-color--4298d4, #4298D4);
  stop-opacity: 0;
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mtfxop-pk {
  stop-color: var(--svg-color--43bbff, #43BBFF);
  stop-opacity: 0;
}

.mvnp_pgek {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.577 15.066l-.574 1.837a.583.583 0 0 0 .563.757h.85c.398 0 .68-.384.563-.757l-.575-1.837c-.123-.408-.698-.408-.827 0");
}

.nc8kb9b6x {
  stop-color: var(--svg-color--d4ab3c, #D4AB3C);
}

.o5icwosnl {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.516 18.36v-.001a.215.215 0 0 0-.257.044a.2.2 0 0 0-.022.255a2.1 2.1 0 0 0 1.754.936c.736 0 1.382-.375 1.753-.937a.2.2 0 0 0-.022-.256a.22.22 0 0 0-.256-.042c-.427.222-.93.35-1.475.35c-.541 0-1.05-.128-1.475-.35Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odw-ccxrl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.p_o6dfb9w {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.693 15.242l-.887 1.838c-.11.378.154.756.528.756h.797c.374 0 .637-.384.527-.756l-.538-1.838c-.116-.407-.306-.407-.427 0");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p0khwib2k {
  stop-color: var(--svg-color--795917, #795917);
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pvukj8myk {
  stop-color: var(--svg-color--e5921a, #E5921A);
  stop-opacity: 0;
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q3wz7tzyo {
  stop-color: var(--svg-color--f59522, #F59522);
  stop-opacity: 0;
}

.q4q53m76f {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
  stop-opacity: 0;
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.q920b5bgt {
  stop-color: var(--svg-color--2691ff, #2691FF);
}

.qc6cxsufz {
  stop-color: var(--svg-color--fdcd33, #FDCD33);
}

.qe_-3ab1e {
  stop-color: var(--svg-color--499efa, #499EFA);
}

.qg4fklbdo {
  stop-color: var(--svg-color--fdcd33, #FDCD33);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qii05trgv {
  stop-color: var(--svg-color--c35b0b, #C35B0B);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qvv7abcya {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r0adxvbzx {
  stop-color: var(--svg-color--54acf3, #54ACF3);
  stop-opacity: 0;
}

.r7flkhbpm {
  stop-color: var(--svg-color--419ae2, #419AE2);
  stop-opacity: 0;
}

.rd2dtjb_d {
  stop-color: var(--svg-color--cf715d, #CF715D);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rl4irpj3j {
  d: path("M7.788 26.79L2.344 16.695l4.594-.812l4.038 7.877c-1.35 2.025-2.688 2.865-3.188 3.032");
}

.rpjijqwhi {
  stop-color: var(--svg-color--2882ff, #2882FF);
  stop-opacity: 0;
}

.rsx-ctbax {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.403 13.827a1.51 1.51 0 0 0-1.465 1.145a.296.296 0 0 0 .29.368h2.412c.153 0 .276-.14.245-.294a1.515 1.515 0 0 0-1.482-1.22");
}

.rv76ab9nb {
  cx: 10.856px;
  cy: 15.374px;
  r: 1.076px;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sg9fyvxai {
  stop-color: var(--svg-color--54acf3, #54ACF3);
}

.ssq48xbfd {
  stop-color: var(--svg-color--1d5894, #1D5894);
  stop-opacity: 0;
}

.t_qwphcjx {
  stop-color: var(--svg-color--2a99ff, #2A99FF);
}

.t-ktlac1b {
  d: path("M18.349 14.12a.965.965 0 0 1 .93 1.22h-1.864a.97.97 0 0 1 .934-1.22");
}

.t4nmlm7ht {
  stop-color: var(--svg-color--46c5ff, #46C5FF);
}

.t9ptdgkkz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M17.786 12.276c.465-.081 1.372-.058 2 .43");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tuzqszfby {
  stop-color: var(--svg-color--3a95fa, #3A95FA);
}

.u8isk7i_t {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.ubeq2y34d {
  stop-color: var(--svg-color--419ae2, #419AE2);
}

.ucmtgi-2a {
  stop-color: var(--svg-color--49abff, #49ABFF);
  stop-opacity: 0;
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ugw3yibbz {
  stop-color: var(--svg-color--cf715d, #CF715D);
  stop-opacity: 0;
}

.ugzll41et {
  stop-color: var(--svg-color--bb8939, #BB8939);
}

.uknzep49t {
  stop-color: var(--svg-color--ffa92a, #FFA92A);
}

.uoe471bev {
  cx: 21.144px;
  cy: 15.374px;
  r: 1.805px;
}

.v20flvb2j {
  d: path("m21.202 8.37l.463.23c.813.404 1.277 1.326 1.103 2.307l-.638 3.287c-.057.34-.282.568-.619.577h-.02s.058-.98.117-1.557c.047-.469-.035-.612-.465-1.038c-.232-.231-.405-.577-.405-.923v-.923c0-.288-.232-.519-.465-.577c-.696-.173-2.146-.461-4.234-.461s-3.538.288-4.234.461a.56.56 0 0 0-.464.577v.923c0 .346-.116.692-.406.923l-.174.173c-.232.173-.348.519-.348.807c.058.634.116 1.557.116 1.557q-.027 0-.053-.002a.685.685 0 0 1-.643-.574l-.638-3.288c-.116-.923.348-1.845 1.16-2.25l.464-.23c.29-.173.58-.403.87-.634l1.044-1.096c.638-.577 1.566-.75 2.378-.346a3.2 3.2 0 0 0 1.798 0c.87-.288 1.856-.058 2.552.577l.87.865c.233.288.523.461.87.634");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.w9m3_8gbd {
  stop-color: var(--svg-color--d5a136, #D5A136);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wkrt2mblo {
  stop-color: var(--svg-color--1284d5, #1284D5);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wto9l9a4f {
  d: path("M7.312 5.365c-.203-.057-.676-.154-.945-.086c-.336.086-.594.329-.812.688c-.175.287-1.47 2.48-2.094 3.539c-.563.823-1.625 3.088-1.375 5.563c.1 1.662.781 3.338 1.11 3.968l4.132 7.855c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.022h17.828c0-.743-.164-1.493-.322-2.022a1.43 1.43 0 0 1 .08-1.076l4.133-7.855c.328-.63 1.01-2.306 1.11-3.968c.25-2.476-.813-4.74-1.376-5.563a915 915 0 0 0-2.094-3.54c-.218-.358-.476-.6-.812-.687c-.269-.068-.742.03-.945.086L21.5 7.53c-.352.415-.19.967-.055 1.18l2.075 3.512a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a24 24 0 0 0-.95-.415a3.4 3.4 0 0 1-.944.285v.006a2.307 2.307 0 1 1-4.615 0v-.017a3.5 3.5 0 0 1-.846-.254a15 15 0 0 0-1 .395a.37.37 0 0 1-.492-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382l2.075-3.512c.135-.213.297-.765-.055-1.18z");
}

.x_40w6btz {
  d: path("M18.278 14.325c.069.092-.075.204-.238.326c-.164.122-.285.208-.354.116c-.068-.092.008-.265.172-.387c.163-.123.351-.147.42-.055");
}

.x_mri4gas {
  d: path("M23.873 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.x034jqb5d {
  stop-color: var(--svg-color--2882ff, #2882FF);
}

.x278nyb7a {
  stop-color: var(--svg-color--ffe23e, #FFE23E);
}

.x2c9x2qad {
  cx: 13.335px;
  cy: 14.533px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.421px;
  ry: 0.213px;
}

.x2e45tbep {
  stop-color: var(--svg-color--ffac1b, #FFAC1B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x52mdu0xg {
  stop-color: var(--svg-color--b37f43, #B37F43);
  stop-opacity: 0;
}

.x9izhgbdw {
  d: path("M19.208 14.959a.9.9 0 0 0-.25-.5l-.28.308l.126.246z");
}

.xcqgndb6i {
  d: path("m15.577 15.066l-.574 1.837a.583.583 0 0 0 .563.757h.85c.398 0 .68-.384.563-.757l-.575-1.837c-.123-.408-.698-.408-.827 0");
}

.xli568bjl {
  stop-color: var(--svg-color--47b8ff, #47B8FF);
}

.xn68z7b1j {
  stop-color: var(--svg-color--d4ab3c, #D4AB3C);
  stop-opacity: 0;
}

.xr5reebcs {
  stop-color: var(--svg-color--4bb4ff, #4BB4FF);
}

.xw2qhwj5i {
  stop-color: var(--svg-color--fbca32, #FBCA32);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ynwn_jvcf {
  stop-color: var(--svg-color--ffd331, #FFD331);
}

.z1wn--b1i {
  stop-color: var(--svg-color--cc8720, #CC8720);
  stop-opacity: 0;
}

.z9wcvylbn {
  stop-color: var(--svg-color--347bc6, #347BC6);
}

.zavl09b9d {
  d: path("M14.508 14.972c0-.311-.253-.52-.322-.582l-.312.301l.192.39z");
}

.zi5l5kj0o {
  stop-color: var(--svg-color--4298d4, #4298D4);
}

.zj7lbebqq {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m11.91 12.433l.002-.001l.002-.002l.005-.004l.012-.01a2 2 0 0 1 .168-.117a3 3 0 0 1 .454-.227a3.06 3.06 0 0 1 1.614-.171a.577.577 0 0 1-.18 1.14a1.9 1.9 0 0 0-1.01.104a1.7 1.7 0 0 0-.325.172l-.008.007a.577.577 0 0 1-.734-.89");
}

.zkbq2obgs {
  stop-color: var(--svg-color--ffcc3e, #FFCC3E);
}

.zpk636z_v {
  stop-color: var(--svg-color--43bbff, #43BBFF);
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

</style>
