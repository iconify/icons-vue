<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iaBNSmv)" class="f0sz96v9r"/><path fill="url(#igH2a8b)" class="f0sz96v9r"/><path fill="url(#i9KFWTd)" class="f0sz96v9r"/><path fill="url(#iNxl2kb)" class="f0sz96v9r"/><path fill="url(#iHOuBQd)" class="f0sz96v9r"/><path fill="url(#i8Vf7fd)" class="f0sz96v9r"/><path fill="url(#iAbth5c)" class="e2_wenbdi"/><path fill="url(#ipNloxS)" class="e2_wenbdi"/><path fill="url(#ibKH0Mb)" class="hqe5c4bli"/><path fill="url(#ihvFh8c)" class="hqe5c4bli"/><g filter="url(#ivLVywd)"><path class="drf1ulbyy"/><path class="tedvzacni"/></g><g filter="url(#i45yKRc)"><path class="tnnw6ib6s"/><path class="d7dg5k-bm"/></g><path class="ud61_vz9g"/><path fill="url(#i0FDate)" class="iu8kp3ahw"/><path fill="url(#i3SQbDe)" class="iu8kp3ahw"/><path fill="url(#iyxEWTc)" class="iu8kp3ahw"/><g filter="url(#icaK6ue)"><path fill="url(#i2laqUd)" class="d3e9_irck"/><path fill="url(#iIKZtAe)" class="d3e9_irck"/><path fill="url(#iHMIXWh)" class="d3e9_irck"/></g><path fill="url(#ir9X3VR)" class="f8xv78wwh"/><path fill="url(#iDre4dc)" class="f8xv78wwh"/><path fill="url(#iZFhrYb)" class="f8xv78wwh"/><path fill="url(#ikKD89c)" class="f8xv78wwh"/><path fill="url(#imfQuDc)" class="f8xv78wwh"/><g filter="url(#ixaHyrc)"><path fill="url(#io9c6zb)" class="vmhbtsb-a"/><path fill="url(#iIfxIeM)" class="vmhbtsb-a"/><path fill="url(#iUfBlYz)" class="vmhbtsb-a"/><path fill="url(#iCPPbCe)" class="vmhbtsb-a"/></g><path fill="url(#iWzzOub)" class="shgrjqbiz"/><path fill="url(#iAMhepd)" class="shgrjqbiz"/><path fill="url(#ivjzpvb)" class="shgrjqbiz"/><path fill="url(#ieYhBrd)" class="shgrjqbiz"/><path fill="url(#i9lS2bb)" class="shgrjqbiz"/><g filter="url(#iVDkuXb)"><path fill="url(#izukjFZ)" class="rnq8zfbyk"/><path fill="url(#iAyKCmx)" class="rnq8zfbyk"/><path fill="url(#i4fzUHl)" class="rnq8zfbyk"/><path fill="url(#iIDnZSj)" class="rnq8zfbyk"/></g><path fill="url(#iKFImcd)" class="kiolp_-pe"/><path fill="url(#iFCx3ZU)" class="kiolp_-pe"/><path fill="url(#iN3ekpY)" class="kiolp_-pe"/><path fill="url(#iC5o5Kc)" class="kiolp_-pe"/><path fill="url(#imus0Oe)" class="kiolp_-pe"/><g filter="url(#ir2swze)"><path fill="url(#ixg7ckd)" class="swjgceb9v"/><path fill="url(#iYIbosd)" class="swjgceb9v"/><path fill="url(#iS5Q3Vc)" class="swjgceb9v"/><path fill="url(#i9Rg3ZK)" class="swjgceb9v"/></g><path fill="url(#iiYTAZq)" class="kbcpr6bot"/><path fill="url(#iDsARPb)" class="kbcpr6bot"/><path fill="url(#iwVkT9d)" class="kbcpr6bot"/><path fill="url(#iqmAtWc)" class="kbcpr6bot"/><path fill="url(#iSeQN2N)" class="kbcpr6bot"/><g filter="url(#iNjNMvc)"><path fill="url(#ixmFp6b)" class="escp53_pi"/><path fill="url(#ixyyVtb)" class="escp53_pi"/><path fill="url(#iAJYwfd)" class="escp53_pi"/><path fill="url(#i8LvJbd)" class="escp53_pi"/></g><path fill="url(#ionfRCd)" class="c0g3mbbdp"/><path fill="url(#i7EcZvd)" class="c0g3mbbdp"/><path fill="url(#iqIlRze)" class="c0g3mbbdp"/><path fill="url(#iraNcty)" class="c0g3mbbdp"/><g filter="url(#iX998Kd)"><path fill="url(#i8a7U2b)" class="fw-_ge0oq"/></g><g filter="url(#iTn7Pkb)"><path fill="url(#iamWsYd)" class="sgtr8ibeb"/><path fill="url(#iLswA2c)" class="sgtr8ibeb"/></g><g filter="url(#iUsBSkb)"><circle class="d-aoszbpp"/></g><g filter="url(#iQObTHb)"><circle class="j-8m34b2o"/></g><circle fill="url(#iZ3BMQx)" class="kfayvkisl"/><g filter="url(#iOxyajd)"><circle fill="url(#iejUKqO)" class="we5kvqbpm"/><circle fill="url(#iz3N9Og)" class="we5kvqbpm"/></g><ellipse fill="url(#iowGvJd)" class="i5vxhhb9k"/><ellipse fill="url(#ivYFrAJ)" class="i5vxhhb9k"/><ellipse fill="url(#iOgzpGe)" class="i5vxhhb9k"/><circle fill="url(#iLnMLcb)" class="f-t10ph2f"/><g filter="url(#iOEwXMc)"><circle fill="url(#iV5XYMe)" class="a2yqhej6q"/></g><g filter="url(#ivuz4ae)"><circle fill="url(#ia0v8Ae)" class="dijw_ccpd"/></g><g filter="url(#iPYUFAc)"><circle fill="url(#iCyzlsk)" class="wt2jy5jep"/><circle fill="url(#iDcLVOb)" class="wt2jy5jep"/></g><g filter="url(#iUaLCXl)"><circle class="ep1-kbb1x"/><circle fill="url(#imsVYfd)" class="jzifsbrfx"/><circle fill="url(#iN1I6id)" class="jzifsbrfx"/></g><path fill="url(#iH93TiY)" class="uo3cwjh_s"/><path fill="url(#iEdnmOS)" class="uo3cwjh_s"/><path fill="url(#iZBx5Qd)" class="uo3cwjh_s"/><path fill="url(#ifO6V9h)" class="uo3cwjh_s"/><path fill="url(#iyETAFb)" class="uo3cwjh_s"/><path fill="url(#iu4tUKd)" class="uo3cwjh_s"/><path fill="url(#icfNiwc)" class="uo3cwjh_s"/><g filter="url(#iTKATRb)"><path fill="url(#iu03MGe)" class="e52rcizoy"/></g><g filter="url(#itTnfPb)"><path class="c2o8f_bwu"/></g><g filter="url(#iN3OwqL)"><path class="tuulhko3b"/><path fill="url(#icL83jm)" class="aqh6zpbtp"/><path fill="url(#ifoZ1kd)" class="aqh6zpbtp"/><path fill="url(#iHtHVPe)" class="aqh6zpbtp"/><path fill="url(#i42J0fb)" class="aqh6zpbtp"/></g><g filter="url(#ikLcEWO)"><path stroke="url(#iHmfxsQ)" class="axg38cfdd"/></g><path class="k4csq1kxn"/><path class="uakpxk1lj"/><path fill="url(#iYxTaDO)" class="o5mupf-2w"/><path class="p-jh4qrfp"/><g filter="url(#i4JnXNd)"><path class="mnkzj2b2e"/><path fill="url(#iQfCoec)" class="j1ajldk8d"/></g><g filter="url(#ix8UXbe)"><path fill="url(#icUJdbb)" class="lvnq4bd5c"/></g><path class="zq_fy1bcr"/><path fill="url(#iTAQg1c)" class="ivvelbx3d"/><path class="e70edmbwm"/><g filter="url(#iZWpCad)"><path fill="url(#ihMBgzd)" class="fasttccsa"/></g><g filter="url(#i5l35xD)"><ellipse transform="rotate(-27.914 13.54 13.872)" class="t9vbol6ta"/><ellipse fill="url(#iiEP4kb)" transform="rotate(-27.914 13.54 13.872)" class="i8km-wymp"/></g><path fill="url(#iQmtHVd)" class="f3nh8zb0n"/><path fill="url(#iPgftde)" class="auvf1abdy"/><g filter="url(#iX5SJKb)"><path fill="url(#iFbzqEd)" class="cz54lzbgf"/></g><g filter="url(#iDECoRb)"><circle fill="url(#ilMc2me)" class="f19u2wb6f"/><circle fill="url(#ijH8mic)" class="f19u2wb6f"/></g><g filter="url(#ieKh8xd)"><path fill="url(#iOspXqd)" class="e324j6gaq"/><path fill="url(#i6HCwxb)" class="e324j6gaq"/></g><g filter="url(#iz8BpVd)"><circle fill="url(#iHTVxLe)" class="qk8v1bc2n"/><circle fill="url(#iprWAmd)" class="qk8v1bc2n"/></g><circle fill="url(#ia01BWX)" class="v-aq_fb5e"/><circle fill="url(#iNe5Amc)" class="v-aq_fb5e"/><circle fill="url(#iPsaLGe)" class="prxm8ubjj"/><circle fill="url(#ijQY9Cb)" class="prxm8ubjj"/><path fill="url(#iq31Hcc)" class="jqlapeb1l"/><path fill="url(#iovwq8b)" class="jqlapeb1l"/><path fill="url(#igPCvHd)" class="jqlapeb1l"/><path fill="url(#iSEn53b)" class="jqlapeb1l"/><path fill="url(#iwwfhfb)" class="jqlapeb1l"/><path fill="url(#imKujHe)" class="jqlapeb1l"/><path fill="url(#i8FlMae)" class="jqlapeb1l"/><path fill="url(#i8z60vd)" class="jqlapeb1l"/><path fill="url(#irCHEVn)" class="jqlapeb1l"/><path fill="url(#iZDC2xd)" class="jqlapeb1l"/><path fill="url(#iaxQkid)" class="jqlapeb1l"/><g filter="url(#iq40Ivc)"><circle fill="url(#iCJwfdb)" class="jzfasvbbp"/><circle fill="url(#ieNywVb)" class="jzfasvbbp"/></g><g filter="url(#iYBivWd)"><circle fill="url(#i2Kf17d)" class="ldyj_nb1e"/><circle fill="url(#iz0Sw1c)" class="ldyj_nb1e"/></g><g filter="url(#iAJDSse)"><circle fill="url(#iwdleKr)" class="ks0-jgbez"/><circle fill="url(#iTvHkyi)" class="ks0-jgbez"/><circle fill="url(#ia6Q7le)" class="ks0-jgbez"/></g><g filter="url(#iju3Zpb)"><circle fill="url(#iUCPwrb)" class="pimf00m2w"/><circle fill="url(#iC0wJeI)" class="pimf00m2w"/></g><g filter="url(#iNQyXdb)"><circle fill="url(#iZfcJcb)" class="ql2irpb2m"/><circle fill="url(#iubs2De)" class="ql2irpb2m"/></g><g filter="url(#iUy02mc)"><path stroke="url(#igCNT7c)" class="ey-1_lflg"/></g><g filter="url(#i40H1Mc)"><path stroke="url(#iWKQGxe)" class="o_84ttbae"/></g><g filter="url(#iQOIGeb)"><path stroke="url(#iSbcJUc)" class="qp7qzchye"/></g><g filter="url(#iChIxpb)"><circle fill="url(#ifvdSwb)" class="kowfi484h"/><circle fill="url(#iHZGaVd)" class="kowfi484h"/></g><circle fill="url(#iH7TL6c)" class="kowfi484h"/><defs><radialGradient id="iaBNSmv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.02441 -14.994 0 16 21.94)" gradientUnits="userSpaceOnUse"><stop class="qxfkfde9r"/><stop offset="1" class="ehy0pm5vd"/></radialGradient><radialGradient id="igH2a8b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24414 0 0 -14.5244 23.807 29.964)" gradientUnits="userSpaceOnUse"><stop class="heg5bdcwd"/><stop offset="1" class="ryq7ubb8z"/></radialGradient><radialGradient id="i9KFWTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.75 -15.6948 0 16 20.815)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="uv5le6qqz"/><stop offset="1" class="knplocckt"/></radialGradient><radialGradient id="i8Vf7fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.8125 -.53125 0 15.688 26.221)" gradientUnits="userSpaceOnUse"><stop class="lup_unb-i"/><stop offset="1" class="im0aqq9wp"/></radialGradient><radialGradient id="iAbth5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.28332 4.28735 0 8.354 29.67)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="klzc01b5d"/><stop offset="1" class="mdad8vdth"/></radialGradient><radialGradient id="ibKH0Mb" cx="0" cy="0" r="1" gradientTransform="matrix(3.36005 0 0 6.32267 23.847 28.93)" gradientUnits="userSpaceOnUse"><stop class="fq5e2gbsk"/><stop offset="1" class="q4uf8hbdw"/></radialGradient><radialGradient id="iyxEWTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .69531 -2.16649 0 16.006 23.956)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="o_4gny8-z"/><stop offset=".622" class="jrd3jzgth"/></radialGradient><radialGradient id="iIKZtAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 8.241 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iHMIXWh" cx="0" cy="0" r="1" gradientTransform="rotate(-84.161 17.495 8.173)scale(2.35566 2.26902)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="o375d620d"/><stop offset="1" class="tgzndhrni"/></radialGradient><radialGradient id="iZFhrYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 20.687 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="imfQuDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 20.177 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iIfxIeM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 9.261 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iUfBlYz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 8.751 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ivjzpvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 21.707 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="i9lS2bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 21.197 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iAyKCmx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 10.282 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="i4fzUHl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 9.772 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iN3ekpY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 22.727 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="imus0Oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 22.217 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iYIbosd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 11.302 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iS5Q3Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 10.792 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iwVkT9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 23.748 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iSeQN2N" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 23.238 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ixyyVtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 12.322 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iAJYwfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 11.812 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iqIlRze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 24.768 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iraNcty" cx="0" cy="0" r="1" gradientTransform="rotate(-97.511 23.055 1.525)scale(2.28523 2.20118)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="i8a7U2b" cx="0" cy="0" r="1" gradientTransform="matrix(3.09374 -3.6172 12.35097 10.56365 9.4 23.59)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="tjsj1op7o"/><stop offset="1" class="gvudu0-9m"/></radialGradient><radialGradient id="iLswA2c" cx="0" cy="0" r="1" gradientTransform="matrix(3.57813 0 0 3.06696 20.104 22.246)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="mqzky-b6t"/><stop offset="1" class="fnx367bbh"/></radialGradient><radialGradient id="iZ3BMQx" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 2.282 18.291)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="iz3N9Og" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 1.30469 -.7272 -.3919 17.533 21.097)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="trt6sabjd"/><stop offset="1" class="s-qqz8oax"/></radialGradient><radialGradient id="iowGvJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.29688 -4.54924 0 15.994 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="jh_m43_mm"/><stop offset=".676" class="i-1u09bvn"/></radialGradient><radialGradient id="ivYFrAJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.43739 -2.14179 0 15.994 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="vscmudgro"/><stop offset="1" class="lt24i1boi"/></radialGradient><radialGradient id="iOgzpGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.90154 0 0 2.93114 15.413 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="xh-geaczg"/><stop offset="1" class="ekivnb4zj"/></radialGradient><radialGradient id="iLnMLcb" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 3.017 16.73)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="iV5XYMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.574 14.65)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iDcLVOb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.14 14.385)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="imsVYfd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.726 15.472)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iN1I6id" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.767 14.65)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iEdnmOS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.345 13.378)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iZBx5Qd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.783 13.512)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iu4tUKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.18536 -13.2838 0 15.65 12.874)" gradientUnits="userSpaceOnUse"><stop offset=".759" class="txn55m2mi"/><stop offset="1" class="ncq6f9bxg"/></radialGradient><radialGradient id="i42J0fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.325 16.258)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iYxTaDO" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.178 13.968)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iQfCoec" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.95 14.051)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTAQg1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.81 13.968)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iiEP4kb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.745 .436)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQmtHVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.55214 0 0 -1.73962 10.976 13.092)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="mgn2xlbnn"/><stop offset="1" class="rul-_pb0t"/></radialGradient><radialGradient id="iPgftde" cx="0" cy="0" r="1" gradientTransform="matrix(-.7431 .28093 -.77159 -2.04097 21.64 12.712)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="m2l89-bxk"/><stop offset="1" class="lft039jrw"/></radialGradient><radialGradient id="ilMc2me" cx="0" cy="0" r="1" gradientTransform="rotate(130.522 5.587 5.085)scale(1.38839)" gradientUnits="userSpaceOnUse"><stop class="zi727lnsv"/><stop offset="1" class="z1e4imbuu"/></radialGradient><radialGradient id="ijH8mic" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.4922 .26158 .32385 13.08 4.253)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="iOspXqd" cx="0" cy="0" r="1" gradientTransform="rotate(133.204 8.71 7.203)scale(1.58625 1.61077)" gradientUnits="userSpaceOnUse"><stop class="d0pq7p0hl"/><stop offset="1" class="kfhq2vx5n"/></radialGradient><radialGradient id="i6HCwxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.86008 .8467 0 19.227 7.23)" gradientUnits="userSpaceOnUse"><stop class="e6qjesbba"/><stop offset="1" class="btm953brw"/></radialGradient><radialGradient id="iHTVxLe" cx="0" cy="0" r="1" gradientTransform="rotate(128.601 8.882 6.9)scale(1.32441)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="iyq1_fb9e"/><stop offset="1" class="smjt6t9ha"/></radialGradient><radialGradient id="iprWAmd" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.54688 .29064 .30725 19.83 4.175)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="ia01BWX" cx="0" cy="0" r="1" gradientTransform="matrix(.7294 .35293 -.4289 .8864 9.106 9.349)" gradientUnits="userSpaceOnUse"><stop class="oughljbvw"/><stop offset="1" class="fm5egxmlo"/></radialGradient><radialGradient id="iNe5Amc" cx="0" cy="0" r="1" gradientTransform="matrix(.10577 -.86594 .53006 .06475 9.966 10.284)" gradientUnits="userSpaceOnUse"><stop class="ufab9bcqz"/><stop offset="1" class="rgangdc7y"/></radialGradient><radialGradient id="iPsaLGe" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 8.602 11.303)scale(1.55689 2.04215)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="i2r14vbib"/><stop offset="1" class="izxaz-bvs"/></radialGradient><radialGradient id="ijQY9Cb" cx="0" cy="0" r="1" gradientTransform="matrix(.48626 -.41568 .26982 .31564 22.611 9.066)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ceu0gybff"/><stop offset="1" class="owp1j2bwg"/></radialGradient><radialGradient id="iq31Hcc" cx="0" cy="0" r="1" gradientTransform="rotate(99.989 6.91 11.148)scale(5.58466 4.97233)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fwcf4ds6u"/><stop offset="1" class="pg0l0_b5e"/></radialGradient><radialGradient id="iovwq8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.31715 14 0 16.37 12.307)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="o_0wq7b5h"/><stop offset="1" class="nd4srkbik"/></radialGradient><radialGradient id="iSEn53b" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 2.5 -2.641 2.608 9.963 5.745)" gradientUnits="userSpaceOnUse"><stop class="vy-t95buc"/><stop offset="1" class="sy6a29bji"/></radialGradient><radialGradient id="iwwfhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73437 1.71095 -.24621 -.39349 22.549 5.206)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="zb7xzjb0z"/><stop offset="1" class="mvaqivyxk"/></radialGradient><radialGradient id="imKujHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40552 1.24554 -1.0015 -.32607 22.679 5.719)" gradientUnits="userSpaceOnUse"><stop class="pldarnz2e"/><stop offset="1" class="sk_xim0ag"/></radialGradient><radialGradient id="i8z60vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37873 .96346 -.87532 -1.2526 15.68 9.806)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="rpngv328y"/><stop offset="1" class="t-rizvbci"/></radialGradient><radialGradient id="irCHEVn" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 .5625 -.53002 -.60363 18.807 9.776)" gradientUnits="userSpaceOnUse"><stop class="xp17b02vv"/><stop offset="1" class="iu34ngpem"/></radialGradient><radialGradient id="iZDC2xd" cx="0" cy="0" r="1" gradientTransform="matrix(.63766 .79277 -.77436 .62286 13.053 9.777)" gradientUnits="userSpaceOnUse"><stop class="dp-wqtbjr"/><stop offset="1" class="b9skxcbce"/></radialGradient><radialGradient id="iaxQkid" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -1.0781 .32438 -.60175 11.697 6.214)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="sdopbqbnf"/><stop offset="1" class="bj8dg0b8l"/></radialGradient><radialGradient id="iCJwfdb" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 10.58 7.516)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="ieNywVb" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 23.257 4.852)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="i2Kf17d" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 3.836 4.541)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iz0Sw1c" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 9.77 4.852)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iwdleKr" cx="0" cy="0" r="1" gradientTransform="rotate(131.102 6.394 8.24)scale(2.51937 2.50772)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="oqfgbbi5b"/><stop offset="1" class="bvgzffjne"/></radialGradient><radialGradient id="iTvHkyi" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 0 0 1.01563 14.557 9.496)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="r7-2wfbcc"/><stop offset="1" class="me2qedj2f"/></radialGradient><radialGradient id="ia6Q7le" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 -.67969 .45049 .56959 16.682 8.917)" gradientUnits="userSpaceOnUse"><stop class="mky8h2bzd"/><stop offset="1" class="dudenh09d"/></radialGradient><radialGradient id="iUCPwrb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.22 -1.443)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iC0wJeI" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 12.994 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iZfcJcb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 14.552 -4.775)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iubs2De" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 19.658 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="ifvdSwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06861 1.1704 -1.32316 -1.20809 16.615 2.453)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iHZGaVd" cx="0" cy="0" r="1" gradientTransform="matrix(.57433 -.42319 .25665 .34832 16.607 2.55)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iH7TL6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.35276 -1.76557 0 15.994 2.495)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="smf6lpbrg"/><stop offset="1" class="h4ps77q_r"/></radialGradient><linearGradient id="iNxl2kb" x1="23.75" x2="23.438" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop offset=".313" class="j7cl_sb5b"/><stop offset="1" class="ih1u_95kr"/></linearGradient><linearGradient id="iHOuBQd" x1="8.125" x2="10.344" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop class="m2u33lbou"/><stop offset=".202" class="ez3oocggw"/></linearGradient><linearGradient id="ipNloxS" x1="8.354" x2="8.12" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop offset=".191" class="g_trrs0xv"/><stop offset="1" class="cjlyh4xsg"/></linearGradient><linearGradient id="ihvFh8c" x1="23.423" x2="24.011" y1="28.188" y2="28.188" gradientUnits="userSpaceOnUse"><stop class="r9e83i3uc"/><stop offset="1" class="aipwkdvhc"/></linearGradient><linearGradient id="i0FDate" x1="15.424" x2="15.658" y1="28.98" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="utflpqb7a"/><stop offset="1" class="k0l9ze_pq"/></linearGradient><linearGradient id="i3SQbDe" x1="16.549" x2="16.283" y1="30.023" y2="30.023" gradientUnits="userSpaceOnUse"><stop offset=".368" class="cgi88gv2t"/><stop offset="1" class="ehqj11bbt"/></linearGradient><linearGradient id="i2laqUd" x1="7.913" x2="7.913" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="ir9X3VR" x1="20.359" x2="20.359" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iDre4dc" x1="19.601" x2="19.805" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="ikKD89c" x1="20.736" x2="20.58" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="io9c6zb" x1="8.933" x2="8.933" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iCPPbCe" x1="8.218" x2="8.367" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iWzzOub" x1="21.379" x2="21.379" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iAMhepd" x1="20.622" x2="20.825" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="ieYhBrd" x1="21.757" x2="21.6" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="izukjFZ" x1="9.953" x2="9.953" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iIDnZSj" x1="9.239" x2="9.387" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iKFImcd" x1="22.399" x2="22.399" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iFCx3ZU" x1="21.642" x2="21.846" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iC5o5Kc" x1="22.777" x2="22.621" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ixg7ckd" x1="10.974" x2="10.974" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i9Rg3ZK" x1="10.259" x2="10.407" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iiYTAZq" x1="23.42" x2="23.42" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iDsARPb" x1="22.662" x2="22.866" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iqmAtWc" x1="23.797" x2="23.641" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ixmFp6b" x1="11.994" x2="11.994" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i8LvJbd" x1="11.279" x2="11.428" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="ionfRCd" x1="24.44" x2="24.44" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="i7EcZvd" x1="23.683" x2="23.886" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iamWsYd" x1="24.338" x2="18.619" y1="21.261" y2="21.261" gradientUnits="userSpaceOnUse"><stop class="aw5v51m2w"/><stop offset="1" class="epa4jwbux"/></linearGradient><linearGradient id="iejUKqO" x1="18.213" x2="13.4" y1="22.839" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".388" class="xoq3wtioq"/><stop offset="1" class="shyqpdbhw"/></linearGradient><linearGradient id="ia0v8Ae" x1="11.245" x2="10.604" y1="14.929" y2="14.929" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iCyzlsk" x1="21.854" x2="21.035" y1="13.557" y2="16.096" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iH93TiY" x1="20.037" x2="12.393" y1="15.04" y2="16.179" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="ifO6V9h" x1="11.21" x2="12.428" y1="17.837" y2="17.711" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iyETAFb" x1="20.863" x2="19.798" y1="16.9" y2="16.798" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="icfNiwc" x1="15.983" x2="15.983" y1="11.962" y2="12.774" gradientUnits="userSpaceOnUse"><stop class="i2p0hhbue"/><stop offset="1" class="gcofc9lxv"/></linearGradient><linearGradient id="iu03MGe" x1="15.465" x2="23.617" y1="12.053" y2="9.134" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="icL83jm" x1="15.132" x2="16.071" y1="15.7" y2="15.7" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="ifoZ1kd" x1="16.936" x2="15.91" y1="16.023" y2="16.008" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iHtHVPe" x1="16.192" x2="16.192" y1="16.766" y2="16.192" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iHmfxsQ" x1="14.959" x2="15.395" y1="18.382" y2="17.694" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="icUJdbb" x1="18.957" x2="18.643" y1="14.022" y2="14.215" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihMBgzd" x1="14.555" x2="14.241" y1="14.021" y2="14.215" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFbzqEd" x1="12.914" x2="12.914" y1="5.827" y2="7.839" gradientUnits="userSpaceOnUse"><stop class="hn2pq365w"/><stop offset="1" class="ckrbxabiw"/></linearGradient><linearGradient id="igPCvHd" x1="15.791" x2="15.791" y1="12.347" y2="11.964" gradientUnits="userSpaceOnUse"><stop class="dfdb-obom"/><stop offset="1" class="ykc__8bxx"/></linearGradient><linearGradient id="i8FlMae" x1="22.878" x2="22.213" y1="6.73" y2="6.651" gradientUnits="userSpaceOnUse"><stop class="lqxvkgj5w"/><stop offset="1" class="omim8hb6o"/></linearGradient><linearGradient id="igCNT7c" x1="19.362" x2="21.79" y1="7.448" y2="6.014" gradientUnits="userSpaceOnUse"><stop class="o_xhqbdfz"/><stop offset="1" class="cm4ghn5oa"/></linearGradient><linearGradient id="iWKQGxe" x1="16.422" x2="19.127" y1="7.074" y2="6.419" gradientUnits="userSpaceOnUse"><stop class="xgp1qchkh"/><stop offset="1" class="s3wqo851w"/></linearGradient><linearGradient id="iSbcJUc" x1="10.153" x2="12.446" y1="6.075" y2="7.817" gradientUnits="userSpaceOnUse"><stop class="xgzvgdboh"/><stop offset="1" class="a5j92oajv"/></linearGradient><filter id="ivLVywd" width="5.555" height="2.089" x="6.861" y="23.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".25"/></filter><filter id="i45yKRc" width="5.555" height="3.591" x="18.982" y="21.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".25"/></filter><filter id="icaK6ue" width="1.02" height="3.045" x="7.221" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="ixaHyrc" width="1.02" height="3.045" x="8.241" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iVDkuXb" width="1.02" height="3.045" x="9.261" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="ir2swze" width="1.02" height="3.045" x="10.282" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iNjNMvc" width="1.02" height="3.045" x="11.302" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iX998Kd" width="6" height="2.728" x="7.08" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.686275 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.584314 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3045" result="effect2_innerShadow_4002_3045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.521569 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3045" result="effect3_innerShadow_4002_3045"/></filter><filter id="iTn7Pkb" width="6" height="2.728" x="18.908" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.886275 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.588235 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3045" result="effect2_innerShadow_4002_3045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.709804 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3045" result="effect3_innerShadow_4002_3045"/></filter><filter id="iUsBSkb" width="1.594" height="1.594" x="16.607" y="27.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".125"/></filter><filter id="iQObTHb" width="1.594" height="1.594" x="16.607" y="24.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".125"/></filter><filter id="iOxyajd" width="8.261" height="7.961" x="11.864" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.631373 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3045" result="effect2_innerShadow_4002_3045"/></filter><filter id="iOEwXMc" width="3.542" height="3.342" x="9.574" y="12.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="ivuz4ae" width="2.992" height="2.992" x="9.749" y="13.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".25"/></filter><filter id="iPYUFAc" width="3.592" height="3.592" x="19.096" y="12.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iUaLCXl" width="2.992" height="2.992" x="19.271" y="13.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".25"/></filter><filter id="iTKATRb" width="8.25" height="7.07" x="14.167" y="7.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation="1"/></filter><filter id="itTnfPb" width="3.262" height="4.184" x="14.127" y="13.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".375"/></filter><filter id="iN3OwqL" width="2.379" height="3.184" x="14.808" y="13.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".125"/></filter><filter id="ikLcEWO" width="3.621" height="1.474" x="14.187" y="17.236" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".05"/></filter><filter id="i4JnXNd" width=".787" height=".697" x="17.444" y="13.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".05"/></filter><filter id="ix8UXbe" width=".892" height=".914" x="18.284" y="13.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".1"/></filter><filter id="iZWpCad" width=".987" height="1.041" x="13.838" y="13.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".1"/></filter><filter id="i5l35xD" width=".914" height=".705" x="13.083" y="13.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".05"/></filter><filter id="iX5SJKb" width="2.557" height="2.672" x="11.685" y="5.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iDECoRb" width="1.521" height="1.521" x="11.84" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.643137 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="ieKh8xd" width="2.416" height="2.353" x="17.968" y="5.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.717647 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iz8BpVd" width="1.521" height="1.521" x="18.629" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.572549 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iq40Ivc" width="1.535" height="1.535" x="21.971" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iYBivWd" width="1.535" height="1.535" x="8.483" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iAJDSse" width="2.656" height="2.656" x="14.668" y="8.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.443137 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iju3Zpb" width="1.646" height="1.646" x="11.84" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iNQyXdb" width="1.646" height="1.646" x="18.504" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter><filter id="iUy02mc" width="3.214" height="1.831" x="18.883" y="5.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".05"/></filter><filter id="i40H1Mc" width="2.847" height="3.566" x="15.985" y="3.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".05"/></filter><filter id="iQOIGeb" width="2.566" height="1.722" x="9.914" y="5.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3045" stdDeviation=".05"/></filter><filter id="iChIxpb" width="1.812" height="1.813" x="15.088" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3045"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:prince-medium-dark" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a2yqhej6q {
  cx: 11.245px;
  cy: 14.65px;
  r: 1.671px;
}

