<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iC0GGje)" class="rc1h76bnl"/><path fill="url(#i1H13xe)" class="rc1h76bnl"/><path fill="url(#iIjTaXd)" class="rc1h76bnl"/><path fill="url(#iPtMmBe)" class="rc1h76bnl"/><path fill="url(#iSl8d6c)" class="rc1h76bnl"/><path fill="url(#i0V1E5m)" class="rc1h76bnl"/><path fill="url(#i5uR2ib)" class="rc1h76bnl"/><path fill="url(#i7ZTzCb)" class="rc1h76bnl"/><ellipse class="i97awtjzh"/><path fill="url(#ix12tuc)" class="y1vs2mb8o"/><path fill="url(#i6YBfoe)" class="y1vs2mb8o"/><path fill="url(#iR3EQje)" class="y1vs2mb8o"/><path fill="url(#igRllSc)" class="xe9zzkbwa"/><path fill="url(#iiaQs9c)" class="xe9zzkbwa"/><path fill="url(#iyBr46b)" class="xe9zzkbwa"/><path fill="url(#if2IOSd)" class="xe9zzkbwa"/><path fill="url(#iR8nzAd)" class="xe9zzkbwa"/><path fill="url(#iQb11jb)" class="xe9zzkbwa"/><g filter="url(#iycQawb)"><path class="k74venbek"/></g><g filter="url(#ia1k7zU)"><path class="h5yeq_p8o"/></g><path class="zfaxh3bfn"/><path fill="url(#ioT0Vle)" class="n6d4a_b5j"/><path fill="url(#i2ehxJc)" class="n6d4a_b5j"/><g filter="url(#iCMF8Ae)"><path fill="url(#is3t01O)" class="usumdabyl"/></g><g filter="url(#in8jmAc)"><path class="euoi8w51b"/><path fill="url(#i5yZ6Xc)" class="ixa-v4b4p"/><path class="czhnbxqgu"/></g><path class="fhncxgd-h"/><path fill="url(#ilCnnQc)" class="connkzb_i"/><path fill="url(#iVBPnAc)" class="connkzb_i"/><g filter="url(#iGeoExd)"><path class="u6r73qbri"/><path fill="url(#iC2iByb)" class="u4y_3o-7a"/><path class="uqjwnc3tu"/></g><path class="te8ien3oi"/><path fill="url(#i2qoomd)" class="pwwpxss9w"/><path fill="url(#i1vgEhd)" class="pwwpxss9w"/><g filter="url(#i2JbdXb)"><path class="zxy-3-e6d"/><path fill="url(#iRB3Txb)" class="qej73rwzq"/><path class="soolqkb6q"/></g><path class="gttumh0rn"/><path fill="url(#iilfnOe)" class="j2fmtrbdy"/><path fill="url(#iNYLSrb)" class="j2fmtrbdy"/><g filter="url(#iYyIyMs)"><path class="y6f7ww84q"/><path fill="url(#iUBS66c)" class="gx_q__y7w"/><path class="gk8j6db1f"/></g><path class="vggl2gbmj"/><path fill="url(#ikZqsye)" class="r0p__dbbg"/><path fill="url(#i3rZnDu)" class="r0p__dbbg"/><g filter="url(#iXW1F7d)"><path class="xhk0g5bbi"/><path fill="url(#iCg3R4b)" class="iasyujhyu"/><path class="jh4yexyss"/></g><path class="tb8i4ngwl"/><path fill="url(#iu17gNc)" class="wy678rbza"/><path fill="url(#i1xojfd)" class="wy678rbza"/><g filter="url(#iCtHGOE)"><path class="s_kg18brx"/><path fill="url(#izSvEvc)" class="p9z09nebo"/><path class="vl9rj1bbt"/></g><path class="z23vi-bpc"/><path fill="url(#ikGtMRc)" class="ufbl8wvxk"/><path fill="url(#iDCwnGc)" class="ufbl8wvxk"/><g filter="url(#izpcoFo)"><path class="h9cc7jbkr"/><path fill="url(#iww3Dfc)" class="hxp0gjv0e"/><path class="oustc6n3n"/></g><path class="qf6vbiben"/><path fill="url(#iZM00hb)" class="vtn-slbby"/><path fill="url(#iGtBzye)" class="vtn-slbby"/><g filter="url(#iYYguxb)"><path class="e_set-rzf"/><path fill="url(#iNnRhyc)" class="llukrjbie"/><path class="w221xkbdh"/></g><path class="fp4z79ipc"/><path fill="url(#if1hLPA)" class="hav-7ub9w"/><path fill="url(#iSbbGKz)" class="hav-7ub9w"/><g filter="url(#ibgMsad)"><path class="pt0qz7beh"/><path fill="url(#ipZ6dGd)" class="ff2clgpop"/><path class="zkiztz5oe"/></g><path class="fupouwgsb"/><path fill="url(#iFExQFI)" class="rxynugb5r"/><path fill="url(#ir2vHgJ)" class="rxynugb5r"/><g filter="url(#iq3jPre)"><path class="be5qqsxzd"/><path fill="url(#iIxbeIc)" class="g7c30hbkx"/><path class="qm-3flptb"/></g><path class="oaznyqb1b"/><path fill="url(#ipVw6Rb)" class="v1g9dtsxo"/><path fill="url(#i7hDSco)" class="v1g9dtsxo"/><g filter="url(#ieWI9Xd)"><path class="s709ah40z"/><path fill="url(#ioOu3vd)" class="v-dxfwb2x"/><path class="lojjlyvyt"/></g><path class="cfswfcc_s"/><path fill="url(#ilixNve)" class="z86dmj94q"/><path fill="url(#idoGdae)" class="z86dmj94q"/><g filter="url(#imyQzib)"><ellipse fill="url(#ih8PlFe)" class="sid9_xdxj"/></g><defs><linearGradient id="iC0GGje" x1="15.98" x2="15.98" y1="17.238" y2="29" gradientUnits="userSpaceOnUse"><stop class="rbrm_frqe"/><stop offset="1" class="khnh02bwl"/></linearGradient><linearGradient id="iIjTaXd" x1="15.98" x2="15.98" y1="13.938" y2="21.75" gradientUnits="userSpaceOnUse"><stop offset=".608" class="zh7074qmj"/><stop offset=".964" class="n350nobim"/></linearGradient><linearGradient id="ix12tuc" x1="10.83" x2="10.83" y1="6" y2="24.465" gradientUnits="userSpaceOnUse"><stop class="iiy98zb0p"/><stop offset=".479" class="vavd6bc0u"/></linearGradient><linearGradient id="igRllSc" x1="21.2" x2="21.2" y1="6.02" y2="24.465" gradientUnits="userSpaceOnUse"><stop class="iiy98zb0p"/><stop offset=".535" class="vavd6bc0u"/></linearGradient><linearGradient id="is3t01O" x1="17.625" x2="17.407" y1="10.781" y2="19.531" gradientUnits="userSpaceOnUse"><stop class="wtcdoebom"/><stop offset="1" class="rigieu9ov"/></linearGradient><linearGradient id="i5yZ6Xc" x1="10.161" x2="11.059" y1="8.045" y2="7.95" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="ilCnnQc" x1="10.509" x2="11.311" y1="7.857" y2="7.772" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iVBPnAc" x1="10.989" x2="10.93" y1="8.464" y2="7.892" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="iC2iByb" x1="16.383" x2="17.289" y1="12.982" y2="13.067" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="i2qoomd" x1="16.683" x2="17.469" y1="12.838" y2="12.912" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="i1vgEhd" x1="17.055" x2="17.101" y1="13.414" y2="12.874" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="iRB3Txb" x1="27.486" x2="28.285" y1="18.633" y2="18.706" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iilfnOe" x1="27.893" x2="28.624" y1="18.372" y2="18.439" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iNYLSrb" x1="28.238" x2="28.283" y1="18.917" y2="18.405" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="iUBS66c" x1="22.732" x2="23.681" y1="8.164" y2="8.064" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="ikZqsye" x1="23.226" x2="24.07" y1="7.882" y2="7.793" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="i3rZnDu" x1="23.731" x2="23.627" y1="8.522" y2="7.866" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="iCg3R4b" x1="3.859" x2="4.986" y1="10.922" y2="10.805" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iu17gNc" x1="4.248" x2="5.375" y1="10.672" y2="10.555" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="i1xojfd" x1="4.922" x2="4.836" y1="11.539" y2="10.723" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="izSvEvc" x1="12.834" x2="14.308" y1="14.466" y2="14.156" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="ikGtMRc" x1="13.57" x2="14.944" y1="14.078" y2="13.79" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iDCwnGc" x1="14.578" x2="14.322" y1="14.992" y2="14.031" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="iww3Dfc" x1="26.844" x2="28.727" y1="15.515" y2="15.553" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iZM00hb" x1="27.457" x2="29.11" y1="15.143" y2="15.176" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iGtBzye" x1="28.219" x2="28.256" y1="16.016" y2="15.095" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="iNnRhyc" x1="9.126" x2="10.543" y1="26.421" y2="26.116" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="if1hLPA" x1="9.659" x2="11.076" y1="26.076" y2="25.77" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="iSbbGKz" x1="10.609" x2="10.447" y1="26.938" y2="26.027" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="ipZ6dGd" x1="19.052" x2="20.084" y1="26.34" y2="26.672" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset="1" class="gx0lcnnhc"/></linearGradient><linearGradient id="iFExQFI" x1="19.445" x2="20.477" y1="26.133" y2="26.465" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset="1" class="gx0lcnnhc"/></linearGradient><linearGradient id="ir2vHgJ" x1="19.656" x2="19.882" y1="27.142" y2="26.544" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><linearGradient id="iIxbeIc" x1="23.326" x2="24.271" y1="22.726" y2="22.49" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="ipVw6Rb" x1="23.797" x2="24.741" y1="22.438" y2="22.201" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="i7hDSco" x1="24.489" x2="24.262" y1="23.032" y2="22.301" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".701" class="nlu07zb2i"/></linearGradient><linearGradient id="ioOu3vd" x1="5.721" x2="6.385" y1="22.918" y2="22.85" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="ilixNve" x1="6.086" x2="6.75" y1="22.699" y2="22.632" gradientUnits="userSpaceOnUse"><stop class="srfnx07hd"/><stop offset=".279" class="x1_3q7b-d"/><stop offset=".55" class="jcis-psqo"/><stop offset=".882" class="gx0lcnnhc"/></linearGradient><linearGradient id="idoGdae" x1="6.452" x2="6.431" y1="23.109" y2="22.73" gradientUnits="userSpaceOnUse"><stop offset=".436" class="lo06ij6ge"/><stop offset=".634" class="nlu07zb2i"/></linearGradient><radialGradient id="i1H13xe" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.6874 -14.8553 0 15.98 15.313)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="aml3ifbpz"/><stop offset=".69" class="yjw6ngb8f"/><stop offset=".84" class="j77bb7vcw"/><stop offset=".902" class="hujdj_bjt"/><stop offset="1" class="ax1u8wb2k"/></radialGradient><radialGradient id="iPtMmBe" cx="0" cy="0" r="1" gradientTransform="rotate(132.919 2.39 13.715)scale(14.7769 22.8662)" gradientUnits="userSpaceOnUse"><stop offset=".503" class="l2zblrd6d"/><stop offset=".581" class="fwjzjwbds"/></radialGradient><radialGradient id="iSl8d6c" cx="0" cy="0" r="1" gradientTransform="rotate(103.561 5.469 18.837)scale(6.3971 2.57251)" gradientUnits="userSpaceOnUse"><stop offset=".589" class="pxcn6lbar"/><stop offset=".823" class="l63nw7bel"/><stop offset="1" class="iogjcvrmq"/></radialGradient><radialGradient id="i0V1E5m" cx="0" cy="0" r="1" gradientTransform="rotate(115.257 9.181 17.824)scale(8.56917 2.76512)" gradientUnits="userSpaceOnUse"><stop class="n-n2d-bre"/><stop offset=".547" class="jncawth0m"/><stop offset="1" class="mrlj1xt3d"/></radialGradient><radialGradient id="i5uR2ib" cx="0" cy="0" r="1" gradientTransform="matrix(-.15623 2.6875 -5.70874 -.33186 24.563 23.406)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="mt-7cqbgl"/><stop offset="1" class="t1h6u8bus"/></radialGradient><radialGradient id="i7ZTzCb" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 2.21875 -3.98336 .84155 8.156 23)" gradientUnits="userSpaceOnUse"><stop offset=".549" class="h71wajw4x"/><stop offset="1" class="vpno3bbhk"/></radialGradient><radialGradient id="i6YBfoe" cx="0" cy="0" r="1" gradientTransform="rotate(95.983 -.004 11.882)scale(9.42635 9.29082)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="il4hsc71x"/><stop offset=".597" class="xd0ikhb1n"/></radialGradient><radialGradient id="iR3EQje" cx="0" cy="0" r="1" gradientTransform="matrix(5.875 7.75 -7.9798 6.04921 11.625 14.438)" gradientUnits="userSpaceOnUse"><stop offset=".791" class="spq9rtbwn"/><stop offset=".937" class="fqxccbbut"/></radialGradient><radialGradient id="iiaQs9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17477 9.9375 -11.34172 -1.34078 22.376 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="d10b9abbz"/><stop offset=".524" class="bm4zk8-rc"/></radialGradient><radialGradient id="iyBr46b" cx="0" cy="0" r="1" gradientTransform="rotate(100.438 7.452 15.2)scale(14.0734 18.2619)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="uo2i71bny"/><stop offset=".819" class="yss09dbiy"/><stop offset=".951" class="o0aneobxc"/></radialGradient><radialGradient id="if2IOSd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46875 1 -.95413 -2.3555 29.563 21.969)" gradientUnits="userSpaceOnUse"><stop class="vhjcx-b5k"/><stop offset="1" class="lg_nz1saz"/></radialGradient><radialGradient id="iR8nzAd" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 .78125 -1.32315 .10585 29.125 21.938)" gradientUnits="userSpaceOnUse"><stop class="qdpejqt4c"/><stop offset="1" class="rdgb2oexq"/></radialGradient><radialGradient id="iQb11jb" cx="0" cy="0" r="1" gradientTransform="matrix(14.31254 6.31974 -5.26618 11.92649 24.375 15.243)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="enb1mtb4o"/><stop offset=".749" class="cxe_p58cj"/></radialGradient><radialGradient id="ioT0Vle" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 6.9375 -15.2827 4.26813 9.188 17.875)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="bd8fzlg2m"/><stop offset=".813" class="y058ac4sn"/></radialGradient><radialGradient id="i2ehxJc" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -.1875 .33465 8.03167 .625 22.25)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="o6kauwbxp"/><stop offset=".887" class="wy2ce_bhg"/></radialGradient><radialGradient id="ih8PlFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.78821 -.9657 0 16.143 14.993)" gradientUnits="userSpaceOnUse"><stop class="t_1cpdbiq"/><stop offset=".955" class="ylxr1ovwo"/></radialGradient><filter id="iycQawb" width="10.878" height="7.542" x="19.043" y="5.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".5"/></filter><filter id="ia1k7zU" width="5.541" height="11.977" x="2.599" y="11.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".5"/></filter><filter id="iCMF8Ae" width="4.297" height="10.375" x="15.781" y="10.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".5"/></filter><filter id="in8jmAc" width="1.99" height="1.999" x="9.661" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="iGeoExd" width="2.013" height="2.026" x="15.883" y="11.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="i2JbdXb" width="1.893" height="1.921" x="26.986" y="17.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="iYyIyMs" width="2.045" height="2.057" x="22.232" y="7.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="iXW1F7d" width="2.241" height="2.274" x="3.359" y="9.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="iCtHGOE" width="2.836" height="2.837" x="12.266" y="12.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="izpcoFo" width="3.069" height="3.061" x="26.267" y="13.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="iYYguxb" width="2.77" height="2.726" x="8.56" y="24.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="ibgMsad" width="2.326" height="2.348" x="18.359" y="25.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="iq3jPre" width="2.182" height="2.183" x="22.778" y="21.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="ieWI9Xd" width="1.731" height="1.768" x="5.221" y="22.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter><filter id="imyQzib" width="2.277" height="4.688" x="15.004" y="12.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29008" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pretzel" /></template>
<style>
.aml3ifbpz {
  stop-color: var(--svg-color--f48736, #F48736);
}

.ax1u8wb2k {
  stop-color: var(--svg-color--b94e5d, #B94E5D);
}

.bd8fzlg2m {
  stop-color: var(--svg-color--ba5a5a, #BA5A5A);
  stop-opacity: 0;
}

.be5qqsxzd {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M23.29 22.455a.25.25 0 0 1 .163-.313l.479-.133a.23.23 0 0 1 .218.047c.093.082.179.172.212.224c.041.067.089.445.093.478v.005c.02.133-.012.211-.138.253l-.012.005c-.054.02-.45.166-.553.162c-.1-.005-.221-.11-.313-.237a.2.2 0 0 1-.034-.072z");
}

.bm4zk8-rc {
  stop-color: var(--svg-color--cc7235, #CC7235);
  stop-opacity: 0;
}

.cfswfcc_s {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M6.815 22.49a.177.177 0 0 0-.163-.183l-.288-.005a.23.23 0 0 0-.202.108a1 1 0 0 0-.072.15c-.015.053.023.312.027.34v.004c.013.092.047.139.134.146l.014.001c.047.005.32.033.385.012c.062-.02.119-.107.155-.205a.2.2 0 0 0 .012-.076z");
}

.connkzb_i {
  d: path("M10.609 7.576a.25.25 0 0 1 .31-.17l.294.086a.25.25 0 0 1 .17.31l-.09.306a.25.25 0 0 1-.31.17l-.294-.086a.25.25 0 0 1-.17-.31z");
}

.cxe_p58cj {
  stop-color: var(--svg-color--d57821, #D57821);
}

.czhnbxqgu {
  fill: var(--svg-color--d28041, #D28041);
  d: path("M10.273 7.73a.28.28 0 0 1 .347-.19l.33.097a.28.28 0 0 1 .19.347l-.1.342a.28.28 0 0 1-.348.19l-.33-.096a.28.28 0 0 1-.19-.347z");
}

.d10b9abbz {
  stop-color: var(--svg-color--ca723b, #CA723B);
}

.e_set-rzf {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M10.75 25.846c-.038-.224-.339-.466-.567-.427l-.82.125c-.228.04-.334.278-.296.503l.085.62a.4.4 0 0 0 .152.261c.066.05.131.095.219.151a.4.4 0 0 0 .288.055l.656-.129c.228-.04.395-.24.358-.465z");
}

.enb1mtb4o {
  stop-color: var(--svg-color--d27d1f, #D27D1F);
  stop-opacity: 0;
}

.euoi8w51b {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M10.273 7.73a.28.28 0 0 1 .347-.19l.33.097a.28.28 0 0 1 .19.347l-.1.342a.28.28 0 0 1-.348.19l-.33-.096a.28.28 0 0 1-.19-.347z");
}

.ff2clgpop {
  d: path("M19.032 26.264a.4.4 0 0 1 .512-.24l.378.136a.4.4 0 0 1 .24.512l-.15.412a.4.4 0 0 1-.512.24l-.377-.136a.4.4 0 0 1-.24-.512z");
}

.fhncxgd-h {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M10.609 7.576a.25.25 0 0 1 .31-.17l.294.086a.25.25 0 0 1 .17.31l-.09.306a.25.25 0 0 1-.31.17l-.294-.086a.25.25 0 0 1-.17-.31z");
}

.fp4z79ipc {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M11.283 25.501c-.038-.225-.339-.467-.567-.427l-.82.124c-.228.04-.334.279-.296.503l.085.622a.4.4 0 0 0 .152.26c.066.05.131.094.219.151a.4.4 0 0 0 .288.055l.656-.13c.228-.039.395-.24.358-.465z");
}

.fqxccbbut {
  stop-color: var(--svg-color--c58531, #C58531);
}

.ft5dv1b6b {
  fill: none;
}

.fupouwgsb {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M19.425 26.057a.4.4 0 0 1 .513-.24l.377.137a.4.4 0 0 1 .24.512l-.149.411a.4.4 0 0 1-.512.24l-.377-.136a.4.4 0 0 1-.24-.512z");
}

.fwjzjwbds {
  stop-color: var(--svg-color--d77e31, #D77E31);
}

.g7c30hbkx {
  d: path("M23.29 22.455a.25.25 0 0 1 .163-.313l.479-.133a.23.23 0 0 1 .218.047c.093.082.179.172.212.224c.041.067.089.445.093.478v.005c.02.133-.012.211-.138.253l-.012.005c-.054.02-.45.166-.553.162c-.1-.005-.221-.11-.313-.237a.2.2 0 0 1-.034-.072z");
}

.gk8j6db1f {
  fill: var(--svg-color--e38924, #E38924);
  d: path("M22.736 8.018a.28.28 0 0 1 .23-.325l.41-.07a.28.28 0 0 1 .324.229l.073.424a.28.28 0 0 1-.229.324l-.41.071a.28.28 0 0 1-.325-.229z");
}

.gttumh0rn {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M27.924 18.163a.25.25 0 0 1 .273-.226l.287.028a.25.25 0 0 1 .225.273l-.03.315a.25.25 0 0 1-.273.225l-.287-.027a.25.25 0 0 1-.225-.273z");
}

.gx_q__y7w {
  d: path("M22.736 8.018a.28.28 0 0 1 .23-.325l.41-.07a.28.28 0 0 1 .324.229l.073.424a.28.28 0 0 1-.229.324l-.41.071a.28.28 0 0 1-.325-.229z");
}

.gx0lcnnhc {
  stop-color: var(--svg-color--f5f0ff, #F5F0FF);
}

.h5yeq_p8o {
  fill: var(--svg-color--ffa053, #FFA053);
  d: path("M4.422 12.297c-1.914 2.601 0 8.203.828 9.234c.937.584 2.631 1.296 1.531.07c-1.375-1.53-2.203-5.492-2.36-9.304");
}

.h71wajw4x {
  stop-color: var(--svg-color--d84004, #D84004);
}

.h9cc7jbkr {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M26.769 14.92c.017-.281.35-.622.632-.605l1.01.037c.282.016.44.295.424.577l-.024.796a.45.45 0 0 1-.136.31a5 5 0 0 1-.27.238a.45.45 0 0 1-.321.1l-.822-.066c-.282-.016-.51-.24-.494-.522z");
}

.hav-7ub9w {
  d: path("M11.283 25.501c-.038-.225-.339-.467-.567-.427l-.82.124c-.228.04-.334.279-.296.503l.085.622a.4.4 0 0 0 .152.26c.066.05.131.094.219.151a.4.4 0 0 0 .288.055l.656-.13c.228-.039.395-.24.358-.465z");
}

.hujdj_bjt {
  stop-color: var(--svg-color--ee6949, #EE6949);
}

.hxp0gjv0e {
  d: path("M26.769 14.92c.017-.281.35-.622.632-.605l1.01.037c.282.016.44.295.424.577l-.024.796a.45.45 0 0 1-.136.31a5 5 0 0 1-.27.238a.45.45 0 0 1-.321.1l-.822-.066c-.282-.016-.51-.24-.494-.522z");
}

.i97awtjzh {
  cx: 16.123px;
  cy: 14.922px;
  fill: var(--svg-color--bd3e03, #BD3E03);
  rx: 0.56px;
  ry: 2.078px;
}

.iasyujhyu {
  d: path("M3.861 10.74a.4.4 0 0 1 .36-.436l.4-.038a.4.4 0 0 1 .436.36l.041.435a.4.4 0 0 1-.36.437l-.399.038a.4.4 0 0 1-.436-.36z");
}

.iiy98zb0p {
  stop-color: var(--svg-color--fdb221, #FDB221);
}

.il4hsc71x {
  stop-color: var(--svg-color--c46940, #C46940);
}

.iogjcvrmq {
  stop-color: var(--svg-color--fa833b, #FA833B);
  stop-opacity: 0;
}

.ixa-v4b4p {
  d: path("M10.273 7.73a.28.28 0 0 1 .347-.19l.33.097a.28.28 0 0 1 .19.347l-.1.342a.28.28 0 0 1-.348.19l-.33-.096a.28.28 0 0 1-.19-.347z");
}

.j2fmtrbdy {
  d: path("M27.924 18.163a.25.25 0 0 1 .273-.226l.287.028a.25.25 0 0 1 .225.273l-.03.315a.25.25 0 0 1-.273.225l-.287-.027a.25.25 0 0 1-.225-.273z");
}

.j77bb7vcw {
  stop-color: var(--svg-color--ff6a0c, #FF6A0C);
}

.jcis-psqo {
  stop-color: var(--svg-color--d0d0ee, #D0D0EE);
}

.jh4yexyss {
  fill: var(--svg-color--c9731b, #C9731B);
  d: path("M3.861 10.74a.4.4 0 0 1 .36-.436l.4-.038a.4.4 0 0 1 .436.36l.041.435a.4.4 0 0 1-.36.437l-.399.038a.4.4 0 0 1-.436-.36z");
}

.jncawth0m {
  stop-color: var(--svg-color--ff7c3e, #FF7C3E);
}

.k74venbek {
  fill: var(--svg-color--ffd557, #FFD557);
  d: path("M28.921 12.17C25.117 7.938 23 7.367 20.045 7.13c-.063-.511 1.233-.52 1.702-.494c3.782.21 6.256 2.955 7.174 5.534");
}

.khnh02bwl {
  stop-color: var(--svg-color--f66f3f, #F66F3F);
}

.l2zblrd6d {
  stop-color: var(--svg-color--d8631d, #D8631D);
  stop-opacity: 0;
}

.l63nw7bel {
  stop-color: var(--svg-color--fa833b, #FA833B);
}

.lg_nz1saz {
  stop-color: var(--svg-color--ff982e, #FF982E);
  stop-opacity: 0;
}

.llukrjbie {
  d: path("M10.75 25.846c-.038-.224-.339-.466-.567-.427l-.82.125c-.228.04-.334.278-.296.503l.085.62a.4.4 0 0 0 .152.261c.066.05.131.095.219.151a.4.4 0 0 0 .288.055l.656-.129c.228-.04.395-.24.358-.465z");
}

.lo06ij6ge {
  stop-color: var(--svg-color--bdb8fe, #BDB8FE);
}

.lojjlyvyt {
  fill: var(--svg-color--e4673f, #E4673F);
  d: path("M6.45 22.709a.177.177 0 0 0-.164-.183l-.288-.005a.23.23 0 0 0-.201.108a1 1 0 0 0-.073.15c-.015.053.023.312.027.34l.001.004c.012.092.047.139.134.146h.013c.047.006.321.033.385.012c.062-.02.119-.107.155-.204a.2.2 0 0 0 .013-.076z");
}

.mrlj1xt3d {
  stop-color: var(--svg-color--ff962e, #FF962E);
  stop-opacity: 0;
}

.mt-7cqbgl {
  stop-color: var(--svg-color--ca3401, #CA3401);
}

.n-n2d-bre {
  stop-color: var(--svg-color--ff952e, #FF952E);
}

.n350nobim {
  stop-color: var(--svg-color--ff853d, #FF853D);
  stop-opacity: 0;
}

.n6d4a_b5j {
  d: path("M16.08 15.475c0 4.06-6.779 5.285-6.849 5.295h-.02c-2.48.445-5.02-.089-5.05-.089c-.96-.207-1.91.386-2.12 1.334s.39 1.887 1.35 2.095c.09.02 1.65.355 3.67.355c.86 0 1.81-.059 2.77-.227c.2-.03 2.42-.435 4.66-1.57c3.349-1.7 5.129-4.18 5.129-7.183c0-.297.005-.598.005-.894h-3.52c0-.006-.025.629-.025.884");
}

.nlu07zb2i {
  stop-color: var(--svg-color--bdb8fe, #BDB8FE);
  stop-opacity: 0;
}

.o0aneobxc {
  stop-color: var(--svg-color--c8604b, #C8604B);
}

.o6kauwbxp {
  stop-color: var(--svg-color--bb5f2b, #BB5F2B);
}

.oaznyqb1b {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M23.76 22.167a.25.25 0 0 1 .163-.314l.48-.133a.23.23 0 0 1 .217.047c.093.082.18.172.212.224c.042.068.09.445.093.479l.001.005c.019.132-.013.21-.138.253l-.013.004c-.054.02-.45.167-.552.162c-.101-.005-.222-.11-.313-.237a.2.2 0 0 1-.034-.072z");
}

.oustc6n3n {
  fill: var(--svg-color--cf6834, #CF6834);
  d: path("M26.769 14.92c.017-.281.35-.622.632-.605l1.01.037c.282.016.44.295.424.577l-.024.796a.45.45 0 0 1-.136.31a5 5 0 0 1-.27.238a.45.45 0 0 1-.321.1l-.822-.066c-.282-.016-.51-.24-.494-.522z");
}

.p9z09nebo {
  d: path("M12.771 14.194c-.043-.233.161-.578.394-.62l.83-.172c.234-.043.419.152.461.385l.136.635a.42.42 0 0 1-.055.314c-.045.07-.09.134-.15.217a.42.42 0 0 1-.272.164l-.665.108c-.233.043-.464-.094-.507-.327z");
}

.pt0qz7beh {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M19.032 26.264a.4.4 0 0 1 .512-.24l.378.136a.4.4 0 0 1 .24.512l-.15.412a.4.4 0 0 1-.512.24l-.377-.136a.4.4 0 0 1-.24-.512z");
}

.pwwpxss9w {
  d: path("M16.719 12.605a.25.25 0 0 1 .272-.225l.345.033a.25.25 0 0 1 .225.272l-.034.357a.25.25 0 0 1-.273.226l-.344-.033a.25.25 0 0 1-.225-.273z");
}

.pxcn6lbar {
  stop-color: var(--svg-color--dd7b39, #DD7B39);
}

.qdpejqt4c {
  stop-color: var(--svg-color--ffa857, #FFA857);
}

.qej73rwzq {
  d: path("M27.52 18.404a.273.273 0 0 1 .298-.246l.314.03c.15.015.26.148.246.298l-.033.345a.273.273 0 0 1-.298.246l-.314-.03a.273.273 0 0 1-.246-.298z");
}

.qf6vbiben {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M27.391 14.621c.015-.247.308-.546.555-.532l.886.033c.247.014.386.259.372.506l-.02.699a.4.4 0 0 1-.12.272a5 5 0 0 1-.236.209a.4.4 0 0 1-.283.088l-.721-.058c-.248-.015-.448-.211-.434-.459z");
}

.qm-3flptb {
  fill: var(--svg-color--da5d22, #DA5D22);
  d: path("M23.29 22.455a.25.25 0 0 1 .163-.313l.479-.133a.23.23 0 0 1 .218.047c.093.082.179.172.212.224c.041.067.089.445.093.478v.005c.02.133-.012.211-.138.253l-.012.005c-.054.02-.45.166-.553.162c-.1-.005-.221-.11-.313-.237a.2.2 0 0 1-.034-.072z");
}

.r0p__dbbg {
  d: path("M23.23 7.751a.25.25 0 0 1 .204-.289l.365-.062a.25.25 0 0 1 .289.203l.065.378a.25.25 0 0 1-.204.289l-.365.063a.25.25 0 0 1-.289-.204z");
}

.rbrm_frqe {
  stop-color: var(--svg-color--f28948, #F28948);
}

.rc1h76bnl {
  d: path("M15.98 29C8.361 29 2.162 22.875 2.162 15.346c0-.336.033-.998.08-1.35c0 0 2.7-.905 3.54 0a20 20 0 0 0-.048 1.35c0 5.612 4.567 10.176 10.246 10.176s10.3-4.564 10.3-10.176c0-.307-.026-.905-.026-.905c.561-1.1 2.786-1.04 3.566-.066c0 0-.021.549-.021.971c0 7.529-6.2 13.654-13.819 13.654");
}

.rdgb2oexq {
  stop-color: var(--svg-color--ffa958, #FFA958);
  stop-opacity: 0;
}

.rigieu9ov {
  stop-color: var(--svg-color--ff9a41, #FF9A41);
}

.rxynugb5r {
  d: path("M19.425 26.057a.4.4 0 0 1 .513-.24l.377.137a.4.4 0 0 1 .24.512l-.149.411a.4.4 0 0 1-.512.24l-.377-.136a.4.4 0 0 1-.24-.512z");
}

.s_kg18brx {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M12.771 14.194c-.043-.233.161-.578.394-.62l.83-.172c.234-.043.419.152.461.385l.136.635a.42.42 0 0 1-.055.314c-.045.07-.09.134-.15.217a.42.42 0 0 1-.272.164l-.665.108c-.233.043-.464-.094-.507-.327z");
}

.s709ah40z {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M6.45 22.709a.177.177 0 0 0-.164-.183l-.288-.005a.23.23 0 0 0-.201.108a1 1 0 0 0-.073.15c-.015.053.023.312.027.34l.001.004c.012.092.047.139.134.146h.013c.047.006.321.033.385.012c.062-.02.119-.107.155-.204a.2.2 0 0 0 .013-.076z");
}

.sid9_xdxj {
  cx: 16.143px;
  cy: 14.993px;
  rx: 0.639px;
  ry: 1.844px;
}

.soolqkb6q {
  fill: var(--svg-color--e86642, #E86642);
  d: path("M27.52 18.404a.273.273 0 0 1 .298-.246l.314.03c.15.015.26.148.246.298l-.033.345a.273.273 0 0 1-.298.246l-.314-.03a.273.273 0 0 1-.246-.298z");
}

.spq9rtbwn {
  stop-color: var(--svg-color--bf8340, #BF8340);
  stop-opacity: 0;
}

.srfnx07hd {
  stop-color: var(--svg-color--9393af, #9393AF);
}

.t_1cpdbiq {
  stop-color: var(--svg-color--d34f00, #D34F00);
}

.t1h6u8bus {
  stop-color: var(--svg-color--c85f3e, #C85F3E);
  stop-opacity: 0;
}

.tb8i4ngwl {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M4.25 10.49a.4.4 0 0 1 .36-.436l.4-.038a.4.4 0 0 1 .436.36l.041.435a.4.4 0 0 1-.36.437l-.399.038a.4.4 0 0 1-.436-.36z");
}

.te8ien3oi {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M16.719 12.605a.25.25 0 0 1 .272-.225l.345.033a.25.25 0 0 1 .225.272l-.034.357a.25.25 0 0 1-.273.226l-.344-.033a.25.25 0 0 1-.225-.273z");
}

.u4y_3o-7a {
  d: path("M16.423 12.713a.29.29 0 0 1 .315-.26l.397.039a.29.29 0 0 1 .26.314l-.04.412a.29.29 0 0 1-.314.26l-.398-.039a.29.29 0 0 1-.259-.314z");
}

.u6r73qbri {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M16.423 12.713a.29.29 0 0 1 .315-.26l.397.039a.29.29 0 0 1 .26.314l-.04.412a.29.29 0 0 1-.314.26l-.398-.039a.29.29 0 0 1-.259-.314z");
}

.ufbl8wvxk {
  d: path("M13.512 13.824c-.04-.217.15-.538.367-.578l.773-.16c.218-.04.39.142.43.36l.127.591c.021.1.004.206-.052.293a4 4 0 0 1-.14.202a.4.4 0 0 1-.253.153l-.62.1c-.217.04-.432-.087-.472-.305z");
}

.uo2i71bny {
  stop-color: var(--svg-color--fd8b49, #FD8B49);
  stop-opacity: 0;
}

.uqjwnc3tu {
  fill: var(--svg-color--e56e16, #E56E16);
  d: path("M16.423 12.713a.29.29 0 0 1 .315-.26l.397.039a.29.29 0 0 1 .26.314l-.04.412a.29.29 0 0 1-.314.26l-.398-.039a.29.29 0 0 1-.259-.314z");
}

.usumdabyl {
  d: path("M19.078 14.672c0-1.656-.687-2.985-1.062-3.516c-.375.406-.578.766-1.125 1.125c2.187 2.469 1.047 4.5-.11 7.25c1.5-1.312 2.297-2.484 2.297-4.86");
}

.v-dxfwb2x {
  d: path("M6.45 22.709a.177.177 0 0 0-.164-.183l-.288-.005a.23.23 0 0 0-.201.108a1 1 0 0 0-.073.15c-.015.053.023.312.027.34l.001.004c.012.092.047.139.134.146h.013c.047.006.321.033.385.012c.062-.02.119-.107.155-.204a.2.2 0 0 0 .013-.076z");
}

.v1g9dtsxo {
  d: path("M23.76 22.167a.25.25 0 0 1 .163-.314l.48-.133a.23.23 0 0 1 .217.047c.093.082.18.172.212.224c.042.068.09.445.093.479l.001.005c.019.132-.013.21-.138.253l-.013.004c-.054.02-.45.167-.552.162c-.101-.005-.222-.11-.313-.237a.2.2 0 0 1-.034-.072z");
}

.vavd6bc0u {
  stop-color: var(--svg-color--f9833b, #F9833B);
}

.vggl2gbmj {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M23.23 7.751a.25.25 0 0 1 .204-.289l.365-.062a.25.25 0 0 1 .289.203l.065.378a.25.25 0 0 1-.204.289l-.365.063a.25.25 0 0 1-.289-.204z");
}

.vhjcx-b5k {
  stop-color: var(--svg-color--ff9b2f, #FF9B2F);
}

.vl9rj1bbt {
  fill: var(--svg-color--c66a25, #C66A25);
  d: path("M12.771 14.194c-.043-.233.161-.578.394-.62l.83-.172c.234-.043.419.152.461.385l.136.635a.42.42 0 0 1-.055.314c-.045.07-.09.134-.15.217a.42.42 0 0 1-.272.164l-.665.108c-.233.043-.464-.094-.507-.327z");
}

.vpno3bbhk {
  stop-color: var(--svg-color--d44814, #D44814);
  stop-opacity: 0;
}

.vtn-slbby {
  d: path("M27.391 14.621c.015-.247.308-.546.555-.532l.886.033c.247.014.386.259.372.506l-.02.699a.4.4 0 0 1-.12.272a5 5 0 0 1-.236.209a.4.4 0 0 1-.283.088l-.721-.058c-.248-.015-.448-.211-.434-.459z");
}

.w221xkbdh {
  fill: var(--svg-color--c24e45, #C24E45);
  d: path("M10.75 25.846c-.038-.224-.339-.466-.567-.427l-.82.125c-.228.04-.334.278-.296.503l.085.62a.4.4 0 0 0 .152.261c.066.05.131.095.219.151a.4.4 0 0 0 .288.055l.656-.129c.228-.04.395-.24.358-.465z");
}

.wtcdoebom {
  stop-color: var(--svg-color--ffb353, #FFB353);
}

.wy2ce_bhg {
  stop-color: var(--svg-color--c16024, #C16024);
  stop-opacity: 0;
}

.wy678rbza {
  d: path("M4.25 10.49a.4.4 0 0 1 .36-.436l.4-.038a.4.4 0 0 1 .436.36l.041.435a.4.4 0 0 1-.36.437l-.399.038a.4.4 0 0 1-.436-.36z");
}

.x1_3q7b-d {
  stop-color: var(--svg-color--bebddf, #BEBDDF);
}

.xd0ikhb1n {
  stop-color: var(--svg-color--ca7028, #CA7028);
  stop-opacity: 0;
}

.xe9zzkbwa {
  d: path("M24.95 24.466c-.86 0-1.82-.06-2.77-.228h-.02c-.4-.079-9.76-1.966-9.76-8.743v-.87c0-4.742 3.91-8.605 8.71-8.605s8.709 3.863 8.709 8.605h-3.56c0-2.806-2.31-5.098-5.16-5.098c-2.84 0-5.159 2.283-5.159 5.098v.87c0 3.774 6.61 5.246 6.88 5.305c2.47.435 4.999-.089 5.029-.099c.96-.207 1.9.395 2.11 1.344c.21.948-.4 1.877-1.35 2.085c-.08.01-1.64.335-3.66.335");
}

.xhk0g5bbi {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M3.861 10.74a.4.4 0 0 1 .36-.436l.4-.038a.4.4 0 0 1 .436.36l.041.435a.4.4 0 0 1-.36.437l-.399.038a.4.4 0 0 1-.436-.36z");
}

.y058ac4sn {
  stop-color: var(--svg-color--d36851, #D36851);
}

.y1vs2mb8o {
  d: path("M7.081 24.465c-2.02 0-3.58-.326-3.67-.355a1.754 1.754 0 0 1-1.35-2.095c.21-.948 1.16-1.541 2.12-1.334c.02 0 2.57.534 5.05.09h.02c.07-.01 6.85-1.236 6.85-5.296v-.87c0-2.806-2.31-5.098-5.16-5.098c-2.84 0-5.191 2.283-5.191 5.098H2.222C2.222 9.863 6.132 6 10.93 6c4.8 0 8.709 3.863 8.709 8.605v.87c0 2.993-1.77 5.483-5.13 7.182c-2.24 1.136-4.459 1.541-4.659 1.571c-.96.178-1.91.237-2.77.237");
}

.y6f7ww84q {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M22.736 8.018a.28.28 0 0 1 .23-.325l.41-.07a.28.28 0 0 1 .324.229l.073.424a.28.28 0 0 1-.229.324l-.41.071a.28.28 0 0 1-.325-.229z");
}

.yjw6ngb8f {
  stop-color: var(--svg-color--ea6e47, #EA6E47);
}

.ylxr1ovwo {
  stop-color: var(--svg-color--df5d00, #DF5D00);
  stop-opacity: 0;
}

.yss09dbiy {
  stop-color: var(--svg-color--fc8325, #FC8325);
}

.z23vi-bpc {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M13.512 13.824c-.04-.217.15-.538.367-.578l.773-.16c.218-.04.39.142.43.36l.127.591c.021.1.004.206-.052.293a4 4 0 0 1-.14.202a.4.4 0 0 1-.253.153l-.62.1c-.217.04-.432-.087-.472-.305z");
}

.z86dmj94q {
  d: path("M6.815 22.49a.177.177 0 0 0-.163-.183l-.288-.005a.23.23 0 0 0-.202.108a1 1 0 0 0-.072.15c-.015.053.023.312.027.34v.004c.013.092.047.139.134.146l.014.001c.047.005.32.033.385.012c.062-.02.119-.107.155-.205a.2.2 0 0 0 .012-.076z");
}

.zfaxh3bfn {
  fill: var(--svg-color--f88533, #F88533);
  d: path("M16.08 15.475c0 4.06-6.779 5.285-6.849 5.295h-.02c-2.48.445-5.02-.089-5.05-.089c-.96-.207-1.91.386-2.12 1.334s.39 1.887 1.35 2.095c.09.02 1.65.355 3.67.355c.86 0 1.81-.059 2.77-.227c.2-.03 2.42-.435 4.66-1.57c3.349-1.7 5.129-4.18 5.129-7.183c0-.297.005-.598.005-.894h-3.52c0-.006-.025.629-.025.884");
}

.zh7074qmj {
  stop-color: var(--svg-color--fb8e39, #FB8E39);
}

.zkiztz5oe {
  fill: var(--svg-color--d94e21, #D94E21);
  d: path("M19.032 26.264a.4.4 0 0 1 .512-.24l.378.136a.4.4 0 0 1 .24.512l-.15.412a.4.4 0 0 1-.512.24l-.377-.136a.4.4 0 0 1-.24-.512z");
}

.zxy-3-e6d {
  fill: var(--svg-color--e1e0f8, #E1E0F8);
  d: path("M27.52 18.404a.273.273 0 0 1 .298-.246l.314.03c.15.015.26.148.246.298l-.033.345a.273.273 0 0 1-.298.246l-.314-.03a.273.273 0 0 1-.246-.298z");
}

</style>
