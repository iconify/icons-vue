<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#svgIDa)" class="d2kvgvbvc"><path fill="url(#svgIDb)" class="nh9nnbcln"/><path fill="url(#svgIDc)" class="nh9nnbcln"/><path fill="url(#svgIDd)" class="nh9nnbcln"/><path fill="url(#svgIDe)" class="nh9nnbcln"/><path fill="url(#svgIDf)" class="nh9nnbcln"/><path fill="url(#svgIDg)" class="nh9nnbcln"/><path fill="url(#svgIDh)" class="nh9nnbcln"/><path fill="url(#svgIDi)" class="nh9nnbcln"/><path fill="url(#svgIDj)" class="nh9nnbcln"/><path fill="url(#svgIDk)" class="nh9nnbcln"/><path fill="url(#svgIDl)" class="nh9nnbcln"/></g><g filter="url(#svgIDm)"><path fill="url(#svgIDn)" class="q4mqk8k3c"/><path fill="url(#svgIDo)" class="q4mqk8k3c"/></g><g filter="url(#svgIDp)"><path fill="url(#svgIDq)" class="qj71mlzuz"/></g><g filter="url(#svgIDr)"><path class="nt442ablb"/></g><path fill="url(#svgIDs)" class="kv8gojb4q"/><path fill="url(#svgIDt)" class="kv8gojb4q"/><path fill="url(#svgIDu)" class="an9jwbc9b"/><path fill="url(#svgIDv)" class="an9jwbc9b"/><circle class="qabbs-ldy"/><g filter="url(#svgIDw)"><path clip-rule="evenodd" class="xdkb6wisn"/></g><circle fill="url(#svgIDx)" transform="matrix(-1 0 0 1 25.185 16.762)" class="kr_eiac3t"/><g filter="url(#svgIDy)"><path clip-rule="evenodd" class="x68ij2b_y"/></g><g filter="url(#svgIDz)"><path stroke="url(#svgIDA)" class="zc-mq7btq"/></g><g filter="url(#svgIDB)"><path class="v0fg4m7wo"/></g><path fill="url(#svgIDC)" class="mhxr-_01m"/><path fill="url(#svgIDD)" class="mhxr-_01m"/><path fill="url(#svgIDE)" class="mhxr-_01m"/><path fill="url(#svgIDF)" class="mhxr-_01m"/><path fill="url(#svgIDG)" class="mhxr-_01m"/><path fill="url(#svgIDH)" class="zo46f1umk"/><g filter="url(#svgIDI)"><path class="pf433ilvb"/></g><path fill="url(#svgIDJ)" class="v85-ckaxn"/><path fill="url(#svgIDK)" class="b7-ctabed"/><g filter="url(#svgIDL)"><path fill="url(#svgIDM)" class="jazr7fbzn"/></g><g filter="url(#svgIDN)"><path fill="url(#svgIDO)" class="qokwrdjlv"/><path fill="url(#svgIDP)" class="qokwrdjlv"/></g><g filter="url(#svgIDQ)"><path class="hbct62biw"/><path fill="url(#svgIDR)" class="xhcvxeb0g"/></g><g filter="url(#svgIDS)"><path class="ss5dpkd_r"/><path fill="url(#svgIDT)" class="dqd2d10jo"/></g><g filter="url(#svgIDU)"><path fill="url(#svgIDV)" class="fdu-88c3z"/><path fill="url(#svgIDW)" class="fdu-88c3z"/><path fill="url(#svgIDX)" class="fdu-88c3z"/><path fill="url(#svgIDY)" class="fdu-88c3z"/><path fill="url(#svgIDZ)" class="fdu-88c3z"/><path fill="url(#svgIDaa)" class="fdu-88c3z"/><path fill="url(#svgIDab)" class="fdu-88c3z"/><path fill="url(#svgIDac)" class="fdu-88c3z"/></g><path fill="url(#svgIDad)" class="fdu-88c3z"/><path fill="url(#svgIDae)" class="fdu-88c3z"/><path fill="url(#svgIDaf)" class="fdu-88c3z"/><g filter="url(#svgIDag)"><path class="r4uzb-bfk"/></g><g filter="url(#svgIDah)"><path class="mhus2r1ko"/><path fill="url(#svgIDai)" class="bqpergbau"/><path fill="url(#svgIDaj)" class="bqpergbau"/><path fill="url(#svgIDak)" class="bqpergbau"/><path fill="url(#svgIDal)" class="bqpergbau"/></g><g filter="url(#svgIDam)"><path stroke="url(#svgIDan)" class="q03u_y6bw"/></g><path class="n2sty6bpf"/><g filter="url(#svgIDao)"><path class="xbalo5d6h"/></g><g filter="url(#svgIDap)"><path class="lx4qs1yor"/></g><g filter="url(#svgIDaq)"><path class="o8xm2kilb"/></g><g filter="url(#svgIDar)"><path clip-rule="evenodd" class="ieerhtbne"/></g><path class="fwgifl_lg"/><path fill="url(#svgIDas)" class="cv-rqurgf"/><path class="dx6oe8bvf"/><g filter="url(#svgIDat)"><path class="q1c3rlqxv"/><path fill="url(#svgIDau)" class="ghjgkyxad"/></g><g filter="url(#svgIDav)"><path fill="url(#svgIDaw)" class="o9eeddf9d"/></g><path class="aikvi6bqc"/><path fill="url(#svgIDax)" class="xohph8avb"/><path class="zc_xnbcsn"/><g filter="url(#svgIDay)"><path fill="url(#svgIDaz)" class="ff4ft0lcb"/></g><g filter="url(#svgIDaA)" transform="rotate(-27.914 20.908 7.345)"><ellipse class="q617abcdu"/><ellipse fill="url(#svgIDaB)" class="ut1ryzbes"/></g><g filter="url(#svgIDaC)"><path class="zaeftuinl"/><path fill="url(#svgIDaD)" class="ksi0wnb_l"/></g><g filter="url(#svgIDaE)"><path class="l0wjcccch"/><path fill="url(#svgIDaF)" class="v6mxwya9l"/><path fill="url(#svgIDaG)" class="v6mxwya9l"/></g><g filter="url(#svgIDaH)"><path stroke="url(#svgIDaI)" class="sk_t0ijru"/></g><g filter="url(#svgIDaJ)"><path class="ms0kjdb9l"/></g><g filter="url(#svgIDaK)"><path class="kq_he4b5n"/></g><g filter="url(#svgIDaL)"><path class="qdb64dbny"/></g><g filter="url(#svgIDaM)"><path fill="url(#svgIDaN)" class="d_vh2-6mg"/></g><g clip-rule="evenodd" filter="url(#svgIDaO)" class="d2kvgvbvc"><path fill="url(#svgIDaP)" class="zobfdsyko"/><path fill="url(#svgIDaQ)" class="zobfdsyko"/><path fill="url(#svgIDaR)" class="zobfdsyko"/><path fill="url(#svgIDaS)" class="zobfdsyko"/><path fill="url(#svgIDaT)" class="zobfdsyko"/><path fill="url(#svgIDaU)" class="zobfdsyko"/><path fill="url(#svgIDaV)" class="zobfdsyko"/><path fill="url(#svgIDaW)" class="zobfdsyko"/><path fill="url(#svgIDaX)" class="zobfdsyko"/><path fill="url(#svgIDaY)" class="zobfdsyko"/><path fill="url(#svgIDaZ)" class="zobfdsyko"/></g><g filter="url(#svgIDba)"><path fill="url(#svgIDbb)" class="rmlg14bhc"/><path fill="url(#svgIDbc)" class="rmlg14bhc"/></g><g filter="url(#svgIDbd)"><path fill="url(#svgIDbe)" class="mwhh96ban"/></g><g filter="url(#svgIDbf)"><path class="oi3c_7bgi"/></g><path fill="url(#svgIDbg)" class="l52ej4bse"/><path fill="url(#svgIDbh)" class="l52ej4bse"/><path fill="url(#svgIDbi)" class="i0noqrbwn"/><path fill="url(#svgIDbj)" class="i0noqrbwn"/><circle class="qsgbqabcy"/><g filter="url(#svgIDbk)"><path clip-rule="evenodd" class="q1poyrpqb"/></g><circle fill="url(#svgIDbl)" transform="matrix(-1 0 0 1 12.14 16.716)" class="kr_eiac3t"/><g filter="url(#svgIDbm)"><path clip-rule="evenodd" class="q_z_uxj4s"/></g><g filter="url(#svgIDbn)"><path stroke="url(#svgIDbo)" class="lusr05uyk"/></g><g filter="url(#svgIDbp)"><path class="iziglpb0o"/></g><path fill="url(#svgIDbq)" class="hcbnkybyd"/><path fill="url(#svgIDbr)" class="hcbnkybyd"/><path fill="url(#svgIDbs)" class="hcbnkybyd"/><path fill="url(#svgIDbt)" class="hcbnkybyd"/><path fill="url(#svgIDbu)" class="hcbnkybyd"/><path fill="url(#svgIDbv)" class="o8grsn7mh"/><g filter="url(#svgIDbw)"><path class="ytvlyzboz"/></g><path fill="url(#svgIDbx)" class="rifc_5b5l"/><path fill="url(#svgIDby)" class="vpnhhy5yj"/><g filter="url(#svgIDbz)"><path fill="url(#svgIDbA)" class="jp2767bds"/></g><g filter="url(#svgIDbB)"><path fill="url(#svgIDbC)" class="wv6kv35lx"/><path fill="url(#svgIDbD)" class="wv6kv35lx"/></g><g filter="url(#svgIDbE)"><path class="j2q7brfqh"/><path fill="url(#svgIDbF)" class="eurjhcb6z"/></g><g filter="url(#svgIDbG)"><path class="xvs5rgbvd"/><path fill="url(#svgIDbH)" class="h1dr1wadf"/></g><g filter="url(#svgIDbI)"><path fill="url(#svgIDbJ)" class="t3pocfb3y"/><path fill="url(#svgIDbK)" class="t3pocfb3y"/><path fill="url(#svgIDbL)" class="t3pocfb3y"/><path fill="url(#svgIDbM)" class="t3pocfb3y"/><path fill="url(#svgIDbN)" class="t3pocfb3y"/><path fill="url(#svgIDbO)" class="t3pocfb3y"/><path fill="url(#svgIDbP)" class="t3pocfb3y"/><path fill="url(#svgIDbQ)" class="t3pocfb3y"/></g><path fill="url(#svgIDbR)" class="t3pocfb3y"/><path fill="url(#svgIDbS)" class="t3pocfb3y"/><path fill="url(#svgIDbT)" class="t3pocfb3y"/><g filter="url(#svgIDbU)"><path class="q9er1fboq"/></g><g filter="url(#svgIDbV)"><path class="dxtq16n8q"/><path fill="url(#svgIDbW)" class="fnk-6xb0v"/><path fill="url(#svgIDbX)" class="fnk-6xb0v"/><path fill="url(#svgIDbY)" class="fnk-6xb0v"/><path fill="url(#svgIDbZ)" class="fnk-6xb0v"/></g><g filter="url(#svgIDca)"><path stroke="url(#svgIDcb)" class="wz6gy8bco"/></g><path class="jmvmcqk3o"/><g filter="url(#svgIDcc)"><path class="ush5kqbwh"/></g><g filter="url(#svgIDcd)"><path class="qij7z_5st"/></g><g filter="url(#svgIDce)"><path class="e2ro39bok"/></g><g filter="url(#svgIDcf)"><path clip-rule="evenodd" class="sl9-fccme"/></g><path class="ay4arcb8b"/><path fill="url(#svgIDcg)" class="mqvt-sq-f"/><path class="phfhlob2g"/><g filter="url(#svgIDch)"><path class="fed6g87wu"/><path fill="url(#svgIDci)" class="y_nb4vsfw"/></g><g filter="url(#svgIDcj)"><path fill="url(#svgIDck)" class="bg4ecacle"/></g><path class="ou20ombub"/><path fill="url(#svgIDcl)" class="dqj_gkbwz"/><path class="fygttbb3n"/><g filter="url(#svgIDcm)"><path fill="url(#svgIDcn)" class="ncz1inbrb"/></g><g filter="url(#svgIDco)" transform="rotate(-27.914 7.862 7.299)"><ellipse class="bwfijxbef"/><ellipse fill="url(#svgIDcp)" class="vhmwta2qj"/></g><g filter="url(#svgIDcq)"><path class="v2j2cxb_d"/><path fill="url(#svgIDcr)" class="hkubfwb8c"/></g><g filter="url(#svgIDcs)"><path class="fm58kvk2x"/><path fill="url(#svgIDct)" class="w947xh_cz"/><path fill="url(#svgIDcu)" class="w947xh_cz"/></g><g filter="url(#svgIDcv)"><path stroke="url(#svgIDcw)" class="ufu-ghvir"/></g><g filter="url(#svgIDcx)"><path class="kz-yrccie"/></g><g filter="url(#svgIDcy)"><path class="fommmccmn"/></g><g filter="url(#svgIDcz)"><path class="i47vi93bg"/></g><g filter="url(#svgIDcA)"><path fill="url(#svgIDcB)" class="uylr5nywc"/></g><defs><radialGradient id="svgIDc" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 7.096 13.927) scale(1.97957 2.47289)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.241 .83694 -1.09967 -1.63057 20.622 8.835)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="svgIDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.56276 .73593 -.56509 -.43212 19.879 7.738)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 8.112 9.062) scale(1.06539 .75048)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(.59163 1.12553 -1.5624 .82126 20.449 4.174)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 11.187 7.604) scale(.87747 1.22625)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-.7936 .23088 -.48148 -1.655 25.196 7.277)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21207 .30304 -.38602 -1.544 24.936 8.749)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="svgIDk" cx="0" cy="0" r="1" gradientTransform="matrix(-.38932 -1.1408 .90231 -.30793 24 6.229)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="matrix(.64736 .0679 -.11003 1.04892 19.32 7.261)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="svgIDs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.137)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.086 34.637) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.248 29.887)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.434)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDx" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="ya-pfekwl"/><stop offset="1" class="lr5tnibbk"/></radialGradient><radialGradient id="svgIDA" cx="0" cy="0" r="1" gradientTransform="rotate(178.182 13.746 7.058) scale(3.93948 5.59762)" gradientUnits="userSpaceOnUse"><stop class="jvinkk5aj"/><stop offset="1" class="txwk9g23l"/></radialGradient><radialGradient id="svgIDC" cx="0" cy="0" r="1" gradientTransform="matrix(-.31576 -4.42702 2.3084 -.16465 22.113 20.313)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09808 -2.34457 .73972 -.34645 22.9 19.75)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="rotate(140.925 9.978 9.921) scale(2.85608 2.68117)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(.40121 -2.33727 .9853 .16914 20.895 19.575)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="matrix(.59437 2.4809 -3.06084 .73331 21.163 9.443)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="y2o07bc4o"/><stop offset=".902" class="m0vc0tb7f"/></radialGradient><radialGradient id="svgIDO" cx="0" cy="0" r="1" gradientTransform="matrix(1.07142 -.48701 .59462 1.30815 23.703 7.832)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(.56637 .31746 -.08975 .16012 24.146 6.92)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(.64993 -.04835 .0378 .50807 23.854 7.691)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="svgIDT" cx="0" cy="0" r="1" gradientTransform="rotate(-180 9.992 3.822) scale(.45454)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="svgIDV" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 10.784 6.251) scale(3.08278 4.12625)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="matrix(-.9385 .41297 -.28759 -.65356 22.812 7.78)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="svgIDX" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 17.567 -9.413) scale(1.77969 2.2581)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="matrix(-.553 3.1738 -3.9672 -.69123 22.404 7.233)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.97255 .58335 -1.00435 -5.11781 22.743 8.157)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49535 .60793 0 22.954 7.232)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56497 .6475 0 21.07 7.133)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="svgIDac" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 8.891 11.758) scale(1.43857 1.1511)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(-.55325 0 0 -2.7745 24.157 7.872)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="svgIDae" cx="0" cy="0" r="1" gradientTransform="matrix(-.34302 -.55824 .59318 -.36449 23.529 9.885)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="svgIDaf" cx="0" cy="0" r="1" gradientTransform="matrix(.7533 -.67258 .7986 .89443 20.226 9.878)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(-.19609 -.87984 .27116 -.06043 22.301 8.184)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(-.3355 0 0 -.0938 22.198 8.276)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="svgIDas" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 22.903 7.386)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(-.09983 -.12864 .17711 -.13745 22.805 7.423)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDax" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 21.025 7.386)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDaB" cx="0" cy="0" r="1" gradientTransform="matrix(-.00333 -.21267 .25564 -.004 20.901 7.48)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaD" cx="0" cy="0" r="1" gradientTransform="matrix(.54324 -1.18607 .60677 .2779 19.528 6.473)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 10.063 9.279) scale(2.09755 3.42936)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(-.09054 .58851 -1.26615 -.1948 22.054 4.391)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .594 8.188) scale(1.97957 2.47289)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="matrix(-1.241 .83694 -1.09967 -1.63057 7.577 8.789)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="matrix(-.56276 .73593 -.56509 -.43212 6.833 7.692)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.602 5.38) scale(1.06539 .75048)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(.59163 1.12553 -1.5624 .82126 7.403 4.128)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 4.674 4.878) scale(.87747 1.22625)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="matrix(-.7936 .23088 -.48148 -1.655 12.15 7.23)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21207 .30304 -.38602 -1.544 11.891 8.702)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="matrix(-.38932 -1.1408 .90231 -.30793 10.956 6.184)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(.64736 .0679 -.11003 1.04892 6.275 7.215)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.09)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.56 21.042) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.84)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.388)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="ya-pfekwl"/><stop offset="1" class="lr5tnibbk"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="rotate(178.182 7.224 6.932) scale(3.93948 5.59762)" gradientUnits="userSpaceOnUse"><stop class="jvinkk5aj"/><stop offset="1" class="txwk9g23l"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(-.31576 -4.42702 2.3084 -.16465 9.067 20.267)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09808 -2.34457 .73972 -.34645 9.856 19.703)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="rotate(140.925 3.463 7.584) scale(2.85608 2.68117)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(.40121 -2.33727 .9853 .16914 7.85 19.529)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(.59437 2.4809 -3.06084 .73331 8.118 9.396)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="y2o07bc4o"/><stop offset=".902" class="m0vc0tb7f"/></radialGradient><radialGradient id="svgIDbC" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 23.3 -20.708) scale(1.17691 1.43695)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="svgIDbD" cx="0" cy="0" r="1" gradientTransform="matrix(.56637 .31745 -.08975 .16012 11.1 6.873)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="matrix(.64993 -.04835 .0378 .50807 10.809 7.645)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="rotate(-180 3.469 3.799) scale(.45454)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 4.266 4.796) scale(3.08278 4.12625)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="svgIDbK" cx="0" cy="0" r="1" gradientTransform="matrix(-.9385 .41297 -.28759 -.65356 9.767 7.733)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 11.012 -.43) scale(1.77969 2.2581)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="matrix(-.553 3.1738 -3.9672 -.69123 9.359 7.186)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="matrix(-2.97255 .58335 -1.00435 -5.11781 9.698 8.11)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="svgIDbO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49535 .60793 0 9.91 7.185)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56497 .6475 0 8.025 7.087)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="svgIDbQ" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 2.387 6.738) scale(1.43857 1.1511)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="svgIDbR" cx="0" cy="0" r="1" gradientTransform="matrix(-.55325 0 0 -2.7745 11.112 7.826)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="svgIDbS" cx="0" cy="0" r="1" gradientTransform="matrix(-.34302 -.55824 .59318 -.36449 10.483 9.838)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="svgIDbT" cx="0" cy="0" r="1" gradientTransform="matrix(.7533 -.67258 .7986 .89443 7.181 9.832)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="svgIDbW" cx="0" cy="0" r="1" gradientTransform="matrix(-.19609 -.87984 .27116 -.06043 9.255 8.14)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="svgIDbZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.3355 0 0 -.0938 9.153 8.23)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="svgIDcg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 9.858 7.34)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDci" cx="0" cy="0" r="1" gradientTransform="matrix(-.09983 -.12864 .17711 -.13745 9.76 7.376)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDcl" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 7.98 7.34)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDcp" cx="0" cy="0" r="1" gradientTransform="matrix(-.00333 -.21267 .25564 -.004 7.856 7.434)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDcr" cx="0" cy="0" r="1" gradientTransform="matrix(.54324 -1.18607 .60677 .2779 6.483 6.427)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="svgIDct" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 3.555 5.155) scale(2.09755 3.42936)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="svgIDcu" cx="0" cy="0" r="1" gradientTransform="matrix(-.09054 .58851 -1.26615 -.1948 9.01 4.345)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="svgIDa" width="6.715" height="7.215" x="18.732" y="3.222" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDm" width="3.254" height="11.85" x="18.86" y="18.206" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDp" width="7.308" height="11.757" x="22.341" y="18.3" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDr" width="5.615" height="11.172" x="23.401" y="17.792" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".25"/></filter><filter id="svgIDw" width="5.896" height="7.11" x="15.796" y="10.179" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.290196 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.305882 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDy" width="5.996" height="7.044" x="22.312" y="10.245" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.266667 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.298039 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDz" width="5.168" height="4.054" x="22.778" y="10.433" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".2"/></filter><filter id="svgIDB" width="8.805" height="9.609" x="17.71" y="9.966" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDI" width="2.793" height="3.034" x="16.366" y="13.415" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".2"/></filter><filter id="svgIDL" width="1.535" height="1.385" x="19.254" y="6.951" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDN" width="1.385" height="1.635" x="23.349" y="6.701" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDQ" width="1.925" height="1.925" x="23.079" y="6.681" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".25"/></filter><filter id="svgIDS" width="1.425" height="1.425" x="19.243" y="6.931" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".125"/></filter><filter id="svgIDU" width="4.387" height="4.932" x="19.77" y="5.531" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDag" width="1.808" height="2.154" x="20.99" y="6.926" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".25"/></filter><filter id="svgIDah" width=".908" height="1.254" x="21.51" y="7.316" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".025"/></filter><filter id="svgIDam" width="1.822" height=".885" x="21.053" y="8.54" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".05"/></filter><filter id="svgIDao" width="1.406" height=".553" x="22.255" y="7.039" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDap" width="1.406" height=".553" x="20.266" y="7.039" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDaq" width="1.17" height=".584" x="20.325" y="6.312" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDar" width="1.17" height=".584" x="22.656" y="6.312" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDat" width=".453" height=".414" x="22.53" y="7.14" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".05"/></filter><filter id="svgIDav" width=".611" height=".621" x="22.835" y="7.115" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDay" width=".652" height=".676" x="20.922" y="7.088" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDaA" width=".507" height=".417" x="20.654" y="7.136" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".05"/></filter><filter id="svgIDaC" width="2.169" height="2.298" x="19.201" y="4.627" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feGaussianBlur result="effect2_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDaE" width="3.987" height="2.624" x="20.428" y="4.124" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feGaussianBlur result="effect2_foregroundBlur_4002_710" stdDeviation=".075"/></filter><filter id="svgIDaH" width=".835" height="1.336" x="20.419" y="4.527" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDaJ" width="2.621" height="1.306" x="21.786" y="5.119" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".125"/></filter><filter id="svgIDaK" width="1.73" height="2.911" x="19.728" y="1.79" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDaL" width="1.73" height="2.911" x="22.439" y="1.79" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDaM" width="4.792" height="2.36" x="19.703" y="3.772" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDaO" width="6.715" height="7.215" x="5.686" y="3.176" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDba" width="3.254" height="11.85" x="5.815" y="18.16" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDbd" width="7.308" height="11.757" x="9.296" y="18.253" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDbf" width="5.615" height="11.172" x="10.355" y="17.746" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".25"/></filter><filter id="svgIDbk" width="5.896" height="7.11" x="2.751" y="10.133" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.290196 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.305882 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDbm" width="5.996" height="7.044" x="9.267" y="10.199" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.266667 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.298039 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDbn" width="5.168" height="4.054" x="9.733" y="10.387" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".2"/></filter><filter id="svgIDbp" width="8.805" height="9.609" x="4.665" y="9.919" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDbw" width="2.793" height="3.034" x="3.321" y="13.369" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".2"/></filter><filter id="svgIDbz" width="1.535" height="1.385" x="6.209" y="6.904" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDbB" width="1.385" height="1.635" x="10.304" y="6.654" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDbE" width="1.925" height="1.925" x="10.034" y="6.635" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".25"/></filter><filter id="svgIDbG" width="1.425" height="1.425" x="6.197" y="6.885" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".125"/></filter><filter id="svgIDbI" width="4.387" height="4.932" x="6.725" y="5.485" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDbU" width="1.808" height="2.154" x="7.944" y="6.88" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".25"/></filter><filter id="svgIDbV" width=".908" height="1.254" x="8.464" y="7.27" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".025"/></filter><filter id="svgIDca" width="1.822" height=".885" x="8.008" y="8.494" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".05"/></filter><filter id="svgIDcc" width="1.406" height=".553" x="9.21" y="6.992" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDcd" width="1.406" height=".553" x="7.221" y="6.992" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDce" width="1.17" height=".584" x="7.279" y="6.266" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDcf" width="1.17" height=".584" x="9.611" y="6.266" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/></filter><filter id="svgIDch" width=".453" height=".414" x="9.485" y="7.094" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".05"/></filter><filter id="svgIDcj" width=".611" height=".621" x="9.789" y="7.069" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDcm" width=".652" height=".676" x="7.877" y="7.042" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDco" width=".507" height=".417" x="7.609" y="7.09" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".05"/></filter><filter id="svgIDcq" width="2.169" height="2.298" x="6.156" y="4.581" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feGaussianBlur result="effect2_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDcs" width="3.987" height="2.624" x="7.383" y="4.078" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feGaussianBlur result="effect2_foregroundBlur_4002_710" stdDeviation=".075"/></filter><filter id="svgIDcv" width=".835" height="1.336" x="7.374" y="4.481" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".1"/></filter><filter id="svgIDcx" width="2.621" height="1.306" x="8.741" y="5.073" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_710" stdDeviation=".125"/></filter><filter id="svgIDcy" width="1.73" height="2.911" x="6.683" y="1.744" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDcz" width="1.73" height="2.911" x="9.394" y="1.744" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><filter id="svgIDcA" width="4.792" height="2.36" x="6.658" y="3.726" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_710"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_710" result="effect2_innerShadow_4002_710"/></filter><linearGradient id="svgIDb" x1="23.984" x2="21.055" y1="4.651" y2="10.076" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="svgIDn" x1="18.96" x2="20.963" y1="22.913" y2="23.05" gradientUnits="userSpaceOnUse"><stop class="mch9zegwt"/><stop offset="1" class="x4y51kb4t"/></linearGradient><linearGradient id="svgIDo" x1="18.846" x2="19.422" y1="23.745" y2="23.745" gradientUnits="userSpaceOnUse"><stop class="w2ejlbckb"/><stop offset="1" class="s_plahh6j"/></linearGradient><linearGradient id="svgIDq" x1="24.691" x2="27.163" y1="23.207" y2="22.292" gradientUnits="userSpaceOnUse"><stop class="dx14qxbsv"/><stop offset="1" class="ce26eet6g"/></linearGradient><linearGradient id="svgIDD" x1="18.797" x2="19.386" y1="18.059" y2="18.045" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDJ" x1="18.78" x2="24.915" y1="9.718" y2="9.718" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDK" x1="18.766" x2="24.928" y1="9.705" y2="9.705" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDM" x1="19.276" x2="19.81" y1="7.681" y2="7.681" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="svgIDaj" x1="21.56" x2="21.964" y1="8.216" y2="8.216" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="svgIDak" x1="21.964" x2="21.964" y1="8.56" y2="8.297" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="svgIDan" x1="21.506" x2="21.704" y1="9.167" y2="8.86" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="svgIDaw" x1="23.238" x2="23.103" y1="7.409" y2="7.493" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDaz" x1="21.345" x2="21.21" y1="7.409" y2="7.493" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDaI" x1="20.719" x2="20.954" y1="4.975" y2="5.524" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="svgIDaN" x1="23.743" x2="20.243" y1="5.231" y2="5.418" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaP" x1="10.939" x2="8.009" y1="4.604" y2="10.03" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="svgIDbb" x1="5.915" x2="7.918" y1="22.867" y2="23.004" gradientUnits="userSpaceOnUse"><stop class="mch9zegwt"/><stop offset="1" class="x4y51kb4t"/></linearGradient><linearGradient id="svgIDbc" x1="5.801" x2="6.377" y1="23.699" y2="23.699" gradientUnits="userSpaceOnUse"><stop class="w2ejlbckb"/><stop offset="1" class="s_plahh6j"/></linearGradient><linearGradient id="svgIDbe" x1="11.646" x2="14.117" y1="23.16" y2="22.245" gradientUnits="userSpaceOnUse"><stop class="dx14qxbsv"/><stop offset="1" class="ce26eet6g"/></linearGradient><linearGradient id="svgIDbr" x1="5.752" x2="6.341" y1="18.012" y2="17.999" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbx" x1="5.735" x2="11.87" y1="9.672" y2="9.672" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDby" x1="5.721" x2="11.883" y1="9.659" y2="9.659" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDbA" x1="6.231" x2="6.765" y1="7.634" y2="7.634" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="svgIDbX" x1="8.514" x2="8.918" y1="8.17" y2="8.17" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="svgIDbY" x1="8.918" x2="8.918" y1="8.514" y2="8.251" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="svgIDcb" x1="8.46" x2="8.659" y1="9.121" y2="8.814" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="svgIDck" x1="10.193" x2="10.058" y1="7.363" y2="7.446" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDcn" x1="8.299" x2="8.164" y1="7.363" y2="7.446" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDcw" x1="7.674" x2="7.908" y1="4.929" y2="5.477" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="svgIDcB" x1="10.697" x2="7.198" y1="5.184" y2="5.372" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-bunny-ears-medium-dark" /></template>
<style>
.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.aikvi6bqc {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.935 7.064a.601.601 0 0 0-.583.456a.118.118 0 0 0 .115.146h.96a.1.1 0 0 0 .098-.117a.603.603 0 0 0-.59-.485Z");
}

