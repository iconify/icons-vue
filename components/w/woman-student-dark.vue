<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icuDXxy)"><path fill="url(#iYftlid)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#iZEZAmd)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#i3kzKad)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#i1iyLJc)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#idiI3jc)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#i6kiB9c)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#ingxItd)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#iuY6ODe)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#iLEhjPd)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#iWpKkiO)" clip-rule="evenodd" class="bhkjimlol"/><path fill="url(#imxPhVe)" clip-rule="evenodd" class="bhkjimlol"/></g><path class="wmomyrb5j"/><path fill="url(#ijUeoCe)" class="hr_-x2kag"/><path fill="url(#iBS4Mnd)" class="hr_-x2kag"/><path fill="url(#i1TIumb)" class="du__vt30i"/><path fill="url(#imZqZdc)" class="du__vt30i"/><path fill="url(#iTakUrb)" class="du__vt30i"/><path fill="url(#ikh36Lc)" class="du__vt30i"/><path fill="url(#iuqKtWD)" class="du__vt30i"/><path fill="url(#ii9olCd)" class="du__vt30i"/><g filter="url(#iz8o2Ui)"><path class="acbojubus"/></g><path fill="url(#i3cxt2d)" class="d9fobtbpp"/><path fill="url(#iz3pA5b)" class="wjo7a7bex"/><path fill="url(#iysxL0c)" class="wjo7a7bex"/><path fill="url(#isHlaEe)" class="pdqk7nbnd"/><path fill="url(#iWHBiUd)" class="pdqk7nbnd"/><g filter="url(#ijPkhWG)"><path stroke="url(#ivXirrc)" class="k3g357sye"/></g><path fill="url(#iz8vJxe)" class="anx9dbcfu"/><path fill="url(#i5w3R3c)" class="anx9dbcfu"/><path fill="url(#icbcdeb)" class="anx9dbcfu"/><path fill="url(#iMjBZEe)" class="anx9dbcfu"/><path fill="url(#ijGbAse)" class="anx9dbcfu"/><path fill="url(#ixGRssb)" class="zv6ta8bxw"/><path fill="url(#iVoILGE)" class="zv6ta8bxw"/><path fill="url(#ivD8nCB)" class="zv6ta8bxw"/><path fill="url(#iR8Fond)" class="p7efr3alc"/><path fill="url(#idbamQV)" class="p7efr3alc"/><g filter="url(#i5wa6Fc)"><path fill="url(#iGwBXPe)" class="xth2jjbyg"/><path fill="url(#iGwBXPe)" class="hsr2gdsok"/><path fill="url(#iGwBXPe)" class="dcw978b8o"/></g><g filter="url(#ix7k8Vd)"><path stroke="url(#iU6psue)" class="bsp52gmfy"/></g><g filter="url(#i2ARnmb)"><path fill="url(#iKRbwHc)" class="edtm2k4mn"/></g><g filter="url(#i9ev6Gb)"><path fill="url(#ivJMHad)" class="oskgvabkg"/><path fill="url(#ieKBa3c)" class="oskgvabkg"/></g><g filter="url(#iHUzJjd)"><path class="ttuv3t6wt"/><path fill="url(#iKneEld)" class="lp540jb3q"/></g><g filter="url(#i8uxVHd)"><path class="yra8txf4s"/><path fill="url(#iEdFIge)" class="ilsmeichs"/></g><g filter="url(#i1KbtYb)"><path fill="url(#i7tiQUd)" class="rpho_cb_u"/><path fill="url(#iEA1zAd)" class="rpho_cb_u"/><path fill="url(#iKeXSjb)" class="rpho_cb_u"/><path fill="url(#iOfX50G)" class="rpho_cb_u"/><path fill="url(#imQSJvc)" class="rpho_cb_u"/><path fill="url(#ibPR9mb)" class="rpho_cb_u"/><path fill="url(#i0CemJe)" class="rpho_cb_u"/></g><path fill="url(#iQDw3Fb)" class="rpho_cb_u"/><g filter="url(#ifejGkb)"><path class="bomryw3mx"/></g><g filter="url(#i0txoxc)"><path class="r_aboqbqw"/><path fill="url(#iJCZh7b)" class="r-t2w9rov"/><path fill="url(#i8rB4Qq)" class="r-t2w9rov"/><path fill="url(#iNXeKWn)" class="r-t2w9rov"/><path fill="url(#ikheEac)" class="r-t2w9rov"/></g><path fill="url(#iRx1pOc)" class="r-t2w9rov"/><path fill="url(#iRrUepb)" class="r-t2w9rov"/><path stroke="url(#i3O5QLe)" class="gtkm56isa"/><g filter="url(#i7557ze)"><path class="njptydi6j"/></g><g filter="url(#isMzhzb)"><path class="p2nuhtbve"/></g><g filter="url(#ivHj2iV)"><path class="voql45s9b"/></g><g filter="url(#iY3CSGe)"><path clip-rule="evenodd" class="ym1rlhfdr"/></g><path class="z-6q60xzi"/><path fill="url(#igl7dkH)" class="qyczxj7-g"/><path class="x20-z4bup"/><g filter="url(#ihE09Dd)"><path class="nae89ybnj"/><path fill="url(#iUfZPUd)" class="i9y-qb10f"/></g><g filter="url(#i6HiDMb)"><path fill="url(#iTNhLDb)" class="ahuingozp"/></g><path class="zy49r70sz"/><path fill="url(#iW77a1c)" class="ovz5vk44l"/><path class="jnje24bmk"/><g filter="url(#iM8oKNW)"><path fill="url(#ibwlxke)" class="s_yujzuhc"/></g><g filter="url(#iCfbg9d)"><ellipse transform="rotate(-27.914 13.847 10.226)" class="zk3jj_8bc"/><ellipse fill="url(#iZfpjod)" transform="rotate(-27.914 13.847 10.226)" class="j2yc5acwm"/></g><g filter="url(#illDA1c)"><path class="sk-p0ogej"/></g><g filter="url(#iIFuyXc)"><path class="p1huxcp_c"/></g><g filter="url(#i55u4fC)"><path class="m5-fuljfc"/><path fill="url(#iupDwvd)" class="h1ploqb3t"/><path fill="url(#i0DRQSd)" class="h1ploqb3t"/></g><g filter="url(#iewe2Oc)"><path class="smcd2gbip"/><path fill="url(#iuATPwb)" class="g1dr-iwvk"/><path fill="url(#ifUI9Wc)" class="g1dr-iwvk"/></g><g filter="url(#iMAWlNd)"><path stroke="url(#iXVHkEe)" class="fk2lldbhl"/></g><g filter="url(#ip5c1Zb)"><path class="dpdvwyp-g"/></g><g filter="url(#itXygMd)"><path fill="url(#il4wune)" class="if_ny3kis"/><path fill="url(#idZr5dc)" class="if_ny3kis"/></g><path fill="url(#iEjGiYd)" class="bwhm58bkm"/><path fill="url(#iLLu1nb)" class="bwhm58bkm"/><path fill="url(#iPI472d)" class="bwhm58bkm"/><defs><radialGradient id="iZEZAmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.63322 4.78464 -5.97698 -.79102 16.105 13.578)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i3kzKad" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02565 2.04052 -2.68108 -3.97546 13.15 13.859)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i1iyLJc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.905 8.394)scale(2.25873 1.73439)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="idiI3jc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35449 2.2164 -1.56126 -.95412 11.813 9.057)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i6kiB9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.298 11.782)scale(3.10013 4.30346)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ingxItd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51269 1.5128 -2.11411 -2.11396 22.543 4.677)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iuY6ODe" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.434 6.761)scale(2.01509 4.20232)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iLEhjPd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.994 8.28)scale(3.04608 3.88025)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iWpKkiO" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 13.378 -3.898)scale(2.93888 2.32449)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="imxPhVe" cx="0" cy="0" r="1" gradientTransform="matrix(1.57832 .16556 -.26825 2.55734 9.976 10.021)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ijUeoCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.737 23.116)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iBS4Mnd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.143 21.46)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="i1TIumb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.443 21.35)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="imZqZdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.435 16.898)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iTakUrb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.018 15.554)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="ikh36Lc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.768 15.32)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="iuqKtWD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.435 23.616)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="ii9olCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.85937 -5.04205 0 16.435 15.32)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i3cxt2d" cx="0" cy="0" r="1" gradientTransform="rotate(-163.355 10.398 7.585)scale(1.58191 3.34381)" gradientUnits="userSpaceOnUse"><stop class="sqvts9xow"/><stop offset="1" class="pgbc5zcxn"/></radialGradient><radialGradient id="iysxL0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.01 11.67)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="isHlaEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.268 12.041)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iWHBiUd" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.93 12.433)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="i5w3R3c" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.33 8.559)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="icbcdeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.768 13.109)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="ijGbAse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.768 16.898)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="ixGRssb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.44 29.997)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iVoILGE" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.206 29.997)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iR8Fond" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.547 29.997)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="idbamQV" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.496 23.158)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="ivJMHad" cx="0" cy="0" r="1" gradientTransform="matrix(2.61153 -1.18706 1.44935 3.18857 20.66 11.414)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="ieKBa3c" cx="0" cy="0" r="1" gradientTransform="matrix(1.38051 .7738 -.21876 .3903 21.742 9.189)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iKneEld" cx="0" cy="0" r="1" gradientTransform="matrix(1.5842 -.11784 .09212 1.2384 21.03 11.07)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iEdFIge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2662 0 0 -.99888 11.592 10.953)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="i7tiQUd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.571 7.326)scale(7.51607 10.0601)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="iEA1zAd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1372 1.0188 -.70947 -1.4883 18.339 11.274)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iKeXSjb" cx="0" cy="0" r="1" gradientTransform="rotate(-72.838 18.932 -.825)scale(3.81805 4.84439)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iOfX50G" cx="0" cy="0" r="1" gradientTransform="matrix(-.56701 6.66474 -6.70043 -.57005 16.988 10.554)" gradientUnits="userSpaceOnUse"><stop offset=".63" class="t2yfqccvi"/><stop offset="1" class="wee83-4gn"/></radialGradient><radialGradient id="imQSJvc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.567 6.993)scale(7.38555 12.7156)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="ibPR9mb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2077 1.48218 0 18.837 9.95)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="i0CemJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37745 1.57865 0 14.242 9.71)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iQDw3Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34887 0 0 -6.76446 21.769 11.511)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iJCZh7b" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 13.542 -.775)scale(2.19721 .67716)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="ikheEac" cx="0" cy="0" r="1" gradientTransform="matrix(-.81775 0 0 -.22862 16.993 12.495)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iRrUepb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43868 .9877 -1.18707 -1.72907 16.817 11.871)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="igl7dkH" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85124 -1.35399 0 18.711 10.326)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUfZPUd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.786 .684)scale(.3969 .54644)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iW77a1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85124 -1.354 0 14.131 10.326)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZfpjod" cx="0" cy="0" r="1" gradientTransform="matrix(-.00812 -.51837 .6231 -.00976 13.83 10.556)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iupDwvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.32413 -2.89102 1.47897 .6774 10.483 8.1)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i0DRQSd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2642 -3.3728 5.51833 -2.06838 13.058 7.46)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="t7u3qkefj"/><stop offset=".93" class="w4h8bubsi"/></radialGradient><radialGradient id="iuATPwb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21644 4.6087 -7.53497 -3.62375 18.427 2.637)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ifUI9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 7.024 8.65)scale(1.45172 3.12329)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="il4wune" cx="0" cy="0" r="1" gradientTransform="matrix(-.6722 -3.65216 4.02251 -.74037 18.968 5.946)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="idZr5dc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02116 -7.18676 0 16.352 2.864)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iLLu1nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.174 2.397)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iPI472d" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.205 3.022)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="icuDXxy" width="16.011" height="16.511" x="8.541" y="1.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="iz8o2Ui" width="5.32" height="9.565" x="13.761" y="9.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".2"/></filter><filter id="ijPkhWG" width=".65" height="8.268" x="24.546" y="3.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".125"/></filter><filter id="i5wa6Fc" width="8.964" height="6.734" x="11.953" y="23.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".075"/></filter><filter id="ix7k8Vd" width="1.172" height="2.394" x="13.087" y="3.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".125"/></filter><filter id="i2ARnmb" width="3.527" height="3.376" x="9.815" y="9.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="i9ev6Gb" width="3.377" height="3.626" x="19.799" y="9.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="iHUzJjd" width="3.254" height="3.254" x="19.86" y="9.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".25"/></filter><filter id="i8uxVHd" width="2.754" height="2.754" x="10.147" y="9.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".125"/></filter><filter id="i1KbtYb" width="10.695" height="11.615" x="11.074" y="5.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="ifejGkb" width="2.97" height="3.814" x="14.766" y="9.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".25"/></filter><filter id="i0txoxc" width="2.47" height="3.314" x="15.186" y="10.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".125"/></filter><filter id="i7557ze" width="3.139" height="1.349" x="17.421" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="isMzhzb" width="3.139" height="1.349" x="12.283" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="ivHj2iV" width="2.564" height="1.135" x="12.425" y="7.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="iY3CSGe" width="2.564" height="1.135" x="18.11" y="7.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><filter id="ihE09Dd" width=".816" height=".721" x="17.946" y="9.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".05"/></filter><filter id="i6HiDMb" width=".915" height=".939" x="18.832" y="9.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".1"/></filter><filter id="iM8oKNW" width="1.015" height="1.072" x="14.17" y="9.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".1"/></filter><filter id="iCfbg9d" width=".948" height=".729" x="13.372" y="9.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".05"/></filter><filter id="illDA1c" width="2.343" height=".996" x="18.157" y="8.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".1"/></filter><filter id="iIFuyXc" width="2.343" height=".996" x="12.436" y="8.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".1"/></filter><filter id="i55u4fC" width="4.38" height="4.696" x="9.772" y="3.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".2"/></filter><filter id="iewe2Oc" width="9.174" height="6.043" x="13.109" y="2.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/><feGaussianBlur result="effect2_foregroundBlur_4002_1583" stdDeviation=".125"/></filter><filter id="iMAWlNd" width="1.172" height="2.394" x="13.087" y="3.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".1"/></filter><filter id="ip5c1Zb" width="7.171" height="3.965" x="15.598" y="4.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1583" stdDeviation=".5"/></filter><filter id="itXygMd" width="12.363" height="3.035" x="10.201" y="3.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1583"/></filter><linearGradient id="iYftlid" x1="21.347" x2="14.205" y1="3.656" y2="16.885" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iz3pA5b" x1="24.125" x2="25.311" y1="8.944" y2="8.944" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="ivXirrc" x1="25.371" x2="25.371" y1="3.71" y2="11.478" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iz8vJxe" x1="25.919" x2="23.6" y1="14.808" y2="14.808" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iMjBZEe" x1="23.719" x2="24.594" y1="14.488" y2="14.667" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="ivD8nCB" x1="9.35" x2="8.924" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iGwBXPe" x1="16.435" x2="16.435" y1="29.866" y2="23.433" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iU6psue" x1="13.387" x2="13.959" y1="4.448" y2="5.785" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iKRbwHc" x1="9.815" x2="12.92" y1="11.044" y2="11.044" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="i8rB4Qq" x1="15.436" x2="16.421" y1="12.35" y2="12.35" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iNXeKWn" x1="16.421" x2="16.421" y1="13.188" y2="12.548" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iRx1pOc" x1="16.503" x2="16.503" y1="13.161" y2="13.014" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="i3O5QLe" x1="15.304" x2="15.788" y1="14.668" y2="13.921" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iTNhLDb" x1="19.528" x2="19.198" y1="10.383" y2="10.586" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibwlxke" x1="14.912" x2="14.583" y1="10.383" y2="10.586" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXVHkEe" x1="13.387" x2="13.959" y1="4.448" y2="5.784" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iEjGiYd" x1="18.205" x2="16.924" y1="3.96" y2="-.415" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-student-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.acbojubus {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.141 18.867c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587Z");
}

