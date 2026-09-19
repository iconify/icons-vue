<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iITAOYb)" class="d2kvgvbvc"><path fill="url(#iYWGHCd)" class="z1su-ab9u"/><path fill="url(#iTef7uc)" class="z1su-ab9u"/><path fill="url(#iwlK4we)" class="z1su-ab9u"/><path fill="url(#iMFs26d)" class="z1su-ab9u"/><path fill="url(#iMeodOc)" class="z1su-ab9u"/><path fill="url(#iMJkMsa)" class="z1su-ab9u"/><path fill="url(#i9G7aPe)" class="z1su-ab9u"/><path fill="url(#irmpGOd)" class="z1su-ab9u"/><path fill="url(#iDgmYye)" class="z1su-ab9u"/></g><path fill="url(#ifW2YHe)" clip-rule="evenodd" class="sxbn0pb5c"/><path fill="url(#iiJISUd)" clip-rule="evenodd" class="sxbn0pb5c"/><path fill="url(#ioqnJKd)" clip-rule="evenodd" class="sxbn0pb5c"/><path fill="url(#iL5vqfb)" clip-rule="evenodd" class="sxbn0pb5c"/><path fill="url(#iKorEZd)" clip-rule="evenodd" class="sxbn0pb5c"/><path fill="url(#iyHj6HP)" clip-rule="evenodd" class="sxbn0pb5c"/><path fill="url(#iaX54De)" class="vi4zq9bup"/><path fill="url(#izzyc2c)" class="vi4zq9bup"/><path fill="url(#ixTDisb)" class="w_8c_6tma"/><g filter="url(#iECXBbd)"><path fill="url(#iWDNyFe)" class="tevglhr_j"/></g><g filter="url(#iOQjrPe)"><path fill="url(#iIm56Pe)" class="cqjhltbpm"/></g><g filter="url(#i7utglc)"><path class="m_15mey2s"/><path fill="url(#iJ2TO3j)" class="uyi8rbivm"/></g><g filter="url(#iFjVvNd)"><path class="ha9szvesl"/><path fill="url(#iD9L0Vd)" class="ozqrj60zd"/></g><g filter="url(#iyWGaWc)"><path fill="url(#iAvxMrb)" class="ed-k8b0de"/><path fill="url(#iSTm3lb)" class="ed-k8b0de"/><path fill="url(#igb3eKb)" class="ed-k8b0de"/><path fill="url(#iIJ3Ise)" class="ed-k8b0de"/><path fill="url(#izFykmd)" class="ed-k8b0de"/></g><path fill="url(#inykMqe)" class="ed-k8b0de"/><g filter="url(#ilVbsGe)"><path class="atl_u83kj"/></g><g filter="url(#iTabyzb)"><path fill="url(#iHVL7sd)" class="hgk_o7b-f"/><path fill="url(#ix9OIPc)" class="hgk_o7b-f"/><path fill="url(#isTFOQb)" class="hgk_o7b-f"/><path fill="url(#i6JhwGi)" class="hgk_o7b-f"/></g><g filter="url(#iFFKsrc)"><path fill="url(#ijLjOYT)" class="nm20ljqyc"/></g><g filter="url(#ilT5qub)"><path stroke="url(#iNCMm6d)" class="myswpvabz"/></g><path class="u2z1wbxzr"/><g filter="url(#iN0YCpf)"><path fill="url(#i7khXok)" class="hf6jj6p6x"/><path fill="url(#iUC6aic)" class="hf6jj6p6x"/></g><g filter="url(#ilSCo6d)"><path fill="url(#iKgAqOc)" class="cnsrceb_i"/><path fill="url(#iM8oh7z)" class="cnsrceb_i"/><path fill="url(#iN3IjTc)" class="cnsrceb_i"/></g><g filter="url(#izD42ub)"><path stroke="url(#iDOELgb)" class="to8hl0otd"/></g><path fill="url(#ilGiRdd)" class="fn9fyz7-m"/><path fill="url(#iBQye3c)" class="ibm7k8bfw"/><g filter="url(#iHE0k2b)" class="tryqaac1t"><path stroke="url(#i2650Kd)" class="k3uuwuaug"/><path stroke="url(#ivgLKeb)" class="k3uuwuaug"/></g><g filter="url(#iQcsh1j)" class="tryqaac1t"><path stroke="url(#iXFFLLb)" class="nevorxyqz"/><path stroke="url(#ihfF2yb)" class="nevorxyqz"/></g><g filter="url(#i1luzqx)"><path fill="url(#i30dAVb)" class="jnie2pbod"/></g><g filter="url(#iSq4Wwj)"><path fill="url(#iykhv6b)" class="taia9tz6b"/></g><g filter="url(#inHS93c)"><path class="c0tk_hbnc"/></g><g filter="url(#iYydDib)"><path clip-rule="evenodd" class="k9qsgnves"/></g><g filter="url(#itBZvyO)"><path class="yjg5mljgk"/></g><g filter="url(#ifkcfSo)"><path class="abx2fsbum"/></g><path class="v-ki5fbze"/><path fill="url(#iHKGhFb)" class="qhwpq86jp"/><path fill="url(#iLeXJLY)" class="qhwpq86jp"/><path fill="url(#iU0YlPb)" class="qhwpq86jp"/><path fill="url(#iZhLZXb)" class="qhwpq86jp"/><path fill="url(#ijmbzwd)" class="qhwpq86jp"/><path fill="url(#ik8dO5d)" class="qhwpq86jp"/><path fill="url(#iOIxfWb)" class="qhwpq86jp"/><g filter="url(#i8wBXqc)"><path fill="url(#igLlVGd)" class="os2--67ch"/><path fill="url(#iG7Z8Cb)" class="os2--67ch"/><path fill="url(#iNV6RPg)" class="os2--67ch"/></g><path fill="url(#ijNBA5q)" class="is0mumb7t"/><path fill="url(#irLKFAe)" class="is0mumb7t"/><g filter="url(#iU6FVqH)"><path fill="url(#ie1pRDd)" class="hhm25-7th"/><path fill="url(#iNEb1vd)" class="hhm25-7th"/></g><g filter="url(#iTTnz2b)"><path class="ikldp2gym"/><path fill="url(#ifCCYDc)" class="cwb0r_h6f"/><path fill="url(#i0z8hCd)" class="cwb0r_h6f"/><path fill="url(#iya3OLc)" class="cwb0r_h6f"/><path fill="url(#igcNzGc)" class="cwb0r_h6f"/></g><path fill="url(#iY1V6pc)" class="rur2bzbtn"/><path fill="url(#i18brXc)" class="rur2bzbtn"/><path fill="url(#iou4tgR)" class="j6h1y6bng"/><path fill="url(#iyZvm1c)" class="j6h1y6bng"/><path fill="url(#iIZPPcV)" class="nbxdhj0eb"/><path fill="url(#iQU0G0d)" class="nbxdhj0eb"/><path fill="url(#iEzrKsc)" class="nbxdhj0eb"/><path fill="url(#iAjq5Gc)" class="nbxdhj0eb"/><path fill="url(#i3m8OeJ)" class="nbxdhj0eb"/><path fill="url(#iYnym2c)" class="ugkic7bua"/><path fill="url(#iVvatdD)" class="h5mt3lbiq"/><path fill="url(#iAvm1pb)" class="h5mt3lbiq"/><path fill="url(#i1Yaffq)" class="h5mt3lbiq"/><g filter="url(#iWe4Y2c)"><path stroke="url(#i3v0fXd)" class="t8a4fabjw"/></g><path fill="url(#iJUhPWb)" class="hqvdynb_q"/><path fill="url(#i4QmUvb)" class="hqvdynb_q"/><path fill="url(#ix4EwOe)" class="so0ia5buv"/><g filter="url(#iUEtmbc)"><path fill="url(#iGs6Iwe)" class="t_f1esbmg"/><path fill="url(#i1UffvO)" class="t_f1esbmg"/><path fill="url(#iIALgDW)" class="t_f1esbmg"/></g><path fill="url(#icqxigE)" class="iuf67u4ou"/><path fill="url(#iKv6xnc)" class="iuf67u4ou"/><path fill="url(#iA8hCRd)" class="iuf67u4ou"/><path class="r-i_cwi0k"/><path fill="url(#iZsBu2d)" class="gag5a5b9h"/><path fill="url(#iCiBASc)" class="gag5a5b9h"/><path fill="url(#iTBbLYj)" class="gag5a5b9h"/><path class="ifdxqh5pu"/><path fill="url(#iFFeume)" class="rk4iehbch"/><path fill="url(#i9rp7BF)" class="rk4iehbch"/><path fill="url(#i2co7Ob)" class="rk4iehbch"/><path fill="url(#iMcPdYc)" class="rk4iehbch"/><path fill="url(#iFnENoe)" class="e2dpq2b7y"/><path fill="url(#ieGaBme)" class="e2dpq2b7y"/><path fill="url(#i1y2VCd)" class="e2dpq2b7y"/><path fill="url(#igt9eoe)" class="e2dpq2b7y"/><path fill="url(#iCTaQNd)" class="mjq_0syxs"/><path fill="url(#in0a6Oe)" class="mjq_0syxs"/><path fill="url(#ipQlMye)" class="mjq_0syxs"/><path fill="url(#iv5Uv0h)" class="gd5jxab6n"/><path fill="url(#i20iJAv)" class="gd5jxab6n"/><path fill="url(#iQOe0gd)" class="gd5jxab6n"/><path fill="url(#ijBxvxh)" class="gd5jxab6n"/><g filter="url(#iwagutd)"><path stroke="url(#iUNZb5w)" class="knli9ccze"/></g><defs><radialGradient id="iTef7uc" cx="0" cy="0" r="1" gradientTransform="rotate(79.088 -3.16 13.073)scale(4.49896 2.71048)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iwlK4we" cx="0" cy="0" r="1" gradientTransform="matrix(1.06465 5.52245 -5.75263 1.10902 14.824 12.918)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iMFs26d" cx="0" cy="0" r="1" gradientTransform="rotate(116.706 1.087 8.995)scale(2.05214 1.99252)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iMeodOc" cx="0" cy="0" r="1" gradientTransform="matrix(.0169 2.58122 -2.68786 .0176 9.731 9.539)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iMJkMsa" cx="0" cy="0" r="1" gradientTransform="rotate(51.693 .383 12.228)scale(2.40368 4.57895)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="i9G7aPe" cx="0" cy="0" r="1" gradientTransform="rotate(121.599 8.249 7.277)scale(1.65274 2.30968)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="irmpGOd" cx="0" cy="0" r="1" gradientTransform="rotate(152.867 9.82 6.884)scale(1.93841 4.21773)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iDgmYye" cx="0" cy="0" r="1" gradientTransform="rotate(-101.263 8.17 -1.099)scale(1.3875 .45492)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="ifW2YHe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.31288 9.77452 -12.04491 -6.54693 14.864 8.586)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="j3monpcls"/><stop offset=".969" class="dqxdj-bqs"/></radialGradient><radialGradient id="ioqnJKd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1681 -.23486 .3514 -6.2365 12.633 16.393)" gradientUnits="userSpaceOnUse"><stop class="n34issb-z"/><stop offset="1" class="a0d1ktmmz"/></radialGradient><radialGradient id="iL5vqfb" cx="0" cy="0" r="1" gradientTransform="rotate(-67.521 21.748 -5.234)scale(1.84247 4.97045)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="bqexp4b8k"/><stop offset="1" class="k7gdagbzg"/></radialGradient><radialGradient id="iKorEZd" cx="0" cy="0" r="1" gradientTransform="matrix(2.28125 .78127 -1.01508 2.96395 19.584 13.907)" gradientUnits="userSpaceOnUse"><stop offset=".453" class="pl9t-3cpb"/><stop offset="1" class="md8cpi4nz"/></radialGradient><radialGradient id="iyHj6HP" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96876 2.59374 -2.6014 -2.97753 11.99 14.219)" gradientUnits="userSpaceOnUse"><stop class="c_5md4big"/><stop offset="1" class="mtaos9b-c"/></radialGradient><radialGradient id="izzyc2c" cx="0" cy="0" r="1" gradientTransform="matrix(2.19471 3.52472 -6.20084 3.86104 16.045 15.788)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="wcbvx-n_a"/><stop offset="1" class="sbx2zkbbn"/></radialGradient><radialGradient id="iIm56Pe" cx="0" cy="0" r="1" gradientTransform="matrix(2.25116 -1.5972 1.9501 2.74855 18.506 10.474)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iJ2TO3j" cx="0" cy="0" r="1" gradientTransform="rotate(-31.209 27.714 -28.958)scale(1.31703)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iD9L0Vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06475 .20527 -.19635 -1.0185 9.792 11.702)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iAvxMrb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.87378 4.21576 -5.64272 -7.86194 17.15 9.732)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iSTm3lb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87812 1.50934 -1.28057 -1.59345 16.332 10.607)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="igb3eKb" cx="0" cy="0" r="1" gradientTransform="matrix(.05655 -4.16983 5.29073 .07175 13.45 17.418)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iIJ3Ise" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56246 7.5 -10.92573 -2.27614 15.49 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".438" class="c1gn9mbdd"/><stop offset=".976" class="jy466vbch"/></radialGradient><radialGradient id="izFykmd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.08878 2.52266 -4.34325 -8.76131 15.254 11.8)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="inykMqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33521 .25741 -.8474 -4.39557 19.57 10.364)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="ix9OIPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1595 -2.29513 1.3133 -.66348 15.435 11.909)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="i7khXok" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59835 4.7574 -2.07485 -1.13322 10.398 4.438)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iUC6aic" cx="0" cy="0" r="1" gradientTransform="rotate(133.546 4.107 4.727)scale(3.84959 1.90252)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iKgAqOc" cx="0" cy="0" r="1" gradientTransform="rotate(104.718 6.39 6.853)scale(5.10034 7.24163)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iM8oh7z" cx="0" cy="0" r="1" gradientTransform="matrix(-.30252 3.45965 -7.25033 -.63398 15.591 3.52)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iN3IjTc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62302 -5.7581 5.14739 -4.1327 15.32 9.361)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="ivgLKeb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11567 .19991 -.19309 -.11172 17.359 10.011)" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></radialGradient><radialGradient id="ihfF2yb" cx="0" cy="0" r="1" gradientTransform="matrix(-.11567 .19991 -.19309 -.11172 13.04 10.772)" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></radialGradient><radialGradient id="iU0YlPb" cx="0" cy="0" r="1" gradientTransform="matrix(.28711 3.40925 -4.12958 .34777 8.64 20.904)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="v442oubmz"/><stop offset="1" class="p_ew-572a"/></radialGradient><radialGradient id="iZhLZXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.39 19.622)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="m0rm-m-qv"/><stop offset="1" class="wi8a08bum"/></radialGradient><radialGradient id="ijmbzwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.598 30.279)" gradientUnits="userSpaceOnUse"><stop class="wagk6dfaq"/><stop offset="1" class="hfzkti_ts"/></radialGradient><radialGradient id="iOIxfWb" cx="0" cy="0" r="1" gradientTransform="rotate(86.386 -7.35 15.764)scale(1.85287 2.95057)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="k5vtewq9k"/><stop offset="1" class="z1zjblq2q"/></radialGradient><radialGradient id="igLlVGd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 25.06)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iG7Z8Cb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.922 10.284)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iNV6RPg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 25.997)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="ijNBA5q" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.328 21.341)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="ie1pRDd" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.04 12.861)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="iNEb1vd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.779)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="ifCCYDc" cx="0" cy="0" r="1" gradientTransform="matrix(2.60938 1.92187 -.5328 .7234 17.156 26.418)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="dubz53-6i"/><stop offset="1" class="fc5g8ruvh"/></radialGradient><radialGradient id="i0z8hCd" cx="0" cy="0" r="1" gradientTransform="matrix(3.90625 0 0 .92188 13.39 28.528)" gradientUnits="userSpaceOnUse"><stop class="dubz53-6i"/><stop offset="1" class="fc5g8ruvh"/></radialGradient><radialGradient id="iya3OLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.265 29.215)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="b7isyt1qh"/><stop offset="1" class="mmnqgv5yf"/></radialGradient><radialGradient id="igcNzGc" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.282 40.57)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="vw31h25pz"/><stop offset="1" class="qdgjyci2c"/></radialGradient><radialGradient id="iY1V6pc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02344 -.68462 0 19.607 28.297)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="rntqzsbvm"/><stop offset="1" class="kn6547brm"/></radialGradient><radialGradient id="iyZvm1c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.5625 1.81252 -.47277 -2.23342 29.083 26.75)" gradientUnits="userSpaceOnUse"><stop class="o7yf4tl0b"/><stop offset="1" class="x9s6ceaht"/></radialGradient><radialGradient id="iIZPPcV" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.766 20.153)" gradientUnits="userSpaceOnUse"><stop class="h0nz-rbjw"/><stop offset="1" class="kfbnffbzx"/></radialGradient><radialGradient id="iEzrKsc" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 -2.9 13.177)scale(2.10677 2.16117)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="jz746dbzd"/><stop offset="1" class="dzs1febsk"/></radialGradient><radialGradient id="iAjq5Gc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.125)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="cwu2h0blp"/><stop offset="1" class="f9-tluqmj"/></radialGradient><radialGradient id="i3m8OeJ" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.763)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yyn9swbvh"/><stop offset="1" class="pviihufyn"/></radialGradient><radialGradient id="i1Yaffq" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.754)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="i3v0fXd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.295)" gradientUnits="userSpaceOnUse"><stop class="ut4bgvb0y"/><stop offset="1" class="gngaedcou"/></radialGradient><radialGradient id="i4QmUvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.094)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="i1UffvO" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.267 34.394)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="iKv6xnc" cx="0" cy="0" r="1" gradientTransform="rotate(53.038 -14.558 16.943)scale(3.87188 5.62527)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="k2dydacno"/><stop offset="1" class="x5utb7s2j"/></radialGradient><radialGradient id="iA8hCRd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82813 3.21874 -1.86644 -1.06007 10.124 17.84)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="b8excebxy"/><stop offset="1" class="hnp1-q05e"/></radialGradient><radialGradient id="iCiBASc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08606 .48023 -.48372 -1.09394 14.414 16.56)" gradientUnits="userSpaceOnUse"><stop class="wzg23bc3x"/><stop offset="1" class="tp27ezb_z"/></radialGradient><radialGradient id="iTBbLYj" cx="0" cy="0" r="1" gradientTransform="rotate(-94.844 15.143 2.855)scale(.92518 1.63477)" gradientUnits="userSpaceOnUse"><stop class="ag6qdsamj"/><stop offset="1" class="mbdelibus"/></radialGradient><radialGradient id="i9rp7BF" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 -.92074 2.28193 .4647 12.109 19.183)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="rvlxae6dq"/><stop offset="1" class="wxdz3ub6w"/></radialGradient><radialGradient id="i2co7Ob" cx="0" cy="0" r="1" gradientTransform="rotate(76.139 -4.48 16.447)scale(2.47842 4.24901)" gradientUnits="userSpaceOnUse"><stop offset=".749" class="s4yd9bb_d"/><stop offset="1" class="zjrohm9wd"/></radialGradient><radialGradient id="iMcPdYc" cx="0" cy="0" r="1" gradientTransform="rotate(150.154 4.482 10.715)scale(1.09887 .84775)" gradientUnits="userSpaceOnUse"><stop offset=".137" class="vo33qub4y"/><stop offset="1" class="r5v36mb_f"/></radialGradient><radialGradient id="iFnENoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.374 19.169)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="l4z1-1b1s"/><stop offset="1" class="ri1yzijvp"/></radialGradient><radialGradient id="ieGaBme" cx="0" cy="0" r="1" gradientTransform="rotate(-41.07 30.178 -1.847)scale(1.45077 3.00819)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="xh9neyo3y"/><stop offset="1" class="bcsnf_bcy"/></radialGradient><radialGradient id="i1y2VCd" cx="0" cy="0" r="1" gradientTransform="rotate(-84.677 17.484 4.162)scale(1.26326 3.54275)" gradientUnits="userSpaceOnUse"><stop class="wlb38ob3l"/><stop offset="1" class="en81-_tdq"/></radialGradient><radialGradient id="igt9eoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.062 19.075)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="f8laadbbd"/><stop offset="1" class="ncukxx3rx"/></radialGradient><radialGradient id="iCTaQNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33928 1.42858 -2.02518 -1.89858 10.868 19.863)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="guytmftkt"/></radialGradient><radialGradient id="in0a6Oe" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 -.98437 4.71032 .82244 10.437 22.278)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="h3osul2wz"/><stop offset="1" class="iwn92ct1p"/></radialGradient><radialGradient id="ipQlMye" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -.875 1.67102 3.163 8.203 21.387)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="ho57by_ce"/><stop offset="1" class="eq0h2gj5z"/></radialGradient><radialGradient id="i20iJAv" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .926 15.938)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iQOe0gd" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .808 16.413)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ijBxvxh" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.348 10.43)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iUNZb5w" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.094)" gradientUnits="userSpaceOnUse"><stop class="zbwshaccu"/><stop offset="1" class="piz2rbc3b"/></radialGradient><linearGradient id="iYWGHCd" x1="17.741" x2="13.132" y1="3.022" y2="17.731" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iiJISUd" x1="18.565" x2="17.972" y1="17.772" y2="16.079" gradientUnits="userSpaceOnUse"><stop offset=".354" class="kc6u0dx1c"/><stop offset="1" class="z6eg73bhs"/></linearGradient><linearGradient id="iaX54De" x1="19.224" x2="12.336" y1="18.883" y2="30.56" gradientUnits="userSpaceOnUse"><stop class="q9xywcr7e"/><stop offset="1" class="jvlxembhy"/></linearGradient><linearGradient id="ixTDisb" x1="14.615" x2="17.595" y1="17.188" y2="18.157" gradientUnits="userSpaceOnUse"><stop offset=".036" class="zfchjpbgt"/><stop offset=".888" class="d3qm7wbdo"/></linearGradient><linearGradient id="iWDNyFe" x1="8.195" x2="11.128" y1="12.1" y2="11.535" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iHVL7sd" x1="14.807" x2="14.294" y1="12.832" y2="10.173" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="isTFOQb" x1="13.624" x2="14.491" y1="12.276" y2="12.216" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="i6JhwGi" x1="14.825" x2="14.708" y1="12.923" y2="12.318" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="ijLjOYT" x1="14.234" x2="14.491" y1="9.98" y2="11.111" gradientUnits="userSpaceOnUse"><stop class="xn8v49gcn"/><stop offset="1" class="nqfu_dp4n"/></linearGradient><linearGradient id="iNCMm6d" x1="14.42" x2="14.702" y1="14.776" y2="13.825" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iDOELgb" x1="10.367" x2="11.15" y1="5.22" y2="6.378" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="ilGiRdd" x1="17.256" x2="15.788" y1="10.351" y2="11.125" gradientUnits="userSpaceOnUse"><stop offset=".558" class="y8a_xmbaj"/><stop offset="1" class="l_uz_8har"/></linearGradient><linearGradient id="iBQye3c" x1="11.166" x2="13.392" y1="11.283" y2="10.863" gradientUnits="userSpaceOnUse"><stop offset=".558" class="htafuph4g"/><stop offset="1" class="l_uz_8har"/><stop offset="1" class="tv-41kbsn"/></linearGradient><linearGradient id="i2650Kd" x1="15.348" x2="17.535" y1="10.443" y2="10.595" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></linearGradient><linearGradient id="iXFFLLb" x1="11.029" x2="13.216" y1="11.204" y2="11.355" gradientUnits="userSpaceOnUse"><stop class="xllr1s1ox"/><stop offset="1" class="y3ozgf0rs"/></linearGradient><linearGradient id="i30dAVb" x1="12.978" x2="11.048" y1="10.171" y2="9.896" gradientUnits="userSpaceOnUse"><stop offset=".329" class="qbyjgz8xo"/><stop offset="1" class="b1zy4ibbj"/></linearGradient><linearGradient id="iykhv6b" x1="17.345" x2="14.081" y1="9.391" y2="8.307" gradientUnits="userSpaceOnUse"><stop offset=".329" class="xoq3wtioq"/><stop offset="1" class="pij34sbcm"/></linearGradient><linearGradient id="iHKGhFb" x1="9.109" x2="3.64" y1="26.591" y2="25.122" gradientUnits="userSpaceOnUse"><stop class="g1c-6jb6y"/><stop offset="1" class="hkdf97w8c"/></linearGradient><linearGradient id="iLeXJLY" x1="3.333" x2="5.328" y1="26.219" y2="26.872" gradientUnits="userSpaceOnUse"><stop class="da95trp0k"/><stop offset="1" class="feoz1vgta"/></linearGradient><linearGradient id="ik8dO5d" x1="9.229" x2="8.836" y1="28.609" y2="28.484" gradientUnits="userSpaceOnUse"><stop class="rehc034in"/><stop offset="1" class="psvt8ubmu"/></linearGradient><linearGradient id="irLKFAe" x1="24.609" x2="24.296" y1="25.622" y2="24.154" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="i18brXc" x1="19.395" x2="19.395" y1="26.911" y2="27.75" gradientUnits="userSpaceOnUse"><stop class="y-ymn0bhn"/><stop offset="1" class="he69lvb0i"/></linearGradient><linearGradient id="iou4tgR" x1="26.546" x2="26.984" y1="27.059" y2="30.778" gradientUnits="userSpaceOnUse"><stop class="tnk2b_bjh"/><stop offset="1" class="p40qzpbtf"/></linearGradient><linearGradient id="iQU0G0d" x1="5.833" x2="6.912" y1="20.031" y2="21.734" gradientUnits="userSpaceOnUse"><stop class="j4n7g28_w"/><stop offset="1" class="laie_nbgc"/></linearGradient><linearGradient id="iYnym2c" x1="12.351" x2="11.964" y1="20.542" y2="18.56" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iVvatdD" x1="16.078" x2="15.296" y1="18.34" y2="21.327" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iAvm1pb" x1="15.205" x2="15.428" y1="21.547" y2="20.656" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iJUhPWb" x1="14.953" x2="13.828" y1="17.575" y2="21.904" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="ix4EwOe" x1="15.265" x2="14.156" y1="17.95" y2="17.591" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iGs6Iwe" x1="14.453" x2="13.223" y1="17.466" y2="22.216" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iIALgDW" x1="12.549" x2="12.768" y1="21.281" y2="20.203" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="icqxigE" x1="8.421" x2="8.964" y1="16.966" y2="21.466" gradientUnits="userSpaceOnUse"><stop class="w5h00ebej"/><stop offset="1" class="ix3yrkb0h"/></linearGradient><linearGradient id="iZsBu2d" x1="9.859" x2="11.234" y1="16.747" y2="16.567" gradientUnits="userSpaceOnUse"><stop offset=".136" class="uqhi6sb2j"/><stop offset="1" class="qynlkiyit"/></linearGradient><linearGradient id="iFFeume" x1="9.555" x2="11.109" y1="17.669" y2="17.669" gradientUnits="userSpaceOnUse"><stop class="bmz8w2byx"/><stop offset="1" class="w6wkm7xob"/></linearGradient><linearGradient id="iv5Uv0h" x1="16.521" x2="15.937" y1="18.841" y2="21.341" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="iITAOYb" width="15.886" height="16.078" x="6.909" y="2.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="iECXBbd" width="3.349" height="3.25" x="8.148" y="10.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="iOQjrPe" width="3.249" height="3.5" x="17.578" y="8.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="i7utglc" width="3.169" height="3.169" x="17.618" y="8.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".25"/></filter><filter id="iFjVvNd" width="2.669" height="2.669" x="8.457" y="10.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".125"/></filter><filter id="iyWGaWc" width="10.672" height="10.58" x="8.984" y="6.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="ilVbsGe" width="2.88" height="3.763" x="13.13" y="9.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".25"/></filter><filter id="iTabyzb" width="2.38" height="3.252" x="13.514" y="9.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".125"/></filter><filter id="iFFKsrc" width="2.38" height="3.252" x="13.454" y="9.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".125"/></filter><filter id="ilT5qub" width="3.678" height="1.84" x="13.131" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".05"/></filter><filter id="iN0YCpf" width="4.751" height="5.717" x="6.973" y="4.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".375"/></filter><filter id="ilSCo6d" width="9.581" height="4.74" x="9.901" y="2.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".125"/></filter><filter id="izD42ub" width="1.467" height="2.19" x="10.001" y="4.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".125"/></filter><filter id="iHE0k2b" width="2.456" height="1.191" x="15.238" y="9.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".075"/></filter><filter id="iQcsh1j" width="2.456" height="1.191" x="10.918" y="10.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".075"/></filter><filter id="i1luzqx" width="3.71" height="2.424" x="10.286" y="8.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".3"/></filter><filter id="iSq4Wwj" width="3.532" height="2.726" x="14.774" y="7.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".3"/></filter><filter id="inHS93c" width="2.381" height="1.388" x="10.255" y="8.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.27451 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="iYydDib" width="2.505" height=".892" x="15.582" y="7.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.27451 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="itBZvyO" width="2.312" height=".771" x="15.606" y="7.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".1"/></filter><filter id="ifkcfSo" width="2.18" height="1.26" x="10.248" y="8.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".1"/></filter><filter id="i8wBXqc" width="11.192" height="8.359" x="11.466" y="22.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="iU6FVqH" width="7.407" height="8.444" x="19.048" y="18.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="iTTnz2b" width="8.208" height="4.667" x="12.416" y="25.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.592157 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="iWe4Y2c" width="3.456" height="1.701" x="7.381" y="22.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".1"/></filter><filter id="iUEtmbc" width="4.309" height="4.662" x="11.043" y="16.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3530"/></filter><filter id="iwagutd" width="3.647" height="2.753" x="6.263" y="19.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3530" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-feeding-baby" /></template>
<style>
.a0d1ktmmz {
  stop-color: var(--svg-color--bb5d1b, #BB5D1B);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.abx2fsbum {
  stroke: var(--svg-color--b45c48, #B45C48);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.129 8.633c-.335-.016-1.122.176-1.58.658");
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ag6qdsamj {
  stop-color: var(--svg-color--caa166, #CAA166);
}

.atl_u83kj {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m13.986 10.665l-.353 1.816a.544.544 0 0 0 .65.594l.78-.15a.546.546 0 0 0 .382-.793l-.852-1.584c-.185-.351-.56-.279-.607.117");
}

.b1zy4ibbj {
  stop-color: var(--svg-color--f2962e, #F2962E);
  stop-opacity: 0;
}

.b7isyt1qh {
  stop-color: var(--svg-color--eb861b, #EB861B);
}

.b8excebxy {
  stop-color: var(--svg-color--ffb725, #FFB725);
}

.bcsnf_bcy {
  stop-color: var(--svg-color--ffb425, #FFB425);
  stop-opacity: 0;
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bmz8w2byx {
  stop-color: var(--svg-color--f6b12c, #F6B12C);
}

.bqexp4b8k {
  stop-color: var(--svg-color--ce6826, #CE6826);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c_5md4big {
  stop-color: var(--svg-color--b75d1d, #B75D1D);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c0tk_hbnc {
  fill: var(--svg-color--a64023, #A64023);
  d: path("m10.71 9.518l-.004.004a.27.27 0 0 1-.361-.404h.001l.003-.003l.008-.007a2 2 0 0 1 .132-.105a3 3 0 0 1 .376-.239c.316-.172.77-.353 1.296-.362a.27.27 0 0 1 .008.542a2.3 2.3 0 0 0-1.045.296a3 3 0 0 0-.414.278");
}

.c1gn9mbdd {
  stop-color: var(--svg-color--e8a930, #E8A930);
  stop-opacity: 0;
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cnsrceb_i {
  d: path("M12.33 3.203c-1.17-.031-2.143 1.396-2.18 1.834c2.221 3.294 4.502 2.5 7.05 1.708c1.526-.474 1.832.204 2.032.522c-1.208-3.938-4.234-3.992-6.901-4.064");
}

.cqjhltbpm {
  d: path("M19.51 11.483a1.624 1.624 0 1 0-.615-3.19a1.624 1.624 0 0 0 .615 3.19");
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cwb0r_h6f {
  d: path("M17.18 25.96a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.cwu2h0blp {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d3qm7wbdo {
  stop-color: var(--svg-color--ebbb36, #EBBB36);
}

.da95trp0k {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dqxdj-bqs {
  stop-color: var(--svg-color--b2614c, #B2614C);
}

.dubz53-6i {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dy155dxdg {
  stop-color: var(--svg-color--33c966, #33C966);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dypnkmnss {
  stop-color: var(--svg-color--33c966, #33C966);
  stop-opacity: 0;
}

.dzs1febsk {
  stop-color: var(--svg-color--6f409a, #6F409A);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e2dpq2b7y {
  d: path("M8.521 18.758a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.304.237 1 .79 1.363 1.083c.446.36.372.961.043 1.316c-.276.298-.751.241-.93.149l-2.097-1.313c-.055-.312-.235-.562-.48-.636c-.247-.075-.403-.133-.415-.329");
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.ed-k8b0de {
  d: path("m9.134 10.532l.012-.003l-.061-.26l-.069-.302c-.16-.945.318-1.415.528-1.581l.047-.03l.047-.03c.482-.345.827-.852.943-1.451l.045-.208a.266.266 0 0 1 .447-.139a3.9 3.9 0 0 0 3.482 1.05l3.192-.616c.178-.034 1.089-.12 1.38 1.104l.47 3.069c.413 2.801-1.397 5.085-4.045 5.595s-5.177-.936-5.835-3.69z");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.en81-_tdq {
  stop-color: var(--svg-color--ffc52d, #FFC52D);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eq0h2gj5z {
  stop-color: var(--svg-color--fda537, #FDA537);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f8laadbbd {
  stop-color: var(--svg-color--df970a, #DF970A);
}

.f9-tluqmj {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
  stop-opacity: 0;
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fc5g8ruvh {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
  stop-opacity: 0;
}

.feoz1vgta {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
  stop-opacity: 0;
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fn9fyz7-m {
  d: path("M17.323 9.795c-.075.01-.132.057-.179.122c-.15.245-.394.423-.695.48a.95.95 0 0 1-.808-.217a.27.27 0 0 0-.206-.056a.25.25 0 0 0-.113.441c.329.273.77.404 1.221.32a1.5 1.5 0 0 0 1.043-.723c.103-.179-.056-.404-.263-.367");
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.g1c-6jb6y {
  stop-color: var(--svg-color--8a4fe4, #8A4FE4);
}

.gag5a5b9h {
  d: path("M10.099 16.74c.356.124.482.33.515.452l.446.391l2.291.362a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.014-2.687.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gd5jxab6n {
  d: path("m15.454 21.044l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.033l.315.084a.485.485 0 0 0 .253-.936l-.304-.082a.13.13 0 0 1-.097-.11l-.069-.439a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.gngaedcou {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
  stop-opacity: 0;
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.guytmftkt {
  stop-color: var(--svg-color--fba335, #FBA335);
}

.h0nz-rbjw {
  stop-color: var(--svg-color--7f5499, #7F5499);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h3osul2wz {
  stop-color: var(--svg-color--cd7a48, #CD7A48);
}

.h5mt3lbiq {
  d: path("m15.53 18.144l.554.159a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.103l-.555-.16z");
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.ha9szvesl {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M9.997 12.767a1.084 1.084 0 1 0-.41-2.13a1.084 1.084 0 0 0 .41 2.13");
}

.he69lvb0i {
  stop-color: var(--svg-color--755994, #755994);
  stop-opacity: 0;
}

.hf6jj6p6x {
  d: path("M8.417 5.785c.51-.667 1.397-.844 1.912-.851l.646 1.202c-.262.01-.473.143-.628.363c-.211 1.336-1.632 2.325-2.315 2.652c-.435-1.45-.496-2.214.385-3.366");
}

.hfzkti_ts {
  stop-color: var(--svg-color--8e5de1, #8E5DE1);
  stop-opacity: 0;
}

.hgk_o7b-f {
  d: path("m13.97 10.526l-.203 1.787a.544.544 0 0 0 .65.594l.78-.15a.546.546 0 0 0 .382-.793l-.852-1.584c-.184-.352-.711-.25-.758.146");
}

.hhm25-7th {
  d: path("M21.575 24.218a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.hkdf97w8c {
  stop-color: var(--svg-color--804ec1, #804EC1);
}

.hnp1-q05e {
  stop-color: var(--svg-color--e1a038, #E1A038);
  stop-opacity: 0;
}

.ho57by_ce {
  stop-color: var(--svg-color--e3992c, #E3992C);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hqvdynb_q {
  d: path("m11.939 16.313l3.172.883c.43.125.744.559.627.96l-.9 3.086c-.115.396-.532.607-1.024.474l-3.129-.883z");
}

.htafuph4g {
  stop-color: var(--svg-color--7b2f2a, #7B2F2A);
}

.ibm7k8bfw {
  d: path("M12.974 10.556c-.075.01-.132.057-.179.122c-.15.244-.394.423-.695.48a1 1 0 0 1-.808-.207a.24.24 0 0 0-.206-.057a.25.25 0 0 0-.113.442c.329.272.77.404 1.221.32a1.5 1.5 0 0 0 1.043-.724c.103-.179-.057-.404-.263-.376");
}

.ifdxqh5pu {
  fill: var(--svg-color--ffc225, #FFC225);
  d: path("M9.67 17.661c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.ikldp2gym {
  fill: var(--svg-color--ffb926, #FFB926);
  d: path("M17.18 25.96a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.is0mumb7t {
  d: path("M23.445 27.438a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iuf67u4ou {
  d: path("M8.13 17.52c1.031-1.085 1.92-1.37 2.32-1.375l.797.868l-.93 3.515c-.179.315-.563.996-.695 1.153c-.164.195-.734.63-1.765.238c-.888-.338-1.15-.899-1.176-1.149c.234-1.167.649-2.357 1.45-3.25");
}

.iwn92ct1p {
  stop-color: var(--svg-color--fda837, #FDA837);
  stop-opacity: 0;
}

.ix3yrkb0h {
  stop-color: var(--svg-color--e49627, #E49627);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j3monpcls {
  stop-color: var(--svg-color--db7725, #DB7725);
  stop-opacity: 0;
}

.j4n7g28_w {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
}

.j6h1y6bng {
  d: path("M20.615 26.055c1.598-.23 4.567-.808 6.543-1.27c1.522-.262 2.641 1.204 2.641 2.782c0 1.37-1.022 2.236-1.747 2.618a.86.86 0 0 1-.403.093h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jnie2pbod {
  d: path("M10.886 9.364c1.292-.247 2.246.338 2.51 1.057c-1.21-.317-1.945-.11-2.356.11z");
}

.jvlxembhy {
  stop-color: var(--svg-color--7d49d2, #7D49D2);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.jy466vbch {
  stop-color: var(--svg-color--a96a3d, #A96A3D);
}

.jz746dbzd {
  stop-color: var(--svg-color--6f409a, #6F409A);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k2dydacno {
  stop-color: var(--svg-color--e69828, #E69828);
  stop-opacity: 0;
}

.k3uuwuaug {
  d: path("M15.488 10.359c.122.114.486.33.96.28c.473-.052.889-.51.995-.684");
}

.k5vtewq9k {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
}

.k7gdagbzg {
  stop-color: var(--svg-color--ce6826, #CE6826);
  stop-opacity: 0;
}

.k9qsgnves {
  fill: var(--svg-color--a64023, #A64023);
  fill-rule: evenodd;
  d: path("m17.708 7.765l-.092.254za.27.27 0 0 1-.185.509l-.005-.002a1 1 0 0 0-.123-.036a3 3 0 0 0-.365-.068a2.3 2.3 0 0 0-1.08.113a.27.27 0 0 1-.194-.506c.491-.187.98-.188 1.338-.145a3.3 3.3 0 0 1 .599.13l.01.003l.003.001z");
}

.kc6u0dx1c {
  stop-color: var(--svg-color--d06e54, #D06E54);
}

.kfbnffbzx {
  stop-color: var(--svg-color--7a45b3, #7A45B3);
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kn6547brm {
  stop-color: var(--svg-color--8259a4, #8259A4);
}

.knli9ccze {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.028c-.206.433-.319 1.449.875 2.055s1.992.148 2.242-.156");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l_uz_8har {
  stop-color: var(--svg-color--c45011, #C45011);
}

.l4z1-1b1s {
  stop-color: var(--svg-color--ffd23e, #FFD23E);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.laie_nbgc {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
  stop-opacity: 0;
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.m_15mey2s {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M19.408 10.954a1.084 1.084 0 1 0-.41-2.13a1.084 1.084 0 0 0 .41 2.13");
}

.m0rm-m-qv {
  stop-color: var(--svg-color--785191, #785191);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbdelibus {
  stop-color: var(--svg-color--caa166, #CAA166);
  stop-opacity: 0;
}

.md8cpi4nz {
  stop-color: var(--svg-color--db8527, #DB8527);
  stop-opacity: 0;
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mjq_0syxs {
  d: path("M8.857 21.208c-.315.22-.723.21-.906-.11c-.391-.947.72-1.579 1.5-1.597c1.167-.027 1.75.629 1.937 1.12c.188.493.227 1.478-.672 1.54c-.803.056-.847-.5-.98-.742s-.594-.41-.879-.211");
}

.mmnqgv5yf {
  stop-color: var(--svg-color--ffba27, #FFBA27);
  stop-opacity: 0;
}

.mtaos9b-c {
  stop-color: var(--svg-color--b75d1d, #B75D1D);
  stop-opacity: 0;
}

.myswpvabz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.01 13.947c-.516.1-1.025.069-1.475-.07c-.153-.046-.272.144-.16.256a1.95 1.95 0 0 0 3.222-.62c.061-.152-.118-.279-.244-.18a3.04 3.04 0 0 1-1.343.614Z");
}

.n34issb-z {
  stop-color: var(--svg-color--8c450c, #8C450C);
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.nbxdhj0eb {
  d: path("M10.214 21.965c-.284.88-1.448 1.292-2.6.92c-1.152-.371-1.793-1.177-1.573-2.266c.18-.888.884-1.75 2.738-1.24c1.153.372 1.719 1.706 1.435 2.586");
}

.ncukxx3rx {
  stop-color: var(--svg-color--ffd03a, #FFD03A);
  stop-opacity: 0;
}

.nevorxyqz {
  d: path("M11.168 11.12c.123.114.486.33.96.28c.473-.052.89-.51.996-.684");
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nm20ljqyc {
  d: path("m13.91 10.333l-.203 1.787a.544.544 0 0 0 .65.593l.78-.15a.546.546 0 0 0 .382-.793l-.852-1.583c-.184-.352-.711-.25-.758.146");
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.nqfu_dp4n {
  stop-color: var(--svg-color--f8c640, #F8C640);
  stop-opacity: 0;
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o7yf4tl0b {
  stop-color: var(--svg-color--b087f9, #B087F9);
}

.os2--67ch {
  d: path("M21.835 24.298c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.ozqrj60zd {
  d: path("M9.997 12.767a1.084 1.084 0 1 0-.41-2.13a1.084 1.084 0 0 0 .41 2.13");
}

.p_ew-572a {
  stop-color: var(--svg-color--8152c8, #8152C8);
  stop-opacity: 0;
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p40qzpbtf {
  stop-color: var(--svg-color--985ef1, #985EF1);
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.pij34sbcm {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
  stop-opacity: 0;
}

.piz2rbc3b {
  stop-color: var(--svg-color--875ab4, #875AB4);
  stop-opacity: 0;
}

.pl9t-3cpb {
  stop-color: var(--svg-color--db8527, #DB8527);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.psvt8ubmu {
  stop-color: var(--svg-color--8356d1, #8356D1);
  stop-opacity: 0;
}

.pviihufyn {
  stop-color: var(--svg-color--784787, #784787);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q9xywcr7e {
  stop-color: var(--svg-color--9c6ed3, #9C6ED3);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qbyjgz8xo {
  stop-color: var(--svg-color--ee9627, #EE9627);
}

.qdgjyci2c {
  stop-color: var(--svg-color--e38f1d, #E38F1D);
  stop-opacity: 0;
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qhwpq86jp {
  d: path("m2.201 30.279l2.93-9.157c.351-1.414 2.07-2.103 3.65-1.613s2.49 2.332 2.006 3.691l-2.216 7.08z");
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.qynlkiyit {
  stop-color: var(--svg-color--f5b12d, #F5B12D);
  stop-opacity: 0;
}

.r-i_cwi0k {
  fill: var(--svg-color--ffc126, #FFC126);
  d: path("M10.099 16.74c.356.124.482.33.515.452l.446.391l2.291.362a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.014-2.687.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.r5v36mb_f {
  stop-color: var(--svg-color--ffe247, #FFE247);
  stop-opacity: 0;
}

.rehc034in {
  stop-color: var(--svg-color--8356d1, #8356D1);
}

.ri1yzijvp {
  stop-color: var(--svg-color--ffbe24, #FFBE24);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rk4iehbch {
  d: path("M9.67 17.661c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.61");
}

.rntqzsbvm {
  stop-color: var(--svg-color--925cbe, #925CBE);
}

.rur2bzbtn {
  d: path("M18.998 27.061a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.rvlxae6dq {
  stop-color: var(--svg-color--f9a325, #F9A325);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s4yd9bb_d {
  stop-color: var(--svg-color--fdb326, #FDB326);
  stop-opacity: 0;
}

.sbx2zkbbn {
  stop-color: var(--svg-color--89579c, #89579C);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.so0ia5buv {
  d: path("m14.826 17.376l-2.636-.734l-1.073 3.895l2.6.733c.408.11.755-.064.85-.393l.78-2.704c.123-.39-.164-.693-.521-.797");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxbn0pb5c {
  fill-rule: evenodd;
  d: path("M21.81 10.835c.127-.472.145-.975.048-1.476a3.3 3.3 0 0 0-.516-1.243l.005-.001a3 3 0 0 0-.377-.455l-.002-.003a3.27 3.27 0 0 1-.86-1.655l-.002-.01a3.33 3.33 0 0 0-3.901-2.64a.54.54 0 0 1-.496-.143a3.34 3.34 0 0 0-2.921-.852a3.34 3.34 0 0 0-2.396 1.877a.57.57 0 0 1-.407.318l-.084.017a3.33 3.33 0 0 0-2.556 3.883l.002.01a3.27 3.27 0 0 1-.183 1.857l-.002.004a3.33 3.33 0 0 0 .402 3.258a.52.52 0 0 1 .087.452a3.3 3.3 0 0 0-.052 1.456a3.244 3.244 0 0 0 3.805 2.575l8.507-1.64a3.244 3.244 0 0 0 2.575-3.805a3.3 3.3 0 0 0-.59-1.332a.52.52 0 0 1-.087-.452M9.144 10.53l-.012.002l1.639 2.106c.657 2.755 1.206-.232 3.854-.743c2.648-.51 4.4 2.36 3.986-.442l.515-3.387c-.291-1.223-1.202-1.138-1.38-1.103l-3.193.615a3.9 3.9 0 0 1-3.48-1.05a.266.266 0 0 0-.449.14l-.044.207a2.33 2.33 0 0 1-.99 1.482l-.047.03c-.21.166-.69.636-.528 1.58l.069.302z");
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t_f1esbmg {
  d: path("m12.167 16.743l2.635.735c.357.103.645.406.521.797l-.779 2.703c-.096.33-.442.504-.851.394l-2.6-.734z");
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.t8a4fabjw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.31c.579.141 1.92.172 2.657-.828");
}

.taia9tz6b {
  d: path("M15.451 8.191c1.315.01 2.136.77 2.255 1.526c-1.124-.547-1.886-.487-2.332-.352z");
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tevglhr_j {
  d: path("M10.08 13.302a1.625 1.625 0 1 0-.615-3.19a1.625 1.625 0 0 0 .615 3.19");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tnk2b_bjh {
  stop-color: var(--svg-color--a078e0, #A078E0);
}

.to8hl0otd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.301 4.879c.07.236.454 1.102.867 1.59");
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tp27ezb_z {
  stop-color: var(--svg-color--ffdf42, #FFDF42);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tv-41kbsn {
  stop-color: var(--svg-color--ab461c, #AB461C);
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u2z1wbxzr {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.01 13.947c-.516.1-1.025.069-1.475-.07c-.153-.046-.272.144-.16.256a1.95 1.95 0 0 0 3.222-.62c.061-.152-.118-.279-.244-.18a3.04 3.04 0 0 1-1.343.614");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ugkic7bua {
  d: path("M10.565 18.848c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uqhi6sb2j {
  stop-color: var(--svg-color--ecaa34, #ECAA34);
}

.ut4bgvb0y {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
}

.uyi8rbivm {
  d: path("M19.408 10.954a1.084 1.084 0 1 0-.41-2.13a1.084 1.084 0 0 0 .41 2.13");
}

.v-ki5fbze {
  fill: var(--svg-color--9c84d0, #9C84D0);
  d: path("m29.145 25.618l-4.94-6.05l-3.16 8.57z");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v442oubmz {
  stop-color: var(--svg-color--7c4ca4, #7C4CA4);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vi4zq9bup {
  d: path("M7.155 30.278c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.vo33qub4y {
  stop-color: var(--svg-color--ffe247, #FFE247);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vw31h25pz {
  stop-color: var(--svg-color--e38f1d, #E38F1D);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w_8c_6tma {
  d: path("M15.685 18.809c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.w5h00ebej {
  stop-color: var(--svg-color--dea33f, #DEA33F);
}

.w6wkm7xob {
  stop-color: var(--svg-color--ffb826, #FFB826);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wagk6dfaq {
  stop-color: var(--svg-color--966be0, #966BE0);
}

.wcbvx-n_a {
  stop-color: var(--svg-color--89579c, #89579C);
}

.wi8a08bum {
  stop-color: var(--svg-color--785191, #785191);
  stop-opacity: 0;
}

.wlb38ob3l {
  stop-color: var(--svg-color--cd7c46, #CD7C46);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wxdz3ub6w {
  stop-color: var(--svg-color--f9a325, #F9A325);
  stop-opacity: 0;
}

.wzg23bc3x {
  stop-color: var(--svg-color--ffdf42, #FFDF42);
}

.x5utb7s2j {
  stop-color: var(--svg-color--be672a, #BE672A);
}

.x9s6ceaht {
  stop-color: var(--svg-color--b087f9, #B087F9);
  stop-opacity: 0;
}

.xh9neyo3y {
  stop-color: var(--svg-color--eea92f, #EEA92F);
}

.xllr1s1ox {
  stop-color: var(--svg-color--b76f5c, #B76F5C);
}

.xn8v49gcn {
  stop-color: var(--svg-color--f8c640, #F8C640);
}

.xoq3wtioq {
  stop-color: var(--svg-color--ffcb2e, #FFCB2E);
}

.y-ymn0bhn {
  stop-color: var(--svg-color--755994, #755994);
}

.y3ozgf0rs {
  stop-color: var(--svg-color--b76f5c, #B76F5C);
  stop-opacity: 0;
}

.y8a_xmbaj {
  stop-color: var(--svg-color--96442e, #96442E);
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yjg5mljgk {
  stroke: var(--svg-color--b45c48, #B45C48);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.906 7.972c.304-.14 1.107-.254 1.712.024");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yyn9swbvh {
  stop-color: var(--svg-color--784787, #784787);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z1su-ab9u {
  d: path("M21.81 10.835c.127-.472.145-.975.048-1.476a3.3 3.3 0 0 0-.516-1.243l.005-.001a3 3 0 0 0-.377-.455l-.002-.003a3.27 3.27 0 0 1-.86-1.655l-.002-.01a3.33 3.33 0 0 0-3.901-2.64a.54.54 0 0 1-.496-.143a3.34 3.34 0 0 0-2.921-.852a3.34 3.34 0 0 0-2.396 1.877a.57.57 0 0 1-.407.318l-.084.017a3.33 3.33 0 0 0-2.556 3.883l.002.01a3.27 3.27 0 0 1-.183 1.857l-.002.004a3.33 3.33 0 0 0 .402 3.258a.52.52 0 0 1 .087.452a3.3 3.3 0 0 0-.052 1.456a3.244 3.244 0 0 0 3.805 2.575l8.507-1.64a3.244 3.244 0 0 0 2.575-3.805a3.3 3.3 0 0 0-.59-1.332a.52.52 0 0 1-.087-.452M9.144 10.53l-.012.002l1.639 2.106c.657 2.755 1.206-.232 3.854-.743c2.648-.51 4.4 2.36 3.986-.442l.515-3.387c-.291-1.223-1.202-1.138-1.38-1.103l-3.193.615a3.9 3.9 0 0 1-3.48-1.05a.266.266 0 0 0-.449.14l-.044.207a2.33 2.33 0 0 1-.99 1.482l-.047.03c-.21.166-.69.636-.528 1.58l.069.302z");
}

.z1zjblq2q {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
  stop-opacity: 0;
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z6eg73bhs {
  stop-color: var(--svg-color--e88128, #E88128);
  stop-opacity: 0;
}

.zbwshaccu {
  stop-color: var(--svg-color--875ab4, #875AB4);
}

.zfchjpbgt {
  stop-color: var(--svg-color--b06f2e, #B06F2E);
}

.zjrohm9wd {
  stop-color: var(--svg-color--d99540, #D99540);
}

</style>
