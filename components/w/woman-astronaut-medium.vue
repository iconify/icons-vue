<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZyFstc)" class="bmdpf4wuk"/><path fill="url(#i3QoCfc)" class="bmdpf4wuk"/><path fill="url(#izDVcVd)" class="bmdpf4wuk"/><path fill="url(#iEMJ8Bb)" class="bmdpf4wuk"/><path fill="url(#i8KCMtW)" class="bmdpf4wuk"/><path class="xf2opsb3a"/><path fill="url(#izCZMmi)" class="rrk_4bb5u"/><path fill="url(#iMLgq5d)" class="rrk_4bb5u"/><path fill="url(#iIzbeSd)" class="rrk_4bb5u"/><path fill="url(#i7Sp7Xb)" class="rrk_4bb5u"/><path class="eu4ef4o7o"/><path fill="url(#isNLGfq)" class="k8p9e6b4e"/><path fill="url(#iaRjLEb)" class="k8p9e6b4e"/><path fill="url(#iA0Y7Qb)" class="k8p9e6b4e"/><g filter="url(#inCIjce)"><path fill="url(#i5kEYjc)" class="bk54hjl7x"/></g><g filter="url(#iR5Arhb)"><path class="dnazjxbei"/></g><g filter="url(#ibaqR2O)"><path class="c0156tydt"/></g><g filter="url(#iKekugb)"><path fill="url(#iPWyAEc)" class="ej4qybc4v"/></g><g filter="url(#ix7DwPf)"><path fill="url(#ikwMLDb)" class="aymqfdc9h"/></g><g filter="url(#i30cuKd)"><path stroke="url(#iveJrlx)" class="vlvwenz1w"/></g><g filter="url(#iZFwsdd)"><path stroke="url(#iyXpkGB)" class="sa_ie2xef"/></g><path fill="url(#iufSQfF)" class="wx8zj3ibb"/><g filter="url(#i8K3hPb)"><path fill="url(#ilrndMd)" class="kil27mbcd"/><path fill="url(#iQWxelH)" class="kil27mbcd"/><path fill="url(#ihUkBIe)" class="kil27mbcd"/></g><path fill="url(#iC85Iad)" class="kil27mbcd"/><path fill="url(#ish3Mwd)" class="kil27mbcd"/><rect fill="url(#itKMH7c)" class="gafovlbte"/><rect fill="url(#iTCRhDv)" class="gafovlbte"/><rect fill="url(#i9HiKBe)" class="gafovlbte"/><rect fill="url(#iaPKrDb)" class="oy755iz6f"/><rect fill="url(#isHF8Xc)" class="oy755iz6f"/><rect fill="url(#i9Wns5d)" class="oy755iz6f"/><path fill="url(#i7UuRDd)" class="k14mqzbhm"/><path fill="url(#im5VnDe)" class="k14mqzbhm"/><path fill="url(#ieDqMib)" class="k14mqzbhm"/><g filter="url(#iMreSxe)"><path fill="url(#iO1Z0sd)" class="jzs5yxmnp"/></g><g filter="url(#ibA70uL)"><path fill="url(#iAxGs6b)" class="yz039z2rc"/></g><path fill="url(#ihRbpqd)" class="dm1r4g2jn"/><path fill="url(#idxLs5c)" class="dm1r4g2jn"/><g filter="url(#irIoOey)"><path class="o3idhyb3x"/></g><g filter="url(#iByXIQd)"><path fill="url(#itQv6Yc)" class="hu1wo0ktt"/><path fill="url(#iZeisBb)" class="hu1wo0ktt"/><path fill="url(#ik6N8Hb)" class="hu1wo0ktt"/><path fill="url(#iFPijuz)" class="hu1wo0ktt"/><path fill="url(#idiDTne)" class="hu1wo0ktt"/><path fill="url(#i4g8eEb)" class="hu1wo0ktt"/><path fill="url(#indRJcd)" class="hu1wo0ktt"/><path fill="url(#izNcAQb)" class="hu1wo0ktt"/></g><path fill="url(#ij5rNOd)" class="hu1wo0ktt"/><path fill="url(#iQFPA7c)" class="hu1wo0ktt"/><g filter="url(#i1GNEib)"><path class="ia0--tbzc"/></g><g filter="url(#iwGaacb)"><path fill="url(#i2tgNWc)" class="q2kk9ivkm"/><path fill="url(#ivYK2hb)" class="q2kk9ivkm"/><path fill="url(#i15yC2b)" class="q2kk9ivkm"/><path fill="url(#iUuAsmd)" class="q2kk9ivkm"/></g><g filter="url(#iuVMaiD)"><path fill="url(#irxl2gc)" class="q2kk9ivkm"/></g><g filter="url(#iehUSnd)"><path stroke="url(#iKyUxQV)" class="euh5i4bis"/></g><path class="s-k35n56i"/><g filter="url(#ieA5gpd)"><path class="cbhbs1bsz"/></g><g filter="url(#iXSEzzd)"><path class="wiwspbbdz"/></g><g filter="url(#ifKsidb)"><path class="sc0spz58z"/></g><g filter="url(#iRPMsqd)"><path clip-rule="evenodd" class="mx1wpgsnc"/></g><path class="etas1ty4n"/><path fill="url(#icaHxcu)" class="ey53_wbbj"/><path class="ydir0-dqg"/><g filter="url(#ig6zxSc)"><path class="cr61bhm2o"/><path fill="url(#iedeGxc)" class="r7b1qibep"/></g><g filter="url(#ir5r1Rl)"><path fill="url(#igHVFsc)" class="s6tilzbvz"/></g><path class="poqmi3b7l"/><path fill="url(#ikzvYue)" class="gzu04ob0t"/><path class="wzv9_kb2h"/><g filter="url(#iUh8cnY)"><path fill="url(#iBENUEb)" class="run8vgloz"/></g><g filter="url(#iE3k0Hd)"><ellipse transform="rotate(-27.914 13.546 9.93)" class="i37lqhbve"/><ellipse fill="url(#ix9wf9p)" transform="rotate(-27.914 13.546 9.93)" class="yhibo8bbq"/></g><g filter="url(#iRjlMXc)"><path fill="url(#iN6oLec)" class="mlm971bus"/><path fill="url(#iSjejDe)" class="mlm971bus"/><path fill="url(#iuf1hzb)" class="mlm971bus"/><path fill="url(#ifncxyb)" class="mlm971bus"/></g><path fill="url(#iaBY2Ge)" class="k0nkw8byw"/><path fill="url(#iFvBH3d)" class="k0nkw8byw"/><path fill="url(#ii73fFb)" class="k0nkw8byw"/><g filter="url(#i4W2h6N)"><rect fill="url(#i8Cj78c)" class="h7_adxbnt"/></g><g filter="url(#iLzB0qd)"><path class="hajtz3bpg"/></g><defs><radialGradient id="izDVcVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.67857 -3.21429 0 22.929 24.695)" gradientUnits="userSpaceOnUse"><stop class="f26p0p1be"/><stop offset="1" class="tb_z1g16m"/></radialGradient><radialGradient id="iEMJ8Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.90626 2.7154 -1.39838 -4.07159 16.688 18.47)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="v130ylbqw"/><stop offset="1" class="cvz68p03p"/></radialGradient><radialGradient id="izCZMmi" cx="0" cy="0" r="1" gradientTransform="matrix(4.375 0 0 11.8756 21.844 29.467)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="rl--s2bxn"/><stop offset="1" class="v-kyyuk0w"/></radialGradient><radialGradient id="i7Sp7Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.53821 -7.17442 0 25 21.807)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="sy5bxccsg"/><stop offset="1" class="veojd009w"/></radialGradient><radialGradient id="isNLGfq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.26999 0 0 -10.4063 9.02 28.998)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="pisufpbzg"/><stop offset="1" class="d6clut5cf"/></radialGradient><radialGradient id="iA0Y7Qb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15625 3.70797 0 7.625 30.342)" gradientUnits="userSpaceOnUse"><stop class="z_vepkinu"/><stop offset="1" class="a_7m96h7b"/></radialGradient><radialGradient id="iPWyAEc" cx="0" cy="0" r="1" gradientTransform="rotate(53.881 -16.076 24.92)scale(2.14706)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="rdedbifir"/><stop offset="1" class="co8wuy7pr"/></radialGradient><radialGradient id="iufSQfF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9375 0 0 -4.97705 7.188 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="wi08z5bgf"/><stop offset="1" class="d0gbo-tip"/></radialGradient><radialGradient id="iQWxelH" cx="0" cy="0" r="1" gradientTransform="rotate(-169.849 7.12 8.488)scale(4.49245 1.66714)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="lewnpt48t"/><stop offset="1" class="cmgaqknre"/></radialGradient><radialGradient id="ihUkBIe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.61229 2.22988 -.54256 -1.36555 22.928 18.83)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="eckdnoofv"/></radialGradient><radialGradient id="iC85Iad" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.09385 -11.9992 0 16 18.136)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="m8nvn-czs"/><stop offset=".943" class="dtg8x0b5w"/></radialGradient><radialGradient id="ish3Mwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.01366 -3.3941 0 16 19.276)" gradientUnits="userSpaceOnUse"><stop class="rsw_em86r"/><stop offset="1" class="xfk5_2xnq"/></radialGradient><radialGradient id="i9HiKBe" cx="0" cy="0" r="1" gradientTransform="matrix(.61774 0 0 2.761 6.093 11.904)" gradientUnits="userSpaceOnUse"><stop class="h2db6f6fo"/><stop offset="1" class="eqvqhkbwy"/></radialGradient><radialGradient id="isHF8Xc" cx="0" cy="0" r="1" gradientTransform="matrix(.98754 0 0 2.55399 24.583 10.638)" gradientUnits="userSpaceOnUse"><stop class="jg30e8bxd"/><stop offset="1" class="djf9lpl6o"/></radialGradient><radialGradient id="i9Wns5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9456 -.49377 0 25.622 10.247)" gradientUnits="userSpaceOnUse"><stop class="s5nmtcc-t"/><stop offset="1" class="teoxnoh1q"/></radialGradient><radialGradient id="im5VnDe" cx="0" cy="0" r="1" gradientTransform="rotate(72.208 .425 16.438)scale(9.27527 14.5186)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="mj0fjsb8e"/><stop offset="1" class="gwnz45kfq"/></radialGradient><radialGradient id="ieDqMib" cx="0" cy="0" r="1" gradientTransform="rotate(-137.406 9.643 7.237)scale(5.26375 2.32464)" gradientUnits="userSpaceOnUse"><stop class="zdd7s4gqs"/><stop offset="1" class="a2dspgbsf"/></radialGradient><radialGradient id="iAxGs6b" cx="0" cy="0" r="1" gradientTransform="rotate(123.891 7.389 7.971)scale(12.2137)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="yx5v_dk3v"/><stop offset="1" class="y2y8kppey"/></radialGradient><radialGradient id="idxLs5c" cx="0" cy="0" r="1" gradientTransform="rotate(6.45 -87.936 138.738)scale(8.5401)" gradientUnits="userSpaceOnUse"><stop offset=".902" class="vzafmqbsv"/><stop offset="1" class="kfjcj3jmf"/></radialGradient><radialGradient id="itQv6Yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.29935 -6.33826 0 17.412 11.48)" gradientUnits="userSpaceOnUse"><stop offset=".454" class="sner6009v"/><stop offset="1" class="v6xww-c3b"/></radialGradient><radialGradient id="iZeisBb" cx="0" cy="0" r="1" gradientTransform="rotate(109.923 2.666 12.455)scale(2.7512 3.08924)" gradientUnits="userSpaceOnUse"><stop class="li31f0e7y"/><stop offset="1" class="hlf8kht3i"/></radialGradient><radialGradient id="ik6N8Hb" cx="0" cy="0" r="1" gradientTransform="matrix(7.64752 0 0 15.4505 13.536 11.198)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="t-wzl5urp"/><stop offset="1" class="hm8wlgbod"/></radialGradient><radialGradient id="iFPijuz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.82897 11.5761 0 15.838 16.386)" gradientUnits="userSpaceOnUse"><stop offset=".662" class="ptm-cybry"/><stop offset=".974" class="jtu9owgtk"/></radialGradient><radialGradient id="idiDTne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.10572 7.69034 0 15.838 15.2)" gradientUnits="userSpaceOnUse"><stop offset=".862" class="s1j2c6bmi"/><stop offset="1" class="cu3-vm6cs"/></radialGradient><radialGradient id="i4g8eEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .96094 -1.45034 0 13.465 10.582)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="ym__citvk"/><stop offset="1" class="ayzp7ibwz"/></radialGradient><radialGradient id="indRJcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.29688 -1.46127 0 18.2 10.355)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="ym__citvk"/><stop offset="1" class="ayzp7ibwz"/></radialGradient><radialGradient id="izNcAQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.82787 -.39867 .1693 .77622 19.105 14.84)" gradientUnits="userSpaceOnUse"><stop class="evzbhtbhj"/><stop offset="1" class="slkz9fi8m"/></radialGradient><radialGradient id="ij5rNOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.77716 -6.52234 0 15.838 8.43)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="ve84mtm6i"/><stop offset=".963" class="w44-0gbtd"/></radialGradient><radialGradient id="iQFPA7c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25 0 0 -1.00984 19.302 15.79)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="o-5rynguc"/><stop offset="1" class="wge1qeybz"/></radialGradient><radialGradient id="ivYK2hb" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 0 0 -.3217 16.471 12.211)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="k3jnt_bvt"/><stop offset="1" class="khh_otzli"/></radialGradient><radialGradient id="i15yC2b" cx="0" cy="0" r="1" gradientTransform="matrix(.35157 2.33593 -.2692 .04052 16.213 10.399)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="k3jnt_bvt"/><stop offset="1" class="khh_otzli"/></radialGradient><radialGradient id="icaHxcu" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 10.026)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="l1h7j0zuv"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="mvq4qdpsh"/></radialGradient><radialGradient id="iedeGxc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.453 .659)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikzvYue" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 10.026)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="sw4f9rbsf"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="a85ejnd0l"/></radialGradient><radialGradient id="ix9wf9p" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.531 10.245)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iN6oLec" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.50166 -9.15821 0 16 3.5)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="lalxu4bkj"/><stop offset="1" class="w-jvyybfs"/></radialGradient><radialGradient id="iSjejDe" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 -2.42187 2.377 1.01214 9.328 9.045)" gradientUnits="userSpaceOnUse"><stop class="f2tw_xhyp"/><stop offset="1" class="h8vr8dbmo"/></radialGradient><radialGradient id="iuf1hzb" cx="0" cy="0" r="1" gradientTransform="rotate(-147.95 12.02 3.515)scale(12.72 10.6468)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="d1-tygbiz"/><stop offset="1" class="ijavpvb5h"/></radialGradient><radialGradient id="iaBY2Ge" cx="0" cy="0" r="1" gradientTransform="matrix(3.07812 0 0 1.2594 18.172 15.16)" gradientUnits="userSpaceOnUse"><stop class="xnke96byi"/><stop offset=".78" class="gvh11p6ie"/></radialGradient><linearGradient id="iZyFstc" x1="10.179" x2="21.429" y1="30.516" y2="30.516" gradientUnits="userSpaceOnUse"><stop offset=".006" class="hwnz8bbgx"/><stop offset="1" class="efhowwcgb"/></linearGradient><linearGradient id="i3QoCfc" x1="8.688" x2="10.844" y1="26.123" y2="26.154" gradientUnits="userSpaceOnUse"><stop class="nqsdswamn"/><stop offset=".231" class="cdku7hg9b"/><stop offset="1" class="oj2-77bel"/></linearGradient><linearGradient id="i8KCMtW" x1="16.594" x2="16.594" y1="30.529" y2="29.623" gradientUnits="userSpaceOnUse"><stop class="v-k4gup8y"/><stop offset="1" class="wjgrr3bwb"/></linearGradient><linearGradient id="iMLgq5d" x1="22.797" x2="23.438" y1="26.608" y2="26.592" gradientUnits="userSpaceOnUse"><stop offset=".127" class="t-c91xbtu"/><stop offset="1" class="zl1nvac2j"/></linearGradient><linearGradient id="iIzbeSd" x1="27" x2="26.281" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="uy-elybtc"/><stop offset="1" class="arric2tqt"/></linearGradient><linearGradient id="iaRjLEb" x1="9.07" x2="8.695" y1="29.99" y2="29.99" gradientUnits="userSpaceOnUse"><stop class="og0r_u8md"/><stop offset="1" class="y1qnskbjy"/></linearGradient><linearGradient id="i5kEYjc" x1="20.5" x2="11.49" y1="29.685" y2="29.685" gradientUnits="userSpaceOnUse"><stop class="fatndpbme"/><stop offset="1" class="skyfyac-t"/></linearGradient><linearGradient id="ikwMLDb" x1="17.344" x2="18.766" y1="24.764" y2="23.358" gradientUnits="userSpaceOnUse"><stop class="rm14ccb4q"/><stop offset="1" class="d6v2o-bft"/></linearGradient><linearGradient id="iveJrlx" x1="18.875" x2="17.383" y1="23.271" y2="24.693" gradientUnits="userSpaceOnUse"><stop class="btagy7mof"/><stop offset=".531" class="qzlgi0c-c"/></linearGradient><linearGradient id="iyXpkGB" x1="14.875" x2="13.383" y1="23.271" y2="24.693" gradientUnits="userSpaceOnUse"><stop class="s5ud30bqo"/><stop offset=".531" class="rwl3x2rgk"/></linearGradient><linearGradient id="ilrndMd" x1="21.612" x2="8.017" y1="19.604" y2="19.604" gradientUnits="userSpaceOnUse"><stop class="bvm_ssbmv"/><stop offset="1" class="qox001bns"/></linearGradient><linearGradient id="itKMH7c" x1="8.296" x2="8.296" y1="8.928" y2="12.498" gradientUnits="userSpaceOnUse"><stop class="okcn0pbqd"/><stop offset="1" class="zd-keimcv"/></linearGradient><linearGradient id="iTCRhDv" x1="7.125" x2="7.125" y1="13.912" y2="13.185" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></linearGradient><linearGradient id="iaPKrDb" x1="25.191" x2="25.191" y1="8.928" y2="14.062" gradientUnits="userSpaceOnUse"><stop class="wgw2105cx"/><stop offset=".743" class="tkxxt2z6p"/><stop offset="1" class="umazj-pya"/></linearGradient><linearGradient id="i7UuRDd" x1="23.937" x2="8.094" y1="6.435" y2="15.717" gradientUnits="userSpaceOnUse"><stop class="yt0sjmb1z"/><stop offset="1" class="egb-_obih"/></linearGradient><linearGradient id="iO1Z0sd" x1="23.726" x2="8.301" y1="6.557" y2="15.592" gradientUnits="userSpaceOnUse"><stop class="g4r6pf4wm"/><stop offset="1" class="xpw6t3bxs"/></linearGradient><linearGradient id="ihRbpqd" x1="9.875" x2="23.344" y1="12.154" y2="12.154" gradientUnits="userSpaceOnUse"><stop class="k8zoqmmdl"/><stop offset=".276" class="s6m-cnbld"/></linearGradient><linearGradient id="i2tgNWc" x1="15.401" x2="16.729" y1="12.207" y2="12.207" gradientUnits="userSpaceOnUse"><stop class="onnr4leag"/><stop offset="1" class="gk1fajbmh"/></linearGradient><linearGradient id="iUuAsmd" x1="16.315" x2="16.315" y1="12.881" y2="12.209" gradientUnits="userSpaceOnUse"><stop offset=".233" class="r_adasbkz"/><stop offset="1" class="thijlefpx"/><stop offset="1" class="gmmw9w25y"/></linearGradient><linearGradient id="irxl2gc" x1="16" x2="16" y1="10.145" y2="11.162" gradientUnits="userSpaceOnUse"><stop offset=".217" class="gn3q_tbxa"/><stop offset="1" class="h3v_6hbxq"/></linearGradient><linearGradient id="iKyUxQV" x1="15.271" x2="15.723" y1="14.396" y2="13.524" gradientUnits="userSpaceOnUse"><stop class="x3cwsm3gp"/><stop offset="1" class="odp4t3bgb"/></linearGradient><linearGradient id="igHVFsc" x1="18.96" x2="18.646" y1="10.08" y2="10.273" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBENUEb" x1="14.561" x2="14.248" y1="10.08" y2="10.273" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifncxyb" x1="23.3" x2="21.625" y1="9.404" y2="7.342" gradientUnits="userSpaceOnUse"><stop class="m9pa3mbws"/><stop offset="1" class="u_tn6mbuw"/></linearGradient><linearGradient id="iFvBH3d" x1="17.586" x2="17.961" y1="15.201" y2="15.201" gradientUnits="userSpaceOnUse"><stop class="bbq9_45bu"/><stop offset="1" class="fcjcde55i"/></linearGradient><linearGradient id="ii73fFb" x1="19.234" x2="19.234" y1="15.764" y2="15.568" gradientUnits="userSpaceOnUse"><stop class="u9byv1bdc"/><stop offset="1" class="zk7oijy-r"/></linearGradient><linearGradient id="i8Cj78c" x1="18.216" x2="20.402" y1="15.225" y2="15.225" gradientUnits="userSpaceOnUse"><stop class="ueq20f_ji"/><stop offset="1" class="o69d91bgq"/></linearGradient><filter id="inCIjce" width="9.31" height="4.17" x="11.34" y="25.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.811765 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.635294 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2538" result="effect2_innerShadow_4002_2538"/></filter><filter id="iR5Arhb" width="3.12" height="3.12" x="12.255" y="22.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".25"/></filter><filter id="ibaqR2O" width="3.12" height="3.12" x="16.325" y="22.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".25"/></filter><filter id="iKekugb" width="2.12" height="2.12" x="12.94" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.498039 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="ix7DwPf" width="2.12" height="2.12" x="16.94" y="22.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.180392 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="i30cuKd" width="2.05" height="2.05" x="16.975" y="22.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".05"/></filter><filter id="iZFwsdd" width="2.05" height="2.05" x="12.975" y="22.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".05"/></filter><filter id="i8K3hPb" width="14.359" height="6.364" x="8.82" y="15.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.87451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="iMreSxe" width="18.043" height="18.043" x="6.925" y="1.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".125"/></filter><filter id="ibA70uL" width="16.155" height="16.155" x="7.869" y="2.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".15"/></filter><filter id="irIoOey" width="14.583" height="16.385" x="9.073" y="2.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".75"/></filter><filter id="iByXIQd" width="10.191" height="12.205" x="10.742" y="4.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.192157 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="i1GNEib" width="2.877" height="3.682" x="14.399" y="9.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".25"/></filter><filter id="iwGaacb" width="2.377" height="3.182" x="14.811" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.388235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/><feGaussianBlur result="effect2_foregroundBlur_4002_2538" stdDeviation=".125"/></filter><filter id="iuVMaiD" width="2.377" height="3.182" x="14.811" y="9.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".125"/></filter><filter id="iehUSnd" width="3.702" height="1.526" x="14.149" y="13.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".05"/></filter><filter id="ieA5gpd" width="3.001" height="1.285" x="17.142" y="9.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0745098 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="iXSEzzd" width="3.001" height="1.285" x="12.057" y="9.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0745098 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="ifKsidb" width="2.253" height="1.091" x="12.165" y="7.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0705882 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="iRPMsqd" width="2.253" height="1.091" x="17.582" y="7.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0705882 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter><filter id="ig6zxSc" width=".786" height=".696" x="17.448" y="9.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".05"/></filter><filter id="ir5r1Rl" width=".891" height=".913" x="18.288" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".1"/></filter><filter id="iUh8cnY" width=".986" height="1.04" x="13.845" y="9.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".1"/></filter><filter id="iE3k0Hd" width=".912" height=".704" x="13.09" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".05"/></filter><filter id="iRjlMXc" width="14.6" height="5.86" x="8.7" y="3.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.215686 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.219608 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2538" result="effect2_innerShadow_4002_2538"/></filter><filter id="i4W2h6N" width="3.344" height=".781" x="17.797" y="14.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2538" stdDeviation=".125"/></filter><filter id="iLzB0qd" width="6.686" height="4.857" x="16.38" y="13.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.486275 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2538"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-astronaut-medium" /></template>
<style>
.a_7m96h7b {
  stop-color: var(--svg-color--c9b5de, #C9B5DE);
  stop-opacity: 0;
}

.a2dspgbsf {
  stop-color: var(--svg-color--a29ca9, #A29CA9);
  stop-opacity: 0;
}

.a85ejnd0l {
  stop-color: var(--svg-color--66453a, #66453A);
}

.arric2tqt {
  stop-color: var(--svg-color--e8e4ef, #E8E4EF);
  stop-opacity: 0;
}

.aymqfdc9h {
  d: path("M18 25.05a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.ayzp7ibwz {
  stop-color: var(--svg-color--936d5c, #936D5C);
  stop-opacity: 0;
}

.bbq9_45bu {
  stop-color: var(--svg-color--575558, #575558);
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

.c0156tydt {
  fill: var(--svg-color--d1b8d6, #D1B8D6);
  d: path("M17.885 25.235a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.cbhbs1bsz {
  fill: var(--svg-color--222023, #222023);
  d: path("M17.142 10.054c.265-.467.669-.835 1.537-.835c.38 0 .747.105 1.073.368c.27.218.233.496.025.6l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.cdku7hg9b {
  stop-color: var(--svg-color--d3cade, #D3CADE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmgaqknre {
  stop-color: var(--svg-color--b3b2b5, #B3B2B5);
  stop-opacity: 0;
}

.co8wuy7pr {
  stop-color: var(--svg-color--3e7cd9, #3E7CD9);
}

.cr61bhm2o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.738c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.007-.245.159-.358c.15-.113.324-.136.388-.05");
}

.cu3-vm6cs {
  stop-color: var(--svg-color--482d2f, #482D2F);
}

.cvz68p03p {
  stop-color: var(--svg-color--c2b2d7, #C2B2D7);
  stop-opacity: 0;
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

.ej4qybc4v {
  d: path("M14 25.05a1.06 1.06 0 1 0 0-2.12a1.06 1.06 0 0 0 0 2.12");
}

.eqvqhkbwy {
  stop-color: var(--svg-color--ada9b1, #ADA9B1);
  stop-opacity: 0;
}

.etas1ty4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.278c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.eu4ef4o7o {
  fill: var(--svg-color--d9cde8, #D9CDE8);
  d: path("m9.003 29.99l.017-.01V19.431a10.98 10.98 0 0 0-4.03 8.51v2.05z");
}

.euh5i4bis {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 13.7c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.evzbhtbhj {
  stop-color: var(--svg-color--7d604c, #7D604C);
}

.ey53_wbbj {
  d: path("M18.184 9.55a.892.892 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
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

.fcjcde55i {
  stop-color: var(--svg-color--575558, #575558);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
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

.gk1fajbmh {
  stop-color: var(--svg-color--b58c73, #B58C73);
}

.gmmw9w25y {
  stop-color: var(--svg-color--a06f74, #A06F74);
  stop-opacity: 0;
}

.gn3q_tbxa {
  stop-color: var(--svg-color--b78879, #B78879);
}

.gvh11p6ie {
  stop-color: var(--svg-color--463d38, #463D38);
}

.gwnz45kfq {
  stop-color: var(--svg-color--9f98a6, #9F98A6);
}

.gzu04ob0t {
  d: path("M13.816 9.55a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.h2db6f6fo {
  stop-color: var(--svg-color--ada9b1, #ADA9B1);
}

.h3v_6hbxq {
  stop-color: var(--svg-color--b78879, #B78879);
  stop-opacity: 0;
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

.hlf8kht3i {
  stop-color: var(--svg-color--946567, #946567);
  stop-opacity: 0;
}

.hm8wlgbod {
  stop-color: var(--svg-color--684e3f, #684E3F);
}

.hu1wo0ktt {
  d: path("M10.75 9.547h.013l-.01-.266l-.01-2.147c.074-3.48 10.071-3.36 10.19.047l-.119 4.914c-.123 2.803-2.311 4.684-4.983 4.684s-4.86-1.881-4.983-4.684z");
}

.hwnz8bbgx {
  stop-color: var(--svg-color--dbcfea, #DBCFEA);
}

.i37lqhbve {
  cx: 13.546px;
  cy: 9.931px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.ia0--tbzc {
  fill: var(--svg-color--936363, #936363);
  d: path("m15.607 10.566l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.ijavpvb5h {
  stop-color: var(--svg-color--493b54, #493B54);
}

.jg30e8bxd {
  stop-color: var(--svg-color--cdcad1, #CDCAD1);
}

.jtu9owgtk {
  stop-color: var(--svg-color--69434a, #69434A);
}

.jzs5yxmnp {
  d: path("M15.947 2.239a8.767 8.767 0 0 0-8.772 8.771a8.767 8.767 0 0 0 8.772 8.772a8.767 8.767 0 0 0 8.772-8.772c0-4.848-3.934-8.771-8.772-8.771");
}

.k0nkw8byw {
  d: path("M18.02 15.66h2.97c.28 0 .5-.22.5-.5s-.22-.5-.5-.5h-2.97c-.28 0-.5.22-.5.5s.23.5.5.5");
}

.k14mqzbhm {
  d: path("M15.947 2c-4.98 0-9.01 4.03-9.01 9.01s4.03 9.01 9.01 9.01s9.01-4.03 9.01-9.01S20.917 2 15.947 2");
}

.k3jnt_bvt {
  stop-color: var(--svg-color--bf9886, #BF9886);
}

.k8p9e6b4e {
  d: path("m9.003 29.99l.017-.01V19.431a10.98 10.98 0 0 0-4.03 8.51v2.05z");
}

.k8zoqmmdl {
  stop-color: var(--svg-color--4e4257, #4E4257);
}

.kfjcj3jmf {
  stop-color: var(--svg-color--362b3d, #362B3D);
}

.khh_otzli {
  stop-color: var(--svg-color--bf9886, #BF9886);
  stop-opacity: 0;
}

.kil27mbcd {
  d: path("M23.18 18.397c0 1.462-2.782 3.515-7.18 3.515c-4.469-.047-7.18-2.053-7.18-3.515s3.215-2.649 7.18-2.649s7.18 1.186 7.18 2.649");
}

.l1h7j0zuv {
  stop-color: var(--svg-color--704d42, #704D42);
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

.li31f0e7y {
  stop-color: var(--svg-color--946567, #946567);
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

.mj0fjsb8e {
  stop-color: var(--svg-color--9f98a6, #9F98A6);
  stop-opacity: 0;
}

.mlm971bus {
  d: path("M16 6.8a12 12 0 0 1 7.3 2.46c-.79-3.3-3.76-5.76-7.3-5.76S9.49 5.96 8.7 9.26A12 12 0 0 1 16 6.8");
}

.mvq4qdpsh {
  stop-color: var(--svg-color--69483c, #69483C);
}

.mx1wpgsnc {
  fill: var(--svg-color--3d2132, #3D2132);
  fill-rule: evenodd;
  d: path("m19.705 8.262l-.138.23za.268.268 0 0 1-.276.46l-.005-.002a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.091.988 0 1.328.109a3.3 3.3 0 0 1 .559.238l.009.006l.003.001z");
}

.nqsdswamn {
  stop-color: var(--svg-color--baa7d0, #BAA7D0);
}

.o-5rynguc {
  stop-color: var(--svg-color--37261e, #37261E);
}

.o3idhyb3x {
  fill: var(--svg-color--1f1428, #1F1428);
  d: path("M10.843 14.054c.292 2.118 2.175 3.694 4.404 3.694h2.138c2.23 0 4.112-1.576 4.404-3.694c.133-2.043.268-4.077.367-6.12c-.012-.83-.697-1.517-1.563-1.552h-1.587c-1.082 0-2.061-.611-2.506-1.565a.75.75 0 0 0-.697-.454H14.36c-2.092 0-3.787 1.64-3.787 3.665c0 2.018.132 4.003.27 6.026");
}

.o69d91bgq {
  stop-color: var(--svg-color--5c595d, #5C595D);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odp4t3bgb {
  stop-color: var(--svg-color--a8817c, #A8817C);
  stop-opacity: 0;
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

.onnr4leag {
  stop-color: var(--svg-color--9b7563, #9B7563);
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

.poqmi3b7l {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.278c-.653 0-1.205.45-1.355 1.058a.274.274 0 0 0 .268.341h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.ptm-cybry {
  stop-color: var(--svg-color--69434a, #69434A);
  stop-opacity: 0;
}

.q2kk9ivkm {
  d: path("m15.737 10.428l-.65 1.7a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.527-.377-.646 0");
}

.qox001bns {
  stop-color: var(--svg-color--d8d0e0, #D8D0E0);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzlgi0c-c {
  stop-color: var(--svg-color--f34b6c, #F34B6C);
  stop-opacity: 0;
}

.r_adasbkz {
  stop-color: var(--svg-color--a06f74, #A06F74);
}

.r7b1qibep {
  d: path("M18.118 9.738c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.007-.245.159-.358c.15-.113.324-.136.388-.05");
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

.run8vgloz {
  d: path("M14.63 10.336c0-.288-.234-.48-.297-.538l-.288.279l.177.36z");
}

.rwl3x2rgk {
  stop-color: var(--svg-color--4d90df, #4D90DF);
  stop-opacity: 0;
}

.s-k35n56i {
  fill: var(--svg-color--88004e, #88004E);
  d: path("M16 13.7c-.52 0-1.01-.125-1.422-.344c-.14-.073-.291.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.s1j2c6bmi {
  stop-color: var(--svg-color--5c393e, #5C393E);
  stop-opacity: 0;
}

.s5nmtcc-t {
  stop-color: var(--svg-color--dcdade, #DCDADE);
}

.s5ud30bqo {
  stop-color: var(--svg-color--4d90df, #4D90DF);
}

.s6m-cnbld {
  stop-color: var(--svg-color--332640, #332640);
}

.s6tilzbvz {
  d: path("M18.979 10.324a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.sa_ie2xef {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14 24.865a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.sc0spz58z {
  fill: var(--svg-color--3d2132, #3D2132);
  d: path("m12.576 8.72l-.005.002a.268.268 0 0 1-.276-.46h.002l.003-.002l.01-.006l.032-.018q.04-.023.116-.059c.098-.046.239-.107.41-.161c.34-.109.815-.2 1.328-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.skyfyac-t {
  stop-color: var(--svg-color--beb1cc, #BEB1CC);
}

.slkz9fi8m {
  stop-color: var(--svg-color--7d604c, #7D604C);
  stop-opacity: 0;
}

.sner6009v {
  stop-color: var(--svg-color--b68778, #B68778);
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

.t-wzl5urp {
  stop-color: var(--svg-color--8c6b57, #8C6B57);
  stop-opacity: 0;
}

.tb_z1g16m {
  stop-color: var(--svg-color--f7efff, #F7EFFF);
  stop-opacity: 0;
}

.teoxnoh1q {
  stop-color: var(--svg-color--dcdade, #DCDADE);
  stop-opacity: 0;
}

.thijlefpx {
  stop-color: var(--svg-color--80515c, #80515C);
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

.v6xww-c3b {
  stop-color: var(--svg-color--916465, #916465);
}

.ve84mtm6i {
  stop-color: var(--svg-color--6f494b, #6F494B);
  stop-opacity: 0;
}

.veojd009w {
  stop-color: var(--svg-color--d8c5ec, #D8C5EC);
}

.vlvwenz1w {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M18 24.865a.875.875 0 1 0 0-1.75a.875.875 0 0 0 0 1.75Z");
}

.vzafmqbsv {
  stop-color: var(--svg-color--362b3d, #362B3D);
  stop-opacity: 0;
}

.w-jvyybfs {
  stop-color: var(--svg-color--655d6d, #655D6D);
}

.w44-0gbtd {
  stop-color: var(--svg-color--392622, #392622);
}

.wge1qeybz {
  stop-color: var(--svg-color--6a4348, #6A4348);
  stop-opacity: 0;
}

.wgw2105cx {
  stop-color: var(--svg-color--c0bfc0, #C0BFC0);
}

.wi08z5bgf {
  stop-color: var(--svg-color--3776c0, #3776C0);
}

.wiwspbbdz {
  fill: var(--svg-color--222023, #222023);
  d: path("M14.858 10.054c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.496-.025.6l.556.317c.652-.21 1.373-.239 2.079-.45");
}

.wjgrr3bwb {
  stop-color: var(--svg-color--c9b4e0, #C9B4E0);
  stop-opacity: 0;
}

.wx8zj3ibb {
  d: path("M7.36 28.66v-1.62c0-.19-.15-.34-.34-.34H5.06c-.03.26-.05.53-.06.8l.01 1.5h2.02c.18 0 .33-.15.33-.34");
}

.wzv9_kb2h {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.442a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
}

.x3cwsm3gp {
  stop-color: var(--svg-color--a8817c, #A8817C);
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

.y1qnskbjy {
  stop-color: var(--svg-color--c1b1d5, #C1B1D5);
  stop-opacity: 0;
}

.y2y8kppey {
  stop-color: var(--svg-color--c8bebf, #C8BEBF);
}

.ydir0-dqg {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.442c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.yhibo8bbq {
  cx: 13.546px;
  cy: 9.931px;
  rx: 0.389px;
  ry: 0.197px;
}

.ym__citvk {
  stop-color: var(--svg-color--936d5c, #936D5C);
}

.yt0sjmb1z {
  stop-color: var(--svg-color--d4d0d7, #D4D0D7);
}

.yx5v_dk3v {
  stop-color: var(--svg-color--877f8d, #877F8D);
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

</style>
