<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixUC95o)" class="j34mlk8gs"/><path fill="url(#iXcqGde)" class="j34mlk8gs"/><path fill="url(#iaiNDDA)" class="pcqhnrb7y"/><circle fill="url(#ix5eLTb)" transform="rotate(-10.457 10.304 12.024)" class="j8v4mabre"/><g filter="url(#iq7Vh6d)"><circle fill="url(#i64VPpJ)" transform="rotate(-10.457 10.304 12.024)" class="l8az8-fre"/></g><g filter="url(#iOlGvIx)"><circle fill="url(#iioW0pd)" transform="rotate(-10.457 19.668 10.296)" class="f_ou_9n9c"/><circle fill="url(#ijiNcfb)" transform="rotate(-10.457 19.668 10.296)" class="f_ou_9n9c"/></g><g filter="url(#iM0qOcb)"><circle transform="rotate(-10.457 19.668 10.296)" class="mjq7-udjh"/><circle fill="url(#ivUWjRb)" transform="rotate(-10.457 19.668 10.296)" class="w-8182bxe"/><circle fill="url(#iSmK2gd)" transform="rotate(-10.457 19.668 10.296)" class="w-8182bxe"/></g><path fill="url(#is0BX9c)" class="s29opkigl"/><path fill="url(#iUGmWHd)" class="s29opkigl"/><path fill="url(#iyYBevC)" class="s29opkigl"/><path fill="url(#iOQHzGc)" class="s29opkigl"/><g filter="url(#i2TerBd)"><path class="b667_nbbo"/><path fill="url(#iKm8Swb)" class="xqbuoqd2r"/><path fill="url(#i0VEgSr)" class="xqbuoqd2r"/><path fill="url(#iePYRPc)" class="xqbuoqd2r"/><path fill="url(#ihtolBe)" class="xqbuoqd2r"/><path fill="url(#iDKdGGe)" class="xqbuoqd2r"/><path fill="url(#isJhHFd)" class="xqbuoqd2r"/></g><path fill="url(#i0C3ncj)" class="xqbuoqd2r"/><path fill="url(#id4HzCb)" class="xqbuoqd2r"/><path fill="url(#ibcR7zc)" class="xqbuoqd2r"/><g filter="url(#isMHmDe)"><path class="dynck1hun"/></g><g filter="url(#ioQ7e3d)"><path class="fm78zsb5n"/><path fill="url(#iUnPMue)" class="iv572vpjm"/><path fill="url(#iy51L7d)" class="iv572vpjm"/><path fill="url(#ixwpvWd)" class="iv572vpjm"/></g><g filter="url(#iKBbjgd)"><path fill="url(#i3fmd1b)" class="g_ne4bbxg"/></g><g filter="url(#ilkZcpe)"><path stroke="url(#iLoT8De)" class="c881hezmg"/></g><path class="tv4pbrbcu"/><g filter="url(#iBbMP1z)"><circle fill="url(#iaxCXad)" class="ijdl0jvfb"/></g><g filter="url(#iN5Wu3c)"><circle fill="url(#iVJdzAe)" class="e1w8bibnt"/></g><path fill="url(#ig7gDsc)" class="mkhmhgo9c"/><path fill="url(#irJ3PCb)" class="x60sgkqlc"/><g filter="url(#iR2dAne)"><path stroke="url(#ia4L4Eb)" class="h54ra-bxl"/><path stroke="url(#izEueOm)" class="h54ra-bxl"/></g><g filter="url(#iFzovlb)"><path stroke="url(#iMeIoVd)" class="yfddh72di"/><path stroke="url(#idKEule)" class="yfddh72di"/></g><g filter="url(#iEpcD5b)"><path fill="url(#if2ILld)" clip-rule="evenodd" class="zx-p2ub7r"/></g><g filter="url(#iJo0PAd)"><path class="f408ctbuj"/></g><g filter="url(#ikysmHd)"><path fill="url(#iqt7QEd)" clip-rule="evenodd" class="ni-nv8b6o"/></g><g filter="url(#iKl4ASc)"><path class="e5uuohsoy"/></g><path class="axeuf1x_d"/><path fill="url(#irXRwub)" class="p0jjqbsfi"/><path fill="url(#ifmp4nd)" class="p0jjqbsfi"/><path fill="url(#i9XuW9b)" class="p0jjqbsfi"/><path fill="url(#iJwouzc)" class="p0jjqbsfi"/><path fill="url(#iRbZs4c)" class="p0jjqbsfi"/><path fill="url(#iV3ubfe)" class="p0jjqbsfi"/><path fill="url(#iQjsQRd)" class="p0jjqbsfi"/><g filter="url(#iKc0hHb)"><path fill="url(#ik7dB2d)" class="p8b40fwze"/><path fill="url(#iwMUHiz)" class="p8b40fwze"/><path fill="url(#i0wYJHd)" class="p8b40fwze"/></g><path fill="url(#iVIrNHb)" class="yar0qubky"/><path fill="url(#iJ3yYyb)" class="yar0qubky"/><g filter="url(#if9wWrw)"><path fill="url(#iFXGzBe)" class="zijl324wt"/><path fill="url(#ihggB4d)" class="zijl324wt"/></g><g filter="url(#i9dcbqc)"><path class="c8jwnkben"/><path fill="url(#ixFuVjQ)" class="z9stdmf7f"/><path fill="url(#ir7oMrc)" class="z9stdmf7f"/><path fill="url(#iuwGcXd)" class="z9stdmf7f"/><path fill="url(#iKI4lac)" class="z9stdmf7f"/></g><path fill="url(#iqYMHmw)" class="w7z4-wbdv"/><path fill="url(#iILFyMZ)" class="w7z4-wbdv"/><path fill="url(#iMfmAje)" class="grt4s0bwb"/><path fill="url(#iZPgUcb)" class="grt4s0bwb"/><path fill="url(#izQPz1c)" class="d0fu_3b7o"/><path fill="url(#iPEgmwb)" class="d0fu_3b7o"/><path fill="url(#idkzRQc)" class="d0fu_3b7o"/><path fill="url(#iG2X4TR)" class="tyejtgulh"/><path fill="url(#iwspnUd)" class="vxm5ioctn"/><path fill="url(#iYSbXmb)" class="scvf_5_fn"/><path fill="url(#i8X8Lcc)" class="scvf_5_fn"/><path fill="url(#isaSREd)" class="scvf_5_fn"/><g filter="url(#iXl6F4d)"><path stroke="url(#iBaZ5ce)" class="hl_hl_bbo"/></g><path fill="url(#iLlFn5O)" class="c22sbnbvc"/><path fill="url(#iDECNnd)" class="c22sbnbvc"/><path fill="url(#iSRahRC)" class="ag13w9yeo"/><g filter="url(#iiApXbd)"><path fill="url(#i4B2LNb)" class="j7ls52uzk"/><path fill="url(#iDhpUoe)" class="j7ls52uzk"/><path fill="url(#iEw028b)" class="j7ls52uzk"/></g><path fill="url(#izl4bMp)" class="ek77-kbpg"/><path fill="url(#iwbiw2i)" class="ek77-kbpg"/><path fill="url(#ieMfoDI)" class="ek77-kbpg"/><path class="g3rwfjsra"/><path fill="url(#inOgqgc)" class="ti0fdkp-w"/><path fill="url(#ioEPCMb)" class="ti0fdkp-w"/><path fill="url(#iSrBPvb)" class="ti0fdkp-w"/><path class="p_1tpbzbs"/><path fill="url(#iiHp0jc)" class="im0tax5vs"/><path fill="url(#iRNdyyd)" class="im0tax5vs"/><path fill="url(#iUnbsYd)" class="im0tax5vs"/><path fill="url(#iXC83te)" class="im0tax5vs"/><path fill="url(#iDuAKte)" class="n4gi5qtmm"/><path fill="url(#izDaxAc)" class="n4gi5qtmm"/><path fill="url(#iXfO1Qb)" class="n4gi5qtmm"/><path fill="url(#i6OQXgX)" class="n4gi5qtmm"/><path fill="url(#iYiqfue)" class="sgl310_ar"/><path fill="url(#idwbvpe)" class="sgl310_ar"/><path fill="url(#ijdGW1j)" class="sgl310_ar"/><path fill="url(#ikVtlzd)" class="in0ed8b2s"/><path fill="url(#iNLWnIb)" class="in0ed8b2s"/><path fill="url(#iR8FRBd)" class="in0ed8b2s"/><path fill="url(#ioTN55R)" class="in0ed8b2s"/><g filter="url(#iDG3GJX)"><path stroke="url(#i82Iekd)" class="c4bf-pnpq"/></g><defs><radialGradient id="iXcqGde" cx="0" cy="0" r="1" gradientTransform="rotate(63.107 -6.086 21.728)scale(2.97834 5.11643)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="hb881329x"/><stop offset="1" class="ma7f6291s"/></radialGradient><radialGradient id="iaiNDDA" cx="0" cy="0" r="1" gradientTransform="rotate(41.812 -15.023 29.265)scale(1.64057 2.45952)" gradientUnits="userSpaceOnUse"><stop class="e4rue289b"/><stop offset=".881" class="whn6ckbja"/></radialGradient><radialGradient id="ix5eLTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.633 12.024)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ijiNcfb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.04 10.03)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="ivUWjRb" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.627 11.118)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iSmK2gd" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.668 10.296)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iyYBevC" cx="0" cy="0" r="1" gradientTransform="rotate(92.697 3.263 12.708)scale(8.63456 22.8991)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="w8e7rtl5w"/><stop offset=".918" class="vqi20dbhj"/></radialGradient><radialGradient id="iOQHzGc" cx="0" cy="0" r="1" gradientTransform="rotate(79.38 2.91 12.068)scale(11.1917 38.1436)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="drp_zccjc"/><stop offset=".969" class="hzg1ozbyv"/></radialGradient><radialGradient id="iKm8Swb" cx="0" cy="0" r="1" gradientTransform="rotate(117.35 7.723 6.687)scale(5.61148 9.54283)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iePYRPc" cx="0" cy="0" r="1" gradientTransform="rotate(-105.747 8.276 .288)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="ihtolBe" cx="0" cy="0" r="1" gradientTransform="rotate(-76.857 14.884 -7.52)scale(2.148 1.75186)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iDKdGGe" cx="0" cy="0" r="1" gradientTransform="matrix(1.20101 1.0322 -.91135 1.0604 12.652 2.836)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="isJhHFd" cx="0" cy="0" r="1" gradientTransform="matrix(.87677 -3.25165 1.12349 .30293 18.334 6.248)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i0C3ncj" cx="0" cy="0" r="1" gradientTransform="matrix(.44145 .95155 -1.56439 .72577 14.099 2.569)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="id4HzCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38007 1.37276 -2.8567 2.87191 9.33 4.732)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="ibcR7zc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50458 4.5055 -5.63766 -8.13909 15.32 6.657)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iLoT8De" cx="0" cy="0" r="1" gradientTransform="rotate(-98.211 14.361 .798)scale(.62835 1.88503)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iaxCXad" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.283 -4.57)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="fmfutibqt"/><stop offset=".876" class="h5yjhacpr"/></radialGradient><radialGradient id="iVJdzAe" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.979 -8.706)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="iq8swxtlk"/><stop offset=".535" class="yebujlt_w"/></radialGradient><radialGradient id="ig7gDsc" cx="0" cy="0" r="1" gradientTransform="matrix(2.43078 -.21576 .21899 2.46713 11.437 11.444)" gradientUnits="userSpaceOnUse"><stop offset=".528" class="ygbxxwbma"/><stop offset="1" class="imr_v6bhk"/></radialGradient><radialGradient id="irJ3PCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 16.067 10.634)" gradientUnits="userSpaceOnUse"><stop class="eekbq1fbt"/><stop offset="1" class="a_eywrbvf"/></radialGradient><radialGradient id="izEueOm" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.609 11.08)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="ttw98lbjw"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="emm-a3pcx"/></radialGradient><radialGradient id="idKEule" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.24 10.271)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="prh97g4sh"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="ez8_35bdx"/></radialGradient><radialGradient id="if2ILld" cx="0" cy="0" r="1" gradientTransform="matrix(.04623 -.83479 1.83138 .10143 16.99 8.552)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iqt7QEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.34118 -.76328 1.67452 -.74849 12.165 9.442)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="i9XuW9b" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 .78125 -.62684 2.50735 8.236 21.39)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="wla505bqs"/><stop offset="1" class="rvju2rlnj"/></radialGradient><radialGradient id="iJwouzc" cx="0" cy="0" r="1" gradientTransform="rotate(129.369 -1.276 11.586)scale(2.35689 2.29948)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="eb47hsvqu"/><stop offset="1" class="jqpapdb1m"/></radialGradient><radialGradient id="iRbZs4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 2.01874 -6.68469 8.598 30.45)" gradientUnits="userSpaceOnUse"><stop class="hk7wqt7lq"/><stop offset="1" class="g3kr4nmzl"/></radialGradient><radialGradient id="iQjsQRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.82811 2.45314 -3.10932 2.3171 8.845 21.39)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t1ofhibdm"/><stop offset="1" class="imlvuhvwp"/></radialGradient><radialGradient id="ik7dB2d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 25.23)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iwMUHiz" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.96 10.37)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="i0wYJHd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 26.168)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iVIrNHb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.328 21.512)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iFXGzBe" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.029 12.947)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="ihggB4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.95)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="ixFuVjQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.60938 1.92187 -.5328 .7234 17.155 26.59)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="dubz53-6i"/><stop offset="1" class="fc5g8ruvh"/></radialGradient><radialGradient id="ir7oMrc" cx="0" cy="0" r="1" gradientTransform="matrix(3.90625 0 0 .92188 13.39 28.699)" gradientUnits="userSpaceOnUse"><stop class="dubz53-6i"/><stop offset="1" class="fc5g8ruvh"/></radialGradient><radialGradient id="iuwGcXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.265 29.386)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="b7isyt1qh"/><stop offset="1" class="mmnqgv5yf"/></radialGradient><radialGradient id="iKI4lac" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.57 40.656)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="vw31h25pz"/><stop offset="1" class="qdgjyci2c"/></radialGradient><radialGradient id="iqYMHmw" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.70313 -.62842 0 19.627 28.64)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="hdo03nb1p"/><stop offset="1" class="b26wppbkf"/></radialGradient><radialGradient id="iZPgUcb" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.81 14.98)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="s231-6bjz"/><stop offset="1" class="s6qjzwjgb"/></radialGradient><radialGradient id="izQPz1c" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.765 20.324)" gradientUnits="userSpaceOnUse"><stop class="ol95frboa"/><stop offset="1" class="i5qbulbys"/></radialGradient><radialGradient id="iPEgmwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.296)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="py7fiqzvo"/><stop offset="1" class="rkoscyb2g"/></radialGradient><radialGradient id="idkzRQc" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.933)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yassptbsb"/><stop offset="1" class="g6isq_a6x"/></radialGradient><radialGradient id="isaSREd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.924)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iBaZ5ce" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.466)" gradientUnits="userSpaceOnUse"><stop class="rihdlqb3v"/><stop offset="1" class="x7yh0i-6p"/></radialGradient><radialGradient id="iDECNnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.265)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iDhpUoe" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.64 34.48)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="iwbiw2i" cx="0" cy="0" r="1" gradientTransform="rotate(53.038 -14.73 17.029)scale(3.87188 5.62527)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="k2dydacno"/><stop offset="1" class="x5utb7s2j"/></radialGradient><radialGradient id="ieMfoDI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82813 3.21874 -1.86644 -1.06007 10.124 18.012)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="b8excebxy"/><stop offset="1" class="hnp1-q05e"/></radialGradient><radialGradient id="ioEPCMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08606 .48023 -.48372 -1.09394 14.414 16.73)" gradientUnits="userSpaceOnUse"><stop class="wzg23bc3x"/><stop offset="1" class="tp27ezb_z"/></radialGradient><radialGradient id="iSrBPvb" cx="0" cy="0" r="1" gradientTransform="rotate(-94.844 15.222 2.94)scale(.92518 1.63477)" gradientUnits="userSpaceOnUse"><stop class="ag6qdsamj"/><stop offset="1" class="mbdelibus"/></radialGradient><radialGradient id="iRNdyyd" cx="0" cy="0" r="1" gradientTransform="matrix(.1875 -.92074 2.28193 .4647 12.109 19.354)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="rvlxae6dq"/><stop offset="1" class="wxdz3ub6w"/></radialGradient><radialGradient id="iUnbsYd" cx="0" cy="0" r="1" gradientTransform="rotate(76.139 -4.589 16.533)scale(2.47842 4.24901)" gradientUnits="userSpaceOnUse"><stop offset=".749" class="s4yd9bb_d"/><stop offset="1" class="zjrohm9wd"/></radialGradient><radialGradient id="iXC83te" cx="0" cy="0" r="1" gradientTransform="rotate(150.154 4.46 10.8)scale(1.09887 .84775)" gradientUnits="userSpaceOnUse"><stop offset=".137" class="vo33qub4y"/><stop offset="1" class="r5v36mb_f"/></radialGradient><radialGradient id="iDuAKte" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.374 19.34)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="l4z1-1b1s"/><stop offset="1" class="ri1yzijvp"/></radialGradient><radialGradient id="izDaxAc" cx="0" cy="0" r="1" gradientTransform="rotate(-41.07 30.406 -1.762)scale(1.45077 3.00819)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="xh9neyo3y"/><stop offset="1" class="bcsnf_bcy"/></radialGradient><radialGradient id="iXfO1Qb" cx="0" cy="0" r="1" gradientTransform="rotate(-84.677 17.578 4.247)scale(1.26326 3.54275)" gradientUnits="userSpaceOnUse"><stop class="wlb38ob3l"/><stop offset="1" class="en81-_tdq"/></radialGradient><radialGradient id="i6OQXgX" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.062 19.246)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="f8laadbbd"/><stop offset="1" class="ncukxx3rx"/></radialGradient><radialGradient id="iYiqfue" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33928 1.42858 -2.02518 -1.89858 10.868 20.034)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="guytmftkt"/></radialGradient><radialGradient id="idwbvpe" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 -.98437 4.71032 .82244 10.437 22.45)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="h3osul2wz"/><stop offset="1" class="iwn92ct1p"/></radialGradient><radialGradient id="ijdGW1j" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -.875 1.67102 3.163 8.202 21.558)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="ho57by_ce"/><stop offset="1" class="eq0h2gj5z"/></radialGradient><radialGradient id="iNLWnIb" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .861 16.023)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iR8FRBd" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .743 16.499)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ioTN55R" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.344 10.516)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="i82Iekd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.265)" gradientUnits="userSpaceOnUse"><stop class="zxch6_gap"/><stop offset="1" class="upwmevb9h"/></radialGradient><linearGradient id="ixUC95o" x1="19.224" x2="12.336" y1="19.054" y2="30.731" gradientUnits="userSpaceOnUse"><stop class="hvtvasx8l"/><stop offset="1" class="sdatcx1hi"/></linearGradient><linearGradient id="i64VPpJ" x1="10.304" x2="9.663" y1="12.303" y2="12.303" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iioW0pd" x1="20.756" x2="19.936" y1="9.203" y2="11.742" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="is0BX9c" x1="19.021" x2="11.711" y1="10.812" y2="13.319" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iUGmWHd" x1="10.227" x2="12.448" y1="15.179" y2="14.462" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="i0VEgSr" x1="10.144" x2="12.064" y1="11.782" y2="6.18" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iUnPMue" x1="14.317" x2="15.241" y1="12.351" y2="12.181" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iy51L7d" x1="16.15" x2="15.138" y1="12.341" y2="12.513" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="ixwpvWd" x1="15.553" x2="15.449" y1="13.207" y2="12.643" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i3fmd1b" x1="14.805" x2="14.995" y1="10.476" y2="11.474" gradientUnits="userSpaceOnUse"><stop class="rh9phcbdx"/><stop offset="1" class="x25a99bcy"/></linearGradient><linearGradient id="ia4L4Eb" x1="11.531" x2="13.812" y1="11.486" y2="11.642" gradientUnits="userSpaceOnUse"><stop class="mmoejgb4j"/><stop offset="1" class="ob6i98bby"/></linearGradient><linearGradient id="iMeIoVd" x1="16.161" x2="18.442" y1="10.679" y2="10.834" gradientUnits="userSpaceOnUse"><stop class="bo389tbht"/><stop offset="1" class="aphc613gk"/></linearGradient><linearGradient id="irXRwub" x1="9.109" x2="3.64" y1="26.762" y2="25.293" gradientUnits="userSpaceOnUse"><stop class="ena81bblx"/><stop offset="1" class="hjax-mb0n"/></linearGradient><linearGradient id="ifmp4nd" x1="3.515" x2="5.486" y1="26.387" y2="26.953" gradientUnits="userSpaceOnUse"><stop class="eyx6dtigb"/><stop offset="1" class="uels9hbwx"/></linearGradient><linearGradient id="iV3ubfe" x1="9.229" x2="8.837" y1="28.78" y2="28.655" gradientUnits="userSpaceOnUse"><stop class="hkmz0xbqe"/><stop offset="1" class="s03vqlghs"/></linearGradient><linearGradient id="iJ3yYyb" x1="24.609" x2="24.296" y1="25.793" y2="24.325" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="iILFyMZ" x1="19.523" x2="19.437" y1="27.012" y2="27.52" gradientUnits="userSpaceOnUse"><stop class="byw39cbfh"/><stop offset="1" class="uvoxmwj8v"/></linearGradient><linearGradient id="iMfmAje" x1="26.546" x2="26.984" y1="27.23" y2="30.949" gradientUnits="userSpaceOnUse"><stop class="gf4r80b0w"/><stop offset="1" class="jd4hd8b4a"/></linearGradient><linearGradient id="iG2X4TR" x1="11.144" x2="10.997" y1="22.522" y2="19.879" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iwspnUd" x1="12.351" x2="11.964" y1="20.713" y2="18.731" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iYSbXmb" x1="16.078" x2="15.296" y1="18.511" y2="21.498" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="i8X8Lcc" x1="15.205" x2="15.428" y1="21.718" y2="20.827" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iLlFn5O" x1="14.952" x2="13.827" y1="17.746" y2="22.074" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="iSRahRC" x1="15.265" x2="14.156" y1="18.121" y2="17.762" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="i4B2LNb" x1="14.453" x2="13.223" y1="17.637" y2="22.387" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iEw028b" x1="12.549" x2="12.768" y1="21.452" y2="20.374" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="izl4bMp" x1="8.421" x2="8.964" y1="17.137" y2="21.637" gradientUnits="userSpaceOnUse"><stop class="w5h00ebej"/><stop offset="1" class="ix3yrkb0h"/></linearGradient><linearGradient id="inOgqgc" x1="9.859" x2="11.234" y1="16.918" y2="16.738" gradientUnits="userSpaceOnUse"><stop offset=".136" class="uqhi6sb2j"/><stop offset="1" class="qynlkiyit"/></linearGradient><linearGradient id="iiHp0jc" x1="9.555" x2="11.109" y1="17.84" y2="17.84" gradientUnits="userSpaceOnUse"><stop class="bmz8w2byx"/><stop offset="1" class="w6wkm7xob"/></linearGradient><linearGradient id="ikVtlzd" x1="16.521" x2="15.937" y1="19.012" y2="21.512" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="iq7Vh6d" width="2.992" height="2.992" x="8.808" y="10.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".25"/></filter><filter id="iOlGvIx" width="3.593" height="3.593" x="17.997" y="8.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/></filter><filter id="iM0qOcb" width="2.992" height="2.992" x="18.172" y="8.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".25"/></filter><filter id="i2TerBd" width="12.463" height="9.279" x="7.933" y="2.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3531" result="effect2_innerShadow_4002_3531"/></filter><filter id="isMHmDe" width="3.251" height="4.246" x="13.432" y="10.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".375"/></filter><filter id="ioQ7e3d" width="2.365" height="3.228" x="14.081" y="10.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".125"/></filter><filter id="iKBbjgd" width="2.365" height="3.228" x="14.012" y="10.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".125"/></filter><filter id="ilkZcpe" width="3.571" height="1.755" x="13.724" y="13.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".05"/></filter><filter id="iBbMP1z" width="3.987" height="3.987" x="10.479" y="8.705" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".325"/></filter><filter id="iN5Wu3c" width="3.987" height="3.987" x="15.068" y="7.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".325"/></filter><filter id="iR2dAne" width="2.323" height=".964" x="11.435" y="10.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".05"/></filter><filter id="iFzovlb" width="2.323" height=".964" x="16.066" y="10.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".05"/></filter><filter id="iEpcD5b" width="2.657" height="1.431" x="15.727" y="7.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/></filter><filter id="iJo0PAd" width="2.761" height="1.285" x="15.655" y="7.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".2"/></filter><filter id="ikysmHd" width="2.497" height="1.93" x="10.759" y="8.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/></filter><filter id="iKl4ASc" width="2.602" height="1.784" x="10.686" y="8.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".2"/></filter><filter id="iKc0hHb" width="11.192" height="8.359" x="11.466" y="22.34" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/></filter><filter id="if9wWrw" width="7.407" height="8.444" x="19.048" y="19.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/></filter><filter id="i9dcbqc" width="8.208" height="4.667" x="12.416" y="25.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.592157 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/></filter><filter id="iXl6F4d" width="3.456" height="1.701" x="7.381" y="22.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".1"/></filter><filter id="iiApXbd" width="4.309" height="4.662" x="11.043" y="16.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3531"/></filter><filter id="iDG3GJX" width="3.647" height="2.753" x="6.263" y="19.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3531" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-feeding-baby" /></template>
<style>
.a_eywrbvf {
  stop-color: var(--svg-color--a2413a, #A2413A);
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.ag13w9yeo {
  d: path("m14.826 17.547l-2.636-.735l-1.073 3.895l2.6.734c.408.11.755-.064.85-.393l.78-2.704c.123-.39-.164-.693-.521-.797");
}

.ag6qdsamj {
  stop-color: var(--svg-color--caa166, #CAA166);
}

.aphc613gk {
  stop-color: var(--svg-color--c35e51, #C35E51);
  stop-opacity: 0;
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.axeuf1x_d {
  fill: var(--svg-color--58b2ec, #58B2EC);
  d: path("m29.145 25.79l-4.94-6.05l-3.16 8.57z");
}

.b26wppbkf {
  stop-color: var(--svg-color--286ad9, #286AD9);
}

.b667_nbbo {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m18.544 3.91l.461.132c.807.231 1.385.993 1.39 1.915l-.028 3.1c.006.318-.16.564-.466.628c-.056-.502-.171-1.308-.182-1.437c-.036-.434-.126-.547-.588-.863c-.25-.172-.467-.457-.525-.772l-.155-.84c-.048-.263-.298-.434-.52-.447c-.662-.04-2.03-.06-3.931.291c-1.9.351-3.172.857-3.777 1.131a.52.52 0 0 0-.325.603l.155.84c.058.315.01.65-.215.909l-.13.186c-.181.197-.227.545-.179.808c.043.15.226 1.028.317 1.391a.634.634 0 0 1-.682-.415L8.031 8.184c-.26-.82.007-1.738.678-2.242c.918-.621 1.159-1.353 1.836-2.184c.484-.632 1.3-.946 2.106-.715a2.94 2.94 0 0 0 1.637-.302c.744-.409 1.68-.364 2.42.096l.938.642c.26.223.552.332.898.43");
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

.bo389tbht {
  stop-color: var(--svg-color--c35e51, #C35E51);
}

.byw39cbfh {
  stop-color: var(--svg-color--0e6996, #0E6996);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c22sbnbvc {
  d: path("m11.939 16.483l3.172.884c.43.125.744.559.627.96l-.9 3.086c-.115.396-.532.607-1.024.474l-3.129-.883z");
}

.c4bf-pnpq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.2c-.206.431-.319 1.448.875 2.054s1.992.148 2.242-.156");
}

.c881hezmg {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.546 14.242c-.5.092-.99.061-1.423-.072c-.147-.043-.264.135-.157.242a1.9 1.9 0 0 0 1.712.545a1.9 1.9 0 0 0 1.404-1.12c.062-.143-.11-.264-.232-.17c-.357.278-.8.482-1.304.575Z");
}

.c8jwnkben {
  fill: var(--svg-color--ffb926, #FFB926);
  d: path("M17.18 26.131a.937.937 0 0 0-1.12 1.498l.93.801a.1.1 0 0 1-.062.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.d0fu_3b7o {
  d: path("M10.214 22.136c-.284.88-1.448 1.292-2.6.92c-1.152-.371-1.793-1.177-1.573-2.266c.18-.888.883-1.75 2.738-1.24c1.153.372 1.719 1.706 1.435 2.586");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.drp_zccjc {
  stop-color: var(--svg-color--cb973b, #CB973B);
  stop-opacity: 0;
}

.dubz53-6i {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
}

.dy155dxdg {
  stop-color: var(--svg-color--33c966, #33C966);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dynck1hun {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.684 11.092l-.498 1.822c-.037.362.267.662.607.599l.726-.134c.34-.063.516-.456.353-.777l-.8-1.582c-.173-.351-.346-.32-.388.072");
}

.dypnkmnss {
  stop-color: var(--svg-color--33c966, #33C966);
  stop-opacity: 0;
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e1w8bibnt {
  cx: 17.061px;
  cy: 9.971px;
  r: 1.344px;
}

.e4rue289b {
  stop-color: var(--svg-color--9e762d, #9E762D);
}

.e5uuohsoy {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.211 9.467c.171-.227.696-.657 1.552-.733");
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.eb47hsvqu {
  stop-color: var(--svg-color--2170a2, #2170A2);
}

.eekbq1fbt {
  stop-color: var(--svg-color--c74c24, #C74C24);
}

.ek77-kbpg {
  d: path("M8.13 17.691c1.032-1.085 1.92-1.37 2.32-1.375l.798.868l-.93 3.515c-.18.315-.564.996-.695 1.153c-.164.195-.735.63-1.766.238c-.888-.338-1.15-.899-1.176-1.149c.234-1.167.65-2.357 1.45-3.25");
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.emm-a3pcx {
  stop-color: var(--svg-color--b6614e, #B6614E);
  stop-opacity: 0;
}

.en81-_tdq {
  stop-color: var(--svg-color--ffc52d, #FFC52D);
  stop-opacity: 0;
}

.ena81bblx {
  stop-color: var(--svg-color--2f71f9, #2F71F9);
}

.eq0h2gj5z {
  stop-color: var(--svg-color--fda537, #FDA537);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.eyx6dtigb {
  stop-color: var(--svg-color--4e83c4, #4E83C4);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.ez8_35bdx {
  stop-color: var(--svg-color--c4725e, #C4725E);
  stop-opacity: 0;
}

.f_ou_9n9c {
  cx: 19.668px;
  cy: 10.296px;
  r: 1.671px;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f408ctbuj {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.891 8.235c-.24-.152-.884-.366-1.711-.132");
}

.f8laadbbd {
  stop-color: var(--svg-color--df970a, #DF970A);
}

.fc5g8ruvh {
  stop-color: var(--svg-color--ffd73e, #FFD73E);
  stop-opacity: 0;
}

.fm78zsb5n {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m14.55 10.95l-.215 1.77a.54.54 0 0 0 .64.593l.773-.142a.54.54 0 0 0 .386-.783l-.832-1.576c-.18-.35-.704-.254-.753.138");
}

.fmfutibqt {
  stop-color: var(--svg-color--ffb12b, #FFB12B);
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

.g_ne4bbxg {
  d: path("m14.48 10.823l-.214 1.77a.54.54 0 0 0 .64.594l.773-.143a.54.54 0 0 0 .385-.783l-.831-1.576c-.18-.35-.704-.254-.753.138");
}

.g3kr4nmzl {
  stop-color: var(--svg-color--317ff4, #317FF4);
  stop-opacity: 0;
}

.g3rwfjsra {
  fill: var(--svg-color--ffc126, #FFC126);
  d: path("M10.1 16.91c.355.125.48.33.515.453l.445.39l2.292.363a.92.92 0 0 0 1.061-.872a.913.913 0 0 0-.922-.95c-1.174.014-2.687.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g6isq_a6x {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
  stop-opacity: 0;
}

.gf4r80b0w {
  stop-color: var(--svg-color--27a9f1, #27A9F1);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.grt4s0bwb {
  d: path("M20.615 26.226c1.598-.23 4.567-.808 6.543-1.27c1.522-.262 2.64 1.204 2.64 2.782c0 1.37-1.022 2.236-1.746 2.618a.86.86 0 0 1-.403.093h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.guytmftkt {
  stop-color: var(--svg-color--fba335, #FBA335);
}

.h3osul2wz {
  stop-color: var(--svg-color--cd7a48, #CD7A48);
}

.h54ra-bxl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.585 11.478c.151.14.548.37 1.063.273c.562-.106.888-.458.96-.64");
}

.h5yjhacpr {
  stop-color: var(--svg-color--e99420, #E99420);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hb881329x {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hdo03nb1p {
  stop-color: var(--svg-color--2176c7, #2176C7);
}

.hjax-mb0n {
  stop-color: var(--svg-color--246bda, #246BDA);
}

.hk7wqt7lq {
  stop-color: var(--svg-color--5289f2, #5289F2);
}

.hkmz0xbqe {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
}

.hl_hl_bbo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.481c.579.141 1.92.172 2.657-.828");
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hnp1-q05e {
  stop-color: var(--svg-color--e1a038, #E1A038);
  stop-opacity: 0;
}

.ho57by_ce {
  stop-color: var(--svg-color--e3992c, #E3992C);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hvtvasx8l {
  stop-color: var(--svg-color--2ba6ec, #2BA6EC);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hzg1ozbyv {
  stop-color: var(--svg-color--947353, #947353);
}

.i5qbulbys {
  stop-color: var(--svg-color--1f70cf, #1F70CF);
}

.ijdl0jvfb {
  cx: 12.473px;
  cy: 10.699px;
  r: 1.344px;
}

.im0tax5vs {
  d: path("M9.67 17.832c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.609");
}

.imlvuhvwp {
  stop-color: var(--svg-color--2e71f4, #2E71F4);
  stop-opacity: 0;
}

.imr_v6bhk {
  stop-color: var(--svg-color--ab4620, #AB4620);
}

.in0ed8b2s {
  d: path("m15.454 21.215l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.033l.315.084a.485.485 0 0 0 .253-.936l-.304-.083a.13.13 0 0 1-.097-.108l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.iq8swxtlk {
  stop-color: var(--svg-color--ffde30, #FFDE30);
}

.iv572vpjm {
  d: path("m14.55 10.95l-.215 1.77a.54.54 0 0 0 .64.593l.773-.142a.54.54 0 0 0 .386-.783l-.832-1.576c-.18-.35-.704-.254-.753.138");
}

.iwn92ct1p {
  stop-color: var(--svg-color--fda837, #FDA837);
  stop-opacity: 0;
}

.ix3yrkb0h {
  stop-color: var(--svg-color--e49627, #E49627);
}

.j34mlk8gs {
  d: path("M7.155 30.449c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.j7ls52uzk {
  d: path("m12.167 16.914l2.635.734c.357.104.645.407.521.798l-.779 2.703c-.095.33-.442.504-.851.394l-2.6-.734z");
}

.j8v4mabre {
  cx: 10.304px;
  cy: 12.024px;
  r: 1.671px;
}

.jd4hd8b4a {
  stop-color: var(--svg-color--297eff, #297EFF);
}

.jqpapdb1m {
  stop-color: var(--svg-color--2374a5, #2374A5);
  stop-opacity: 0;
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k2dydacno {
  stop-color: var(--svg-color--e69828, #E69828);
  stop-opacity: 0;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l4z1-1b1s {
  stop-color: var(--svg-color--ffd23e, #FFD23E);
}

.l8az8-fre {
  cx: 10.304px;
  cy: 12.024px;
  r: 0.996px;
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.ma7f6291s {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
  stop-opacity: 0;
}

.mbdelibus {
  stop-color: var(--svg-color--caa166, #CAA166);
  stop-opacity: 0;
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mjq7-udjh {
  cx: 19.668px;
  cy: 10.296px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.mkhmhgo9c {
  d: path("M11.544 11.21c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.mmnqgv5yf {
  stop-color: var(--svg-color--ffba27, #FFBA27);
  stop-opacity: 0;
}

.mmoejgb4j {
  stop-color: var(--svg-color--b16251, #B16251);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.n4gi5qtmm {
  d: path("M8.521 18.93a.28.28 0 0 1 .133-.27c.981-.69 2.005-.305 2.383 0c.304.235 1 .789 1.363 1.082c.446.36.372.96.043 1.316c-.276.298-.751.241-.93.149l-2.097-1.313c-.055-.312-.235-.562-.48-.636c-.247-.075-.403-.133-.415-.329");
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.ncukxx3rx {
  stop-color: var(--svg-color--ffd03a, #FFD03A);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.ni-nv8b6o {
  fill-rule: evenodd;
  d: path("M12.825 9.314c-.72.064-1.124.425-1.215.547a.473.473 0 0 1-.757-.568c.25-.333.897-.832 1.888-.92a.473.473 0 0 1 .084.941");
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.ob6i98bby {
  stop-color: var(--svg-color--b16251, #B16251);
  stop-opacity: 0;
}

.ol95frboa {
  stop-color: var(--svg-color--277aa9, #277AA9);
}

.p_1tpbzbs {
  fill: var(--svg-color--ffc225, #FFC225);
  d: path("M9.67 17.832c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.609");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p0jjqbsfi {
  d: path("m2.201 30.45l2.93-9.157c.351-1.414 2.07-2.104 3.65-1.613c1.58.49 2.49 2.332 2.006 3.691L8.571 30.45z");
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p8b40fwze {
  d: path("M21.835 24.469c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pcqhnrb7y {
  d: path("M15.685 18.98c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.prh97g4sh {
  stop-color: var(--svg-color--c4725e, #C4725E);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.py7fiqzvo {
  stop-color: var(--svg-color--052e6b, #052E6B);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qdgjyci2c {
  stop-color: var(--svg-color--e38f1d, #E38F1D);
  stop-opacity: 0;
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qynlkiyit {
  stop-color: var(--svg-color--f5b12d, #F5B12D);
  stop-opacity: 0;
}

.r5v36mb_f {
  stop-color: var(--svg-color--ffe247, #FFE247);
  stop-opacity: 0;
}

.rh9phcbdx {
  stop-color: var(--svg-color--fcc22d, #FCC22D);
}

.ri1yzijvp {
  stop-color: var(--svg-color--ffbe24, #FFBE24);
}

.rihdlqb3v {
  stop-color: var(--svg-color--429ce6, #429CE6);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rkoscyb2g {
  stop-color: var(--svg-color--124ea0, #124EA0);
  stop-opacity: 0;
}

.rvju2rlnj {
  stop-color: var(--svg-color--1972ba, #1972BA);
  stop-opacity: 0;
}

.rvlxae6dq {
  stop-color: var(--svg-color--f9a325, #F9A325);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s03vqlghs {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
  stop-opacity: 0;
}

.s231-6bjz {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
}

.s29opkigl {
  d: path("M9.846 11.485a30 30 0 0 1-.318-1.405c-.049-.263-.001-.597.181-.794l.13-.186c.224-.259.272-.593.214-.908l-.155-.84a.52.52 0 0 1 .325-.603c.605-.275 1.876-.78 3.777-1.132c1.9-.35 3.27-.332 3.932-.291c.22.013.47.184.52.447l.154.84c.058.315.275.6.525.772c.558.255.562.45.597.867c.01.128.164 1.185.173 1.433l.458 3.945c.163 1.77-.982 3.237-2.615 3.539l-3.16.583c-1.685.311-3.226-.66-3.705-2.373z");
}

.s4yd9bb_d {
  stop-color: var(--svg-color--fdb326, #FDB326);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s6qjzwjgb {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
  stop-opacity: 0;
}

.scvf_5_fn {
  d: path("m15.53 18.315l.554.159a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.103l-.555-.16z");
}

.sdatcx1hi {
  stop-color: var(--svg-color--1577e2, #1577E2);
}

.sgl310_ar {
  d: path("M8.857 21.379c-.315.22-.723.21-.906-.11c-.392-.948.72-1.579 1.5-1.597c1.167-.028 1.75.629 1.937 1.12c.188.493.227 1.477-.672 1.54c-.804.056-.847-.5-.98-.742s-.594-.41-.88-.211");
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.t1ofhibdm {
  stop-color: var(--svg-color--3395d2, #3395D2);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.ti0fdkp-w {
  d: path("M10.1 16.91c.355.125.48.33.515.453l.445.39l2.292.363a.92.92 0 0 0 1.061-.872a.913.913 0 0 0-.922-.95c-1.174.014-2.687.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tp27ezb_z {
  stop-color: var(--svg-color--ffdf42, #FFDF42);
  stop-opacity: 0;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.ttw98lbjw {
  stop-color: var(--svg-color--b6614e, #B6614E);
}

.tv4pbrbcu {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.546 14.242c-.5.092-.99.061-1.423-.072c-.147-.043-.264.135-.157.242a1.9 1.9 0 0 0 1.712.545a1.9 1.9 0 0 0 1.404-1.12c.062-.143-.11-.264-.232-.17c-.357.278-.8.482-1.304.575");
}

.tyejtgulh {
  d: path("m11.845 21.049l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.uels9hbwx {
  stop-color: var(--svg-color--5082c1, #5082C1);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.upwmevb9h {
  stop-color: var(--svg-color--377dcb, #377DCB);
  stop-opacity: 0;
}

.uqhi6sb2j {
  stop-color: var(--svg-color--ecaa34, #ECAA34);
}

.uvoxmwj8v {
  stop-color: var(--svg-color--0e6996, #0E6996);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.vo33qub4y {
  stop-color: var(--svg-color--ffe247, #FFE247);
}

.vqi20dbhj {
  stop-color: var(--svg-color--977550, #977550);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vw31h25pz {
  stop-color: var(--svg-color--e38f1d, #E38F1D);
}

.vxm5ioctn {
  d: path("M10.565 19.019c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w-8182bxe {
  cx: 19.668px;
  cy: 10.296px;
  r: 0.996px;
}

.w5h00ebej {
  stop-color: var(--svg-color--dea33f, #DEA33F);
}

.w6wkm7xob {
  stop-color: var(--svg-color--ffb826, #FFB826);
  stop-opacity: 0;
}

.w7z4-wbdv {
  d: path("M18.998 27.232a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.w8e7rtl5w {
  stop-color: var(--svg-color--d09733, #D09733);
  stop-opacity: 0;
}

.whn6ckbja {
  stop-color: var(--svg-color--d0b13a, #D0B13A);
}

.wla505bqs {
  stop-color: var(--svg-color--1972ba, #1972BA);
}

.wlb38ob3l {
  stop-color: var(--svg-color--cd7c46, #CD7C46);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wxdz3ub6w {
  stop-color: var(--svg-color--f9a325, #F9A325);
  stop-opacity: 0;
}

.wzg23bc3x {
  stop-color: var(--svg-color--ffdf42, #FFDF42);
}

.x25a99bcy {
  stop-color: var(--svg-color--fcc22d, #FCC22D);
  stop-opacity: 0;
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x5utb7s2j {
  stop-color: var(--svg-color--be672a, #BE672A);
}

.x60sgkqlc {
  d: path("M16.173 10.4c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.x7yh0i-6p {
  stop-color: var(--svg-color--429ce6, #429CE6);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xh9neyo3y {
  stop-color: var(--svg-color--eea92f, #EEA92F);
}

.xqbuoqd2r {
  d: path("m18.544 3.91l.461.132c.807.231 1.385.993 1.39 1.915l-.028 3.1c.006.318-.16.564-.466.628c-.056-.502-.171-1.308-.182-1.437c-.036-.434-.126-.547-.588-.863c-.25-.172-.467-.457-.525-.772l-.155-.84c-.048-.263-.298-.434-.52-.447c-.662-.04-2.03-.06-3.931.291c-1.9.351-3.172.857-3.777 1.131a.52.52 0 0 0-.325.603l.155.84c.058.315.01.65-.215.909l-.13.186c-.181.197-.227.545-.179.808c.043.15.226 1.028.317 1.391a.634.634 0 0 1-.682-.415L8.031 8.184c-.26-.82.007-1.738.678-2.242c.918-.621 1.159-1.353 1.836-2.184c.484-.632 1.3-.946 2.106-.715a2.94 2.94 0 0 0 1.637-.302c.744-.409 1.68-.364 2.42.096l.938.642c.26.223.552.332.898.43");
}

.yar0qubky {
  d: path("M23.445 27.609a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.yassptbsb {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
}

.yebujlt_w {
  stop-color: var(--svg-color--ffc81d, #FFC81D);
}

.yfddh72di {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.216 10.67c.15.14.547.37 1.062.273c.563-.106.888-.458.961-.64");
}

.ygbxxwbma {
  stop-color: var(--svg-color--993330, #993330);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z9stdmf7f {
  d: path("M17.18 26.131a.937.937 0 0 0-1.12 1.498l.93.801a.1.1 0 0 1-.062.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.zijl324wt {
  d: path("M21.575 24.389a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zjrohm9wd {
  stop-color: var(--svg-color--d99540, #D99540);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zx-p2ub7r {
  fill-rule: evenodd;
  d: path("M16.329 8.667c.696-.197 1.201-.004 1.33.077a.473.473 0 0 0 .504-.8c-.352-.222-1.134-.457-2.092-.186a.473.473 0 1 0 .258.91");
}

.zxch6_gap {
  stop-color: var(--svg-color--377dcb, #377DCB);
}

</style>
