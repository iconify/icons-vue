<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuYeINe)"><path fill="url(#i1Pd52d)" class="e5n7-cbky"/><path fill="url(#iM6rPqd)" class="e5n7-cbky"/></g><g filter="url(#iqXvaPd)"><path class="ii_vcdblz"/></g><g filter="url(#i1M3e4d)"><path class="x9-b3hbfy"/></g><g filter="url(#iOQmwkd)"><path class="a424ylq9x"/><path fill="url(#i7bctJc)" class="m3dxw5b4u"/><path fill="url(#izNqDsc)" class="m3dxw5b4u"/><path fill="url(#it3vqkc)" class="m3dxw5b4u"/></g><path class="a1i_j40xh"/><path fill="url(#igSiocc)" class="rq76sybla"/><path fill="url(#iQD9PdN)" class="rq76sybla"/><path fill="url(#ifkmApd)" class="rq76sybla"/><path fill="url(#iUzRGHc)" class="rq76sybla"/><path fill="url(#iZLtlOc)" class="ndlc49hkf"/><path fill="url(#iHff3Oe)" class="ndlc49hkf"/><path fill="url(#iFGxoeb)" class="lt_b3wboz"/><path fill="url(#i5m29vW)" class="lt_b3wboz"/><path class="vbc9nqbss"/><path fill="url(#iPRoNnL)" class="pi6c47yng"/><path class="javsik_yi"/><path fill="url(#iOgo57h)" class="u-q3e7b8s"/><path fill="url(#imSNiSc)" class="js7qsnbrb"/><path fill="url(#ifJpCTc)" class="fbjx3y-qb"/><path fill="url(#itn3zqq)" class="fbjx3y-qb"/><g filter="url(#ivm1NEe)"><path class="kc9q3mbff"/><path fill="url(#ifFH9Wc)" class="qv8wc6zla"/></g><path fill="url(#iUEJUid)" class="ue1gv6enh"/><path fill="url(#i294t4w)" class="ue1gv6enh"/><g filter="url(#iHLoBCc)"><path fill="url(#igKMsTc)" class="na59ribzw"/></g><path class="vczswwwcd"/><g filter="url(#iR76rzd)"><path fill="url(#iRrCpFd)" class="qtzewq2gr"/><path fill="url(#irXsggA)" class="qtzewq2gr"/><path fill="url(#iGAXcHe)" class="qtzewq2gr"/><path fill="url(#i16MIqd)" class="qtzewq2gr"/><path fill="url(#iwHUrfZ)" class="qtzewq2gr"/></g><g filter="url(#iwwWXgc)"><path stroke="url(#il7Uzxb)" class="bzs2-ddka"/></g><g filter="url(#iIPdPlb)"><path stroke="url(#iClF6kr)" class="pjsi77bhr"/></g><g filter="url(#iquAAMd)"><path stroke="url(#iNjvqRd)" class="oool1tdti"/></g><g filter="url(#iXPhfcc)"><circle fill="url(#iuBo9ic)" class="i4ysa-bno"/></g><g filter="url(#iiTZ6cc)"><circle class="wc7956bqp"/></g><circle fill="url(#iLH9WGb)" class="wct4qccbg"/><g filter="url(#i3UB1Je)"><circle fill="url(#iro4E6b)" class="hh437879c"/></g><g filter="url(#i2LjjCb)"><path fill="url(#i6fkuKm)" class="dlrwjtb7t"/><path fill="url(#i57Fyjb)" class="dlrwjtb7t"/></g><path fill="url(#ieYpCTc)" class="dlrwjtb7t"/><path fill="url(#iSimDXd)" class="dlrwjtb7t"/><path fill="url(#iiQVAWb)" class="dlrwjtb7t"/><path fill="url(#iVYCWCe)" class="dlrwjtb7t"/><path fill="url(#iIwRp6X)" class="dlrwjtb7t"/><path fill="url(#icCofSH)" class="dlrwjtb7t"/><path fill="url(#iPGrOQx)" class="dlrwjtb7t"/><path fill="url(#iZV0ooe)" class="dlrwjtb7t"/><path fill="url(#iOILiXb)" class="dlrwjtb7t"/><path fill="url(#i8LQiRb)" class="dlrwjtb7t"/><g filter="url(#iNJP4dc)"><path class="uit74mbey"/><path fill="url(#is4oeLb)" class="ybrylxbuq"/><path fill="url(#i5RNXhc)" class="ybrylxbuq"/><path fill="url(#iLS37Ld)" class="ybrylxbuq"/><path fill="url(#iK5yQFd)" class="ybrylxbuq"/><path fill="url(#iDPgS1a)" class="ybrylxbuq"/><path fill="url(#iZ8VHxd)" class="ybrylxbuq"/></g><path class="t2vg81bwy"/><path fill="url(#iTvJAjb)" class="ybrylxbuq"/><path fill="url(#imUXuId)" class="ybrylxbuq"/><g filter="url(#iOMc2Ed)"><path class="q-1fu8b-z"/></g><g filter="url(#iZeJOKe)"><path class="afr-yacht"/><path fill="url(#iMTOk3S)" class="b175b4n1p"/><path fill="url(#imHXA1b)" class="b175b4n1p"/><path fill="url(#ilm2Vkd)" class="b175b4n1p"/><path fill="url(#itVWUfN)" class="b175b4n1p"/><path fill="url(#idDCd2X)" class="b175b4n1p"/></g><g filter="url(#il4BltB)"><path stroke="url(#inh3Akc)" class="ul2vnhvnj"/></g><path fill="url(#ih3qMgc)" class="ctdepmc0e"/><path class="jwqe_jbgo"/><path fill="url(#iC4ORHc)" class="cwr7ndbvn"/><path class="hdusbzsjg"/><g filter="url(#iW11yve)"><path class="jl9xgibbw"/><path fill="url(#iZmGKKW)" class="b0svlhbnq"/></g><g filter="url(#iuDUN8z)"><path fill="url(#ivjr05J)" class="hyj07d54k"/></g><path class="uf734fbqu"/><path fill="url(#imbF5Lg)" class="i9v5wucat"/><path class="tr80mtbrp"/><g filter="url(#io0yHid)"><path fill="url(#iilVjNe)" class="rj390kbfq"/></g><g filter="url(#iW6EnPd)"><ellipse transform="rotate(-27.914 12.393 9.954)" class="kyknafbgp"/><ellipse fill="url(#iuoxayc)" transform="rotate(-27.914 12.393 9.954)" class="jht53ab1w"/></g><g filter="url(#i7rSnUc)"><path clip-rule="evenodd" class="gcm7kgbsj"/></g><g filter="url(#iLPADBc)"><path class="yi5yu6x4i"/></g><g filter="url(#irCxmSb)"><path clip-rule="evenodd" class="p6lllsbjv"/></g><g filter="url(#iF3cTxc)"><path class="uvblrcend"/></g><path fill="url(#icBL91d)" class="iycy_sbnz"/><path fill="url(#ibvcPeT)" class="g9arp8b8o"/><path fill="url(#ic8iSPb)" class="g9arp8b8o"/><path fill="url(#iLeaTZU)" class="sb1phf9zd"/><path fill="url(#iE9kqQd)" class="sb1phf9zd"/><path fill="url(#ijzTWdd)" class="ltwsa8bld"/><path fill="url(#iT74aTv)" class="ltwsa8bld"/><path fill="url(#ivqY3ab)" class="ltwsa8bld"/><g filter="url(#iiPXGPx)"><path fill="url(#iCmdwmN)" class="o12zmvuzn"/></g><g filter="url(#ir74Xje)"><path class="ojb-ttbmo"/></g><g filter="url(#i89EI5b)"><path class="ac3zfwb5z"/></g><defs><radialGradient id="iM6rPqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.5 5.875 0 20.418 30)" gradientUnits="userSpaceOnUse"><stop class="bbqwceq4e"/><stop offset="1" class="s5pm96b_v"/></radialGradient><radialGradient id="i7bctJc" cx="0" cy="0" r="1" gradientTransform="rotate(137.578 3.33 12.372)scale(3.51039 2.85287)" gradientUnits="userSpaceOnUse"><stop class="ypv_kpaja"/><stop offset="1" class="iv7bj_baj"/></radialGradient><radialGradient id="izNqDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 1.72406 -2.87775 -1.46054 13.106 16.844)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="d7sh3eboe"/><stop offset="1" class="tizux9w7p"/></radialGradient><radialGradient id="ifkmApd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94352 -1.86047 0 16.66 16.037)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="rtj8_6bqg"/><stop offset="1" class="m8_l30tsr"/></radialGradient><radialGradient id="iUzRGHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.94683 2.47509 -1.65865 -.6345 15.664 17.448)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="s1rw4px-b"/><stop offset="1" class="p3_97vb4n"/></radialGradient><radialGradient id="iFGxoeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.9375 0 6.668 30)" gradientUnits="userSpaceOnUse"><stop class="mx797o4di"/><stop offset="1" class="m1_q07_me"/></radialGradient><radialGradient id="iPRoNnL" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -3.70312 0 24.043 20.063)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="p7prpqhjw"/><stop offset="1" class="m4mhe8bqv"/></radialGradient><radialGradient id="iOgo57h" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.76563 6.85285 0 14.734 21.438)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="ee8yo8bto"/><stop offset="1" class="dn7nvsb1v"/></radialGradient><radialGradient id="imSNiSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.58518 -1.88176 0 14.79 16.917)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zyz2-nbsw"/><stop offset=".719" class="vbelliord"/><stop offset="1" class="yrmgmz50r"/></radialGradient><radialGradient id="ifJpCTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 26.796 23.749)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="itn3zqq" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 26.205 23.597)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="ifFH9Wc" cx="0" cy="0" r="1" gradientTransform="rotate(-45 32.088 -22.467)scale(.99437 .32275)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="ky_dg6bhp"/><stop offset="1" class="qwfi8obtf"/></radialGradient><radialGradient id="i294t4w" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45773 0 0 -.25781 25.259 22.922)" gradientUnits="userSpaceOnUse"><stop class="wp6rq3sqk"/><stop offset="1" class="hnxygroex"/></radialGradient><radialGradient id="irXsggA" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 24.568 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iGAXcHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 24.568 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="i16MIqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 24.568 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iwHUrfZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 24.568 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iuBo9ic" cx="0" cy="0" r="1" gradientTransform="matrix(1.87734 3.31408 -3.81282 2.15986 10.317 9.32)" gradientUnits="userSpaceOnUse"><stop class="tay54u6mm"/><stop offset="1" class="vrqwlje0q"/></radialGradient><radialGradient id="iLH9WGb" cx="0" cy="0" r="1" gradientTransform="rotate(134.683 7.852 8.74)scale(4.53896 4.6606)" gradientUnits="userSpaceOnUse"><stop class="er0-s6-2m"/><stop offset="1" class="wli8v5-ip"/></radialGradient><radialGradient id="iro4E6b" cx="0" cy="0" r="1" gradientTransform="matrix(1.33227 0 0 .70161 18.597 10.729)" gradientUnits="userSpaceOnUse"><stop class="si5zi3baz"/><stop offset="1" class="cfie9isot"/></radialGradient><radialGradient id="i6fkuKm" cx="0" cy="0" r="1" gradientTransform="matrix(-4.75885 0 0 -8.08312 17.66 11.117)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="i57Fyjb" cx="0" cy="0" r="1" gradientTransform="rotate(122.2 6.904 7.91)scale(3.3087 2.78183)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iSimDXd" cx="0" cy="0" r="1" gradientTransform="matrix(.07141 7.61943 -9.05698 .08489 15.387 10.032)" gradientUnits="userSpaceOnUse"><stop offset=".673" class="ym2yqhbxf"/><stop offset=".941" class="s2fk7zbzg"/></radialGradient><radialGradient id="iiQVAWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.11523 1.43734 0 17.296 9.842)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iVYCWCe" cx="0" cy="0" r="1" gradientTransform="matrix(.00397 -1.06272 1.20445 .0045 12.495 9.887)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iIwRp6X" cx="0" cy="0" r="1" gradientTransform="matrix(-8.59317 .52091 -1.27808 -21.0836 18.293 12.076)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="icCofSH" cx="0" cy="0" r="1" gradientTransform="matrix(-.23734 2.42541 -1.009 -.09874 20.43 8.284)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iPGrOQx" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84645 -1.69234 0 12.58 10.636)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="iZV0ooe" cx="0" cy="0" r="1" gradientTransform="matrix(-.24752 5.65505 -6.12708 -.26818 19.79 7.443)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="u7iwqu4ui"/><stop offset="1" class="ajscfxbli"/></radialGradient><radialGradient id="iOILiXb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.83654 3.2442 -2.75342 -3.25616 11.714 6.848)" gradientUnits="userSpaceOnUse"><stop class="q955-k8fs"/><stop offset="1" class="hui1uab7b"/></radialGradient><radialGradient id="is4oeLb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 8.514 6.057)scale(5.58654 9.5004)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iLS37Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.18385 -1.98553 .97514 -.0903 10.719 7.103)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iK5yQFd" cx="0" cy="0" r="1" gradientTransform="rotate(-66.4 16.4 -10.059)scale(2.13845 1.74407)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iDPgS1a" cx="0" cy="0" r="1" gradientTransform="matrix(.9893 1.22755 -1.08384 .87349 14.067 2.157)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iZ8VHxd" cx="0" cy="0" r="1" gradientTransform="matrix(1.4459 -3.025 1.04518 .49958 19.015 6.524)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="imUXuId" cx="0" cy="0" r="1" gradientTransform="matrix(.2578 -1.89062 1.57611 .21492 20.49 9.762)" gradientUnits="userSpaceOnUse"><stop class="l8cne9blx"/><stop offset="1" class="f-ei52boo"/></radialGradient><radialGradient id="imHXA1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22489 -.76432 0 15.304 12.356)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="itVWUfN" cx="0" cy="0" r="1" gradientTransform="rotate(157.024 6.508 7.483)scale(1.64605 2.5094)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ih3qMgc" cx="0" cy="0" r="1" gradientTransform="matrix(2.17383 -1.06872 4.29973 8.74588 14.35 14.571)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iC4ORHc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .80829 -1.28568 0 17.012 10.049)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iZmGKKW" cx="0" cy="0" r="1" gradientTransform="matrix(-.23105 -.29773 .40992 -.31811 16.784 10.132)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imbF5Lg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .80833 -1.28574 0 12.663 10.049)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iuoxayc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0077 -.49224 .59169 -.00926 12.379 10.267)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic8iSPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -.47665 0 23.309 6.469)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y66dh_b5l"/><stop offset="1" class="nzjwoybta"/></radialGradient><radialGradient id="iLeaTZU" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40034 6.13 0 14.849 7.33)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="ixw-oi7aq"/><stop offset="1" class="mguibccfx"/></radialGradient><radialGradient id="ijzTWdd" cx="0" cy="0" r="1" gradientTransform="rotate(129.472 9.359 6.843)scale(6.19389 12.2026)" gradientUnits="userSpaceOnUse"><stop class="qyg3b1b6n"/><stop offset="1" class="p64oiyb7x"/></radialGradient><radialGradient id="iT74aTv" cx="0" cy="0" r="1" gradientTransform="rotate(146.725 7.907 4.576)scale(9.56883 10.9225)" gradientUnits="userSpaceOnUse"><stop offset=".512" class="yytwt1d8s"/><stop offset="1" class="s1a8ycb7r"/></radialGradient><radialGradient id="iCmdwmN" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -10.576 0 14.791 6.156)" gradientUnits="userSpaceOnUse"><stop class="z2rllvutr"/><stop offset="1" class="t8ye-ilvp"/></radialGradient><filter id="iuYeINe" width="22.99" height="15" x="3.739" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.431373 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="iqXvaPd" width="5.492" height="8.119" x="9.76" y="14.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".5"/></filter><filter id="i1M3e4d" width="5.492" height="8.113" x="13.872" y="15.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".5"/></filter><filter id="iOQmwkd" width="3.592" height="6.219" x="10.712" y="15.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.337255 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="ivm1NEe" width="3.02" height="8.58" x="23.729" y="14.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="iHLoBCc" width="3.675" height="3.685" x="24.636" y="12.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.870588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="iR76rzd" width="4.468" height="5.556" x="22.131" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="iwwWXgc" width="2.097" height=".3" x="22.598" y="25.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".05"/></filter><filter id="iIPdPlb" width="2.097" height=".3" x="22.52" y="27.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".05"/></filter><filter id="iquAAMd" width="2.097" height=".3" x="22.598" y="28.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".05"/></filter><filter id="iXPhfcc" width="3.427" height="3.327" x="8.445" y="9.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.341176 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="iiTZ6cc" width="2.483" height="2.483" x="8.867" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".125"/></filter><filter id="i3UB1Je" width="2.483" height="2.483" x="18.347" y="9.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".125"/></filter><filter id="i2LjjCb" width="11.337" height="12.086" x="9.7" y="5.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2028" result="effect2_innerShadow_4002_2028"/></filter><filter id="iNJP4dc" width="12.557" height="8.265" x="8.561" y="1.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2028" result="effect2_innerShadow_4002_2028"/></filter><filter id="iOMc2Ed" width="3.754" height="4.672" x="12.725" y="9.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".5"/></filter><filter id="iZeJOKe" width="2.27" height="3.072" x="13.705" y="9.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".1"/></filter><filter id="il4BltB" width="3.606" height="1.469" x="13.037" y="13.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".05"/></filter><filter id="iW11yve" width=".785" height=".694" x="16.279" y="9.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".05"/></filter><filter id="iuDUN8z" width=".889" height=".911" x="17.116" y="9.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".1"/></filter><filter id="io0yHid" width=".984" height="1.038" x="12.69" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".1"/></filter><filter id="iW6EnPd" width=".91" height=".703" x="11.938" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".05"/></filter><filter id="i7rSnUc" width="2.693" height="1.592" x="16.099" y="7.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.113725 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="iLPADBc" width="2.499" height="1.193" x="16.195" y="7.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".125"/></filter><filter id="irCxmSb" width="2.693" height="1.592" x="10.988" y="7.379" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.113725 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="iF3cTxc" width="2.402" height="1.2" x="11.084" y="7.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2028" stdDeviation=".125"/></filter><filter id="iiPXGPx" width="15.17" height="4.76" x="7.155" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.588235 0 0 0 0 0.47451 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.329412 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2028" result="effect2_innerShadow_4002_2028"/></filter><filter id="ir74Xje" width="9.99" height="2.47" x="9.739" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.843137 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><filter id="i89EI5b" width="6.31" height="2.47" x="13.419" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.890196 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2028"/></filter><linearGradient id="i1Pd52d" x1="14.735" x2="14.735" y1="16.438" y2="30.563" gradientUnits="userSpaceOnUse"><stop class="troaenb0e"/><stop offset="1" class="jsbk_hbmd"/></linearGradient><linearGradient id="it3vqkc" x1="10.637" x2="11.379" y1="18.219" y2="18.242" gradientUnits="userSpaceOnUse"><stop offset=".344" class="u9ri-jbkw"/><stop offset="1" class="j0xtzac4y"/></linearGradient><linearGradient id="igSiocc" x1="18.805" x2="18.012" y1="18.937" y2="18.937" gradientUnits="userSpaceOnUse"><stop class="ph46gxbvy"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iQD9PdN" x1="16.746" x2="17.254" y1="20.766" y2="19.984" gradientUnits="userSpaceOnUse"><stop class="sq-bwm1qa"/><stop offset="1" class="s21zh4b3w"/></linearGradient><linearGradient id="iZLtlOc" x1="8.242" x2="21.651" y1="9.948" y2="9.948" gradientUnits="userSpaceOnUse"><stop offset=".006" class="z-f4zlb4n"/><stop offset="1" class="z88owpbip"/></linearGradient><linearGradient id="iHff3Oe" x1="17.985" x2="17.985" y1="10.031" y2="9.742" gradientUnits="userSpaceOnUse"><stop class="q9u3nxbxg"/><stop offset="1" class="lvlvw7bgp"/></linearGradient><linearGradient id="i5m29vW" x1="7.769" x2="5.387" y1="27.844" y2="27.844" gradientUnits="userSpaceOnUse"><stop class="r5fk93cur"/><stop offset="1" class="bl3c3b0wv"/></linearGradient><linearGradient id="iUEJUid" x1="25.259" x2="23.652" y1="24.265" y2="24.265" gradientUnits="userSpaceOnUse"><stop class="ec1jnjbjz"/><stop offset="1" class="yd41utmlw"/></linearGradient><linearGradient id="igKMsTc" x1="25.442" x2="26.863" y1="15.852" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="avgmeibok"/><stop offset="1" class="lasn3qwok"/></linearGradient><linearGradient id="iRrCpFd" x1="26.159" x2="22.131" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="il7Uzxb" x1="22.748" x2="24.458" y1="26.08" y2="26.08" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iClF6kr" x1="22.67" x2="24.38" y1="27.385" y2="27.385" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iNjvqRd" x1="22.748" x2="24.458" y1="28.689" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ieYpCTc" x1="20.037" x2="17.479" y1="12.754" y2="12.754" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="i8LQiRb" x1="14.869" x2="14.869" y1="7.272" y2="7.545" gradientUnits="userSpaceOnUse"><stop class="h3zngkbgy"/><stop offset="1" class="p2mvr3bvu"/></linearGradient><linearGradient id="i5RNXhc" x1="9.996" x2="12.888" y1="10.462" y2="5.326" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iTvJAjb" x1="9.075" x2="9.87" y1="9.597" y2="9.453" gradientUnits="userSpaceOnUse"><stop offset=".171" class="rttu7sb8r"/><stop offset="1" class="vmw-awokf"/></linearGradient><linearGradient id="iMTOk3S" x1="15.675" x2="14.84" y1="11.725" y2="11.762" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ilm2Vkd" x1="14.84" x2="14.84" y1="12.774" y2="12.346" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="idDCd2X" x1="14.84" x2="14.84" y1="10.282" y2="11.31" gradientUnits="userSpaceOnUse"><stop class="d0tf12b0a"/><stop offset="1" class="bg9f-0j-b"/></linearGradient><linearGradient id="inh3Akc" x1="13.643" x2="13.96" y1="14.334" y2="13.503" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="ivjr05J" x1="17.786" x2="17.474" y1="10.103" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iilVjNe" x1="13.405" x2="13.092" y1="10.103" y2="10.295" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="icBL91d" x1="6.356" x2="7.059" y1="7.633" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="qo28zhh9b"/><stop offset="1" class="yhrc8s1zu"/></linearGradient><linearGradient id="ibvcPeT" x1="22.462" x2="22.462" y1="6" y2="8.01" gradientUnits="userSpaceOnUse"><stop class="ott3_jqut"/><stop offset="1" class="l8p6brbrs"/></linearGradient><linearGradient id="iE9kqQd" x1="15.051" x2="15.051" y1="7.33" y2="7.174" gradientUnits="userSpaceOnUse"><stop class="j3h4o1d7b"/><stop offset="1" class="lo1ogpbbw"/></linearGradient><linearGradient id="ivqY3ab" x1="6.787" x2="7.841" y1="7.125" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="it1_ig0bc"/><stop offset="1" class="qgmif2bih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-factory-worker-medium" /></template>
<style>
.a1i_j40xh {
  fill: var(--svg-color--3c77cf, #3C77CF);
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.a424ylq9x {
  fill: var(--svg-color--3674c9, #3674C9);
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.ac3zfwb5z {
  fill: var(--svg-color--8cf5ff, #8CF5FF);
  d: path("m16.169 2l-2.45 2.37h5.45c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19z");
}

.afr-yacht {
  fill: var(--svg-color--977062, #977062);
  d: path("m14.459 10.445l-.53 1.693a.537.537 0 0 0 .52.697h.783a.54.54 0 0 0 .518-.697l-.53-1.694c-.113-.375-.642-.375-.761 0");
}

.ajscfxbli {
  stop-color: var(--svg-color--996869, #996869);
  stop-opacity: 0;
}

.avgmeibok {
  stop-color: var(--svg-color--73d7ff, #73D7FF);
}

.b0svlhbnq {
  d: path("M16.948 9.762c.063.085-.07.188-.22.3c-.15.113-.262.192-.325.107c-.064-.084.007-.244.158-.357c.15-.112.323-.135.387-.05");
}

.b175b4n1p {
  d: path("m14.459 10.445l-.53 1.693a.537.537 0 0 0 .52.697h.783a.54.54 0 0 0 .518-.697l-.53-1.694c-.113-.375-.642-.375-.761 0");
}

.bbqwceq4e {
  stop-color: var(--svg-color--3878e5, #3878E5);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bg9f-0j-b {
  stop-color: var(--svg-color--a2756c, #A2756C);
  stop-opacity: 0;
}

.bl3c3b0wv {
  stop-color: var(--svg-color--3e6fc6, #3E6FC6);
  stop-opacity: 0;
}

.bzs2-ddka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 26.002h1.797");
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cfie9isot {
  stop-color: var(--svg-color--522e38, #522E38);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctdepmc0e {
  d: path("M14.84 13.848c-.506 0-.981-.12-1.38-.328c-.137-.069-.284.085-.198.209c.334.505.916.842 1.578.842s1.244-.337 1.577-.842c.086-.13-.06-.278-.197-.209c-.4.209-.87.328-1.38.328");
}

.cwr7ndbvn {
  d: path("M17.013 9.574a.89.89 0 0 1 .857 1.123h-1.718a.893.893 0 0 1 .86-1.124");
}

.d0tf12b0a {
  stop-color: var(--svg-color--a2756c, #A2756C);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d7sh3eboe {
  stop-color: var(--svg-color--26386d, #26386D);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dlrwjtb7t {
  d: path("M9.758 10.118A30 30 0 0 1 9.7 8.685c0-.266.107-.585.32-.744l.161-.16c.267-.212.374-.531.374-.85v-.85c0-.266.16-.479.428-.532c.641-.16 1.977-.425 3.902-.425c1.924 0 3.26.266 3.902.425c.213.053.427.266.427.532v.85c0 .319.16.638.375.85c.5.351.469.544.427.957c-.013.128-.053 1.19-.089 1.435l-.265 3.944c-.16 1.764-1.546 2.993-3.199 2.993h-3.199c-1.706 0-3.04-1.23-3.2-2.993z");
}

.dn7nvsb1v {
  stop-color: var(--svg-color--806879, #806879);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5n7-cbky {
  d: path("M14.739 15.5c-6.07 0-11 4.92-11 11V30h20.99a1 1 0 0 0 1-1v-2.5c0-6.08-4.92-11-10.99-11");
}

.ec1jnjbjz {
  stop-color: var(--svg-color--675479, #675479);
}

.ee8yo8bto {
  stop-color: var(--svg-color--806879, #806879);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.er0-s6-2m {
  stop-color: var(--svg-color--49262b, #49262B);
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.f-ei52boo {
  stop-color: var(--svg-color--1e161b, #1E161B);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fbjx3y-qb {
  d: path("M25.449 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g9arp8b8o {
  d: path("M22.819 8.01h-.713a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.713c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.gcm7kgbsj {
  fill: var(--svg-color--3e2030, #3E2030);
  fill-rule: evenodd;
  d: path("M16.614 8.53c.717-.066 1.177.213 1.288.316a.47.47 0 1 0 .638-.692c-.305-.281-1.028-.653-2.014-.56a.47.47 0 0 0 .087.937");
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.h3zngkbgy {
  stop-color: var(--svg-color--784656, #784656);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hdusbzsjg {
  fill: var(--svg-color--000, #000);
  d: path("M16.504 10.463c0-.283.226-.51.51-.51a.507.507 0 0 1 .452.744h-.901a.46.46 0 0 1-.061-.234");
}

.hh437879c {
  cx: 19.589px;
  cy: 10.729px;
  r: 0.991px;
}

.hnxygroex {
  stop-color: var(--svg-color--624b78, #624B78);
  stop-opacity: 0;
}

.hui1uab7b {
  stop-color: var(--svg-color--754757, #754757);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hyj07d54k {
  d: path("M17.805 10.346a.84.84 0 0 0-.23-.461l-.26.284l.118.227z");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i4ysa-bno {
  cx: 10.109px;
  cy: 10.729px;
  r: 1.664px;
}

.i9v5wucat {
  d: path("M12.661 9.574a.89.89 0 0 0-.856 1.123h1.717a1 1 0 0 0 .033-.234a.895.895 0 0 0-.894-.89");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ii_vcdblz {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M10.76 16.494v4.63c-.002.26.024.579.25.72c.234.144.581-.02.743-.142l2.5-1.765V15.78a11 11 0 0 0-3.492.713");
}

.it1_ig0bc {
  stop-color: var(--svg-color--57525e, #57525E);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iv7bj_baj {
  stop-color: var(--svg-color--4680db, #4680DB);
  stop-opacity: 0;
}

.ixw-oi7aq {
  stop-color: var(--svg-color--3d3248, #3D3248);
}

.iycy_sbnz {
  d: path("M7.366 8.01h-.707a.49.49 0 0 1-.49-.49V6.49c-.01-.27.21-.49.49-.49h.707c.27 0 .49.22.49.49v1.02c0 .28-.22.5-.49.5");
}

.j0xtzac4y {
  stop-color: var(--svg-color--4d79b0, #4D79B0);
  stop-opacity: 0;
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j3h4o1d7b {
  stop-color: var(--svg-color--391f48, #391F48);
}

.javsik_yi {
  fill: var(--svg-color--f3d8ed, #F3D8ED);
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.jht53ab1w {
  cx: 12.393px;
  cy: 9.954px;
  rx: 0.388px;
  ry: 0.196px;
}

.jl9xgibbw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.948 9.762c.063.085-.07.188-.22.3c-.15.113-.262.192-.325.107c-.064-.084.007-.244.158-.357c.15-.112.323-.135.387-.05");
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.js7qsnbrb {
  d: path("M14.79 18.103c-1.239 0-2.239-.948-2.239-2.123v-2.637c0-1.164 1-2.112 2.24-2.112c1.239 0 2.239.948 2.239 2.122v2.638c-.011 1.164-1.011 2.112-2.24 2.112");
}

.jsbk_hbmd {
  stop-color: var(--svg-color--3e80ff, #3E80FF);
}

.jwqe_jbgo {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.22 9.303c.65 0 1.2.449 1.35 1.055a.273.273 0 0 1-.268.34H16.08a.23.23 0 0 1-.227-.271a1.39 1.39 0 0 1 1.366-1.124");
}

.kc9q3mbff {
  fill: var(--svg-color--c6c6c6, #C6C6C6);
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.ky_dg6bhp {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
}

.kyknafbgp {
  cx: 12.393px;
  cy: 9.954px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.388px;
  ry: 0.196px;
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l8cne9blx {
  stop-color: var(--svg-color--1e161b, #1E161B);
}

.l8p6brbrs {
  stop-color: var(--svg-color--38234f, #38234F);
}

.lasn3qwok {
  stop-color: var(--svg-color--93ffff, #93FFFF);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo1ogpbbw {
  stop-color: var(--svg-color--391f48, #391F48);
  stop-opacity: 0;
}

.lt_b3wboz {
  d: path("m3.769 30l4-.02l-.06-11.94a11 11 0 0 0-3.563 5.482c-.262.948-.4 1.947-.397 2.978z");
}

.ltwsa8bld {
  d: path("M7.757 10.031c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.47c.27 0 .48-.22.48-.48v-3.24c0-2.36-1.91-4.27-4.27-4.27h-7.45a4.253 4.253 0 0 0-4.27 4.26v3.24c0 .27.21.49.48.49z");
}

.lvlvw7bgp {
  stop-color: var(--svg-color--513a64, #513A64);
  stop-opacity: 0;
}

.m1_q07_me {
  stop-color: var(--svg-color--6899f0, #6899F0);
}

.m3dxw5b4u {
  d: path("M10.812 16.221v4.63c-.002.26.024.579.25.72c.234.144.581-.019.743-.141l2.5-1.766v-4.156a11 11 0 0 0-3.493.713");
}

.m4mhe8bqv {
  stop-color: var(--svg-color--4f94d3, #4F94D3);
  stop-opacity: 0;
}

.m8_l30tsr {
  stop-color: var(--svg-color--2a3765, #2A3765);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mguibccfx {
  stop-color: var(--svg-color--2a193d, #2A193D);
}

.mx797o4di {
  stop-color: var(--svg-color--4086f6, #4086F6);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.na59ribzw {
  d: path("M28.245 13.16c.081-.326-.151-.554-.478-.472c-.878.18-2.296.406-2.714.954c-.571.613-.55 1.582.03 2.184a1.577 1.577 0 0 0 2.256.01c.503-.512.733-1.836.906-2.676");
}

.ndlc49hkf {
  d: path("M21.974 6.741H7.744v3.29h14.23z");
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nzjwoybta {
  stop-color: var(--svg-color--675878, #675878);
  stop-opacity: 0;
}

.o12zmvuzn {
  d: path("M20.756 7.641a7.5 7.5 0 0 0-2.31-1.49c-1.09-.45-2.32-.68-3.66-.68c-1.22 0-2.36.2-3.38.6c-.84.33-1.61.79-2.28 1.38c-1.16 1-1.69 2.07-1.83 2.37c-.03.07-.04.14-.04.21h.5c.21-.47 1.98-4.06 7.03-4.06c5.6 0 7.04 4.06 7.04 4.06h.5c0-.06-.01-.11-.03-.17c-.01-.05-.41-1.14-1.54-2.22");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ojb-ttbmo {
  fill: var(--svg-color--c4ffff, #C4FFFF);
  d: path("M10.299 4.37h8.87c.31 0 .56-.25.56-.56V2.19c-.4-.12-.83-.19-1.27-.19h-7.45c-.44 0-.87.07-1.27.19v1.62c0 .31.25.56.56.56");
}

.oool1tdti {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.748 28.611h1.797");
}

.ott3_jqut {
  stop-color: var(--svg-color--534065, #534065);
}

.p2mvr3bvu {
  stop-color: var(--svg-color--784656, #784656);
  stop-opacity: 0;
}

.p3_97vb4n {
  stop-color: var(--svg-color--465e8a, #465E8A);
  stop-opacity: 0;
}

.p64oiyb7x {
  stop-color: var(--svg-color--55406a, #55406A);
}

.p6lllsbjv {
  fill: var(--svg-color--3e2030, #3E2030);
  fill-rule: evenodd;
  d: path("M13.066 8.53c-.717-.066-1.177.213-1.288.316a.47.47 0 1 1-.638-.692c.305-.281 1.028-.653 2.014-.56a.47.47 0 0 1-.088.937");
}

.p7prpqhjw {
  stop-color: var(--svg-color--5da7f2, #5DA7F2);
}

.ph46gxbvy {
  stop-color: var(--svg-color--4f8dd8, #4F8DD8);
}

.pi6c47yng {
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.pjsi77bhr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.67 27.307h1.797");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q-1fu8b-z {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.566 10.607l-.818 1.694c-.101.348.142.696.486.696h.735c.345 0 .588-.354.487-.697l-.497-1.693c-.107-.375-.282-.375-.393 0");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q955-k8fs {
  stop-color: var(--svg-color--754757, #754757);
}

.q9u3nxbxg {
  stop-color: var(--svg-color--513a64, #513A64);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qgmif2bih {
  stop-color: var(--svg-color--57525e, #57525E);
  stop-opacity: 0;
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qo28zhh9b {
  stop-color: var(--svg-color--3a2252, #3A2252);
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qtzewq2gr {
  d: path("M22.13 25.326c0-.402.326-.732.727-.732h2.392a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.qv8wc6zla {
  d: path("m26.449 14.92l-.71-.71l-1.42 1.42c-.38.38-.59.89-.59 1.42v5.54h1v-5.74c0-.14.05-.27.15-.37z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.qyg3b1b6n {
  stop-color: var(--svg-color--6f5b84, #6F5B84);
}

.r5fk93cur {
  stop-color: var(--svg-color--2869c1, #2869C1);
}

.rj390kbfq {
  d: path("M13.474 10.359c0-.288-.234-.48-.297-.537l-.287.278l.176.36z");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rq76sybla {
  d: path("M18.804 16.276v4.576c.003.26-.023.578-.25.718c-.233.145-.58-.018-.742-.14l-2.5-1.766v-4.15c1.228.064 2.403.329 3.492.762");
}

.rtj8_6bqg {
  stop-color: var(--svg-color--2a3765, #2A3765);
}

.rttu7sb8r {
  stop-color: var(--svg-color--3e2d2b, #3E2D2B);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s1a8ycb7r {
  stop-color: var(--svg-color--362d41, #362D41);
}

.s1rw4px-b {
  stop-color: var(--svg-color--465e8a, #465E8A);
}

.s21zh4b3w {
  stop-color: var(--svg-color--3d78d0, #3D78D0);
  stop-opacity: 0;
}

.s2fk7zbzg {
  stop-color: var(--svg-color--8f4f83, #8F4F83);
}

.s5pm96b_v {
  stop-color: var(--svg-color--3578e5, #3578E5);
  stop-opacity: 0;
}

.sb1phf9zd {
  d: path("M20.979 4.68H8.719v2.65h12.26z");
}

.si5zi3baz {
  stop-color: var(--svg-color--5e3f41, #5E3F41);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.sq-bwm1qa {
  stop-color: var(--svg-color--1f54c5, #1F54C5);
}

.t2vg81bwy {
  fill: var(--svg-color--291128, #291128);
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t8ye-ilvp {
  stop-color: var(--svg-color--7b51c6, #7B51C6);
}

.tay54u6mm {
  stop-color: var(--svg-color--4c272e, #4C272E);
}

.tizux9w7p {
  stop-color: var(--svg-color--3877cc, #3877CC);
  stop-opacity: 0;
}

.tr80mtbrp {
  fill: var(--svg-color--000, #000);
  d: path("M13.17 10.463a.507.507 0 0 0-.508-.51a.507.507 0 0 0-.453.744h.901a.5.5 0 0 0 .06-.234");
}

.troaenb0e {
  stop-color: var(--svg-color--428ef7, #428EF7);
}

.u-q3e7b8s {
  d: path("m15.659 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09a2.07 2.07 0 0 1 2.07-2.05c1.14 0 2.06.92 2.06 2.06v3.09c-.01.97-.42 1.89-1.14 2.54");
}

.u7iwqu4ui {
  stop-color: var(--svg-color--5f354b, #5F354B);
}

.u9ri-jbkw {
  stop-color: var(--svg-color--547eb3, #547EB3);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ue1gv6enh {
  d: path("M25.259 25.94h-2.05v-3c0-.19.16-.35.35-.35h1.35c.19 0 .35.16.35.35z");
}

.uf734fbqu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.455 9.303c-.65 0-1.2.449-1.35 1.055a.273.273 0 0 0 .267.34h2.223a.23.23 0 0 0 .226-.271a1.396 1.396 0 0 0-1.366-1.124");
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.uit74mbey {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.ul2vnhvnj {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.483 13.476a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24c.343.519.94.864 1.619.864c.68 0 1.276-.346 1.619-.865a.19.19 0 0 0-.02-.24a.2.2 0 0 0-.241-.04h-.001a2.9 2.9 0 0 1-1.357.322c-.498 0-.965-.118-1.357-.322Z");
}

.uvblrcend {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.459 8.39c.208-.192.8-.518 1.651-.438");
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vbc9nqbss {
  fill: var(--svg-color--1e64bd, #1E64BD);
  d: path("M21.729 18.01v11.98h3a1 1 0 0 0 1-1v-2.5c0-3.41-1.55-6.46-4-8.48");
}

.vbelliord {
  stop-color: var(--svg-color--8e5e64, #8E5E64);
}

.vczswwwcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.151 15.597a.85.85 0 1 0 0-1.7a.85.85 0 0 0 0 1.7");
}

.vmw-awokf {
  stop-color: var(--svg-color--372e2c, #372E2C);
  stop-opacity: 0;
}

.vrqwlje0q {
  stop-color: var(--svg-color--613847, #613847);
}

.wc7956bqp {
  cx: 10.109px;
  cy: 10.729px;
  r: 0.991px;
  fill: var(--svg-color--532e38, #532E38);
}

.wct4qccbg {
  cx: 19.589px;
  cy: 10.729px;
  r: 1.664px;
}

.wli8v5-ip {
  stop-color: var(--svg-color--745355, #745355);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wp6rq3sqk {
  stop-color: var(--svg-color--6e5981, #6E5981);
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.x9-b3hbfy {
  fill: var(--svg-color--1e6dc3, #1E6DC3);
  d: path("M18.365 16.768v4.575c.002.26-.024.578-.25.719c-.234.145-.581-.018-.743-.14l-2.5-1.766v-4.15c1.229.064 2.403.328 3.492.762");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y66dh_b5l {
  stop-color: var(--svg-color--675878, #675878);
}

.ybrylxbuq {
  d: path("m19.642 4.274l.428.212c.748.372 1.176 1.223 1.015 2.126l-.588 3.03c-.052.312-.259.523-.57.53c.036-.501.069-1.31.082-1.439c.043-.431-.025-.558-.42-.952c-.214-.212-.375-.531-.375-.85v-.85c0-.266-.213-.479-.427-.532c-.642-.16-1.978-.425-3.902-.425s-3.26.266-3.902.425a.52.52 0 0 0-.428.531v.85c0 .32-.107.639-.374.851l-.16.16c-.214.16-.322.492-.322.758c.014.155.035 1.048.059 1.419a.63.63 0 0 1-.592-.53l-.588-3.03c-.107-.85.32-1.7 1.069-2.072c1.01-.443 1.378-1.115 2.191-1.807c.588-.531 1.443-.69 2.192-.319a2.93 2.93 0 0 0 1.657 0c.801-.266 1.71-.053 2.351.532l.802.797c.214.266.481.425.802.585");
}

.yd41utmlw {
  stop-color: var(--svg-color--32263f, #32263F);
}

.yhrc8s1zu {
  stop-color: var(--svg-color--31263f, #31263F);
}

.yi5yu6x4i {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.32 8.452c-.477-.336-1.087-.492-1.75-.43");
}

.ym2yqhbxf {
  stop-color: var(--svg-color--996377, #996377);
  stop-opacity: 0;
}

.ypv_kpaja {
  stop-color: var(--svg-color--4680db, #4680DB);
}

.yrmgmz50r {
  stop-color: var(--svg-color--5e373c, #5E373C);
}

.yytwt1d8s {
  stop-color: var(--svg-color--362d41, #362D41);
  stop-opacity: 0;
}

.z-f4zlb4n {
  stop-color: var(--svg-color--251229, #251229);
}

.z2rllvutr {
  stop-color: var(--svg-color--8c68d5, #8C68D5);
}

.z88owpbip {
  stop-color: var(--svg-color--24132c, #24132C);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zyz2-nbsw {
  stop-color: var(--svg-color--975d72, #975D72);
}

</style>
