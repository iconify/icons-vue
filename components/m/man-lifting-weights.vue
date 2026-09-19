<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNO478c)" transform="rotate(-27.486 8.007 6.843)" class="r2323ni5a"/><path fill="url(#iIqT2ic)" transform="rotate(-27.486 8.007 6.843)" class="r2323ni5a"/><path fill="url(#iFC3mCe)" transform="rotate(-27.486 8.007 6.843)" class="r2323ni5a"/><path fill="url(#ipPutBc)" transform="rotate(-27.486 8.007 6.843)" class="r2323ni5a"/><path fill="url(#i2XYmZd)" transform="scale(-1 1)rotate(-27.486 1.697 53.688)" class="pnmas4b0d"/><path fill="url(#igK5sqX)" transform="scale(-1 1)rotate(-27.486 1.697 53.688)" class="pnmas4b0d"/><path fill="url(#iieTJ2c)" transform="scale(-1 1)rotate(-27.486 1.697 53.688)" class="pnmas4b0d"/><path fill="url(#ivBLUee)" transform="scale(-1 1)rotate(-27.486 1.697 53.688)" class="pnmas4b0d"/><g filter="url(#iNPJJuc)"><path fill="url(#i8BsR3L)" class="q84b8gbos"/><path fill="url(#iyr2jjb)" class="q84b8gbos"/><path fill="url(#iA887td)" class="q84b8gbos"/><path fill="url(#iFJuqMg)" class="q84b8gbos"/></g><g filter="url(#iNRGCfg)"><rect fill="url(#iwpw4kb)" class="pfb3nmbzx"/><rect fill="url(#iAdAWNe)" class="pfb3nmbzx"/></g><g filter="url(#iMNVavb)"><path stroke="url(#iYb926c)" class="sp615bwzb"/></g><path fill="url(#idlHhwb)" class="r0vct0bxc"/><path fill="url(#ivey35x)" class="llt2d4k3t"/><path fill="url(#ipQOJKe)" class="oim54biyf"/><path fill="url(#iSdqBig)" class="pfa_6pb4c"/><circle fill="url(#ilC5L2c)" class="ahr5oi4iv"/><path fill="url(#iBti5ab)" class="d17nnkbms"/><path fill="url(#i0xsB9P)" class="hvv7pu--y"/><path fill="url(#iGqQgCb)" class="fcgf5xxjn"/><path fill="url(#iHoD9xe)" class="rrrtuhbgt"/><circle fill="url(#i9Hs44c)" transform="matrix(-1 0 0 1 21.67 6.992)" class="e4y-1lbum"/><g filter="url(#iV1Xz1b)"><path fill="url(#ibC7Xxd)" class="v7ljtacue"/><path fill="url(#iSU9J2d)" class="v7ljtacue"/><path fill="url(#ipIvzvg)" class="v7ljtacue"/></g><g filter="url(#irZQC2b)"><path fill="url(#ipf3ntc)" class="ikuh81bgr"/><path fill="url(#ijG1Scb)" class="ikuh81bgr"/><path fill="url(#iRbdFhE)" class="ikuh81bgr"/></g><g filter="url(#iBxc1ZI)"><path fill="url(#iVMgWCa)" class="yjimcbbiz"/><path fill="url(#iJSJ9nw)" class="yjimcbbiz"/></g><g filter="url(#i1nsBrW)"><path fill="url(#ioV9Wyr)" class="p6n01rbon"/><path fill="url(#iCRW0ab)" class="p6n01rbon"/><path fill="url(#ilUg4zb)" class="p6n01rbon"/></g><g filter="url(#iYlAZ1d)"><path fill="url(#i3kYRIe)" class="ykomameua"/><path fill="url(#igbGzse)" class="ykomameua"/></g><g filter="url(#igrEknk)"><path class="uqmb6ugxh"/></g><g filter="url(#iuSnGrc)"><path fill="url(#i8WwGCb)" class="on8yo4b7v"/><path fill="url(#inENCpe)" class="on8yo4b7v"/></g><g filter="url(#iBFrJpb)"><path fill="url(#ifsN2De)" class="d1gp_g11g"/></g><g filter="url(#i2siG0d)"><path class="y-e7vcc5k"/></g><g filter="url(#ilH0avf)"><path fill="url(#iDPYmGc)" class="ll_709mpe"/><path fill="url(#iuXozJe)" class="ll_709mpe"/></g><g filter="url(#iUK4tAb)"><path fill="url(#i7Wc23i)" class="f4gqbz3op"/></g><circle fill="url(#i84u7vb)" class="nljnqb0nz"/><g filter="url(#iZolsib)"><circle fill="url(#i1TBlmd)" class="nogq8eago"/></g><g filter="url(#izIhckQ)"><circle fill="url(#iiy1o8b)" class="ol19wcbvf"/><circle fill="url(#iadz8Oc)" class="ol19wcbvf"/></g><g filter="url(#itoDS5b)"><circle class="zgbx-wnop"/><circle fill="url(#idhdSwb)" class="f1tl95bzc"/><circle fill="url(#i4wY4WJ)" class="f1tl95bzc"/></g><path fill="url(#i5Ufv5c)" class="aphn9woct"/><path fill="url(#iMpB6Wi)" class="aphn9woct"/><path fill="url(#iYTxBIv)" class="aphn9woct"/><path fill="url(#ifytHbe)" class="aphn9woct"/><path fill="url(#i1rUjhd)" class="aphn9woct"/><g filter="url(#isvseyd)"><path class="mt8rpyb3q"/><path fill="url(#ieFXU1c)" class="j98jk_0ni"/><path fill="url(#i7tmiRd)" class="j98jk_0ni"/><path fill="url(#igheYXp)" class="j98jk_0ni"/><path fill="url(#inx0mrd)" class="j98jk_0ni"/><path fill="url(#inSfJ1c)" class="j98jk_0ni"/><path fill="url(#ieGGOhd)" class="j98jk_0ni"/></g><path fill="url(#ib0UTYc)" class="j98jk_0ni"/><path fill="url(#iOouw6d)" class="j98jk_0ni"/><path fill="url(#iqeMtfb)" class="j98jk_0ni"/><g filter="url(#iOZbCfb)"><path class="qo_n--bed"/></g><g filter="url(#iIsAJRd)"><path class="amvrbvbxw"/><path fill="url(#iL8Gz9h)" class="zc5-d7b0z"/><path fill="url(#i1PMOPe)" class="zc5-d7b0z"/><path fill="url(#iQWPc5d)" class="zc5-d7b0z"/></g><path class="yk2muc65a"/><path class="bovpymbne"/><path fill="url(#iWVnsQc)" class="r54c9vbje"/><path class="kl1u7rbsv"/><g filter="url(#ieG1T2d)"><path class="wjfhnjbtt"/><path fill="url(#iMlmuuc)" class="li45d39az"/></g><g filter="url(#id80Muk)"><path fill="url(#ixiEaXF)" class="ddwgo9b7x"/></g><path class="jxkt3cb4q"/><path fill="url(#iNS63wb)" class="h71_zvbhv"/><path class="r1rc_gbab"/><g filter="url(#iDq1gBe)"><path fill="url(#ir0iDsc)" class="n5c0xsaoq"/></g><g filter="url(#icZJEYd)"><ellipse transform="rotate(-27.914 15.136 12.943)" class="mf1korzxm"/><ellipse fill="url(#ik3TP0c)" transform="rotate(-27.914 15.136 12.943)" class="njp91_blj"/></g><g filter="url(#iGOAAHe)"><path fill="url(#iEhwTGd)" clip-rule="evenodd" class="w6lcltbke"/></g><g filter="url(#iVjKgpd)"><path class="x7o57ybft"/></g><g filter="url(#ioqzVFj)"><path fill="url(#iCftLPc)" clip-rule="evenodd" class="ii3rax_td"/></g><g filter="url(#ibhVIJd)"><path class="cpqj88hcl"/></g><defs><radialGradient id="iNO478c" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -.675 10.556)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="g77rtfbof"/><stop offset="1" class="x1baucbnz"/></radialGradient><radialGradient id="iFC3mCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.312 7.761)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tifd2nbhd"/><stop offset="1" class="o4u-l0lno"/></radialGradient><radialGradient id="ipPutBc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.498 6.824)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="yyejvbcrw"/><stop offset="1" class="i1j-sacds"/></radialGradient><radialGradient id="i2XYmZd" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -1.122 2.973)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="g77rtfbof"/><stop offset="1" class="x1baucbnz"/></radialGradient><radialGradient id="iieTJ2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 2.305 .918)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tifd2nbhd"/><stop offset="1" class="o4u-l0lno"/></radialGradient><radialGradient id="ivBLUee" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="yyejvbcrw"/><stop offset="1" class="i1j-sacds"/></radialGradient><radialGradient id="i8BsR3L" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.647 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="iFJuqMg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 18.21 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iwpw4kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 18.053 5.688)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="iAdAWNe" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 9.233 6.266)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="idlHhwb" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 4.127 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="i3etvmbtq"/><stop offset="1" class="v3dxsi25s"/></radialGradient><radialGradient id="ivey35x" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 9.135 5.867)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="ipQOJKe" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.167 3.121)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="iSdqBig" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.823 3.117)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="bhv6r6bju"/><stop offset="1" class="zcsf4yb5o"/></radialGradient><radialGradient id="ilC5L2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.39453 .51953 -.51953 -.39453 11.053 6.832)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="m0lqw5bea"/><stop offset=".91" class="rdwyvqbpo"/></radialGradient><radialGradient id="iBti5ab" cx="0" cy="0" r="1" gradientTransform="matrix(.70313 0 0 1.26563 24.108 5.844)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="vjv772cbv"/><stop offset="1" class="f3x0tmb2q"/></radialGradient><radialGradient id="i0xsB9P" cx="0" cy="0" r="1" gradientTransform="rotate(176.697 11.964 3.28)scale(.90756 1.0035)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="xot5t6pkw"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="iGqQgCb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8606 .05074 -.05742 -.97387 22.663 5.887)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="u521robxh"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="iHoD9xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.90871 .05556 -.06514 -1.06541 23.38 5.889)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="u521robxh"/><stop offset="1" class="wjkbrmbdg"/></radialGradient><radialGradient id="i9Hs44c" cx="0" cy="0" r="1" gradientTransform="rotate(37.439 -.33 .432)scale(.62972)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="tydx0uunk"/><stop offset=".91" class="vea9pibbt"/></radialGradient><radialGradient id="ibC7Xxd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.584 18.75)" gradientUnits="userSpaceOnUse"><stop class="cnpza7b-j"/><stop offset="1" class="qcugcqlkb"/></radialGradient><radialGradient id="iSU9J2d" cx="0" cy="0" r="1" gradientTransform="rotate(111.28 3.002 12.537)scale(2.73303 3.08168)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="my3wtvo7r"/><stop offset="1" class="yi8xsxb7e"/></radialGradient><radialGradient id="ipIvzvg" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 20.097 21.248)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="xjez76bam"/><stop offset="1" class="fc_42m6ea"/></radialGradient><radialGradient id="ipf3ntc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.772 6.48)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iVMgWCa" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.565 6.48)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ioV9Wyr" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.346 6.48)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iCRW0ab" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 3.045 6.875)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i3kYRIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.71 6.48)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="igbGzse" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.46 6.875)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="inENCpe" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.282 12.158)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="ifsN2De" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.678 27.984)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iuXozJe" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.867 15.377)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="i7Wc23i" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.99 28.531)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="i84u7vb" cx="0" cy="0" r="1" gradientTransform="matrix(.8333 0 0 1.45828 13.253 12.734)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iadz8Oc" cx="0" cy="0" r="1" gradientTransform="matrix(.39256 -.28584 .32625 .44806 18.74 12.609)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="idhdSwb" cx="0" cy="0" r="1" gradientTransform="rotate(-61.468 20.309 -9.032)scale(.81644 .47786)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="i4wY4WJ" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -6.202 28.937)scale(.17324 .22333)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iYTxBIv" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.07689 -4.65507 0 16.54 12.202)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="ifytHbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62067 .7639 0 17.414 12.356)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="i1rUjhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.66045 .82133 0 15.25 12.34)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="ieFXU1c" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 6.75 9.07)scale(2.6621 4.52713)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="igheYXp" cx="0" cy="0" r="1" gradientTransform="matrix(-.0876 -.94614 .46467 -.04302 14.337 11.23)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="inx0mrd" cx="0" cy="0" r="1" gradientTransform="matrix(.40796 -.93378 .76158 .33273 18.307 12.134)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="inSfJ1c" cx="0" cy="0" r="1" gradientTransform="matrix(.47143 .58495 -.51647 .41623 15.932 8.875)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="ieGGOhd" cx="0" cy="0" r="1" gradientTransform="matrix(.689 -1.44148 .49805 .23806 18.289 10.956)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ib0UTYc" cx="0" cy="0" r="1" gradientTransform="matrix(.12402 .48193 -.79231 .20389 16.63 8.875)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iOouw6d" cx="0" cy="0" r="1" gradientTransform="matrix(.52563 .75925 -1.58 1.09384 14.22 9.474)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iqeMtfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.42247 1.54186 -1.9293 -4.28249 16.847 10.887)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iWVnsQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42886 -.50746 0 17.335 13.146)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iMlmuuc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.803 2.296)scale(.17939 .24698)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNS63wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42889 -.50748 0 15.264 13.146)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ik3TP0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00367 -.2343 .28164 -.00441 15.128 13.092)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iEhwTGd" cx="0" cy="0" r="1" gradientTransform="matrix(.10625 -.38213 .83835 .2331 15.097 12.253)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iCftLPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10625 -.38214 .83834 -.2331 17.53 12.265)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><filter id="iNPJJuc" width="9.5" height="4.284" x="11.444" y="21.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iNRGCfg" width="27.875" height="1.225" x="2.334" y="5.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iMNVavb" width="27.781" height=".75" x="2.295" y="6.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".125"/></filter><filter id="iV1Xz1b" width="10.708" height="10.353" x="11.075" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.490196 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="irZQC2b" width="1.93" height="8.989" x="5.311" y="1.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iBxc1ZI" width="1.93" height="8.989" x="25.264" y="1.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="i1nsBrW" width="1.93" height="5.973" x="3.381" y="3.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iYlAZ1d" width="1.93" height="5.973" x="27.194" y="3.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="igrEknk" width="3.719" height="6.065" x="9.162" y="22.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.654902 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.631373 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23307" result="effect2_innerShadow_3987_23307"/></filter><filter id="iuSnGrc" width="4.477" height="4.023" x="8.787" y="19.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iBFrJpb" width="4.833" height="2.114" x="7.311" y="27.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="i2siG0d" width="3.719" height="5.564" x="20.194" y="22.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.654902 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.576471 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23307" result="effect2_innerShadow_3987_23307"/></filter><filter id="ilH0avf" width="4.477" height="4.023" x="19.811" y="19.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iUK4tAb" width="4.833" height="2.114" x="20.431" y="27.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iZolsib" width="1.945" height="1.945" x="13.073" y="11.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".25"/></filter><filter id="izIhckQ" width="1.835" height="1.835" x="17.77" y="11.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="itoDS5b" width="1.945" height="1.945" x="17.591" y="11.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".25"/></filter><filter id="isvseyd" width="5.984" height="3.919" x="13.308" y="8.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iOZbCfb" width="1.636" height="2.073" x="15.369" y="12.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".2"/></filter><filter id="iIsAJRd" width="1.091" height="1.473" x="15.754" y="12.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".05"/></filter><filter id="ieG1T2d" width=".378" height=".335" x="16.983" y="12.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".025"/></filter><filter id="id80Muk" width=".333" height=".344" x="17.43" y="12.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".025"/></filter><filter id="iDq1gBe" width=".378" height=".404" x="15.322" y="12.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".025"/></filter><filter id="icZJEYd" width=".438" height=".339" x="14.916" y="12.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".025"/></filter><filter id="iGOAAHe" width="1.238" height=".914" x="14.49" y="11.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="iVjKgpd" width="1.289" height=".716" x="14.49" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".1"/></filter><filter id="ioqzVFj" width="1.238" height=".914" x="16.899" y="11.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23307"/></filter><filter id="ibhVIJd" width="1.289" height=".716" x="16.848" y="11.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23307" stdDeviation=".1"/></filter><linearGradient id="iIqT2ic" x1="7.435" x2="8.556" y1="7.942" y2="8.088" gradientUnits="userSpaceOnUse"><stop offset=".136" class="rysyofyzl"/><stop offset="1" class="d85j9ed1i"/></linearGradient><linearGradient id="igK5sqX" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="rysyofyzl"/><stop offset="1" class="d85j9ed1i"/></linearGradient><linearGradient id="iyr2jjb" x1="20.584" x2="18.053" y1="25.25" y2="24.813" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="iA887td" x1="11.897" x2="14.709" y1="25.344" y2="24.25" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="iYb926c" x1="2.67" x2="30.139" y1="7.398" y2="7.398" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="ijG1Scb" x1="5.311" x2="6.803" y1="7.469" y2="7.469" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iRbdFhE" x1="5.311" x2="5.584" y1="7.34" y2="7.34" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iJSJ9nw" x1="25.264" x2="26.459" y1="6.48" y2="6.48" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="ilUg4zb" x1="3.229" x2="3.723" y1="6.48" y2="6.48" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="i8WwGCb" x1="12.764" x2="8.787" y1="21.766" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iDPYmGc" x1="19.811" x2="23.787" y1="21.766" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="i1TBlmd" x1="14.046" x2="13.741" y1="12.867" y2="12.867" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iiy1o8b" x1="19.079" x2="18.69" y1="12.216" y2="13.42" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i5Ufv5c" x1="18.216" x2="14.59" y1="13.144" y2="13.685" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iMpB6Wi" x1="13.738" x2="14.836" y1="14.425" y2="14.281" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="i7tmiRd" x1="13.992" x2="15.37" y1="12.832" y2="10.385" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iL8Gz9h" x1="15.889" x2="16.335" y1="13.698" y2="13.698" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="i1PMOPe" x1="16.745" x2="16.258" y1="13.851" y2="13.844" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iQWPc5d" x1="16.392" x2="16.392" y1="14.204" y2="13.932" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ixiEaXF" x1="17.704" x2="17.555" y1="13.014" y2="13.105" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ir0iDsc" x1="15.618" x2="15.469" y1="13.014" y2="13.105" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-lifting-weights" /></template>
<style>
.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.ahr5oi4iv {
  cx: 10.858px;
  cy: 6.992px;
  r: 0.398px;
}

.amvrbvbxw {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m16.118 13.065l-.252.807a.256.256 0 0 0 .247.332h.373a.257.257 0 0 0 .248-.332l-.253-.807c-.054-.18-.306-.18-.363 0");
}

.aphn9woct {
  d: path("M13.878 12.668a14 14 0 0 1-.027-.683c0-.126.05-.278.152-.354l.077-.076a.5.5 0 0 0 .178-.405v-.406c0-.126.077-.227.204-.253c.306-.076.942-.202 1.86-.202c.916 0 1.553.126 1.859.202a.27.27 0 0 1 .203.253v.406c0 .152.077.303.179.405c.238.167.223.259.203.456c-.006.06-.025.567-.042.683l-.126 1.88c-.076.84-.737 1.426-1.525 1.426H15.55c-.813 0-1.448-.586-1.524-1.426z");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.bhv6r6bju {
  stop-color: var(--svg-color--ffd83f, #FFD83F);
}

.bovpymbne {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.434 12.632c.31 0 .572.214.643.503a.13.13 0 0 1-.127.162h-1.06a.11.11 0 0 1-.107-.13a.664.664 0 0 1 .651-.535");
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnpza7b-j {
  stop-color: var(--svg-color--4baeff, #4BAEFF);
}

.cpqj88hcl {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.887 11.986c-.131-.032-.453-.03-.79.201");
}

.d17nnkbms {
  d: path("M24.755 5.701a.399.399 0 1 0-.796-.033v.46a.38.38 0 0 0 .757.032z");
}

.d1gp_g11g {
  d: path("M7.31 29.522v.376h4.634v-1.914H9.592c-.383.377-1.215.73-1.836.942c-.398.168-.445.442-.445.596");
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.d85j9ed1i {
  stop-color: var(--svg-color--af7222, #AF7222);
  stop-opacity: 0;
}

.ddwgo9b7x {
  d: path("M17.713 13.13a.4.4 0 0 0-.11-.22l-.123.135l.055.108z");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e4y-1lbum {
  r: 0.398px;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f1tl95bzc {
  cx: 18.563px;
  cy: 12.734px;
  r: 0.472px;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f3x0tmb2q {
  stop-color: var(--svg-color--ad8518, #AD8518);
}

.f4gqbz3op {
  d: path("M25.264 29.522v.376H20.63v-1.914h2.352c.383.377 1.215.73 1.836.942c.398.168.445.442.445.596");
}

.fc_42m6ea {
  stop-color: var(--svg-color--3a9cef, #3A9CEF);
  stop-opacity: 0;
}

.fcgf5xxjn {
  d: path("M22.663 5.618a.401.401 0 1 0-.802-.014v.575a.391.391 0 0 0 .783.013z");
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g77rtfbof {
  stop-color: var(--svg-color--ffdf3f, #FFDF3F);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.h71_zvbhv {
  d: path("M15.264 12.762a.424.424 0 0 0-.409.535h.819a.427.427 0 0 0-.41-.535");
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.hvv7pu--y {
  d: path("M24.095 5.62a.422.422 0 1 0-.843-.034v.585a.4.4 0 0 0 .798.03z");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i1j-sacds {
  stop-color: var(--svg-color--efad2e, #EFAD2E);
  stop-opacity: 0;
}

.i3etvmbtq {
  stop-color: var(--svg-color--ffc935, #FFC935);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ii3rax_td {
  fill-rule: evenodd;
  d: path("M17.25 12.418c.284-.195.54-.185.61-.168a.224.224 0 1 0 .105-.436c-.192-.046-.58-.033-.968.234a.224.224 0 1 0 .254.37");
}

.ikuh81bgr {
  d: path("M5.31 2.886a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j98jk_0ni {
  d: path("m18.588 9.883l.204.102c.357.177.56.582.484 1.013l-.28 1.443c-.025.15-.124.25-.272.253c.017-.239.033-.625.04-.686c.02-.205-.013-.266-.201-.453a.6.6 0 0 1-.178-.405v-.006a.27.27 0 0 0-.204-.253c-.306-.076-.943-.203-1.86-.203s-1.553.127-1.859.203a.25.25 0 0 0-.204.253v.006a.5.5 0 0 1-.178.405l-.076.076c-.102.076-.154.235-.154.361c.007.074.017.5.028.676a.3.3 0 0 1-.282-.252l-.28-1.444a.97.97 0 0 1 .51-.987c.48-.211.656-.532 1.044-.861a.93.93 0 0 1 1.044-.152c.255.076.535.076.79 0a1.15 1.15 0 0 1 1.12.253l.382.38c.102.126.23.202.382.278");
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.jxkt3cb4q {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.165 12.632a.66.66 0 0 0-.643.503a.13.13 0 0 0 .127.162h1.06a.11.11 0 0 0 .107-.13a.665.665 0 0 0-.65-.535");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kl1u7rbsv {
  fill: var(--svg-color--000, #000);
  d: path("M17.093 13.185c0-.135.108-.242.243-.242a.242.242 0 0 1 .215.354h-.43a.2.2 0 0 1-.028-.112");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li45d39az {
  d: path("M17.304 12.851c.03.04-.033.09-.104.143c-.072.054-.125.091-.155.051s.003-.116.075-.17c.071-.053.154-.064.184-.024");
}

.ll_709mpe {
  d: path("M23.787 21.059a1.988 1.988 0 0 0-3.976 0v1.685c0 .193.157.35.35.35h3.276a.35.35 0 0 0 .35-.35z");
}

.llt2d4k3t {
  d: path("M8.432 5.62a.422.422 0 1 1 .844-.034v.585a.4.4 0 0 1-.799.03z");
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.m0lqw5bea {
  stop-color: var(--svg-color--ffd741, #FFD741);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mf1korzxm {
  cx: 15.136px;
  cy: 12.943px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.185px;
  ry: 0.094px;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mt8rpyb3q {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m18.588 9.883l.204.102c.357.177.56.582.484 1.013l-.28 1.443c-.025.15-.124.25-.272.253c.017-.239.033-.625.04-.686c.02-.205-.013-.266-.201-.453a.6.6 0 0 1-.178-.405v-.006a.27.27 0 0 0-.204-.253c-.306-.076-.943-.203-1.86-.203s-1.553.127-1.859.203a.25.25 0 0 0-.204.253v.006a.5.5 0 0 1-.178.405l-.076.076c-.102.076-.154.235-.154.361c.007.074.017.5.028.676a.3.3 0 0 1-.282-.252l-.28-1.444a.97.97 0 0 1 .51-.987c.48-.211.656-.532 1.044-.861a.93.93 0 0 1 1.044-.152c.255.076.535.076.79 0a1.15 1.15 0 0 1 1.12.253l.382.38c.102.126.23.202.382.278");
}

.my3wtvo7r {
  stop-color: var(--svg-color--2161bb, #2161BB);
}

.n5c0xsaoq {
  d: path("M15.65 13.135c0-.136-.11-.228-.14-.255l-.138.132l.085.172z");
}

.njp91_blj {
  cx: 15.136px;
  cy: 12.943px;
  rx: 0.185px;
  ry: 0.094px;
}

.nljnqb0nz {
  cx: 14.045px;
  cy: 12.734px;
  r: 0.793px;
}

.nogq8eago {
  cx: 14.046px;
  cy: 12.734px;
  r: 0.472px;
}

.o4u-l0lno {
  stop-color: var(--svg-color--eca42a, #ECA42A);
  stop-opacity: 0;
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oim54biyf {
  d: path("M9.864 5.618a.401.401 0 1 1 .802-.014v.575a.391.391 0 0 1-.782.013z");
}

.ol19wcbvf {
  cx: 18.563px;
  cy: 12.734px;
  r: 0.793px;
}

.on8yo4b7v {
  d: path("M8.787 21.059a1.988 1.988 0 1 1 3.977 0v1.685a.35.35 0 0 1-.35.35H9.137a.35.35 0 0 1-.35-.35z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p6n01rbon {
  d: path("M3.381 4.394a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pfa_6pb4c {
  d: path("M9.147 5.58a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.822.016z");
}

.pfb3nmbzx {
  width: 27.875px;
  height: 1.025px;
  x: 2.334px;
  y: 5.967px;
  rx: 0.2px;
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q84b8gbos {
  d: path("M16.272 25.922c-2.363 0-4.203-.719-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qcugcqlkb {
  stop-color: var(--svg-color--2e82d2, #2E82D2);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qo_n--bed {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m16.17 13.142l-.39.807c-.049.166.067.332.231.332h.35c.165 0 .28-.168.232-.332l-.236-.807c-.051-.179-.135-.179-.188 0");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0vct0bxc {
  d: path("M7.773 5.701a.399.399 0 1 1 .796-.033v.46a.38.38 0 0 1-.758.032z");
}

.r1rc_gbab {
  fill: var(--svg-color--000, #000);
  d: path("M15.506 13.185a.24.24 0 0 0-.242-.242a.242.242 0 0 0-.216.354h.43a.24.24 0 0 0 .028-.112");
}

.r2323ni5a {
  d: path("M8.007 6.843h2.46v7.269h-2.46z");
}

.r54c9vbje {
  d: path("M17.336 12.762a.424.424 0 0 1 .408.535h-.819a.425.425 0 0 1 .41-.535");
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rdwyvqbpo {
  stop-color: var(--svg-color--d69025, #D69025);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rrrtuhbgt {
  d: path("M23.38 5.58a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.016z");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.rysyofyzl {
  stop-color: var(--svg-color--825426, #825426);
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.sp615bwzb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.67 6.398h27.031");
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tifd2nbhd {
  stop-color: var(--svg-color--ba760f, #BA760F);
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tydx0uunk {
  stop-color: var(--svg-color--f2b927, #F2B927);
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u521robxh {
  stop-color: var(--svg-color--fdc632, #FDC632);
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.uqmb6ugxh {
  fill: var(--svg-color--ffdf41, #FFDF41);
  d: path("m9.675 28.87l-.513-5.893h3.22l-.534 5.965z");
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.v3dxsi25s {
  stop-color: var(--svg-color--ae7a16, #AE7A16);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7ljtacue {
  d: path("m11.22 13.018l2.396-1.12l2.578 3.399l2.468-3.563l2.73 1.318a.25.25 0 0 1 .113.34l-1.194 2.304a1 1 0 0 0-.112.48l.12 5.762h-7.985V16.15a1 1 0 0 0-.098-.433L11.1 13.353a.25.25 0 0 1 .12-.335");
}

.vea9pibbt {
  stop-color: var(--svg-color--cc8e21, #CC8E21);
}

.vjv772cbv {
  stop-color: var(--svg-color--e1a82d, #E1A82D);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.w6lcltbke {
  fill-rule: evenodd;
  d: path("M15.377 12.406c-.283-.194-.54-.184-.61-.168a.224.224 0 1 1-.105-.436c.192-.046.58-.033.969.235a.224.224 0 1 1-.255.37");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wjfhnjbtt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.304 12.851c.03.04-.033.09-.104.143c-.072.054-.125.091-.155.051s.003-.116.075-.17c.071-.053.154-.064.184-.024");
}

.wjkbrmbdg {
  stop-color: var(--svg-color--d08d1f, #D08D1F);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x1baucbnz {
  stop-color: var(--svg-color--eba32a, #EBA32A);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x7o57ybft {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.74 11.974c.132-.031.453-.03.79.202");
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xjez76bam {
  stop-color: var(--svg-color--1071cb, #1071CB);
}

.xot5t6pkw {
  stop-color: var(--svg-color--e9b430, #E9B430);
}

.y-e7vcc5k {
  fill: var(--svg-color--ffdf41, #FFDF41);
  d: path("m22.94 28.44l.472-5.463h-3.218l.477 5.464z");
}

.yi8xsxb7e {
  stop-color: var(--svg-color--3770bc, #3770BC);
  stop-opacity: 0;
}

.yjimcbbiz {
  d: path("M27.194 2.886a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.yk2muc65a {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.3 14.733c-.241 0-.468-.056-.658-.156c-.065-.033-.135.04-.094.1a.9.9 0 0 0 .752.401c.315 0 .592-.16.752-.401c.04-.062-.03-.133-.095-.1c-.19.1-.414.156-.657.156");
}

.ykomameua {
  d: path("M29.123 4.394a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yyejvbcrw {
  stop-color: var(--svg-color--d48a23, #D48A23);
}

.zc5-d7b0z {
  d: path("m16.118 13.065l-.252.807a.256.256 0 0 0 .247.332h.373a.257.257 0 0 0 .248-.332l-.253-.807c-.054-.18-.306-.18-.363 0");
}

.zcsf4yb5o {
  stop-color: var(--svg-color--e0a20c, #E0A20C);
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zgbx-wnop {
  cx: 18.563px;
  cy: 12.734px;
  r: 0.472px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
