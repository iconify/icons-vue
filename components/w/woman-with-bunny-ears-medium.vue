<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#svgIDa)" class="d2kvgvbvc"><path fill="url(#svgIDb)" class="kl5t8b-wc"/><path fill="url(#svgIDc)" class="kl5t8b-wc"/><path fill="url(#svgIDd)" class="kl5t8b-wc"/><path fill="url(#svgIDe)" class="kl5t8b-wc"/><path fill="url(#svgIDf)" class="kl5t8b-wc"/><path fill="url(#svgIDg)" class="kl5t8b-wc"/><path fill="url(#svgIDh)" class="kl5t8b-wc"/><path fill="url(#svgIDi)" class="kl5t8b-wc"/><path fill="url(#svgIDj)" class="kl5t8b-wc"/><path fill="url(#svgIDk)" class="kl5t8b-wc"/><path fill="url(#svgIDl)" class="kl5t8b-wc"/><path fill="url(#svgIDm)" class="kl5t8b-wc"/></g><g filter="url(#svgIDn)"><path fill="url(#svgIDo)" class="m13u431kg"/><path fill="url(#svgIDp)" class="m13u431kg"/></g><g filter="url(#svgIDq)"><path fill="url(#svgIDr)" class="ih9jpspul"/></g><g filter="url(#svgIDs)"><path class="pp409vf4q"/></g><path fill="url(#svgIDt)" class="xbx983bqi"/><path fill="url(#svgIDu)" class="xbx983bqi"/><path fill="url(#svgIDv)" class="d1e4u8m5p"/><path fill="url(#svgIDw)" class="d1e4u8m5p"/><circle fill="url(#svgIDx)" class="dhdllmbnv"/><g filter="url(#svgIDy)"><path clip-rule="evenodd" class="yfip4ewpb"/></g><circle fill="url(#svgIDz)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDA)"><path clip-rule="evenodd" class="iw4kkgb9v"/></g><g filter="url(#svgIDB)"><path stroke="url(#svgIDC)" class="wtdu8s9gc"/></g><g filter="url(#svgIDD)"><path class="g8jg3w7ba"/></g><path fill="url(#svgIDE)" class="rn6o83bbv"/><path fill="url(#svgIDF)" class="rn6o83bbv"/><path fill="url(#svgIDG)" class="rn6o83bbv"/><path fill="url(#svgIDH)" class="rn6o83bbv"/><path fill="url(#svgIDI)" class="rn6o83bbv"/><path fill="url(#svgIDJ)" class="bu8cbcb5t"/><g filter="url(#svgIDK)"><path class="sbcwsbc2z"/></g><path fill="url(#svgIDL)" class="o7s685biz"/><path fill="url(#svgIDM)" class="i5qnlkb7r"/><g filter="url(#svgIDN)"><path fill="url(#svgIDO)" class="juat2ccab"/></g><path fill="url(#svgIDP)" class="juat2ccab"/><g filter="url(#svgIDQ)"><path fill="url(#svgIDR)" class="dgz-pcbjo"/><path fill="url(#svgIDS)" class="dgz-pcbjo"/></g><g filter="url(#svgIDT)"><path class="y0kpo0b3j"/><path fill="url(#svgIDU)" class="p1op2_pku"/></g><g filter="url(#svgIDV)"><path class="k2oy8rbvq"/><path fill="url(#svgIDW)" class="f2kz_-b-b"/></g><g filter="url(#svgIDX)"><path fill="url(#svgIDY)" class="hxhlt-5kf"/><path fill="url(#svgIDZ)" class="hxhlt-5kf"/><path fill="url(#svgIDaa)" class="hxhlt-5kf"/><path fill="url(#svgIDab)" class="hxhlt-5kf"/><path fill="url(#svgIDac)" class="hxhlt-5kf"/><path fill="url(#svgIDad)" class="hxhlt-5kf"/><path fill="url(#svgIDae)" class="hxhlt-5kf"/><path fill="url(#svgIDaf)" class="hxhlt-5kf"/></g><path fill="url(#svgIDag)" class="hxhlt-5kf"/><g filter="url(#svgIDah)"><path class="y9sk--bki"/></g><g filter="url(#svgIDai)"><path class="x8qx1chyk"/><path fill="url(#svgIDaj)" class="bf_q98buf"/><path fill="url(#svgIDak)" class="bf_q98buf"/><path fill="url(#svgIDal)" class="bf_q98buf"/><path fill="url(#svgIDam)" class="bf_q98buf"/></g><g filter="url(#svgIDan)"><path stroke="url(#svgIDao)" class="c9qmapbez"/></g><path class="jqr179a-y"/><g filter="url(#svgIDap)"><path class="u395am2di"/></g><g filter="url(#svgIDaq)"><path class="ju_febl2z"/></g><g filter="url(#svgIDar)"><path class="do-ctebya"/></g><g filter="url(#svgIDas)"><path clip-rule="evenodd" class="gdjp32joa"/></g><path class="mlz1_3shy"/><path fill="url(#svgIDat)" class="a09-_rbjr"/><path class="vosupht-x"/><g filter="url(#svgIDau)"><path class="r5sk2m5_h"/><path fill="url(#svgIDav)" class="ah7lx2b2u"/></g><g filter="url(#svgIDaw)"><path fill="url(#svgIDax)" class="b5t1_sbqs"/></g><path class="xtgnltbbo"/><path fill="url(#svgIDay)" class="m2_nb2bed"/><path class="fz06w4zyp"/><g filter="url(#svgIDaz)"><path fill="url(#svgIDaA)" class="p_9dvab3h"/></g><g filter="url(#svgIDaB)" transform="rotate(-27.914 7.798 7.322)"><ellipse class="xy4leobwb"/><ellipse fill="url(#svgIDaC)" class="x-q4feb6o"/></g><g filter="url(#svgIDaD)"><path class="bt9it9b5j"/><path fill="url(#svgIDaE)" class="ce22v4b6v"/><path fill="url(#svgIDaF)" class="ce22v4b6v"/></g><g filter="url(#svgIDaG)"><path class="zwe3oacdw"/><path fill="url(#svgIDaH)" class="ju0xvk2bt"/><path fill="url(#svgIDaI)" class="ju0xvk2bt"/></g><g filter="url(#svgIDaJ)"><path class="qe8xsfyen"/></g><g filter="url(#svgIDaK)"><path class="ev0kozb_a"/></g><g filter="url(#svgIDaL)"><path class="mddk40bcp"/></g><g filter="url(#svgIDaM)"><path fill="url(#svgIDaN)" class="ubd-76htt"/></g><g clip-rule="evenodd" filter="url(#svgIDaO)" class="d2kvgvbvc"><path fill="url(#svgIDaP)" class="yw6lu845o"/><path fill="url(#svgIDaQ)" class="yw6lu845o"/><path fill="url(#svgIDaR)" class="yw6lu845o"/><path fill="url(#svgIDaS)" class="yw6lu845o"/><path fill="url(#svgIDaT)" class="yw6lu845o"/><path fill="url(#svgIDaU)" class="yw6lu845o"/><path fill="url(#svgIDaV)" class="yw6lu845o"/><path fill="url(#svgIDaW)" class="yw6lu845o"/><path fill="url(#svgIDaX)" class="yw6lu845o"/><path fill="url(#svgIDaY)" class="yw6lu845o"/><path fill="url(#svgIDaZ)" class="yw6lu845o"/><path fill="url(#svgIDba)" class="yw6lu845o"/></g><g filter="url(#svgIDbb)"><path fill="url(#svgIDbc)" class="rk548sxih"/><path fill="url(#svgIDbd)" class="rk548sxih"/></g><g filter="url(#svgIDbe)"><path fill="url(#svgIDbf)" class="p2mycvwjb"/></g><g filter="url(#svgIDbg)"><path class="e5b07q_tj"/></g><path fill="url(#svgIDbh)" class="g1-cakgjb"/><path fill="url(#svgIDbi)" class="g1-cakgjb"/><path fill="url(#svgIDbj)" class="arrvtbcvm"/><path fill="url(#svgIDbk)" class="arrvtbcvm"/><circle fill="url(#svgIDbl)" class="rdymgqtsv"/><g filter="url(#svgIDbm)"><path clip-rule="evenodd" class="kkrh02mfv"/></g><circle fill="url(#svgIDbn)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDbo)"><path clip-rule="evenodd" class="ruaowacmv"/></g><g filter="url(#svgIDbp)"><path stroke="url(#svgIDbq)" class="utd98p5ur"/></g><g filter="url(#svgIDbr)"><path class="e-189exfc"/></g><path fill="url(#svgIDbs)" class="q7uwbs60e"/><path fill="url(#svgIDbt)" class="q7uwbs60e"/><path fill="url(#svgIDbu)" class="q7uwbs60e"/><path fill="url(#svgIDbv)" class="q7uwbs60e"/><path fill="url(#svgIDbw)" class="q7uwbs60e"/><path fill="url(#svgIDbx)" class="ufmf8rqul"/><g filter="url(#svgIDby)"><path class="q-xc9wbob"/></g><path fill="url(#svgIDbz)" class="yxaejacmd"/><path fill="url(#svgIDbA)" class="zndunbc5i"/><g filter="url(#svgIDbB)"><path fill="url(#svgIDbC)" class="alt-ysbep"/></g><path fill="url(#svgIDbD)" class="alt-ysbep"/><g filter="url(#svgIDbE)"><path fill="url(#svgIDbF)" class="wtgtu1b-g"/><path fill="url(#svgIDbG)" class="wtgtu1b-g"/></g><g filter="url(#svgIDbH)"><path class="kx8mzyb9o"/><path fill="url(#svgIDbI)" class="awfqzcbpn"/></g><g filter="url(#svgIDbJ)"><path class="o865-rp2f"/><path fill="url(#svgIDbK)" class="b87amo3ra"/></g><g filter="url(#svgIDbL)"><path fill="url(#svgIDbM)" class="biu945u6v"/><path fill="url(#svgIDbN)" class="biu945u6v"/><path fill="url(#svgIDbO)" class="biu945u6v"/><path fill="url(#svgIDbP)" class="biu945u6v"/><path fill="url(#svgIDbQ)" class="biu945u6v"/><path fill="url(#svgIDbR)" class="biu945u6v"/><path fill="url(#svgIDbS)" class="biu945u6v"/><path fill="url(#svgIDbT)" class="biu945u6v"/></g><path fill="url(#svgIDbU)" class="biu945u6v"/><g filter="url(#svgIDbV)"><path class="kp-yl6zgl"/></g><g filter="url(#svgIDbW)"><path class="an1nzpbht"/><path fill="url(#svgIDbX)" class="gogpt5r0t"/><path fill="url(#svgIDbY)" class="gogpt5r0t"/><path fill="url(#svgIDbZ)" class="gogpt5r0t"/><path fill="url(#svgIDca)" class="gogpt5r0t"/></g><g filter="url(#svgIDcb)"><path stroke="url(#svgIDcc)" class="yq_c117hz"/></g><path class="tao0qcb3s"/><g filter="url(#svgIDcd)"><path class="hhf6kebuo"/></g><g filter="url(#svgIDce)"><path class="osxc1zbpw"/></g><g filter="url(#svgIDcf)"><path class="tp4ii18rm"/></g><g filter="url(#svgIDcg)"><path clip-rule="evenodd" class="gph4dwfrb"/></g><path class="m322lobnf"/><path fill="url(#svgIDch)" class="hmlezuw4j"/><path class="pbli_fbie"/><g filter="url(#svgIDci)"><path class="x8ep3tv2b"/><path fill="url(#svgIDcj)" class="xl5y2z0hn"/></g><g filter="url(#svgIDck)"><path fill="url(#svgIDcl)" class="dj6-7hb_y"/></g><path class="fzkrlcbyb"/><path fill="url(#svgIDcm)" class="swq8274lr"/><path class="kj5mz8y_h"/><g filter="url(#svgIDcn)"><path fill="url(#svgIDco)" class="wsf9mcbkr"/></g><g filter="url(#svgIDcp)" transform="rotate(-27.914 20.843 7.322)"><ellipse class="q551x4bka"/><ellipse fill="url(#svgIDcq)" class="nrjp926-o"/></g><g filter="url(#svgIDcr)"><path class="lvqzn2bnw"/><path fill="url(#svgIDcs)" class="l41-bmbwo"/><path fill="url(#svgIDct)" class="l41-bmbwo"/></g><g filter="url(#svgIDcu)"><path class="izilbdb_e"/><path fill="url(#svgIDcv)" class="th1ove_oq"/><path fill="url(#svgIDcw)" class="th1ove_oq"/></g><g filter="url(#svgIDcx)"><path class="ykgij1bvx"/></g><g filter="url(#svgIDcy)"><path class="e4l_esb9l"/></g><g filter="url(#svgIDcz)"><path class="j_f9hxb4x"/></g><g filter="url(#svgIDcA)"><path fill="url(#svgIDcB)" class="s22h3gbmb"/></g><defs><radialGradient id="svgIDc" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 .551 8.17) scale(1.97957 2.47289)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="svgIDd" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 2.409 5.554) scale(1.49684 1.96674)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="svgIDe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.478 5.53) scale(.92644 .71137)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.563 5.374) scale(1.06539 .75048)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(.59163 1.12553 -1.5624 .82126 7.338 4.151)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="matrix(-.62044 .62049 -.86712 -.86706 11.364 5.046)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-.7936 .23088 -.48148 -1.655 12.086 7.254)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21207 .30304 -.38602 -1.544 11.826 8.725)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="svgIDk" cx="0" cy="0" r="1" gradientTransform="matrix(-.38932 -1.1408 .90231 -.30793 10.89 6.206)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="matrix(.64736 .0679 -.11003 1.04892 6.21 7.238)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="svgIDm" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 8.307 -.937) scale(1.6348 .59003)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDu" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDz" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="cgv9fqb9i"/><stop offset="1" class="e21rj57oo"/></radialGradient><radialGradient id="svgIDC" cx="0" cy="0" r="1" gradientTransform="rotate(-171.004 7.889 6.01) scale(4.74588 6.74344)" gradientUnits="userSpaceOnUse"><stop class="uee_89odc"/><stop offset="1" class="g491cdewz"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(-.31576 -4.42702 2.3084 -.16465 9.067 20.29)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09808 -2.34457 .73972 -.34645 9.856 19.727)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="rotate(140.925 3.46 7.595) scale(2.85608 2.68117)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(.40121 -2.33727 .9853 .16914 7.85 19.552)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 1.92188 -2.37114 .96387 8.413 9.883)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="iohdz6y9b"/><stop offset=".902" class="vvah7_hxr"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(-.28139 -.51803 .587 -.31885 6.668 8.313)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="matrix(1.07142 -.48701 .59462 1.30815 10.592 7.809)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="svgIDS" cx="0" cy="0" r="1" gradientTransform="matrix(.51948 0 0 .22366 10.982 6.886)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="svgIDU" cx="0" cy="0" r="1" gradientTransform="matrix(.64994 -.04835 .0378 .50807 10.744 7.669)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="rotate(-180 3.437 3.81) scale(.45454)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="svgIDY" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 4.231 4.8) scale(3.08278 4.12625)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="svgIDZ" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 4.035 4.898) scale(1.02535 .71404)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="svgIDaa" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 10.996 -.374) scale(1.77969 2.2581)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(-.553 3.1738 -3.96721 -.69123 9.294 7.21)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="svgIDac" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 4.421 4.535) scale(3.02925 5.21544)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49535 .60793 0 9.844 7.209)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="svgIDae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56497 .6475 0 7.96 7.11)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="svgIDaf" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 2.345 6.725) scale(1.43857 1.1511)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="svgIDag" cx="0" cy="0" r="1" gradientTransform="matrix(-.55325 0 0 -2.7745 11.047 7.849)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="svgIDaj" cx="0" cy="0" r="1" gradientTransform="matrix(-.19609 -.87984 .27116 -.06043 9.19 8.162)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="svgIDam" cx="0" cy="0" r="1" gradientTransform="matrix(-.3355 0 0 -.0938 9.088 8.253)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="svgIDat" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 9.793 7.363)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDav" cx="0" cy="0" r="1" gradientTransform="matrix(-.09983 -.12864 .17711 -.13744 9.695 7.4)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDay" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 7.914 7.363)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="matrix(-.00333 -.21266 .25564 -.004 7.79 7.457)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaE" cx="0" cy="0" r="1" gradientTransform="matrix(.54324 -1.18608 .60677 .2779 6.418 6.45)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="svgIDaF" cx="0" cy="0" r="1" gradientTransform="matrix(.49481 -.85025 .45647 .26565 7.153 6.028)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="svgIDaH" cx="0" cy="0" r="1" gradientTransform="matrix(-.9091 1.8903 -3.09054 -1.48631 9.676 4.209)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="matrix(-.09054 .58851 -1.26615 -.1948 8.944 4.368)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="svgIDaQ" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 7.074 13.887) scale(1.97957 2.47289)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 8.932 7.548) scale(1.49684 1.96674)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 8 8.753) scale(.92644 .71137)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 8.086 9.032) scale(1.06539 .75048)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(.59163 1.12553 -1.5624 .82126 20.384 4.151)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="matrix(-.62044 .62049 -.86712 -.86706 24.41 5.046)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="matrix(-.7936 .23088 -.48148 -1.655 25.131 7.254)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21207 .30304 -.38602 -1.544 24.872 8.725)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="matrix(-.38932 -1.1408 .90231 -.30793 23.936 6.206)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(.64736 .0679 -.11003 1.04892 19.255 7.238)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="matrix(-.36074 -1.5945 .57549 -.1302 24.1 6.958)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.248 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="cgv9fqb9i"/><stop offset="1" class="e21rj57oo"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.6875 -.7421 1.05444 -6.6605 27.786 13.18)" gradientUnits="userSpaceOnUse"><stop class="uee_89odc"/><stop offset="1" class="g491cdewz"/></radialGradient><radialGradient id="svgIDbs" cx="0" cy="0" r="1" gradientTransform="matrix(-.31576 -4.42702 2.3084 -.16465 22.113 20.29)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09808 -2.34457 .73972 -.34645 22.9 19.727)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="rotate(140.925 9.982 9.91) scale(2.85608 2.68117)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(.40121 -2.33727 .9853 .16914 20.895 19.552)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 1.92188 -2.37114 .96387 21.458 9.883)" gradientUnits="userSpaceOnUse"><stop offset=".028" class="iohdz6y9b"/><stop offset=".902" class="vvah7_hxr"/></radialGradient><radialGradient id="svgIDbD" cx="0" cy="0" r="1" gradientTransform="matrix(-.28139 -.51803 .587 -.31885 19.713 8.313)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="matrix(1.07142 -.48701 .59462 1.30815 23.638 7.809)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(.51948 0 0 .22366 24.027 6.886)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="matrix(.64994 -.04835 .0378 .50807 23.79 7.669)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="svgIDbK" cx="0" cy="0" r="1" gradientTransform="rotate(-180 9.96 3.81) scale(.45454)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 10.754 6.232) scale(3.08278 4.12625)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="svgIDbN" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 10.558 6.27) scale(1.02535 .71404)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="svgIDbO" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 17.518 -9.38) scale(1.77969 2.2581)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(-.553 3.1738 -3.96721 -.69123 22.34 7.21)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="svgIDbQ" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 10.944 5.169) scale(3.02925 5.21544)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="svgIDbR" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49535 .60793 0 22.89 7.209)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="svgIDbS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56497 .6475 0 21.005 7.11)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="svgIDbT" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 8.868 11.722) scale(1.43857 1.1511)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="svgIDbU" cx="0" cy="0" r="1" gradientTransform="matrix(-.55325 0 0 -2.7745 24.092 7.849)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="svgIDbX" cx="0" cy="0" r="1" gradientTransform="matrix(-.19609 -.87984 .27116 -.06043 22.237 8.162)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="svgIDca" cx="0" cy="0" r="1" gradientTransform="matrix(-.3355 0 0 -.0938 22.133 8.253)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="svgIDch" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 22.838 7.363)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDcj" cx="0" cy="0" r="1" gradientTransform="matrix(-.09983 -.12864 .17711 -.13744 22.74 7.4)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDcm" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34923 -.5555 0 20.96 7.363)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDcq" cx="0" cy="0" r="1" gradientTransform="matrix(-.00333 -.21267 .25564 -.004 20.836 7.457)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDcs" cx="0" cy="0" r="1" gradientTransform="matrix(.54324 -1.18608 .60677 .2779 19.464 6.45)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="svgIDct" cx="0" cy="0" r="1" gradientTransform="matrix(.49481 -.85025 .45647 .26565 20.199 6.028)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="svgIDcv" cx="0" cy="0" r="1" gradientTransform="matrix(-.9091 1.8903 -3.09054 -1.48631 22.721 4.209)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="svgIDcw" cx="0" cy="0" r="1" gradientTransform="matrix(-.09054 .58851 -1.26615 -.1948 21.99 4.368)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="svgIDa" width="6.715" height="7.215" x="5.621" y="3.199" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDn" width="3.254" height="11.85" x="5.815" y="18.183" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.505882 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDq" width="7.308" height="11.757" x="9.296" y="18.276" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.388235 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDs" width="5.615" height="11.172" x="10.355" y="17.769" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".25"/></filter><filter id="svgIDy" width="5.896" height="7.109" x="2.601" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.388235 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.337255 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDA" width="5.996" height="7.194" x="9.267" y="10.072" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.396078 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.32549 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDB" width="5.168" height="4.054" x="9.733" y="10.41" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".2"/></filter><filter id="svgIDD" width="8.805" height="9.609" x="4.665" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDK" width="2.793" height="3.034" x="3.321" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".2"/></filter><filter id="svgIDN" width="1.535" height="1.385" x="6.144" y="6.927" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDQ" width="1.385" height="1.635" x="10.239" y="6.677" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDT" width="1.925" height="1.925" x="9.969" y="6.658" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".25"/></filter><filter id="svgIDV" width="1.625" height="1.625" x="6.033" y="6.808" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".175"/></filter><filter id="svgIDX" width="4.387" height="4.782" x="6.66" y="5.508" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDah" width="1.808" height="2.154" x="7.88" y="6.903" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".25"/></filter><filter id="svgIDai" width="1.008" height="1.354" x="8.35" y="7.243" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDan" width="1.822" height=".885" x="7.943" y="8.517" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDap" width="1.406" height=".553" x="9.145" y="7.016" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDaq" width="1.406" height=".553" x="7.156" y="7.016" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDar" width="1.17" height=".584" x="7.214" y="6.289" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDas" width="1.17" height=".584" x="9.546" y="6.289" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDau" width=".453" height=".414" x="9.42" y="7.117" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDaw" width=".611" height=".621" x="9.724" y="7.092" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".1"/></filter><filter id="svgIDaz" width=".652" height=".676" x="7.812" y="7.065" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".1"/></filter><filter id="svgIDaB" width=".507" height=".417" x="7.544" y="7.113" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDaD" width="2.169" height="2.298" x="6.091" y="4.604" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feGaussianBlur result="effect2_foregroundBlur_4002_713" stdDeviation=".1"/></filter><filter id="svgIDaG" width="3.987" height="2.624" x="7.318" y="4.101" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feGaussianBlur result="effect2_foregroundBlur_4002_713" stdDeviation=".075"/></filter><filter id="svgIDaJ" width="3.621" height="2.306" x="8.176" y="4.596" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".375"/></filter><filter id="svgIDaK" width="1.73" height="2.911" x="6.683" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDaL" width="1.73" height="2.911" x="9.394" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDaM" width="4.792" height="2.36" x="6.658" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDaO" width="6.715" height="7.215" x="18.667" y="3.199" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDbb" width="3.254" height="11.85" x="18.86" y="18.183" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.505882 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDbe" width="7.308" height="11.757" x="22.341" y="18.276" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.388235 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDbg" width="5.615" height="11.172" x="23.401" y="17.769" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".25"/></filter><filter id="svgIDbm" width="5.896" height="7.109" x="15.646" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.388235 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.337255 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDbo" width="5.996" height="7.194" x="22.312" y="10.072" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.396078 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.32549 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDbp" width="5.168" height="4.054" x="22.778" y="10.41" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".2"/></filter><filter id="svgIDbr" width="8.805" height="9.609" x="17.71" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDby" width="2.793" height="3.034" x="16.366" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".2"/></filter><filter id="svgIDbB" width="1.535" height="1.385" x="19.19" y="6.927" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDbE" width="1.385" height="1.635" x="23.284" y="6.677" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDbH" width="1.925" height="1.925" x="23.015" y="6.658" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".25"/></filter><filter id="svgIDbJ" width="1.625" height="1.625" x="19.078" y="6.808" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".175"/></filter><filter id="svgIDbL" width="4.387" height="4.782" x="19.706" y="5.508" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDbV" width="1.808" height="2.154" x="20.925" y="6.903" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".25"/></filter><filter id="svgIDbW" width="1.008" height="1.354" x="21.395" y="7.243" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDcb" width="1.822" height=".885" x="20.988" y="8.517" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDcd" width="1.406" height=".553" x="22.19" y="7.016" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDce" width="1.406" height=".553" x="20.201" y="7.016" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDcf" width="1.17" height=".584" x="20.26" y="6.289" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDcg" width="1.17" height=".584" x="22.591" y="6.289" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/></filter><filter id="svgIDci" width=".453" height=".414" x="22.465" y="7.117" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDck" width=".611" height=".621" x="22.77" y="7.092" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".1"/></filter><filter id="svgIDcn" width=".652" height=".676" x="20.857" y="7.065" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".1"/></filter><filter id="svgIDcp" width=".507" height=".417" x="20.589" y="7.113" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".05"/></filter><filter id="svgIDcr" width="2.169" height="2.298" x="19.136" y="4.604" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feGaussianBlur result="effect2_foregroundBlur_4002_713" stdDeviation=".1"/></filter><filter id="svgIDcu" width="3.987" height="2.624" x="20.363" y="4.101" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feGaussianBlur result="effect2_foregroundBlur_4002_713" stdDeviation=".075"/></filter><filter id="svgIDcx" width="3.621" height="2.306" x="21.221" y="4.596" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_713" stdDeviation=".375"/></filter><filter id="svgIDcy" width="1.73" height="2.911" x="19.728" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDcz" width="1.73" height="2.911" x="22.439" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><filter id="svgIDcA" width="4.792" height="2.36" x="19.703" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_713" result="effect2_innerShadow_4002_713"/></filter><linearGradient id="svgIDb" x1="10.874" x2="8.233" y1="4.627" y2="9.259" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="svgIDo" x1="5.915" x2="7.918" y1="22.89" y2="23.027" gradientUnits="userSpaceOnUse"><stop class="yf8e95b_r"/><stop offset="1" class="w9jofw35x"/></linearGradient><linearGradient id="svgIDp" x1="5.801" x2="6.377" y1="23.722" y2="23.722" gradientUnits="userSpaceOnUse"><stop class="rtm0-3azz"/><stop offset="1" class="ds145h5rv"/></linearGradient><linearGradient id="svgIDr" x1="11.646" x2="14.117" y1="23.184" y2="22.269" gradientUnits="userSpaceOnUse"><stop class="itvmy4ksx"/><stop offset="1" class="eak9q3b3v"/></linearGradient><linearGradient id="svgIDx" x1="4.972" x2="5.831" y1="16.711" y2="17.376" gradientUnits="userSpaceOnUse"><stop class="c35nx7qyj"/><stop offset="1" class="xh8imlblg"/></linearGradient><linearGradient id="svgIDF" x1="5.752" x2="6.341" y1="18.036" y2="18.022" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDL" x1="5.735" x2="11.87" y1="9.695" y2="9.695" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDM" x1="5.721" x2="11.883" y1="9.682" y2="9.682" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDO" x1="6.144" x2="6.944" y1="7.658" y2="7.658" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="svgIDak" x1="8.45" x2="8.854" y1="8.193" y2="8.193" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="svgIDal" x1="8.854" x2="8.854" y1="8.498" y2="8.228" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="svgIDao" x1="8.396" x2="8.594" y1="9.144" y2="8.837" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="svgIDax" x1="10.128" x2="9.993" y1="7.386" y2="7.469" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDaA" x1="8.235" x2="8.099" y1="7.386" y2="7.469" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDaN" x1="10.697" x2="7.198" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaP" x1="23.919" x2="21.278" y1="4.627" y2="9.259" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="svgIDbc" x1="18.96" x2="20.963" y1="22.89" y2="23.027" gradientUnits="userSpaceOnUse"><stop class="yf8e95b_r"/><stop offset="1" class="w9jofw35x"/></linearGradient><linearGradient id="svgIDbd" x1="18.846" x2="19.422" y1="23.722" y2="23.722" gradientUnits="userSpaceOnUse"><stop class="rtm0-3azz"/><stop offset="1" class="ds145h5rv"/></linearGradient><linearGradient id="svgIDbf" x1="24.691" x2="27.163" y1="23.184" y2="22.269" gradientUnits="userSpaceOnUse"><stop class="itvmy4ksx"/><stop offset="1" class="eak9q3b3v"/></linearGradient><linearGradient id="svgIDbl" x1="18.017" x2="18.876" y1="16.711" y2="17.376" gradientUnits="userSpaceOnUse"><stop class="c35nx7qyj"/><stop offset="1" class="xh8imlblg"/></linearGradient><linearGradient id="svgIDbt" x1="18.797" x2="19.386" y1="18.036" y2="18.022" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbz" x1="18.78" x2="24.915" y1="9.695" y2="9.695" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDbA" x1="18.766" x2="24.928" y1="9.682" y2="9.682" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="svgIDbC" x1="19.19" x2="19.989" y1="7.658" y2="7.658" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="svgIDbY" x1="21.495" x2="21.899" y1="8.193" y2="8.193" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="svgIDbZ" x1="21.899" x2="21.899" y1="8.498" y2="8.228" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="svgIDcc" x1="21.441" x2="21.639" y1="9.144" y2="8.837" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="svgIDcl" x1="23.173" x2="23.038" y1="7.386" y2="7.469" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDco" x1="21.28" x2="21.145" y1="7.386" y2="7.469" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDcB" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-bunny-ears-medium" /></template>
<style>
.a09-_rbjr {
  d: path("M9.794 7.158a.384.384 0 0 1 .37.485h-.742a.386.386 0 0 1 .372-.485Z");
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ah7lx2b2u {
  d: path("M9.766 7.239c.027.037-.03.081-.095.13c-.065.048-.113.083-.14.046c-.028-.037.002-.106.067-.154c.065-.049.14-.059.168-.022Z");
}

.alt-ysbep {
  d: path("M19.882 8.313a.693.693 0 1 0 0-1.386a.693.693 0 0 0 0 1.386Z");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.an1nzpbht {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m21.734 7.465l-.229.731a.232.232 0 0 0 .225.302h.338c.159 0 .27-.153.224-.302l-.229-.731c-.049-.162-.277-.162-.329 0Z");
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.arrvtbcvm {
  d: path("M28.675 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.awfqzcbpn {
  d: path("M23.977 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b5t1_sbqs {
  d: path("M10.136 7.491a.362.362 0 0 0-.1-.199l-.112.123l.05.098l.162-.022Z");
}

.b87amo3ra {
  d: path("M19.89 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.bf_q98buf {
  d: path("m8.689 7.465l-.229.731a.232.232 0 0 0 .224.302h.339c.159 0 .27-.153.224-.302l-.229-.731c-.049-.162-.278-.162-.329 0Z");
}

.biu945u6v {
  d: path("M19.71 7.077h.005l-.005-.115l-.004-.131c.009-.409.247-.567.348-.62a.306.306 0 0 0 .023-.008l.022-.01a.992.992 0 0 0 .512-.53l.035-.084a.114.114 0 0 1 .199-.022c.309.452.825.72 1.372.72h1.386c.078 0 .466.038.49.574l-.052 1.322c-.053 1.207-.995 2.017-2.145 2.017s-2.092-.81-2.145-2.017l-.042-1.096Z");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bt9it9b5j {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M6.672 5.042c.243-.258.704-.258.917-.22l.17.556c-.109-.017-.127 0-.209.079c-.059.47-.592.756-1.242.946c-.064-.643.047-1.025.364-1.36Z");
}

.bu8cbcb5t {
  d: path("M9.319 9.992c.23.043.451.114.659.209l-.926 1.57a.25.25 0 0 1-.435.004l-.98-1.593c.17-.074.348-.132.532-.173l1.15-.017Z");
}

.c35nx7qyj {
  stop-color: var(--svg-color--8c5a5e, #8C5A5E);
}

.c9qmapbez {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.854 8.873c-.224 0-.435-.054-.612-.148c-.06-.032-.126.038-.088.094a.832.832 0 0 0 1.399 0c.038-.058-.027-.126-.087-.094a1.296 1.296 0 0 1-.612.148Z");
}

.ce22v4b6v {
  d: path("M6.672 5.042c.243-.258.704-.258.917-.22l.17.556c-.109-.017-.127 0-.209.079c-.059.47-.592.756-1.242.946c-.064-.643.047-1.025.364-1.36Z");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.cgv9fqb9i {
  stop-color: var(--svg-color--a67779, #A67779);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d1e4u8m5p {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .206-.12.166-.234l-.563-1.607Z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dgz-pcbjo {
  d: path("M10.931 8.313a.693.693 0 1 0 0-1.386a.693.693 0 0 0 0 1.386Z");
}

.dhdllmbnv {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
}

.dj6-7hb_y {
  d: path("M23.181 7.491a.362.362 0 0 0-.1-.199l-.111.123l.05.098l.161-.022Z");
}

.do-ctebya {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m7.391 6.855l-.002.001a.115.115 0 0 1-.118-.198l.002-.001l.004-.003l.014-.007c.011-.007.028-.015.05-.026c.042-.02.102-.046.176-.07c.146-.046.35-.085.572-.046a.115.115 0 1 1-.04.227a.977.977 0 0 0-.462.04a1.18 1.18 0 0 0-.186.078l-.01.005Z");
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.ds145h5rv {
  stop-color: var(--svg-color--9e7669, #9E7669);
  stop-opacity: 0;
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e-189exfc {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M18.96 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.566Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e21rj57oo {
  stop-color: var(--svg-color--93547f, #93547F);
}

.e4l_esb9l {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.981 3.273c.222.71.522 1.166.645 1.305l.633-.242c-.013-.183-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.e5b07q_tj {
  fill: var(--svg-color--c59b8a, #C59B8A);
  d: path("m23.9 18.571l.824-.302l3.792 10.172h-.758L23.9 18.57Z");
}

.eak9q3b3v {
  stop-color: var(--svg-color--c09881, #C09881);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.ev0kozb_a {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.273c.222.71.522 1.166.644 1.305l.633-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.f2kz_-b-b {
  d: path("M6.845 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.fz06w4zyp {
  fill: var(--svg-color--000, #000);
  d: path("M8.134 7.542a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.196.321h.39a.218.218 0 0 0 .026-.101Z");
}

.fzkrlcbyb {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.87 7.04a.601.601 0 0 0-.583.456a.118.118 0 0 0 .115.147h.96a.1.1 0 0 0 .098-.117a.603.603 0 0 0-.59-.485Z");
}

.g1-cakgjb {
  d: path("m20.928 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g491cdewz {
  stop-color: var(--svg-color--b68e7e, #B68E7E);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g8jg3w7ba {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M5.915 12.814a2.872 2.872 0 0 1 5.744 0v3.804a2 2 0 0 0 .117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.13-1.14v-5.566Z");
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gdjp32joa {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m10.46 6.658l-.06.099l.06-.099a.116.116 0 0 1-.119.198l-.002-.001l-.01-.005a1.179 1.179 0 0 0-.187-.078a.977.977 0 0 0-.46-.04a.115.115 0 1 1-.04-.227c.22-.04.425 0 .571.047a1.417 1.417 0 0 1 .24.102l.005.003h.001v.001Z");
}

.gogpt5r0t {
  d: path("m21.734 7.465l-.229.731a.232.232 0 0 0 .225.302h.338c.159 0 .27-.153.224-.302l-.229-.731c-.049-.162-.277-.162-.329 0Z");
}

.gph4dwfrb {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m23.505 6.658l-.06.099l.06-.099a.115.115 0 0 1-.118.198l-.003-.001l-.009-.005a1.185 1.185 0 0 0-.187-.078a.977.977 0 0 0-.461-.04a.115.115 0 0 1-.04-.227c.22-.04.425 0 .572.047a1.409 1.409 0 0 1 .226.095l.014.007l.004.003h.001l.001.001Z");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hhf6kebuo {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M22.39 7.375c.115-.2.288-.36.662-.36a.71.71 0 0 1 .462.16c.116.093.1.212.01.257l-.239.137c-.28-.09-.59-.103-.895-.194Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hmlezuw4j {
  d: path("M22.84 7.158a.384.384 0 0 1 .37.485h-.743a.386.386 0 0 1 .372-.485Z");
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxhlt-5kf {
  d: path("M6.664 7.077h.005l-.004-.115l-.005-.131c.01-.409.247-.567.349-.62a.305.305 0 0 0 .022-.008l.022-.01a.992.992 0 0 0 .512-.53l.035-.084a.114.114 0 0 1 .2-.022c.308.452.825.72 1.372.72h1.386c.078 0 .466.038.489.574l-.051 1.322C10.943 9.38 10 10.19 8.85 10.19s-2.092-.81-2.145-2.017l-.042-1.096Z");
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i5qnlkb7r {
  d: path("M8.811 9.682h-.017c.043 0 .082 0 .124.005c-.034-.005-.072-.005-.107-.005Z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.ih9jpspul {
  d: path("m12.124 18.276l-2.828.954l4.334 9.27a2.64 2.64 0 0 0 2.397 1.533c.122 0 .207-.12.167-.234l-4.07-11.523Z");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iohdz6y9b {
  stop-color: var(--svg-color--7b4445, #7B4445);
}

.itvmy4ksx {
  stop-color: var(--svg-color--9c6b6d, #9C6B6D);
}

.iw4kkgb9v {
  fill: var(--svg-color--ac8079, #AC8079);
  fill-rule: evenodd;
  d: path("M9.369 10.716a.8.8 0 0 0 .307 1.088l3.527 1.978a.2.2 0 0 1 .035.325l-1.9 1.763a.8.8 0 0 0 1.068 1.191l1.973-1.72c.93-.821.856-2.149-.347-2.918l-3.907-2.12c-.385-.216-.54.027-.756.413Z");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.izilbdb_e {
  fill: var(--svg-color--553836, #553836);
  d: path("M21.64 4.267c-.488-.108-.926.378-.977.559c.453 1.526 1.599 1.442 2.73 1.317c.677-.076.75.233.808.382c0-1.693-1.44-2.01-2.55-2.256l-.012-.002Z");
}

.j_f9hxb4x {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.817 3.273c-.222.71-.523 1.166-.645 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29Z");
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jqr179a-y {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M8.854 8.873c-.224 0-.435-.054-.612-.148c-.06-.032-.126.038-.088.094a.832.832 0 0 0 1.399 0c.038-.058-.027-.126-.087-.094a1.296 1.296 0 0 1-.612.148Z");
}

.ju_febl2z {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M8.362 7.375c-.114-.2-.288-.36-.662-.36a.713.713 0 0 0-.461.16c-.116.093-.1.212-.01.257l.238.137c.281-.09.591-.103.895-.194Z");
}

.ju0xvk2bt {
  d: path("M8.594 4.267c-.487-.108-.925.378-.976.559c.453 1.526 1.599 1.442 2.73 1.317c.676-.076.75.233.807.382c0-1.693-1.44-2.01-2.549-2.256l-.012-.002Z");
}

.juat2ccab {
  d: path("M6.837 8.313a.693.693 0 1 0 0-1.386a.693.693 0 0 0 0 1.386Z");
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k2oy8rbvq {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M6.845 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kj5mz8y_h {
  fill: var(--svg-color--000, #000);
  d: path("M21.179 7.542a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.196.321h.39a.218.218 0 0 0 .026-.101Z");
}

.kkrh02mfv {
  fill: var(--svg-color--9c7765, #9C7765);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.kl5t8b-wc {
  d: path("M11.946 8.227a1.411 1.411 0 0 0 .024-1.176h.002a1.372 1.372 0 0 0-.12-.221l-.001-.001a1.394 1.394 0 0 1-.227-.763v-.004a1.42 1.42 0 0 0-1.42-1.42a.232.232 0 0 1-.196-.1a1.423 1.423 0 0 0-2.309 0a.243.243 0 0 1-.196.1h-.037a1.42 1.42 0 0 0-1.383 1.42v.004c0 .27-.078.536-.227.763v.001a1.42 1.42 0 0 0-.095 1.397c.03.06.03.135 0 .196a1.383 1.383 0 0 0 1.246 1.99H10.7a1.383 1.383 0 0 0 1.246-1.99a.221.221 0 0 1 0-.196ZM6.67 7.077h-.005L7.18 8.09c.053 1.207.524 0 1.673 0c1.15 0 1.652 1.343 1.705.137l.489-1.376c-.023-.536-.412-.574-.49-.574H9.173a1.663 1.663 0 0 1-1.373-.72a.114.114 0 0 0-.199.022l-.035.083a.992.992 0 0 1-.534.54l-.022.01c-.102.052-.34.21-.349.619l.005.131l.004.115Z");
}

.kp-yl6zgl {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m21.73 7.524l-.294.732a.232.232 0 0 0 .224.301h.338a.233.233 0 0 0 .224-.301l-.229-.732c-.048-.162-.212-.162-.263 0Z");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.kr_eiac3t {
  r: 0.766px;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.kx8mzyb9o {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M23.977 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.l41-bmbwo {
  d: path("M19.717 5.042c.244-.258.705-.258.917-.22l.17.556c-.108-.017-.127 0-.208.079c-.06.47-.593.756-1.243.946c-.064-.643.047-1.025.364-1.36Z");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvqzn2bnw {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M19.717 5.042c.244-.258.705-.258.917-.22l.17.556c-.108-.017-.127 0-.208.079c-.06.47-.593.756-1.243.946c-.064-.643.047-1.025.364-1.36Z");
}

.m13u431kg {
  d: path("m5.915 18.183l3.154 1.125l-1.22 9.141a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V18.183Z");
}

.m2_nb2bed {
  d: path("M7.914 7.158a.384.384 0 0 0-.37.485h.742a.387.387 0 0 0-.372-.485Z");
}

.m322lobnf {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.928 7.04c.281 0 .519.195.583.457a.118.118 0 0 1-.115.146h-.96a.1.1 0 0 1-.098-.117a.602.602 0 0 1 .59-.485Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mddk40bcp {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.273c-.222.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mlz1_3shy {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.883 7.04c.28 0 .518.195.583.457a.118.118 0 0 1-.115.146h-.96a.1.1 0 0 1-.098-.117a.602.602 0 0 1 .59-.485Z");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.nrjp926-o {
  cx: 20.843px;
  cy: 7.322px;
  rx: 0.168px;
  ry: 0.085px;
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o7s685biz {
  d: path("M8.953 9.682Z");
}

.o865-rp2f {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M19.89 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.osxc1zbpw {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M21.407 7.375c-.114-.2-.288-.36-.661-.36a.714.714 0 0 0-.462.16c-.116.093-.1.212-.01.257l.239.137c.28-.09.59-.103.894-.194Z");
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p_9dvab3h {
  d: path("M8.264 7.497c0-.124-.1-.207-.128-.232l-.124.12l.076.155l.176-.043Z");
}

.p1op2_pku {
  d: path("M10.932 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.p2mycvwjb {
  d: path("m25.169 18.276l-2.828.954l4.334 9.27a2.64 2.64 0 0 0 2.398 1.533c.121 0 .206-.12.166-.234l-4.07-11.523Z");
}

.pbli_fbie {
  fill: var(--svg-color--000, #000);
  d: path("M22.619 7.542a.22.22 0 0 1 .22-.22a.22.22 0 0 1 .196.321h-.39a.199.199 0 0 1-.026-.101Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp409vf4q {
  fill: var(--svg-color--c59b8a, #C59B8A);
  d: path("m10.855 18.571l.823-.302L15.47 28.44h-.758l-3.857-9.87Z");
}

.q-xc9wbob {
  stroke: var(--svg-color--b08b7e, #B08B7E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.986 13.917c-.089.073-.194.29.093.57a70.98 70.98 0 0 0 1.555 1.415");
}

.q551x4bka {
  cx: 20.843px;
  cy: 7.322px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.q7uwbs60e {
  d: path("M18.96 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.129-1.14v-5.566Z");
}

.qe8xsfyen {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m9.89 5.82l-.614.113a.296.296 0 1 1-.054-.587h1.008c.596 0 .793.6.817.806A1.355 1.355 0 0 0 9.89 5.82Z");
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r5sk2m5_h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.766 7.239c.027.037-.03.081-.095.13c-.065.048-.113.083-.14.046c-.028-.037.002-.106.067-.154c.065-.049.14-.059.168-.022Z");
}

.rdymgqtsv {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
}

.rk548sxih {
  d: path("m18.96 18.183l3.154 1.125l-1.22 9.141a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V18.183Z");
}

.rn6o83bbv {
  d: path("M5.915 12.814a2.872 2.872 0 0 1 5.744 0v3.804a2 2 0 0 0 .117.676l.444 1.235l-2.758 1.023l-.078-.158a.175.175 0 0 0-.33.054l-.01.072l-3.13-1.14v-5.566Z");
}

.rtm0-3azz {
  stop-color: var(--svg-color--9e7669, #9E7669);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.ruaowacmv {
  fill: var(--svg-color--ac8079, #AC8079);
  fill-rule: evenodd;
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.191l1.973-1.72c.93-.821.856-2.149-.347-2.918l-3.907-2.12c-.385-.216-.54.027-.756.413Z");
}

.s22h3gbmb {
  d: path("M24.093 5.75c.019.097-.101.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.sbcwsbc2z {
  stroke: var(--svg-color--b08b7e, #B08B7E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.917c-.088.073-.193.29.094.57a70.94 70.94 0 0 0 1.555 1.415");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.swq8274lr {
  d: path("M20.959 7.158a.384.384 0 0 0-.37.485h.742a.387.387 0 0 0-.372-.485Z");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tao0qcb3s {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M21.899 8.873c-.224 0-.435-.054-.612-.148c-.06-.032-.126.038-.087.094a.832.832 0 0 0 1.398 0c.038-.058-.027-.126-.087-.094a1.297 1.297 0 0 1-.612.148Z");
}

.th1ove_oq {
  d: path("M21.64 4.267c-.488-.108-.926.378-.977.559c.453 1.526 1.599 1.442 2.73 1.317c.677-.076.75.233.808.382c0-1.693-1.44-2.01-2.55-2.256l-.012-.002Z");
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tp4ii18rm {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m20.437 6.855l-.002.001a.116.116 0 0 1-.119-.198l.002-.001l.004-.003l.014-.007l.05-.026c.042-.02.103-.046.176-.07c.147-.046.351-.085.572-.046a.115.115 0 1 1-.04.227a.978.978 0 0 0-.461.04a1.185 1.185 0 0 0-.187.078l-.01.005Z");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u395am2di {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M9.345 7.375c.115-.2.288-.36.662-.36a.71.71 0 0 1 .462.16c.116.093.1.212.01.257l-.239.137c-.28-.09-.59-.103-.895-.194Z");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ubd-76htt {
  d: path("M11.048 5.75c.018.097-.102.145-.167.071c-.453-.513-1.132-1.01-2.023-1.01c-.838 0-1.553.532-2.033 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.uee_89odc {
  stop-color: var(--svg-color--b68e7e, #B68E7E);
}

.ufmf8rqul {
  d: path("M22.364 9.992c.23.043.451.114.66.209l-.927 1.57a.25.25 0 0 1-.435.004l-.979-1.593c.17-.074.347-.132.531-.173l1.15-.017Z");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.utd98p5ur {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m23.303 10.935l3.55 2.002c.193.1.578.44.569 1.002");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vosupht-x {
  fill: var(--svg-color--000, #000);
  d: path("M9.574 7.542a.22.22 0 0 1 .22-.22a.22.22 0 0 1 .195.321H9.6a.199.199 0 0 1-.026-.101Z");
}

.vvah7_hxr {
  stop-color: var(--svg-color--ae8474, #AE8474);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.w9jofw35x {
  stop-color: var(--svg-color--c09084, #C09084);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wsf9mcbkr {
  d: path("M21.31 7.497c0-.124-.101-.207-.129-.232l-.124.12l.077.155l.176-.043Z");
}

.wtdu8s9gc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m10.258 10.935l3.55 2.002c.193.1.578.44.568 1.002");
}

.wtgtu1b-g {
  d: path("M23.977 8.313a.693.693 0 1 0 0-1.386a.693.693 0 0 0 0 1.386Z");
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x-q4feb6o {
  cx: 7.798px;
  cy: 7.322px;
  rx: 0.168px;
  ry: 0.085px;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x8ep3tv2b {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.81 7.239c.028.037-.029.081-.094.13c-.065.048-.113.083-.14.046c-.028-.037.002-.106.067-.154c.066-.049.14-.059.168-.022Z");
}

.x8qx1chyk {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m8.689 7.465l-.229.731a.232.232 0 0 0 .224.302h.339c.159 0 .27-.153.224-.302l-.229-.731c-.049-.162-.278-.162-.329 0Z");
}

.xbx983bqi {
  d: path("m7.883 28.192l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.xh8imlblg {
  stop-color: var(--svg-color--8a4c72, #8A4C72);
}

.xl5y2z0hn {
  d: path("M22.81 7.239c.028.037-.029.081-.094.13c-.065.048-.113.083-.14.046c-.028-.037.002-.106.067-.154c.066-.049.14-.059.168-.022Z");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xtgnltbbo {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.824 7.04a.601.601 0 0 0-.583.456a.118.118 0 0 0 .115.147h.96a.1.1 0 0 0 .099-.117a.603.603 0 0 0-.59-.485Z");
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.xy4leobwb {
  cx: 7.798px;
  cy: 7.322px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.y0kpo0b3j {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M10.932 8.083a.462.462 0 1 0 0-.925a.462.462 0 0 0 0 .925Z");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y9sk--bki {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m8.685 7.524l-.295.732a.232.232 0 0 0 .225.301h.338c.159 0 .27-.153.224-.301l-.229-.732c-.049-.162-.212-.162-.263 0Z");
}

.yf8e95b_r {
  stop-color: var(--svg-color--966b64, #966B64);
}

.yfip4ewpb {
  fill: var(--svg-color--9c7765, #9C7765);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.856-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308Z");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ykgij1bvx {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m22.935 5.82l-.614.113a.296.296 0 1 1-.054-.587h1.008c.596 0 .793.6.817.806a1.354 1.354 0 0 0-1.157-.332Z");
}

.yq_c117hz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.899 8.873c-.224 0-.435-.054-.612-.148c-.06-.032-.126.038-.087.094a.832.832 0 0 0 1.398 0c.038-.058-.027-.126-.087-.094a1.297 1.297 0 0 1-.612.148Z");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yw6lu845o {
  d: path("M24.992 8.227a1.411 1.411 0 0 0 .024-1.176h.002a1.372 1.372 0 0 0-.121-.221l-.001-.001a1.395 1.395 0 0 1-.227-.763v-.004a1.42 1.42 0 0 0-1.42-1.42a.232.232 0 0 1-.196-.1a1.423 1.423 0 0 0-2.309 0a.243.243 0 0 1-.195.1h-.037a1.42 1.42 0 0 0-1.384 1.42v.004c0 .27-.078.536-.226.763l-.001.001a1.42 1.42 0 0 0-.095 1.397c.03.06.03.135 0 .196a1.383 1.383 0 0 0 1.246 1.99h3.694a1.383 1.383 0 0 0 1.246-1.99a.221.221 0 0 1 0-.196Zm-5.278-1.15h-.005l.516 1.013c.053 1.207.524 0 1.674 0s1.651 1.343 1.704.137l.49-1.376c-.024-.536-.412-.574-.49-.574h-1.386a1.663 1.663 0 0 1-1.373-.72a.113.113 0 0 0-.198.022l-.036.083a.992.992 0 0 1-.534.54l-.022.01c-.101.052-.34.21-.348.619l.004.131l.004.115Z");
}

.yxaejacmd {
  d: path("M21.998 9.682Z");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zndunbc5i {
  d: path("M21.857 9.682h-.017c.042 0 .08 0 .124.005c-.034-.005-.073-.005-.107-.005Z");
}

.zwe3oacdw {
  fill: var(--svg-color--553836, #553836);
  d: path("M8.594 4.267c-.487-.108-.925.378-.976.559c.453 1.526 1.599 1.442 2.73 1.317c.676-.076.75.233.807.382c0-1.693-1.44-2.01-2.549-2.256l-.012-.002Z");
}

</style>
