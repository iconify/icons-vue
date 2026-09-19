<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4X6gQb)" class="f0sz96v9r"/><path fill="url(#iP6PLfc)" class="f0sz96v9r"/><path fill="url(#iQIno6d)" class="e2_wenbdi"/><path fill="url(#iBGggtc)" class="e2_wenbdi"/><path fill="url(#iMyPqOK)" class="hqe5c4bli"/><path fill="url(#iwSpWAe)" class="hqe5c4bli"/><g filter="url(#iFCtGZc)"><path class="hpg9gtbjd"/><path class="wo3ljv8tf"/></g><g filter="url(#iy24B5b)"><path class="zw4segwhh"/><path class="hq6570jxd"/></g><path class="ud61_vz9g"/><path fill="url(#i0FDate)" class="iu8kp3ahw"/><path fill="url(#i3SQbDe)" class="iu8kp3ahw"/><path fill="url(#iyxEWTc)" class="iu8kp3ahw"/><circle fill="url(#iZ3BMQx)" class="kfayvkisl"/><g filter="url(#iK1xBje)"><path fill="url(#i2laqUd)" class="d3e9_irck"/><path fill="url(#iIKZtAe)" class="d3e9_irck"/><path fill="url(#iHMIXWh)" class="d3e9_irck"/></g><path fill="url(#ir9X3VR)" class="f8xv78wwh"/><path fill="url(#iDre4dc)" class="f8xv78wwh"/><path fill="url(#iZFhrYb)" class="f8xv78wwh"/><path fill="url(#ikKD89c)" class="f8xv78wwh"/><path fill="url(#imfQuDc)" class="f8xv78wwh"/><g filter="url(#iTBEtOb)"><path fill="url(#io9c6zb)" class="vmhbtsb-a"/><path fill="url(#iIfxIeM)" class="vmhbtsb-a"/><path fill="url(#iUfBlYz)" class="vmhbtsb-a"/><path fill="url(#iCPPbCe)" class="vmhbtsb-a"/></g><path fill="url(#iWzzOub)" class="shgrjqbiz"/><path fill="url(#iAMhepd)" class="shgrjqbiz"/><path fill="url(#ivjzpvb)" class="shgrjqbiz"/><path fill="url(#ieYhBrd)" class="shgrjqbiz"/><path fill="url(#i9lS2bb)" class="shgrjqbiz"/><g filter="url(#ibgL0nb)"><path fill="url(#izukjFZ)" class="rnq8zfbyk"/><path fill="url(#iAyKCmx)" class="rnq8zfbyk"/><path fill="url(#i4fzUHl)" class="rnq8zfbyk"/><path fill="url(#iIDnZSj)" class="rnq8zfbyk"/></g><path fill="url(#iKFImcd)" class="kiolp_-pe"/><path fill="url(#iFCx3ZU)" class="kiolp_-pe"/><path fill="url(#iN3ekpY)" class="kiolp_-pe"/><path fill="url(#iC5o5Kc)" class="kiolp_-pe"/><path fill="url(#imus0Oe)" class="kiolp_-pe"/><g filter="url(#i1jHkMe)"><path fill="url(#ixg7ckd)" class="swjgceb9v"/><path fill="url(#iYIbosd)" class="swjgceb9v"/><path fill="url(#iS5Q3Vc)" class="swjgceb9v"/><path fill="url(#i9Rg3ZK)" class="swjgceb9v"/></g><path fill="url(#iiYTAZq)" class="kbcpr6bot"/><path fill="url(#iDsARPb)" class="kbcpr6bot"/><path fill="url(#iwVkT9d)" class="kbcpr6bot"/><path fill="url(#iqmAtWc)" class="kbcpr6bot"/><path fill="url(#iSeQN2N)" class="kbcpr6bot"/><g filter="url(#icwR9wd)"><path fill="url(#ixmFp6b)" class="escp53_pi"/><path fill="url(#ixyyVtb)" class="escp53_pi"/><path fill="url(#iAJYwfd)" class="escp53_pi"/><path fill="url(#i8LvJbd)" class="escp53_pi"/></g><path fill="url(#ionfRCd)" class="c0g3mbbdp"/><path fill="url(#i7EcZvd)" class="c0g3mbbdp"/><path fill="url(#iqIlRze)" class="c0g3mbbdp"/><path fill="url(#iraNcty)" class="c0g3mbbdp"/><g filter="url(#iZ2wRSb)"><path fill="url(#i8a7U2b)" class="fw-_ge0oq"/></g><g filter="url(#igrnXdc)"><path fill="url(#iamWsYd)" class="sgtr8ibeb"/><path fill="url(#iLswA2c)" class="sgtr8ibeb"/></g><g filter="url(#iNWAy3d)"><circle fill="url(#iejUKqO)" class="we5kvqbpm"/><circle fill="url(#iz3N9Og)" class="we5kvqbpm"/></g><ellipse fill="url(#iaypyjc)" class="i5vxhhb9k"/><ellipse fill="url(#iIO83sT)" class="i5vxhhb9k"/><ellipse fill="url(#ikoOD3c)" class="i5vxhhb9k"/><circle fill="url(#iLnMLcb)" class="f-t10ph2f"/><path fill="url(#iuRbXYc)" class="x9yzxpkmm"/><path fill="url(#i7SGk9b)" class="x9yzxpkmm"/><path fill="url(#iLEZZ2c)" class="rp-i_6biq"/><path fill="url(#iwdpwuv)" class="rp-i_6biq"/><g filter="url(#iv1Fbze)"><path fill="url(#iRAmQjb)" class="i2l-0n8bq"/></g><path fill="url(#iQK6ftc)" class="i2l-0n8bq"/><path fill="url(#igJvytd)" class="i2l-0n8bq"/><path fill="url(#itcT5nb)" class="i2l-0n8bq"/><path fill="url(#iszqEtb)" class="i2l-0n8bq"/><g filter="url(#iU4FHou)"><path class="gf8nacb0x"/></g><g filter="url(#idFprbe)"><path fill="url(#iNN6PBc)" class="w5vv1ga9t"/><path fill="url(#i5WtJJb)" class="w5vv1ga9t"/><path fill="url(#iAob3Wd)" class="w5vv1ga9t"/><path fill="url(#id0j4Hd)" class="w5vv1ga9t"/></g><g filter="url(#ipDpRvc)"><path stroke="url(#iyhmRld)" class="fqsay0-oq"/></g><path fill="url(#ioUM7wc)" class="bh78v-hfd"/><path class="m2fe6ac_o"/><path fill="url(#i0vyG8d)" class="ryyd73bhi"/><path class="avzkhub4m"/><g filter="url(#iPFVIdc)"><path class="jtr2kbb9c"/><path fill="url(#ifjTTDb)" class="fjxmamblp"/></g><g filter="url(#iRqgCPc)"><path fill="url(#inEe8kP)" class="m0c3dhblj"/></g><path class="jy5rmybcl"/><path fill="url(#i9l2Vyy)" class="y6-34fvwd"/><path class="tlvsbm58e"/><g filter="url(#imceLAr)"><path fill="url(#iPN6ppX)" class="wgfty7mbu"/></g><g filter="url(#iFCCvDC)"><ellipse transform="rotate(-27.914 13.54 13.937)" class="n5q_2-c9z"/><ellipse fill="url(#ixqWmrd)" transform="rotate(-27.914 13.54 13.937)" class="k8wj80bfs"/></g><path fill="url(#izbP5Bb)" class="x6pg6seap"/><path fill="url(#iRZvUZb)" class="x6pg6seap"/><path fill="url(#iUx42Gd)" class="x6pg6seap"/><path fill="url(#iyZ46Bd)" class="t4qznn7ln"/><path fill="url(#imp5Krd)" class="t4qznn7ln"/><g filter="url(#iNFdfMr)"><path class="gqfytjify"/></g><g filter="url(#iur7Cud)"><path class="rrf7pv4xq"/></g><g filter="url(#iti50Ok)"><path fill="url(#iFbzqEd)" class="cz54lzbgf"/></g><g filter="url(#iE20MGi)"><circle fill="url(#ilMc2me)" class="f19u2wb6f"/><circle fill="url(#ijH8mic)" class="f19u2wb6f"/></g><g filter="url(#itKvJEK)"><path fill="url(#iOspXqd)" class="e324j6gaq"/><path fill="url(#i6HCwxb)" class="e324j6gaq"/></g><g filter="url(#iut7Dud)"><circle fill="url(#iHTVxLe)" class="qk8v1bc2n"/><circle fill="url(#iprWAmd)" class="qk8v1bc2n"/></g><circle fill="url(#ia01BWX)" class="v-aq_fb5e"/><circle fill="url(#iNe5Amc)" class="v-aq_fb5e"/><circle fill="url(#iPsaLGe)" class="prxm8ubjj"/><circle fill="url(#ijQY9Cb)" class="prxm8ubjj"/><path fill="url(#iq31Hcc)" class="jqlapeb1l"/><path fill="url(#iovwq8b)" class="jqlapeb1l"/><path fill="url(#igPCvHd)" class="jqlapeb1l"/><path fill="url(#iSEn53b)" class="jqlapeb1l"/><path fill="url(#iwwfhfb)" class="jqlapeb1l"/><path fill="url(#imKujHe)" class="jqlapeb1l"/><path fill="url(#i8FlMae)" class="jqlapeb1l"/><path fill="url(#i8z60vd)" class="jqlapeb1l"/><path fill="url(#irCHEVn)" class="jqlapeb1l"/><path fill="url(#iZDC2xd)" class="jqlapeb1l"/><path fill="url(#iaxQkid)" class="jqlapeb1l"/><g filter="url(#iCjD8xc)"><circle fill="url(#iCJwfdb)" class="jzfasvbbp"/><circle fill="url(#ieNywVb)" class="jzfasvbbp"/></g><g filter="url(#iPjIuBb)"><circle fill="url(#i2Kf17d)" class="ldyj_nb1e"/><circle fill="url(#iz0Sw1c)" class="ldyj_nb1e"/></g><g filter="url(#iSrN2Me)"><circle fill="url(#iwdleKr)" class="ks0-jgbez"/><circle fill="url(#iTvHkyi)" class="ks0-jgbez"/><circle fill="url(#ia6Q7le)" class="ks0-jgbez"/></g><g filter="url(#i5jgnqe)"><circle fill="url(#iUCPwrb)" class="pimf00m2w"/><circle fill="url(#iC0wJeI)" class="pimf00m2w"/></g><g filter="url(#iBS4Cld)"><circle fill="url(#iZfcJcb)" class="ql2irpb2m"/><circle fill="url(#iubs2De)" class="ql2irpb2m"/></g><g filter="url(#iFLPgte)"><path stroke="url(#igCNT7c)" class="ey-1_lflg"/></g><g filter="url(#i0DGObc)"><path stroke="url(#iWKQGxe)" class="o_84ttbae"/></g><g filter="url(#ijdElUb)"><path stroke="url(#iSbcJUc)" class="qp7qzchye"/></g><g filter="url(#i9MsMuc)"><circle fill="url(#ifvdSwb)" class="kowfi484h"/><circle fill="url(#iHZGaVd)" class="kowfi484h"/></g><circle fill="url(#iH7TL6c)" class="kowfi484h"/><defs><radialGradient id="i4X6gQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.5625 -14.1309 0 16 22.402)" gradientUnits="userSpaceOnUse"><stop class="vsg8c7gji"/><stop offset=".542" class="x9knvh_3c"/></radialGradient><radialGradient id="iP6PLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9375 0 0 -23.6312 23.807 29.964)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="q5a0_7mqo"/><stop offset="1" class="rrwvrg1ho"/></radialGradient><radialGradient id="iQIno6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.28332 4.28735 0 8.354 29.67)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="fsr110b8t"/><stop offset="1" class="jo4sxnm8i"/></radialGradient><radialGradient id="iMyPqOK" cx="0" cy="0" r="1" gradientTransform="matrix(3.36005 0 0 6.32267 23.847 28.93)" gradientUnits="userSpaceOnUse"><stop class="u_7404bbu"/><stop offset="1" class="v4gg9p-ym"/></radialGradient><radialGradient id="iyxEWTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .69531 -2.16649 0 16.006 23.956)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="o_4gny8-z"/><stop offset=".622" class="jrd3jzgth"/></radialGradient><radialGradient id="iZ3BMQx" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 2.282 18.291)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="iIKZtAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 8.241 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iHMIXWh" cx="0" cy="0" r="1" gradientTransform="rotate(-84.161 17.495 8.173)scale(2.35566 2.26902)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="o375d620d"/><stop offset="1" class="tgzndhrni"/></radialGradient><radialGradient id="iZFhrYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 20.687 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="imfQuDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 20.177 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iIfxIeM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 9.261 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iUfBlYz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 8.751 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ivjzpvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 21.707 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="i9lS2bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 21.197 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iAyKCmx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 10.282 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="i4fzUHl" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 9.772 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iN3ekpY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 22.727 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="imus0Oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 22.217 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iYIbosd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 11.302 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iS5Q3Vc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 10.792 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iwVkT9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 23.748 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iSeQN2N" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 23.238 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".847" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="ixyyVtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.24609 .52291 0 12.322 24.566)" gradientUnits="userSpaceOnUse"><stop class="w_ld-kbgg"/><stop offset="1" class="v1k_mhzfg"/></radialGradient><radialGradient id="iAJYwfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 2.13715 0 11.812 24.664)" gradientUnits="userSpaceOnUse"><stop offset=".887" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="iqIlRze" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.94531 .573 0 24.768 24.566)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="xmc2l2-sl"/><stop offset="1" class="pd-kjcckg"/></radialGradient><radialGradient id="iraNcty" cx="0" cy="0" r="1" gradientTransform="rotate(-97.511 23.055 1.525)scale(2.28523 2.20118)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="o375d620d"/><stop offset=".974" class="tgzndhrni"/></radialGradient><radialGradient id="i8a7U2b" cx="0" cy="0" r="1" gradientTransform="matrix(3.09374 -3.6172 12.35097 10.56365 9.4 23.59)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="tjsj1op7o"/><stop offset="1" class="gvudu0-9m"/></radialGradient><radialGradient id="iLswA2c" cx="0" cy="0" r="1" gradientTransform="matrix(3.57813 0 0 3.06696 20.104 22.246)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="mqzky-b6t"/><stop offset="1" class="fnx367bbh"/></radialGradient><radialGradient id="iz3N9Og" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 1.30469 -.7272 -.3919 17.533 21.097)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="trt6sabjd"/><stop offset="1" class="s-qqz8oax"/></radialGradient><radialGradient id="iaypyjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.29688 -4.54924 0 15.994 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="inf8k3cdd"/><stop offset=".676" class="m8qxht3di"/></radialGradient><radialGradient id="iIO83sT" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.43739 -2.14179 0 15.994 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="yg19gcced"/><stop offset="1" class="dl6zet80s"/></radialGradient><radialGradient id="ikoOD3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.90154 0 0 2.93114 15.413 20.519)" gradientUnits="userSpaceOnUse"><stop offset=".892" class="jnzs3bbbz"/><stop offset="1" class="p-h-_brca"/></radialGradient><radialGradient id="iLnMLcb" cx="0" cy="0" r="1" gradientTransform="rotate(129.591 3.017 16.73)scale(.96356)" gradientUnits="userSpaceOnUse"><stop class="w_324qbof"/><stop offset="1" class="zl0i2nl5t"/></radialGradient><radialGradient id="iuRbXYc" cx="0" cy="0" r="1" gradientTransform="rotate(103.169 4.47 16.487)scale(3.82897 4.54852)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="i7SGk9b" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 -5.492 28.53)scale(.49786 .42293)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iLEZZ2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.33305 3.92345 -1.7834 .60594 10.446 16.008)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iwdpwuv" cx="0" cy="0" r="1" gradientTransform="matrix(.31846 .9973 -.87484 .27936 11.108 16)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iRAmQjb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24801 18.801 14.95)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iQK6ftc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40256 6.10192 -2.24332 -.148 21.15 14.717)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="igJvytd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41386 1.70221 0 13.902 13.769)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="itcT5nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53524 1.99125 0 18.482 13.357)" gradientUnits="userSpaceOnUse"><stop offset=".327" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="iszqEtb" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.602 14.438)scale(8.9402)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="efd1-abcd"/><stop offset=".973" class="z0ydb9xti"/></radialGradient><radialGradient id="iyhmRld" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 22.998 -3.568)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="ioUM7wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.994 18.488)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="i0vyG8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.176 14.033)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ifjTTDb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.43 2.664)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9l2Vyy" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.812 14.033)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ixqWmrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.526 14.252)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRZvUZb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.611 14.047)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iUx42Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.972 14.591)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="imp5Krd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.468 11.51)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="ilMc2me" cx="0" cy="0" r="1" gradientTransform="rotate(130.522 5.587 5.085)scale(1.38839)" gradientUnits="userSpaceOnUse"><stop class="zi727lnsv"/><stop offset="1" class="z1e4imbuu"/></radialGradient><radialGradient id="ijH8mic" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.4922 .26158 .32385 13.08 4.253)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="iOspXqd" cx="0" cy="0" r="1" gradientTransform="rotate(133.204 8.71 7.203)scale(1.58625 1.61077)" gradientUnits="userSpaceOnUse"><stop class="d0pq7p0hl"/><stop offset="1" class="kfhq2vx5n"/></radialGradient><radialGradient id="i6HCwxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.86008 .8467 0 19.227 7.23)" gradientUnits="userSpaceOnUse"><stop class="e6qjesbba"/><stop offset="1" class="btm953brw"/></radialGradient><radialGradient id="iHTVxLe" cx="0" cy="0" r="1" gradientTransform="rotate(128.601 8.882 6.9)scale(1.32441)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="iyq1_fb9e"/><stop offset="1" class="smjt6t9ha"/></radialGradient><radialGradient id="iprWAmd" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.54688 .29064 .30725 19.83 4.175)" gradientUnits="userSpaceOnUse"><stop class="jnpel9bup"/><stop offset="1" class="eif22vbdr"/></radialGradient><radialGradient id="ia01BWX" cx="0" cy="0" r="1" gradientTransform="matrix(.7294 .35293 -.4289 .8864 9.106 9.349)" gradientUnits="userSpaceOnUse"><stop class="oughljbvw"/><stop offset="1" class="fm5egxmlo"/></radialGradient><radialGradient id="iNe5Amc" cx="0" cy="0" r="1" gradientTransform="matrix(.10577 -.86594 .53006 .06475 9.966 10.284)" gradientUnits="userSpaceOnUse"><stop class="ufab9bcqz"/><stop offset="1" class="rgangdc7y"/></radialGradient><radialGradient id="iPsaLGe" cx="0" cy="0" r="1" gradientTransform="rotate(117.967 8.602 11.303)scale(1.55689 2.04215)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="i2r14vbib"/><stop offset="1" class="izxaz-bvs"/></radialGradient><radialGradient id="ijQY9Cb" cx="0" cy="0" r="1" gradientTransform="matrix(.48626 -.41568 .26982 .31564 22.611 9.066)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="ceu0gybff"/><stop offset="1" class="owp1j2bwg"/></radialGradient><radialGradient id="iq31Hcc" cx="0" cy="0" r="1" gradientTransform="rotate(99.989 6.91 11.148)scale(5.58466 4.97233)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fwcf4ds6u"/><stop offset="1" class="pg0l0_b5e"/></radialGradient><radialGradient id="iovwq8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.31715 14 0 16.37 12.307)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="o_0wq7b5h"/><stop offset="1" class="nd4srkbik"/></radialGradient><radialGradient id="iSEn53b" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 2.5 -2.641 2.608 9.963 5.745)" gradientUnits="userSpaceOnUse"><stop class="vy-t95buc"/><stop offset="1" class="sy6a29bji"/></radialGradient><radialGradient id="iwwfhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.73437 1.71095 -.24621 -.39349 22.549 5.206)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="zb7xzjb0z"/><stop offset="1" class="mvaqivyxk"/></radialGradient><radialGradient id="imKujHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.40552 1.24554 -1.0015 -.32607 22.679 5.719)" gradientUnits="userSpaceOnUse"><stop class="pldarnz2e"/><stop offset="1" class="sk_xim0ag"/></radialGradient><radialGradient id="i8z60vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37873 .96346 -.87532 -1.2526 15.68 9.806)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="rpngv328y"/><stop offset="1" class="t-rizvbci"/></radialGradient><radialGradient id="irCHEVn" cx="0" cy="0" r="1" gradientTransform="matrix(-.64062 .5625 -.53002 -.60363 18.807 9.776)" gradientUnits="userSpaceOnUse"><stop class="xp17b02vv"/><stop offset="1" class="iu34ngpem"/></radialGradient><radialGradient id="iZDC2xd" cx="0" cy="0" r="1" gradientTransform="matrix(.63766 .79277 -.77436 .62286 13.053 9.777)" gradientUnits="userSpaceOnUse"><stop class="dp-wqtbjr"/><stop offset="1" class="b9skxcbce"/></radialGradient><radialGradient id="iaxQkid" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -1.0781 .32438 -.60175 11.697 6.214)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="sdopbqbnf"/><stop offset="1" class="bj8dg0b8l"/></radialGradient><radialGradient id="iCJwfdb" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 10.58 7.516)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="ieNywVb" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 23.257 4.852)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="i2Kf17d" cx="0" cy="0" r="1" gradientTransform="rotate(132.397 3.836 4.541)scale(1.34189 1.51703)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iz0Sw1c" cx="0" cy="0" r="1" gradientTransform="matrix(.48628 -.35831 .2173 .29492 9.77 4.852)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iwdleKr" cx="0" cy="0" r="1" gradientTransform="rotate(131.102 6.394 8.24)scale(2.51937 2.50772)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="oqfgbbi5b"/><stop offset="1" class="bvgzffjne"/></radialGradient><radialGradient id="iTvHkyi" cx="0" cy="0" r="1" gradientTransform="matrix(.76563 0 0 1.01563 14.557 9.496)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="r7-2wfbcc"/><stop offset="1" class="me2qedj2f"/></radialGradient><radialGradient id="ia6Q7le" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 -.67969 .45049 .56959 16.682 8.917)" gradientUnits="userSpaceOnUse"><stop class="mky8h2bzd"/><stop offset="1" class="dudenh09d"/></radialGradient><radialGradient id="iUCPwrb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 11.22 -1.443)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iC0wJeI" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 12.994 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="iZfcJcb" cx="0" cy="0" r="1" gradientTransform="rotate(-90 14.552 -4.775)scale(1.04688)" gradientUnits="userSpaceOnUse"><stop class="m8_9xackt"/><stop offset="1" class="sblhzud6f"/></radialGradient><radialGradient id="iubs2De" cx="0" cy="0" r="1" gradientTransform="matrix(.67969 -.63281 .411 .44144 19.658 9.09)" gradientUnits="userSpaceOnUse"><stop class="jxvb9w84e"/><stop offset="1" class="a-oylkk7f"/></radialGradient><radialGradient id="ifvdSwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06861 1.1704 -1.32316 -1.20809 16.615 2.453)" gradientUnits="userSpaceOnUse"><stop class="l0yglmb3r"/><stop offset="1" class="kz6jvgbzd"/></radialGradient><radialGradient id="iHZGaVd" cx="0" cy="0" r="1" gradientTransform="matrix(.57433 -.42319 .25665 .34832 16.607 2.55)" gradientUnits="userSpaceOnUse"><stop class="h_mah-buv"/><stop offset="1" class="fiwhz1yao"/></radialGradient><radialGradient id="iH7TL6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.35276 -1.76557 0 15.994 2.495)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="smf6lpbrg"/><stop offset="1" class="h4ps77q_r"/></radialGradient><linearGradient id="iBGggtc" x1="8.354" x2="8.12" y1="29.964" y2="29.964" gradientUnits="userSpaceOnUse"><stop offset=".191" class="wjgmmu2gq"/><stop offset="1" class="a7d2l_-4t"/></linearGradient><linearGradient id="iwSpWAe" x1="23.423" x2="24.011" y1="28.188" y2="28.188" gradientUnits="userSpaceOnUse"><stop class="aosu0gbmr"/><stop offset="1" class="p7fclrrnf"/></linearGradient><linearGradient id="i0FDate" x1="15.424" x2="15.658" y1="28.98" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="utflpqb7a"/><stop offset="1" class="k0l9ze_pq"/></linearGradient><linearGradient id="i3SQbDe" x1="16.549" x2="16.283" y1="30.023" y2="30.023" gradientUnits="userSpaceOnUse"><stop offset=".368" class="cgi88gv2t"/><stop offset="1" class="ehqj11bbt"/></linearGradient><linearGradient id="i2laqUd" x1="7.913" x2="7.913" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="ir9X3VR" x1="20.359" x2="20.359" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iDre4dc" x1="19.601" x2="19.805" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="ikKD89c" x1="20.736" x2="20.58" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="io9c6zb" x1="8.933" x2="8.933" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iCPPbCe" x1="8.218" x2="8.367" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iWzzOub" x1="21.379" x2="21.379" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iAMhepd" x1="20.622" x2="20.825" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="ieYhBrd" x1="21.757" x2="21.6" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="izukjFZ" x1="9.953" x2="9.953" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="iIDnZSj" x1="9.239" x2="9.387" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iKFImcd" x1="22.399" x2="22.399" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iFCx3ZU" x1="21.642" x2="21.846" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iC5o5Kc" x1="22.777" x2="22.621" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ixg7ckd" x1="10.974" x2="10.974" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i9Rg3ZK" x1="10.259" x2="10.407" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="iiYTAZq" x1="23.42" x2="23.42" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="iDsARPb" x1="22.662" x2="22.866" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iqmAtWc" x1="23.797" x2="23.641" y1="23.871" y2="23.871" gradientUnits="userSpaceOnUse"><stop offset=".1" class="zupcoccwr"/><stop offset="1" class="dpitlhbpx"/></linearGradient><linearGradient id="ixmFp6b" x1="11.994" x2="11.994" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop offset=".442" class="bc7d6obfi"/><stop offset="1" class="ltsxllb3q"/></linearGradient><linearGradient id="i8LvJbd" x1="11.279" x2="11.428" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="o-695ij2e"/><stop offset="1" class="j0k3id93s"/></linearGradient><linearGradient id="ionfRCd" x1="24.44" x2="24.44" y1="24.793" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="mx5qf9bzw"/><stop offset="1" class="l2jyntb4f"/></linearGradient><linearGradient id="i7EcZvd" x1="23.683" x2="23.886" y1="23.717" y2="23.717" gradientUnits="userSpaceOnUse"><stop class="rez3ddccp"/><stop offset="1" class="u8ozf6b8x"/></linearGradient><linearGradient id="iamWsYd" x1="24.338" x2="18.619" y1="21.261" y2="21.261" gradientUnits="userSpaceOnUse"><stop class="aw5v51m2w"/><stop offset="1" class="epa4jwbux"/></linearGradient><linearGradient id="iejUKqO" x1="18.213" x2="13.4" y1="22.839" y2="19.277" gradientUnits="userSpaceOnUse"><stop offset=".388" class="xoq3wtioq"/><stop offset="1" class="shyqpdbhw"/></linearGradient><linearGradient id="iNN6PBc" x1="15.994" x2="16.848" y1="15.778" y2="15.778" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="i5WtJJb" x1="14.921" x2="15.995" y1="15.622" y2="15.682" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iAob3Wd" x1="15.994" x2="15.994" y1="16.177" y2="17.029" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="id0j4Hd" x1="15.994" x2="15.994" y1="13.929" y2="14.349" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="inEe8kP" x1="18.953" x2="18.64" y1="14.087" y2="14.28" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPN6ppX" x1="14.555" x2="14.242" y1="14.087" y2="14.28" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izbP5Bb" x1="22.43" x2="21.223" y1="14.114" y2="16.29" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iyZ46Bd" x1="10.144" x2="11.602" y1="14.818" y2="14.69" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iFbzqEd" x1="12.914" x2="12.914" y1="5.827" y2="7.839" gradientUnits="userSpaceOnUse"><stop class="hn2pq365w"/><stop offset="1" class="ckrbxabiw"/></linearGradient><linearGradient id="igPCvHd" x1="15.791" x2="15.791" y1="12.347" y2="11.964" gradientUnits="userSpaceOnUse"><stop class="dfdb-obom"/><stop offset="1" class="ykc__8bxx"/></linearGradient><linearGradient id="i8FlMae" x1="22.878" x2="22.213" y1="6.73" y2="6.651" gradientUnits="userSpaceOnUse"><stop class="lqxvkgj5w"/><stop offset="1" class="omim8hb6o"/></linearGradient><linearGradient id="igCNT7c" x1="19.362" x2="21.79" y1="7.448" y2="6.014" gradientUnits="userSpaceOnUse"><stop class="o_xhqbdfz"/><stop offset="1" class="cm4ghn5oa"/></linearGradient><linearGradient id="iWKQGxe" x1="16.422" x2="19.127" y1="7.074" y2="6.419" gradientUnits="userSpaceOnUse"><stop class="xgp1qchkh"/><stop offset="1" class="s3wqo851w"/></linearGradient><linearGradient id="iSbcJUc" x1="10.153" x2="12.446" y1="6.075" y2="7.817" gradientUnits="userSpaceOnUse"><stop class="xgzvgdboh"/><stop offset="1" class="a5j92oajv"/></linearGradient><filter id="iFCtGZc" width="6.055" height="2.589" x="6.611" y="23.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".375"/></filter><filter id="iy24B5b" width="6.055" height="4.091" x="18.732" y="21.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".375"/></filter><filter id="iK1xBje" width="1.02" height="3.045" x="7.221" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iTBEtOb" width="1.02" height="3.045" x="8.241" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="ibgL0nb" width="1.02" height="3.045" x="9.261" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="i1jHkMe" width="1.02" height="3.045" x="10.282" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="icwR9wd" width="1.02" height="3.045" x="11.302" y="21.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.537255 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iZ2wRSb" width="6" height="2.728" x="7.08" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.686275 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.584314 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3518" result="effect2_innerShadow_13929_3518"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.521569 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_13929_3518" result="effect3_innerShadow_13929_3518"/></filter><filter id="igrnXdc" width="6" height="2.728" x="18.908" y="19.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.886275 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.588235 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3518" result="effect2_innerShadow_13929_3518"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.709804 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_13929_3518" result="effect3_innerShadow_13929_3518"/></filter><filter id="iNWAy3d" width="8.261" height="7.961" x="11.864" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.905882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.631373 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3518" result="effect2_innerShadow_13929_3518"/></filter><filter id="iv1Fbze" width="10.72" height="12.542" x="10.93" y="8.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13929_3518" result="effect2_innerShadow_13929_3518"/></filter><filter id="iU4FHou" width="3.877" height="4.9" x="13.848" y="13.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".5"/></filter><filter id="idFprbe" width="2.077" height="3.1" x="14.955" y="13.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".05"/></filter><filter id="ipDpRvc" width="3.718" height="1.573" x="14.134" y="17.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".05"/></filter><filter id="iPFVIdc" width=".787" height=".696" x="17.441" y="13.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".05"/></filter><filter id="iRqgCPc" width=".891" height=".913" x="18.281" y="13.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".1"/></filter><filter id="imceLAr" width=".986" height="1.04" x="13.839" y="13.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".1"/></filter><filter id="iFCCvDC" width=".913" height=".705" x="13.084" y="13.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".05"/></filter><filter id="iNFdfMr" width="1.329" height="2.379" x="9.961" y="13.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".125"/></filter><filter id="iur7Cud" width="1.447" height="2.403" x="20.705" y="13.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".125"/></filter><filter id="iti50Ok" width="2.557" height="2.672" x="11.685" y="5.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.670588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iE20MGi" width="1.521" height="1.521" x="11.84" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.643137 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="itKvJEK" width="2.416" height="2.353" x="17.968" y="5.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.717647 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iut7Dud" width="1.521" height="1.521" x="18.629" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.572549 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iCjD8xc" width="1.535" height="1.535" x="21.971" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iPjIuBb" width="1.535" height="1.535" x="8.483" y="4.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iSrN2Me" width="2.656" height="2.656" x="14.668" y="8.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.443137 0 0 0 0 0.803922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="i5jgnqe" width="1.646" height="1.646" x="11.84" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iBS4Cld" width="1.646" height="1.646" x="18.504" y="8.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.168627 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter><filter id="iFLPgte" width="3.214" height="1.831" x="18.883" y="5.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".05"/></filter><filter id="i0DGObc" width="2.847" height="3.566" x="15.985" y="3.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".05"/></filter><filter id="ijdElUb" width="2.566" height="1.722" x="9.914" y="5.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13929_3518" stdDeviation=".05"/></filter><filter id="i9MsMuc" width="1.812" height="1.812" x="15.088" y="2.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.666667 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13929_3518"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-crown" /></template>
<style>
.a-oylkk7f {
  stop-color: var(--svg-color--fc586e, #FC586E);
  stop-opacity: 0;
}

.a5j92oajv {
  stop-color: var(--svg-color--d99c45, #D99C45);
}

.a7d2l_-4t {
  stop-color: var(--svg-color--ff4c2c, #FF4C2C);
  stop-opacity: 0;
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.aosu0gbmr {
  stop-color: var(--svg-color--ff4d0c, #FF4D0C);
}

.avzkhub4m {
  fill: var(--svg-color--000, #000);
  d: path("M17.667 14.449c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.aw5v51m2w {
  stop-color: var(--svg-color--ffca34, #FFCA34);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.b9skxcbce {
  stop-color: var(--svg-color--e47a3c, #E47A3C);
  stop-opacity: 0;
}

.bc7d6obfi {
  stop-color: var(--svg-color--fda839, #FDA839);
}

.bh78v-hfd {
  d: path("M15.994 17.846c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845c.664 0 1.248-.338 1.583-.846c.086-.13-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bj8dg0b8l {
  stop-color: var(--svg-color--e4ad53, #E4AD53);
  stop-opacity: 0;
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.btm953brw {
  stop-color: var(--svg-color--c18731, #C18731);
  stop-opacity: 0;
}

.bvgzffjne {
  stop-color: var(--svg-color--377be9, #377BE9);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c0g3mbbdp {
  d: path("M23.748 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.ceu0gybff {
  stop-color: var(--svg-color--59bfed, #59BFED);
}

.cgi88gv2t {
  stop-color: var(--svg-color--ffcf53, #FFCF53);
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

.d0pq7p0hl {
  stop-color: var(--svg-color--d9a439, #D9A439);
}

.d3e9_irck {
  d: path("M7.22 21.847h1.021v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.dfdb-obom {
  stop-color: var(--svg-color--ff7468, #FF7468);
}

.dl6zet80s {
  stop-color: var(--svg-color--ec7921, #EC7921);
}

.dp-wqtbjr {
  stop-color: var(--svg-color--e47a3c, #E47A3C);
}

.dpitlhbpx {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
  stop-opacity: 0;
}

.dudenh09d {
  stop-color: var(--svg-color--52b8f8, #52B8F8);
  stop-opacity: 0;
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
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

.efd1-abcd {
  stop-color: var(--svg-color--ec893a, #EC893A);
  stop-opacity: 0;
}

.ehqj11bbt {
  stop-color: var(--svg-color--fc4, #FC4);
  stop-opacity: 0;
}

.eif22vbdr {
  stop-color: var(--svg-color--f7d06d, #F7D06D);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
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

.fjxmamblp {
  d: path("M18.112 13.745c.064.085-.07.189-.22.302c-.152.112-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.fm5egxmlo {
  stop-color: var(--svg-color--267ebb, #267EBB);
}

.fnx367bbh {
  stop-color: var(--svg-color--ffcc36, #FFCC36);
  stop-opacity: 0;
}

.fqsay0-oq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.643 17.45c.39.204.855.32 1.35.32c.501 0 .961-.116 1.351-.32h.001a.23.23 0 0 1 .27.045a.214.214 0 0 1 .025.273m-2.997-.317l2.934.275m-2.934-.275a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271m.295-.317l-.233.275m3.23.042l-.063-.042m.063.042l-.063-.042m.063.042c-.349.528-.956.88-1.646.88s-1.297-.352-1.646-.88m3.229-.042a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.584-.846m-.062.042v.001l.062-.043m-.062.042l.062-.042");
}

.fsr110b8t {
  stop-color: var(--svg-color--ff6a30, #FF6A30);
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

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gf8nacb0x {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.507 14.43l-.634 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.542-.407-.662 0");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gqfytjify {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.956 13.752a.956.956 0 0 0 .084 1.879a78 78 0 0 1-.084-1.88");
}

.gvudu0-9m {
  stop-color: var(--svg-color--c37b21, #C37B21);
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h_mah-buv {
  stop-color: var(--svg-color--fad771, #FAD771);
}

.h4ps77q_r {
  stop-color: var(--svg-color--d89b45, #D89B45);
}

.hn2pq365w {
  stop-color: var(--svg-color--f6c164, #F6C164);
}

.hpg9gtbjd {
  fill: var(--svg-color--e12706, #E12706);
  d: path("M7.361 23.904h1.822v.821c0 .148-.12.268-.268.268H8.54a.27.27 0 0 1-.268-.264a.27.27 0 0 1-.268.264H7.63a.27.27 0 0 1-.268-.268zm1.822 0v.821c0 .148.12.268.268.268h.375a.27.27 0 0 0 .268-.264a.27.27 0 0 0 .268.264h.375c.148 0 .268-.12.268-.268v-.82z");
}

.hq6570jxd {
  fill: var(--svg-color--fb3310, #FB3310);
  d: path("M24.037 23.89h-.911v.82c0 .148.12.268.268.268h.375c.148 0 .268-.12.268-.267z");
}

.hqe5c4bli {
  d: path("M23.635 22.456c2.514 2.142 3.575 5.222 4.027 7.508h-4.027z");
}

.i2l-0n8bq {
  d: path("M11.169 17.714a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.342 1.513-3.342 3.38c0 1.86.117 3.69.239 5.556");
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

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.inf8k3cdd {
  stop-color: var(--svg-color--cf7638, #CF7638);
}

.iu34ngpem {
  stop-color: var(--svg-color--e57b3e, #E57B3E);
  stop-opacity: 0;
}

.iu8kp3ahw {
  d: path("M16.549 29.964h-1.086v-6.28h1.086z");
}

.iyq1_fb9e {
  stop-color: var(--svg-color--e4bb48, #E4BB48);
}

.izxaz-bvs {
  stop-color: var(--svg-color--3c7dcd, #3C7DCD);
}

.j0k3id93s {
  stop-color: var(--svg-color--984900, #984900);
  stop-opacity: 0;
}

.jnpel9bup {
  stop-color: var(--svg-color--f7d06d, #F7D06D);
}

.jnzs3bbbz {
  stop-color: var(--svg-color--a54a00, #A54A00);
  stop-opacity: 0;
}

.jo4sxnm8i {
  stop-color: var(--svg-color--e0613c, #E0613C);
}

.jqlapeb1l {
  d: path("m9.11 5.009l1.287 7.093a.25.25 0 0 0 .246.205h10.702a.25.25 0 0 0 .246-.205l1.287-7.093l-3.37 2.107a.495.495 0 0 1-.666-.13a160 160 0 0 1-.666-.946c-.551-.784-1.11-1.58-1.371-1.89c-.38-.454-.651-.477-.807-.477h-.007c-.156 0-.427.023-.808.476c-.26.31-.82 1.107-1.37 1.891c-.232.33-.462.657-.667.945a.495.495 0 0 1-.667.131z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jrd3jzgth {
  stop-color: var(--svg-color--dd7423, #DD7423);
  stop-opacity: 0;
}

.jtr2kbb9c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.112 13.745c.064.085-.07.189-.22.302c-.152.112-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.jxvb9w84e {
  stop-color: var(--svg-color--fc586e, #FC586E);
}

.jy5rmybcl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.603 13.284c-.653 0-1.205.45-1.355 1.059a.273.273 0 0 0 .267.34h2.232a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
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

.k8wj80bfs {
  cx: 13.54px;
  cy: 13.937px;
  rx: 0.39px;
  ry: 0.197px;
}

.kbcpr6bot {
  d: path("M22.727 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
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

.kz6jvgbzd {
  stop-color: var(--svg-color--e0a155, #E0A155);
}

.l0yglmb3r {
  stop-color: var(--svg-color--e5c652, #E5C652);
}

.l2jyntb4f {
  stop-color: var(--svg-color--ffad23, #FFAD23);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.ldyj_nb1e {
  cx: 9.25px;
  cy: 5.184px;
  r: 0.767px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lqxvkgj5w {
  stop-color: var(--svg-color--ebc06f, #EBC06F);
}

.ltsxllb3q {
  stop-color: var(--svg-color--d37902, #D37902);
}

.m0c3dhblj {
  d: path("M18.973 14.33a.84.84 0 0 0-.232-.462l-.26.285l.118.229z");
}

.m2fe6ac_o {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.385 13.284c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34H17.24a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.m8_9xackt {
  stop-color: var(--svg-color--e7175a, #E7175A);
}

.m8qxht3di {
  stop-color: var(--svg-color--fb9d2e, #FB9D2E);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me2qedj2f {
  stop-color: var(--svg-color--467ec1, #467EC1);
  stop-opacity: 0;
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
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

.n5q_2-c9z {
  cx: 13.54px;
  cy: 13.937px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nd4srkbik {
  stop-color: var(--svg-color--fa865b, #FA865B);
  stop-opacity: 0;
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
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

.p-h-_brca {
  stop-color: var(--svg-color--a54a00, #A54A00);
}

.p7fclrrnf {
  stop-color: var(--svg-color--ff4d0c, #FF4D0C);
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

.prxm8ubjj {
  cx: 22.026px;
  cy: 9.418px;
  r: 0.817px;
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q5a0_7mqo {
  stop-color: var(--svg-color--ff6e46, #FF6E46);
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

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r7-2wfbcc {
  stop-color: var(--svg-color--467ec1, #467EC1);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
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

.rp-i_6biq {
  d: path("M11.132 16.2a1.64 1.64 0 0 1-.904-.31v.932c0 .893.532 1.688 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.rpngv328y {
  stop-color: var(--svg-color--e1754f, #E1754F);
}

.rrf7pv4xq {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.955 15.64q.059-.953.11-1.904a.956.956 0 0 1-.11 1.903");
}

.rrwvrg1ho {
  stop-color: var(--svg-color--ff6e46, #FF6E46);
  stop-opacity: 0;
}

.ryyd73bhi {
  d: path("M18.178 13.556a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.s-qqz8oax {
  stop-color: var(--svg-color--e68600, #E68600);
  stop-opacity: 0;
}

.s3wqo851w {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
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

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
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

.t4qznn7ln {
  d: path("M10.94 13.09a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.tgzndhrni {
  stop-color: var(--svg-color--ae5301, #AE5301);
}

.tjsj1op7o {
  stop-color: var(--svg-color--dda72d, #DDA72D);
}

.tlvsbm58e {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 14.449a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.trt6sabjd {
  stop-color: var(--svg-color--e68600, #E68600);
}

.u_7404bbu {
  stop-color: var(--svg-color--ff834e, #FF834E);
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
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

.v-aq_fb5e {
  cx: 9.966px;
  cy: 9.418px;
  r: 0.817px;
}

.v1k_mhzfg {
  stop-color: var(--svg-color--ffb34d, #FFB34D);
  stop-opacity: 0;
}

.v4gg9p-ym {
  stop-color: var(--svg-color--ff8258, #FF8258);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vmhbtsb-a {
  d: path("M8.241 21.847h1.02v2.645a.3.3 0 0 1-.3.3h-.42a.3.3 0 0 1-.3-.3z");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vsg8c7gji {
  stop-color: var(--svg-color--ff432e, #FF432E);
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

.w5vv1ga9t {
  d: path("m15.611 14.235l-.531 1.838c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.we5kvqbpm {
  cx: 15.994px;
  cy: 20.206px;
  r: 3.98px;
}

.wgfty7mbu {
  d: path("M14.625 14.344c0-.289-.235-.481-.298-.54l-.288.28l.177.36z");
}

.wjgmmu2gq {
  stop-color: var(--svg-color--ff4c2c, #FF4C2C);
}

.wo3ljv8tf {
  fill: var(--svg-color--e12706, #E12706);
  d: path("M11.916 23.904h-.911v.821c0 .148.12.268.268.268h.375c.148 0 .268-.12.268-.268z");
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.x6pg6seap {
  d: path("M20.915 16.29q.1-1.595.185-3.191a1.61 1.61 0 0 1-.185 3.19");
}

.x9knvh_3c {
  stop-color: var(--svg-color--ff5730, #FF5730);
}

.x9yzxpkmm {
  d: path("M20.855 16.2c.335-.012.65-.125.904-.31v.932c0 .893-.532 1.688-1.34 2.019q.256-.546.346-1.18z");
}

.xgp1qchkh {
  stop-color: var(--svg-color--eebf6c, #EEBF6C);
}

.xgzvgdboh {
  stop-color: var(--svg-color--e4aa42, #E4AA42);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
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

.y6-34fvwd {
  d: path("M13.81 13.556a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.yg19gcced {
  stop-color: var(--svg-color--ec7921, #EC7921);
  stop-opacity: 0;
}

.ykc__8bxx {
  stop-color: var(--svg-color--ff865b, #FF865B);
  stop-opacity: 0;
}

.z0ydb9xti {
  stop-color: var(--svg-color--d47010, #D47010);
}

.z1e4imbuu {
  stop-color: var(--svg-color--e2aa40, #E2AA40);
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
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

.zupcoccwr {
  stop-color: var(--svg-color--ca5f00, #CA5F00);
}

.zw4segwhh {
  fill: var(--svg-color--fb3310, #FB3310);
  d: path("M19.482 22.387h1.822v2.324c0 .148-.12.267-.268.267h-.375a.27.27 0 0 1-.268-.264a.27.27 0 0 1-.268.264h-.375a.27.27 0 0 1-.268-.267zm1.822 0v2.324c0 .148.12.267.268.267h.375a.27.27 0 0 0 .268-.264a.27.27 0 0 0 .268.264h.375c.148 0 .268-.12.268-.267v-.821z");
}

</style>
