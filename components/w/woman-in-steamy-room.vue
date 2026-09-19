<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iIR1gzd)" class="lci33sbas"/><circle fill="url(#iGl3jDb)" class="lci33sbas"/><circle fill="url(#iI1NFde)" class="tyonxd6hb"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.14)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.14)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.344)" class="n5l_opbqq"/><g filter="url(#irNpT7c)"><path fill="url(#iQAZpDl)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#i7kJTjc)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#igolvxb)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#i0JkjOb)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#ivhxCnb)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#il6l2Kd)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iL9GytM)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#ir7clLb)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#i30OAsd)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#inrp41b)" clip-rule="evenodd" class="hysa-obih"/><path fill="url(#iXCQkCb)" clip-rule="evenodd" class="hysa-obih"/></g><path fill="url(#i0kcK7c)" class="hieissb8f"/><path fill="url(#iolH3vb)" class="hieissb8f"/><path fill="url(#iB3hoPT)" class="hieissb8f"/><path fill="url(#iusAoje)" class="jzdyl8vho"/><path fill="url(#il155vc)" class="jzdyl8vho"/><path class="r7qt7msxe"/><path fill="url(#iwk2VUb)" class="g82rs5bds"/><path fill="url(#i5JGmPe)" class="g82rs5bds"/><path fill="url(#ivaa0Tz)" class="g82rs5bds"/><path fill="url(#i4bO0ep)" class="g82rs5bds"/><path fill="url(#il8OUce)" class="g82rs5bds"/><path fill="url(#iEjsBbc)" class="g82rs5bds"/><path class="fuhh63zgj"/><path fill="url(#iMN29Ne)" class="kodm2eyrj"/><path fill="url(#iUzxEbL)" class="kodm2eyrj"/><path fill="url(#ihkZPvb)" class="kodm2eyrj"/><g filter="url(#iQUZNNc)"><path class="lbpaw9boc"/><path fill="url(#iCxhGbd)" class="t8fto9bsf"/><path fill="url(#iyUR8Jc)" class="t8fto9bsf"/></g><path class="x584qub8p"/><g filter="url(#iAmUczq)"><path fill="url(#iam0zVM)" class="zcbc6uesb"/></g><g filter="url(#ixkVi0c)"><path fill="url(#iQoDlbQ)" class="l3s-hrybn"/></g><g filter="url(#icRDTPc)"><path class="bcy695iyf"/><path fill="url(#i1Q4wed)" class="lkbw50g8u"/></g><g filter="url(#iWho5yd)"><path class="cfj2ohn-g"/><path fill="url(#iayE8Be)" class="n27uwn5ui"/></g><g filter="url(#imXsjDb)"><path fill="url(#iHKfiPb)" class="b8qbyubud"/><path fill="url(#ilA0plc)" class="b8qbyubud"/><path fill="url(#iY7wQRc)" class="b8qbyubud"/><path fill="url(#iy5zk0K)" class="b8qbyubud"/><path fill="url(#i0W2Ffc)" class="b8qbyubud"/><path fill="url(#i4eVaFc)" class="b8qbyubud"/><path fill="url(#iWUN0Vd)" class="b8qbyubud"/></g><path fill="url(#iJGobje)" class="b8qbyubud"/><g filter="url(#iCzbZuy)"><path class="vog-4k2ir"/></g><g filter="url(#iAs4xLe)"><path fill="url(#icTkOZd)" class="e7cczo7nf"/><path fill="url(#iseGOfd)" class="e7cczo7nf"/><path fill="url(#idCsMsb)" class="e7cczo7nf"/><path fill="url(#i48TIXG)" class="e7cczo7nf"/></g><g filter="url(#iSKimqc)"><path stroke="url(#i9f42Td)" class="x1f74ybcu"/></g><path class="js41udvzr"/><g filter="url(#iABUsbc)"><path class="ej7gq-22b"/></g><g filter="url(#iRz8Tfx)"><path class="j0o8babxq"/></g><g filter="url(#iLL2tYc)"><path class="ytmz60blo"/></g><g filter="url(#iDvYD3d)"><path clip-rule="evenodd" class="pihl49b_k"/></g><path class="g3dwi4b-d"/><path fill="url(#iiWLzPe)" class="kdxd4jb8w"/><path class="usevvd_vg"/><g filter="url(#iIwaXqe)"><path class="legemywhx"/><path fill="url(#iQUn9Ic)" class="q-7ma3bte"/></g><g filter="url(#i85YlPe)"><path fill="url(#iPQ3lYd)" class="pmtm0xb1d"/></g><path class="bg9a43hyt"/><path fill="url(#iBOnRfb)" class="g-phrvb2c"/><path class="dnrth1wtg"/><g filter="url(#iNwkeKb)"><path fill="url(#ija1TNe)" class="u8tti6bmm"/></g><g filter="url(#iz8xnKb)"><ellipse transform="rotate(-27.914 13.454 9.981)" class="arxs48xhc"/><ellipse fill="url(#iEgBXmc)" transform="rotate(-27.914 13.454 9.981)" class="a042a5b8x"/></g><g filter="url(#iCz81Rb)"><path class="berna27oo"/></g><g filter="url(#iHNuUQb)"><path class="ulkip2bwn"/></g><g filter="url(#iOOkmsc)"><path fill="url(#iKoGQge)" class="e941jjb9d"/><path fill="url(#i8r4YMd)" class="e941jjb9d"/></g><g filter="url(#izJn82T)"><path fill="url(#iQB6FYd)" class="vhrq1fbqo"/><path fill="url(#ioqh9Fe)" class="vhrq1fbqo"/><path fill="url(#iPWUsad)" class="vhrq1fbqo"/></g><g filter="url(#iAd5k5U)"><path stroke="url(#iUVtZad)" class="ptw-qpjib"/></g><defs><radialGradient id="iIR1gzd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.305)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="iGl3jDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.805)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="iI1NFde" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.244)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="i7kJTjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.8353 1.5267 -2.1625 4.01607 19.79 14.011)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="igolvxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.4993 -2.71068 0 11.316 12.733)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="i0JkjOb" cx="0" cy="0" r="1" gradientTransform="scale(5.859 5.62456)rotate(90 .22 2.5)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="ivhxCnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25268 1.62564 -1.57841 -1.21629 10.973 11.004)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="il6l2Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-.47208 2.53795 -2.64279 -.49158 11.57 8.544)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iL9GytM" cx="0" cy="0" r="1" gradientTransform="matrix(1.10608 2.13427 -4.06574 2.10707 12.562 3.449)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="ir7clLb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.668 7.165)scale(1.65287 2.30985)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="i30OAsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86139 .54152 -1.17828 -4.05014 23.512 9.82)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="inrp41b" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.622 4.17)scale(4.70698 6.75977)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iXCQkCb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.352 9.565 -3.576)scale(1.38761 .45495)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="i0kcK7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.555)" gradientUnits="userSpaceOnUse"><stop class="ttp7yqb-m"/><stop offset="1" class="jletv-brl"/></radialGradient><radialGradient id="iusAoje" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.295)" gradientUnits="userSpaceOnUse"><stop class="wv2o2nbhk"/><stop offset="1" class="n44b27bdp"/></radialGradient><radialGradient id="iwk2VUb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.367)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="epu6iq_fg"/><stop offset="1" class="q8d1l4bok"/></radialGradient><radialGradient id="ivaa0Tz" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.938)" gradientUnits="userSpaceOnUse"><stop class="x37sucbkr"/><stop offset="1" class="k796fybnd"/></radialGradient><radialGradient id="il8OUce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.555)" gradientUnits="userSpaceOnUse"><stop class="bp-uy2zsn"/><stop offset="1" class="dfpk_zbbl"/></radialGradient><radialGradient id="iEjsBbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.49)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="jhdqd89ez"/><stop offset="1" class="tbqxjbcmi"/></radialGradient><radialGradient id="iUzxEbL" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.305)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="x4p5bn7mz"/><stop offset="1" class="rz_1qnb6a"/></radialGradient><radialGradient id="ihkZPvb" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.499 18.281)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="tqo-vnfob"/><stop offset="1" class="fqnn-rb2e"/></radialGradient><radialGradient id="iCxhGbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.75 -2.19025 2.26847 13.158 17.18)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="weoi4g6va"/><stop offset="1" class="v8h40hgkm"/></radialGradient><radialGradient id="iyUR8Jc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.40625 -5.78125 0 16.14 16.047)" gradientUnits="userSpaceOnUse"><stop class="j_6olubtd"/><stop offset="1" class="ckw15_03n"/></radialGradient><radialGradient id="iQoDlbQ" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 35.682 -40.626)scale(2.76041 3.37034)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="i1Q4wed" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.788 -51.99)scale(1.31713)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iayE8Be" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08444 0 0 -1.03733 11.22 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iHKfiPb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56611 3.02785 -4.05273 -8.78862 18.818 10.138)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="ilA0plc" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.58 7.636)scale(2.40963 2.0444)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iY7wQRc" cx="0" cy="0" r="1" gradientTransform="matrix(.84497 -4.08402 5.18187 1.07211 13.73 16.986)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iy5zk0K" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.51213 -11.9313 0 15.667 9.65)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="i0W2Ffc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4747 1.51395 -2.60655 -9.42574 16.564 11.81)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i4eVaFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16184 1.42589 0 18.255 9.715)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iWUN0Vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37308 1.57364 0 13.994 9.803)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iJGobje" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3599 0 0 -4.47684 21.076 11.217)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iseGOfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.70416 -2.4733 1.41525 -.40293 16.723 11.951)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iiWLzPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81912 -1.3029 0 18.134 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iQUn9Ic" cx="0" cy="0" r="1" gradientTransform="matrix(-.23384 -.30133 .41486 -.32194 17.903 10.162)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iBOnRfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81912 -1.30291 0 13.728 10.078)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iEgBXmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0078 -.49815 .5988 -.00938 13.438 10.298)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKoGQge" cx="0" cy="0" r="1" gradientTransform="matrix(-3.45221 4.17983 -1.82295 -1.50561 13.19 3.661)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="i8r4YMd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1326 2.23793 -1.10602 -1.54817 13.049 4.214)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iQB6FYd" cx="0" cy="0" r="1" gradientTransform="rotate(115.63 8.09 6.821)scale(5.10072 7.24217)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="ioqh9Fe" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.82 8.84)scale(3.47311 7.27855)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iPWUsad" cx="0" cy="0" r="1" gradientTransform="rotate(-117.848 11.387 -.436)scale(7.38486 6.60161)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="irNpT7c" width="15.412" height="15.412" x="8.35" y="1.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="iQUZNNc" width="6.879" height="12.039" x="12.32" y="15.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.552941 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="iAmUczq" width="3.349" height="3.249" x="9.576" y="9.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="ixkVi0c" width="3.249" height="3.499" x="19.18" y="8.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="icRDTPc" width="3.169" height="3.169" x="19.221" y="9.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".25"/></filter><filter id="iWho5yd" width="2.669" height="2.669" x="9.886" y="9.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".125"/></filter><filter id="imXsjDb" width="10.289" height="11.381" x="10.787" y="5.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="iCzbZuy" width="2.895" height="3.708" x="14.32" y="9.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".25"/></filter><filter id="iAs4xLe" width="2.395" height="3.208" x="14.733" y="9.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".125"/></filter><filter id="iSKimqc" width="3.734" height="1.537" x="14.064" y="13.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".05"/></filter><filter id="iABUsbc" width="3.028" height="1.298" x="16.884" y="9.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="iRz8Tfx" width="3.028" height="1.298" x="11.95" y="9.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="iLL2tYc" width="2.474" height="1.1" x="12.086" y="7.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="iDvYD3d" width="2.474" height="1.1" x="17.556" y="7.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_777"/></filter><filter id="iIwaXqe" width=".792" height=".7" x="17.394" y="9.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".05"/></filter><filter id="i85YlPe" width=".896" height=".918" x="18.243" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".1"/></filter><filter id="iNwkeKb" width=".991" height="1.046" x="13.757" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".1"/></filter><filter id="iz8xnKb" width=".919" height=".709" x="12.994" y="9.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".05"/></filter><filter id="iCz81Rb" width="2.277" height=".981" x="17.589" y="7.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".1"/></filter><filter id="iHNuUQb" width="2.277" height=".981" x="12.085" y="7.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".1"/></filter><filter id="iOOkmsc" width="5.019" height="5.249" x="9.166" y="3.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".375"/></filter><filter id="izJn82T" width="8.995" height="5.831" x="12.584" y="2.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".125"/></filter><filter id="iAd5k5U" width="1.15" height="2.326" x="12.712" y="3.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_777" stdDeviation=".125"/></filter><linearGradient id="iQAZpDl" x1="20.669" x2="13.359" y1="3.661" y2="17.233" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iolH3vb" x1="24.158" x2="24.189" y1="30.305" y2="26.648" gradientUnits="userSpaceOnUse"><stop offset=".078" class="y41hsabjm"/><stop offset="1" class="y-a_999zn"/></linearGradient><linearGradient id="iB3hoPT" x1="18.12" x2="19.472" y1="27.74" y2="28.127" gradientUnits="userSpaceOnUse"><stop class="mbuex5b5r"/><stop offset="1" class="ozroxmy8l"/></linearGradient><linearGradient id="il155vc" x1="13.658" x2="12.158" y1="28.711" y2="29.242" gradientUnits="userSpaceOnUse"><stop class="g82zxu-vf"/><stop offset="1" class="sv9br1byn"/></linearGradient><linearGradient id="i5JGmPe" x1="12.315" x2="13.69" y1="27.367" y2="26.805" gradientUnits="userSpaceOnUse"><stop offset=".223" class="zantcf-1d"/><stop offset="1" class="tkat5cdin"/></linearGradient><linearGradient id="i4bO0ep" x1="15.627" x2="14.221" y1="30.148" y2="29.461" gradientUnits="userSpaceOnUse"><stop offset=".208" class="roh2cebgd"/><stop offset="1" class="u44j7rbwl"/></linearGradient><linearGradient id="iMN29Ne" x1="16.002" x2="18.033" y1="24.805" y2="25.711" gradientUnits="userSpaceOnUse"><stop class="z0qi4zb3s"/><stop offset="1" class="nh4l3fbho"/></linearGradient><linearGradient id="iam0zVM" x1="9.576" x2="12.563" y1="10.768" y2="10.768" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="icTkOZd" x1="15.931" x2="15.931" y1="12.738" y2="10.031" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="idCsMsb" x1="14.875" x2="15.737" y1="11.969" y2="12.074" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="i48TIXG" x1="15.931" x2="15.931" y1="12.831" y2="12.215" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="i9f42Td" x1="15.195" x2="15.652" y1="14.322" y2="13.442" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iPQ3lYd" x1="18.919" x2="18.603" y1="10.132" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ija1TNe" x1="14.479" x2="14.162" y1="10.132" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUVtZad" x1="13.012" x2="13.562" y1="4.423" y2="5.709" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-steamy-room" /></template>
<style>
.a042a5b8x {
  cx: 13.454px;
  cy: 9.981px;
  rx: 0.393px;
  ry: 0.199px;
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.arxs48xhc {
  cx: 13.454px;
  cy: 9.981px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.393px;
  ry: 0.199px;
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.b8qbyubud {
  d: path("M10.795 9.406h.012l-.01-.268l-.01-.31c.02-.957.58-1.328.817-1.452l.052-.02q.028-.013.052-.02a2.33 2.33 0 0 0 1.201-1.247l.083-.196a.266.266 0 0 1 .466-.051a3.9 3.9 0 0 0 3.22 1.689h3.25c.182 0 1.093.088 1.148 1.345l-.12 3.103c-.125 2.829-2.334 4.729-5.032 4.729s-4.906-1.9-5.03-4.73z");
}

.bcy695iyf {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.805 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
}

.berna27oo {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.89 8.285c.325-.08 1.135-.04 1.676.348");
}

.bg9a43hyt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.517 9.322a1.41 1.41 0 0 0-1.368 1.069a.277.277 0 0 0 .27.344h2.253a.232.232 0 0 0 .23-.275a1.415 1.415 0 0 0-1.385-1.138");
}

.bp-uy2zsn {
  stop-color: var(--svg-color--442d6d, #442D6D);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.cfj2ohn-g {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.22 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
}

.ckw15_03n {
  stop-color: var(--svg-color--f8a933, #F8A933);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dfpk_zbbl {
  stop-color: var(--svg-color--7c5fac, #7C5FAC);
  stop-opacity: 0;
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dnrth1wtg {
  fill: var(--svg-color--000, #000);
  d: path("M14.242 10.497a.514.514 0 0 0-.516-.516a.514.514 0 0 0-.459.754h.914a.5.5 0 0 0 .061-.238");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e7cczo7nf {
  d: path("m15.545 10.316l-.537 1.716a.544.544 0 0 0 .526.706h.794a.546.546 0 0 0 .526-.706l-.537-1.716c-.115-.38-.652-.38-.772 0");
}

.e941jjb9d {
  d: path("M10.99 4.609c.627-.559 1.531-.564 2.039-.474l.406 1.303c-.26-.04-.49.05-.685.237c-.46 1.272-2.042 1.974-2.775 2.166c-.153-1.506-.068-2.268 1.015-3.232");
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.ej7gq-22b {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.084 10.106c.268-.471.676-.844 1.552-.844c.384 0 .755.107 1.084.373c.27.219.235.5.024.605l-.561.32c-.658-.213-1.386-.241-2.099-.454");
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.epu6iq_fg {
  stop-color: var(--svg-color--4f3466, #4F3466);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fqnn-rb2e {
  stop-color: var(--svg-color--7b63b3, #7B63B3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuhh63zgj {
  fill: var(--svg-color--7a60bc, #7A60BC);
  d: path("M21.82 17.328c-.642-1.312-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.816 3.383-8.741c.42-1.004.809-2.477.215-3.86");
}

.g-phrvb2c {
  d: path("M13.726 9.596a.9.9 0 0 0-.868 1.139h1.74a1 1 0 0 0 .033-.238a.907.907 0 0 0-.905-.901");
}

.g3dwi4b-d {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.345 9.322c.66 0 1.216.454 1.368 1.069a.277.277 0 0 1-.27.344H17.19a.232.232 0 0 1-.23-.275a1.41 1.41 0 0 1 1.385-1.138");
}

.g82rs5bds {
  d: path("M9.9 17.328c.641-1.312 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.816-3.68-8.741c-.42-1.004-.89-2.477-.297-3.86");
}

.g82zxu-vf {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hieissb8f {
  d: path("M26.947 29.914c0-7.96-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hysa-obih {
  fill-rule: evenodd;
  d: path("M23.185 12.104c.215-.44.327-.93.327-1.44a3.3 3.3 0 0 0-.27-1.319h.005a3 3 0 0 0-.284-.518l-.002-.003a3.27 3.27 0 0 1-.532-1.788v-.01a3.33 3.33 0 0 0-3.33-3.331a.54.54 0 0 1-.46-.235a3.34 3.34 0 0 0-2.708-1.39a3.34 3.34 0 0 0-2.708 1.39a.57.57 0 0 1-.46.235l-.085.001a3.33 3.33 0 0 0-3.245 3.33v.01A3.27 3.27 0 0 1 8.9 8.824l-.002.004a3.33 3.33 0 0 0-.222 3.276a.52.52 0 0 1 0 .46a3.244 3.244 0 0 0 2.922 4.67h8.664a3.244 3.244 0 0 0 2.922-4.67a.52.52 0 0 1 0-.46M10.807 9.406h-.012l1.21 2.378c.125 2.83 1.229 0 3.926 0s3.873 3.15 3.998.32l1.147-3.228c-.055-1.257-.966-1.345-1.147-1.345h-3.251a3.9 3.9 0 0 1-3.22-1.69a.266.266 0 0 0-.466.052l-.083.196a2.33 2.33 0 0 1-1.2 1.246l-.053.02l-.051.021c-.239.124-.798.495-.818 1.453l.01.309z");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j_6olubtd {
  stop-color: var(--svg-color--f8a933, #F8A933);
}

.j0o8babxq {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.778 10.106c-.268-.471-.675-.844-1.552-.844c-.384 0-.754.107-1.083.373c-.271.219-.235.5-.025.605l.562.32c.658-.213 1.385-.241 2.098-.454");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jhdqd89ez {
  stop-color: var(--svg-color--342554, #342554);
}

.jletv-brl {
  stop-color: var(--svg-color--8067c6, #8067C6);
}

.js41udvzr {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.931 13.62a3.06 3.06 0 0 1-1.435-.348c-.142-.074-.295.09-.205.221a1.95 1.95 0 0 0 3.28 0c.09-.137-.063-.295-.205-.221a3.04 3.04 0 0 1-1.435.348");
}

.jzdyl8vho {
  d: path("M5.096 29.914c0-7.96 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.k796fybnd {
  stop-color: var(--svg-color--8870c8, #8870C8);
  stop-opacity: 0;
}

.kdxd4jb8w {
  d: path("M18.136 9.596a.9.9 0 0 1 .868 1.139h-1.74a.905.905 0 0 1 .872-1.139");
}

.kodm2eyrj {
  d: path("M21.82 17.328c-.642-1.312-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.583 2.995-7.816 3.383-8.741c.42-1.004.809-2.477.215-3.86");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.l3s-hrybn {
  d: path("M20.805 12.305a1.625 1.625 0 1 0 0-3.249a1.625 1.625 0 0 0 0 3.249");
}

.lbpaw9boc {
  fill: var(--svg-color--ffce26, #FFCE26);
  d: path("M14.01 15.39h4v1.99c.01.174.045.373.152.53a.8.8 0 0 0 .445.332l.465.164c.076.068.22.478.04.985c-.181.505-2.043 5.51-3.094 8.019v.02l-.005-.01l-.004.01v-.02c-1.052-2.51-3.139-7.515-3.32-8.02c-.18-.506-.122-.87-.046-.937l.68-.191c.218-.063.373-.14.515-.348c.113-.165.158-.39.172-.572z");
}

.lci33sbas {
  cx: 10.674px;
  cy: 16.141px;
  r: 4.086px;
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.legemywhx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.069 9.787c.064.086-.07.19-.222.304c-.153.114-.266.194-.33.108c-.064-.085.008-.247.16-.361s.328-.137.392-.051");
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkbw50g8u {
  d: path("M20.805 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbuex5b5r {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n27uwn5ui {
  d: path("M11.22 11.765a1.084 1.084 0 1 0 0-2.169a1.084 1.084 0 0 0 0 2.169");
}

.n44b27bdp {
  stop-color: var(--svg-color--7353bf, #7353BF);
}

.n5l_opbqq {
  r: 6.305px;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nh4l3fbho {
  stop-color: var(--svg-color--684c87, #684C87);
  stop-opacity: 0;
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ozroxmy8l {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
  stop-opacity: 0;
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pihl49b_k {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.699 8.424l-.14.232za.271.271 0 0 1-.279.464l-.004-.002l-.022-.013l-.092-.046a3 3 0 0 0-.346-.136a2.3 2.3 0 0 0-1.082-.093a.27.27 0 0 1-.095-.534c.518-.091.998.001 1.341.11a3.3 3.3 0 0 1 .564.241l.01.006l.003.002z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmtm0xb1d {
  d: path("M18.938 10.378a.85.85 0 0 0-.233-.467l-.262.288l.118.23z");
}

.ptw-qpjib {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.012 4.076c.024.245.237 1.167.55 1.726");
}

.q-7ma3bte {
  d: path("M18.069 9.787c.064.086-.07.19-.222.304c-.153.114-.266.194-.33.108c-.064-.085.008-.247.16-.361s.328-.137.392-.051");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q8d1l4bok {
  stop-color: var(--svg-color--6d4f8c, #6D4F8C);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qnar36wle {
  r: 4.086px;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r7qt7msxe {
  fill: var(--svg-color--795cc2, #795CC2);
  d: path("M9.9 17.328c.641-1.312 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.816-3.68-8.741c-.42-1.004-.89-2.477-.297-3.86");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.roh2cebgd {
  stop-color: var(--svg-color--6349aa, #6349AA);
}

.rz_1qnb6a {
  stop-color: var(--svg-color--593d6e, #593D6E);
  stop-opacity: 0;
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sv9br1byn {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
  stop-opacity: 0;
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t8fto9bsf {
  d: path("M14.01 15.39h4v1.99c.01.174.045.373.152.53a.8.8 0 0 0 .445.332l.465.164c.076.068.22.478.04.985c-.181.505-2.043 5.51-3.094 8.019v.02l-.005-.01l-.004.01v-.02c-1.052-2.51-3.139-7.515-3.32-8.02c-.18-.506-.122-.87-.046-.937l.68-.191c.218-.063.373-.14.515-.348c.113-.165.158-.39.172-.572z");
}

.tbqxjbcmi {
  stop-color: var(--svg-color--614279, #614279);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tkat5cdin {
  stop-color: var(--svg-color--795cc2, #795CC2);
  stop-opacity: 0;
}

.tqo-vnfob {
  stop-color: var(--svg-color--9078d3, #9078D3);
}

.ttp7yqb-m {
  stop-color: var(--svg-color--9279d5, #9279D5);
}

.tyonxd6hb {
  cx: 8.275px;
  cy: 23.344px;
  r: 6.305px;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u44j7rbwl {
  stop-color: var(--svg-color--7c60c4, #7C60C4);
  stop-opacity: 0;
}

.u8tti6bmm {
  d: path("M14.549 10.39c0-.29-.237-.484-.3-.543l-.292.282l.18.364z");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ulkip2bwn {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.062 8.285c-.326-.08-1.135-.04-1.677.348");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.usevvd_vg {
  fill: var(--svg-color--000, #000);
  d: path("M17.62 10.497c0-.287.23-.516.516-.516a.514.514 0 0 1 .459.754h-.913a.47.47 0 0 1-.062-.238");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.v8h40hgkm {
  stop-color: var(--svg-color--ffae2f, #FFAE2F);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vhrq1fbqo {
  d: path("M15.322 2.815c-1.144-.253-2.37.964-2.488 1.388c1.557 3.655 3.948 3.306 6.6 3.012c1.588-.177 1.76.547 1.895.897c-.44-4.096-3.401-4.722-6.007-5.297");
}

.vog-4k2ir {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.535 10.456l-.69 1.716a.544.544 0 0 0 .525.706h.794a.546.546 0 0 0 .526-.706l-.537-1.716c-.115-.38-.498-.38-.618 0");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.weoi4g6va {
  stop-color: var(--svg-color--c17b1f, #C17B1F);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wv2o2nbhk {
  stop-color: var(--svg-color--7a67ab, #7A67AB);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x1f74ybcu {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.931 13.62a3.06 3.06 0 0 1-1.435-.348c-.142-.074-.295.09-.205.221a1.95 1.95 0 0 0 3.28 0c.09-.137-.063-.295-.205-.221a3.04 3.04 0 0 1-1.435.348Z");
}

.x37sucbkr {
  stop-color: var(--svg-color--8870c8, #8870C8);
}

.x4p5bn7mz {
  stop-color: var(--svg-color--2c1c48, #2C1C48);
}

.x584qub8p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 23.992h3.298a5.94 5.94 0 0 1 5.937 5.938H1.971zm28.06 0h-3.298a5.937 5.937 0 0 0-5.937 5.938h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y-a_999zn {
  stop-color: var(--svg-color--7e64c5, #7E64C5);
  stop-opacity: 0;
}

.y41hsabjm {
  stop-color: var(--svg-color--704cc0, #704CC0);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.ytmz60blo {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.5 8.886l-.004.002a.27.27 0 0 1-.278-.464l.002-.001l.003-.002l.01-.006a2 2 0 0 1 .149-.077c.1-.048.241-.108.414-.163c.343-.11.823-.202 1.341-.11a.27.27 0 1 1-.094.533a2.3 2.3 0 0 0-1.082.092a3 3 0 0 0-.46.196");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z0qi4zb3s {
  stop-color: var(--svg-color--684c87, #684C87);
}

.zantcf-1d {
  stop-color: var(--svg-color--775cbc, #775CBC);
}

.zcbc6uesb {
  d: path("M11.2 12.305a1.625 1.625 0 1 0 0-3.249a1.625 1.625 0 0 0 0 3.249");
}

</style>
