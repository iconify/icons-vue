<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZyFstc)" class="bmdpf4wuk"/><path fill="url(#i3QoCfc)" class="bmdpf4wuk"/><path fill="url(#iqoVp8c)" class="bmdpf4wuk"/><path fill="url(#iEMJ8Bb)" class="bmdpf4wuk"/><path fill="url(#i8KCMtW)" class="bmdpf4wuk"/><path class="xf2opsb3a"/><path fill="url(#izCZMmi)" class="rrk_4bb5u"/><path fill="url(#iwycdCV)" class="rrk_4bb5u"/><path fill="url(#iIzbeSd)" class="rrk_4bb5u"/><path fill="url(#iRPAmNc)" class="rrk_4bb5u"/><path class="eu4ef4o7o"/><path fill="url(#isNLGfq)" class="k8p9e6b4e"/><path fill="url(#iaRjLEb)" class="k8p9e6b4e"/><path fill="url(#iA0Y7Qb)" class="k8p9e6b4e"/><g filter="url(#iCP5Hmc)"><path fill="url(#i5kEYjc)" class="bk54hjl7x"/></g><g filter="url(#iqDTwGT)"><path class="dnazjxbei"/></g><g filter="url(#igh3DuC)"><path class="c0156tydt"/></g><g filter="url(#ieR15jb)"><path fill="url(#iPWyAEc)" class="ej4qybc4v"/></g><g filter="url(#ilpm1Sd)"><path fill="url(#iZEHnib)" class="aymqfdc9h"/></g><g filter="url(#iQeNBZd)"><path stroke="url(#iveJrlx)" class="vlvwenz1w"/></g><g filter="url(#iBV1Jwe)"><path stroke="url(#iyXpkGB)" class="sa_ie2xef"/></g><path fill="url(#iufSQfF)" class="wx8zj3ibb"/><g filter="url(#idcg3eF)"><path fill="url(#ilrndMd)" class="kil27mbcd"/><path fill="url(#iQWxelH)" class="kil27mbcd"/><path fill="url(#ihUkBIe)" class="kil27mbcd"/></g><path fill="url(#iC85Iad)" class="kil27mbcd"/><path fill="url(#ish3Mwd)" class="kil27mbcd"/><rect fill="url(#itKMH7c)" class="gafovlbte"/><rect fill="url(#iTCRhDv)" class="gafovlbte"/><rect fill="url(#i9HiKBe)" class="gafovlbte"/><rect fill="url(#iaPKrDb)" class="oy755iz6f"/><rect fill="url(#isHF8Xc)" class="oy755iz6f"/><rect fill="url(#i9Wns5d)" class="oy755iz6f"/><path fill="url(#i7UuRDd)" class="k14mqzbhm"/><path fill="url(#im5VnDe)" class="k14mqzbhm"/><path fill="url(#ieDqMib)" class="k14mqzbhm"/><g filter="url(#ieZ8SXb)"><path fill="url(#i3I63Tc)" class="xagcxqb0l"/></g><g filter="url(#i2cwuIe)"><path fill="url(#iAxGs6b)" class="yz039z2rc"/></g><path fill="url(#iDo69Ec)" class="dm1r4g2jn"/><path fill="url(#iRf4JZc)" class="dm1r4g2jn"/><g filter="url(#iYEb1ed)"><path class="a0yqjpbvz"/></g><g filter="url(#iIewwEd)"><path fill="url(#iKlLAxk)" class="cdcaw77-g"/><path fill="url(#idwa9sd)" class="cdcaw77-g"/><path fill="url(#iYGWSXd)" class="cdcaw77-g"/></g><path fill="url(#i93OjHe)" class="cdcaw77-g"/><path fill="url(#ibDOt9d)" class="cdcaw77-g"/><g filter="url(#i3IoU4b)"><path class="siu29i9yh"/></g><g filter="url(#iNZhCPe)"><path fill="url(#i601Rnc)" class="qw-0xrp0e"/><path fill="url(#iKcOMrd)" class="qw-0xrp0e"/></g><path stroke="url(#i9qEEse)" class="xtn5m1b_o"/><g filter="url(#iVvJayc)"><path class="asil7b01k"/></g><g filter="url(#iASi9rb)"><path class="mblf-fbmn"/></g><g filter="url(#itr8vjc)"><path class="a34p3q8ba"/></g><g filter="url(#iIeVwbe)"><path clip-rule="evenodd" class="nh0n8dbkp"/></g><path class="lz2odobri"/><path fill="url(#iTa88bd)" class="wv0-ezbvn"/><path class="bxq8_bb0o"/><g filter="url(#ip8TY7L)"><path class="k4tl-1b7s"/><path fill="url(#ipzi1Jd)" class="tdu-one2g"/></g><g filter="url(#iJrh4cb)"><path fill="url(#i6Jbb2d)" class="kohkstb1d"/></g><path class="gt1ciq90h"/><path fill="url(#i77RKXd)" class="t3-xa75qp"/><path class="zu3h95b2s"/><g filter="url(#ioNW49G)"><path fill="url(#ijKZyCd)" class="xqwbulb_w"/></g><g filter="url(#i9eMEWE)"><ellipse transform="rotate(-27.914 13.476 9.958)" class="yxahsabsw"/><ellipse fill="url(#igxWV3b)" transform="rotate(-27.914 13.476 9.958)" class="s4_tz-b4e"/></g><g filter="url(#iWM8avc)"><path fill="url(#iN6oLec)" class="mlm971bus"/><path fill="url(#iSjejDe)" class="mlm971bus"/><path fill="url(#iuf1hzb)" class="mlm971bus"/><path fill="url(#ifncxyb)" class="mlm971bus"/></g><path fill="url(#iaBY2Ge)" class="k0nkw8byw"/><path fill="url(#iaMe28d)" class="k0nkw8byw"/><path fill="url(#ii73fFb)" class="k0nkw8byw"/><g filter="url(#i6YExZc)"><rect fill="url(#i8Cj78c)" class="h7_adxbnt"/></g><g filter="url(#iKigS5b)"><path class="hajtz3bpg"/></g><defs><radialGradient id="iqoVp8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.67857 -3.21429 0 22.929 24.694)" gradientUnits="userSpaceOnUse"><stop class="f26p0p1be"/><stop offset="1" class="tb_z1g16m"/></radialGradient><radialGradient id="iEMJ8Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90626 2.7154 -1.39838 -4.07159 16.688 18.47)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="v130ylbqw"/><stop offset="1" class="cvz68p03p"/></radialGradient><radialGradient id="izCZMmi" cx="0" cy="0" r="1" gradientTransform="matrix(4.375 0 0 11.8756 21.844 29.467)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="rl--s2bxn"/><stop offset="1" class="v-kyyuk0w"/></radialGradient><radialGradient id="iRPAmNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.53821 -7.17442 0 25 21.806)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="sy5bxccsg"/><stop offset="1" class="veojd009w"/></radialGradient><radialGradient id="isNLGfq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.26999 0 0 -10.4063 9.02 28.998)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="pisufpbzg"/><stop offset="1" class="d6clut5cf"/></radialGradient><radialGradient id="iA0Y7Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15625 3.70797 0 7.625 30.342)" gradientUnits="userSpaceOnUse"><stop class="z_vepkinu"/><stop offset="1" class="a_7m96h7b"/></radialGradient><radialGradient id="iPWyAEc" cx="0" cy="0" r="1" gradientTransform="rotate(53.881 -16.076 24.92)scale(2.14706)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rdedbifir"/><stop offset="1" class="co8wuy7pr"/></radialGradient><radialGradient id="iufSQfF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9375 0 0 -4.97705 7.188 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="wi08z5bgf"/><stop offset="1" class="d0gbo-tip"/></radialGradient><radialGradient id="iQWxelH" cx="0" cy="0" r="1" gradientTransform="rotate(-169.849 7.12 8.488)scale(4.49245 1.66714)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="lewnpt48t"/><stop offset="1" class="cmgaqknre"/></radialGradient><radialGradient id="ihUkBIe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.61229 2.22988 -.54256 -1.36555 22.928 18.83)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="eckdnoofv"/></radialGradient><radialGradient id="iC85Iad" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.09385 -11.9992 0 16 18.136)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="m8nvn-czs"/><stop offset=".943" class="dtg8x0b5w"/></radialGradient><radialGradient id="ish3Mwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.01366 -3.3941 0 16 19.276)" gradientUnits="userSpaceOnUse"><stop class="rsw_em86r"/><stop offset="1" class="xfk5_2xnq"/></radialGradient><radialGradient id="i9HiKBe" cx="0" cy="0" r="1" gradientTransform="matrix(.61774 0 0 2.761 6.093 11.904)" gradientUnits="userSpaceOnUse"><stop class="h2db6f6fo"/><stop offset="1" class="eqvqhkbwy"/></radialGradient><radialGradient id="isHF8Xc" cx="0" cy="0" r="1" gradientTransform="matrix(.98754 0 0 2.55399 24.583 10.638)" gradientUnits="userSpaceOnUse"><stop class="jg30e8bxd"/><stop offset="1" class="djf9lpl6o"/></radialGradient><radialGradient id="i9Wns5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9456 -.49377 0 25.622 10.247)" gradientUnits="userSpaceOnUse"><stop class="s5nmtcc-t"/><stop offset="1" class="teoxnoh1q"/></radialGradient><radialGradient id="im5VnDe" cx="0" cy="0" r="1" gradientTransform="rotate(72.208 .425 16.438)scale(9.27527 14.5186)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="mj0fjsb8e"/><stop offset="1" class="gwnz45kfq"/></radialGradient><radialGradient id="ieDqMib" cx="0" cy="0" r="1" gradientTransform="rotate(-137.406 9.643 7.237)scale(5.26375 2.32464)" gradientUnits="userSpaceOnUse"><stop class="zdd7s4gqs"/><stop offset="1" class="a2dspgbsf"/></radialGradient><radialGradient id="iAxGs6b" cx="0" cy="0" r="1" gradientTransform="rotate(123.891 7.389 7.971)scale(12.2137)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="yx5v_dk3v"/><stop offset="1" class="y2y8kppey"/></radialGradient><radialGradient id="iRf4JZc" cx="0" cy="0" r="1" gradientTransform="matrix(7.51562 .70668 -.70668 7.51563 16 11.01)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="ks4acsbkh"/><stop offset="1" class="vaq9-43er"/></radialGradient><radialGradient id="iKlLAxk" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.94614 -5.2449 0 17.504 11.84)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="clwto0w_i"/><stop offset="1" class="qcrtr22ik"/></radialGradient><radialGradient id="idwa9sd" cx="0" cy="0" r="1" gradientTransform="rotate(9.09 -63.66 91.318)scale(7.23896 13.257)" gradientUnits="userSpaceOnUse"><stop offset=".796" class="vcvleub-x"/><stop offset="1" class="ej3feacnd"/></radialGradient><radialGradient id="iYGWSXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.76827 8.72263 0 15.93 15.207)" gradientUnits="userSpaceOnUse"><stop offset=".804" class="gs9t_lbvj"/><stop offset="1" class="ve1n4kbct"/></radialGradient><radialGradient id="i93OjHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -7.14966 0 15.93 8.437)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="wmbw4gubo"/><stop offset=".984" class="xq3-0xbtq"/></radialGradient><radialGradient id="ibDOt9d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25 0 0 -1.00984 19.393 15.797)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="b6rgpfbiy"/><stop offset="1" class="a67ts5brd"/></radialGradient><radialGradient id="iKcOMrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 -2.07813 .9809 -.1475 16.612 12.063)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="cyd9f573s"/><stop offset="1" class="fua9u6bte"/></radialGradient><radialGradient id="iTa88bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.111 10.054)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="sw4f9rbsf"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="a85ejnd0l"/></radialGradient><radialGradient id="ipzi1Jd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.424 .69)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i77RKXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.747 10.054)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="sw4f9rbsf"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="a85ejnd0l"/></radialGradient><radialGradient id="igxWV3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.46 10.273)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iN6oLec" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.50166 -9.15821 0 16 3.5)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="lalxu4bkj"/><stop offset="1" class="w-jvyybfs"/></radialGradient><radialGradient id="iSjejDe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 -2.42187 2.377 1.01214 9.328 9.045)" gradientUnits="userSpaceOnUse"><stop class="f2tw_xhyp"/><stop offset="1" class="h8vr8dbmo"/></radialGradient><radialGradient id="iuf1hzb" cx="0" cy="0" r="1" gradientTransform="rotate(-147.95 12.02 3.515)scale(12.72 10.6468)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="d1-tygbiz"/><stop offset="1" class="ijavpvb5h"/></radialGradient><radialGradient id="iaBY2Ge" cx="0" cy="0" r="1" gradientTransform="matrix(3.07812 0 0 1.2594 18.172 15.16)" gradientUnits="userSpaceOnUse"><stop class="xnke96byi"/><stop offset=".78" class="gvh11p6ie"/></radialGradient><linearGradient id="iZyFstc" x1="10.179" x2="21.429" y1="30.516" y2="30.516" gradientUnits="userSpaceOnUse"><stop offset=".006" class="hwnz8bbgx"/><stop offset="1" class="efhowwcgb"/></linearGradient><linearGradient id="i3QoCfc" x1="8.688" x2="10.844" y1="26.123" y2="26.154" gradientUnits="userSpaceOnUse"><stop class="nqsdswamn"/><stop offset=".231" class="cdku7hg9b"/><stop offset="1" class="oj2-77bel"/></linearGradient><linearGradient id="i8KCMtW" x1="16.594" x2="16.594" y1="30.529" y2="29.623" gradientUnits="userSpaceOnUse"><stop class="v-k4gup8y"/><stop offset="1" class="wjgrr3bwb"/></linearGradient><linearGradient id="iwycdCV" x1="22.797" x2="23.438" y1="26.607" y2="26.592" gradientUnits="userSpaceOnUse"><stop offset=".127" class="t-c91xbtu"/><stop offset="1" class="zl1nvac2j"/></linearGradient><linearGradient id="iIzbeSd" x1="27" x2="26.281" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset="1" class="arric2tqt"/></linearGradient><linearGradient id="iaRjLEb" x1="9.07" x2="8.695" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="og0r_u8md"/><stop offset="1" class="y1qnskbjy"/></linearGradient><linearGradient id="i5kEYjc" x1="20.5" x2="11.49" y1="29.685" y2="29.685" gradientUnits="userSpaceOnUse"><stop class="fatndpbme"/><stop offset="1" class="skyfyac-t"/></linearGradient><linearGradient id="iZEHnib" x1="17.344" x2="18.766" y1="24.764" y2="23.357" gradientUnits="userSpaceOnUse"><stop class="rm14ccb4q"/><stop offset="1" class="d6v2o-bft"/></linearGradient><linearGradient id="iveJrlx" x1="18.875" x2="17.383" y1="23.271" y2="24.693" gradientUnits="userSpaceOnUse"><stop class="btagy7mof"/><stop offset=".531" class="qzlgi0c-c"/></linearGradient><linearGradient id="iyXpkGB" x1="14.875" x2="13.383" y1="23.271" y2="24.693" gradientUnits="userSpaceOnUse"><stop class="s5ud30bqo"/><stop offset=".531" class="rwl3x2rgk"/></linearGradient><linearGradient id="ilrndMd" x1="21.612" x2="8.017" y1="19.604" y2="19.604" gradientUnits="userSpaceOnUse"><stop class="bvm_ssbmv"/><stop offset="1" class="qox001bns"/></linearGradient><linearGradient id="itKMH7c" x1="8.296" x2="8.296" y1="8.928" y2="12.498" gradientUnits="userSpaceOnUse"><stop class="okcn0pbqd"/><stop offset="1" class="zd-keimcv"/></linearGradient><linearGradient id="iTCRhDv" x1="7.125" x2="7.125" y1="13.912" y2="13.185" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></linearGradient><linearGradient id="iaPKrDb" x1="25.191" x2="25.191" y1="8.928" y2="14.062" gradientUnits="userSpaceOnUse"><stop class="wgw2105cx"/><stop offset=".743" class="tkxxt2z6p"/><stop offset="1" class="umazj-pya"/></linearGradient><linearGradient id="i7UuRDd" x1="23.937" x2="8.094" y1="6.435" y2="15.717" gradientUnits="userSpaceOnUse"><stop class="yt0sjmb1z"/><stop offset="1" class="egb-_obih"/></linearGradient><linearGradient id="i3I63Tc" x1="23.726" x2="8.301" y1="6.556" y2="15.592" gradientUnits="userSpaceOnUse"><stop class="g4r6pf4wm"/><stop offset="1" class="xpw6t3bxs"/></linearGradient><linearGradient id="iDo69Ec" x1="9.875" x2="23.344" y1="12.154" y2="12.154" gradientUnits="userSpaceOnUse"><stop class="x2f4vzbdz"/><stop offset=".276" class="ncb26z0py"/></linearGradient><linearGradient id="i601Rnc" x1="15.331" x2="16.659" y1="12.234" y2="12.234" gradientUnits="userSpaceOnUse"><stop class="b8excebxy"/><stop offset="1" class="lkweb2z-l"/></linearGradient><linearGradient id="i9qEEse" x1="15.2" x2="15.653" y1="14.423" y2="13.552" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="i6Jbb2d" x1="18.889" x2="18.575" y1="10.107" y2="10.301" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ijKZyCd" x1="14.491" x2="14.177" y1="10.107" y2="10.3" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifncxyb" x1="23.3" x2="21.625" y1="9.404" y2="7.342" gradientUnits="userSpaceOnUse"><stop class="m9pa3mbws"/><stop offset="1" class="u_tn6mbuw"/></linearGradient><linearGradient id="iaMe28d" x1="17.586" x2="17.961" y1="15.201" y2="15.201" gradientUnits="userSpaceOnUse"><stop class="f-fzccbem"/><stop offset="1" class="hd7z3-brp"/></linearGradient><linearGradient id="ii73fFb" x1="19.234" x2="19.234" y1="15.764" y2="15.568" gradientUnits="userSpaceOnUse"><stop class="u9byv1bdc"/><stop offset="1" class="zk7oijy-r"/></linearGradient><linearGradient id="i8Cj78c" x1="18.216" x2="20.402" y1="15.225" y2="15.225" gradientUnits="userSpaceOnUse"><stop class="ueq20f_ji"/><stop offset="1" class="o69d91bgq"/></linearGradient><filter id="iCP5Hmc" width="9.31" height="4.17" x="11.34" y="25.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.811765 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.635294 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2529" result="effect2_innerShadow_4002_2529"/></filter><filter id="iqDTwGT" width="3.12" height="3.12" x="12.255" y="22.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".25"/></filter><filter id="igh3DuC" width="3.12" height="3.12" x="16.325" y="22.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".25"/></filter><filter id="ieR15jb" width="2.12" height="2.12" x="12.94" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.498039 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="ilpm1Sd" width="2.12" height="2.12" x="16.94" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.180392 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="iQeNBZd" width="2.05" height="2.05" x="16.975" y="22.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".05"/></filter><filter id="iBV1Jwe" width="2.05" height="2.05" x="12.975" y="22.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".05"/></filter><filter id="idcg3eF" width="14.359" height="6.364" x="8.82" y="15.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.87451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="ieZ8SXb" width="18.043" height="18.043" x="6.925" y="1.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".125"/></filter><filter id="i2cwuIe" width="16.155" height="16.155" x="7.869" y="2.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".15"/></filter><filter id="iYEb1ed" width="14.583" height="16.385" x="9.073" y="2.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".75"/></filter><filter id="iIewwEd" width="10.191" height="12.205" x="10.834" y="4.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.298039 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="i3IoU4b" width="2.877" height="3.682" x="14.328" y="9.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".25"/></filter><filter id="iNZhCPe" width="2.377" height="3.182" x="14.741" y="9.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.596078 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/><feGaussianBlur result="effect2_foregroundBlur_4002_2529" stdDeviation=".125"/></filter><filter id="iVvJayc" width="3.001" height="1.285" x="16.871" y="9.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="iASi9rb" width="3.001" height="1.285" x="11.986" y="9.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="itr8vjc" width="2.253" height="1.091" x="12.094" y="7.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.113725 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="iIeVwbe" width="2.253" height="1.091" x="17.511" y="7.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.113725 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter><filter id="ip8TY7L" width=".786" height=".696" x="17.377" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".05"/></filter><filter id="iJrh4cb" width=".891" height=".913" x="18.217" y="9.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".1"/></filter><filter id="ioNW49G" width=".986" height="1.04" x="13.774" y="9.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".1"/></filter><filter id="i9eMEWE" width=".912" height=".704" x="13.019" y="9.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".05"/></filter><filter id="iWM8avc" width="14.6" height="5.86" x="8.7" y="3.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.215686 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.219608 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2529" result="effect2_innerShadow_4002_2529"/></filter><filter id="i6YExZc" width="3.344" height=".781" x="17.797" y="14.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2529" stdDeviation=".125"/></filter><filter id="iKigS5b" width="6.686" height="4.857" x="16.38" y="13.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.486275 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2529"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-astronaut" /></template>
<style>
.a_7m96h7b {
  stop-color: var(--svg-color--c9b5de, #C9B5DE);
  stop-opacity: 0;
}

.a0yqjpbvz {
  fill: var(--svg-color--351c24, #351C24);
  d: path("M10.843 14.054c.292 2.117 2.175 3.694 4.404 3.694h2.138c2.23 0 4.112-1.577 4.404-3.694c.133-2.043.268-4.078.367-6.12c-.012-.831-.697-1.518-1.563-1.552h-1.587c-1.082 0-2.061-.611-2.506-1.565a.75.75 0 0 0-.697-.454H14.36c-2.092 0-3.787 1.64-3.787 3.665c0 2.018.132 4.003.27 6.026");
}

.a2dspgbsf {
  stop-color: var(--svg-color--a29ca9, #A29CA9);
  stop-opacity: 0;
}

.a34p3q8ba {
  fill: var(--svg-color--8f383f, #8F383F);
  d: path("m12.505 8.747l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.11a.268.268 0 0 1-.093.53a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.455.193");
}

.a67ts5brd {
  stop-color: var(--svg-color--c16f2d, #C16F2D);
  stop-opacity: 0;
}

.a85ejnd0l {
  stop-color: var(--svg-color--66453a, #66453A);
}

.arric2tqt {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
  stop-opacity: 0;
}

.asil7b01k {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.071 10.082c.266-.467.67-.836 1.538-.836c.38 0 .746.105 1.072.369c.27.217.233.495.025.6l-.556.316c-.652-.21-1.373-.239-2.079-.45");
}

.aymqfdc9h {
  d: path("M18 25.05a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.b6rgpfbiy {
  stop-color: var(--svg-color--8a3436, #8A3436);
}

.b8excebxy {
  stop-color: var(--svg-color--ffb725, #FFB725);
}

.bk54hjl7x {
  d: path("M19.68 25.98h-7.37c-.45 0-.82.37-.82.82V30h9.01v-3.2c0-.46-.36-.82-.82-.82");
}

.bmdpf4wuk {
  d: path("M21.6 18.47H10.39c-3.23 1.92-5.4 5.44-5.4 9.47v2.05h22.02v-2.05c0-4.03-2.17-7.55-5.41-9.47");
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.btagy7mof {
  stop-color: var(--svg-color--fb4f70, #FB4F70);
}

.bvm_ssbmv {
  stop-color: var(--svg-color--f0e4fc, #F0E4FC);
}

.bxq8_bb0o {
  fill: var(--svg-color--000, #000);
  d: path("M17.602 10.47c0-.285.227-.512.511-.512a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.c0156tydt {
  fill: var(--svg-color--d1b8d6, #D1B8D6);
  d: path("M17.885 25.235a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.cdcaw77-g {
  d: path("M10.842 9.553h.012l-.01-.265l-.01-2.147c.075-3.48 10.072-3.36 10.19.046l-.118 4.915c-.123 2.802-2.312 4.684-4.983 4.684c-2.672 0-4.86-1.882-4.984-4.684z");
}

.cdku7hg9b {
  stop-color: var(--svg-color--d3cade, #D3CADE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clwto0w_i {
  stop-color: var(--svg-color--ffca32, #FFCA32);
}

.cmgaqknre {
  stop-color: var(--svg-color--b3b2b5, #B3B2B5);
  stop-opacity: 0;
}

.co8wuy7pr {
  stop-color: var(--svg-color--3e7cd9, #3E7CD9);
}

.cvz68p03p {
  stop-color: var(--svg-color--c2b2d7, #C2B2D7);
  stop-opacity: 0;
}

.cyd9f573s {
  stop-color: var(--svg-color--ffd03e, #FFD03E);
}

.d0gbo-tip {
  stop-color: var(--svg-color--648cbc, #648CBC);
}

.d1-tygbiz {
  stop-color: var(--svg-color--493b54, #493B54);
  stop-opacity: 0;
}

.d6clut5cf {
  stop-color: var(--svg-color--c4c1c5, #C4C1C5);
}

.d6v2o-bft {
  stop-color: var(--svg-color--f13c6a, #F13C6A);
}

.djf9lpl6o {
  stop-color: var(--svg-color--cdcad1, #CDCAD1);
  stop-opacity: 0;
}

.dm1r4g2jn {
  d: path("M16 18.526a7.516 7.516 0 1 0 0-15.031a7.516 7.516 0 0 0 0 15.03");
}

.dnazjxbei {
  fill: var(--svg-color--d6bcdb, #D6BCDB);
  d: path("M13.815 25.235a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.dtg8x0b5w {
  stop-color: var(--svg-color--c9a7ef, #C9A7EF);
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.eckdnoofv {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
  stop-opacity: 0;
}

.efhowwcgb {
  stop-color: var(--svg-color--e7d8f7, #E7D8F7);
}

.egb-_obih {
  stop-color: var(--svg-color--a6a2ab, #A6A2AB);
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.ej3feacnd {
  stop-color: var(--svg-color--a77a09, #A77A09);
}

.ej4qybc4v {
  d: path("M14 25.05a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.eqvqhkbwy {
  stop-color: var(--svg-color--ada9b1, #ADA9B1);
  stop-opacity: 0;
}

.eu4ef4o7o {
  fill: var(--svg-color--d9cde8, #D9CDE8);
  d: path("m9.003 29.99l.017-.01V19.431a10.98 10.98 0 0 0-4.03 8.51v2.05z");
}

.f-fzccbem {
  stop-color: var(--svg-color--7a6566, #7A6566);
}

.f26p0p1be {
  stop-color: var(--svg-color--f7efff, #F7EFFF);
}

.f2tw_xhyp {
  stop-color: var(--svg-color--6c6176, #6C6176);
}

.fatndpbme {
  stop-color: var(--svg-color--cdc0da, #CDC0DA);
}

.ft5dv1b6b {
  fill: none;
}

.fua9u6bte {
  stop-color: var(--svg-color--ffd03e, #FFD03E);
  stop-opacity: 0;
}

.g4r6pf4wm {
  stop-color: var(--svg-color--bab4c1, #BAB4C1);
}

.gafovlbte {
  width: 4.406px;
  height: 4.984px;
  x: 6.093px;
  y: 8.928px;
  rx: 0.75px;
}

.gs9t_lbvj {
  stop-color: var(--svg-color--ac671a, #AC671A);
  stop-opacity: 0;
}

.gt1ciq90h {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.538 9.305c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.gvh11p6ie {
  stop-color: var(--svg-color--463d38, #463D38);
}

.gwnz45kfq {
  stop-color: var(--svg-color--9f98a6, #9F98A6);
}

.h2db6f6fo {
  stop-color: var(--svg-color--ada9b1, #ADA9B1);
}

.h7_adxbnt {
  width: 2.844px;
  height: 0.281px;
  x: 18.047px;
  y: 14.943px;
  rx: 0.141px;
}

.h8vr8dbmo {
  stop-color: var(--svg-color--6c6176, #6C6176);
  stop-opacity: 0;
}

.hajtz3bpg {
  fill: var(--svg-color--b9b2bf, #B9B2BF);
  d: path("M23.016 13.71h-.956c-.4-.01-.78.19-1 .53a6.04 6.04 0 0 1-3.92 2.67c-.44.08-.76.46-.76.91v.696a7.52 7.52 0 0 0 6.636-4.806");
}

.hd7z3-brp {
  stop-color: var(--svg-color--7a6566, #7A6566);
  stop-opacity: 0;
}

.hwnz8bbgx {
  stop-color: var(--svg-color--dbcfea, #DBCFEA);
}

.ijavpvb5h {
  stop-color: var(--svg-color--493b54, #493B54);
}

.jg30e8bxd {
  stop-color: var(--svg-color--cdcad1, #CDCAD1);
}

.k0nkw8byw {
  d: path("M18.02 15.66h2.97c.28 0 .5-.22.5-.5s-.22-.5-.5-.5h-2.97c-.28 0-.5.22-.5.5s.23.5.5.5");
}

.k14mqzbhm {
  d: path("M15.947 2c-4.98 0-9.01 4.03-9.01 9.01s4.03 9.01 9.01 9.01s9.01-4.03 9.01-9.01S20.917 2 15.947 2");
}

.k4tl-1b7s {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.047 9.766c.063.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.324-.135.388-.05");
}

.k8p9e6b4e {
  d: path("m9.003 29.99l.017-.01V19.431a10.98 10.98 0 0 0-4.03 8.51v2.05z");
}

.kil27mbcd {
  d: path("M23.18 18.397c0 1.462-2.782 3.515-7.18 3.515c-4.469-.047-7.18-2.053-7.18-3.515s3.215-2.649 7.18-2.649s7.18 1.186 7.18 2.649");
}

.kohkstb1d {
  d: path("M18.908 10.351a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.ks4acsbkh {
  stop-color: var(--svg-color--543b3e, #543B3E);
  stop-opacity: 0;
}

.lalxu4bkj {
  stop-color: var(--svg-color--848286, #848286);
}

.lewnpt48t {
  stop-color: var(--svg-color--a59eac, #A59EAC);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkweb2z-l {
  stop-color: var(--svg-color--ffc822, #FFC822);
}

.lz2odobri {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.32 9.305c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.m8nvn-czs {
  stop-color: var(--svg-color--c9a7ef, #C9A7EF);
  stop-opacity: 0;
}

.m9pa3mbws {
  stop-color: var(--svg-color--726080, #726080);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mblf-fbmn {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.787 10.082c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.6l.557.316c.651-.21 1.372-.239 2.078-.45");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mj0fjsb8e {
  stop-color: var(--svg-color--9f98a6, #9F98A6);
  stop-opacity: 0;
}

.mlm971bus {
  d: path("M16 6.8a12 12 0 0 1 7.3 2.46c-.79-3.3-3.76-5.76-7.3-5.76S9.49 5.96 8.7 9.26A12 12 0 0 1 16 6.8");
}

.ncb26z0py {
  stop-color: var(--svg-color--503645, #503645);
}

.nh0n8dbkp {
  fill: var(--svg-color--8f373f, #8F373F);
  fill-rule: evenodd;
  d: path("m19.634 8.29l-.138.23za.268.268 0 0 1-.276.46l-.004-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.nqsdswamn {
  stop-color: var(--svg-color--baa7d0, #BAA7D0);
}

.o69d91bgq {
  stop-color: var(--svg-color--5c595d, #5C595D);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.og0r_u8md {
  stop-color: var(--svg-color--bbb7c0, #BBB7C0);
}

.oj2-77bel {
  stop-color: var(--svg-color--d3cade, #D3CADE);
  stop-opacity: 0;
}

.okcn0pbqd {
  stop-color: var(--svg-color--919092, #919092);
}

.oy755iz6f {
  width: 4.406px;
  height: 4.984px;
  x: 21.499px;
  y: 8.928px;
  rx: 0.75px;
}

.pisufpbzg {
  stop-color: var(--svg-color--c4c1c5, #C4C1C5);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.qcrtr22ik {
  stop-color: var(--svg-color--db892b, #DB892B);
}

.qox001bns {
  stop-color: var(--svg-color--d8d0e0, #D8D0E0);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw-0xrp0e {
  d: path("m15.547 10.455l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.646-.377-.765 0");
}

.qzlgi0c-c {
  stop-color: var(--svg-color--f34b6c, #F34B6C);
  stop-opacity: 0;
}

.rdedbifir {
  stop-color: var(--svg-color--3d8ee2, #3D8EE2);
}

.rl--s2bxn {
  stop-color: var(--svg-color--f6edff, #F6EDFF);
  stop-opacity: 0;
}

.rm14ccb4q {
  stop-color: var(--svg-color--ee3880, #EE3880);
}

.rrk_4bb5u {
  d: path("M23 19.45v10.54h4v-2.37c-.09-3.29-1.63-6.21-4-8.17");
}

.rsw_em86r {
  stop-color: var(--svg-color--d7d2dd, #D7D2DD);
}

.rwl3x2rgk {
  stop-color: var(--svg-color--4d90df, #4D90DF);
  stop-opacity: 0;
}

.s4_tz-b4e {
  cx: 13.476px;
  cy: 9.958px;
  rx: 0.389px;
  ry: 0.197px;
}

.s5nmtcc-t {
  stop-color: var(--svg-color--dcdade, #DCDADE);
}

.s5ud30bqo {
  stop-color: var(--svg-color--4d90df, #4D90DF);
}

.sa_ie2xef {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14 24.865a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.siu29i9yh {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.537 10.594l-.684 1.7a.54.54 0 0 0 .52.699h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.613 0");
}

.skyfyac-t {
  stop-color: var(--svg-color--beb1cc, #BEB1CC);
}

.sw4f9rbsf {
  stop-color: var(--svg-color--724d44, #724D44);
}

.sy5bxccsg {
  stop-color: var(--svg-color--ded6eb, #DED6EB);
  stop-opacity: 0;
}

.t-c91xbtu {
  stop-color: var(--svg-color--c8b9da, #C8B9DA);
}

.t3-xa75qp {
  d: path("M13.745 9.577a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.tb_z1g16m {
  stop-color: var(--svg-color--f7efff, #F7EFFF);
  stop-opacity: 0;
}

.tdu-one2g {
  d: path("M18.047 9.766c.063.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.324-.135.388-.05");
}

.teoxnoh1q {
  stop-color: var(--svg-color--dcdade, #DCDADE);
  stop-opacity: 0;
}

.tkxxt2z6p {
  stop-color: var(--svg-color--afa9b7, #AFA9B7);
}

.u_tn6mbuw {
  stop-color: var(--svg-color--726080, #726080);
  stop-opacity: 0;
}

.u9byv1bdc {
  stop-color: var(--svg-color--3d3438, #3D3438);
}

.ueq20f_ji {
  stop-color: var(--svg-color--797278, #797278);
}

.umazj-pya {
  stop-color: var(--svg-color--8e8895, #8E8895);
}

.uy-elybtc {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
}

.v-k4gup8y {
  stop-color: var(--svg-color--c9b4e0, #C9B4E0);
}

.v-kyyuk0w {
  stop-color: var(--svg-color--fdfaff, #FDFAFF);
}

.v130ylbqw {
  stop-color: var(--svg-color--b096cb, #B096CB);
}

.vaq9-43er {
  stop-color: var(--svg-color--543b3e, #543B3E);
}

.vcvleub-x {
  stop-color: var(--svg-color--e4ae11, #E4AE11);
  stop-opacity: 0;
}

.ve1n4kbct {
  stop-color: var(--svg-color--753e11, #753E11);
}

.veojd009w {
  stop-color: var(--svg-color--d8c5ec, #D8C5EC);
}

.vlvwenz1w {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18 24.865a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.w-jvyybfs {
  stop-color: var(--svg-color--655d6d, #655D6D);
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.wi08z5bgf {
  stop-color: var(--svg-color--3776c0, #3776C0);
}

.wjgrr3bwb {
  stop-color: var(--svg-color--c9b4e0, #C9B4E0);
  stop-opacity: 0;
}

.wmbw4gubo {
  stop-color: var(--svg-color--d27f2d, #D27F2D);
  stop-opacity: 0;
}

.wv0-ezbvn {
  d: path("M18.113 9.577a.892.892 0 0 1 .86 1.127H17.25a.896.896 0 0 1 .864-1.128");
}

.wx8zj3ibb {
  d: path("M7.36 28.66v-1.62c0-.19-.15-.34-.34-.34H5.06c-.03.26-.05.53-.06.8l.01 1.5h2.02c.18 0 .33-.15.33-.34");
}

.x2f4vzbdz {
  stop-color: var(--svg-color--5c4355, #5C4355);
}

.xagcxqb0l {
  d: path("M15.947 2.238a8.767 8.767 0 0 0-8.772 8.772a8.767 8.767 0 0 0 8.772 8.772a8.767 8.767 0 0 0 8.772-8.772c0-4.848-3.934-8.772-8.772-8.772");
}

.xf2opsb3a {
  fill: var(--svg-color--ebdef9, #EBDEF9);
  d: path("M23 19.45v10.54h4v-2.37c-.09-3.29-1.63-6.21-4-8.17");
}

.xfk5_2xnq {
  stop-color: var(--svg-color--d7d2dd, #D7D2DD);
  stop-opacity: 0;
}

.xnke96byi {
  stop-color: var(--svg-color--736a6c, #736A6C);
}

.xpw6t3bxs {
  stop-color: var(--svg-color--bdb7c4, #BDB7C4);
}

.xq3-0xbtq {
  stop-color: var(--svg-color--973d4a, #973D4A);
}

.xqwbulb_w {
  d: path("M14.56 10.364c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

.xtn5m1b_o {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.531 13.339a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.041a3 3 0 0 1-1.399.339c-.513 0-.994-.124-1.398-.339Z");
}

.y1qnskbjy {
  stop-color: var(--svg-color--c1b1d5, #C1B1D5);
  stop-opacity: 0;
}

.y2y8kppey {
  stop-color: var(--svg-color--c8bebf, #C8BEBF);
}

.yt0sjmb1z {
  stop-color: var(--svg-color--d4d0d7, #D4D0D7);
}

.yx5v_dk3v {
  stop-color: var(--svg-color--877f8d, #877F8D);
}

.yxahsabsw {
  cx: 13.476px;
  cy: 9.958px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.yz039z2rc {
  d: path("M15.947 3.232A7.773 7.773 0 0 0 8.17 11.01a7.773 7.773 0 0 0 7.778 7.778a7.779 7.779 0 0 0 0-15.555");
}

.z_vepkinu {
  stop-color: var(--svg-color--c9b5de, #C9B5DE);
}

.zd-keimcv {
  stop-color: var(--svg-color--938b9c, #938B9C);
}

.zdd7s4gqs {
  stop-color: var(--svg-color--a29ca9, #A29CA9);
}

.zk7oijy-r {
  stop-color: var(--svg-color--3d3438, #3D3438);
  stop-opacity: 0;
}

.zl1nvac2j {
  stop-color: var(--svg-color--c8b9da, #C8B9DA);
  stop-opacity: 0;
}

.zu3h95b2s {
  fill: var(--svg-color--000, #000);
  d: path("M14.256 10.47a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

</style>
