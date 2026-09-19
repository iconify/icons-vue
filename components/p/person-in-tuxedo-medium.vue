<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDFerFe)" class="fgk-5hbhi"/><path fill="url(#i0bnV8d)" class="fgk-5hbhi"/><path fill="url(#iKSChfb)" class="fgk-5hbhi"/><path fill="url(#iOgV9Cc)" class="fgk-5hbhi"/><path fill="url(#iREYwin)" class="fgk-5hbhi"/><path fill="url(#iZenc8c)" class="jockr5brf"/><path fill="url(#iKXZx0b)" class="jockr5brf"/><g filter="url(#i3m6N0b)"><path fill="url(#i1gRHJc)" class="hkh85bbeh"/><path fill="url(#iOyX0na)" class="hkh85bbeh"/></g><path fill="url(#i1fkYzc)" class="k8ix0jbxx"/><g filter="url(#iM2R1fV)"><path fill="url(#iviLTSb)" class="mj9a-09qg"/><path fill="url(#iLbvW7l)" class="mj9a-09qg"/></g><g filter="url(#i3EiLIe)"><path class="ow2sicbjy"/></g><path fill="url(#ivWFWhb)" class="r66it6rvi"/><path fill="url(#ikgV5Dc)" class="r66it6rvi"/><path fill="url(#iuTRW6b)" class="r66it6rvi"/><path fill="url(#iRSaCgd)" class="r66it6rvi"/><path fill="url(#i5AU1ke)" class="x3n8sshto"/><path fill="url(#iCIUKvd)" class="x3n8sshto"/><path fill="url(#iG0bM9I)" class="x3n8sshto"/><path fill="url(#iqxFvob)" class="x3n8sshto"/><g filter="url(#i4kLzcc)"><path fill="url(#iWg0yye)" class="o4j6k38-e"/></g><g filter="url(#iqADaLe)"><path fill="url(#imi6qCe)" class="rnafodbyg"/></g><path fill="url(#igjxDfb)" class="rnafodbyg"/><path fill="url(#i6QxIpL)" class="rnafodbyg"/><path fill="url(#iZVvX9d)" class="rnafodbyg"/><g filter="url(#inxHtEb)"><path class="c3yl_4bph"/></g><g filter="url(#iCPfmQe)"><circle class="dr-k41b2k"/></g><g filter="url(#i0aOfze)"><circle class="uy8ok031y"/></g><g filter="url(#iZi6Jte)"><circle fill="url(#iu4bQzc)" class="smrxvvbzr"/></g><g filter="url(#ic4tGSc)"><circle fill="url(#i1xsAGY)" class="cnk20mb3o"/></g><rect fill="url(#ik7tfjM)" class="cydfracdw"/><rect fill="url(#iDZYQMd)" class="cydfracdw"/><rect fill="url(#ipYxmdc)" class="cydfracdw"/><rect fill="url(#iMnIfIc)" class="cydfracdw"/><rect fill="url(#iy2nufe)" class="cydfracdw"/><rect fill="url(#ihhaQud)" class="cydfracdw"/><g filter="url(#iiY2Wid)"><path fill="url(#iHrAMlb)" class="zipbdebnb"/></g><path fill="url(#iDvp61c)" class="zipbdebnb"/><g filter="url(#iGxiYad)"><path class="t7vx_s46x"/><path fill="url(#i0fii8l)" class="d5_vr-a5y"/><path fill="url(#i2xtQ7c)" class="d5_vr-a5y"/><path fill="url(#iQbtvjb)" class="d5_vr-a5y"/></g><g filter="url(#iB7CLfb)"><circle fill="url(#in03t1b)" class="x5prydbjk"/><circle fill="url(#iHjr1Ec)" class="x5prydbjk"/></g><path fill="url(#ifSSZRc)" class="figjjtb-s"/><path fill="url(#iVkDeMd)" class="e0k8lr6lc"/><g filter="url(#ildwylc)"><path fill="url(#iY8vFwo)" class="me67wdall"/><path fill="url(#i2g7kxc)" class="me67wdall"/></g><path fill="url(#iC3AEcT)" class="me67wdall"/><path fill="url(#izdtprK)" class="me67wdall"/><path fill="url(#iynddEe)" class="me67wdall"/><path fill="url(#if4y5ke)" class="me67wdall"/><path fill="url(#i4CefMP)" class="me67wdall"/><path fill="url(#isKJ56b)" class="me67wdall"/><path fill="url(#iJllIVb)" class="me67wdall"/><path fill="url(#if5U0pb)" class="me67wdall"/><g filter="url(#iUlURkb)"><path class="qc_1wtbre"/></g><g filter="url(#i52f5qY)"><path class="vlx6qqbyo"/><path fill="url(#iyoCbCb)" class="xy_mcgbce"/><path fill="url(#ilI89Lc)" class="xy_mcgbce"/><path fill="url(#i6tFhOe)" class="xy_mcgbce"/><path fill="url(#ir6ffae)" class="xy_mcgbce"/></g><g filter="url(#i0kYV6c)"><path fill="url(#iqtNoXc)" class="lm8zjeehi"/></g><g filter="url(#ihJqBOb)"><path stroke="url(#iMU7YKc)" class="btk7yvwjb"/></g><path fill="url(#ilExRSc)" class="dgxlbjban"/><g filter="url(#iJ1ZWwd)"><path fill="url(#i1iAqmb)" class="ktoe2guci"/></g><path fill="url(#iDZgbdc)" class="ktoe2guci"/><path fill="url(#irmeXMe)" class="ktoe2guci"/><path fill="url(#igr9MNd)" class="ktoe2guci"/><g filter="url(#ia6IZiW)"><path class="pn-d2objo"/></g><g filter="url(#ixbihEd)"><path class="r4am9te6i"/></g><g filter="url(#isCGUua)"><path class="kdfj-l6sz"/><path fill="url(#io7yFEk)" class="r54rbum0o"/><path fill="url(#iLRoaQn)" class="r54rbum0o"/></g><g filter="url(#ioV4vNe)"><path class="l_9304bcq"/><path fill="url(#iUPLkKb)" class="yinwx9bvx"/><path fill="url(#iYK1mnb)" class="yinwx9bvx"/><path fill="url(#iUmXHId)" class="yinwx9bvx"/></g><path class="hme3-kb_l"/><path fill="url(#iA6gCcd)" class="x5jm7ko1g"/><path class="ov6xm3lmb"/><g filter="url(#isVMVsd)"><path class="eq_3kbbch"/><path fill="url(#iXji5Pe)" class="em3tl2krq"/></g><g filter="url(#idZe4Md)"><path fill="url(#iWzUqod)" class="qikp8hbij"/></g><path class="lxisos1ed"/><path fill="url(#iqvNiUc)" class="osom_pynh"/><path class="ly1hfctjd"/><g filter="url(#iSPzgld)"><path fill="url(#iStBeqe)" class="r0nlfgbir"/></g><g filter="url(#iWMiVDe)"><ellipse transform="rotate(-27.914 13.54 9.923)" class="uh8nutbgw"/><ellipse fill="url(#i0BXHTn)" transform="rotate(-27.914 13.54 9.923)" class="hrf63_bwb"/></g><path fill="url(#iAue3gb)" class="te9nsb79d"/><path fill="url(#iRm82jb)" class="te9nsb79d"/><path fill="url(#iR34zyr)" class="te9nsb79d"/><path fill="url(#imnmczd)" class="te9nsb79d"/><path fill="url(#iZFiOce)" class="wyw9-c7mz"/><path fill="url(#iySmxJb)" class="wyw9-c7mz"/><g filter="url(#if5CV5b)"><path fill="url(#ir7FZDd)" class="epcq356vd"/></g><g filter="url(#iv3acxe)"><path fill="url(#iQrD2OA)" class="w9v-pug-r"/></g><g filter="url(#iz9B23i)"><path class="hgdc885zr"/></g><g filter="url(#iQZA8Ae)"><path class="p09pkfbpa"/></g><g filter="url(#ianf0hc)"><path class="xl7wzqbjl"/></g><defs><radialGradient id="iDFerFe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.315)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="i0bnV8d" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.77 10.813)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iKSChfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.226)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iZenc8c" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.241 2.61)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iKXZx0b" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.127)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="i1gRHJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.382)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="i1fkYzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.538)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iviLTSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.508)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iLbvW7l" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.349 13.025)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ikgV5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.104 8.356)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iuTRW6b" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.648)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iCIUKvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iG0bM9I" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.383)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="imi6qCe" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.075 11.856)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="igjxDfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.264)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i6QxIpL" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.322)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iZVvX9d" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.659 20.617)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iu4bQzc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.875 16.044)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i1xsAGY" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.493 14.54)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iDZYQMd" cx="0" cy="0" r="1" gradientTransform="rotate(87.563 -1.069 16.555)scale(.73504 2.79136)" gradientUnits="userSpaceOnUse"><stop class="yg9k7ccsh"/><stop offset="1" class="b1wun9brm"/></radialGradient><radialGradient id="ipYxmdc" cx="0" cy="0" r="1" gradientTransform="matrix(.55469 -.25781 .4579 .98516 14.189 17.607)" gradientUnits="userSpaceOnUse"><stop offset=".44" class="t1phj3b7k"/><stop offset="1" class="uemt-9boh"/></radialGradient><radialGradient id="iMnIfIc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.262 11.033 6.956)scale(.82759 1.88786)" gradientUnits="userSpaceOnUse"><stop class="c86qlth6u"/><stop offset="1" class="cb-i4r-gg"/></radialGradient><radialGradient id="iy2nufe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -1.0625 .47656 -.47656 15.313 18.403)" gradientUnits="userSpaceOnUse"><stop class="xiziqcb-g"/><stop offset="1" class="b8r_pg8dx"/></radialGradient><radialGradient id="ihhaQud" cx="0" cy="0" r="1" gradientTransform="matrix(1 -.57813 .3345 .5786 16.501 18.606)" gradientUnits="userSpaceOnUse"><stop class="xiziqcb-g"/><stop offset="1" class="b8r_pg8dx"/></radialGradient><radialGradient id="iHrAMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.73)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iDvp61c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.105)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="i2xtQ7c" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.438 6.855)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iQbtvjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.96)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="in03t1b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.375 12.583)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iHjr1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="ifSSZRc" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.839 20.848)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iVkDeMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.937 12.367)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iY8vFwo" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.8 10.935)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="i2g7kxc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.53 8.172)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="izdtprK" cx="0" cy="0" r="1" gradientTransform="scale(12.7516 12.7173)rotate(90 .455 .83)" gradientUnits="userSpaceOnUse"><stop offset=".784" class="q1qe9kf_q"/><stop offset=".982" class="lbtqybbgc"/></radialGradient><radialGradient id="iynddEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.44 9.622)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="if4y5ke" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.698 -2.037)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="i4CefMP" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.525 6.268)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="isKJ56b" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.202 8.202)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iJllIVb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.12 13.813)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="if5U0pb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.777 10.44)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="ilI89Lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.46 12.296)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="ir6ffae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.576 11.726)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="ilExRSc" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.502 14.558)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iDZgbdc" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 10.286 9.01)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="irmeXMe" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.437 -4.074)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="igr9MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.122 -3.685)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="io7yFEk" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.247 3.743)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iLRoaQn" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.254 -5.739)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iUPLkKb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5152 -2.83003 4.38594 5.4478 17.912 6.3)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="iYK1mnb" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 18.627 7.558)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iUmXHId" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72413 -.30318 1.35036 17.763 5.736)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iA6gCcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.175 10.019)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iXji5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.448 .657)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqvNiUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.811 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i0BXHTn" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.526 10.237)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRm82jb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.611 10.032)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iR34zyr" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.971 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="imnmczd" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.085 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iySmxJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.078 10.673)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="ir7FZDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.08 10.676)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="i3m6N0b" width="4.081" height="11.683" x="5.07" y="18.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="iM2R1fV" width="5.909" height="14.117" x="12.858" y="15.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="i3EiLIe" width="7.13" height="5.229" x="12.285" y="16.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".3"/></filter><filter id="i4kLzcc" width="7.239" height="14.645" x="9.195" y="15.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".5"/></filter><filter id="iqADaLe" width="5.917" height="14.31" x="10.326" y="15.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3329" result="effect2_innerShadow_4002_3329"/></filter><filter id="inxHtEb" width="6.504" height="14.261" x="15.345" y="15.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3329" result="effect2_innerShadow_4002_3329"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3329" result="effect3_innerShadow_4002_3329"/></filter><filter id="iCPfmQe" width="2" height="2" x="14.731" y="24.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".25"/></filter><filter id="i0aOfze" width="2" height="2" x="14.731" y="21.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".25"/></filter><filter id="iZi6Jte" width="1.05" height="1.05" x="15.504" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="ic4tGSc" width="1.05" height="1.05" x="15.504" y="22.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="iiY2Wid" width="2.465" height="2.95" x="16.029" y="17.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3329" result="effect2_innerShadow_4002_3329"/></filter><filter id="iGxiYad" width="2.365" height="2.9" x="13.731" y="17.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="iB7CLfb" width="1.717" height="1.717" x="15.204" y="17.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="ildwylc" width="11.22" height="12.442" x="10.93" y="4.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3329" result="effect2_innerShadow_4002_3329"/></filter><filter id="iUlURkb" width="3.747" height="4.9" x="13.978" y="9.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".5"/></filter><filter id="i52f5qY" width="2.277" height="3.3" x="14.855" y="9.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".1"/></filter><filter id="i0kYV6c" width="2.277" height="3.3" x="14.855" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".1"/></filter><filter id="ihJqBOb" width="3.718" height="1.573" x="14.134" y="13.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".05"/></filter><filter id="iJ1ZWwd" width="12.873" height="8.356" x="9.557" y="1.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3329" result="effect2_innerShadow_4002_3329"/></filter><filter id="ia6IZiW" width="2.339" height="1.19" x="17.582" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="ixbihEd" width="2.339" height="1.176" x="12.326" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/></filter><filter id="isCGUua" width="6.584" height="5.992" x="9.912" y="2.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/><feGaussianBlur result="effect2_foregroundBlur_4002_3329" stdDeviation=".125"/></filter><filter id="ioV4vNe" width="7.112" height="5.986" x="15.834" y="2.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3329"/><feGaussianBlur result="effect2_foregroundBlur_4002_3329" stdDeviation=".125"/></filter><filter id="isVMVsd" width=".787" height=".696" x="17.441" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".05"/></filter><filter id="idZe4Md" width=".891" height=".913" x="18.281" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".1"/></filter><filter id="iSPzgld" width=".986" height="1.04" x="13.838" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".1"/></filter><filter id="iWMiVDe" width=".913" height=".705" x="13.083" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".05"/></filter><filter id="if5CV5b" width="1.329" height="2.379" x="9.912" y="9.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".125"/></filter><filter id="iv3acxe" width="1.806" height="2.758" x="20.544" y="9.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".25"/></filter><filter id="iz9B23i" width="2.405" height="1.16" x="12.245" y="7.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".125"/></filter><filter id="iQZA8Ae" width="2.405" height="1.16" x="17.561" y="7.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".125"/></filter><filter id="ianf0hc" width="5.367" height="3.046" x="17.009" y="3.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3329" stdDeviation=".375"/></filter><linearGradient id="iOgV9Cc" x1="23.131" x2="22.971" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iREYwin" x1="8.858" x2="9.061" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iOyX0na" x1="9.19" x2="7.596" y1="29.912" y2="29.912" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="ivWFWhb" x1="14.705" x2="13.268" y1="19.976" y2="16.851" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iRSaCgd" x1="15.518" x2="15.209" y1="20.054" y2="19.937" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i5AU1ke" x1="16.799" x2="18.471" y1="19.992" y2="17.117" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iqxFvob" x1="16.486" x2="16.713" y1="19.793" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iWg0yye" x1="12.815" x2="12.815" y1="16.773" y2="29.418" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="ik7tfjM" x1="17.033" x2="14.649" y1="18.383" y2="17.814" gradientUnits="userSpaceOnUse"><stop class="e6bv6j5je"/><stop offset="1" class="s_4r2dj6u"/></linearGradient><linearGradient id="i0fii8l" x1="15.205" x2="14.838" y1="19.429" y2="18.976" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iC3AEcT" x1="21.15" x2="18.621" y1="12.62" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iyoCbCb" x1="16.832" x2="15.993" y1="11.61" y2="11.645" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i6tFhOe" x1="15.993" x2="15.993" y1="12.749" y2="12.284" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iqtNoXc" x1="15.993" x2="15.993" y1="9.736" y2="11.606" gradientUnits="userSpaceOnUse"><stop offset=".056" class="xykls_i6k"/><stop offset="1" class="ib660abxw"/></linearGradient><linearGradient id="iMU7YKc" x1="14.792" x2="15.11" y1="14.32" y2="13.485" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="i1iAqmb" x1="22.845" x2="11.233" y1="5.272" y2="5.272" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iWzUqod" x1="18.953" x2="18.639" y1="10.072" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iStBeqe" x1="14.555" x2="14.241" y1="10.072" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAue3gb" x1="22.43" x2="21.223" y1="10.099" y2="12.275" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iZFiOce" x1="10.143" x2="11.602" y1="10.803" y2="10.676" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iQrD2OA" x1="21.446" x2="21.446" y1="9.79" y2="11.548" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-tuxedo-medium" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.az-h38bei {
  stop-color: var(--svg-color--4b3973, #4B3973);
}

.b_mjjkbmw {
  stop-color: var(--svg-color--8179b0, #8179B0);
}

.b0z0paczy {
  stop-color: var(--svg-color--4f3a77, #4F3A77);
}

.b1wun9brm {
  stop-color: var(--svg-color--884b63, #884B63);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.b8r_pg8dx {
  stop-color: var(--svg-color--733a5f, #733A5F);
  stop-opacity: 0;
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
  stop-opacity: 0;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.btk7yvwjb {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.643 13.436h-.001a.23.23 0 0 0-.271.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.645.88s1.298-.352 1.646-.88a.214.214 0 0 0-.023-.272a.23.23 0 0 0-.271-.045c-.39.204-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c3yl_4bph {
  fill: var(--svg-color--443452, #443452);
  d: path("M20.316 17.543c.031-1.094-.595-1.537-.887-1.626l-.668-.07v5.815c0 3.874-1.388 6.264-2.648 8.09c-.062.09.047.2.139.138c2.976-2.036 4.851-4.005 5.196-9.228a.203.203 0 0 0-.188-.215c-.321-.02-.607-.047-.809-.066a.204.204 0 0 1-.185-.206c.011-.575.022-1.66.05-2.632");
}

.c5vb29odw {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
  stop-opacity: 0;
}

.c86qlth6u {
  stop-color: var(--svg-color--a47a70, #A47A70);
}

.cb-i4r-gg {
  stop-color: var(--svg-color--a47a70, #A47A70);
  stop-opacity: 0;
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm2l5-bra {
  stop-color: var(--svg-color--554181, #554181);
}

.cnk20mb3o {
  cx: 16.004px;
  cy: 22.567px;
  r: 0.5px;
}

.cof-_sb7w {
  stop-color: var(--svg-color--a487bb, #A487BB);
}

.cosmi4y3y {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
}

.cydfracdw {
  width: 3.875px;
  height: 4.5px;
  x: 14.075px;
  y: 14.281px;
  rx: 1.938px;
}

.cyzx27bkq {
  stop-color: var(--svg-color--978394, #978394);
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d5_vr-a5y {
  d: path("m14.133 17.475l1.813 1.251l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dgxlbjban {
  d: path("M15.993 13.831c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.583.846c.665 0 1.249-.339 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dr-k41b2k {
  cx: 15.731px;
  cy: 25.848px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0k8lr6lc {
  d: path("M11.132 12.185a1.64 1.64 0 0 1-.905-.309v.931c0 .893.532 1.689 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.e6bv6j5je {
  stop-color: var(--svg-color--986473, #986473);
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.em3tl2krq {
  d: path("M18.112 9.73c.063.085-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.389-.05");
}

.epcq356vd {
  d: path("M10.908 9.736a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.eq_3kbbch {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.112 9.73c.063.085-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.136.389-.05");
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fgk-5hbhi {
  d: path("M5.07 26.41c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.figjjtb-s {
  d: path("M20.855 12.185a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.02c.17-.363.287-.759.345-1.18z");
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hgdc885zr {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.62 8.126c.257-.185.898-.509 1.655-.382");
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hkh85bbeh {
  d: path("M8.901 18.23a10.69 10.69 0 0 0-3.831 8.184v3.498H8.9z");
}

.hme3-kb_l {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.384 9.27c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.hrf63_bwb {
  cx: 13.54px;
  cy: 9.923px;
  rx: 0.39px;
  ry: 0.197px;
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ib660abxw {
  stop-color: var(--svg-color--a4786d, #A4786D);
  stop-opacity: 0;
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jockr5brf {
  d: path("M23.099 18.23a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k8ix0jbxx {
  d: path("M8.901 18.23a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.kdfj-l6sz {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.226 5.32l-.066-.138a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.142-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.ktoe2guci {
  d: path("M20.848 4.292a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.143-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.383-1.11a2.326 2.326 0 0 1 2.891-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.187.912-.187c.843 0 1.58.456 1.989 1.131c.307.51.79.88 1.352 1.073");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l_9304bcq {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.206 8.586l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.367c-.256-.97.671-1.713 1.656-1.522c.973.189 2.082.517 2.902 1.052c1.745 1.138 1.44 3.188.52 4.154");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lbtqybbgc {
  stop-color: var(--svg-color--935279, #935279);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lm8zjeehi {
  d: path("m15.611 10.042l-.532 1.838c-.108.378.152.756.521.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.lxisos1ed {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.602 9.27c-.653 0-1.204.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.128");
}

.ly1hfctjd {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 10.434a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.me67wdall {
  d: path("M11.168 13.7a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mj9a-09qg {
  d: path("M18.767 16.057a10.3 10.3 0 0 0-2.337-.268h-.86q-1.194.002-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o4j6k38-e {
  d: path("M11.242 18.34c-.03-1.01.55-1.42.819-1.502l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.083-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.187.187 0 0 1 .174-.198c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.192c-.01-.53-.02-1.532-.046-2.43");
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.osom_pynh {
  d: path("M13.81 9.541a.893.893 0 0 0-.86 1.128h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.ov6xm3lmb {
  fill: var(--svg-color--000, #000);
  d: path("M17.666 10.434c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.ow2sicbjy {
  fill: var(--svg-color--9c80b1, #9C80B1);
  d: path("M12.889 16.68c-.037.825.18 2.637 1.367 3.872c.255.265.715.18.863-.13l.73-1.434l.731 1.435c.149.308.609.394.863.129c1.186-1.235 1.404-3.047 1.368-3.872z");
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p09pkfbpa {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.591 8.07c-.257-.184-.897-.509-1.655-.381");
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn-d2objo {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.726 7.955a1.85 1.85 0 0 0-.687-.412c-.305-.095-.686-.121-1.213-.057a.277.277 0 1 0 .068.551c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q1qe9kf_q {
  stop-color: var(--svg-color--9d6575, #9D6575);
  stop-opacity: 0;
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qc_1wtbre {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("M15.592 10.416L15 12.254c-.101.379.141.757.484.757h.732c.343 0 .585-.384.484-.757l-.494-1.838c-.106-.407-.504-.407-.615 0");
}

.qikp8hbij {
  d: path("M18.972 10.317a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r0nlfgbir {
  d: path("M14.625 10.33c0-.29-.235-.482-.298-.54l-.289.28l.178.36z");
}

.r4am9te6i {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.582 7.846a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.r54rbum0o {
  d: path("m16.226 5.32l-.066-.138a.66.66 0 0 0-.616-.418h-1.273c-1.845 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.142-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.r66it6rvi {
  d: path("M14.41 20.277c-1.185-1.235-1.403-3.046-1.367-3.871h2.969l.035 2.223l-.773 1.52c-.148.308-.608.393-.863.128");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rnafodbyg {
  d: path("M11.709 17.543c-.032-1.094.595-1.537.886-1.626l.668-.07v5.815c0 3.874 1.453 6.262 2.712 8.088c.063.09-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.66-.05-2.632");
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s_4r2dj6u {
  stop-color: var(--svg-color--814c5c, #814C5C);
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.smrxvvbzr {
  cx: 16.004px;
  cy: 25.575px;
  r: 0.5px;
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1phj3b7k {
  stop-color: var(--svg-color--88595a, #88595A);
}

.t1trakjku {
  stop-color: var(--svg-color--635275, #635275);
}

.t7vx_s46x {
  fill: var(--svg-color--543b70, #543B70);
  d: path("m14.133 17.475l1.813 1.251l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.tayze7bgq {
  stop-color: var(--svg-color--60556d, #60556D);
}

.te9nsb79d {
  d: path("M20.915 12.276q.1-1.597.185-3.192a1.61 1.61 0 0 1-.185 3.191");
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.u21vfmbcf {
  stop-color: var(--svg-color--c6b5d5, #C6B5D5);
}

.ubq14mb-s {
  stop-color: var(--svg-color--422131, #422131);
}

.uc5leibtb {
  stop-color: var(--svg-color--796ba6, #796BA6);
}

.udzp2zp0e {
  stop-color: var(--svg-color--4e3566, #4E3566);
}

.uemt-9boh {
  stop-color: var(--svg-color--88595a, #88595A);
  stop-opacity: 0;
}

.uh8nutbgw {
  cx: 13.54px;
  cy: 9.923px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uy8ok031y {
  cx: 15.731px;
  cy: 22.7px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vlx6qqbyo {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.611 10.22l-.532 1.839c-.108.378.152.756.521.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w9v-pug-r {
  d: path("m21.044 11.548l.094-1.758c.4.055.711.426.711.876c0 .484-.36.878-.805.882");
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wyw9-c7mz {
  d: path("M10.949 9.071a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.56 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x3n8sshto {
  d: path("M17.598 20.277c1.186-1.235 1.404-3.046 1.367-3.871h-2.968l-.036 2.223l.774 1.52c.148.308.608.393.863.128");
}

.x5jm7ko1g {
  d: path("M18.177 9.542a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.x5prydbjk {
  cx: 16.012px;
  cy: 18.695px;
  r: 0.809px;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xiziqcb-g {
  stop-color: var(--svg-color--733a5f, #733A5F);
}

.xl7wzqbjl {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.392 5.322h-2.137a.496.496 0 1 1 .08-.987c.553.088 1.29.211 1.783.334c1.115.276 1.423.819 1.509 1.206a1.56 1.56 0 0 0-1.235-.553");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xy_mcgbce {
  d: path("m15.611 10.22l-.532 1.839c-.108.378.152.756.521.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.xykls_i6k {
  stop-color: var(--svg-color--a4786d, #A4786D);
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yg9k7ccsh {
  stop-color: var(--svg-color--884b63, #884B63);
}

.yinwx9bvx {
  d: path("m21.206 8.586l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.367c-.256-.97.671-1.713 1.656-1.522c.973.189 2.082.517 2.902 1.052c1.745 1.138 1.44 3.188.52 4.154");
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z58nq_enb {
  stop-color: var(--svg-color--5e536c, #5E536C);
}

.z7qr8pb7n {
  stop-color: var(--svg-color--ba9fd3, #BA9FD3);
}

.zhh5xs6ht {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
  stop-opacity: 0;
}

.zipbdebnb {
  d: path("m17.892 17.475l-1.813 1.251l1.795 1.258a.246.246 0 0 0 .388-.187c.041-.79.041-1.569.008-2.143a.239.239 0 0 0-.378-.18");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

</style>
