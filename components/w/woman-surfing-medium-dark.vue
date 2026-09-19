<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyHTAjG)"><path fill="url(#iXUQDLb)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#iZCQjRg)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#iLSojpb)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#iA1ESDd)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#imokkjd)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#iCadJLQ)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#i6Atgeb)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#iL9Xwrc)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#i2lFbnb)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#iZOIbQb)" clip-rule="evenodd" class="ky73x0y7d"/><path fill="url(#ieLHI8c)" clip-rule="evenodd" class="ky73x0y7d"/></g><g filter="url(#iSMxoMe)"><path class="v3o00sb-r"/><path fill="url(#iowsK2d)" class="spiav37_w"/></g><path fill="url(#ibynXii)" class="spiav37_w"/><path fill="url(#iF117ye)" class="spiav37_w"/><path fill="url(#iihFrAe)" class="spiav37_w"/><path fill="url(#io8EX5F)" class="spiav37_w"/><g filter="url(#iyW2JLb)"><path class="ti72hvb7a"/><path fill="url(#iydEkKe)" class="df2tm2kiw"/></g><path class="n56fboscg"/><path fill="url(#iaUQ09W)" class="f_bai15_a"/><path fill="url(#iZce21V)" class="pevp8osef"/><path fill="url(#imgPM3b)" class="squazsbic"/><path fill="url(#iJKMIsb)" class="squazsbic"/><g filter="url(#iaLNMJe)"><path fill="url(#i16dXQd)" class="xbuocibzd"/><path fill="url(#iPonf1c)" class="xbuocibzd"/></g><g filter="url(#iCD7yad)"><circle fill="url(#igywHHb)" class="lwub8rssv"/></g><g filter="url(#iA22Ntd)"><circle fill="url(#iFuLNKe)" class="pd-zpcboh"/></g><g filter="url(#i5hRyhe)"><circle fill="url(#iRaRmfb)" class="b-ol02ugq"/></g><rect fill="url(#iKSozFd)" transform="rotate(26.595 20.662 12.82)" class="oomjc-sil"/><g filter="url(#iIcad2c)"><path fill="url(#iXciOTc)" class="z6w0stb_p"/></g><path class="peboev3qr"/><g filter="url(#iCVBpzR)"><path class="v6w85gvyn"/><path fill="url(#i19w8xe)" class="hn_bv-o8l"/><path fill="url(#iQyx2Wd)" class="hn_bv-o8l"/></g><g filter="url(#iOUvISc)"><path fill="url(#ipp2gzz)" class="sfsv_3a8g"/><path fill="url(#i0xbTKc)" class="sfsv_3a8g"/><path fill="url(#iLd4nFc)" class="sfsv_3a8g"/></g><path fill="url(#iEoY6lI)" class="sfsv_3a8g"/><path fill="url(#iynIiHo)" class="gucljibwu"/><path fill="url(#iqwHkAf)" class="gucljibwu"/><path clip-rule="evenodd" class="hg_t1bday"/><path fill="url(#iQSMnLb)" clip-rule="evenodd" class="w8uqgs95a"/><path clip-rule="evenodd" class="evfvct-qj"/><path fill="url(#iqKZAhc)" clip-rule="evenodd" class="bl_kaz3mv"/><path clip-rule="evenodd" class="kxn5dhbfw"/><path fill="url(#il2d4Bc)" clip-rule="evenodd" class="n8i4bqb2n"/><path clip-rule="evenodd" class="vln9mtb2n"/><path fill="url(#i83aPKb)" clip-rule="evenodd" class="gajp_bcxs"/><path class="obf6m6btg"/><path fill="url(#iG3cVMb)" class="wzla9f9hn"/><g filter="url(#idQTLue)"><path fill="url(#iVxKvFH)" class="wd51-mbqr"/></g><g filter="url(#ib2o9Fc)"><path fill="url(#idJlRfc)" class="vvbxneb8i"/></g><g filter="url(#iBUWGBh)"><path stroke="url(#iUwJeuc)" class="bstx89bkb"/></g><g filter="url(#ieezC5d)"><path fill="url(#i6ANFQd)" class="zw9dk7_gn"/></g><g filter="url(#i8mikLb)"><path fill="url(#iHIze4Y)" class="ezwvyjbgd"/><path fill="url(#iaY4J7c)" class="ezwvyjbgd"/></g><g filter="url(#iZ5dtQq)"><path class="ndhxmjbhk"/><path fill="url(#im8Ngjd)" class="kulekbbdr"/></g><g filter="url(#iCGZCfc)"><path class="p1c36qb0p"/><path fill="url(#iQGnYJb)" class="edey37bkf"/></g><path fill="url(#iihTxgb)" class="u8bt2vh8z"/><path fill="url(#iakVNge)" class="u8bt2vh8z"/><path fill="url(#ievsZHd)" class="u8bt2vh8z"/><path fill="url(#iPt8sMe)" class="u8bt2vh8z"/><path fill="url(#idjqt8d)" class="u8bt2vh8z"/><path fill="url(#iMmWhfg)" class="u8bt2vh8z"/><path fill="url(#iBqVJCe)" class="u8bt2vh8z"/><path fill="url(#i15AkNb)" class="u8bt2vh8z"/><path fill="url(#ieL0xYb)" class="u8bt2vh8z"/><path fill="url(#ijVXfuc)" class="u8bt2vh8z"/><path fill="url(#islhjUz)" class="u8bt2vh8z"/><g filter="url(#iPUtx4d)"><path class="b09mlfbiy"/></g><g filter="url(#ifXFRPc)"><path class="jsoj3zb4g"/><path fill="url(#iXIWx8d)" class="q7sghhb7r"/><path fill="url(#id4FRyd)" class="q7sghhb7r"/><path fill="url(#iDHz6vd)" class="q7sghhb7r"/><path fill="url(#i2CzEtI)" class="q7sghhb7r"/></g><g filter="url(#iVB0uoc)"><path stroke="url(#iAip3kc)" class="tepvci4fv"/></g><path class="bg48d4bgb"/><g filter="url(#iblfWZe)"><path class="h_wlmobny"/></g><g filter="url(#iAyIzud)"><path class="iiddcpbjy"/></g><g filter="url(#ix27Aqd)"><path class="gup2v7b1l"/></g><g filter="url(#iwzCVie)"><path clip-rule="evenodd" class="advjedcfm"/></g><path class="mxapj4bet"/><path fill="url(#iyi86Be)" class="mk-ekgbrr"/><path class="m83dwdzqt"/><g filter="url(#ioeLFud)"><path class="gt4i2pufu"/><path fill="url(#iasY9Fb)" class="h_-534bnn"/></g><g filter="url(#i16A7Rd)"><path fill="url(#iLw4sJb)" class="k2upteb3j"/></g><path class="tgeakqbju"/><path fill="url(#iOoN6ub)" class="lpb4-ho7u"/><path class="ikctb2biu"/><g filter="url(#iAnbhfb)"><path fill="url(#itZbXDb)" class="ai828bc5p"/></g><g filter="url(#iZDR8Kc)"><ellipse transform="rotate(-27.914 13.025 5.697)" class="tc20nkbkx"/><ellipse fill="url(#i6xjh4c)" transform="rotate(-27.914 13.025 5.697)" class="jkpb8hegz"/></g><g filter="url(#iBjYvpb)"><path class="a1kb-gbjm"/><path fill="url(#iaq9Zfb)" class="c6gtp0frs"/></g><g filter="url(#i3SFoOd)"><path class="hpqs6fynv"/><path fill="url(#i6nHzqO)" class="bxvk24bop"/><path fill="url(#ijkWpZo)" class="bxvk24bop"/></g><g filter="url(#iLngKOc)"><path class="of7ndv-6i"/></g><defs><radialGradient id="iZCQjRg" cx="0" cy="0" r="1" gradientTransform="matrix(-.26786 2.02388 -2.52824 -.33462 13.98 7.115)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iLSojpb" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 5.26 5.563)scale(1.54369 2.02829)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iA1ESDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.58037 .75896 -.58278 -.44565 11.964 6.103)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="imokkjd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 4.624 6.013)scale(1.09874 .77397)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iCadJLQ" cx="0" cy="0" r="1" gradientTransform="matrix(.61014 1.16076 -1.6113 .84697 12.552 2.427)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="i6Atgeb" cx="0" cy="0" r="1" gradientTransform="matrix(-.63987 .63991 -.89425 -.89419 16.704 3.35)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iL9Xwrc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81845 .2381 -.49655 -1.7068 17.448 5.627)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i2lFbnb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 8.15 4.63)scale(1.28848 1.64133)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iZOIbQb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4015 -1.17652 .93055 -.31757 16.216 4.546)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ieLHI8c" cx="0" cy="0" r="1" gradientTransform="matrix(.66763 .07003 -.11347 1.08175 11.388 5.61)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ibynXii" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.78)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="iihFrAe" cx="0" cy="0" r="1" gradientTransform="matrix(3.56253 -6.12498 3.8162 2.21965 22.203 21.937)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="io8EX5F" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.781)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iydEkKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.169 25.219)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iaUQ09W" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.761 25.15)" gradientUnits="userSpaceOnUse"><stop class="nz1yf2bug"/><stop offset="1" class="c2e0llb1c"/></radialGradient><radialGradient id="iJKMIsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.484)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="iPonf1c" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.746 2.824)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="igywHHb" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.213 11.143)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iFuLNKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.567)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iRaRmfb" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.166 9.178)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iKSozFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.119)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="bv25hsebv"/><stop offset="1" class="j_v8jdemw"/></radialGradient><radialGradient id="iXciOTc" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.197 10.93)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="m3ok-p19m"/><stop offset="1" class="fv0gs1r5b"/></radialGradient><radialGradient id="i19w8xe" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.924 6.723)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="hiph0yb8z"/><stop offset="1" class="nng6piu-d"/></radialGradient><radialGradient id="iQyx2Wd" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.33 10.558)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="rjhj4ebho"/><stop offset="1" class="m0m5thktx"/></radialGradient><radialGradient id="i0xbTKc" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.328 24.437)" gradientUnits="userSpaceOnUse"><stop class="zhpuq6bwb"/><stop offset="1" class="lrsiznbuc"/></radialGradient><radialGradient id="iLd4nFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.49191 -2.04898 0 13.776 7.617)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="sz7_smkrr"/><stop offset="1" class="rqh0k2bpm"/></radialGradient><radialGradient id="iEoY6lI" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 -.625 2.3294 4.19292 17.339 21.25)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="tn---htwd"/><stop offset="1" class="accyaboul"/></radialGradient><radialGradient id="iqwHkAf" cx="0" cy="0" r="1" gradientTransform="matrix(3.55689 1.62587 -1.10084 2.4083 18.61 10.764)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="ns_rnx4db"/><stop offset="1" class="airol1bay"/><stop offset="1" class="cfcr9ub1k"/></radialGradient><radialGradient id="iQSMnLb" cx="0" cy="0" r="1" gradientTransform="rotate(-164.074 4.364 6.446)scale(1.78035 1.88131)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="iqKZAhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6671 -.63637 .8491 -2.2244 6.355 14.415)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="il2d4Bc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6486 -.68743 .9779 -2.34523 6.177 14.958)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="i83aPKb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40308 -.60156 .87252 -2.03506 6.294 15.229)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="iG3cVMb" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.791)" gradientUnits="userSpaceOnUse"><stop class="d0tatcb7l"/><stop offset="1" class="ri6ddsbqu"/></radialGradient><radialGradient id="iVxKvFH" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.505 15.408)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iHIze4Y" cx="0" cy="0" r="1" gradientTransform="matrix(1.10495 -.50225 .61322 1.34909 15.908 6.2)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iaY4J7c" cx="0" cy="0" r="1" gradientTransform="matrix(.5841 .3274 -.09256 .16513 16.366 5.259)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="im8Ngjd" cx="0" cy="0" r="1" gradientTransform="matrix(.67028 -.04986 .03898 .52397 16.064 6.055)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iQGnYJb" cx="0" cy="0" r="1" gradientTransform="rotate(180 6.036 3.002)scale(.46877)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iihTxgb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.06 4.571)scale(3.17927 4.2554)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iakVNge" cx="0" cy="0" r="1" gradientTransform="matrix(-.96788 .4259 -.29659 -.67402 14.99 6.145)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="ievsZHd" cx="0" cy="0" r="1" gradientTransform="matrix(.57229 -1.7439 2.21268 .72612 13.155 8.655)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iPt8sMe" cx="0" cy="0" r="1" gradientTransform="rotate(99.884 4.938 8.916)scale(3.32245 4.15302)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="idjqt8d" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.142 3.992)scale(3.12406 5.37868)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iMmWhfg" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51085 .62696 0 15.136 5.58)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iBqVJCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58266 .66776 0 13.193 5.479)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="i15AkNb" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.62 7.918)scale(1.4836 1.18712)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="ieL0xYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57057 0 0 -2.86134 16.377 6.24)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="ijVXfuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.35375 -.57571 .61175 -.3759 15.729 8.316)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="islhjUz" cx="0" cy="0" r="1" gradientTransform="matrix(.77686 -.69363 .8236 .92243 12.323 8.31)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iXIWx8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.20223 -.90739 .27965 -.06232 14.462 6.564)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i2CzEtI" cx="0" cy="0" r="1" gradientTransform="matrix(-.346 0 0 -.09673 14.356 6.657)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iyi86Be" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36016 -.57288 0 15.083 5.74)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iasY9Fb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.906 -.78)scale(.16754 .23065)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOoN6ub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36017 -.57288 0 13.146 5.74)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6xjh4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00343 -.21881 .26302 -.00412 13.018 5.837)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaq9Zfb" cx="0" cy="0" r="1" gradientTransform="matrix(.56025 -1.2232 .62576 .2866 11.603 4.798)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i6nHzqO" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.7 5.947)scale(2.1632 3.5367)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ijkWpZo" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 5.967 7.42)scale(.61407 1.32114)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iyHTAjG" width="6.917" height="7.417" x="10.781" y="1.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iSMxoMe" width="23.977" height="13.398" x="6.016" y="16.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iyW2JLb" width="20.681" height="10.082" x="6.11" y="20.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".75"/></filter><filter id="iaLNMJe" width="24.344" height="8.644" x="2.007" y="21.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iCD7yad" width="2.686" height="2.686" x="24.571" y="13.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iA22Ntd" width="2.186" height="2.186" x="27.821" y="11.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="i5hRyhe" width="1.928" height="1.928" x="25.946" y="9.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iIcad2c" width="2.857" height="2.898" x="20.532" y="12.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iCVBpzR" width="5.571" height="6.952" x="7.773" y="7.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.219608 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iOUvISc" width="14.97" height="18.152" x="8.427" y="7.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.470588 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="idQTLue" width="17.737" height="14.8" x="13.579" y="15.862" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation="1"/></filter><filter id="ib2o9Fc" width="6.506" height="14.75" x="14.572" y="7.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".375"/></filter><filter id="iBUWGBh" width="5.506" height="5.421" x="17.991" y="7.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".3"/></filter><filter id="ieezC5d" width="1.579" height="1.429" x="11.32" y="5.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="i8mikLb" width="1.429" height="1.679" x="15.543" y="5.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iZ5dtQq" width="1.954" height="1.954" x="15.281" y="5.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".25"/></filter><filter id="iCGZCfc" width="1.454" height="1.454" x="11.316" y="5.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".125"/></filter><filter id="iPUtx4d" width="1.833" height="2.191" x="13.126" y="5.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".25"/></filter><filter id="ifXFRPc" width="1.033" height="1.391" x="13.598" y="5.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".05"/></filter><filter id="iVB0uoc" width="1.866" height=".9" x="13.182" y="6.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".05"/></filter><filter id="iblfWZe" width="1.444" height=".571" x="14.422" y="5.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iAyIzud" width="1.444" height=".571" x="12.364" y="5.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="ix27Aqd" width="1.2" height=".596" x="12.424" y="4.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="iwzCVie" width="1.2" height=".596" x="14.829" y="4.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/></filter><filter id="ioeLFud" width=".46" height=".42" x="14.702" y="5.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".05"/></filter><filter id="i16A7Rd" width=".618" height=".627" x="15.019" y="5.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".1"/></filter><filter id="iAnbhfb" width=".66" height=".684" x="13.047" y="5.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".1"/></filter><filter id="iZDR8Kc" width=".516" height=".424" x="12.767" y="5.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".05"/></filter><filter id="iBjYvpb" width="2.415" height="2.548" x="11.071" y="2.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/><feGaussianBlur result="effect2_foregroundBlur_3987_22995" stdDeviation=".2"/></filter><filter id="i3SFoOd" width="4.198" height="2.845" x="12.54" y="2.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22995"/><feGaussianBlur result="effect2_foregroundBlur_3987_22995" stdDeviation=".125"/></filter><filter id="iLngKOc" width="4.187" height="2.831" x="13.189" y="2.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22995" stdDeviation=".5"/></filter><linearGradient id="iXUQDLb" x1="16.198" x2="13.177" y1="2.918" y2="8.514" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iowsK2d" x1="7.172" x2="16.735" y1="29.375" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iF117ye" x1="16.86" x2="16.766" y1="30.281" y2="28.656" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="iZce21V" x1="21.172" x2="19.469" y1="21.937" y2="23.023" gradientUnits="userSpaceOnUse"><stop class="sgu3uubpp"/><stop offset="1" class="hpb-k7b_o"/></linearGradient><linearGradient id="imgPM3b" x1="22.095" x2="23.329" y1="24.843" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="i16dXQd" x1="5.891" x2="25.735" y1="29.25" y2="22.343" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="ipp2gzz" x1="15.777" x2="15.777" y1="7.617" y2="25.578" gradientUnits="userSpaceOnUse"><stop class="t_t1uhgaw"/><stop offset="1" class="wlohty-lv"/></linearGradient><linearGradient id="iynIiHo" x1="23.651" x2="16.517" y1="12.514" y2="8.56" gradientUnits="userSpaceOnUse"><stop class="g55u5uboh"/><stop offset=".91" class="hq3x-3bjw"/></linearGradient><linearGradient id="idJlRfc" x1="17.826" x2="20.269" y1="8.171" y2="21.408" gradientUnits="userSpaceOnUse"><stop class="xf-olmy6i"/><stop offset="1" class="nb49g6u5x"/></linearGradient><linearGradient id="iUwJeuc" x1="22.438" x2="18.766" y1="11.89" y2="8" gradientUnits="userSpaceOnUse"><stop class="o-7v_hpgv"/><stop offset="1" class="qosi95ahb"/></linearGradient><linearGradient id="i6ANFQd" x1="11.343" x2="11.893" y1="6.044" y2="6.044" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="id4FRyd" x1="13.698" x2="14.115" y1="6.596" y2="6.596" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iDHz6vd" x1="14.115" x2="14.115" y1="6.95" y2="6.679" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iAip3kc" x1="13.642" x2="13.847" y1="7.576" y2="7.26" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iLw4sJb" x1="15.428" x2="15.289" y1="5.763" y2="5.849" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itZbXDb" x1="13.476" x2="13.337" y1="5.763" y2="5.849" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-surfing-medium-dark" /></template>
<style>
.a1kb-gbjm {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M11.864 3.346c.251-.266.727-.266.946-.226l.176.573a.34.34 0 0 0-.296.104c-.2.56-.884.868-1.2.952c-.067-.662.047-1.056.374-1.403");
}

.accyaboul {
  stop-color: var(--svg-color--593b9d, #593B9D);
  stop-opacity: 0;
}

.advjedcfm {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m15.771 5.013l-.061.102za.12.12 0 0 1-.122.205l-.002-.001l-.01-.006l-.04-.02a1 1 0 0 0-.152-.06a1 1 0 0 0-.476-.041a.119.119 0 1 1-.042-.234c.228-.04.44 0 .59.048a1.5 1.5 0 0 1 .248.106l.004.002z");
}

.ai828bc5p {
  d: path("M13.506 5.877c0-.128-.104-.213-.132-.239l-.127.124l.078.16z");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.airol1bay {
  stop-color: var(--svg-color--815ecd, #815ECD);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b-ol02ugq {
  cx: 26.86px;
  cy: 10.738px;
  r: 0.914px;
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b09mlfbiy {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m13.94 5.906l-.303.755a.24.24 0 0 0 .231.31h.35a.24.24 0 0 0 .23-.31l-.236-.755c-.05-.167-.219-.167-.272 0");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bg48d4bgb {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M14.115 7.297c-.232 0-.449-.055-.631-.153c-.063-.032-.13.04-.09.098a.858.858 0 0 0 1.442 0c.04-.06-.028-.13-.09-.098a1.34 1.34 0 0 1-.631.153");
}

.bl_kaz3mv {
  fill-rule: evenodd;
  d: path("M5.404 14.15s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bstx89bkb {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.297c1.209-.021 3.782.828 4.104 4");
}

.bv25hsebv {
  stop-color: var(--svg-color--744543, #744543);
}

.bxvk24bop {
  d: path("M13.847 2.546c-.503-.11-.954.391-1.006.577c.466 1.574 1.648 1.488 2.814 1.358c.698-.078.774.24.833.394c0-1.745-1.484-2.073-2.628-2.326z");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c2e0llb1c {
  stop-color: var(--svg-color--8f6c66, #8F6C66);
  stop-opacity: 0;
}

.c6gtp0frs {
  d: path("M11.864 3.346c.251-.266.727-.266.946-.226l.176.573a.34.34 0 0 0-.296.104c-.2.56-.884.868-1.2.952c-.067-.662.047-1.056.374-1.403");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cfcr9ub1k {
  stop-color: var(--svg-color--6845b9, #6845B9);
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

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d0tatcb7l {
  stop-color: var(--svg-color--906e6a, #906E6A);
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.df2tm2kiw {
  d: path("m21.985 27.344l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.624-3.281 4.124");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.edey37bkf {
  d: path("M12.043 6.482a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.evfvct-qj {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M5.404 14.15s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.ezwvyjbgd {
  d: path("M16.258 6.72a.714.714 0 1 0 0-1.43a.714.714 0 0 0 0 1.43");
}

.f_bai15_a {
  d: path("m7.305 27.36l1.172-2.392l1.766.305v1.04z");
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv0gs1r5b {
  stop-color: var(--svg-color--794853, #794853);
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g55u5uboh {
  stop-color: var(--svg-color--896ad2, #896AD2);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gajp_bcxs {
  fill-rule: evenodd;
  d: path("M5.611 14.956a.375.375 0 0 1-.69-.295c.093-.216.328-.446.6-.605a1.76 1.76 0 0 1 1.119-.236a.375.375 0 1 1-.099.743a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.089");
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gt4i2pufu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.055 5.612c.028.038-.031.084-.098.134s-.117.085-.145.047c-.028-.037.003-.109.07-.159s.144-.06.173-.022");
}

.gucljibwu {
  d: path("M17.568 10.289a.37.37 0 0 1 .34-.416c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.075a.05.05 0 0 0 .052-.047c.033-.793-.235-2.545-1.589-3.592c-1.381-1.069-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.672");
}

.gup2v7b1l {
  fill: var(--svg-color--352827, #352827);
  d: path("M12.606 5.216h-.002a.12.12 0 0 1-.122-.203l.002-.002l.004-.002l.015-.008l.051-.026c.044-.021.106-.048.182-.072c.151-.048.362-.089.59-.048a.12.12 0 0 1-.042.234c-.177-.031-.347 0-.475.04a1 1 0 0 0-.193.081z");
}

.h_-534bnn {
  d: path("M15.055 5.612c.028.038-.031.084-.098.134s-.117.085-.145.047c-.028-.037.003-.109.07-.159s.144-.06.173-.022");
}

.h_wlmobny {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M14.622 5.752c.118-.207.297-.37.682-.37c.169 0 .332.046.476.163c.12.096.104.22.011.266l-.246.14c-.29-.093-.61-.105-.923-.199");
}

.hg_t1bday {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M7.127 13.555c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 1 1-.216.719");
}

.hiph0yb8z {
  stop-color: var(--svg-color--8069a8, #8069A8);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hn_bv-o8l {
  d: path("M10.684 11.707c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hpb-k7b_o {
  stop-color: var(--svg-color--6b3f38, #6B3F38);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hpqs6fynv {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M13.847 2.546c-.503-.11-.954.391-1.006.577c.466 1.574 1.648 1.488 2.814 1.358c.698-.078.774.24.833.394c0-1.745-1.484-2.073-2.628-2.326z");
}

.hq3x-3bjw {
  stop-color: var(--svg-color--8c6dd3, #8C6DD3);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.iiddcpbjy {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.608 5.752c-.118-.207-.297-.37-.683-.37a.74.74 0 0 0-.476.163c-.12.096-.103.22-.01.266l.246.14c.29-.093.61-.105.923-.199");
}

.ikctb2biu {
  fill: var(--svg-color--000, #000);
  d: path("M13.372 5.924c0-.126-.1-.227-.227-.227a.226.226 0 0 0-.202.332h.402a.2.2 0 0 0 .027-.105");
}

.j_v8jdemw {
  stop-color: var(--svg-color--703d44, #703D44);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jgkh1vbol {
  stop-color: var(--svg-color--8a675b, #8A675B);
  stop-opacity: 0;
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jkpb8hegz {
  cx: 13.025px;
  cy: 5.697px;
  rx: 0.173px;
  ry: 0.087px;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jsoj3zb4g {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m13.945 5.844l-.236.755a.24.24 0 0 0 .231.31h.35a.24.24 0 0 0 .23-.31l-.236-.755c-.05-.167-.286-.167-.34 0");
}

.k2upteb3j {
  d: path("M15.437 5.871a.37.37 0 0 0-.103-.205l-.115.127l.052.1z");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kulekbbdr {
  d: path("M16.258 6.482a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.kxn5dhbfw {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M5.25 14.678q-.005.006-.002.001a.375.375 0 0 1-.69-.296c.056-.129.165-.253.27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.369a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.262a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.ky73x0y7d {
  fill-rule: evenodd;
  d: path("M17.304 6.63a1.44 1.44 0 0 0 .144-.633c0-.207-.043-.402-.12-.58h.003a1.4 1.4 0 0 0-.125-.227v-.001a1.44 1.44 0 0 1-.234-.787v-.004c0-.809-.656-1.465-1.465-1.465a.24.24 0 0 1-.202-.103a1.468 1.468 0 0 0-2.381 0a.25.25 0 0 1-.202.103h-.038a1.465 1.465 0 0 0-1.427 1.465v.004c0 .279-.08.553-.233.787l-.001.001a1.47 1.47 0 0 0-.098 1.44a.23.23 0 0 1 0 .203a1.427 1.427 0 0 0 1.285 2.053h3.81a1.426 1.426 0 0 0 1.284-2.053a.23.23 0 0 1 0-.202m-5.442-1.186h-.006l.532 1.046c.055 1.244.54 0 1.726 0s1.704 1.385 1.758.14l.505-1.419c-.024-.552-.425-.591-.505-.591h-1.43a1.72 1.72 0 0 1-1.415-.743a.117.117 0 0 0-.205.023l-.036.086c-.1.249-.291.44-.528.548l-.023.009l-.023.009c-.104.054-.35.217-.36.639l.005.136z");
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpb4-ho7u {
  d: path("M13.145 5.528a.396.396 0 0 0-.382.5h.766a.4.4 0 0 0-.384-.5");
}

.lrsiznbuc {
  stop-color: var(--svg-color--623f8d, #623F8D);
  stop-opacity: 0;
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.lwub8rssv {
  cx: 25.864px;
  cy: 14.773px;
  r: 1.293px;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m0m5thktx {
  stop-color: var(--svg-color--572cad, #572CAD);
  stop-opacity: 0;
}

.m3ok-p19m {
  stop-color: var(--svg-color--997a72, #997A72);
}

.m83dwdzqt {
  fill: var(--svg-color--000, #000);
  d: path("M14.857 5.924c0-.126.101-.227.227-.227a.226.226 0 0 1 .202.332h-.402a.2.2 0 0 1-.027-.105");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mk-ekgbrr {
  d: path("M15.084 5.528a.396.396 0 0 1 .382.5H14.7a.398.398 0 0 1 .383-.5");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxapj4bet {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.176 5.407c.29 0 .535.2.601.47a.122.122 0 0 1-.118.152h-.99a.102.102 0 0 1-.102-.121a.62.62 0 0 1 .609-.5");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n56fboscg {
  fill: var(--svg-color--81584a, #81584A);
  d: path("m7.305 27.36l1.172-2.392l1.766.305v1.04z");
}

.n8i4bqb2n {
  fill-rule: evenodd;
  d: path("M5.25 14.678q-.005.006-.002.001a.375.375 0 0 1-.69-.296c.056-.129.165-.253.27-.354a2.6 2.6 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.369a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.262a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.nb49g6u5x {
  stop-color: var(--svg-color--8b79ca, #8B79CA);
}

.ndhxmjbhk {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M16.258 6.482a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nng6piu-d {
  stop-color: var(--svg-color--8069a8, #8069A8);
  stop-opacity: 0;
}

.ns_rnx4db {
  stop-color: var(--svg-color--6845b9, #6845B9);
}

.nz1yf2bug {
  stop-color: var(--svg-color--8f6c66, #8F6C66);
}

.o-7v_hpgv {
  stop-color: var(--svg-color--9577dc, #9577DC);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.obf6m6btg {
  fill: var(--svg-color--815b52, #815B52);
  d: path("M6.126 14.898c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.of7ndv-6i {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m15.183 4.149l-.633.116a.306.306 0 1 1-.055-.606h1.039c.614 0 .818.62.843.831a1.4 1.4 0 0 0-1.194-.341");
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.oomjc-sil {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.82px;
  rx: 0.299px;
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p1c36qb0p {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M12.043 6.482a.477.477 0 1 0 0-.954a.477.477 0 0 0 0 .954");
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pd-zpcboh {
  cx: 28.864px;
  cy: 12.824px;
  r: 1.043px;
}

.peboev3qr {
  fill: var(--svg-color--825c4d, #825C4D);
  d: path("M7.602 12.787h.594c-.106.669.012 1.608.114 1.996c-1.006.132-1.637-.108-1.856-.246l-.11-1.461c.332-.256.977-.3 1.258-.29");
}

.pevp8osef {
  d: path("M19.837 23.023a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.q7sghhb7r {
  d: path("m13.945 5.844l-.236.755a.24.24 0 0 0 .231.31h.35a.24.24 0 0 0 .23-.31l-.236-.755c-.05-.167-.286-.167-.34 0");
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qosi95ahb {
  stop-color: var(--svg-color--9577dc, #9577DC);
  stop-opacity: 0;
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

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.ri6ddsbqu {
  stop-color: var(--svg-color--906e6a, #906E6A);
  stop-opacity: 0;
}

.rjhj4ebho {
  stop-color: var(--svg-color--572cad, #572CAD);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rqh0k2bpm {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
  stop-opacity: 0;
}

.sfsv_3a8g {
  d: path("M12.759 11.664c-.432-1.715.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.8 1.589 3.592a.05.05 0 0 1-.051.047l-1.989-.075a.05.05 0 0 1-.049-.058c.038-.37-.066-1.273-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.513 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.192 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.852a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.826-2.562-3.99c-.062-.163-.23-.53-.574-.53c-.275 0-.59.351-.809.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.163 4.542-9.51 4.773-10.057c.21-.5.181-.917.14-1.086c-.03-.13-.218-.711-.585-2.172");
}

.sgu3uubpp {
  stop-color: var(--svg-color--967a70, #967A70);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.spiav37_w {
  d: path("M19.75 29.759H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.squazsbic {
  d: path("m23.469 25.338l-.422-1.143l-2.351.536l2.225 1.1a.396.396 0 0 0 .547-.493");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sz7_smkrr {
  stop-color: var(--svg-color--6f43ac, #6F43AC);
}

.t_t1uhgaw {
  stop-color: var(--svg-color--8463ce, #8463CE);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tc20nkbkx {
  cx: 13.025px;
  cy: 5.697px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.173px;
  ry: 0.087px;
}

.tepvci4fv {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.115 7.297c-.232 0-.449-.055-.631-.153c-.063-.032-.13.04-.09.098a.858.858 0 0 0 1.442 0c.04-.06-.028-.13-.09-.098a1.34 1.34 0 0 1-.631.153Z");
}

.tgeakqbju {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.053 5.407a.62.62 0 0 0-.601.47c-.02.078.04.152.119.152h.99a.102.102 0 0 0 .1-.121a.62.62 0 0 0-.608-.5");
}

.ti72hvb7a {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("m21.985 27.344l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.624-3.281 4.124");
}

.tn---htwd {
  stop-color: var(--svg-color--593b9d, #593B9D);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u8bt2vh8z {
  d: path("M11.856 5.444h.006l-.005-.117l-.004-.136c.009-.422.255-.585.36-.639l.022-.01l.023-.008c.237-.109.428-.3.528-.548l.036-.086c.037-.086.15-.1.205-.023c.319.467.852.743 1.416.743h1.43c.08 0 .48.039.504.591l-.053 1.365c-.055 1.244-1.026 2.079-2.212 2.079s-2.158-.835-2.212-2.08z");
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v3o00sb-r {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.759H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.v6w85gvyn {
  fill: var(--svg-color--7a5cb9, #7A5CB9);
  d: path("M10.684 11.707c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vln9mtb2n {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M5.611 14.956a.375.375 0 0 1-.69-.295c.093-.216.328-.446.6-.605a1.76 1.76 0 0 1 1.119-.236a.375.375 0 1 1-.099.743a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.089");
}

.vvbxneb8i {
  d: path("M16.782 13.46c-.65-1.28-1.166-3.184-1.443-4.422a.714.714 0 0 1 .588-.856c.447-.075.855.271.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.312 1.062.234 3.516c-.057 1.78 1.266 3.25 1.813 4.109l-.407.21c-.609-.827-2.203-2.944-2.203-4.85c0-1.792.063-1.141-.937-3.11");
}

.w8uqgs95a {
  fill-rule: evenodd;
  d: path("M7.127 13.555c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 1 1-.216.719");
}

.wd51-mbqr {
  d: path("M26.485 24.344c.981-2.279.626-3.887.055-5.014c-.474-.936-.003-1.662 1.018-1.42c.737.173 1.364.693 1.54 1.43c.721 3.025-.313 6.182-3.582 7.816c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.722 10.906-4.282");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wlohty-lv {
  stop-color: var(--svg-color--6247a5, #6247A5);
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wvc2-1b2k {
  stop-color: var(--svg-color--8a675b, #8A675B);
}

.wzla9f9hn {
  d: path("M6.126 14.898c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.xbuocibzd {
  d: path("M24.458 21.273L2.29 28.962a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.099 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.001c.094-.25.047-1.032-.5-1.454c-.437-.337-1.105-.184-1.355-.07");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xf-olmy6i {
  stop-color: var(--svg-color--9a7ce0, #9A7CE0);
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z6w0stb_p {
  d: path("M20.68 13.86c.256-.588.373-1.22.399-1.462l2.047.024c.046.269-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.018a.43.43 0 0 1-.227.018a.43.43 0 0 1-.204-.112a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.041c-.098-.082-.219-.176.031-.747");
}

.zhpuq6bwb {
  stop-color: var(--svg-color--623f8d, #623F8D);
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zw9dk7_gn {
  d: path("M12.035 6.72a.714.714 0 1 0 0-1.43a.714.714 0 0 0 0 1.43");
}

</style>