.an9jwbc9b {
  d: path("M28.675 28.215h-2.142l.142.308a2.64 2.64 0 0 0 2.397 1.533c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.ay4arcb8b {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.948 7.018c.28 0 .518.194.583.455a.118.118 0 0 1-.115.147h-.96a.1.1 0 0 1-.099-.117a.602.602 0 0 1 .59-.485Z");
}

.b7-ctabed {
  d: path("M21.857 9.705h-.017c.042 0 .08 0 .124.005c-.034-.005-.073-.005-.107-.005Z");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bg4ecacle {
  d: path("M10.2 7.468a.362.362 0 0 0-.099-.2l-.112.124l.05.098l.162-.022Z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bqpergbau {
  d: path("m21.8 7.488l-.23.731a.232.232 0 0 0 .224.301h.339c.159 0 .27-.152.224-.3l-.229-.732c-.049-.162-.277-.162-.329 0Z");
}

.bwfijxbef {
  cx: 7.862px;
  cy: 7.299px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ce26eet6g {
  stop-color: var(--svg-color--967267, #967267);
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

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cv-rqurgf {
  d: path("M22.904 7.18a.384.384 0 0 1 .37.486h-.742a.386.386 0 0 1 .372-.485Z");
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d_vh2-6mg {
  d: path("M24.093 5.774c.019.097-.101.144-.167.07c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.064c-.064.071-.182.025-.166-.07a2.231 2.231 0 0 1 4.389-.054Z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dqd2d10jo {
  d: path("M19.955 8.105a.462.462 0 1 0 0-.924a.462.462 0 0 0 0 .924Z");
}

.dqj_gkbwz {
  d: path("M7.979 7.135a.384.384 0 0 0-.37.485h.741a.387.387 0 0 0-.372-.485Z");
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.dx14qxbsv {
  stop-color: var(--svg-color--84565a, #84565A);
}

.dx6oe8bvf {
  fill: var(--svg-color--000, #000);
  d: path("M22.684 7.565a.22.22 0 0 1 .22-.22a.219.219 0 0 1 .195.321h-.39a.199.199 0 0 1-.025-.1Z");
}

.dxtq16n8q {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m8.754 7.442l-.229.731a.232.232 0 0 0 .224.301h.339c.158 0 .27-.152.224-.3l-.23-.732c-.048-.163-.277-.163-.328 0Z");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2ro39bok {
  fill: var(--svg-color--352827, #352827);
  d: path("M7.456 6.832h-.002a.115.115 0 0 1-.118-.197l.001-.001l.005-.003l.014-.007a1.41 1.41 0 0 1 .226-.095c.146-.047.35-.086.572-.047a.115.115 0 0 1-.04.227a.977.977 0 0 0-.462.04a1.18 1.18 0 0 0-.187.078l-.009.005Z");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.eurjhcb6z {
  d: path("M10.996 8.06a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .924Z");
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fdu-88c3z {
  d: path("M19.774 7.1h.005l-.004-.114l-.005-.132c.01-.409.248-.567.35-.62a.306.306 0 0 0 .021-.008a.992.992 0 0 0 .534-.54l.036-.084a.113.113 0 0 1 .198-.022c.31.453.826.72 1.373.72h1.386c.078 0 .466.038.49.574l-.052 1.323c-.053 1.206-.995 2.016-2.145 2.016s-2.092-.81-2.145-2.016L19.774 7.1Z");
}

.fed6g87wu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.83 7.216c.028.036-.03.081-.094.13c-.066.048-.114.082-.141.046c-.028-.037.003-.106.068-.155c.065-.048.14-.058.167-.021Z");
}

.ff4ft0lcb {
  d: path("M21.375 7.52c0-.124-.101-.207-.129-.232l-.124.12l.077.156l.176-.044Z");
}

.fm58kvk2x {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M8.659 4.244c-.488-.108-.926.378-.976.559c.453 1.526 1.598 1.442 2.73 1.316c.676-.075.75.234.807.383c0-1.693-1.44-2.01-2.549-2.256l-.012-.002Z");
}

.fnk-6xb0v {
  d: path("m8.754 7.442l-.229.731a.232.232 0 0 0 .224.301h.339c.158 0 .27-.152.224-.3l-.23-.732c-.048-.163-.277-.163-.328 0Z");
}

.fommmccmn {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.25c.222.71.522 1.165.644 1.305l.633-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.402-.078 1.29Z");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwgifl_lg {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.993 7.064a.6.6 0 0 1 .583.456a.118.118 0 0 1-.115.146h-.96a.1.1 0 0 1-.098-.117a.602.602 0 0 1 .59-.485Z");
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fygttbb3n {
  fill: var(--svg-color--000, #000);
  d: path("M8.198 7.519a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.195.321h.39a.218.218 0 0 0 .025-.101Z");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ghjgkyxad {
  d: path("M22.876 7.262c.027.037-.03.081-.095.13s-.114.083-.141.046c-.027-.036.003-.105.068-.154s.14-.058.168-.022Z");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1dr1wadf {
  d: path("M6.91 8.06a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .924Z");
}

.hbct62biw {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M24.042 8.105a.462.462 0 1 0 0-.924a.462.462 0 0 0 0 .924Z");
}

.hcbnkybyd {
  d: path("M5.915 12.791a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.13-1.14V12.79Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hkubfwb8c {
  d: path("M6.737 5.02c.243-.259.704-.26.917-.22l.17.555a.329.329 0 0 0-.287.1c-.193.543-.857.843-1.164.924c-.064-.642.047-1.024.364-1.36Z");
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i0noqrbwn {
  d: path("M15.63 28.169h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .206-.12.166-.234l-.563-1.607Z");
}

.i47vi93bg {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.25c-.222.71-.522 1.165-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.402.078 1.29Z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.ieerhtbne {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m23.57 6.68l-.06.1l.06-.1a.116.116 0 0 1-.119.2v-.001l-.002-.001a.65.65 0 0 0-.048-.025a1.179 1.179 0 0 0-.148-.058a.977.977 0 0 0-.461-.04a.116.116 0 1 1-.04-.227c.22-.04.425 0 .572.047a1.417 1.417 0 0 1 .24.102l.004.003h.002Z");
}

.iziglpb0o {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M5.915 12.791a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.13-1.14V12.79Z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j2q7brfqh {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M10.996 8.06a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .924Z");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jazr7fbzn {
  d: path("M19.947 8.336a.693.693 0 1 0 0-1.385a.693.693 0 0 0 0 1.385Z");
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jmvmcqk3o {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M8.918 8.85c-.224 0-.434-.054-.612-.148c-.06-.032-.125.038-.087.094a.832.832 0 0 0 1.399 0c.038-.058-.027-.126-.088-.094a1.297 1.297 0 0 1-.612.148Z");
}

.jp2767bds {
  d: path("M6.902 8.29a.693.693 0 1 0 0-1.386a.693.693 0 0 0 0 1.385Z");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jvinkk5aj {
  stop-color: var(--svg-color--8d6d67, #8D6D67);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kq_he4b5n {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.981 3.296c.222.71.522 1.166.645 1.305l.633-.242c-.013-.182-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.kr_eiac3t {
  r: 0.766px;
}

.ksi0wnb_l {
  d: path("M19.782 5.066c.243-.258.704-.259.917-.22l.17.555a.329.329 0 0 0-.287.101c-.193.543-.856.842-1.164.924c-.064-.642.047-1.025.364-1.36Z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.kv8gojb4q {
  d: path("m20.928 28.215l-.034.258a1.828 1.828 0 0 1-1.812 1.583a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.kz-yrccie {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m9.954 5.797l-.613.113a.296.296 0 1 1-.054-.587h1.007c.596 0 .794.6.818.805a1.354 1.354 0 0 0-1.158-.33Z");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0wjcccch {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M21.704 4.29c-.488-.108-.925.378-.976.559c.453 1.526 1.598 1.442 2.73 1.317c.676-.076.75.233.807.382c0-1.693-1.44-2.01-2.549-2.256l-.012-.002Z");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l52ej4bse {
  d: path("m7.883 28.169l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.72h1.968Z");
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

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lr5tnibbk {
  stop-color: var(--svg-color--744160, #744160);
}

.lusr05uyk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m10.258 10.912l3.55 2.002c.193.1.578.44.568 1.002");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lx4qs1yor {
  fill: var(--svg-color--272528, #272528);
  d: path("M21.472 7.398c-.114-.2-.288-.36-.662-.36a.714.714 0 0 0-.461.16c-.116.093-.1.213-.011.257l.24.137c.28-.09.59-.103.894-.194Z");
}

.m0vc0tb7f {
  stop-color: var(--svg-color--825f59, #825F59);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mch9zegwt {
  stop-color: var(--svg-color--7b504e, #7B504E);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mhus2r1ko {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m21.8 7.488l-.23.731a.232.232 0 0 0 .224.301h.339c.159 0 .27-.152.224-.3l-.229-.732c-.049-.162-.277-.162-.329 0Z");
}

.mhxr-_01m {
  d: path("M18.96 12.838a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.459.117.675l.444 1.236l-2.758 1.022l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.565Z");
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mqvt-sq-f {
  d: path("M9.859 7.135a.384.384 0 0 1 .37.485h-.742a.386.386 0 0 1 .372-.485Z");
}

.ms0kjdb9l {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m23 5.843l-.614.113a.296.296 0 1 1-.054-.587h1.008c.596 0 .793.6.817.806A1.355 1.355 0 0 0 23 5.843Z");
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mwhh96ban {
  d: path("m12.124 18.253l-2.828.953l4.334 9.27a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-4.07-11.523Z");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n2sty6bpf {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M21.964 8.897c-.224 0-.435-.054-.612-.149c-.06-.031-.126.038-.088.095a.832.832 0 0 0 1.4 0c.037-.059-.028-.126-.088-.095a1.296 1.296 0 0 1-.612.149Z");
}

.ncz1inbrb {
  d: path("M8.33 7.473c0-.124-.102-.206-.13-.231l-.123.12l.076.155l.176-.044Z");
}

.nh9nnbcln {
  d: path("M25.057 8.25a1.41 1.41 0 0 0 .024-1.176h.002a1.371 1.371 0 0 0-.121-.22l-.001-.002a1.395 1.395 0 0 1-.227-.763v-.004a1.42 1.42 0 0 0-1.42-1.42a.232.232 0 0 1-.196-.1a1.423 1.423 0 0 0-2.309 0a.243.243 0 0 1-.196.1h-.036a1.42 1.42 0 0 0-1.384 1.42v.004c0 .27-.078.536-.226.763l-.001.001a1.42 1.42 0 0 0-.095 1.397c.03.061.03.135 0 .196a1.383 1.383 0 0 0 1.246 1.99h3.694a1.383 1.383 0 0 0 1.246-1.99a.221.221 0 0 1 0-.196ZM19.779 7.1h-.005l.516 1.014c.053 1.206.524 0 1.674 0s1.651 1.342 1.704.136l.49-1.376c-.024-.536-.412-.574-.49-.574h-1.386a1.663 1.663 0 0 1-1.373-.72a.114.114 0 0 0-.198.022l-.036.084a.992.992 0 0 1-.534.54l-.022.009c-.101.052-.34.21-.349.619l.005.132l.004.114Z");
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nt442ablb {
  fill: var(--svg-color--9c7870, #9C7870);
  d: path("m23.9 18.594l.824-.302l3.792 10.172h-.758l-3.857-9.87Z");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o8grsn7mh {
  d: path("M9.319 9.968c.23.044.451.114.659.21l-.926 1.57a.25.25 0 0 1-.435.004l-.98-1.594a2.85 2.85 0 0 1 .532-.172l1.15-.018Z");
}

.o8xm2kilb {
  fill: var(--svg-color--352827, #352827);
  d: path("M20.501 6.878H20.5v.001a.116.116 0 0 1-.118-.198l.002-.001l.004-.003l.014-.007a1.415 1.415 0 0 1 .226-.095c.146-.047.351-.086.572-.047a.115.115 0 1 1-.04.227a.977.977 0 0 0-.462.04a1.185 1.185 0 0 0-.186.078l-.01.005Z");
}

.o9eeddf9d {
  d: path("M23.246 7.514a.362.362 0 0 0-.1-.199l-.111.123l.05.098l.161-.022Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.oi3c_7bgi {
  fill: var(--svg-color--9c7870, #9C7870);
  d: path("m10.855 18.548l.823-.302l3.792 10.172h-.758l-3.857-9.87Z");
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou20ombub {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.89 7.017a.601.601 0 0 0-.584.456a.118.118 0 0 0 .115.147h.96a.1.1 0 0 0 .099-.117a.603.603 0 0 0-.59-.486Z");
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pf433ilvb {
  stroke: var(--svg-color--866a64, #866A64);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.986 13.94c-.089.073-.194.29.093.57a70.98 70.98 0 0 0 1.555 1.415");
}

.phfhlob2g {
  fill: var(--svg-color--000, #000);
  d: path("M9.639 7.519a.22.22 0 0 1 .22-.22a.22.22 0 0 1 .195.321h-.39a.199.199 0 0 1-.025-.101Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_z_uxj4s {
  fill: var(--svg-color--815a5c, #815A5C);
  fill-rule: evenodd;
  d: path("M9.369 10.693a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.918l-3.907-2.12c-.385-.215-.54.028-.756.414Z");
}

.q03u_y6bw {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.964 8.897c-.224 0-.435-.054-.612-.149c-.06-.031-.126.038-.088.095a.832.832 0 0 0 1.4 0c.037-.059-.028-.126-.088-.095a1.296 1.296 0 0 1-.612.149Z");
}

.q1c3rlqxv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.876 7.262c.027.037-.03.081-.095.13s-.114.083-.141.046c-.027-.036.003-.105.068-.154s.14-.058.168-.022Z");
}

.q1poyrpqb {
  fill: var(--svg-color--745249, #745249);
  fill-rule: evenodd;
  d: path("M8.395 10.692a.8.8 0 0 1-.307 1.09L4.56 13.758a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.856-2.148.347-2.918l3.575-2.014a.8.8 0 0 1 1.088.307Z");
}

.q4mqk8k3c {
  d: path("m18.96 18.206l3.154 1.125l-1.22 9.142a1.828 1.828 0 0 1-1.812 1.583a.122.122 0 0 1-.122-.122V18.206Z");
}

.q617abcdu {
  cx: 20.908px;
  cy: 7.345px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.q9er1fboq {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m8.75 7.501l-.295.732a.232.232 0 0 0 .224.3h.339c.158 0 .27-.152.224-.3L9.013 7.5c-.049-.162-.212-.162-.264 0Z");
}

.qabbs-ldy {
  cx: 18.559px;
  cy: 16.633px;
  r: 0.766px;
  fill: var(--svg-color--693a42, #693A42);
}

.qdb64dbny {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.817 3.296c-.222.71-.523 1.166-.645 1.305l-.633-.242c.013-.182.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29Z");
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qij7z_5st {
  fill: var(--svg-color--272528, #272528);
  d: path("M8.427 7.352c-.114-.201-.288-.36-.662-.36a.713.713 0 0 0-.462.159c-.115.094-.1.213-.01.258l.24.137c.28-.091.59-.103.894-.194Z");
}

.qj71mlzuz {
  d: path("m25.169 18.3l-2.828.953l4.334 9.27a2.64 2.64 0 0 0 2.398 1.533c.121 0 .206-.12.166-.234L25.169 18.3Z");
}

.qokwrdjlv {
  d: path("M24.042 8.336a.693.693 0 1 0 0-1.385a.693.693 0 0 0 0 1.385Z");
}

.qsgbqabcy {
  cx: 5.514px;
  cy: 16.587px;
  r: 0.766px;
  fill: var(--svg-color--693a42, #693A42);
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

.r4uzb-bfk {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m21.795 7.547l-.294.732a.232.232 0 0 0 .224.301h.338c.159 0 .27-.153.224-.301l-.229-.732c-.049-.162-.212-.162-.263 0Z");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rifc_5b5l {
  d: path("M8.953 9.66c.106.003.217.012.328.02c-.11-.008-.218-.017-.328-.02Z");
}

.rmlg14bhc {
  d: path("m5.915 18.16l3.154 1.125l-1.22 9.141a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V18.16Z");
}

.s_plahh6j {
  stop-color: var(--svg-color--774d4a, #774D4A);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sk_t0ijru {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.72 4.827c.01.105.1.498.234.736");
}

.sl9-fccme {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m10.525 6.635l-.06.099l.06-.1a.116.116 0 0 1-.119.199l-.002-.001a.455.455 0 0 0-.049-.025a1.177 1.177 0 0 0-.147-.058a.977.977 0 0 0-.462-.04a.115.115 0 0 1-.04-.227c.221-.04.426 0 .572.047a1.414 1.414 0 0 1 .24.102l.005.003h.001Z");
}

.ss5dpkd_r {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M19.955 8.105a.462.462 0 1 0 0-.924a.462.462 0 0 0 0 .924Z");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t3pocfb3y {
  d: path("M6.729 7.053h.005L6.73 6.94l-.005-.132c.01-.408.247-.566.349-.619l.022-.009a.992.992 0 0 0 .534-.54l.035-.083a.114.114 0 0 1 .2-.022c.308.452.825.72 1.372.72h1.386c.078 0 .466.038.489.574L11.06 8.15c-.053 1.207-.995 2.017-2.145 2.017S6.824 9.357 6.77 8.15l-.042-1.097Z");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.txwk9g23l {
  stop-color: var(--svg-color--8d6d67, #8D6D67);
  stop-opacity: 0;
}

.ufu-ghvir {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.674 4.78c.01.106.101.499.234.737");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.ush5kqbwh {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M9.41 7.352c.114-.201.288-.36.662-.36c.163 0 .321.046.462.159c.115.094.1.213.01.258l-.24.137c-.28-.091-.59-.103-.894-.194Z");
}

.ut1ryzbes {
  cx: 20.908px;
  cy: 7.345px;
  rx: 0.168px;
  ry: 0.085px;
}

.uylr5nywc {
  d: path("M11.048 5.728c.018.096-.102.144-.167.07c-.453-.513-1.132-1.011-2.023-1.011c-.838 0-1.553.533-2.033 1.064c-.064.072-.182.025-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.v0fg4m7wo {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M18.96 12.838a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.459.117.675l.444 1.236l-2.758 1.022l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.565Z");
}

.v2j2cxb_d {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M6.737 5.02c.243-.259.704-.26.917-.22l.17.555a.329.329 0 0 0-.287.1c-.193.543-.857.843-1.164.924c-.064-.642.047-1.024.364-1.36Z");
}

.v6mxwya9l {
  d: path("M21.704 4.29c-.488-.108-.925.378-.976.559c.453 1.526 1.598 1.442 2.73 1.317c.676-.076.75.233.807.382c0-1.693-1.44-2.01-2.549-2.256l-.012-.002Z");
}

.v85-ckaxn {
  d: path("M21.998 9.705Z");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vhmwta2qj {
  cx: 7.862px;
  cy: 7.299px;
  rx: 0.168px;
  ry: 0.085px;
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vpnhhy5yj {
  d: path("M8.811 9.66h-.017c.043 0 .082 0 .124.003c-.034-.004-.072-.004-.107-.004Z");
}

.w2ejlbckb {
  stop-color: var(--svg-color--876058, #876058);
}

.w947xh_cz {
  d: path("M8.659 4.244c-.488-.108-.926.378-.976.559c.453 1.526 1.598 1.442 2.73 1.316c.676-.075.75.234.807.383c0-1.693-1.44-2.01-2.549-2.256l-.012-.002Z");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wv6kv35lx {
  d: path("M10.996 8.29a.693.693 0 1 0 0-1.386a.693.693 0 0 0 0 1.385Z");
}

.wz6gy8bco {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.918 8.85c-.224 0-.434-.054-.612-.148c-.06-.032-.125.038-.087.094a.832.832 0 0 0 1.399 0c.038-.058-.027-.126-.088-.094a1.297 1.297 0 0 1-.612.148Z");
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x4y51kb4t {
  stop-color: var(--svg-color--906665, #906665);
}

.x68ij2b_y {
  fill: var(--svg-color--815a5c, #815A5C);
  fill-rule: evenodd;
  d: path("M22.414 10.739a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.191l1.973-1.72c.93-.821.856-2.149-.347-2.918l-3.907-2.12c-.385-.216-.54.027-.756.413Z");
}

.xbalo5d6h {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M22.455 7.398c.115-.2.288-.36.662-.36a.71.71 0 0 1 .462.16c.116.093.1.213.01.257l-.239.137c-.28-.09-.59-.103-.895-.194Z");
}

.xdkb6wisn {
  fill: var(--svg-color--745249, #745249);
  fill-rule: evenodd;
  d: path("M21.44 10.739a.8.8 0 0 1-.307 1.089l-3.527 1.977a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.191l-1.973-1.72c-.93-.82-.855-2.149.348-2.918l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xhcvxeb0g {
  d: path("M24.042 8.105a.462.462 0 1 0 0-.924a.462.462 0 0 0 0 .924Z");
}

.xohph8avb {
  d: path("M21.024 7.18a.384.384 0 0 0-.37.486h.742a.387.387 0 0 0-.372-.485Z");
}

.xvs5rgbvd {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M6.91 8.06a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .924Z");
}

.y_nb4vsfw {
  d: path("M9.83 7.216c.028.036-.03.081-.094.13c-.066.048-.114.082-.141.046c-.028-.037.003-.106.068-.155c.065-.048.14-.058.167-.021Z");
}

.y2o07bc4o {
  stop-color: var(--svg-color--5d302d, #5D302D);
}

.ya-pfekwl {
  stop-color: var(--svg-color--7b575a, #7B575A);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ytvlyzboz {
  stroke: var(--svg-color--866a64, #866A64);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.894c-.088.073-.193.289.094.57a70.94 70.94 0 0 0 1.555 1.414");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zaeftuinl {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M19.782 5.066c.243-.258.704-.259.917-.22l.17.555a.329.329 0 0 0-.287.101c-.193.543-.856.842-1.164.924c-.064-.642.047-1.025.364-1.36Z");
}

.zc_xnbcsn {
  fill: var(--svg-color--000, #000);
  d: path("M21.244 7.565a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.196.321h.39a.218.218 0 0 0 .026-.1Z");
}

.zc-mq7btq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m23.303 10.958l3.55 2.002c.193.1.578.44.569 1.002");
}

.zo46f1umk {
  d: path("M22.364 10.015c.23.043.451.114.66.208l-.927 1.571a.25.25 0 0 1-.435.004l-.979-1.593c.17-.074.347-.132.531-.173l1.15-.017Z");
}

.zobfdsyko {
  d: path("M12.011 8.204a1.411 1.411 0 0 0 .024-1.176h.002a1.372 1.372 0 0 0-.12-.221l-.002-.002a1.395 1.395 0 0 1-.226-.762v-.004a1.42 1.42 0 0 0-1.42-1.42a.232.232 0 0 1-.196-.1a1.423 1.423 0 0 0-2.309 0a.243.243 0 0 1-.196.1h-.037a1.42 1.42 0 0 0-1.383 1.42v.004c0 .27-.079.536-.227.762v.002a1.42 1.42 0 0 0-.095 1.397c.03.06.03.135 0 .196a1.383 1.383 0 0 0 1.246 1.99h3.693a1.383 1.383 0 0 0 1.246-1.99a.221.221 0 0 1 0-.196Zm-5.277-1.15h-.005l.516 1.013c.053 1.207.523 0 1.673 0s1.652 1.343 1.705.137l.489-1.377c-.023-.535-.412-.573-.49-.573H9.238a1.663 1.663 0 0 1-1.373-.72a.114.114 0 0 0-.199.022l-.035.083a.992.992 0 0 1-.512.532l-.022.008l-.022.01c-.102.052-.34.21-.349.618l.005.132l.004.114Z");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

</style>
