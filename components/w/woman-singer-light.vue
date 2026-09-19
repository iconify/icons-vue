<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyNFMId)"><path fill="url(#iU8FSCb)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#iOIZf3b)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#iwlcdSd)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#i30LAwb)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#igJmVHb)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#igEhRcd)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#imLfgtd)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#ieRVR0q)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#io2Y3Xd)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#iJAz26T)" clip-rule="evenodd" class="aduj_e_lm"/><path fill="url(#i9m1wvb)" clip-rule="evenodd" class="aduj_e_lm"/></g><g filter="url(#iphu5Ud)"><path class="kf5ydzbkw"/><path fill="url(#ijkmK3c)" class="hw6w5_j-k"/></g><path fill="url(#inuVhoc)" class="pw-u_fdhk"/><path fill="url(#iR1RITc)" class="pw-u_fdhk"/><path fill="url(#ikfrscc)" class="h2jzxy-bn"/><path fill="url(#iWUfERd)" class="h2jzxy-bn"/><path fill="url(#iANN6AD)" class="ksylej4ab"/><path fill="url(#il9oWTc)" class="l2j9uceik"/><path fill="url(#iQN7nye)" class="l2j9uceik"/><path fill="url(#i5awphc)" class="l2j9uceik"/><path fill="url(#iY1pySx)" class="l2j9uceik"/><path fill="url(#iDwn6Mc)" class="zt-wrvhib"/><path fill="url(#iEY0BoG)" class="zt-wrvhib"/><path fill="url(#ivW6UiV)" class="zt-wrvhib"/><path fill="url(#i0lSTRC)" class="jgezf_b9n"/><path fill="url(#i0Y8ITc)" class="jgezf_b9n"/><path fill="url(#iY49Koc)" class="juej_y2lu"/><path fill="url(#iD9bnjb)" class="juej_y2lu"/><path fill="url(#iRYyoVc)" class="juej_y2lu"/><g filter="url(#ip7IWQd)"><path stroke="url(#iZHIWMe)" class="b47p23b5p"/></g><path fill="url(#iFpupib)" class="j5o0fgbjo"/><path fill="url(#ir3pXsX)" class="j5o0fgbjo"/><path fill="url(#i0iZZje)" class="j5o0fgbjo"/><path fill="url(#iamgald)" class="j5o0fgbjo"/><path fill="url(#ijxhxQd)" class="ywl0znmqv"/><path fill="url(#ikPIbFb)" class="ywl0znmqv"/><path fill="url(#iVR9mdQ)" class="mmgungb3m"/><path fill="url(#iInrlfc)" class="mmgungb3m"/><path fill="url(#i5MbPed)" class="mmgungb3m"/><path fill="url(#icKxB2c)" class="mmgungb3m"/><g filter="url(#iunsznd)"><path fill="url(#i18GEid)" class="h6q9k5kxv"/><path fill="url(#iDv2keZ)" class="h6q9k5kxv"/><path fill="url(#iLyFy7b)" class="h6q9k5kxv"/></g><path fill="url(#irS5kGd)" class="hso2r22lu"/><path fill="url(#i0FUNoc)" class="hso2r22lu"/><path fill="url(#iGJinme)" class="hso2r22lu"/><g filter="url(#iWCWMHc)"><path fill="url(#iPeBEgd)" class="y55zg8_5g"/></g><g filter="url(#ivuWpGb)"><path fill="url(#iOzixqb)" class="xtu76vbhx"/><path fill="url(#iXomRHe)" class="xtu76vbhx"/><path fill="url(#i3MiB6b)" class="xtu76vbhx"/><path fill="url(#ieLtYWd)" class="xtu76vbhx"/><path fill="url(#iN1y7Nb)" class="xtu76vbhx"/></g><path fill="url(#iuUTU2i)" class="xtu76vbhx"/><g filter="url(#ixPpuKu)"><path stroke="url(#iNjD6fd)" class="rbncc3b0e"/></g><g filter="url(#iSSxx4v)"><path stroke="url(#ifn6xSb)" class="tzt1rlcao"/></g><g filter="url(#iwaqj9f)"><path stroke="url(#iRwsBue)" class="iw_bv4b1h"/></g><path fill="url(#iuBS74d)" class="in_wyk0zp"/><path fill="url(#iiafFze)" class="gazjkfbup"/><g filter="url(#iQTgyjb)"><path fill="url(#iOxrNie)" class="ut1b6miug"/></g><g filter="url(#iHpj2qc)"><path fill="url(#iVu9Wke)" class="k4b5_re5u"/><path fill="url(#iXT77sd)" class="k4b5_re5u"/></g><g filter="url(#iAXdFLh)"><path class="yp8n-rn2r"/><path fill="url(#it9tiGb)" class="k7dts8bpe"/></g><g filter="url(#iwIWh1d)"><path class="zvmepf4fu"/><path fill="url(#iwYmUZb)" class="jl987rbmq"/></g><g filter="url(#iiQsk5c)"><path fill="url(#imcxqfe)" class="h6t5p905l"/><path fill="url(#ijI2rqe)" class="h6t5p905l"/><path fill="url(#iMQcTMb)" class="h6t5p905l"/><path fill="url(#iCiIIYb)" class="h6t5p905l"/><path fill="url(#iiBQ7GC)" class="h6t5p905l"/><path fill="url(#iR5wXEb)" class="h6t5p905l"/><path fill="url(#iGTsoDv)" class="h6t5p905l"/></g><path fill="url(#ihIaepe)" class="h6t5p905l"/><path fill="url(#idbfJBe)" class="h6t5p905l"/><g filter="url(#iYzbp1X)"><path class="tlltu7bve"/></g><g filter="url(#idMJIFb)"><path class="d6t2hnbxr"/><path fill="url(#iopsEzc)" class="wlxpthuom"/><path fill="url(#iNv5cge)" class="wlxpthuom"/><path fill="url(#i3doeec)" class="wlxpthuom"/><path fill="url(#iNhhNwe)" class="wlxpthuom"/></g><path fill="url(#ibqErpR)" class="wlxpthuom"/><path fill="url(#iMGz5Dc)" class="wlxpthuom"/><path fill="url(#idUaFIb)" class="f205oymgm"/><path fill="url(#ixxTHgK)" class="f205oymgm"/><path stroke="url(#ioXRNDb)" class="wkwgzejyp"/><g filter="url(#iQ8YnSd)"><path class="bmgrkrbrw"/></g><g filter="url(#iKCvSJc)"><path class="mll_4yzkv"/></g><g filter="url(#iO4pYLO)"><path class="fp95ddcik"/></g><g filter="url(#ik1Xvlc)"><path clip-rule="evenodd" class="rxf2-tb2y"/></g><path class="kbfjnbxqd"/><path fill="url(#iEp5Vpe)" class="dztghoe_v"/><path class="brbongonp"/><g filter="url(#ichs15c)"><path class="yed6gbc7b"/><path fill="url(#ijyqYlc)" class="iwa57f-nl"/></g><g filter="url(#iNjZTPT)"><path fill="url(#iHzy0Rb)" class="csz49e0wn"/></g><path class="pc0jjfb4m"/><path fill="url(#idxogNd)" class="sjqag04ua"/><path class="twjbs1b_o"/><g filter="url(#ilHu7qc)"><path fill="url(#iTnZO9b)" class="w195y1hlc"/></g><g filter="url(#ia2ZMtb)"><ellipse transform="rotate(-27.914 12.586 11.223)" class="u0avi0m9c"/><ellipse fill="url(#iusJ7ee)" transform="rotate(-27.914 12.586 11.223)" class="xee49ibqz"/></g><g filter="url(#iDd9AUc)"><path class="i3l80f5yx"/></g><g filter="url(#iMd1Awc)"><path class="nfk3w17av"/></g><g filter="url(#iH4XtGP)"><path class="jyj_wjglj"/><path fill="url(#iHrfgye)" class="izjahjbxf"/></g><g filter="url(#iF70dRY)"><path class="tji43n2vg"/><path fill="url(#i8ArfgE)" class="cm4ql_sfr"/><path fill="url(#iWbu6xe)" class="cm4ql_sfr"/></g><g filter="url(#iTM6uyc)"><path stroke="url(#igcfosb)" class="fc-87yb5j"/></g><g filter="url(#isTsLib)"><path class="f6_2lub5i"/></g><defs><radialGradient id="iOIZf3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.61764 4.66662 -5.82956 -.77156 14.789 14.491)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iwlcdSd" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.696 9.203)scale(3.55941 4.67679)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i30LAwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33821 1.75 -1.34375 -1.02756 10.14 12.158)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="igJmVHb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.474 8.014)scale(2.53345 1.78459)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="igEhRcd" cx="0" cy="0" r="1" gradientTransform="matrix(1.40685 2.67644 -3.71532 1.95293 11.495 3.683)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="imLfgtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47538 1.47549 -2.06197 -2.06182 21.068 5.81)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ieRVR0q" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.604 7.153)scale(1.96539 4.09867)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="io2Y3Xd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88224 .7206 -.91794 -3.67154 22.166 14.56)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iJAz26T" cx="0" cy="0" r="1" gradientTransform="matrix(-.92578 -2.71278 2.14566 -.73224 19.942 8.569)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i9m1wvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5394 .16147 -.26164 2.49427 8.81 11.023)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="inuVhoc" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.896)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="ikfrscc" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.569 19.687)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="iY1pySx" cx="0" cy="0" r="1" gradientTransform="rotate(44.502 -14.575 38.533)scale(2.54126 2.34764)" gradientUnits="userSpaceOnUse"><stop class="apsa9cl1l"/><stop offset="1" class="ji3tmwq8i"/></radialGradient><radialGradient id="ivW6UiV" cx="0" cy="0" r="1" gradientTransform="rotate(127.231 1.558 11.246)scale(5.01003 5.42155)" gradientUnits="userSpaceOnUse"><stop offset=".054" class="mi2y_fs0q"/><stop offset="1" class="l1asq8nfe"/></radialGradient><radialGradient id="iY49Koc" cx="0" cy="0" r="1" gradientTransform="scale(5.21858 8.19791)rotate(90 .16 2.733)" gradientUnits="userSpaceOnUse"><stop class="vi1b5eb1y"/><stop offset="1" class="l395fyurn"/></radialGradient><radialGradient id="iD9bnjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.03341 12.2744 0 15.098 24.488)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="adcs_o2_t"/><stop offset="1" class="sttbc8byn"/></radialGradient><radialGradient id="iZHIWMe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.697 12.303 6.617)scale(2.35978 2.2583)" gradientUnits="userSpaceOnUse"><stop class="ehzds51-c"/><stop offset="1" class="zodlqdm5x"/></radialGradient><radialGradient id="iFpupib" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.44554 -3.83658 0 15.098 17.603)" gradientUnits="userSpaceOnUse"><stop class="phr4kdbzq"/><stop offset=".736" class="dvz5h743a"/></radialGradient><radialGradient id="ir3pXsX" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.08555 -.86564 0 13.195 17.502)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="vg7nsbfmw"/><stop offset="1" class="p0rifmbnf"/></radialGradient><radialGradient id="i0iZZje" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -.82178 0 17.267 17.44)" gradientUnits="userSpaceOnUse"><stop class="tm4l-bi2r"/><stop offset="1" class="ey48hjebw"/></radialGradient><radialGradient id="iamgald" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.38834 -3.3618 0 15.098 18.043)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="zt-l4cc2x"/><stop offset="1" class="yolby-u1j"/></radialGradient><radialGradient id="ijxhxQd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36264 1.13067 -1.10926 -2.3179 28.941 22.136)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="ikPIbFb" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.086 21.644)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iInrlfc" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.26 12.222)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="i5MbPed" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.493)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="icKxB2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.85)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="iDv2keZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 17.242)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iPeBEgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.98 21.113)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="iXomRHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.651)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i3MiB6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 25.07)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ieLtYWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.44)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iN1y7Nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.922)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iuUTU2i" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49946 -4.50112 0 28.605 23.298)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="iVu9Wke" cx="0" cy="0" r="1" gradientTransform="matrix(1.87008 -2.08454 2.54513 2.28328 19.713 12.93)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iXT77sd" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -9.406 43.949)scale(1.54394 .4365)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="it9tiGb" cx="0" cy="0" r="1" gradientTransform="rotate(-4.254 171.969 -257.734)scale(1.54978 1.2115)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iwYmUZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23528 0 0 -.97449 10.388 11.932)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="imcxqfe" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.763 7.669)scale(7.33069 9.812)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="ijI2rqe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.54281 .46177 -.5097 -3.91064 18.426 12.776)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iMQcTMb" cx="0" cy="0" r="1" gradientTransform="rotate(-70.959 19.578 .56)scale(4.10185 5.20449)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iCiIIYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.88331 -7.96768 0 15.098 11.16)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="oahyagbtm"/><stop offset="1" class="au5a3_kml"/></radialGradient><radialGradient id="iiBQ7GC" cx="0" cy="0" r="1" gradientTransform="matrix(-7.06857 1.38718 -2.3883 -12.16987 16.95 13.153)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iR5wXEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17792 1.44563 0 17.453 10.953)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iGTsoDv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34348 1.53971 0 12.972 10.72)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ihIaepe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3156 0 0 -6.59762 20.313 12.476)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="idbfJBe" cx="0" cy="0" r="1" gradientTransform="rotate(71.834 2.812 11.499)scale(4.30914 7.50704)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iopsEzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.46629 -2.09223 .6448 -.1437 15.9 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="iNhhNwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.79779 0 0 -.22304 15.655 13.436)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iMGz5Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40355 .9636 -1.15809 -1.68686 15.483 12.827)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="idUaFIb" cx="0" cy="0" r="1" gradientTransform="rotate(159.839 6.646 6.638)scale(6.89096 6.0187)" gradientUnits="userSpaceOnUse"><stop class="ic-qqq3du"/><stop offset="1" class="w6le0vxed"/><stop offset="1" class="ym086l4wg"/></radialGradient><radialGradient id="ixxTHgK" cx="0" cy="0" r="1" gradientTransform="rotate(131.12 5.026 6.904)scale(.66525 2.54787)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="ri6vfobjz"/><stop offset="1" class="vslufkb1d"/></radialGradient><radialGradient id="iEp5Vpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32093 0 17.331 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijyqYlc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.342 1.516)scale(.38721 .53309)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idxogNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32094 0 12.864 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iusJ7ee" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.968 -.415)scale(.50578 .60796)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHrfgye" cx="0" cy="0" r="1" gradientTransform="matrix(1.2918 -2.82043 1.44286 .66085 9.306 9.15)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i8ArfgE" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.326 7.27)scale(4.98785 8.15485)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iWbu6xe" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 5.856 8.668)scale(1.41591 3.04626)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><linearGradient id="iU8FSCb" x1="19.901" x2="12.936" y1="4.815" y2="17.717" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="ijkmK3c" x1="16.901" x2="15.504" y1="26.418" y2="26.115" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iR1RITc" x1="7.199" x2="6.027" y1="26.217" y2="26.217" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iWUfERd" x1="23.128" x2="23.77" y1="26.303" y2="26.271" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iANN6AD" x1="23.395" x2="21.614" y1="26.334" y2="26.334" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="il9oWTc" x1="22.77" x2="18.395" y1="16.288" y2="28.798" gradientUnits="userSpaceOnUse"><stop class="p3s97ubgt"/><stop offset="1" class="uhr48tggx"/></linearGradient><linearGradient id="iQN7nye" x1="17.486" x2="17.954" y1="23.056" y2="23.142" gradientUnits="userSpaceOnUse"><stop class="n-07uqbej"/><stop offset="1" class="k5vnjbbpd"/></linearGradient><linearGradient id="i5awphc" x1="23.501" x2="22.829" y1="20.642" y2="20.36" gradientUnits="userSpaceOnUse"><stop offset=".258" class="e6ztocy0u"/><stop offset="1" class="tjnac7b5i"/></linearGradient><linearGradient id="iDwn6Mc" x1="8.954" x2="11.895" y1="16.809" y2="29.178" gradientUnits="userSpaceOnUse"><stop class="yhs78-b2s"/><stop offset="1" class="ou99nli7g"/></linearGradient><linearGradient id="iEY0BoG" x1="13.408" x2="12.861" y1="25.876" y2="25.985" gradientUnits="userSpaceOnUse"><stop class="tyg1xhaog"/><stop offset="1" class="wn22vh-9z"/></linearGradient><linearGradient id="i0lSTRC" x1="8.114" x2="10.395" y1="28.146" y2="26.99" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="i0Y8ITc" x1="9.877" x2="9.013" y1="26.165" y2="26.68" gradientUnits="userSpaceOnUse"><stop class="a9i5gdgdq"/><stop offset="1" class="qrkl270nd"/></linearGradient><linearGradient id="iRYyoVc" x1="17.86" x2="16.54" y1="22.682" y2="22.523" gradientUnits="userSpaceOnUse"><stop offset=".061" class="dlh6c6b0i"/><stop offset="1" class="cz1-mcbkd"/></linearGradient><linearGradient id="iVR9mdQ" x1="25.739" x2="25.739" y1="15.984" y2="20.041" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="i18GEid" x1="25.933" x2="25.792" y1="16.92" y2="18.123" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iLyFy7b" x1="23.236" x2="23.363" y1="16.857" y2="17.293" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="irS5kGd" x1="26.936" x2="24.648" y1="21.427" y2="21.427" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="i0FUNoc" x1="24.466" x2="24.847" y1="21.269" y2="21.241" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iGJinme" x1="27.084" x2="26.822" y1="21.141" y2="21.117" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="iOzixqb" x1="27.996" x2="23.128" y1="26.674" y2="26.674" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iNjD6fd" x1="23.742" x2="25.663" y1="24.471" y2="24.471" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ifn6xSb" x1="23.742" x2="25.663" y1="25.913" y2="25.913" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iRwsBue" x1="23.742" x2="25.663" y1="27.343" y2="27.343" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iuBS74d" x1="7.743" x2="22.458" y1="16.855" y2="16.855" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iiafFze" x1="7.743" x2="22.458" y1="16.824" y2="16.824" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iOxrNie" x1="8.654" x2="11.683" y1="12.021" y2="12.021" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iNv5cge" x1="14.137" x2="15.098" y1="13.294" y2="13.294" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="i3doeec" x1="15.098" x2="15.098" y1="14.112" y2="13.487" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ibqErpR" x1="15.178" x2="15.178" y1="14.085" y2="13.943" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="ioXRNDb" x1="14.008" x2="14.48" y1="15.555" y2="14.826" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iHzy0Rb" x1="18.127" x2="17.806" y1="11.376" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTnZO9b" x1="13.625" x2="13.304" y1="11.376" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igcfosb" x1="12.138" x2="12.695" y1="5.587" y2="6.891" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><filter id="iyNFMId" width="15.622" height="16.122" x="7.411" y="2.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="iphu5Ud" width="5.513" height="4.74" x="12.848" y="24.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="ip7IWQd" width="5.221" height="5.427" x="12.487" y="15.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".1"/></filter><filter id="iunsznd" width="6.102" height="1.228" x="22.791" y="16.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="iWCWMHc" width="1.075" height="1.075" x="25.198" y="20.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2325" result="effect2_innerShadow_4002_2325"/></filter><filter id="ivuWpGb" width="5.369" height="6.076" x="23.128" y="22.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="ixPpuKu" width="2.319" height=".3" x="23.592" y="24.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".05"/></filter><filter id="iSSxx4v" width="2.319" height=".3" x="23.592" y="25.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".05"/></filter><filter id="iwaqj9f" width="2.319" height=".3" x="23.592" y="27.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".05"/></filter><filter id="iQTgyjb" width="3.444" height="3.294" x="8.654" y="10.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="iHpj2qc" width="3.294" height="3.544" x="18.392" y="10.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="iAXdFLh" width="3.199" height="3.199" x="18.439" y="10.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".25"/></filter><filter id="iwIWh1d" width="2.999" height="2.999" x="8.822" y="10.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".2"/></filter><filter id="iiQsk5c" width="10.431" height="11.533" x="9.882" y="6.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="iYzbp1X" width="2.922" height="3.745" x="13.47" y="10.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".25"/></filter><filter id="idMJIFb" width="2.422" height="3.245" x="13.887" y="11.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".125"/></filter><filter id="iQ8YnSd" width="3.067" height="1.316" x="16.066" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="iKCvSJc" width="3.067" height="1.316" x="11.061" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="iO4pYLO" width="2.506" height="1.112" x="11.2" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="ik1Xvlc" width="2.506" height="1.112" x="16.744" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/></filter><filter id="ichs15c" width=".801" height=".708" x="16.582" y="10.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".05"/></filter><filter id="iNjZTPT" width=".903" height=".926" x="17.444" y="10.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".1"/></filter><filter id="ilHu7qc" width="1" height="1.055" x="12.896" y="10.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".1"/></filter><filter id="ia2ZMtb" width=".93" height=".716" x="12.121" y="10.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".05"/></filter><filter id="iDd9AUc" width="2.3" height=".987" x="16.783" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".1"/></filter><filter id="iMd1Awc" width="2.3" height=".987" x="11.202" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".1"/></filter><filter id="iH4XtGP" width="4.292" height="4.601" x="8.703" y="4.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/><feGaussianBlur result="effect2_foregroundBlur_4002_2325" stdDeviation=".15"/></filter><filter id="iF70dRY" width="8.961" height="5.907" x="11.859" y="3.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2325"/><feGaussianBlur result="effect2_foregroundBlur_4002_2325" stdDeviation=".125"/></filter><filter id="iTM6uyc" width="1.158" height="2.35" x="11.838" y="4.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".1"/></filter><filter id="isTsLib" width="6.543" height="3.416" x="14.52" y="5.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2325" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-singer-light" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a9i5gdgdq {
  stop-color: var(--svg-color--55447c, #55447C);
}

.adcs_o2_t {
  stop-color: var(--svg-color--8e5f51, #8E5F51);
  stop-opacity: 0;
}

.aduj_e_lm {
  fill-rule: evenodd;
  d: path("M22.452 13.375a3.3 3.3 0 0 0 .332-1.461c0-.478-.099-.927-.275-1.336h.005a3.3 3.3 0 0 0-.288-.525l-.002-.004a3.3 3.3 0 0 1-.538-1.812v-.01a3.377 3.377 0 0 0-3.377-3.378a.55.55 0 0 1-.466-.238a3.38 3.38 0 0 0-2.746-1.409c-1.129 0-2.134.56-2.745 1.41a.58.58 0 0 1-.466.237l-.087.001a3.38 3.38 0 0 0-3.29 3.376v.01c0 .643-.186 1.275-.538 1.813l-.003.004a3.38 3.38 0 0 0-.225 3.322a.53.53 0 0 1 0 .466a3.34 3.34 0 0 0-.332 1.44a3.29 3.29 0 0 0 3.294 3.294h8.785a3.29 3.29 0 0 0 3.294-3.294a3.34 3.34 0 0 0-.332-1.44a.53.53 0 0 1 0-.466m-12.55-2.736H9.89l1.227 2.411c.126 2.869 1.246 0 3.98 0s3.927 3.193 4.053.325l1.163-3.273c-.055-1.274-.978-1.364-1.163-1.364h-3.295a3.95 3.95 0 0 1-3.265-1.712a.27.27 0 0 0-.472.052l-.084.198a2.36 2.36 0 0 1-1.218 1.264l-.053.02l-.052.022c-.241.125-.808.501-.83 1.472l.011.314z");
}

.apsa9cl1l {
  stop-color: var(--svg-color--7955b5, #7955B5);
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au5a3_kml {
  stop-color: var(--svg-color--cd879f, #CD879F);
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.b47p23b5p {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.812 15.654h4.571v2.8c0 1.262-1.023 1.977-2.285 1.977s-2.286-.715-2.286-1.978z");
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bmgrkrbrw {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.266 11.349c.272-.478.685-.855 1.574-.855c.39 0 .765.108 1.098.377c.275.223.239.507.025.614l-.569.325c-.667-.216-1.405-.245-2.128-.461");
}

.brbongonp {
  fill: var(--svg-color--000, #000);
  d: path("M16.81 11.746c0-.29.233-.524.523-.524a.52.52 0 0 1 .465.765h-.926a.5.5 0 0 1-.062-.241");
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
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

.cm4ql_sfr {
  d: path("M14.48 3.957c-1.16-.256-2.2.9-2.32 1.33c1.076 3.628 3.8 3.43 6.489 3.13c1.61-.178 1.784.556 1.922.91c0-4.025-3.424-4.781-6.062-5.363z");
}

.csz49e0wn {
  d: path("M18.147 11.625a.86.86 0 0 0-.237-.473l-.266.292l.12.233z");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cz1-mcbkd {
  stop-color: var(--svg-color--c48f89, #C48F89);
  stop-opacity: 0;
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.d6t2hnbxr {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m14.706 11.562l-.544 1.74a.552.552 0 0 0 .533.716h.805a.554.554 0 0 0 .533-.716l-.544-1.74c-.117-.385-.66-.385-.783 0");
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dlh6c6b0i {
  stop-color: var(--svg-color--a87171, #A87171);
}

.dvz5h743a {
  stop-color: var(--svg-color--cd8d94, #CD8D94);
}

.dztghoe_v {
  d: path("M17.333 10.832a.914.914 0 0 1 .88 1.154H16.45a.917.917 0 0 1 .885-1.154");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e6ztocy0u {
  stop-color: var(--svg-color--876bc0, #876BC0);
}

.ehzds51-c {
  stop-color: var(--svg-color--dca89e, #DCA89E);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.ey48hjebw {
  stop-color: var(--svg-color--d3a59b, #D3A59B);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f205oymgm {
  d: path("M14.096 8.33a3.9 3.9 0 0 1-1.506-1.304a.27.27 0 0 0-.467.04l-1.906 5.61h1.895l-.522 2.921l3.92-5.504h-2.02z");
}

.f6_2lub5i {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.56 7.652l-1.458.268a.704.704 0 1 1-.128-1.397h2.396c1.417 0 1.886 1.428 1.943 1.916a3.22 3.22 0 0 0-2.752-.787");
}

.fc-87yb5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.138 5.235c.024.249.24 1.184.557 1.75");
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.fp95ddcik {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.62 10.112l-.005.002a.275.275 0 0 1-.282-.47v-.001h.002l.003-.002l.01-.006a2 2 0 0 1 .151-.079c.101-.048.245-.11.42-.165a2.9 2.9 0 0 1 1.36-.112a.274.274 0 1 1-.096.54c-.408-.071-.8 0-1.097.095a3 3 0 0 0-.466.198");
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gazjkfbup {
  d: path("M15.123 16.824h-.041c.102 0 .194 0 .297.01c-.082-.01-.174-.01-.256-.01");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h2jzxy-bn {
  d: path("M27.018 28.788c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h6q9k5kxv {
  d: path("m28.214 16.828l-4.844-.02a.57.57 0 0 0-.58.579c0 .325.255.578.58.578l4.844.02a.57.57 0 0 0 .578-.578a.585.585 0 0 0-.578-.579");
}

.h6t5p905l {
  d: path("M9.89 10.64h.013l-.01-.272l-.011-.314c.02-.97.588-1.347.83-1.472l.052-.021l.052-.021c.546-.25.987-.69 1.218-1.264l.084-.198a.27.27 0 0 1 .472-.052a3.95 3.95 0 0 0 3.265 1.712h3.296c.184 0 1.107.09 1.162 1.364l-.121 3.146c-.127 2.868-2.367 4.794-5.101 4.794s-4.975-1.926-5.101-4.794z");
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hso2r22lu {
  d: path("M25.726 26.628a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.hw6w5_j-k {
  d: path("M12.848 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i3l80f5yx {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.083 9.503c.33-.08 1.15-.04 1.7.353");
}

.ic-qqq3du {
  stop-color: var(--svg-color--f63273, #F63273);
}

.in_wyk0zp {
  d: path("M15.46 16.824c.257.01.523.031.789.051c-.266-.02-.522-.04-.788-.05");
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iw_bv4b1h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 27.265h2.02");
}

.iwa57f-nl {
  d: path("M17.266 11.025c.065.087-.071.194-.226.31c-.154.115-.27.196-.334.11c-.065-.088.007-.252.162-.368s.333-.139.398-.052");
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.izjahjbxf {
  d: path("M9.909 5.802c.579-.613 1.675-.614 2.181-.523l.405 1.321c-.259-.04-.49.052-.683.24c-.46 1.29-2.037 2.002-2.768 2.197c-.152-1.527.111-2.437.865-3.235");
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j5o0fgbjo {
  d: path("M12.812 15.654h4.571v2.8c0 1.262-1.023 1.977-2.285 1.977s-2.286-.715-2.286-1.978z");
}

.jgezf_b9n {
  d: path("M7.078 28.788h3.87l-3.87-7.596z");
}

.ji3tmwq8i {
  stop-color: var(--svg-color--7955b5, #7955B5);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jl987rbmq {
  d: path("M10.321 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.juej_y2lu {
  d: path("M15.118 17.688c-1.16 0-2.298.171-3.378.491l1.098 5.869c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.jyj_wjglj {
  fill: var(--svg-color--232121, #232121);
  d: path("M9.909 5.802c.579-.613 1.675-.614 2.181-.523l.405 1.321c-.259-.04-.49.052-.683.24c-.46 1.29-2.037 2.002-2.768 2.197c-.152-1.527.111-2.437.865-3.235");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k4b5_re5u {
  d: path("M20.039 13.579a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.k5vnjbbpd {
  stop-color: var(--svg-color--845ebf, #845EBF);
  stop-opacity: 0;
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k7dts8bpe {
  d: path("M20.039 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.kbfjnbxqd {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 10.554a1.43 1.43 0 0 1 1.387 1.084a.28.28 0 0 1-.274.349h-2.284a.236.236 0 0 1-.233-.279a1.43 1.43 0 0 1 1.404-1.154");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kf5ydzbkw {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.ksylej4ab {
  d: path("M23.128 28.788v-7.303l-3.52 7.303z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l1asq8nfe {
  stop-color: var(--svg-color--815eb7, #815EB7);
  stop-opacity: 0;
}

.l2j9uceik {
  d: path("m24.313 16.801l-4.779.021a1 1 0 0 0-.978.816l-2.097 11.16h3.149l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l395fyurn {
  stop-color: var(--svg-color--ae756b, #AE756B);
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mi2y_fs0q {
  stop-color: var(--svg-color--6c3b70, #6C3B70);
}

.mll_4yzkv {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.929 11.349c-.272-.478-.685-.855-1.574-.855c-.39 0-.764.108-1.098.377c-.275.223-.238.507-.025.614l.569.325c.667-.216 1.405-.245 2.128-.461");
}

.mmgungb3m {
  d: path("M25.766 19.986a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n-07uqbej {
  stop-color: var(--svg-color--8e5280, #8E5280);
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.nfk3w17av {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.202 9.503c-.33-.08-1.15-.04-1.7.353");
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.oahyagbtm {
  stop-color: var(--svg-color--d496a4, #D496A4);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ou99nli7g {
  stop-color: var(--svg-color--9266df, #9266DF);
}

.p0rifmbnf {
  stop-color: var(--svg-color--d4948d, #D4948D);
  stop-opacity: 0;
}

.p3s97ubgt {
  stop-color: var(--svg-color--8866b4, #8866B4);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pc0jjfb4m {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.65 10.554a1.43 1.43 0 0 0-1.387 1.084a.28.28 0 0 0 .274.348h2.284a.236.236 0 0 0 .233-.278a1.434 1.434 0 0 0-1.404-1.154");
}

.phr4kdbzq {
  stop-color: var(--svg-color--c88491, #C88491);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pw-u_fdhk {
  d: path("M7.078 28.788v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qrkl270nd {
  stop-color: var(--svg-color--55447c, #55447C);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.rbncc3b0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.393h2.02");
}

.ri6vfobjz {
  stop-color: var(--svg-color--860c4f, #860C4F);
}

.rxf2-tb2y {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m18.917 9.643l-.141.236za.275.275 0 0 1-.282.471l-.005-.002a1 1 0 0 0-.115-.06a3 3 0 0 0-.351-.138a2.3 2.3 0 0 0-1.097-.094a.275.275 0 0 1-.096-.54a2.9 2.9 0 0 1 1.36.11a3.4 3.4 0 0 1 .572.245l.01.006l.002.001z");
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sjqag04ua {
  d: path("M12.862 10.832a.913.913 0 0 0-.88 1.154h1.764a1 1 0 0 0 .034-.24a.92.92 0 0 0-.918-.914");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sttbc8byn {
  stop-color: var(--svg-color--8e5f51, #8E5F51);
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tji43n2vg {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M14.48 3.957c-1.16-.256-2.2.9-2.32 1.33c1.076 3.628 3.8 3.43 6.489 3.13c1.61-.178 1.784.556 1.922.91c0-4.025-3.424-4.781-6.062-5.363z");
}

.tjnac7b5i {
  stop-color: var(--svg-color--8263bd, #8263BD);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tlltu7bve {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m14.696 11.704l-.7 1.74a.552.552 0 0 0 .533.715h.805a.554.554 0 0 0 .533-.715l-.544-1.74c-.117-.386-.505-.386-.627 0");
}

.tm4l-bi2r {
  stop-color: var(--svg-color--d3a59b, #D3A59B);
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.twjbs1b_o {
  fill: var(--svg-color--000, #000);
  d: path("M13.385 11.746a.52.52 0 0 0-.523-.524a.52.52 0 0 0-.465.765h.926a.5.5 0 0 0 .062-.241");
}

.tyg1xhaog {
  stop-color: var(--svg-color--6e3c78, #6E3C78);
}

.tzt1rlcao {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.835h2.02");
}

.u0avi0m9c {
  cx: 12.586px;
  cy: 11.223px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.399px;
  ry: 0.202px;
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uhr48tggx {
  stop-color: var(--svg-color--7f54c6, #7F54C6);
}

.ut1b6miug {
  d: path("M10.301 13.579a1.647 1.647 0 1 0 0-3.294a1.647 1.647 0 0 0 0 3.294");
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vg7nsbfmw {
  stop-color: var(--svg-color--d4948d, #D4948D);
}

.vi1b5eb1y {
  stop-color: var(--svg-color--edb5a7, #EDB5A7);
}

.vslufkb1d {
  stop-color: var(--svg-color--860c4f, #860C4F);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w195y1hlc {
  d: path("M13.696 11.638c0-.295-.24-.492-.305-.551l-.295.285l.182.37z");
}

.w6le0vxed {
  stop-color: var(--svg-color--bc2f50, #BC2F50);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wkwgzejyp {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.666 14.515c.413.22.906.347 1.431.347a3.04 3.04 0 0 0 1.432-.347a.21.21 0 0 1 .252.042c.06.063.08.163.021.254m-3.136-.296l3.095.268m-3.095-.268a.21.21 0 0 0-.252.044a.2.2 0 0 0-.021.252m.273-.296l-.232.268m3.368.028l-.041-.027m.041.027l-.041-.027m.041.027a2.028 2.028 0 0 1-3.41 0m3.369-.027a1.977 1.977 0 0 1-3.326 0m-.042.027l.041-.027m-.041.027l.041-.027");
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wlxpthuom {
  d: path("m14.706 11.562l-.544 1.74a.552.552 0 0 0 .533.716h.805a.554.554 0 0 0 .533-.716l-.544-1.74c-.117-.385-.66-.385-.783 0");
}

.wn22vh-9z {
  stop-color: var(--svg-color--825db9, #825DB9);
  stop-opacity: 0;
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xee49ibqz {
  cx: 12.586px;
  cy: 11.223px;
  rx: 0.399px;
  ry: 0.202px;
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xtu76vbhx {
  d: path("M23.128 23.674a.81.81 0 0 1 .816-.802h3.054c.745 0 1.349.59 1.349 1.316v3.514c0 .605-.503 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.315.187-.59.458-.72a.8.8 0 0 1-.457-.72c0-.315.186-.59.457-.721a.8.8 0 0 1-.457-.72c0-.314.186-.59.457-.72a.8.8 0 0 1-.457-.72");
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y55zg8_5g {
  d: path("M25.736 21.916a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.yed6gbc7b {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.266 11.025c.065.087-.071.194-.226.31c-.154.115-.27.196-.334.11c-.065-.088.007-.252.162-.368s.333-.139.398-.052");
}

.yhs78-b2s {
  stop-color: var(--svg-color--7c5aad, #7C5AAD);
}

.ym086l4wg {
  stop-color: var(--svg-color--d5415e, #D5415E);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yolby-u1j {
  stop-color: var(--svg-color--d3928e, #D3928E);
}

.yp8n-rn2r {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.039 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.ywl0znmqv {
  d: path("M27.277 21.112c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zodlqdm5x {
  stop-color: var(--svg-color--dca89e, #DCA89E);
  stop-opacity: 0;
}

.zt-l4cc2x {
  stop-color: var(--svg-color--d49493, #D49493);
  stop-opacity: 0;
}

.zt-wrvhib {
  d: path("M5.405 16.809h5.256a1 1 0 0 1 .983.816l2.095 11.173h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.zvmepf4fu {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M10.321 13.031a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.2");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
