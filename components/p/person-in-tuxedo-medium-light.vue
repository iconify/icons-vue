<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iDFerFe)" class="fgk-5hbhi"/><path fill="url(#i0bnV8d)" class="fgk-5hbhi"/><path fill="url(#iKSChfb)" class="fgk-5hbhi"/><path fill="url(#iOgV9Cc)" class="fgk-5hbhi"/><path fill="url(#iREYwin)" class="fgk-5hbhi"/><path fill="url(#iZenc8c)" class="jockr5brf"/><path fill="url(#iKXZx0b)" class="jockr5brf"/><g filter="url(#ihMeJTd)"><path fill="url(#i1gRHJc)" class="hkh85bbeh"/><path fill="url(#iOyX0na)" class="hkh85bbeh"/></g><path fill="url(#i1fkYzc)" class="k8ix0jbxx"/><g filter="url(#iqOKxpq)"><path fill="url(#iviLTSb)" class="mj9a-09qg"/><path fill="url(#iLbvW7l)" class="mj9a-09qg"/></g><g filter="url(#i69LHUb)"><path class="ow2sicbjy"/></g><path fill="url(#ivWFWhb)" class="r66it6rvi"/><path fill="url(#ikgV5Dc)" class="r66it6rvi"/><path fill="url(#iuTRW6b)" class="r66it6rvi"/><path fill="url(#iRSaCgd)" class="r66it6rvi"/><path fill="url(#i5AU1ke)" class="x3n8sshto"/><path fill="url(#iCIUKvd)" class="x3n8sshto"/><path fill="url(#iG0bM9I)" class="x3n8sshto"/><path fill="url(#iqxFvob)" class="x3n8sshto"/><g filter="url(#ibIU4fc)"><path fill="url(#iWg0yye)" class="o4j6k38-e"/></g><g filter="url(#ilcltHe)"><path fill="url(#imi6qCe)" class="rnafodbyg"/></g><path fill="url(#igjxDfb)" class="rnafodbyg"/><path fill="url(#i6QxIpL)" class="rnafodbyg"/><path fill="url(#iZVvX9d)" class="rnafodbyg"/><g filter="url(#iW5uVdd)"><path class="c3yl_4bph"/></g><g filter="url(#ieRCnfU)"><circle class="dr-k41b2k"/></g><g filter="url(#i9juPQd)"><circle class="uy8ok031y"/></g><g filter="url(#inRmjVT)"><circle fill="url(#iu4bQzc)" class="smrxvvbzr"/></g><g filter="url(#i8lfUjc)"><circle fill="url(#i1xsAGY)" class="cnk20mb3o"/></g><rect fill="url(#iCrVWOd)" class="cydfracdw"/><rect fill="url(#iWGvSsc)" class="cydfracdw"/><rect fill="url(#i4nVo8k)" class="cydfracdw"/><rect fill="url(#i7msYob)" class="cydfracdw"/><rect fill="url(#ihsrrwe)" class="cydfracdw"/><rect fill="url(#il8a3pw)" class="cydfracdw"/><g filter="url(#iBJTPke)"><path fill="url(#iHrAMlb)" class="zipbdebnb"/></g><path fill="url(#iDvp61c)" class="zipbdebnb"/><g filter="url(#iGEgXFe)"><path class="t7vx_s46x"/><path fill="url(#i0fii8l)" class="d5_vr-a5y"/><path fill="url(#i2xtQ7c)" class="d5_vr-a5y"/><path fill="url(#iQbtvjb)" class="d5_vr-a5y"/></g><g filter="url(#ikFfyIb)"><circle fill="url(#in03t1b)" class="x5prydbjk"/><circle fill="url(#iHjr1Ec)" class="x5prydbjk"/></g><path fill="url(#iTGh48d)" class="lxwpisb2p"/><path fill="url(#ilue1zc)" class="vasmcsk-j"/><path fill="url(#il6JONd)" class="vasmcsk-j"/><path fill="url(#ilue1zc)" class="vasmcsk-j"/><path fill="url(#il6JONd)" class="vasmcsk-j"/><g filter="url(#iF3Mkyc)"><path fill="url(#ipiDxob)" class="umnprcbus"/></g><path fill="url(#iTdZAec)" class="umnprcbus"/><path fill="url(#iZdxsWc)" class="umnprcbus"/><path fill="url(#iIRmj9d)" class="umnprcbus"/><path fill="url(#iroXPhb)" class="umnprcbus"/><path fill="url(#iJhN1Jb)" class="umnprcbus"/><path fill="url(#iyCfrOD)" class="umnprcbus"/><path fill="url(#i5JYFYb)" class="umnprcbus"/><path fill="url(#i8lc92l)" class="umnprcbus"/><g filter="url(#igE3Azc)"><path class="s507jacaa"/></g><g filter="url(#i71SOLd)"><path fill="url(#irw89zb)" class="wfmetqbgx"/><path fill="url(#i9AxG6q)" class="wfmetqbgx"/><path fill="url(#i9eT3jd)" class="wfmetqbgx"/></g><g filter="url(#icxnJje)"><path fill="url(#iFfwSBQ)" class="g5mghpalx"/></g><g filter="url(#iEO5oFc)"><path stroke="url(#i9TSqSd)" class="znu8sgtfx"/></g><path fill="url(#iFhhBDb)" class="mmm3axrtb"/><g filter="url(#iYgFl1c)"><path fill="url(#im6rBjc)" class="hti544kus"/><path fill="url(#iZimzsd)" class="hti544kus"/><path fill="url(#iyMhDNc)" class="hti544kus"/><path fill="url(#iQptJrd)" class="hti544kus"/><path fill="url(#icp1zPl)" class="hti544kus"/></g><g filter="url(#iQuBvib)"><path class="a2wf6ib0j"/></g><g filter="url(#iRI3sjR)"><path class="baxr22b7u"/></g><g filter="url(#iNqbbHe)"><path fill="url(#i2gHqye)" class="sg2m5cbxm"/><path fill="url(#iXLNhZz)" class="sg2m5cbxm"/></g><g filter="url(#iM8EMLb)"><path fill="url(#iAW9iNc)" class="zyxaf_pxn"/><path fill="url(#igdWSpd)" class="zyxaf_pxn"/><path fill="url(#i2goRac)" class="zyxaf_pxn"/><path fill="url(#im2zYwe)" class="zyxaf_pxn"/><path fill="url(#ipU7Ojc)" class="zyxaf_pxn"/><path fill="url(#in0awqc)" class="zyxaf_pxn"/></g><path class="w492tsmgk"/><path fill="url(#iq7Gmmd)" class="d-ip5gb4m"/><path class="n_y8m0brh"/><g filter="url(#iUOXbkc)"><path class="ada54r3xa"/><path fill="url(#iQrbTKe)" class="oh5bx4blu"/></g><g filter="url(#iVhjHtb)"><path fill="url(#ioAMirb)" class="ruy4zhbtw"/></g><path class="d0bs4vbqv"/><path fill="url(#iPeVPAb)" class="fr8ylbcvb"/><path class="qfzp84bkx"/><g filter="url(#iDUcEfd)"><path fill="url(#iImiyLv)" class="wld2jrblf"/></g><g filter="url(#ivCK91b)"><ellipse transform="rotate(-27.914 13.56 9.923)" class="orotltb9o"/><ellipse fill="url(#ihDOOAc)" transform="rotate(-27.914 13.56 9.923)" class="vca9s_gbm"/></g><path fill="url(#icaxPJe)" class="t-zi6pepl"/><path fill="url(#izgRRKe)" class="t-zi6pepl"/><path fill="url(#imaSkXa)" class="t-zi6pepl"/><path fill="url(#ixTTvOc)" class="tehj07b4u"/><path fill="url(#ifYo1Bd)" class="tehj07b4u"/><g filter="url(#it0W6gc)"><path class="f7l-i6bpz"/></g><g filter="url(#iLenNoe)"><path class="tyz17fbjs"/></g><g filter="url(#imn9Zyc)"><path class="ibz8l0m-b"/></g><g filter="url(#izQWeEc)"><path class="pb_34pb7j"/></g><defs><radialGradient id="iDFerFe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.875 0 0 -9.21464 22.408 25.315)" gradientUnits="userSpaceOnUse"><stop class="rp3tqelhu"/><stop offset="1" class="nwb1x8bnq"/></radialGradient><radialGradient id="i0bnV8d" cx="0" cy="0" r="1" gradientTransform="rotate(133.011 2.77 10.813)scale(6.32206 7.4475)" gradientUnits="userSpaceOnUse"><stop class="cosmi4y3y"/><stop offset="1" class="fs5qncc9z"/></radialGradient><radialGradient id="iKSChfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.5 0 0 -14.0625 23.19 23.226)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="b_mjjkbmw"/><stop offset="1" class="tg6m8fb0a"/></radialGradient><radialGradient id="iZenc8c" cx="0" cy="0" r="1" gradientTransform="rotate(-91.369 27.241 2.61)scale(11.2456 1.27919)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="uc5leibtb"/><stop offset="1" class="j8ireobfm"/><stop offset="1" class="hj096sb7e"/></radialGradient><radialGradient id="iKXZx0b" cx="0" cy="0" r="1" gradientTransform="matrix(.5755 0 0 15.6193 23.099 28.127)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n_pmxxxsa"/><stop offset="1" class="a_orf89wt"/></radialGradient><radialGradient id="i1gRHJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.9375 4 0 6.69 30.382)" gradientUnits="userSpaceOnUse"><stop class="cm2l5-bra"/><stop offset="1" class="z_d2yzmmm"/></radialGradient><radialGradient id="i1fkYzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55519 1.9364 -1.64284 -1.31942 8.901 18.538)" gradientUnits="userSpaceOnUse"><stop class="aba3uxblf"/><stop offset="1" class="bbv_pqbfl"/></radialGradient><radialGradient id="iviLTSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03127 9.1875 -4.7805 -.01627 17.096 22.508)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="geqh5zowk"/><stop offset="1" class="u21vfmbcf"/></radialGradient><radialGradient id="iLbvW7l" cx="0" cy="0" r="1" gradientTransform="rotate(116.36 1.349 13.025)scale(5.4245 1.91221)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lf_z1-eut"/><stop offset="1" class="safapbcnd"/></radialGradient><radialGradient id="ikgV5Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-152.488 10.104 8.356)scale(1.16274 3.57827)" gradientUnits="userSpaceOnUse"><stop class="ff2asxc8d"/><stop offset="1" class="c5vb29odw"/></radialGradient><radialGradient id="iuTRW6b" cx="0" cy="0" r="1" gradientTransform="matrix(.79687 -.22754 .55824 1.95507 13.236 18.648)" gradientUnits="userSpaceOnUse"><stop class="vdt_t3f2x"/><stop offset="1" class="v0ftcskkn"/></radialGradient><radialGradient id="iCIUKvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.39062 .34376 -1.28105 5.18228 17.174 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="fojlwlb9t"/><stop offset="1" class="cyzx27bkq"/></radialGradient><radialGradient id="iG0bM9I" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 .35156 -1.56152 -1.21452 17.276 19.383)" gradientUnits="userSpaceOnUse"><stop class="ojp787kql"/><stop offset="1" class="zhh5xs6ht"/></radialGradient><radialGradient id="imi6qCe" cx="0" cy="0" r="1" gradientTransform="rotate(172.755 6.075 11.856)scale(1.9846 6.9682)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="z58nq_enb"/><stop offset="1" class="v5ndbpbdn"/></radialGradient><radialGradient id="igjxDfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91838 1.78314 -4.30906 -2.21931 13.135 16.264)" gradientUnits="userSpaceOnUse"><stop class="ubq14mb-s"/><stop offset="1" class="q0kampb0a"/></radialGradient><radialGradient id="i6QxIpL" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94239 -.4885 0 11.747 16.322)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="ihl9krbbc"/><stop offset="1" class="vjj8ifxqk"/></radialGradient><radialGradient id="iZVvX9d" cx="0" cy="0" r="1" gradientTransform="matrix(.0919 1.7035 -.36222 .01954 10.659 20.617)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="jfikb2f0k"/><stop offset="1" class="k5y7j_bmf"/></radialGradient><radialGradient id="iu4bQzc" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 2.875 16.044)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="i1xsAGY" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 3.493 14.54)scale(.5552)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iWGvSsc" cx="0" cy="0" r="1" gradientTransform="matrix(.75 1.28125 -.67469 .39494 14.204 17.66)" gradientUnits="userSpaceOnUse"><stop class="m8qj67bxn"/><stop offset="1" class="lurh12x1h"/></radialGradient><radialGradient id="i4nVo8k" cx="0" cy="0" r="1" gradientTransform="matrix(-.9475 1.63953 -.43892 -.25365 17.949 17.306)" gradientUnits="userSpaceOnUse"><stop class="q4e4b80yr"/><stop offset="1" class="b39zhf_zv"/></radialGradient><radialGradient id="i7msYob" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42187 .2344 -.06955 -.71857 15.923 16.831)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="h1w9f41ug"/><stop offset="1" class="wupw8ebgu"/></radialGradient><radialGradient id="ihsrrwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 -.57813 .21434 -.3302 15.47 18.374)" gradientUnits="userSpaceOnUse"><stop class="fd31sgblt"/><stop offset="1" class="i20artbwr"/></radialGradient><radialGradient id="il8a3pw" cx="0" cy="0" r="1" gradientTransform="matrix(.79688 -.5 .2051 .32688 16.736 18.393)" gradientUnits="userSpaceOnUse"><stop class="lhk6elbnr"/><stop offset="1" class="gq_8cv3su"/></radialGradient><radialGradient id="iHrAMlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39331 0 0 -1.18711 18.294 18.73)" gradientUnits="userSpaceOnUse"><stop class="udzp2zp0e"/><stop offset="1" class="mgsb3vbjk"/></radialGradient><radialGradient id="iDvp61c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.92504 -.35938 0 18.143 18.105)" gradientUnits="userSpaceOnUse"><stop class="tayze7bgq"/><stop offset="1" class="s41karbfc"/></radialGradient><radialGradient id="i2xtQ7c" cx="0" cy="0" r="1" gradientTransform="rotate(-144.958 10.438 6.855)scale(1.79393 .6786)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="i8gd1zbwo"/><stop offset="1" class="fj3b0ib3x"/></radialGradient><radialGradient id="iQbtvjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 0 0 -1.53003 15.424 18.96)" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></radialGradient><radialGradient id="in03t1b" cx="0" cy="0" r="1" gradientTransform="rotate(135.285 4.375 12.583)scale(.89786)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="t1trakjku"/><stop offset=".765" class="voa0z2bgu"/></radialGradient><radialGradient id="iHjr1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 -1.4336 1.50732 -.5257 16.174 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="yl8zw5b_j"/><stop offset="1" class="dh4f0mlhm"/></radialGradient><radialGradient id="iTGh48d" cx="0" cy="0" r="1" gradientTransform="matrix(-.60936 3.53447 -4.19867 -.72388 21.47 11.71)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="ilue1zc" cx="0" cy="0" r="1" gradientTransform="matrix(1.27387 2.6818 -1.219 .57904 10.465 11.994)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="il6JONd" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 -1.213 12.437)scale(1.20702 1.05881)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="ipiDxob" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.82 10.935)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="iZdxsWc" cx="0" cy="0" r="1" gradientTransform="scale(10.1962 12.3125)rotate(90 .6 1.014)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="jty-k5bai"/><stop offset=".982" class="fsweb-u-a"/></radialGradient><radialGradient id="iIRmj9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34091 1.65937 0 18.46 9.814)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="iroXPhb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.478 -1.695)scale(1.10493 1.20242)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="iJhN1Jb" cx="0" cy="0" r="1" gradientTransform="matrix(1.20682 0 0 6.13397 11.132 11.32)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="iyCfrOD" cx="0" cy="0" r="1" gradientTransform="matrix(2.61477 -3.65397 .82763 .59225 10.16 7.934)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="i5JYFYb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4136 -10.24298 11.2829 -2.65864 15.858 15.007)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="i8lc92l" cx="0" cy="0" r="1" gradientTransform="matrix(2.04488 .72074 -.43236 1.2267 17.97 5.553)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i9TSqSd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.732 19.581 -5.591)scale(.7101 2.06639)" gradientUnits="userSpaceOnUse"><stop class="xkl1z0brj"/><stop offset="1" class="pqs_750gt"/></radialGradient><radialGradient id="iFhhBDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 16.012 14.474)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iZimzsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 10.783 9.353)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iyMhDNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.63266 6.43635 0 20.873 9.353)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iQptJrd" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.343 -.315)scale(3.48023 1.85345)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="icp1zPl" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 15.107 1.484)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i2gHqye" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 7.877 2.886)scale(4.04714 1.12642)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iXLNhZz" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.263 -5.756)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iAW9iNc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 .80083 -.44788 1.89356 19.633 4.087)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="igdWSpd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.074 -1.743)scale(4.28182 2.38794)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="i2goRac" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30736 -2.20229 1.57741 -.93641 20.521 8.391)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="im2zYwe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.79843 1.1512 -1.2445 -5.18728 20.806 3.97)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="ipU7Ojc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11733 .38373 -1.75436 -.53643 19.465 3.845)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="in0awqc" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 8.823 7.36)scale(4.25147 10.9633)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iq7Gmmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.195 10.019)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iQrbTKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41146 -.3193 17.966 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPeVPAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.83 10.018)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ihDOOAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.544 10.237)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izgRRKe" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.63 10.033)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="imaSkXa" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.99 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="ifYo1Bd" cx="0" cy="0" r="1" gradientTransform="rotate(-171.68 5.937 4.934)scale(1.69283 1.66421)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="ihMeJTd" width="4.081" height="11.683" x="5.07" y="18.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.345098 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="iqOKxpq" width="5.909" height="14.117" x="12.858" y="15.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="i69LHUb" width="7.13" height="5.229" x="12.285" y="16.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".3"/></filter><filter id="ibIU4fc" width="7.239" height="14.645" x="9.195" y="15.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".5"/></filter><filter id="ilcltHe" width="5.917" height="14.31" x="10.326" y="15.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.113725 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3332" result="effect2_innerShadow_4002_3332"/></filter><filter id="iW5uVdd" width="6.504" height="14.261" x="15.345" y="15.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.372549 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3332" result="effect2_innerShadow_4002_3332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0901961 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3332" result="effect3_innerShadow_4002_3332"/></filter><filter id="ieRCnfU" width="2" height="2" x="14.731" y="24.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".25"/></filter><filter id="i9juPQd" width="2" height="2" x="14.731" y="21.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".25"/></filter><filter id="inRmjVT" width="1.05" height="1.05" x="15.504" y="25.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="i8lfUjc" width="1.05" height="1.05" x="15.504" y="22.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="iBJTPke" width="2.465" height="2.95" x="16.029" y="17.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.164706 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.145098 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3332" result="effect2_innerShadow_4002_3332"/></filter><filter id="iGEgXFe" width="2.365" height="2.9" x="13.731" y="17.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="ikFfyIb" width="1.717" height="1.717" x="15.204" y="17.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.113725 0 0 0 0 0.243137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="iF3Mkyc" width="10.97" height="12.542" x="10.949" y="4.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3332" result="effect2_innerShadow_4002_3332"/></filter><filter id="igE3Azc" width="3.754" height="4.823" x="13.867" y="9.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".5"/></filter><filter id="i71SOLd" width="2.077" height="3.1" x="14.974" y="9.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".05"/></filter><filter id="icxnJje" width="2.077" height="3.1" x="14.974" y="9.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".05"/></filter><filter id="iEO5oFc" width="3.618" height="1.473" x="14.203" y="13.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".05"/></filter><filter id="iYgFl1c" width="12.873" height="8.356" x="9.576" y="1.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3332" result="effect2_innerShadow_4002_3332"/></filter><filter id="iQuBvib" width="2.339" height="1.19" x="17.602" y="7.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="iRI3sjR" width="2.339" height="1.176" x="12.345" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3332"/></filter><filter id="iNqbbHe" width="6.584" height="5.992" x="9.931" y="2.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".125"/></filter><filter id="iM8EMLb" width="6.362" height="5.736" x="15.853" y="3.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".125"/></filter><filter id="iUOXbkc" width=".787" height=".696" x="17.46" y="9.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".05"/></filter><filter id="iVhjHtb" width=".891" height=".913" x="18.3" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".1"/></filter><filter id="iDUcEfd" width=".986" height="1.04" x="13.857" y="9.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".1"/></filter><filter id="ivCK91b" width=".913" height=".705" x="13.103" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".05"/></filter><filter id="it0W6gc" width="1.329" height="2.379" x="9.98" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".125"/></filter><filter id="iLenNoe" width="1.447" height="2.403" x="20.724" y="9.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".125"/></filter><filter id="imn9Zyc" width="2.405" height="1.16" x="12.264" y="7.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".125"/></filter><filter id="izQWeEc" width="2.405" height="1.16" x="17.543" y="7.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3332" stdDeviation=".125"/></filter><linearGradient id="iOgV9Cc" x1="23.131" x2="22.971" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="xg711ab6m"/><stop offset="1" class="eets9_b_s"/></linearGradient><linearGradient id="iREYwin" x1="8.858" x2="9.061" y1="29.906" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="az-h38bei"/><stop offset="1" class="fajspub8c"/></linearGradient><linearGradient id="iOyX0na" x1="9.19" x2="7.596" y1="29.912" y2="29.912" gradientUnits="userSpaceOnUse"><stop class="t1dt_ab6m"/><stop offset="1" class="a519fg_-g"/></linearGradient><linearGradient id="ivWFWhb" x1="14.705" x2="13.268" y1="19.976" y2="16.851" gradientUnits="userSpaceOnUse"><stop class="z7qr8pb7n"/><stop offset="1" class="zynu2nm7a"/></linearGradient><linearGradient id="iRSaCgd" x1="15.518" x2="15.209" y1="20.054" y2="19.937" gradientUnits="userSpaceOnUse"><stop class="x1yfsqmdm"/><stop offset="1" class="kqc3y0bzc"/></linearGradient><linearGradient id="i5AU1ke" x1="16.799" x2="18.471" y1="19.992" y2="17.117" gradientUnits="userSpaceOnUse"><stop class="d4kfw7asd"/><stop offset="1" class="ig120dbzq"/></linearGradient><linearGradient id="iqxFvob" x1="16.486" x2="16.713" y1="19.793" y2="19.703" gradientUnits="userSpaceOnUse"><stop class="cof-_sb7w"/><stop offset="1" class="vo3um_bur"/></linearGradient><linearGradient id="iWg0yye" x1="12.815" x2="12.815" y1="16.773" y2="29.418" gradientUnits="userSpaceOnUse"><stop class="wm85g1cnx"/><stop offset="1" class="b0z0paczy"/></linearGradient><linearGradient id="iCrVWOd" x1="17.033" x2="14.649" y1="18.383" y2="17.814" gradientUnits="userSpaceOnUse"><stop class="gn95f1bvk"/><stop offset="1" class="sxhqjti5d"/></linearGradient><linearGradient id="i0fii8l" x1="15.205" x2="14.838" y1="19.429" y2="18.976" gradientUnits="userSpaceOnUse"><stop class="p5lz4ubjd"/><stop offset="1" class="tyszy7o8n"/></linearGradient><linearGradient id="iTdZAec" x1="21.17" x2="16.817" y1="12.62" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="irw89zb" x1="16.012" x2="16.867" y1="11.764" y2="11.764" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset=".791" class="hk633lr2o"/></linearGradient><linearGradient id="i9AxG6q" x1="14.94" x2="16.014" y1="11.608" y2="11.667" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="i9eT3jd" x1="16.012" x2="16.012" y1="12.162" y2="13.014" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iFfwSBQ" x1="16.012" x2="16.012" y1="9.737" y2="11.325" gradientUnits="userSpaceOnUse"><stop class="fsokymbxc"/><stop offset="1" class="y9wexbcvh"/></linearGradient><linearGradient id="im6rBjc" x1="21.376" x2="11.252" y1="5.272" y2="5.272" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="ioAMirb" x1="18.973" x2="18.659" y1="10.072" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iImiyLv" x1="14.574" x2="14.26" y1="10.072" y2="10.266" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icaxPJe" x1="22.449" x2="21.242" y1="10.099" y2="12.275" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ixTTvOc" x1="10.163" x2="11.621" y1="10.803" y2="10.676" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-tuxedo-medium-light" /></template>
<style>
.a_orf89wt {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
  stop-opacity: 0;
}

.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a2wf6ib0j {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.745 7.955a1.85 1.85 0 0 0-.687-.412c-.305-.095-.686-.121-1.213-.057a.277.277 0 1 0 .068.551c.48-.059.776-.028.978.036c.198.062.333.163.49.3a.277.277 0 0 0 .364-.418");
}

.a519fg_-g {
  stop-color: var(--svg-color--463766, #463766);
  stop-opacity: 0;
}

.aba3uxblf {
  stop-color: var(--svg-color--4e475c, #4E475C);
}

.ada54r3xa {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.13 9.73c.065.085-.068.189-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
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

.b39zhf_zv {
  stop-color: var(--svg-color--c29281, #C29281);
  stop-opacity: 0;
}

.baxr22b7u {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.602 7.846a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.bbv_pqbfl {
  stop-color: var(--svg-color--4e475c, #4E475C);
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

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
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

.d-ip5gb4m {
  d: path("M18.197 9.542a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.d0bs4vbqv {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.621 9.27c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.231a.23.23 0 0 0 .228-.271A1.4 1.4 0 0 0 13.62 9.27");
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d4kfw7asd {
  stop-color: var(--svg-color--dabff4, #DABFF4);
}

.d5_vr-a5y {
  d: path("m14.133 17.475l1.813 1.251l-1.795 1.258a.246.246 0 0 1-.389-.187c-.04-.79-.04-1.569-.007-2.143a.239.239 0 0 1 .378-.18");
}

.dh4f0mlhm {
  stop-color: var(--svg-color--592f4f, #592F4F);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dr-k41b2k {
  cx: 15.731px;
  cy: 25.848px;
  r: 0.5px;
  fill: var(--svg-color--c5a9df, #C5A9DF);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.eets9_b_s {
  stop-color: var(--svg-color--4e377f, #4E377F);
  stop-opacity: 0;
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f7l-i6bpz {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M10.975 9.737a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.fajspub8c {
  stop-color: var(--svg-color--4b3973, #4B3973);
  stop-opacity: 0;
}

.fd31sgblt {
  stop-color: var(--svg-color--a05d67, #A05D67);
}

.ff2asxc8d {
  stop-color: var(--svg-color--e0c6f9, #E0C6F9);
}

.fgk-5hbhi {
  d: path("M5.07 26.41c0-5.797 4.7-10.62 10.5-10.62h.86c5.8 0 10.5 4.823 10.5 10.62v3.496H5.07z");
}

.fj3b0ib3x {
  stop-color: var(--svg-color--564561, #564561);
  stop-opacity: 0;
}

.fojlwlb9t {
  stop-color: var(--svg-color--dfc6d4, #DFC6D4);
  stop-opacity: 0;
}

.fr8ylbcvb {
  d: path("M13.828 9.541a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.fs5qncc9z {
  stop-color: var(--svg-color--4d3b5d, #4D3B5D);
  stop-opacity: 0;
}

.fsokymbxc {
  stop-color: var(--svg-color--e0a78b, #E0A78B);
}

.fsweb-u-a {
  stop-color: var(--svg-color--ae6681, #AE6681);
}

.ft5dv1b6b {
  fill: none;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g5mghpalx {
  d: path("m15.63 10.043l-.531 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.geqh5zowk {
  stop-color: var(--svg-color--e8d4fa, #E8D4FA);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gn95f1bvk {
  stop-color: var(--svg-color--b67a7c, #B67A7C);
}

.gq_8cv3su {
  stop-color: var(--svg-color--a8686e, #A8686E);
  stop-opacity: 0;
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h1w9f41ug {
  stop-color: var(--svg-color--af6a76, #AF6A76);
}

.hj096sb7e {
  stop-color: var(--svg-color--6b628b, #6B628B);
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hkh85bbeh {
  d: path("M8.901 18.23a10.69 10.69 0 0 0-3.831 8.184v3.498H8.9z");
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hti544kus {
  d: path("M20.867 4.292a2.32 2.32 0 0 1 1.268 1.051a2.37 2.37 0 0 1-.106 2.527c-.175.257-.27.563-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.078-1.607a1.45 1.45 0 0 0-1.378-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.616-.418H14.29c-1.845 0-3.34 1.513-3.34 3.38l.03 1.537a1.7 1.7 0 0 0-.72.263v-1.2a1.56 1.56 0 0 0-.27-.874a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.193 0a2.4 2.4 0 0 1 .913-.187c.843 0 1.58.456 1.989 1.131c.307.51.79.88 1.352 1.073");
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i20artbwr {
  stop-color: var(--svg-color--a05d67, #A05D67);
  stop-opacity: 0;
}

.i8gd1zbwo {
  stop-color: var(--svg-color--564561, #564561);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibz8l0m-b {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.64 8.126c.256-.185.897-.509 1.654-.382");
}

.ig120dbzq {
  stop-color: var(--svg-color--aea5b6, #AEA5B6);
}

.ihl9krbbc {
  stop-color: var(--svg-color--5e5962, #5E5962);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j8ireobfm {
  stop-color: var(--svg-color--72659b, #72659B);
}

.jfikb2f0k {
  stop-color: var(--svg-color--48414f, #48414F);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jockr5brf {
  d: path("M23.099 18.23a10.68 10.68 0 0 1 3.831 8.18v3.496H23.1z");
}

.jty-k5bai {
  stop-color: var(--svg-color--c28387, #C28387);
  stop-opacity: 0;
}

.k5y7j_bmf {
  stop-color: var(--svg-color--48414f, #48414F);
  stop-opacity: 0;
}

.k8ix0jbxx {
  d: path("M8.901 18.23a10.68 10.68 0 0 0-3.831 8.18v3.496H8.9z");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kqc3y0bzc {
  stop-color: var(--svg-color--ccb1e3, #CCB1E3);
  stop-opacity: 0;
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lf_z1-eut {
  stop-color: var(--svg-color--705775, #705775);
}

.lhk6elbnr {
  stop-color: var(--svg-color--a8686e, #A8686E);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.lurh12x1h {
  stop-color: var(--svg-color--bd8176, #BD8176);
  stop-opacity: 0;
}

.lxwpisb2p {
  d: path("M20.874 12.185a1.64 1.64 0 0 0 .904-.309v.931c0 .893-.532 1.689-1.34 2.02c.17-.363.287-.759.345-1.18z");
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.m8qj67bxn {
  stop-color: var(--svg-color--bd8176, #BD8176);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgsb3vbjk {
  stop-color: var(--svg-color--462c5b, #462C5B);
}

.mj9a-09qg {
  d: path("M18.767 16.057a10.3 10.3 0 0 0-2.337-.268h-.86q-1.194.002-2.312.262v5.422c0 4.175 1.065 5.972 2.654 8.433h.285c1.59-2.461 2.57-4.258 2.57-8.433z");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mmm3axrtb {
  d: path("M16.012 13.831c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.583.846c.665 0 1.249-.339 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33");
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n_pmxxxsa {
  stop-color: var(--svg-color--4f3b7b, #4F3B7B);
}

.n_y8m0brh {
  fill: var(--svg-color--000, #000);
  d: path("M17.685 10.434a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nwb1x8bnq {
  stop-color: var(--svg-color--594687, #594687);
}

.o4j6k38-e {
  d: path("M11.242 18.34c-.03-1.01.55-1.42.819-1.502l.617-.065v5.373c0 3.575.239 4.662 2.733 7.12l.011.015c.047.083-.05.176-.132.12c-2.75-1.881-4.776-3.354-5.094-8.18a.187.187 0 0 1 .174-.198c.297-.019.56-.044.747-.06a.19.19 0 0 0 .171-.192c-.01-.53-.02-1.532-.046-2.43");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oh5bx4blu {
  d: path("M18.13 9.73c.065.085-.068.189-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.ojp787kql {
  stop-color: var(--svg-color--bb9dd6, #BB9DD6);
}

.orotltb9o {
  cx: 13.559px;
  cy: 9.923px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.ow2sicbjy {
  fill: var(--svg-color--9c80b1, #9C80B1);
  d: path("M12.889 16.68c-.037.825.18 2.637 1.367 3.872c.255.265.715.18.863-.13l.73-1.434l.731 1.435c.149.308.609.394.863.129c1.186-1.235 1.404-3.047 1.368-3.872z");
}

.p5lz4ubjd {
  stop-color: var(--svg-color--391f50, #391F50);
}

.pb_34pb7j {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.573 8.08c-.257-.185-.897-.51-1.655-.382");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqs_750gt {
  stop-color: var(--svg-color--e3b4a5, #E3B4A5);
  stop-opacity: 0;
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q0kampb0a {
  stop-color: var(--svg-color--422131, #422131);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q4e4b80yr {
  stop-color: var(--svg-color--c29281, #C29281);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qfzp84bkx {
  fill: var(--svg-color--000, #000);
  d: path("M14.34 10.434a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r66it6rvi {
  d: path("M14.41 20.277c-1.185-1.235-1.403-3.046-1.367-3.871h2.969l.035 2.223l-.773 1.52c-.148.308-.608.393-.863.128");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rnafodbyg {
  d: path("M11.709 17.543c-.032-1.094.595-1.537.886-1.626l.668-.07v5.815c0 3.874 1.453 6.262 2.712 8.088c.063.09-.047.2-.138.138c-2.977-2.036-4.916-4.003-5.26-9.226a.203.203 0 0 1 .188-.215c.321-.02.606-.047.808-.066c.107-.01.188-.1.186-.206c-.011-.575-.023-1.66-.05-2.632");
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rp3tqelhu {
  stop-color: var(--svg-color--63519f, #63519F);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.ruy4zhbtw {
  d: path("M18.992 10.317a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

.s41karbfc {
  stop-color: var(--svg-color--5a4772, #5A4772);
  stop-opacity: 0;
}

.s507jacaa {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.582 10.599l-.692 1.655c-.102.378.142.756.486.756h.735c.345 0 .588-.384.487-.756l-.497-1.838c-.106-.408-.408-.225-.52.182");
}

.safapbcnd {
  stop-color: var(--svg-color--937da2, #937DA2);
  stop-opacity: 0;
}

.sg2m5cbxm {
  d: path("m16.245 5.32l-.066-.138a.66.66 0 0 0-.616-.418H14.29c-1.845 0-3.341 1.513-3.341 3.38v.274c-.34-.258-.768-.804-.768-1.687c0-1.072.782-1.614 1.28-1.96c.142-.097.26-.18.332-.253l.1-.105c.349-.37.971-1.031 2.059-1.32a5.5 5.5 0 0 1 1.508-.165c.472.012.806.42.806.893v1.485z");
}

.smrxvvbzr {
  cx: 16.004px;
  cy: 25.575px;
  r: 0.5px;
}

.sxhqjti5d {
  stop-color: var(--svg-color--b06e72, #B06E72);
}

.t-zi6pepl {
  d: path("M20.934 12.276q.1-1.597.185-3.192a1.61 1.61 0 0 1-.185 3.191");
}

.t1dt_ab6m {
  stop-color: var(--svg-color--463766, #463766);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
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

.tehj07b4u {
  d: path("M10.958 9.076a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.tg6m8fb0a {
  stop-color: var(--svg-color--8179b0, #8179B0);
  stop-opacity: 0;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.tyszy7o8n {
  stop-color: var(--svg-color--391f50, #391F50);
  stop-opacity: 0;
}

.tyz17fbjs {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.974 11.625q.058-.952.111-1.904a.956.956 0 0 1-.11 1.904");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
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

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.umnprcbus {
  d: path("M11.188 13.7a3.916 3.916 0 0 0 3.885 3.406h1.887a3.916 3.916 0 0 0 3.886-3.406c.117-1.884.236-3.76.324-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418H14.29c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.116 3.691.239 5.557");
}

.uy8ok031y {
  cx: 15.731px;
  cy: 22.7px;
  r: 0.5px;
  fill: var(--svg-color--bfa7d5, #BFA7D5);
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v0ftcskkn {
  stop-color: var(--svg-color--866c89, #866C89);
  stop-opacity: 0;
}

.v5ndbpbdn {
  stop-color: var(--svg-color--463856, #463856);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vasmcsk-j {
  d: path("M11.151 12.185a1.64 1.64 0 0 1-.904-.309v.931c0 .893.532 1.689 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.vca9s_gbm {
  cx: 13.559px;
  cy: 9.923px;
  rx: 0.39px;
  ry: 0.197px;
}

.vdt_t3f2x {
  stop-color: var(--svg-color--866c89, #866C89);
}

.vjj8ifxqk {
  stop-color: var(--svg-color--5e5962, #5E5962);
  stop-opacity: 0;
}

.vo3um_bur {
  stop-color: var(--svg-color--dcc1f4, #DCC1F4);
  stop-opacity: 0;
}

.voa0z2bgu {
  stop-color: var(--svg-color--47305d, #47305D);
}

.w492tsmgk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.403 9.27c.654 0 1.205.45 1.355 1.059a.274.274 0 0 1-.267.34h-2.232a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wfmetqbgx {
  d: path("m15.63 10.22l-.531 1.839c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.839c-.114-.407-.646-.407-.765 0");
}

.wld2jrblf {
  d: path("M14.644 10.33c0-.29-.235-.482-.298-.54l-.289.28l.178.36z");
}

.wm85g1cnx {
  stop-color: var(--svg-color--4b385d, #4B385D);
}

.wupw8ebgu {
  stop-color: var(--svg-color--af6a76, #AF6A76);
  stop-opacity: 0;
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x1yfsqmdm {
  stop-color: var(--svg-color--ab90c0, #AB90C0);
}

.x3n8sshto {
  d: path("M17.598 20.277c1.186-1.235 1.404-3.046 1.367-3.871h-2.968l-.036 2.223l.774 1.52c.148.308.608.393.863.128");
}

.x5prydbjk {
  cx: 16.012px;
  cy: 18.695px;
  r: 0.809px;
}

.xg711ab6m {
  stop-color: var(--svg-color--4e377f, #4E377F);
}

.xkl1z0brj {
  stop-color: var(--svg-color--e3b4a5, #E3B4A5);
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y9wexbcvh {
  stop-color: var(--svg-color--e0a78b, #E0A78B);
  stop-opacity: 0;
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yl8zw5b_j {
  stop-color: var(--svg-color--592f4f, #592F4F);
  stop-opacity: 0;
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_d2yzmmm {
  stop-color: var(--svg-color--4b435b, #4B435B);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
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

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znu8sgtfx {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.012 13.831c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.583.846c.665 0 1.249-.339 1.584-.846c.086-.13-.061-.279-.198-.21a3 3 0 0 1-1.386.33Z");
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zynu2nm7a {
  stop-color: var(--svg-color--6b5977, #6B5977);
}

.zyxaf_pxn {
  d: path("m21.225 8.691l-.03-.63c-.01-.764-.64-1.394-1.404-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.136-.12-.368c-.257-.97.67-1.712 1.655-1.521c.974.188 2.082.517 2.902 1.051c1.745 1.138 1.44 3.189.521 4.154");
}

</style>