.ahuingozp {
  d: path("M19.548 10.639a.9.9 0 0 0-.243-.486l-.273.3l.123.239z");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.anx9dbcfu {
  d: path("m23.914 13.607l-.516 2.239a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bhkjimlol {
  fill-rule: evenodd;
  d: path("M23.962 12.433c.223-.457.34-.967.34-1.498c0-.49-.101-.95-.282-1.37h.006c-.085-.19-.18-.37-.296-.538l-.002-.004a3.4 3.4 0 0 1-.552-1.858v-.011a3.463 3.463 0 0 0-3.462-3.462a.57.57 0 0 1-.478-.245a3.47 3.47 0 0 0-2.815-1.444a3.47 3.47 0 0 0-2.814 1.444a.6.6 0 0 1-.478.245h-.09a3.463 3.463 0 0 0-3.373 3.462v.01a3.4 3.4 0 0 1-.552 1.86l-.002.003a3.46 3.46 0 0 0-.231 3.406a.54.54 0 0 1 0 .477c-.213.447-.34.946-.34 1.477a3.37 3.37 0 0 0 3.377 3.377h9.006a3.37 3.37 0 0 0 3.378-3.377c0-.531-.128-1.03-.34-1.477a.54.54 0 0 1 0-.478M11.095 9.628h-.013L12.34 12.1c.13 2.941 1.278 0 4.081 0s4.026 3.274 4.156.332l1.192-3.355c-.056-1.306-1.003-1.398-1.192-1.398h-3.38a4.05 4.05 0 0 1-3.347-1.756a.277.277 0 0 0-.484.054l-.086.203a2.42 2.42 0 0 1-1.248 1.296q-.025.008-.054.021q-.03.013-.054.021c-.247.129-.829.514-.85 1.51l.01.321z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bomryw3mx {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m16.01 10.72l-.718 1.783a.566.566 0 0 0 .546.734h.825c.387 0 .66-.373.547-.734l-.558-1.784c-.12-.395-.518-.395-.643 0");
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.bsp52gmfy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.387 4.087c.024.255.246 1.214.572 1.795");
}

.bwhm58bkm {
  d: path("M24.378 3.607H8.408c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d9fobtbpp {
  d: path("M16.141 18.867c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587");
}

.dcw978b8o {
  d: path("M20.076 23.773c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.691z");
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dpdvwyp-g {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.947 6.566l-1.496.275a.722.722 0 1 1-.131-1.433h2.456c1.453 0 1.934 1.464 1.993 1.965a3.3 3.3 0 0 0-2.822-.807");
}

.du__vt30i {
  d: path("M23.456 18.096a.24.24 0 0 0-.059-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.014 7.013-4.614");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.edtm2k4mn {
  d: path("M11.504 12.641a1.688 1.688 0 1 0 0-3.376a1.688 1.688 0 0 0 0 3.376");
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fk2lldbhl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.387 4.087c.024.255.246 1.214.572 1.794");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1dr-iwvk {
  d: path("M15.788 2.777c-1.188-.262-2.256.924-2.379 1.364c1.104 3.72 3.897 3.516 6.654 3.21c1.65-.184 1.83.569 1.97.932c0-4.127-3.51-4.902-6.215-5.5z");
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gtkm56isa {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.953 13.603c.424.226.93.356 1.468.356c.544 0 1.044-.13 1.468-.356a.21.21 0 0 1 .257.043c.06.064.082.166.021.258m-3.214-.301l3.173.274m-3.173-.274a.21.21 0 0 0-.257.045a.2.2 0 0 0-.021.257m.278-.302l-.237.274m3.452.027l-.042-.027m.041.027l-.041-.027m.041.027a2.077 2.077 0 0 1-3.492 0m3.45-.027a2.027 2.027 0 0 1-3.409 0m-.041.028l.041-.028m-.041.028l.041-.028");
}

.h1ploqb3t {
  d: path("M11.101 4.669c.594-.63 1.717-.63 2.236-.536l.415 1.354c-.265-.041-.502.053-.7.246c-.471 1.323-2.088 2.052-2.837 2.251c-.156-1.565.114-2.497.886-3.315");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hr_-x2kag {
  d: path("M16.44 15.497c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.hsr2gdsok {
  d: path("M16.09 23.773c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.692z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.i9y-qb10f {
  d: path("M18.644 10.024c.067.089-.072.198-.23.316c-.16.119-.277.202-.344.113s.008-.258.166-.376c.16-.119.342-.142.408-.053");
}

.if_ny3kis {
  d: path("m10.202 5.249l1.253-1.992l9.75-.11l1.36 2.063C17.9 6.82 12.29 5.983 10.2 5.249");
}

.ilsmeichs {
  d: path("M11.524 12.08a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j2yc5acwm {
  cx: 13.847px;
  cy: 10.226px;
  rx: 0.409px;
  ry: 0.207px;
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jnje24bmk {
  fill: var(--svg-color--000, #000);
  d: path("M14.665 10.762a.534.534 0 0 0-.536-.536a.534.534 0 0 0-.477.783h.95a.5.5 0 0 0 .063-.247");
}

.k3g357sye {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.871 3.71v7.768");
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lp540jb3q {
  d: path("M21.487 12.08a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.m5-fuljfc {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M11.101 4.669c.594-.63 1.717-.63 2.236-.536l.415 1.354c-.265-.041-.502.053-.7.246c-.471 1.323-2.088 2.052-2.837 2.251c-.156-1.565.114-2.497.886-3.315");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.nae89ybnj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.644 10.024c.067.089-.072.198-.23.316c-.16.119-.277.202-.344.113s.008-.258.166-.376c.16-.119.342-.142.408-.053");
}

.njptydi6j {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.62 10.356c.28-.49.703-.877 1.614-.877c.399 0 .783.11 1.125.387c.282.228.245.52.026.629l-.583.333c-.684-.221-1.44-.251-2.181-.472");
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.oskgvabkg {
  d: path("M21.487 12.641a1.688 1.688 0 1 0 0-3.376a1.688 1.688 0 0 0 0 3.376");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ovz5vk44l {
  d: path("M14.129 9.826a.936.936 0 0 0-.902 1.183h1.809a1 1 0 0 0 .034-.247a.943.943 0 0 0-.941-.936");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p1huxcp_c {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.478 8.463c-.338-.082-1.18-.04-1.742.362");
}

.p2nuhtbve {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.222 10.356c-.278-.49-.702-.877-1.613-.877c-.399 0-.784.11-1.125.387c-.283.228-.245.52-.026.629l.583.333c.684-.221 1.44-.251 2.181-.472");
}

.p7efr3alc {
  d: path("M23.665 29.997V18.211a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pdqk7nbnd {
  d: path("M24.368 11.646a.837.837 0 1 0 .8 0z");
}

.pgbc5zcxn {
  stop-color: var(--svg-color--2e181b, #2E181B);
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qyczxj7-g {
  d: path("M18.713 9.826a.936.936 0 0 1 .903 1.183h-1.81a.94.94 0 0 1 .907-1.183");
}

.r_aboqbqw {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m16.02 10.574l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.558-1.784c-.12-.395-.677-.395-.802 0");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-t2w9rov {
  d: path("m16.02 10.574l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.558-1.784c-.12-.395-.677-.395-.802 0");
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rpho_cb_u {
  d: path("M11.083 9.628h.012l-.01-.278l-.011-.321c.021-.996.603-1.382.85-1.51l.054-.022q.029-.013.054-.021A2.42 2.42 0 0 0 13.28 6.18l.086-.203a.277.277 0 0 1 .485-.054a4.05 4.05 0 0 0 3.347 1.756h3.379c.189 0 1.135.092 1.192 1.398l-.125 3.226c-.13 2.94-2.426 4.916-5.23 4.916c-2.803 0-5.1-1.975-5.23-4.917z");
}

.s_yujzuhc {
  d: path("M14.985 10.652c0-.302-.246-.504-.313-.565l-.302.293l.186.379z");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sk-p0ogej {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.457 8.463c.338-.082 1.18-.04 1.742.362");
}

.smcd2gbip {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.788 2.777c-1.188-.262-2.256.924-2.379 1.364c1.104 3.72 3.897 3.516 6.654 3.21c1.65-.184 1.83.569 1.97.932c0-4.127-3.51-4.902-6.215-5.5z");
}

.sqvts9xow {
  stop-color: var(--svg-color--432c2b, #432C2B);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t2yfqccvi {
  stop-color: var(--svg-color--3b202c, #3B202C);
  stop-opacity: 0;
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t7u3qkefj {
  stop-color: var(--svg-color--545253, #545253);
  stop-opacity: 0;
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.ttuv3t6wt {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M21.487 12.08a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.voql45s9b {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.856 9.087l-.005.003a.281.281 0 0 1-.29-.483h.001l.001-.001l.003-.002l.01-.006q.013-.006.034-.019q.044-.024.122-.061c.103-.05.25-.113.43-.17c.357-.114.856-.21 1.394-.114a.281.281 0 0 1-.098.554a2.4 2.4 0 0 0-1.125.096a3 3 0 0 0-.477.203");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w4h8bubsi {
  stop-color: var(--svg-color--545253, #545253);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wee83-4gn {
  stop-color: var(--svg-color--2c161d, #2C161D);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wjo7a7bex {
  d: path("M25.168 11.67V2.807h-.8v8.863z");
}

.wmomyrb5j {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.44 15.497c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x20-z4bup {
  fill: var(--svg-color--000, #000);
  d: path("M18.177 10.762c0-.298.238-.536.536-.536a.534.534 0 0 1 .477.783h-.95a.5.5 0 0 1-.063-.247");
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xth2jjbyg {
  d: path("M12.103 23.773c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ym1rlhfdr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m20.337 8.607l-.145.241za.282.282 0 0 1-.289.483l-.005-.003l-.023-.013l-.096-.048a3 3 0 0 0-.359-.142a2.4 2.4 0 0 0-1.125-.096a.281.281 0 0 1-.097-.554c.538-.095 1.037 0 1.393.114a3.4 3.4 0 0 1 .586.25l.01.006l.003.002z");
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.yra8txf4s {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.524 12.08a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z-6q60xzi {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.93 9.54c.686 0 1.264.473 1.422 1.111a.288.288 0 0 1-.281.358H17.73a.24.24 0 0 1-.238-.285A1.466 1.466 0 0 1 18.93 9.54");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zk3jj_8bc {
  cx: 13.847px;
  cy: 10.226px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.zv6ta8bxw {
  d: path("M9.206 29.997V18.211a10.97 10.97 0 0 0-3.766 8.286v3.5z");
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zy49r70sz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.912 9.54c-.686 0-1.264.473-1.422 1.111a.288.288 0 0 0 .281.358h2.341a.24.24 0 0 0 .238-.285a1.47 1.47 0 0 0-1.438-1.183");
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