.a5j92oajv {
  stop-color: var(--svg-color--d99c45, #D99C45);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.aipwkdvhc {
  stop-color: var(--svg-color--1895e8, #1895E8);
  stop-opacity: 0;
}

.aqh6zpbtp {
  d: path("m15.615 14.365l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.auvf1abdy {
  d: path("M21.103 13.167c.03-.497-.155-.878-.262-.977l.407-.184c.265.305.437.996.383 1.45c-.044.362-.383.5-.547.523c.005-.154 0-.5.02-.812");
}

.aw5v51m2w {
  stop-color: var(--svg-color--ffca34, #FFCA34);
}

.axg38cfdd {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.997 17.783c-.508 0-.985-.12-1.386-.329c-.137-.07-.285.085-.198.21c.335.507.919.846 1.584.846c.666 0 1.25-.339 1.585-.847c.086-.129-.061-.278-.198-.209c-.402.21-.874.329-1.387.329Z");
}

.b9skxcbce {
  stop-color: var(--svg-color--e47a3c, #E47A3C);
  stop-opacity: 0;
}

.bc7d6obfi {
  stop-color: var(--svg-color--fda839, #FDA839);
}

.bj8dg0b8l {
  stop-color: var(--svg-color--e4ad53, #E4AD53);
  stop-opacity: 0;
}

.btm953brw {
  stop-color: var(--svg-color--c18731, #C18731);
  stop-opacity: 0;
}

.bvgzffjne {
  stop-color: var(--svg-color--377be9, #377BE9);
}

.c0g3mbbdp {
  d: path("M23.748 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c2o8f_bwu {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.722 14.528l-.822 1.701c-.101.35.143.7.489.7h.738c.346 0 .59-.355.489-.7l-.5-1.701c-.106-.377-.282-.377-.394 0");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ceu0gybff {
  stop-color: var(--svg-color--59bfed, #59BFED);
}

.cgi88gv2t {
  stop-color: var(--svg-color--ffcf53, #FFCF53);
}

.cjlyh4xsg {
  stop-color: var(--svg-color--178ce6, #178CE6);
  stop-opacity: 0;
}

.ckrbxabiw {
  stop-color: var(--svg-color--efb863, #EFB863);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm4ghn5oa {
  stop-color: var(--svg-color--fbc46e, #FBC46E);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.cz54lzbgf {
  d: path("M12.65 5.167c-.468.188-.824 1.206-.965 1.649l1.16 1.023l1.298-.96c-.801-1.454-1.149-1.637-1.297-1.68z");
}

.d-aoszbpp {
  cx: 17.404px;
  cy: 28.48px;
  r: 0.547px;
  fill: var(--svg-color--2f71c6, #2F71C6);
}

.d0pq7p0hl {
  stop-color: var(--svg-color--d9a439, #D9A439);
}

.d3e9_irck {
  d: path("M7.22 21.847h1.021v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d7dg5k-bm {
  fill: var(--svg-color--24599f, #24599F);
  d: path("M24.037 23.89h-.911v.82c0 .148.12.268.268.268h.375c.148 0 .268-.12.268-.267z");
}

.dfdb-obom {
  stop-color: var(--svg-color--ff7468, #FF7468);
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dijw_ccpd {
  cx: 11.245px;
  cy: 14.65px;
  r: 0.996px;
}

.dp-wqtbjr {
  stop-color: var(--svg-color--e47a3c, #E47A3C);
}

.dpitlhbpx {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
  stop-opacity: 0;
}

.drf1ulbyy {
  fill: var(--svg-color--24599f, #24599F);
  d: path("M7.361 23.904h1.822v.821c0 .148-.12.268-.268.268H8.54a.27.27 0 0 1-.268-.264a.27.27 0 0 1-.268.264H7.63a.27.27 0 0 1-.268-.268zm1.822 0v.821c0 .148.12.268.268.268h.375a.27.27 0 0 0 .268-.264a.27.27 0 0 0 .268.264h.375c.148 0 .268-.12.268-.268v-.82z");
}

.dudenh09d {
  stop-color: var(--svg-color--52b8f8, #52B8F8);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_wenbdi {
  d: path("M8.354 22.465c-2.507 2.142-3.565 5.216-4.016 7.5h4.016z");
}

.e324j6gaq {
  d: path("M19.15 5.218c-.362.135-.868.961-1.082 1.317l.664 1.011l1.653-.535c-.43-1.27-.782-1.96-1.235-1.793");
}

.e52rcizoy {
  d: path("m19.964 9.02l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.063-.41z");
}

.e6qjesbba {
  stop-color: var(--svg-color--c18731, #C18731);
}

.e70edmbwm {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 14.383a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.ehqj11bbt {
  stop-color: var(--svg-color--fc4, #FC4);
  stop-opacity: 0;
}

.ehy0pm5vd {
  stop-color: var(--svg-color--409bff, #409BFF);
}

.eif22vbdr {
  stop-color: var(--svg-color--f7d06d, #F7D06D);
  stop-opacity: 0;
}

.ekivnb4zj {
  stop-color: var(--svg-color--644542, #644542);
}

.ep1-kbb1x {
  cx: 20.767px;
  cy: 14.65px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.epa4jwbux {
  stop-color: var(--svg-color--ffbc10, #FFBC10);
}

.escp53_pi {
  d: path("M11.302 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ey-1_lflg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 7.269c.07.08.261.227.461.164c.2-.062 1.719-1.036 2.453-1.516");
}

.ez3oocggw {
  stop-color: var(--svg-color--1183d9, #1183D9);
  stop-opacity: 0;
}

.f-t10ph2f {
  cx: 17.494px;
  cy: 25.261px;
  r: 0.547px;
}

.f0sz96v9r {
  d: path("M4.338 29.964c.766-3.875 3.281-10.03 11.656-10.03v.037l.012-.038c8.375 0 10.89 6.156 11.656 10.031z");
}

.f19u2wb6f {
  cx: 12.601px;
  cy: 4.609px;
  r: 0.761px;
}

.f3nh8zb0n {
  d: path("M10.855 13.167c-.03-.497.155-.878.262-.977l-.407-.184c-.265.305-.437.996-.382 1.45c.043.362.383.5.547.523c-.006-.154-.001-.5-.02-.812");
}

.f8xv78wwh {
  d: path("M19.667 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.fasttccsa {
  d: path("M14.625 14.278c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.fiwhz1yao {
  stop-color: var(--svg-color--fad771, #FAD771);
  stop-opacity: 0;
}

.fm5egxmlo {
  stop-color: var(--svg-color--267ebb, #267EBB);
}

.fnx367bbh {
  stop-color: var(--svg-color--ffcc36, #FFCC36);
  stop-opacity: 0;
}

.fq5e2gbsk {
  stop-color: var(--svg-color--55d8ff, #55D8FF);
}

.ft5dv1b6b {
  fill: none;
}

.fw-_ge0oq {
  d: path("M7.08 20.972a1 1 0 0 1 1-1h5v2.578h-5.2a.8.8 0 0 1-.8-.8z");
}

.fwcf4ds6u {
  stop-color: var(--svg-color--f2b056, #F2B056);
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g_trrs0xv {
  stop-color: var(--svg-color--178ce6, #178CE6);
}

.gcofc9lxv {
  stop-color: var(--svg-color--734548, #734548);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gvudu0-9m {
  stop-color: var(--svg-color--c37b21, #C37B21);
}

.h_mah-buv {
  stop-color: var(--svg-color--fad771, #FAD771);
}

.h4ps77q_r {
  stop-color: var(--svg-color--d89b45, #D89B45);
}

.heg5bdcwd {
  stop-color: var(--svg-color--54b5ff, #54B5FF);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hn2pq365w {
  stop-color: var(--svg-color--f6c164, #F6C164);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hqe5c4bli {
  d: path("M23.635 22.456c2.514 2.142 3.575 5.222 4.027 7.508h-4.027z");
}

.i-1u09bvn {
  stop-color: var(--svg-color--784851, #784851);
}

.i2p0hhbue {
  stop-color: var(--svg-color--734548, #734548);
}

.i2r14vbib {
  stop-color: var(--svg-color--39b6de, #39B6DE);
}

.i5vxhhb9k {
  cx: 15.994px;
  cy: 20.519px;
  rx: 2.32px;
  ry: 2.297px;
}

.i8km-wymp {
  cx: 13.54px;
  cy: 13.872px;
  rx: 0.39px;
  ry: 0.197px;
}

.ih1u_95kr {
  stop-color: var(--svg-color--2fa1f8, #2FA1F8);
  stop-opacity: 0;
}

.im0aqq9wp {
  stop-color: var(--svg-color--3b77d1, #3B77D1);
  stop-opacity: 0;
}

.iu34ngpem {
  stop-color: var(--svg-color--e57b3e, #E57B3E);
  stop-opacity: 0;
}

.iu8kp3ahw {
  d: path("M16.549 29.964h-1.086v-6.28h1.086z");
}

.ivvelbx3d {
  d: path("M13.809 13.49a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.iyq1_fb9e {
  stop-color: var(--svg-color--e4bb48, #E4BB48);
}

.izxaz-bvs {
  stop-color: var(--svg-color--3c7dcd, #3C7DCD);
}

.j-8m34b2o {
  cx: 17.404px;
  cy: 25.308px;
  r: 0.547px;
  fill: var(--svg-color--2f71c6, #2F71C6);
}

.j0k3id93s {
  stop-color: var(--svg-color--984900, #984900);
  stop-opacity: 0;
}

.j1ajldk8d {
  d: path("M18.115 13.679c.063.085-.07.189-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.j7cl_sb5b {
  stop-color: var(--svg-color--2fa1f8, #2FA1F8);
}

.jh_m43_mm {
  stop-color: var(--svg-color--67374b, #67374B);
}

.jnpel9bup {
  stop-color: var(--svg-color--f7d06d, #F7D06D);
}

.jqlapeb1l {
  d: path("m9.11 5.009l1.287 7.093a.25.25 0 0 0 .246.205h10.702a.25.25 0 0 0 .246-.205l1.287-7.093l-3.37 2.107a.495.495 0 0 1-.666-.13a160 160 0 0 1-.666-.946c-.551-.784-1.11-1.58-1.371-1.89c-.38-.454-.651-.477-.807-.477h-.007c-.156 0-.427.023-.808.476c-.26.31-.82 1.107-1.37 1.891c-.232.33-.462.657-.667.945a.495.495 0 0 1-.667.131z");
}

.jrd3jzgth {
  stop-color: var(--svg-color--dd7423, #DD7423);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jxvb9w84e {
  stop-color: var(--svg-color--fc586e, #FC586E);
}

.jzfasvbbp {
  cx: 22.739px;
  cy: 5.184px;
  r: 0.767px;
}

.jzifsbrfx {
  cx: 20.767px;
  cy: 14.65px;
  r: 0.996px;
}

.k0l9ze_pq {
  stop-color: var(--svg-color--da7c13, #DA7C13);
  stop-opacity: 0;
}

.k4csq1kxn {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M15.997 17.783c-.508 0-.985-.12-1.386-.329c-.137-.07-.285.085-.198.21c.335.507.919.846 1.584.846c.666 0 1.25-.339 1.585-.847c.086-.129-.061-.278-.198-.209c-.402.21-.874.329-1.387.329");
}

.kbcpr6bot {
  d: path("M22.727 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.kfayvkisl {
  cx: 17.494px;
  cy: 28.386px;
  r: 0.547px;
}

.kfhq2vx5n {
  stop-color: var(--svg-color--c68e33, #C68E33);
}

.kiolp_-pe {
  d: path("M21.707 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.klzc01b5d {
  stop-color: var(--svg-color--3ab2ff, #3AB2FF);
}

.knplocckt {
  stop-color: var(--svg-color--3a7ada, #3A7ADA);
  stop-opacity: 0;
}

.kowfi484h {
  cx: 15.994px;
  cy: 2.942px;
  r: 0.906px;
}

.ks0-jgbez {
  cx: 15.996px;
  cy: 9.41px;
  r: 1.328px;
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kz6jvgbzd {
  stop-color: var(--svg-color--e0a155, #E0A155);
}

.l0yglmb3r {
  stop-color: var(--svg-color--e5c652, #E5C652);
}

.l2jyntb4f {
  stop-color: var(--svg-color--ffad23, #FFAD23);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldyj_nb1e {
  cx: 9.25px;
  cy: 5.184px;
  r: 0.767px;
}

.lft039jrw {
  stop-color: var(--svg-color--170b1b, #170B1B);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqxvkgj5w {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
}

.lt24i1boi {
  stop-color: var(--svg-color--643633, #643633);
}

.ltsxllb3q {
  stop-color: var(--svg-color--d37902, #D37902);
}

.lup_unb-i {
  stop-color: var(--svg-color--3b77d1, #3B77D1);
}

.lvnq4bd5c {
  d: path("M18.976 14.266a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m2l89-bxk {
  stop-color: var(--svg-color--3d3c3d, #3D3C3D);
}

.m2u33lbou {
  stop-color: var(--svg-color--1183d9, #1183D9);
}

.m8_9xackt {
  stop-color: var(--svg-color--e7175a, #E7175A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdad8vdth {
  stop-color: var(--svg-color--4e97be, #4E97BE);
}

.me2qedj2f {
  stop-color: var(--svg-color--467ec1, #467EC1);
  stop-opacity: 0;
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mgn2xlbnn {
  stop-color: var(--svg-color--140b1b, #140B1B);
}

.mky8h2bzd {
  stop-color: var(--svg-color--52b8f8, #52B8F8);
}

.mnkzj2b2e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.115 13.679c.063.085-.07.189-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.mqzky-b6t {
  stop-color: var(--svg-color--ffcc36, #FFCC36);
}

.mvaqivyxk {
  stop-color: var(--svg-color--cd9d50, #CD9D50);
  stop-opacity: 0;
}

.mx5qf9bzw {
  stop-color: var(--svg-color--ffab48, #FFAB48);
}

.ncq6f9bxg {
  stop-color: var(--svg-color--633343, #633343);
}

.nd4srkbik {
  stop-color: var(--svg-color--fa865b, #FA865B);
  stop-opacity: 0;
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.o_0wq7b5h {
  stop-color: var(--svg-color--fa865b, #FA865B);
}

.o_4gny8-z {
  stop-color: var(--svg-color--dd7423, #DD7423);
}

.o_84ttbae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.135 3.808c.11.031.387.172.625.484c.237.313 1.38 1.985 1.922 2.782");
}

.o_xhqbdfz {
  stop-color: var(--svg-color--fbc46e, #FBC46E);
}

.o-695ij2e {
  stop-color: var(--svg-color--984900, #984900);
}

.o375d620d {
  stop-color: var(--svg-color--e08711, #E08711);
  stop-opacity: 0;
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o5mupf-2w {
  d: path("M18.18 13.49a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omim8hb6o {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
  stop-opacity: 0;
}

.oqfgbbi5b {
  stop-color: var(--svg-color--26a4db, #26A4DB);
}

.oughljbvw {
  stop-color: var(--svg-color--3f8dc5, #3F8DC5);
}

.owp1j2bwg {
  stop-color: var(--svg-color--59bfed, #59BFED);
  stop-opacity: 0;
}

.p-jh4qrfp {
  fill: var(--svg-color--000, #000);
  d: path("M17.669 14.383a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.061-.235");
}

.pd-kjcckg {
  stop-color: var(--svg-color--ffc95d, #FFC95D);
  stop-opacity: 0;
}

.pg0l0_b5e {
  stop-color: var(--svg-color--e3964c, #E3964C);
}

.pimf00m2w {
  cx: 12.663px;
  cy: 9.41px;
  r: 0.823px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pldarnz2e {
  stop-color: var(--svg-color--d79e4a, #D79E4A);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.prxm8ubjj {
  cx: 22.026px;
  cy: 9.418px;
  r: 0.817px;
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q4uf8hbdw {
  stop-color: var(--svg-color--68c4ee, #68C4EE);
}

.qk8v1bc2n {
  cx: 19.39px;
  cy: 4.609px;
  r: 0.761px;
}

.ql2irpb2m {
  cx: 19.327px;
  cy: 9.41px;
  r: 0.823px;
}

.qp7qzchye {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m10.065 5.863l2.265 1.422");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxfkfde9r {
  stop-color: var(--svg-color--3e85e8, #3E85E8);
}

.r7-2wfbcc {
  stop-color: var(--svg-color--467ec1, #467EC1);
}

.r9e83i3uc {
  stop-color: var(--svg-color--1895e8, #1895E8);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rez3ddccp {
  stop-color: var(--svg-color--e5780c, #E5780C);
}

.rgangdc7y {
  stop-color: var(--svg-color--416ec4, #416EC4);
  stop-opacity: 0;
}

.rnq8zfbyk {
  d: path("M9.261 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.rpngv328y {
  stop-color: var(--svg-color--e1754f, #E1754F);
}

.rul-_pb0t {
  stop-color: var(--svg-color--484341, #484341);
}

.ryq7ubb8z {
  stop-color: var(--svg-color--54b5ff, #54B5FF);
  stop-opacity: 0;
}

.s-qqz8oax {
  stop-color: var(--svg-color--e68600, #E68600);
  stop-opacity: 0;
}

.s3wqo851w {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sblhzud6f {
  stop-color: var(--svg-color--e11f40, #E11F40);
}

.sdopbqbnf {
  stop-color: var(--svg-color--e4ad53, #E4AD53);
}

.sgtr8ibeb {
  d: path("M24.908 20.972a1 1 0 0 0-1-1h-5v2.578h5.2a.8.8 0 0 0 .8-.8z");
}

.shgrjqbiz {
  d: path("M20.687 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.shyqpdbhw {
  stop-color: var(--svg-color--d88f1c, #D88F1C);
}

.sk_xim0ag {
  stop-color: var(--svg-color--d79e4a, #D79E4A);
  stop-opacity: 0;
}

.smf6lpbrg {
  stop-color: var(--svg-color--d89b45, #D89B45);
  stop-opacity: 0;
}

.smjt6t9ha {
  stop-color: var(--svg-color--d2961e, #D2961E);
}

.swjgceb9v {
  d: path("M10.282 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.sy6a29bji {
  stop-color: var(--svg-color--dda44f, #DDA44F);
  stop-opacity: 0;
}

.t-rizvbci {
  stop-color: var(--svg-color--e1754f, #E1754F);
  stop-opacity: 0;
}

.t9vbol6ta {
  cx: 13.54px;
  cy: 13.872px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.tedvzacni {
  fill: var(--svg-color--24599f, #24599F);
  d: path("M11.916 23.904h-.911v.821c0 .148.12.268.268.268h.375c.148 0 .268-.12.268-.268z");
}

.tgzndhrni {
  stop-color: var(--svg-color--ae5301, #AE5301);
}

.tjsj1op7o {
  stop-color: var(--svg-color--dda72d, #DDA72D);
}

.tnnw6ib6s {
  fill: var(--svg-color--24599f, #24599F);
  d: path("M19.482 22.387h1.822v2.324c0 .148-.12.267-.268.267h-.375a.27.27 0 0 1-.268-.264a.27.27 0 0 1-.268.264h-.375a.27.27 0 0 1-.268-.267zm1.822 0v2.324c0 .148.12.267.268.267h.375a.27.27 0 0 0 .268-.264a.27.27 0 0 0 .268.264h.375c.148 0 .268-.12.268-.267v-.821z");
}

.trt6sabjd {
  stop-color: var(--svg-color--e68600, #E68600);
}

.tuulhko3b {
  fill: var(--svg-color--7e5350, #7E5350);
  d: path("m15.615 14.365l-.532 1.7a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.txn55m2mi {
  stop-color: var(--svg-color--754058, #754058);
  stop-opacity: 0;
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u8ozf6b8x {
  stop-color: var(--svg-color--e5780c, #E5780C);
  stop-opacity: 0;
}

.uakpxk1lj {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.387 13.218c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.ud61_vz9g {
  fill: var(--svg-color--ffbf46, #FFBF46);
  d: path("M16.549 29.964h-1.086v-6.28h1.086z");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ufab9bcqz {
  stop-color: var(--svg-color--416ec4, #416EC4);
}

.uo3cwjh_s {
  d: path("M10.749 12.65c0-.266.193-.64.407-.8l.161-.16c.269-.214.376-.534.376-.854V9.98a.52.52 0 0 1 .43-.533c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.266 3.919.427c.214.053.43.267.43.533v.855c0 .32.16.64.375.854c.503.352.471.546.43.96c-.18 1.794-.235 3.606-.356 5.404c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.052-1.235-3.213-3.006c-.14-1.826-.287-3.59-.452-5.403");
}

.utflpqb7a {
  stop-color: var(--svg-color--da7c13, #DA7C13);
}

.uv5le6qqz {
  stop-color: var(--svg-color--22478d, #22478D);
}

.v-aq_fb5e {
  cx: 9.966px;
  cy: 9.418px;
  r: 0.817px;
}

.v1k_mhzfg {
  stop-color: var(--svg-color--ffb34d, #FFB34D);
  stop-opacity: 0;
}

.vmhbtsb-a {
  d: path("M8.241 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.vscmudgro {
  stop-color: var(--svg-color--643633, #643633);
  stop-opacity: 0;
}

.vy-t95buc {
  stop-color: var(--svg-color--dda44f, #DDA44F);
}

.w_324qbof {
  stop-color: var(--svg-color--fff150, #FFF150);
}

.w_ld-kbgg {
  stop-color: var(--svg-color--ffb34d, #FFB34D);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.we5kvqbpm {
  cx: 15.994px;
  cy: 20.206px;
  r: 3.98px;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wt2jy5jep {
  cx: 20.767px;
  cy: 14.65px;
  r: 1.671px;
}

.xgp1qchkh {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
}

.xgzvgdboh {
  stop-color: var(--svg-color--e4aa42, #E4AA42);
}

.xh-geaczg {
  stop-color: var(--svg-color--644542, #644542);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xmc2l2-sl {
  stop-color: var(--svg-color--ffc95d, #FFC95D);
}

.xoq3wtioq {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
}

.xp17b02vv {
  stop-color: var(--svg-color--e57b3e, #E57B3E);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ykc__8bxx {
  stop-color: var(--svg-color--ff865b, #FF865B);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z1e4imbuu {
  stop-color: var(--svg-color--e2aa40, #E2AA40);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zb7xzjb0z {
  stop-color: var(--svg-color--cd9d50, #CD9D50);
}

.zi727lnsv {
  stop-color: var(--svg-color--f1c752, #F1C752);
}

.zl0i2nl5t {
  stop-color: var(--svg-color--fca135, #FCA135);
}

.zq_fy1bcr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.602 13.218c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.zupcoccwr {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
}

</style>
