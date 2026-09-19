<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iaBNSmv)" class="f0sz96v9r"/><path fill="url(#igH2a8b)" class="f0sz96v9r"/><path fill="url(#i9KFWTd)" class="f0sz96v9r"/><path fill="url(#iNxl2kb)" class="f0sz96v9r"/><path fill="url(#iHOuBQd)" class="f0sz96v9r"/><path fill="url(#i8Vf7fd)" class="f0sz96v9r"/><path fill="url(#iAbth5c)" class="e2_wenbdi"/><path fill="url(#ipNloxS)" class="e2_wenbdi"/><path fill="url(#ibKH0Mb)" class="hqe5c4bli"/><path fill="url(#ihvFh8c)" class="hqe5c4bli"/><g filter="url(#ijVFzId)"><path class="drf1ulbyy"/><path class="tedvzacni"/></g><g filter="url(#ipg1qUL)"><path class="tnnw6ib6s"/><path class="d7dg5k-bm"/></g><path class="ud61_vz9g"/><path fill="url(#i0FDate)" class="iu8kp3ahw"/><path fill="url(#i3SQbDe)" class="iu8kp3ahw"/><path fill="url(#iyxEWTc)" class="iu8kp3ahw"/><g filter="url(#iVNaINc)"><path fill="url(#i2laqUd)" class="d3e9_irck"/><path fill="url(#iIKZtAe)" class="d3e9_irck"/><path fill="url(#iHMIXWh)" class="d3e9_irck"/></g><path fill="url(#ir9X3VR)" class="f8xv78wwh"/><path fill="url(#iDre4dc)" class="f8xv78wwh"/><path fill="url(#iZFhrYb)" class="f8xv78wwh"/><path fill="url(#ikKD89c)" class="f8xv78wwh"/><path fill="url(#imfQuDc)" class="f8xv78wwh"/><g filter="url(#i4tfEku)"><path fill="url(#io9c6zb)" class="vmhbtsb-a"/><path fill="url(#iIfxIeM)" class="vmhbtsb-a"/><path fill="url(#iUfBlYz)" class="vmhbtsb-a"/><path fill="url(#iCPPbCe)" class="vmhbtsb-a"/></g><path fill="url(#iWzzOub)" class="shgrjqbiz"/><path fill="url(#iAMhepd)" class="shgrjqbiz"/><path fill="url(#ivjzpvb)" class="shgrjqbiz"/><path fill="url(#ieYhBrd)" class="shgrjqbiz"/><path fill="url(#i9lS2bb)" class="shgrjqbiz"/><g filter="url(#iT8tPnd)"><path fill="url(#izukjFZ)" class="rnq8zfbyk"/><path fill="url(#iAyKCmx)" class="rnq8zfbyk"/><path fill="url(#i4fzUHl)" class="rnq8zfbyk"/><path fill="url(#iIDnZSj)" class="rnq8zfbyk"/></g><path fill="url(#iKFImcd)" class="kiolp_-pe"/><path fill="url(#iFCx3ZU)" class="kiolp_-pe"/><path fill="url(#iN3ekpY)" class="kiolp_-pe"/><path fill="url(#iC5o5Kc)" class="kiolp_-pe"/><path fill="url(#imus0Oe)" class="kiolp_-pe"/><g filter="url(#iHkzsgb)"><path fill="url(#ixg7ckd)" class="swjgceb9v"/><path fill="url(#iYIbosd)" class="swjgceb9v"/><path fill="url(#iS5Q3Vc)" class="swjgceb9v"/><path fill="url(#i9Rg3ZK)" class="swjgceb9v"/></g><path fill="url(#iiYTAZq)" class="kbcpr6bot"/><path fill="url(#iDsARPb)" class="kbcpr6bot"/><path fill="url(#iwVkT9d)" class="kbcpr6bot"/><path fill="url(#iqmAtWc)" class="kbcpr6bot"/><path fill="url(#iSeQN2N)" class="kbcpr6bot"/><g filter="url(#iOf89mT)"><path fill="url(#ixmFp6b)" class="escp53_pi"/><path fill="url(#ixyyVtb)" class="escp53_pi"/><path fill="url(#iAJYwfd)" class="escp53_pi"/><path fill="url(#i8LvJbd)" class="escp53_pi"/></g><path fill="url(#ionfRCd)" class="c0g3mbbdp"/><path fill="url(#i7EcZvd)" class="c0g3mbbdp"/><path fill="url(#iqIlRze)" class="c0g3mbbdp"/><path fill="url(#iraNcty)" class="c0g3mbbdp"/><g filter="url(#ibxHFrc)"><path fill="url(#i8a7U2b)" class="fw-_ge0oq"/></g><g filter="url(#i5W8oLd)"><path fill="url(#iamWsYd)" class="sgtr8ibeb"/><path fill="url(#iLswA2c)" class="sgtr8ibeb"/></g><g filter="url(#iVp6dbl)"><circle class="d-aoszbpp"/></g><g filter="url(#iSlwuhe)"><circle class="j-8m34b2o"/></g><circle fill="url(#iZ3BMQx)" class="kfayvkisl"/><g filter="url(#i3A4MSc)"><circle fill="url(#iejUKqO)" class="we5kvqbpm"/><circle fill="url(#iz3N9Og)" class="we5kvqbpm"/></g><ellipse fill="url(#ifouf8c)" class="i5vxhhb9k"/><ellipse fill="url(#iUC83Ic)" class="i5vxhhb9k"/><ellipse fill="url(#ijRunPc)" class="i5vxhhb9k"/><circle fill="url(#iLnMLcb)" class="f-t10ph2f"/><g filter="url(#iFL56IS)"><path fill="url(#isv1Lsb)" class="ng5rfdb2t"/></g><g filter="url(#iXcg9qk)"><circle fill="url(#itwpvbb)" class="fl1_jabov"/></g><g filter="url(#ifxOXse)"><circle fill="url(#iw340je)" class="xapif3b3d"/></g><g filter="url(#ifTZUpe)"><circle fill="url(#iXXMvll)" class="qdik7cb2m"/><circle fill="url(#ioTAbRb)" class="qdik7cb2m"/></g><g filter="url(#ijl3Odc)"><circle class="atc8o_0_r"/><circle fill="url(#i1hTzIb)" class="asgxu8b-r"/><circle fill="url(#iIZvxwd)" class="asgxu8b-r"/></g><path fill="url(#ie4jqdb)" class="hatp33bbn"/><path fill="url(#i1iMpsc)" class="hatp33bbn"/><path fill="url(#i0OIHTb)" class="hatp33bbn"/><path fill="url(#iks8HCd)" class="hatp33bbn"/><path fill="url(#iHga53c)" class="hatp33bbn"/><g filter="url(#iNFO48b)"><path class="k47d47bgr"/></g><g filter="url(#i4CtxCd)"><path class="iz7sw1_5z"/><path fill="url(#ieADf5c)" class="xty8ecqkp"/><path fill="url(#iUBNS1d)" class="xty8ecqkp"/><path fill="url(#iWmsIwc)" class="xty8ecqkp"/></g><g filter="url(#iotz08b)"><path stroke="url(#icj3UJI)" class="j7_pugjtz"/></g><path class="t46s86b2x"/><path class="zpm1xbbni"/><path fill="url(#igzrG2d)" class="jj87kxbfm"/><path class="hmc1oabhr"/><g filter="url(#iHtudrc)"><path class="uyt1djb3f"/><path fill="url(#iPcfgwd)" class="r4f162bfw"/></g><g filter="url(#ibSKyAd)"><path fill="url(#iYS7Fzc)" class="xu8dt4-7y"/></g><path class="n4tij1bsl"/><path fill="url(#iWCPZDc)" class="iukj6rsyu"/><path class="lln-5jbqh"/><g filter="url(#i5xoseb)"><path fill="url(#issFFRq)" class="ea9x8-par"/></g><g filter="url(#iIDIKgl)"><ellipse transform="rotate(-27.914 13.53 13.88)" class="nrdc_cb1b"/><ellipse fill="url(#iyJ6fDe)" transform="rotate(-27.914 13.53 13.88)" class="xhy6cj0-l"/></g><path fill="url(#iilViob)" class="c4_z29l-c"/><path fill="url(#iEbYbLb)" class="auvf1abdy"/><g filter="url(#iXynSYc)"><path fill="url(#iFbzqEd)" class="cz54lzbgf"/></g><g filter="url(#iEIOPAQ)"><circle fill="url(#ilMc2me)" class="f19u2wb6f"/><circle fill="url(#ijH8mic)" class="f19u2wb6f"/></g><g filter="url(#iZUc5fb)"><path fill="url(#iOspXqd)" class="e324j6gaq"/><path fill="url(#i6HCwxb)" class="e324j6gaq"/></g><g filter="url(#iBVJUNT)"><circle fill="url(#iHTVxLe)" class="qk8v1bc2n"/><circle fill="url(#iprWAmd)" class="qk8v1bc2n"/></g><circle fill="url(#ia01BWX)" class="v-aq_fb5e"/><circle fill="url(#iNe5Amc)" class="v-aq_fb5e"/><circle fill="url(#iPsaLGe)" class="prxm8ubjj"/><circle fill="url(#ijQY9Cb)" class="prxm8ubjj"/><path fill="url(#iq31Hcc)" class="jqlapeb1l"/><path fill="url(#iovwq8b)" class="jqlapeb1l"/><path fill="url(#igPCvHd)" class="jqlapeb1l"/><path fill="url(#iSEn53b)" class="jqlapeb1l"/><path fill="url(#iwwfhfb)" class="jqlapeb1l"/><path fill="url(#imKujHe)" class="jqlapeb1l"/><path fill="url(#i8FlMae)" class="jqlapeb1l"/><path fill="url(#i8z60vd)" class="jqlapeb1l"/><path fill="url(#irCHEVn)" class="jqlapeb1l"/><path fill="url(#iZDC2xd)" class="jqlapeb1l"/><path fill="url(#iaxQkid)" class="jqlapeb1l"/><g filter="url(#iNM3qNK)"><circle fill="url(#iCJwfdb)" class="jzfasvbbp"/><circle fill="url(#ieNywVb)" class="jzfasvbbp"/></g><g filter="url(#i1xBLvb)"><circle fill="url(#i2Kf17d)" class="ldyj_nb1e"/><circle fill="url(#iz0Sw1c)" class="ldyj_nb1e"/></g><g filter="url(#iHxo80k)"><circle fill="url(#iwdleKr)" class="ks0-jgbez"/><circle fill="url(#iTvHkyi)" class="ks0-jgbez"/><circle fill="url(#ia6Q7le)" class="ks0-jgbez"/></g><g filter="url(#icUi2cb)"><circle fill="url(#iUCPwrb)" class="pimf00m2w"/><circle fill="url(#iC0wJeI)" class="pimf00m2w"/></g><g filter="url(#iuS9i6P)"><circle fill="url(#iZfcJcb)" class="ql2irpb2m"/><circle fill="url(#iubs2De)" class="ql2irpb2m"/></g><g filter="url(#iuGzt3r)"><path stroke="url(#igCNT7c)" class="ey-1_lflg"/></g><g filter="url(#iDRMmfe)"><path stroke="url(#iWKQGxe)" class="o_84ttbae"/></g><g filter="url(#iMArZzb)"><path stroke="url(#iSbcJUc)" class="qp7qzchye"/></g><g filter="url(#igi6Rgs)"><circle fill="url(#ifvdSwb)" class="kowfi484h"/><circle fill="url(#iHZGaVd)" class="kowfi484h"/></g><circle fill="url(#iH7TL6c)" class="kowfi484h"/><defs><radialGradient id="iaBNSmv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.02441 -14.994 0 16 21.94)" gradientUnits="userSpaceOnUse"><stop class="qxfkfde9r"/><stop offset="1" class="ehy0pm5vd"/></radialGradient><radialGradient id="igH2a8b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24414 0 0 -14.5244 23.807 29.964)" gradientUnits="userSpaceOnUse"><stop class="heg5bdcwd"/><stop offset="1" class="ryq7ubb8z"/></radialGradient><radialGradient id="i9KFWTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.75 -15.6948 0 16 20.815)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="uv5le6qqz"/><stop offset="1" class="knplocckt"/></radialGradient><radialGradient id="i8Vf7fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.8125 -.53125 0 15.688 26.221)" gradientUnits="userSpaceOnUse"><stop class="lup_unb-i"/><stop offset="1" class="im0aqq9wp"/></radialGradient><radialGradient id="iAbth5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.28332 4.28735 0 8.354 29.67)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="klzc01b5d"/><stop offset="1" class="mdad8vdth"/></radialGradient><radialGradient id="ibKH0Mb" cx="0" cy="0" r="1" gradientTransform="matrix(3.36005 0 0 6.32267 23.847 28.93)" gradientUnits="userSpaceOnUse"><stop class="fq5e2gbsk"/><stop offset="1" class="q4uf8hbdw"/></radialGradient><radialGradient id="iyxEWTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .69531 -2.16649 0 16.006 23.956)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="o_4gny8-z"/><stop offset=".622" class="jrd3jzgth"/></radialGradient><radialGradient id="iIKZtAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 8.241 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iHMIXWh" cx="0" cy="0" r="1" gradientTransform="rotate(-84.161 17.495 8.173)scale(2.35566 2.26902)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="o375d620d"/><stop offset="1" class="tgzndhrni"/></radialGradient><radialGradient id="iZFhrYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 20.687 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="imfQuDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 20.177 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iIfxIeM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 9.261 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iUfBlYz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 8.751 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ivjzpvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 21.707 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="i9lS2bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 21.197 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iAyKCmx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 10.282 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="i4fzUHl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 9.772 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iN3ekpY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 22.727 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="imus0Oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 22.217 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iYIbosd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 11.302 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iS5Q3Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 10.792 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iwVkT9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 23.748 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iSeQN2N" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 23.238 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ixyyVtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 12.322 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iAJYwfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 11.812 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iqIlRze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 24.768 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iraNcty" cx="0" cy="0" r="1" gradientTransform="rotate(-97.511 23.055 1.525)scale(2.28523 2.20118)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="i8a7U2b" cx="0" cy="0" r="1" gradientTransform="matrix(3.09374 -3.6172 12.35097 10.56365 9.4 23.59)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="tjsj1op7o"/><stop offset="1" class="gvudu0-9m"/></radialGradient><radialGradient id="iLswA2c" cx="0" cy="0" r="1" gradientTransform="matrix(3.57813 0 0 3.06696 20.104 22.246)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="mqzky-b6t"/><stop offset="1" class="fnx367bbh"/></radialGradient><radialGradient id="iZ3BMQx" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 2.282 18.291)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="iz3N9Og" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 1.30469 -.7272 -.3919 17.533 21.097)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="trt6sabjd"/><stop offset="1" class="s-qqz8oax"/></radialGradient><radialGradient id="ifouf8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.29688 -4.54924 0 15.994 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="oi3toxbac"/><stop offset=".676" class="v_f73g3eq"/></radialGradient><radialGradient id="iUC83Ic" cx="0" cy="0" r="1" gradientTransform="matrix(2.90154 0 0 2.93114 15.413 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="ywtk7chnk"/><stop offset=".976" class="yikibccuc"/></radialGradient><radialGradient id="ijRunPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2627 2.6875 -2.36156 -.23084 16.257 20.385)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="ig4gozswr"/><stop offset="1" class="jan8zubqz"/></radialGradient><radialGradient id="iLnMLcb" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 3.017 16.73)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="itwpvbb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.569 14.657)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="ioTAbRb" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.122 14.392)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="i1hTzIb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.709 15.478)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iIZvxwd" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.75 14.657)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="ie4jqdb" cx="0" cy="0" r="1" gradientTransform="rotate(178.354 9.52 8.169)scale(5.43974 9.56592)" gradientUnits="userSpaceOnUse"><stop class="yg62pxmzx"/><stop offset="1" class="qurli5bai"/></radialGradient><radialGradient id="i1iMpsc" cx="0" cy="0" r="1" gradientTransform="rotate(89.979 2.569 13.889)scale(10.0106 11.076)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="d9coszo5i"/><stop offset="1" class="yyhzubb7m"/></radialGradient><radialGradient id="iks8HCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.331 13.385)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="igzrG2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 18.164 14.308)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iPcfgwd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.41 2.637)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWCPZDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 13.802 14.308)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iyJ6fDe" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.744 .444)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iilViob" cx="0" cy="0" r="1" gradientTransform="matrix(-.55214 0 0 -1.73962 11.042 13.092)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="am7cw_b3p"/><stop offset="1" class="w2mtfir4z"/></radialGradient><radialGradient id="iEbYbLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7431 .28093 -.77159 -2.04097 21.64 12.712)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="a5dpq-jqr"/><stop offset="1" class="dneyxcbdm"/></radialGradient><radialGradient id="ilMc2me" cx="0" cy="0" r="1" gradientTransform="rotate(130.522 5.587 5.085)scale(1.38839)" gradientUnits="userSpaceOnUse"><stop class="zi727lnsv"/><stop offset="1" class="z1e4imbuu"/></radialGradient><radialGradient id="ijH8mic" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.4922 .26158 .32385 13.08 4.253)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="iOspXqd" cx="0" cy="0" r="1" gradientTransform="rotate(133.204 8.71 7.203)scale(1.58625 1.61077)" gradientUnits="userSpaceOnUse"><stop class="d0pq7p0hl"/><stop offset="1" class="kfhq2vx5n"/></radialGradient><radialGradient id="i6HCwxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.86008 .8467 0 19.227 7.23)" gradientUnits="userSpaceOnUse"><stop class="e6qjesbba"/><stop offset="1" class="btm953brw"/></radialGradient><radialGradient id="iHTVxLe" cx="0" cy="0" r="1" gradientTransform="rotate(128.601 8.882 6.9)scale(1.32441)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="iyq1_fb9e"/><stop offset="1" class="smjt6t9ha"/></radialGradient><radialGradient id="iprWAmd" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.54688 .29064 .30725 19.83 4.175)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="ia01BWX" cx="0" cy="0" r="1" gradientTransform="matrix(.7294 .35293 -.4289 .8864 9.106 9.349)" gradientUnits="userSpaceOnUse"><stop class="oughljbvw"/><stop offset="1" class="fm5egxmlo"/></radialGradient><radialGradient id="iNe5Amc" cx="0" cy="0" r="1" gradientTransform="matrix(.10577 -.86594 .53006 .06475 9.966 10.284)" gradientUnits="userSpaceOnUse"><stop class="ufab9bcqz"/><stop offset="1" class="rgangdc7y"/></radialGradient><radialGradient id="iPsaLGe" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 8.602 11.303)scale(1.55689 2.04215)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="i2r14vbib"/><stop offset="1" class="izxaz-bvs"/></radialGradient><radialGradient id="ijQY9Cb" cx="0" cy="0" r="1" gradientTransform="matrix(.48626 -.41568 .26982 .31564 22.611 9.066)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ceu0gybff"/><stop offset="1" class="owp1j2bwg"/></radialGradient><radialGradient id="iq31Hcc" cx="0" cy="0" r="1" gradientTransform="rotate(99.989 6.91 11.148)scale(5.58466 4.97233)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fwcf4ds6u"/><stop offset="1" class="pg0l0_b5e"/></radialGradient><radialGradient id="iovwq8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.31715 14 0 16.37 12.307)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="o_0wq7b5h"/><stop offset="1" class="nd4srkbik"/></radialGradient><radialGradient id="iSEn53b" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 2.5 -2.641 2.608 9.963 5.745)" gradientUnits="userSpaceOnUse"><stop class="vy-t95buc"/><stop offset="1" class="sy6a29bji"/></radialGradient><radialGradient id="iwwfhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73437 1.71095 -.24621 -.39349 22.549 5.206)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="zb7xzjb0z"/><stop offset="1" class="mvaqivyxk"/></radialGradient><radialGradient id="imKujHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40552 1.24554 -1.0015 -.32607 22.679 5.719)" gradientUnits="userSpaceOnUse"><stop class="pldarnz2e"/><stop offset="1" class="sk_xim0ag"/></radialGradient><radialGradient id="i8z60vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37873 .96346 -.87532 -1.2526 15.68 9.806)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="rpngv328y"/><stop offset="1" class="t-rizvbci"/></radialGradient><radialGradient id="irCHEVn" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 .5625 -.53002 -.60363 18.807 9.776)" gradientUnits="userSpaceOnUse"><stop class="xp17b02vv"/><stop offset="1" class="iu34ngpem"/></radialGradient><radialGradient id="iZDC2xd" cx="0" cy="0" r="1" gradientTransform="matrix(.63766 .79277 -.77436 .62286 13.053 9.777)" gradientUnits="userSpaceOnUse"><stop class="dp-wqtbjr"/><stop offset="1" class="b9skxcbce"/></radialGradient><radialGradient id="iaxQkid" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -1.0781 .32438 -.60175 11.697 6.214)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="sdopbqbnf"/><stop offset="1" class="bj8dg0b8l"/></radialGradient><radialGradient id="iCJwfdb" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 10.58 7.516)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="ieNywVb" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 23.257 4.852)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="i2Kf17d" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 3.836 4.541)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iz0Sw1c" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 9.77 4.852)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iwdleKr" cx="0" cy="0" r="1" gradientTransform="rotate(131.102 6.394 8.24)scale(2.51937 2.50772)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="oqfgbbi5b"/><stop offset="1" class="bvgzffjne"/></radialGradient><radialGradient id="iTvHkyi" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 0 0 1.01563 14.557 9.496)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="r7-2wfbcc"/><stop offset="1" class="me2qedj2f"/></radialGradient><radialGradient id="ia6Q7le" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 -.67969 .45049 .56959 16.682 8.917)" gradientUnits="userSpaceOnUse"><stop class="mky8h2bzd"/><stop offset="1" class="dudenh09d"/></radialGradient><radialGradient id="iUCPwrb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.22 -1.443)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iC0wJeI" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 12.994 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iZfcJcb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 14.552 -4.775)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iubs2De" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 19.658 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="ifvdSwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06861 1.1704 -1.32316 -1.20809 16.615 2.453)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iHZGaVd" cx="0" cy="0" r="1" gradientTransform="matrix(.57433 -.42319 .25665 .34832 16.607 2.55)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iH7TL6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.35276 -1.76557 0 15.994 2.495)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="smf6lpbrg"/><stop offset="1" class="h4ps77q_r"/></radialGradient><linearGradient id="iNxl2kb" x1="23.75" x2="23.438" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop offset=".313" class="j7cl_sb5b"/><stop offset="1" class="ih1u_95kr"/></linearGradient><linearGradient id="iHOuBQd" x1="8.125" x2="10.344" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop class="m2u33lbou"/><stop offset=".202" class="ez3oocggw"/></linearGradient><linearGradient id="ipNloxS" x1="8.354" x2="8.12" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop offset=".191" class="g_trrs0xv"/><stop offset="1" class="cjlyh4xsg"/></linearGradient><linearGradient id="ihvFh8c" x1="23.423" x2="24.011" y1="28.188" y2="28.188" gradientUnits="userSpaceOnUse"><stop class="r9e83i3uc"/><stop offset="1" class="aipwkdvhc"/></linearGradient><linearGradient id="i0FDate" x1="15.424" x2="15.658" y1="28.98" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="utflpqb7a"/><stop offset="1" class="k0l9ze_pq"/></linearGradient><linearGradient id="i3SQbDe" x1="16.549" x2="16.283" y1="30.023" y2="30.023" gradientUnits="userSpaceOnUse"><stop offset=".368" class="cgi88gv2t"/><stop offset="1" class="ehqj11bbt"/></linearGradient><linearGradient id="i2laqUd" x1="7.913" x2="7.913" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="ir9X3VR" x1="20.359" x2="20.359" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iDre4dc" x1="19.601" x2="19.805" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="ikKD89c" x1="20.736" x2="20.58" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="io9c6zb" x1="8.933" x2="8.933" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iCPPbCe" x1="8.218" x2="8.367" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iWzzOub" x1="21.379" x2="21.379" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iAMhepd" x1="20.622" x2="20.825" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="ieYhBrd" x1="21.757" x2="21.6" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="izukjFZ" x1="9.953" x2="9.953" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iIDnZSj" x1="9.239" x2="9.387" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iKFImcd" x1="22.399" x2="22.399" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iFCx3ZU" x1="21.642" x2="21.846" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iC5o5Kc" x1="22.777" x2="22.621" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ixg7ckd" x1="10.974" x2="10.974" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i9Rg3ZK" x1="10.259" x2="10.407" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iiYTAZq" x1="23.42" x2="23.42" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iDsARPb" x1="22.662" x2="22.866" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iqmAtWc" x1="23.797" x2="23.641" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ixmFp6b" x1="11.994" x2="11.994" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i8LvJbd" x1="11.279" x2="11.428" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="ionfRCd" x1="24.44" x2="24.44" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="i7EcZvd" x1="23.683" x2="23.886" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iamWsYd" x1="24.338" x2="18.619" y1="21.261" y2="21.261" gradientUnits="userSpaceOnUse"><stop class="aw5v51m2w"/><stop offset="1" class="epa4jwbux"/></linearGradient><linearGradient id="iejUKqO" x1="18.213" x2="13.4" y1="22.839" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".388" class="xoq3wtioq"/><stop offset="1" class="shyqpdbhw"/></linearGradient><linearGradient id="isv1Lsb" x1="15.465" x2="23.617" y1="12.052" y2="9.133" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iw340je" x1="11.238" x2="10.597" y1="14.935" y2="14.935" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iXXMvll" x1="21.837" x2="21.018" y1="13.565" y2="16.101" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="i0OIHTb" x1="10.59" x2="12.902" y1="17.742" y2="17.44" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iHga53c" x1="16.014" x2="16.014" y1="12.091" y2="12.669" gradientUnits="userSpaceOnUse"><stop class="c1yplzojd"/><stop offset="1" class="wurc8ub3v"/></linearGradient><linearGradient id="ieADf5c" x1="15.121" x2="16.059" y1="15.705" y2="15.705" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iUBNS1d" x1="16.924" x2="15.898" y1="16.028" y2="16.013" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iWmsIwc" x1="16.18" x2="16.18" y1="16.77" y2="16.197" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="icj3UJI" x1="14.948" x2="15.383" y1="18.385" y2="17.697" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iYS7Fzc" x1="18.942" x2="18.628" y1="14.029" y2="14.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="issFFRq" x1="14.545" x2="14.231" y1="14.029" y2="14.222" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFbzqEd" x1="12.914" x2="12.914" y1="5.827" y2="7.839" gradientUnits="userSpaceOnUse"><stop class="hn2pq365w"/><stop offset="1" class="ckrbxabiw"/></linearGradient><linearGradient id="igPCvHd" x1="15.791" x2="15.791" y1="12.347" y2="11.964" gradientUnits="userSpaceOnUse"><stop class="dfdb-obom"/><stop offset="1" class="ykc__8bxx"/></linearGradient><linearGradient id="i8FlMae" x1="22.878" x2="22.213" y1="6.73" y2="6.651" gradientUnits="userSpaceOnUse"><stop class="lqxvkgj5w"/><stop offset="1" class="omim8hb6o"/></linearGradient><linearGradient id="igCNT7c" x1="19.362" x2="21.79" y1="7.448" y2="6.014" gradientUnits="userSpaceOnUse"><stop class="o_xhqbdfz"/><stop offset="1" class="cm4ghn5oa"/></linearGradient><linearGradient id="iWKQGxe" x1="16.422" x2="19.127" y1="7.074" y2="6.419" gradientUnits="userSpaceOnUse"><stop class="xgp1qchkh"/><stop offset="1" class="s3wqo851w"/></linearGradient><linearGradient id="iSbcJUc" x1="10.153" x2="12.446" y1="6.075" y2="7.817" gradientUnits="userSpaceOnUse"><stop class="xgzvgdboh"/><stop offset="1" class="a5j92oajv"/></linearGradient><filter id="ijVFzId" width="5.555" height="2.089" x="6.861" y="23.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".25"/></filter><filter id="ipg1qUL" width="5.555" height="3.591" x="18.982" y="21.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".25"/></filter><filter id="iVNaINc" width="1.02" height="3.045" x="7.221" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="i4tfEku" width="1.02" height="3.045" x="8.241" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iT8tPnd" width="1.02" height="3.045" x="9.261" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iHkzsgb" width="1.02" height="3.045" x="10.282" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iOf89mT" width="1.02" height="3.045" x="11.302" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="ibxHFrc" width="6" height="2.728" x="7.08" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.686275 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.584314 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3047" result="effect2_innerShadow_4002_3047"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.521569 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3047" result="effect3_innerShadow_4002_3047"/></filter><filter id="i5W8oLd" width="6" height="2.728" x="18.908" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.886275 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.588235 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3047" result="effect2_innerShadow_4002_3047"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.709804 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3047" result="effect3_innerShadow_4002_3047"/></filter><filter id="iVp6dbl" width="1.594" height="1.594" x="16.607" y="27.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".125"/></filter><filter id="iSlwuhe" width="1.594" height="1.594" x="16.607" y="24.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".125"/></filter><filter id="i3A4MSc" width="8.261" height="7.961" x="11.864" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.631373 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3047" result="effect2_innerShadow_4002_3047"/></filter><filter id="iFL56IS" width="8.25" height="7.07" x="14.167" y="7.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation="1"/></filter><filter id="iXcg9qk" width="3.539" height="3.339" x="9.569" y="12.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="ifxOXse" width="2.99" height="2.99" x="9.743" y="13.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".25"/></filter><filter id="ifTZUpe" width="3.589" height="3.589" x="19.081" y="12.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="ijl3Odc" width="2.99" height="2.99" x="19.255" y="13.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".25"/></filter><filter id="iNFO48b" width="3.26" height="4.181" x="14.117" y="13.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".375"/></filter><filter id="i4CtxCd" width="2.377" height="3.181" x="14.797" y="13.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".125"/></filter><filter id="iotz08b" width="3.617" height="1.472" x="14.177" y="17.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".05"/></filter><filter id="iHtudrc" width=".787" height=".696" x="17.43" y="13.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".05"/></filter><filter id="ibSKyAd" width=".891" height=".913" x="18.27" y="13.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".1"/></filter><filter id="i5xoseb" width=".986" height="1.04" x="13.828" y="13.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".1"/></filter><filter id="iIDIKgl" width=".913" height=".704" x="13.074" y="13.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".05"/></filter><filter id="iXynSYc" width="2.557" height="2.672" x="11.685" y="5.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iEIOPAQ" width="1.521" height="1.521" x="11.84" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.643137 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iZUc5fb" width="2.416" height="2.353" x="17.968" y="5.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.717647 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iBVJUNT" width="1.521" height="1.521" x="18.629" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.572549 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iNM3qNK" width="1.535" height="1.535" x="21.971" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="i1xBLvb" width="1.535" height="1.535" x="8.483" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iHxo80k" width="2.656" height="2.656" x="14.668" y="8.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.443137 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="icUi2cb" width="1.646" height="1.646" x="11.84" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iuS9i6P" width="1.646" height="1.646" x="18.504" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter><filter id="iuGzt3r" width="3.214" height="1.831" x="18.883" y="5.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".05"/></filter><filter id="iDRMmfe" width="2.847" height="3.566" x="15.985" y="3.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".05"/></filter><filter id="iMArZzb" width="2.566" height="1.722" x="9.914" y="5.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3047" stdDeviation=".05"/></filter><filter id="igi6Rgs" width="1.812" height="1.813" x="15.088" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3047"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:prince-medium-light" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a5dpq-jqr {
  stop-color: var(--svg-color--ffd9ab, #FFD9AB);
}

.a5j92oajv {
  stop-color: var(--svg-color--d99c45, #D99C45);
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.aipwkdvhc {
  stop-color: var(--svg-color--1895e8, #1895E8);
  stop-opacity: 0;
}

.am7cw_b3p {
  stop-color: var(--svg-color--dfa281, #DFA281);
}

.asgxu8b-r {
  cx: 20.75px;
  cy: 14.656px;
  r: 0.995px;
}

.atc8o_0_r {
  cx: 20.75px;
  cy: 14.656px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.auvf1abdy {
  d: path("M21.103 13.167c.03-.497-.155-.878-.262-.977l.407-.184c.265.305.437.996.383 1.45c-.044.362-.383.5-.547.523c.005-.154 0-.5.02-.812");
}

.aw5v51m2w {
  stop-color: var(--svg-color--ffca34, #FFCA34);
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

.c1yplzojd {
  stop-color: var(--svg-color--c87e7a, #C87E7A);
}

.c4_z29l-c {
  d: path("M10.921 13.167c-.03-.497.155-.878.262-.977l-.407-.184c-.265.305-.437.996-.382 1.45c.043.362.383.5.547.523c-.006-.154-.001-.5-.02-.812");
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

.d7dg5k-bm {
  fill: var(--svg-color--24599f, #24599F);
  d: path("M24.037 23.89h-.911v.82c0 .148.12.268.268.268h.375c.148 0 .268-.12.268-.267z");
}

.d9coszo5i {
  stop-color: var(--svg-color--b87881, #B87881);
  stop-opacity: 0;
}

.dfdb-obom {
  stop-color: var(--svg-color--ff7468, #FF7468);
}

.dneyxcbdm {
  stop-color: var(--svg-color--f2bb8e, #F2BB8E);
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

.e2_wenbdi {
  d: path("M8.354 22.465c-2.507 2.142-3.565 5.216-4.016 7.5h4.016z");
}

.e324j6gaq {
  d: path("M19.15 5.218c-.362.135-.868.961-1.082 1.317l.664 1.011l1.653-.535c-.43-1.27-.782-1.96-1.235-1.793");
}

.e6qjesbba {
  stop-color: var(--svg-color--c18731, #C18731);
}

.ea9x8-par {
  d: path("M14.615 14.285c0-.288-.235-.48-.298-.538l-.289.278l.178.362z");
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

.epa4jwbux {
  stop-color: var(--svg-color--ffbc10, #FFBC10);
}

.escp53_pi {
  d: path("M11.302 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
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

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
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

.f8xv78wwh {
  d: path("M19.667 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.fiwhz1yao {
  stop-color: var(--svg-color--fad771, #FAD771);
  stop-opacity: 0;
}

.fl1_jabov {
  cx: 11.238px;
  cy: 14.657px;
  r: 1.669px;
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

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gvudu0-9m {
  stop-color: var(--svg-color--c37b21, #C37B21);
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.h_mah-buv {
  stop-color: var(--svg-color--fad771, #FAD771);
}

.h4ps77q_r {
  stop-color: var(--svg-color--d89b45, #D89B45);
}

.hatp33bbn {
  d: path("M10.828 12.606c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853c0-.267.16-.48.43-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.271.266 3.915.426c.214.054.429.267.429.534v.853c0 .32.16.64.375.853c.502.352.471.546.43.96c-.18 1.791-.235 3.601-.356 5.398c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003c-.14-1.816-.2-3.638-.366-5.451");
}

.heg5bdcwd {
  stop-color: var(--svg-color--54b5ff, #54B5FF);
}

.hmc1oabhr {
  fill: var(--svg-color--000, #000);
  d: path("M17.655 14.39c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.hn2pq365w {
  stop-color: var(--svg-color--f6c164, #F6C164);
}

.hqe5c4bli {
  d: path("M23.635 22.456c2.514 2.142 3.575 5.222 4.027 7.508h-4.027z");
}

.i2r14vbib {
  stop-color: var(--svg-color--39b6de, #39B6DE);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i5vxhhb9k {
  cx: 15.994px;
  cy: 20.519px;
  rx: 2.32px;
  ry: 2.297px;
}

.ig4gozswr {
  stop-color: var(--svg-color--c07c6b, #C07C6B);
  stop-opacity: 0;
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

.iukj6rsyu {
  d: path("M13.8 13.498a.892.892 0 0 0-.86 1.127h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.iyq1_fb9e {
  stop-color: var(--svg-color--e4bb48, #E4BB48);
}

.iz7sw1_5z {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.603 14.371l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .521-.7l-.531-1.699c-.114-.376-.645-.376-.765 0");
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

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j7_pugjtz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.985 17.786c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.845c.086-.13-.06-.279-.198-.21c-.4.21-.872.329-1.385.329Z");
}

.j7cl_sb5b {
  stop-color: var(--svg-color--2fa1f8, #2FA1F8);
}

.jan8zubqz {
  stop-color: var(--svg-color--c07c6b, #C07C6B);
}

.jj87kxbfm {
  d: path("M18.166 13.498a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
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

.jxvb9w84e {
  stop-color: var(--svg-color--fc586e, #FC586E);
}

.jzfasvbbp {
  cx: 22.739px;
  cy: 5.184px;
  r: 0.767px;
}

.k0l9ze_pq {
  stop-color: var(--svg-color--da7c13, #DA7C13);
  stop-opacity: 0;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k47d47bgr {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.71 14.534l-.82 1.7c-.102.35.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
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

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
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

.ldyj_nb1e {
  cx: 9.25px;
  cy: 5.184px;
  r: 0.767px;
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lln-5jbqh {
  fill: var(--svg-color--000, #000);
  d: path("M14.31 14.39a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.lqxvkgj5w {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ltsxllb3q {
  stop-color: var(--svg-color--d37902, #D37902);
}

.lup_unb-i {
  stop-color: var(--svg-color--3b77d1, #3B77D1);
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

.mky8h2bzd {
  stop-color: var(--svg-color--52b8f8, #52B8F8);
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

.n4tij1bsl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.592 13.226c-.652 0-1.204.45-1.354 1.059c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.nd4srkbik {
  stop-color: var(--svg-color--fa865b, #FA865B);
  stop-opacity: 0;
}

.ng5rfdb2t {
  d: path("m19.964 9.02l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.nrdc_cb1b {
  cx: 13.53px;
  cy: 13.879px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
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

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oi3toxbac {
  stop-color: var(--svg-color--ab696c, #AB696C);
}

.omim8hb6o {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
  stop-opacity: 0;
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
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

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.prxm8ubjj {
  cx: 22.026px;
  cy: 9.418px;
  r: 0.817px;
}

.q4uf8hbdw {
  stop-color: var(--svg-color--68c4ee, #68C4EE);
}

.qdik7cb2m {
  cx: 20.75px;
  cy: 14.657px;
  r: 1.669px;
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

.qurli5bai {
  stop-color: var(--svg-color--cd9582, #CD9582);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxfkfde9r {
  stop-color: var(--svg-color--3e85e8, #3E85E8);
}

.r4f162bfw {
  d: path("M18.1 13.686c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.r7-2wfbcc {
  stop-color: var(--svg-color--467ec1, #467EC1);
}

.r9e83i3uc {
  stop-color: var(--svg-color--1895e8, #1895E8);
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

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.ryq7ubb8z {
  stop-color: var(--svg-color--54b5ff, #54B5FF);
  stop-opacity: 0;
}

.s-qqz8oax {
  stop-color: var(--svg-color--e68600, #E68600);
  stop-opacity: 0;
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s3wqo851w {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
  stop-opacity: 0;
}

.sblhzud6f {
  stop-color: var(--svg-color--e11f40, #E11F40);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
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

.t46s86b2x {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.985 17.786c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.845c.086-.13-.06-.279-.198-.21c-.4.21-.872.329-1.385.329");
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

.u8ozf6b8x {
  stop-color: var(--svg-color--e5780c, #E5780C);
  stop-opacity: 0;
}

.ud61_vz9g {
  fill: var(--svg-color--ffbf46, #FFBF46);
  d: path("M16.549 29.964h-1.086v-6.28h1.086z");
}

.ufab9bcqz {
  stop-color: var(--svg-color--416ec4, #416EC4);
}

.utflpqb7a {
  stop-color: var(--svg-color--da7c13, #DA7C13);
}

.uv5le6qqz {
  stop-color: var(--svg-color--22478d, #22478D);
}

.uyt1djb3f {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.1 13.686c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.v_f73g3eq {
  stop-color: var(--svg-color--c27e76, #C27E76);
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

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vmhbtsb-a {
  d: path("M8.241 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
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

.w2mtfir4z {
  stop-color: var(--svg-color--f2bb95, #F2BB95);
}

.we5kvqbpm {
  cx: 15.994px;
  cy: 20.206px;
  r: 3.98px;
}

.wurc8ub3v {
  stop-color: var(--svg-color--c87e7a, #C87E7A);
  stop-opacity: 0;
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.xapif3b3d {
  cx: 11.238px;
  cy: 14.656px;
  r: 0.995px;
}

.xgp1qchkh {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
}

.xgzvgdboh {
  stop-color: var(--svg-color--e4aa42, #E4AA42);
}

.xhy6cj0-l {
  cx: 13.53px;
  cy: 13.879px;
  rx: 0.389px;
  ry: 0.197px;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
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

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xty8ecqkp {
  d: path("m15.603 14.371l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .521-.7l-.531-1.699c-.114-.376-.645-.376-.765 0");
}

.xu8dt4-7y {
  d: path("M18.96 14.273a.84.84 0 0 0-.23-.463l-.26.285l.117.228z");
}

.yg62pxmzx {
  stop-color: var(--svg-color--f9bf9e, #F9BF9E);
}

.yikibccuc {
  stop-color: var(--svg-color--9c5944, #9C5944);
}

.ykc__8bxx {
  stop-color: var(--svg-color--ff865b, #FF865B);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.ywtk7chnk {
  stop-color: var(--svg-color--9c5944, #9C5944);
  stop-opacity: 0;
}

.yyhzubb7m {
  stop-color: var(--svg-color--a3666e, #A3666E);
}

.z1e4imbuu {
  stop-color: var(--svg-color--e2aa40, #E2AA40);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zb7xzjb0z {
  stop-color: var(--svg-color--cd9d50, #CD9D50);
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zi727lnsv {
  stop-color: var(--svg-color--f1c752, #F1C752);
}

.zl0i2nl5t {
  stop-color: var(--svg-color--fca135, #FCA135);
}

.zpm1xbbni {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.373 13.226c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.341h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.zupcoccwr {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
}

</style>
