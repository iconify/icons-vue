<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ikOPUbe)"><path fill="url(#iipqRnc)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#iUsTskc)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#iQw90wc)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#ihwSwFb)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#iWlJCCe)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#ibTWjZb)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#i0eC2Oe)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#i4dwdDm)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#ioQL1gU)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#i4AEXIE)" clip-rule="evenodd" class="w7gy_9e9s"/><path fill="url(#iUnrtGd)" clip-rule="evenodd" class="w7gy_9e9s"/></g><rect fill="url(#i9lGIGd)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#ih9q0qd)"><path class="u9h3-mbda"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#idTE2Yd)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#itYc30S)" class="b1yazzwzl"/><path fill="url(#i4AzWsY)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#iAhtUrd)"><path fill="url(#ikclHuc)" class="ga-j-qbpm"/><path fill="url(#iqSctJd)" class="ga-j-qbpm"/><path fill="url(#iZVep2c)" class="ga-j-qbpm"/></g><g filter="url(#iwD54de)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#i0488Ae)" class="qexsyge6i"/><path fill="url(#iWGq1Cd)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iBSJg6c)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#iHStJHb)"><path fill="url(#i55AUOe)" class="dc-w_nb2z"/><path fill="url(#i136FHe)" class="dc-w_nb2z"/></g><g filter="url(#iMaMKwi)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#i9U6Cyd)"><path fill="url(#ikZpzfd)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="n6nx14b2o"/><path fill="url(#iUb69tc)" class="eikeckbha"/><path fill="url(#iChZRWc)" class="eikeckbha"/><path clip-rule="evenodd" class="d0rf-bclq"/><path fill="url(#iUcCxIc)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="tyifp67am"/><path fill="url(#i00icHe)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="nypbhiwdj"/><path fill="url(#iuop6Pe)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="x41u_8htb"/><path fill="url(#ikyprXc)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#itvErnc)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#ieQsmbd)"><path class="tmtee3wvy"/><path fill="url(#iQBvayU)" class="p3ru7q3ze"/></g><path fill="url(#i3EK4rb)" class="p3ru7q3ze"/><path fill="url(#io3Gp0b)" clip-rule="evenodd" class="y_4pajl7d"/><g filter="url(#iLov5Rb)"><path class="vyhwsac2j"/></g><g filter="url(#i8rz0Bt)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><g filter="url(#i2XPHfK)"><path fill="url(#i5u6EUY)" class="ij3hr1_1o"/></g><g filter="url(#i3LXUAb)"><path fill="url(#iIbJM7v)" class="r-4t27brr"/><path fill="url(#ihEprBe)" class="r-4t27brr"/></g><g filter="url(#iFSazmd)"><path class="rjj-89bwr"/><path fill="url(#iAIWz3b)" class="v18-6mbdj"/></g><g filter="url(#io4gFdb)"><path class="ct6bgla2r"/><path fill="url(#inD1TBc)" class="wn-8yz5zd"/></g><g filter="url(#iMUUBAd)"><path fill="url(#iauF7kB)" class="s0jqq-b-a"/><path fill="url(#iNdhHoc)" class="s0jqq-b-a"/><path fill="url(#imh67Mb)" class="s0jqq-b-a"/><path fill="url(#i8wWTtm)" class="s0jqq-b-a"/><path fill="url(#icIzNtd)" class="s0jqq-b-a"/><path fill="url(#iaoMMjd)" class="s0jqq-b-a"/><path fill="url(#ii7VUWc)" class="s0jqq-b-a"/><path fill="url(#izQFoxd)" class="s0jqq-b-a"/></g><path fill="url(#iBnpKze)" class="s0jqq-b-a"/><path fill="url(#ib7Ksme)" class="s0jqq-b-a"/><path fill="url(#iPWKXec)" class="s0jqq-b-a"/><g filter="url(#i9Nncab)"><path class="fr5lpnb8e"/></g><g filter="url(#it7im8c)"><path class="x2cy8lb4b"/><path fill="url(#iQTG42c)" class="rune_jfwz"/><path fill="url(#iZLOXme)" class="rune_jfwz"/><path fill="url(#iSJOGEd)" class="rune_jfwz"/><path fill="url(#iN0CIMc)" class="rune_jfwz"/></g><g filter="url(#ihLAX7b)"><path stroke="url(#ipg2vec)" class="znoi6dbpx"/></g><path class="vlzz19buw"/><g filter="url(#ipVNa2c)"><path class="gkusc7bym"/></g><g filter="url(#iGoG7Db)"><path class="ea6c45boh"/></g><g filter="url(#i0ctKMe)"><path class="ndv_tabmb"/></g><g filter="url(#i6h94sc)"><path clip-rule="evenodd" class="r5ju49bro"/></g><path class="zdghv6w0b"/><path fill="url(#iEOJi4H)" class="ym57y3k6t"/><path class="h_g495b7x"/><g filter="url(#ir8Bvde)"><path class="bizcp20wg"/><path fill="url(#iW2vb1d)" class="n9y9mzb3z"/></g><g filter="url(#iaGOyad)"><path fill="url(#iddnyCt)" class="g497ilbmf"/></g><path class="c75isoifh"/><path fill="url(#igu0flz)" class="l_m-s_sfy"/><path class="kc9o73bex"/><g filter="url(#iypDeEe)"><path fill="url(#iSOljPR)" class="l42l1fe0r"/></g><g filter="url(#irinzUb)"><ellipse transform="rotate(-27.914 11.78 5.704)" class="npc7sya5c"/><ellipse fill="url(#iIuINZW)" transform="rotate(-27.914 11.78 5.704)" class="dsp4d0frw"/></g><g filter="url(#iRdrrOz)"><path class="lqj1o1bqw"/></g><g filter="url(#ipefQxe)"><path class="kg2v313dj"/></g><g filter="url(#is7vJgb)"><path class="br9cige2t"/><path fill="url(#i92J5Dd)" class="e8luse4zg"/></g><g filter="url(#i8NzAuc)"><path class="r0-mcdcik"/><path fill="url(#iWia7de)" class="q56466b2p"/><path fill="url(#iQlts8d)" class="q56466b2p"/></g><g filter="url(#inEPYFb)"><path class="igykgyblk"/></g><g filter="url(#idwI7He)"><path clip-rule="evenodd" class="laf_gab5x"/></g><defs><radialGradient id="iUsTskc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27664 2.09016 -2.61104 -.34558 12.767 7.168)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iQw90wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32176 .8914 -1.17123 -1.73668 11.476 7.29)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ihwSwFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.59938 .78382 -.60186 -.46024 10.685 6.123)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iWlJCCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.5917 .96823 -.68203 -.4168 10.892 5.192)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ibTWjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.63012 1.19877 -1.66409 .8747 11.292 2.327)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i0eC2Oe" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 7.11 4.867)scale(.93457 1.30605)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i4dwdDm" cx="0" cy="0" r="1" gradientTransform="matrix(-.84525 .2459 -.51281 -1.7627 16.348 5.631)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ioQL1gU" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 7.593 4.589)scale(1.33068 1.69509)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i4AEXIE" cx="0" cy="0" r="1" gradientTransform="matrix(-.41465 -1.21504 .96103 -.32797 15.075 4.515)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iUnrtGd" cx="0" cy="0" r="1" gradientTransform="matrix(.68949 .07232 -.11719 1.11717 10.09 5.614)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i9lGIGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="bpjbo-5wq"/><stop offset="1" class="fpwanpawi"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="itYc30S" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="i1ugtm59q"/><stop offset="1" class="jcizzuyvv"/></radialGradient><radialGradient id="i4AzWsY" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ita7_2enr"/><stop offset="1" class="xau3og86r"/></radialGradient><radialGradient id="ikclHuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="b1kvifv3j"/><stop offset="1" class="w__bqyylv"/></radialGradient><radialGradient id="iqSctJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="iZVep2c" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="jfk78yx3r"/><stop offset="1" class="v_thlccbr"/></radialGradient><radialGradient id="i0488Ae" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="vinvwq12a"/><stop offset="1" class="aaj8m1ghv"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="i55AUOe" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uwn_p0-dn"/><stop offset="1" class="sa6pubcic"/></radialGradient><radialGradient id="ikZpzfd" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="ibqq90als"/><stop offset="1" class="enjwdpbad"/></radialGradient><radialGradient id="iUb69tc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="qudtebbqf"/><stop offset="1" class="qle5g2bis"/></radialGradient><radialGradient id="iChZRWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="ew_xbgbtk"/><stop offset=".945" class="za46tubip"/></radialGradient><radialGradient id="iUcCxIc" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="i00icHe" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="iuop6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="ikyprXc" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="itvErnc" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="o9doel8cg"/><stop offset="1" class="b5xboq-mx"/></radialGradient><radialGradient id="i3EK4rb" cx="0" cy="0" r="1" gradientTransform="rotate(106.912 4.941 9.22)scale(3.20093 4.86981)" gradientUnits="userSpaceOnUse"><stop class="env4r_bwx"/><stop offset="1" class="spg8_pgop"/></radialGradient><radialGradient id="io3Gp0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="y2teulbve"/><stop offset="1" class="rrpkz-bur"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><radialGradient id="iIbJM7v" cx="0" cy="0" r="1" gradientTransform="matrix(1.14113 -.5187 .63331 1.39328 14.758 6.223)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ihEprBe" cx="0" cy="0" r="1" gradientTransform="matrix(.60323 .33812 -.0956 .17054 15.23 5.25)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iAIWz3b" cx="0" cy="0" r="1" gradientTransform="matrix(.69223 -.0515 .04025 .54113 14.919 6.073)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="inD1TBc" cx="0" cy="0" r="1" gradientTransform="rotate(-179.884 5.398 3.01)scale(.48412)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iauF7kB" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.475 4.447)scale(3.28339 4.39477)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iNdhHoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.99958 .43985 -.3063 -.69609 13.809 6.166)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="imh67Mb" cx="0" cy="0" r="1" gradientTransform="matrix(.59103 -1.80101 2.28514 .7499 11.915 8.758)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i8wWTtm" cx="0" cy="0" r="1" gradientTransform="rotate(99.884 4.34 8.415)scale(3.43126 4.28903)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="icIzNtd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 6.549 3.952)scale(3.22638 5.55483)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iaoMMjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.52758 .6475 0 13.96 5.583)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="ii7VUWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60174 .68963 0 11.954 5.478)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="izQFoxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.39894 1.47934 -1.18371 -.31921 13.54 4.521)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iBnpKze" cx="0" cy="0" r="1" gradientTransform="matrix(-.58925 0 0 -2.95505 15.242 6.265)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="ib7Ksme" cx="0" cy="0" r="1" gradientTransform="matrix(-.36534 -.59457 .63178 -.3882 14.573 8.409)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="iPWKXec" cx="0" cy="0" r="1" gradientTransform="matrix(.8023 -.71635 .85057 .95264 11.055 8.402)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iQTG42c" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 9.277 -2.018)scale(.96009 .29589)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iN0CIMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.35733 0 0 -.0999 13.155 6.695)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iEOJi4H" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37196 -.59164 0 13.906 5.748)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iW2vb1d" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 8.318 -.487)scale(.17343 .23877)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igu0flz" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37196 -.59164 0 11.905 5.748)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iIuINZW" cx="0" cy="0" r="1" gradientTransform="matrix(-.00355 -.2265 .27227 -.00426 11.774 5.848)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i92J5Dd" cx="0" cy="0" r="1" gradientTransform="matrix(.5786 -1.26326 .64625 .296 10.312 4.775)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iWia7de" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.14 5.526)scale(2.23404 3.65253)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iQlts8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.09643 .6268 -1.34854 -.20747 13.002 2.558)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="ikOPUbe" width="7.135" height="7.635" x="9.463" y="1.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="ih9q0qd" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="idTE2Yd" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="iAhtUrd" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.341176 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="iwD54de" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="iBSJg6c" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="iHStJHb" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.286275 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="iMaMKwi" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="i9U6Cyd" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.298039 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.203922 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23227" result="effect2_innerShadow_3987_23227"/></filter><filter id="ieQsmbd" width="8.236" height="9.786" x="11.582" y="7.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.2"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.262745 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23227" result="effect2_innerShadow_3987_23227"/></filter><filter id="iLov5Rb" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".25"/></filter><filter id="i8rz0Bt" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="i2XPHfK" width="1.625" height="1.475" x="10.02" y="5.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="i3LXUAb" width="1.475" height="1.725" x="14.381" y="5.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="iFSazmd" width="1.985" height="1.985" x="14.126" y="5.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".25"/></filter><filter id="io4gFdb" width="1.485" height="1.485" x="10.024" y="5.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".125"/></filter><filter id="iMUUBAd" width="4.672" height="5.237" x="10.57" y="3.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="i9Nncab" width="1.861" height="2.23" x="11.901" y="5.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".25"/></filter><filter id="it7im8c" width="1.061" height="1.43" x="12.375" y="5.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".05"/></filter><filter id="ihLAX7b" width="1.914" height=".916" x="11.948" y="6.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".05"/></filter><filter id="ipVNa2c" width="1.484" height=".589" x="13.229" y="5.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="iGoG7Db" width="1.484" height=".589" x="11.098" y="5.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="i0ctKMe" width="1.233" height=".608" x="11.16" y="4.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="i6h94sc" width="1.233" height=".609" x="13.643" y="4.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><filter id="ir8Bvde" width=".469" height=".428" x="13.515" y="5.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".05"/></filter><filter id="iaGOyad" width=".625" height=".635" x="13.846" y="5.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".1"/></filter><filter id="iypDeEe" width=".669" height=".694" x="11.809" y="5.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".1"/></filter><filter id="irinzUb" width=".527" height=".431" x="11.517" y="5.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".05"/></filter><filter id="iRdrrOz" width="1.061" height=".473" x="13.645" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".05"/></filter><filter id="ipefQxe" width="1.061" height=".473" x="11.146" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".05"/></filter><filter id="is7vJgb" width="2.264" height="2.402" x="9.976" y="2.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/><feGaussianBlur result="effect2_foregroundBlur_3987_23227" stdDeviation=".1"/></filter><filter id="i8NzAuc" width="4.217" height="2.772" x="11.29" y="2.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/><feGaussianBlur result="effect2_foregroundBlur_3987_23227" stdDeviation=".075"/></filter><filter id="inEPYFb" width="2.759" height="1.358" x="12.733" y="3.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23227" stdDeviation=".125"/></filter><filter id="idwI7He" width="1.518" height=".691" x="11.054" y="3.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.345098 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23227"/></filter><linearGradient id="iipqRnc" x1="15.057" x2="11.937" y1="2.834" y2="8.613" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iWGq1Cd" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="d5idi46tx"/><stop offset="1" class="cf_a3cr-i"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="i136FHe" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ivbdbpjuw"/><stop offset="1" class="zovioqy4e"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iQBvayU" x1="18.384" x2="14.604" y1="15.165" y2="16.372" gradientUnits="userSpaceOnUse"><stop offset=".207" class="uov-5vb3w"/><stop offset="1" class="mzo6olgul"/></linearGradient><linearGradient id="i5u6EUY" x1="10.043" x2="10.612" y1="6.061" y2="6.061" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iZLOXme" x1="12.475" x2="12.905" y1="6.632" y2="6.632" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iSJOGEd" x1="12.905" x2="12.905" y1="6.998" y2="6.718" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="ipg2vec" x1="12.418" x2="12.629" y1="7.644" y2="7.318" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iddnyCt" x1="14.263" x2="14.119" y1="5.772" y2="5.861" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSOljPR" x1="12.246" x2="12.102" y1="5.772" y2="5.861" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-bouncing-ball-medium-dark" /></template>
<style>
.aaj8m1ghv {
  stop-color: var(--svg-color--7d4d5e, #7D4D5E);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b1kvifv3j {
  stop-color: var(--svg-color--8668c7, #8668C7);
}

.b1yazzwzl {
  d: path("m11 20.604l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.b1ysgbbus {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.469px;
  rx: 0.33px;
}

.b5xboq-mx {
  stop-color: var(--svg-color--835a58, #835A58);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bizcp20wg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.877 5.615c.029.04-.032.087-.101.139c-.07.051-.12.088-.15.049s.003-.113.073-.164s.149-.063.178-.024");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bpjbo-5wq {
  stop-color: var(--svg-color--6f423e, #6F423E);
}

.br9cige2t {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.582 3.276c.26-.275.75-.275.977-.234l.181.591a.35.35 0 0 0-.306.108c-.206.578-.912.897-1.24.984c-.068-.684.05-1.092.388-1.45");
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c75isoifh {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.81 5.404a.64.64 0 0 0-.622.486c-.02.08.041.156.123.156h1.023c.065 0 .117-.06.104-.125a.64.64 0 0 0-.628-.517");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cf_a3cr-i {
  stop-color: var(--svg-color--7e4d5f, #7E4D5F);
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

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.ct6bgla2r {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M10.766 6.514a.492.492 0 1 0 0-.985a.492.492 0 0 0 0 .985");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d0rf-bclq {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.d5idi46tx {
  stop-color: var(--svg-color--7e4d5f, #7E4D5F);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dsp4d0frw {
  cx: 11.781px;
  cy: 5.704px;
  rx: 0.179px;
  ry: 0.09px;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e8luse4zg {
  d: path("M10.582 3.276c.26-.275.75-.275.977-.234l.181.591a.35.35 0 0 0-.306.108c-.206.578-.912.897-1.24.984c-.068-.684.05-1.092.388-1.45");
}

.ea6c45boh {
  fill: var(--svg-color--272528, #272528);
  d: path("M12.382 5.76c-.122-.214-.307-.383-.705-.383a.76.76 0 0 0-.492.17c-.123.099-.106.226-.01.274l.254.146c.299-.097.63-.11.953-.207");
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.enjwdpbad {
  stop-color: var(--svg-color--79574b, #79574B);
}

.env4r_bwx {
  stop-color: var(--svg-color--966bb1, #966BB1);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.ew_xbgbtk {
  stop-color: var(--svg-color--8e695d, #8E695D);
  stop-opacity: 0;
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.fpwanpawi {
  stop-color: var(--svg-color--703536, #703536);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.fr5lpnb8e {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m12.726 5.92l-.314.779c-.05.16.07.32.24.32h.36a.247.247 0 0 0 .238-.32l-.243-.78c-.053-.172-.226-.172-.281 0");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g497ilbmf {
  d: path("M14.272 5.884a.4.4 0 0 0-.107-.212l-.119.13l.054.105z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.ga-j-qbpm {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gkusc7bym {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M13.43 5.76c.121-.214.306-.383.704-.383a.76.76 0 0 1 .492.17c.123.099.107.226.011.274l-.255.146c-.298-.097-.629-.11-.953-.207");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.h_g495b7x {
  fill: var(--svg-color--000, #000);
  d: path("M13.673 5.938c0-.13.104-.234.234-.234a.233.233 0 0 1 .208.342H13.7a.2.2 0 0 1-.027-.108");
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i1ugtm59q {
  stop-color: var(--svg-color--8e625f, #8E625F);
}

.ibqq90als {
  stop-color: var(--svg-color--7c5554, #7C5554);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.igykgyblk {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m14.009 4.105l-.654.12a.316.316 0 1 1-.057-.626h1.073c.635 0 .845.64.87.858a1.44 1.44 0 0 0-1.232-.352");
}

.ij3hr1_1o {
  d: path("M10.758 6.759a.738.738 0 1 0 0-1.475a.738.738 0 0 0 0 1.475");
}

.ita7_2enr {
  stop-color: var(--svg-color--774359, #774359);
  stop-opacity: 0;
}

.ivbdbpjuw {
  stop-color: var(--svg-color--614a93, #614A93);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jcizzuyvv {
  stop-color: var(--svg-color--734840, #734840);
}

.jfk78yx3r {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kc9o73bex {
  fill: var(--svg-color--000, #000);
  d: path("M12.139 5.938a.233.233 0 0 0-.235-.234a.233.233 0 0 0-.208.342h.415a.23.23 0 0 0 .028-.108");
}

.kg2v313dj {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.057 4.934a1.1 1.1 0 0 0-.761.157");
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l_m-s_sfy {
  d: path("M11.904 5.529a.41.41 0 0 0-.394.517h.79a.412.412 0 0 0-.396-.517");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l42l1fe0r {
  d: path("M12.278 5.89c0-.132-.107-.22-.136-.247l-.133.128l.082.166z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.laf_gab5x {
  fill: var(--svg-color--9f97a6, #9F97A6);
  fill-rule: evenodd;
  d: path("M12.571 4.457h-1.517a1.05 1.05 0 0 0 .469-.527l.037-.089a.12.12 0 0 1 .212-.023c.199.292.48.512.8.64");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqj1o1bqw {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.795 4.934c.148-.036.516-.018.761.157");
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mzo6olgul {
  stop-color: var(--svg-color--8568c5, #8568C5);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n6nx14b2o {
  fill: var(--svg-color--9f7b71, #9F7B71);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.n9y9mzb3z {
  d: path("M13.877 5.615c.029.04-.032.087-.101.139c-.07.051-.12.088-.15.049s.003-.113.073-.164s.149-.063.178-.024");
}

.ndv_tabmb {
  fill: var(--svg-color--352827, #352827);
  d: path("m11.348 5.206l-.002.001a.123.123 0 0 1-.126-.21l.002-.002l.004-.002l.015-.008l.053-.027c.045-.022.11-.05.188-.075a1.3 1.3 0 0 1 .609-.05a.123.123 0 1 1-.043.243c-.182-.033-.358 0-.491.042a1.3 1.3 0 0 0-.199.083z");
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.npc7sya5c {
  cx: 11.781px;
  cy: 5.704px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.179px;
  ry: 0.09px;
}

.nypbhiwdj {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.o9doel8cg {
  stop-color: var(--svg-color--93736e, #93736E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
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

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.q56466b2p {
  d: path("M12.63 2.45c-.52-.115-.987.403-1.04.595c.482 1.625 1.702 1.536 2.906 1.403c.721-.08.8.248.861.407c0-1.803-1.533-2.142-2.715-2.402z");
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qle5g2bis {
  stop-color: var(--svg-color--683733, #683733);
  stop-opacity: 0;
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qudtebbqf {
  stop-color: var(--svg-color--683733, #683733);
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

.r-4t27brr {
  d: path("M15.119 6.759a.738.738 0 1 0 0-1.475a.738.738 0 0 0 0 1.475");
}

.r0-mcdcik {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M12.63 2.45c-.52-.115-.987.403-1.04.595c.482 1.625 1.702 1.536 2.906 1.403c.721-.08.8.248.861.407c0-1.803-1.533-2.142-2.715-2.402z");
}

.r5ju49bro {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m14.617 4.997l-.064.105za.123.123 0 0 1-.126.21h-.002l-.052-.027a1 1 0 0 0-.157-.062a1.04 1.04 0 0 0-.491-.042a.123.123 0 0 1-.043-.243c.235-.041.453 0 .609.05a1.5 1.5 0 0 1 .256.11l.004.002l.002.001");
}

.r6n7exbot {
  stop-color: var(--svg-color--7d4348, #7D4348);
  stop-opacity: 0;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rjj-89bwr {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M15.119 6.514a.492.492 0 1 0 0-.985a.492.492 0 0 0 0 .985");
}

.rrpkz-bur {
  stop-color: var(--svg-color--805e51, #805E51);
  stop-opacity: 0;
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rune_jfwz {
  d: path("m12.73 5.856l-.243.78c-.05.16.07.32.238.32h.36c.17 0 .29-.163.24-.32l-.244-.78c-.052-.173-.296-.173-.35 0");
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s0jqq-b-a {
  d: path("M10.574 5.443h.005l-.005-.122l-.004-.14c.01-.435.263-.604.371-.66l.024-.01l.023-.009c.245-.112.442-.308.546-.566l.037-.089a.12.12 0 0 1 .212-.023a1.77 1.77 0 0 0 1.462.767h1.476c.083 0 .496.04.52.61l-.054 1.41c-.056 1.285-1.06 2.147-2.284 2.147c-1.225 0-2.228-.862-2.285-2.147z");
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s6non86-m {
  stop-color: var(--svg-color--7d4348, #7D4348);
}

.sa6pubcic {
  stop-color: var(--svg-color--8466c4, #8466C4);
}

.sa73rem9k {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.spg8_pgop {
  stop-color: var(--svg-color--966bb1, #966BB1);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.tmtee3wvy {
  fill: var(--svg-color--876cc6, #876CC6);
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.tyifp67am {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.u9h3-mbda {
  fill: var(--svg-color--876054, #876054);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.uov-5vb3w {
  stop-color: var(--svg-color--9782d0, #9782D0);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uwn_p0-dn {
  stop-color: var(--svg-color--8366c4, #8366C4);
}

.v_thlccbr {
  stop-color: var(--svg-color--9a82d0, #9A82D0);
  stop-opacity: 0;
}

.v18-6mbdj {
  d: path("M15.119 6.514a.492.492 0 1 0 0-.985a.492.492 0 0 0 0 .985");
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vinvwq12a {
  stop-color: var(--svg-color--825853, #825853);
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vlzz19buw {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M12.906 7.356c-.24 0-.464-.057-.652-.158c-.065-.033-.134.04-.093.1a.886.886 0 0 0 1.49 0c.04-.062-.03-.133-.094-.1c-.188.1-.41.158-.652.158");
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.vyhwsac2j {
  fill: var(--svg-color--9c776f, #9C776F);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.w__bqyylv {
  stop-color: var(--svg-color--8768cb, #8768CB);
}

.w7gy_9e9s {
  fill-rule: evenodd;
  d: path("M16.2 6.668c.097-.2.148-.423.148-.655a1.5 1.5 0 0 0-.123-.598h.003a1.5 1.5 0 0 0-.13-.235v-.002a1.5 1.5 0 0 1-.241-.812v-.004c0-.835-.678-1.513-1.513-1.513a.25.25 0 0 1-.209-.107a1.515 1.515 0 0 0-2.459 0a.26.26 0 0 1-.209.107h-.039a1.513 1.513 0 0 0-1.473 1.513v.004c0 .288-.084.571-.241.812l-.002.002a1.51 1.51 0 0 0-.1 1.488a.24.24 0 0 1 0 .208a1.473 1.473 0 0 0 1.327 2.12h3.934a1.473 1.473 0 0 0 1.327-2.12a.24.24 0 0 1 0-.208m-5.621-1.226h-.006l.55 1.08c.056 1.285.558 0 1.783 0s1.758 1.43 1.815.146l.52-1.466c-.024-.57-.437-.61-.52-.61h-1.476a1.77 1.77 0 0 1-1.462-.768a.12.12 0 0 0-.212.023l-.038.09a1.06 1.06 0 0 1-.592.584c-.108.056-.362.224-.371.66l.004.14z");
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wn-8yz5zd {
  d: path("M10.766 6.514a.492.492 0 1 0 0-.985a.492.492 0 0 0 0 .985");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x2cy8lb4b {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m12.73 5.856l-.243.78c-.05.16.07.32.238.32h.36c.17 0 .29-.163.24-.32l-.244-.78c-.052-.173-.296-.173-.35 0");
}

.x41u_8htb {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.xau3og86r {
  stop-color: var(--svg-color--774359, #774359);
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y2teulbve {
  stop-color: var(--svg-color--805e51, #805E51);
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.ym57y3k6t {
  d: path("M13.907 5.529a.41.41 0 0 1 .394.517h-.79a.41.41 0 0 1 .396-.517");
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.za46tubip {
  stop-color: var(--svg-color--8e695d, #8E695D);
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zdghv6w0b {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.002 5.404c.3 0 .552.207.621.486c.02.08-.04.156-.123.156h-1.023a.106.106 0 0 1-.104-.125a.64.64 0 0 1 .629-.517");
}

.znoi6dbpx {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.906 7.356c-.24 0-.464-.057-.652-.158c-.065-.033-.134.04-.093.1a.886.886 0 0 0 1.49 0c.04-.062-.03-.133-.094-.1c-.188.1-.41.158-.652.158Z");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zovioqy4e {
  stop-color: var(--svg-color--614a93, #614A93);
  stop-opacity: 0;
}

</style>
