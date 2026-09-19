<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4iLdbe)"><path fill="url(#iWentAe)" clip-rule="evenodd" class="up54513se"/><path fill="url(#iE4kjLc)" clip-rule="evenodd" class="up54513se"/><path fill="url(#iwWzBGc)" clip-rule="evenodd" class="up54513se"/><path fill="url(#iRRiWGb)" clip-rule="evenodd" class="up54513se"/><path fill="url(#i0aGyod)" clip-rule="evenodd" class="up54513se"/><path fill="url(#i1A9Nfe)" clip-rule="evenodd" class="up54513se"/><path fill="url(#iTun5nb)" clip-rule="evenodd" class="up54513se"/><path fill="url(#i83YGka)" clip-rule="evenodd" class="up54513se"/><path fill="url(#io7Ciib)" clip-rule="evenodd" class="up54513se"/><path fill="url(#igriQTb)" clip-rule="evenodd" class="up54513se"/><path fill="url(#iTKaG7d)" clip-rule="evenodd" class="up54513se"/></g><path fill="url(#i4nhBEc)" class="nh8uxd9yq"/><path fill="url(#iMgzVBd)" class="nh8uxd9yq"/><path fill="url(#iyIEsgb)" class="nh8uxd9yq"/><path fill="url(#iL6b4oc)" class="nh8uxd9yq"/><rect fill="url(#iqyQthe)" class="c-m0h9unw"/><rect fill="url(#i9VU1Ne)" class="c-m0h9unw"/><path class="sytdg2lon"/><path fill="url(#iyIVSxb)" class="am_leczcr"/><path fill="url(#i69MZwc)" class="am_leczcr"/><path fill="url(#iiH4C6b)" class="am_leczcr"/><path clip-rule="evenodd" class="kk_3itzve"/><path fill="url(#i0KzLAV)" clip-rule="evenodd" class="bnzw6db8d"/><path fill="url(#i6baVWc)" clip-rule="evenodd" class="bnzw6db8d"/><path fill="url(#iD75oGe)" clip-rule="evenodd" class="bnzw6db8d"/><path clip-rule="evenodd" class="n3taf0bpp"/><path fill="url(#idNjHfd)" clip-rule="evenodd" class="ffk74mcdz"/><path fill="url(#iNSZeud)" clip-rule="evenodd" class="ffk74mcdz"/><path fill="url(#izxBksx)" clip-rule="evenodd" class="ffk74mcdz"/><path clip-rule="evenodd" class="sjgxm1b2n"/><path fill="url(#iV0cjke)" clip-rule="evenodd" class="i4nc5ubdm"/><path fill="url(#iA3HkMb)" clip-rule="evenodd" class="i4nc5ubdm"/><path fill="url(#icEqese)" clip-rule="evenodd" class="i4nc5ubdm"/><g filter="url(#i3ybiep)"><path clip-rule="evenodd" class="qckx50ztf"/><path fill="url(#i9RC0xe)" clip-rule="evenodd" class="xb9bedrcg"/><path fill="url(#iwgV4id)" clip-rule="evenodd" class="xb9bedrcg"/><path fill="url(#iYEV2Ib)" clip-rule="evenodd" class="xb9bedrcg"/></g><g filter="url(#iVos8Jb)"><path class="see570bma"/><path fill="url(#iCBVyCd)" class="puuq5tbqx"/><path fill="url(#iINPiRC)" class="puuq5tbqx"/><path fill="url(#iZX2SIb)" class="puuq5tbqx"/></g><path fill="url(#id5WUfd)" class="zxu2ysp1r"/><path fill="url(#i4YUGQe)" class="zxu2ysp1r"/><g filter="url(#idFHJ8G)"><path fill="url(#iAqGPVc)" class="rmvpd4mhh"/><path fill="url(#itzcXdb)" class="rmvpd4mhh"/><path fill="url(#iVVJc3d)" class="rmvpd4mhh"/><path fill="url(#ijXaCKc)" class="rmvpd4mhh"/></g><g filter="url(#iqRqDce)"><path stroke="url(#iIsrzEb)" class="pmufndiyn"/></g><g filter="url(#iZkDU0c)"><path fill="url(#iRwyS6b)" class="aubp6f5sf"/></g><g filter="url(#i4aOmKc)"><path fill="url(#ilv3sed)" class="ecxp3acnm"/><path fill="url(#iKoweGd)" class="ecxp3acnm"/></g><g filter="url(#ikYUkye)"><path class="e6ku9-bfd"/><path fill="url(#ia42KEe)" class="yc1hzye0g"/></g><g filter="url(#ivRtF0y)"><path class="beedbripo"/><path fill="url(#iYAHHPc)" class="vtr03nb2t"/></g><g filter="url(#iC9tcmd)"><path fill="url(#iLwl3cU)" class="l2bvj24_f"/><path fill="url(#icNX5Lc)" class="l2bvj24_f"/><path fill="url(#ifuCOfb)" class="l2bvj24_f"/><path fill="url(#iHNhhXd)" class="l2bvj24_f"/><path fill="url(#iH9Yvsw)" class="l2bvj24_f"/><path fill="url(#iHVx8kc)" class="l2bvj24_f"/><path fill="url(#ifss99b)" class="l2bvj24_f"/><path fill="url(#ipOXlGb)" class="l2bvj24_f"/><path fill="url(#ixKtYhc)" class="l2bvj24_f"/></g><path fill="url(#iRCeZvd)" class="l2bvj24_f"/><g filter="url(#iZjMiPe)"><path class="be6ivuuiz"/></g><g filter="url(#iMlwuxc)"><path class="nmj_f4f7l"/><path fill="url(#iE0VxQe)" class="b0x3w24sy"/><path fill="url(#il0xsMd)" class="b0x3w24sy"/><path fill="url(#i6BTvmc)" class="b0x3w24sy"/><path fill="url(#ipxmsYb)" class="b0x3w24sy"/></g><path fill="url(#iZPXjJd)" class="b0x3w24sy"/><path fill="url(#iOzbs7c)" class="b0x3w24sy"/><path stroke="url(#icI76me)" class="mm2bm0bxd"/><g filter="url(#iX6NI6d)"><path class="it5lnvbxl"/></g><g filter="url(#iZGvgqd)"><path class="vr1_zb_-t"/></g><g filter="url(#ituVzug)"><path class="itugyk7_m"/></g><g filter="url(#i0YHl7d)"><path clip-rule="evenodd" class="jipz97bfm"/></g><path class="swb8accuq"/><path fill="url(#iZs9AVs)" class="hz0c1gb6j"/><path class="jriw1q9_v"/><g filter="url(#iskPa5b)"><path class="jxl_o2voh"/><path fill="url(#ioUXeXb)" class="s4qvszy4o"/></g><g filter="url(#iEVzjgb)"><path fill="url(#icAqVGb)" class="za99d-bah"/></g><path class="rc1xtba_a"/><path fill="url(#in6AVdb)" class="z6y2fcbkg"/><path class="svarm4bjn"/><g filter="url(#iPKptUp)"><path fill="url(#ivtINGs)" class="gcpzdbbkx"/></g><g filter="url(#iKRjMxb)"><ellipse transform="rotate(-27.914 9.309 12.437)" class="o_wwhum3v"/><ellipse fill="url(#iJh9jxe)" transform="rotate(-27.914 9.309 12.437)" class="yr6rbcbly"/></g><g filter="url(#i9pQdwb)"><path class="q95yh9o6h"/></g><g filter="url(#i9jgZtd)"><path class="yl-lr5bah"/></g><g filter="url(#i15eC9c)"><path class="xbmh90b2p"/><path fill="url(#i4jsSyc)" class="mbgrc7i9r"/></g><g filter="url(#i7r5Wnc)"><path class="cpzf18vba"/><path fill="url(#iQmyZoc)" class="yxiddbz_j"/><path fill="url(#ifDU07b)" class="yxiddbz_j"/></g><g filter="url(#iWeri6d)"><path stroke="url(#i7U2Ftc)" class="drh5-1y3c"/></g><g filter="url(#ioNbfHe)"><path class="lsrlnbclx"/></g><defs><radialGradient id="iE4kjLc" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 -1.213 13.573)scale(5.93134 7.40945)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iwWzBGc" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 1.643 9.743)scale(4.48495 5.89288)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iRRiWGb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 -.252 8.346)scale(2.77586 2.13147)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="i0aGyod" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 .32 7.41)scale(3.19221 2.24863)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i1A9Nfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.77265 3.3724 -4.6814 2.46071 7.934 2.937)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iTun5nb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.834 6.95)scale(2.62914 3.67419)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i83YGka" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.207 7.695)scale(2.47645 5.16443)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="io7Ciib" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6317 .90798 -1.15662 -4.62624 21.38 16.643)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="igriQTb" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.54 -2.098)scale(3.61174 2.85668)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iTKaG7d" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -114.217 49.602)scale(1.95032 3.16008)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iMgzVBd" cx="0" cy="0" r="1" gradientTransform="rotate(-128.9 17.788 9.584)scale(14.3752 17.7454)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="prklqobcj"/><stop offset="1" class="ff_veq9dp"/></radialGradient><radialGradient id="iyIEsgb" cx="0" cy="0" r="1" gradientTransform="rotate(80.311 -5.821 15.88)scale(6.49895 15.3845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="qt4ap0b2z"/><stop offset="1" class="f46_0ydpi"/></radialGradient><radialGradient id="iL6b4oc" cx="0" cy="0" r="1" gradientTransform="rotate(-120.904 18.97 8.72)scale(9.57741 4.33562)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="kptn98y8b"/><stop offset="1" class="xy2mpdbhe"/></radialGradient><radialGradient id="iqyQthe" cx="0" cy="0" r="1" gradientTransform="matrix(3.28953 3.6097 -4.23027 3.85506 10.875 20.349)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zwfwru8ot"/><stop offset=".826" class="o-add4pxu"/></radialGradient><radialGradient id="iyIVSxb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14487 1.17029 -.21646 -.21176 24.027 13.1)" gradientUnits="userSpaceOnUse"><stop class="o3zst353r"/><stop offset="1" class="yk_3_lmdp"/></radialGradient><radialGradient id="i69MZwc" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.37 -8.64)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="ax61zhbvm"/><stop offset="1" class="tw5b7-bqr"/></radialGradient><radialGradient id="iiH4C6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.10937 .79688 -1.21512 -.16677 23.927 14.657)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="ns2xpk6fj"/><stop offset="1" class="y_oq21bme"/></radialGradient><radialGradient id="i0KzLAV" cx="0" cy="0" r="1" gradientTransform="matrix(-.69262 .16923 -.21445 -.87773 29.73 14.163)" gradientUnits="userSpaceOnUse"><stop class="r-1zse6uu"/><stop offset="1" class="ib8qs4a_l"/></radialGradient><radialGradient id="iD75oGe" cx="0" cy="0" r="1" gradientTransform="rotate(82.145 5.871 22.42)scale(.37067 3.64537)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="hcgd5kb7l"/><stop offset="1" class="cf_38xbde"/></radialGradient><radialGradient id="idNjHfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68924 .16508 -.20552 -.85808 30.307 14.474)" gradientUnits="userSpaceOnUse"><stop class="r-1zse6uu"/><stop offset="1" class="ib8qs4a_l"/></radialGradient><radialGradient id="izxBksx" cx="0" cy="0" r="1" gradientTransform="matrix(.05214 .36215 -3.63059 .52268 27.866 13.807)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="hcgd5kb7l"/><stop offset="1" class="cf_38xbde"/></radialGradient><radialGradient id="iV0cjke" cx="0" cy="0" r="1" gradientTransform="matrix(-.69149 .15913 -.19118 -.83072 30.026 14.936)" gradientUnits="userSpaceOnUse"><stop class="r-1zse6uu"/><stop offset="1" class="ib8qs4a_l"/></radialGradient><radialGradient id="icEqese" cx="0" cy="0" r="1" gradientTransform="matrix(.0523 .34914 -3.63628 .54474 27.577 14.292)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="hcgd5kb7l"/><stop offset="1" class="cf_38xbde"/></radialGradient><radialGradient id="i9RC0xe" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.888 9.192)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iwgV4id" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.885 23.49)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iCBVyCd" cx="0" cy="0" r="1" gradientTransform="rotate(173.822 14.229 8.66)scale(.96972 .53174)" gradientUnits="userSpaceOnUse"><stop class="k8893l_5s"/><stop offset="1" class="dagxnpbxc"/></radialGradient><radialGradient id="iINPiRC" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.885 23.49)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="tc83oubxb"/><stop offset="1" class="jc2cbvyjw"/></radialGradient><radialGradient id="iZX2SIb" cx="0" cy="0" r="1" gradientTransform="matrix(.92109 -.74564 1.75363 2.16625 21.894 16.899)" gradientUnits="userSpaceOnUse"><stop class="mcx49tb9t"/><stop offset="1" class="evh57dbtz"/></radialGradient><radialGradient id="id5WUfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05458 -3.66708 0 24.195 17.387)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="sipuclb6i"/><stop offset="1" class="su4gzg9-j"/></radialGradient><radialGradient id="iVVJc3d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 0 0 -.57813 24.812 19.227)" gradientUnits="userSpaceOnUse"><stop class="ow11_7b9u"/><stop offset="1" class="n-9oslbsi"/></radialGradient><radialGradient id="ilv3sed" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 40.92 -33.869)scale(3.52633 4.30549)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iKoweGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.697 .95119 -.26892 .47977 19.012 11.163)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="ia42KEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.94738 -.14486 .11324 1.52231 18.137 13.476)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iYAHHPc" cx="0" cy="0" r="1" gradientTransform="rotate(-180 3.27 6.665)scale(1.36193)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iLwl3cU" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.694 8.092)scale(9.23686 12.3634)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="icNX5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 6.063 8.448)scale(3.07222 2.13944)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="ifuCOfb" cx="0" cy="0" r="1" gradientTransform="matrix(1.66268 -5.0666 6.42858 2.10963 9.684 21.03)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iHNhhXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65695 9.50957 -11.8868 -2.07116 13.793 12.1)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ermiffb8a"/><stop offset="1" class="d5lrpr21j"/></radialGradient><radialGradient id="iH9Yvsw" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.08507 -8.12837 0 12.135 13.14)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="plx9t1yez"/><stop offset="1" class="tcn1mccqj"/></radialGradient><radialGradient id="iHVx8kc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 6.681 8.155)scale(9.07646 15.6269)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="ifss99b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.48421 1.82152 0 15.441 12.098)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="ipOXlGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69281 1.94008 0 9.795 11.803)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ixKtYhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12229 4.1617 -3.33004 -.89802 14.257 9.11)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iRCeZvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65769 0 0 -8.31317 19.045 14.016)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iE0VxQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.58754 -2.63626 .81247 -.18107 13.485 14.954)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ipxmsYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00523 0 0 -.28103 13.175 15.227)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iOzbs7c" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 4.237 9.24)scale(2.14519 2.57818)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="iZs9AVs" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04639 -1.66441 0 15.287 12.56)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ioUXeXb" cx="0" cy="0" r="1" gradientTransform="matrix(-.29911 -.38545 .53068 -.41181 14.993 12.67)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="in6AVdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0464 -1.66442 0 9.659 12.56)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iJh9jxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00998 -.63721 .76596 -.012 9.29 12.843)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4jsSyc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 10.242 .881)scale(3.90883 1.99966)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iQmyZoc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 6.491 6.25)scale(6.28482 10.2753)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ifDU07b" cx="0" cy="0" r="1" gradientTransform="matrix(-.27128 1.76334 -3.79374 -.58365 12.744 3.586)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="i4iLdbe" width="19.62" height="20.12" x="2.788" y="1.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="i3ybiep" width="7.879" height="3.847" x="21.349" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="iVos8Jb" width="7.879" height="3.847" x="21.349" y="13.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.286275 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="idFHJ8G" width="6.491" height="11.844" x="20.207" y="18.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="iqRqDce" width="5.722" height="1.374" x="23.292" y="15.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".125"/></filter><filter id="iZkDU0c" width="4.301" height="4.151" x="4.354" y="11.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="i4aOmKc" width="4.151" height="4.401" x="16.623" y="11.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="ikYUkye" width="3.771" height="3.771" x="16.814" y="11.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".25"/></filter><filter id="ivRtF0y" width="3.271" height="3.271" x="4.819" y="11.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".125"/></filter><filter id="iC9tcmd" width="13.144" height="14.428" x="5.901" y="7.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="iZjMiPe" width="3.421" height="4.459" x="10.553" y="12.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".25"/></filter><filter id="iMlwuxc" width="2.921" height="3.959" x="11.012" y="12.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".125"/></filter><filter id="iX6NI6d" width="3.813" height="1.658" x="13.746" y="11.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="iZGvgqd" width="3.813" height="1.658" x="7.387" y="11.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="ituVzug" width="3.106" height="1.349" x="7.561" y="9.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="i0YHl7d" width="3.106" height="1.349" x="14.548" y="9.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/></filter><filter id="iskPa5b" width=".957" height=".84" x="14.369" y="12.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".05"/></filter><filter id="iEVzjgb" width="1.034" height="1.062" x="15.482" y="12.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".1"/></filter><filter id="iPKptUp" width="1.156" height="1.226" x="9.751" y="12.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".1"/></filter><filter id="iKRjMxb" width="1.12" height=".851" x="8.749" y="12.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".05"/></filter><filter id="i9pQdwb" width="3.342" height="1.687" x="14.374" y="9.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".2"/></filter><filter id="i9jgZtd" width="3.342" height="1.687" x="7.343" y="9.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".2"/></filter><filter id="i15eC9c" width="5.3" height="5.689" x="4.393" y="4.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/><feGaussianBlur result="effect2_foregroundBlur_4002_3793" stdDeviation=".2"/></filter><filter id="i7r5Wnc" width="11.148" height="7.313" x="8.471" y="2.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3793"/><feGaussianBlur result="effect2_foregroundBlur_4002_3793" stdDeviation=".125"/></filter><filter id="iWeri6d" width="1.303" height="2.805" x="8.444" y="4.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".1"/></filter><filter id="ioNbfHe" width="8.355" height="4.414" x="11.69" y="5.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3793" stdDeviation=".5"/></filter><linearGradient id="iWentAe" x1="18.526" x2="9.749" y1="4.364" y2="20.62" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="i4nhBEc" x1="12.473" x2="12.473" y1="30.602" y2="25.696" gradientUnits="userSpaceOnUse"><stop class="actv8ccua"/><stop offset="1" class="g60esfuqb"/></linearGradient><linearGradient id="i9VU1Ne" x1="12.442" x2="12.442" y1="20.641" y2="21.875" gradientUnits="userSpaceOnUse"><stop class="cf8k-ab2e"/><stop offset="1" class="kle1b9b2e"/></linearGradient><linearGradient id="i6baVWc" x1="27.732" x2="27.599" y1="15.711" y2="14.454" gradientUnits="userSpaceOnUse"><stop offset=".217" class="rnkxh8b0f"/><stop offset="1" class="vsq2kybkm"/></linearGradient><linearGradient id="iNSZeud" x1="28.319" x2="28.193" y1="15.984" y2="14.758" gradientUnits="userSpaceOnUse"><stop offset=".217" class="rnkxh8b0f"/><stop offset="1" class="vsq2kybkm"/></linearGradient><linearGradient id="iA3HkMb" x1="28.032" x2="27.914" y1="16.39" y2="15.208" gradientUnits="userSpaceOnUse"><stop offset=".217" class="rnkxh8b0f"/><stop offset="1" class="vsq2kybkm"/></linearGradient><linearGradient id="iYEV2Ib" x1="24.679" x2="26.273" y1="16.84" y2="16.528" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="i4YUGQe" x1="23.574" x2="23.574" y1="18.339" y2="18.164" gradientUnits="userSpaceOnUse"><stop offset=".316" class="gublzhv6p"/><stop offset="1" class="crzqbdcxn"/></linearGradient><linearGradient id="iAqGPVc" x1="24.445" x2="24.445" y1="19.403" y2="38.715" gradientUnits="userSpaceOnUse"><stop class="eh67o3baq"/><stop offset=".621" class="fhdfn3b2i"/></linearGradient><linearGradient id="itzcXdb" x1="27.859" x2="22.432" y1="28.93" y2="28.93" gradientUnits="userSpaceOnUse"><stop class="p82q4v34p"/><stop offset=".458" class="aw40h5l5c"/><stop offset="1" class="p82q4v34p"/></linearGradient><linearGradient id="ijXaCKc" x1="23.403" x2="23.403" y1="18.243" y2="19.278" gradientUnits="userSpaceOnUse"><stop offset=".366" class="kj63bk6ym"/><stop offset="1" class="weadzoqrn"/></linearGradient><linearGradient id="iIsrzEb" x1="28.294" x2="23.473" y1="15.74" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="qrm8h702x"/><stop offset="1" class="g7kay-2kl"/></linearGradient><linearGradient id="iRwyS6b" x1="4.42" x2="6.02" y1="13.443" y2="13.443" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="il0xsMd" x1="11.262" x2="12.473" y1="15.048" y2="15.048" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="i6BTvmc" x1="12.473" x2="12.473" y1="16.078" y2="15.291" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iZPXjJd" x1="12.574" x2="12.574" y1="16.044" y2="15.865" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="icI76me" x1="11.1" x2="11.695" y1="17.896" y2="16.978" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="icAqVGb" x1="16.291" x2="15.886" y1="12.63" y2="12.88" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivtINGs" x1="10.618" x2="10.213" y1="12.63" y2="12.88" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7U2Ftc" x1="8.744" x2="9.447" y1="5.337" y2="6.979" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-tipping-hand-medium-dark" /></template>
<style>
.actv8ccua {
  stop-color: var(--svg-color--9069d4, #9069D4);
}

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.am_leczcr {
  d: path("M22.121 13.876c-.554.649-.74 1.417-.761 1.758l1.847-.101l.887-1.184c.29-.383.54-1.02-.035-1.442c-.466-.342-.946-.066-1.102.106a28 28 0 0 0-.836.863");
}

.aubp6f5sf {
  d: path("M6.43 15.406a2.075 2.075 0 1 0 0-4.15a2.075 2.075 0 0 0 0 4.15");
}

.aw40h5l5c {
  stop-color: var(--svg-color--9f77e5, #9F77E5);
}

.ax61zhbvm {
  stop-color: var(--svg-color--6c4a3e, #6C4A3E);
  stop-opacity: 0;
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b0x3w24sy {
  d: path("m11.98 12.865l-.686 2.192a.696.696 0 0 0 .672.902h1.014a.698.698 0 0 0 .672-.902l-.686-2.192c-.147-.486-.832-.486-.986 0");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.be6ivuuiz {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m11.967 13.044l-.882 2.192a.695.695 0 0 0 .672.902h1.014a.698.698 0 0 0 .671-.902l-.685-2.193c-.147-.485-.636-.485-.79 0");
}

.beedbripo {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M6.455 14.716a1.385 1.385 0 1 0 0-2.77a1.385 1.385 0 0 0 0 2.77");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bnzw6db8d {
  fill-rule: evenodd;
  d: path("M29.716 14.182a.85.85 0 0 1-.69.984q-.222.04-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.317-.38q.39-.082.716-.142a.85.85 0 0 1 .985.69");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c-m0h9unw {
  width: 4.898px;
  height: 6.68px;
  x: 10.035px;
  y: 17.009px;
  rx: 2.449px;
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cf_38xbde {
  stop-color: var(--svg-color--8e6f62, #8E6F62);
  stop-opacity: 0;
}

.cf8k-ab2e {
  stop-color: var(--svg-color--693744, #693744);
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

.cpzf18vba {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M11.695 3.283C10.234 2.96 8.922 4.418 8.77 4.958c1.356 4.572 4.789 4.322 8.177 3.945c2.028-.225 2.248.7 2.421 1.146c0-5.072-4.313-6.024-7.637-6.758z");
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.crzqbdcxn {
  stop-color: var(--svg-color--533b7c, #533B7C);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d5lrpr21j {
  stop-color: var(--svg-color--793e68, #793E68);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dagxnpbxc {
  stop-color: var(--svg-color--99786f, #99786F);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.drh5-1y3c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.744 4.893c.03.314.303 1.492.703 2.205");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6ku9-bfd {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M18.699 14.716a1.385 1.385 0 1 0 0-2.77a1.385 1.385 0 0 0 0 2.77");
}

.ecxp3acnm {
  d: path("M18.699 15.406a2.075 2.075 0 1 0 0-4.15a2.075 2.075 0 0 0 0 4.15");
}

.eh67o3baq {
  stop-color: var(--svg-color--8860cb, #8860CB);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ermiffb8a {
  stop-color: var(--svg-color--793e68, #793E68);
  stop-opacity: 0;
}

.evh57dbtz {
  stop-color: var(--svg-color--825b55, #825B55);
  stop-opacity: 0;
}

.f46_0ydpi {
  stop-color: var(--svg-color--8460bf, #8460BF);
  stop-opacity: 0;
}

.ff_veq9dp {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
  stop-opacity: 0;
}

.ffk74mcdz {
  fill-rule: evenodd;
  d: path("M30.294 14.51a.85.85 0 0 1-.689.985q-.18.031-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.085a.85.85 0 0 1 .984.69");
}

.fhdfn3b2i {
  stop-color: var(--svg-color--8560c7, #8560C7);
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

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g60esfuqb {
  stop-color: var(--svg-color--8d66ce, #8D66CE);
}

.g7kay-2kl {
  stop-color: var(--svg-color--9b7b71, #9B7B71);
  stop-opacity: 0;
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gcpzdbbkx {
  d: path("M10.708 12.961c0-.372-.303-.62-.385-.695l-.372.36l.23.466z");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gublzhv6p {
  stop-color: var(--svg-color--533b7c, #533B7C);
}

.hcgd5kb7l {
  stop-color: var(--svg-color--8e6f62, #8E6F62);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hz0c1gb6j {
  d: path("M15.29 11.946a1.15 1.15 0 0 1 1.109 1.454h-2.224a1.156 1.156 0 0 1 1.114-1.455");
}

.i4nc5ubdm {
  fill-rule: evenodd;
  d: path("M30.023 15.067a.85.85 0 0 1-.773.922a26 26 0 0 0-1.26.161l-.03.005c-.525.074-1.133.16-1.787.23a.85.85 0 0 1-.182-1.69a50 50 0 0 0 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.ib8qs4a_l {
  stop-color: var(--svg-color--9b7b70, #9B7B70);
  stop-opacity: 0;
}

.it5lnvbxl {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M13.946 12.597c.342-.602.863-1.078 1.983-1.078c.49 0 .963.136 1.383.476c.347.28.3.638.032.773l-.717.41c-.84-.273-1.77-.31-2.681-.581");
}

.itugyk7_m {
  fill: var(--svg-color--352827, #352827);
  d: path("m8.09 11.038l-.005.003a.346.346 0 0 1-.355-.593l.002-.002l.003-.002l.013-.007l.041-.023q.054-.03.15-.076c.127-.06.308-.138.529-.208c.438-.14 1.051-.258 1.713-.141a.346.346 0 1 1-.12.681c-.514-.09-1.008 0-1.383.119a3.5 3.5 0 0 0-.56.233z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jc2cbvyjw {
  stop-color: var(--svg-color--886658, #886658);
  stop-opacity: 0;
}

.jipz97bfm {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m17.286 10.448l-.178.296za.346.346 0 0 1-.355.593l-.007-.003l-.028-.016l-.117-.06a4 4 0 0 0-.442-.173c-.374-.12-.868-.21-1.383-.119a.346.346 0 0 1-.12-.681c.662-.117 1.275 0 1.713.14a4.3 4.3 0 0 1 .72.308l.013.007l.004.002z");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jriw1q9_v {
  fill: var(--svg-color--000, #000);
  d: path("M14.63 13.097c0-.367.294-.66.66-.66a.656.656 0 0 1 .586.963h-1.167a.6.6 0 0 1-.078-.303");
}

.jxl_o2voh {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.205 12.189c.082.11-.09.243-.284.389c-.195.146-.34.248-.422.139c-.082-.11.01-.317.205-.463s.42-.175.501-.065");
}

.k8893l_5s {
  stop-color: var(--svg-color--99786f, #99786F);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kj63bk6ym {
  stop-color: var(--svg-color--8d67cd, #8D67CD);
}

.kk_3itzve {
  fill: var(--svg-color--7d5447, #7D5447);
  fill-rule: evenodd;
  d: path("M29.716 14.182a.85.85 0 0 1-.69.984q-.222.04-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.693c.909-.086 1.678-.246 2.317-.38q.39-.082.716-.142a.85.85 0 0 1 .985.69");
}

.kle1b9b2e {
  stop-color: var(--svg-color--693744, #693744);
  stop-opacity: 0;
}

.kptn98y8b {
  stop-color: var(--svg-color--613ea5, #613EA5);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l2bvj24_f {
  d: path("M5.912 11.702h.016l-.014-.342l-.013-.395c.027-1.223.74-1.697 1.045-1.855l.066-.026q.035-.016.066-.027a2.97 2.97 0 0 0 1.534-1.592l.106-.25a.34.34 0 0 1 .595-.066a4.98 4.98 0 0 0 4.114 2.158h4.153c.232 0 1.396.113 1.465 1.718l-.153 3.964c-.16 3.614-2.982 6.041-6.427 6.041c-3.446 0-6.269-2.427-6.428-6.041z");
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

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lsrlnbclx {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m15.577 7.938l-1.839.339a.888.888 0 1 1-.161-1.76h3.019c1.785 0 2.376 1.799 2.449 2.414a4.06 4.06 0 0 0-3.469-.993");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbgrc7i9r {
  d: path("M5.935 5.607c.73-.773 2.11-.774 2.748-.658l.51 1.664c-.325-.05-.616.065-.86.303c-.579 1.625-2.566 2.522-3.488 2.767c-.191-1.924.14-3.07 1.09-4.076");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcx49tb9t {
  stop-color: var(--svg-color--825b55, #825B55);
}

.mm2bm0bxd {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.663 16.597a3.86 3.86 0 0 0 1.81.439c.67 0 1.287-.16 1.81-.439a.25.25 0 0 1 .302.05a.24.24 0 0 1 .025.305l-.042-.028a2.492 2.492 0 0 1-4.19 0zm0 0a.25.25 0 0 0-.302.053a.24.24 0 0 0-.025.302z");
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

.n-9oslbsi {
  stop-color: var(--svg-color--a681e6, #A681E6);
  stop-opacity: 0;
}

.n3taf0bpp {
  fill: var(--svg-color--7d5447, #7D5447);
  fill-rule: evenodd;
  d: path("M30.294 14.51a.85.85 0 0 1-.689.985q-.18.031-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383l.459-.085a.85.85 0 0 1 .984.69");
}

.nh8uxd9yq {
  d: path("M12.473 20.036c-5.523 0-10 4.477-10 10v.051h20v-.05c0-5.523-4.477-10-10-10");
}

.nmj_f4f7l {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m11.98 12.865l-.686 2.192a.696.696 0 0 0 .672.902h1.014a.698.698 0 0 0 .672-.902l-.686-2.192c-.147-.486-.832-.486-.986 0");
}

.ns2xpk6fj {
  stop-color: var(--svg-color--917568, #917568);
}

.o_wwhum3v {
  cx: 9.309px;
  cy: 12.437px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.502px;
  ry: 0.254px;
}

.o-add4pxu {
  stop-color: var(--svg-color--805558, #805558);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o3zst353r {
  stop-color: var(--svg-color--927568, #927568);
}

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
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

.ow11_7b9u {
  stop-color: var(--svg-color--a681e6, #A681E6);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p82q4v34p {
  stop-color: var(--svg-color--9f77e5, #9F77E5);
  stop-opacity: 0;
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plx9t1yez {
  stop-color: var(--svg-color--885485, #885485);
  stop-opacity: 0;
}

.pmufndiyn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.667 16.363c.85-.057 3.032-.263 4.973-.623");
}

.prklqobcj {
  stop-color: var(--svg-color--8e6bd1, #8E6BD1);
}

.puuq5tbqx {
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.873-.095 1.181-.192c.243-.076.5-.218.96-.305c.917-.103 1.759-.207 2.234-.31a.825.825 0 1 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.q95yh9o6h {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.975 10.27c.415-.1 1.45-.05 2.141.445");
}

.qckx50ztf {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.247c.917-.103 1.759-.207 2.234-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.qrm8h702x {
  stop-color: var(--svg-color--9b7b71, #9B7B71);
}

.qt4ap0b2z {
  stop-color: var(--svg-color--503876, #503876);
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

.r-1zse6uu {
  stop-color: var(--svg-color--9b7b70, #9B7B70);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rc1xtba_a {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.39 11.595a1.8 1.8 0 0 0-1.748 1.365a.354.354 0 0 0 .345.44h2.878c.183 0 .33-.168.293-.35a1.81 1.81 0 0 0-1.769-1.455");
}

.rmvpd4mhh {
  d: path("M20.207 19.043a.8.8 0 0 1 .8-.8h4.79a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.rnkxh8b0f {
  stop-color: var(--svg-color--7d4b55, #7D4B55);
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.s4qvszy4o {
  d: path("M15.205 12.189c.082.11-.09.243-.284.389c-.195.146-.34.248-.422.139c-.082-.11.01-.317.205-.463s.42-.175.501-.065");
}

.see570bma {
  fill: var(--svg-color--7d5447, #7D5447);
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.832 1.954c.593-.067.873-.095 1.181-.192c.243-.076.5-.218.96-.305c.917-.103 1.759-.207 2.234-.31a.825.825 0 1 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sipuclb6i {
  stop-color: var(--svg-color--7c65a2, #7C65A2);
}

.sjgxm1b2n {
  fill: var(--svg-color--7d5447, #7D5447);
  fill-rule: evenodd;
  d: path("M30.023 15.067a.85.85 0 0 1-.773.922a26 26 0 0 0-1.26.161l-.03.005c-.525.074-1.133.16-1.787.23a.85.85 0 0 1-.182-1.69a50 50 0 0 0 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.su4gzg9-j {
  stop-color: var(--svg-color--604789, #604789);
}

.svarm4bjn {
  fill: var(--svg-color--000, #000);
  d: path("M10.315 13.097a.656.656 0 0 0-.659-.66a.656.656 0 0 0-.586.963h1.167a.65.65 0 0 0 .078-.303");
}

.swb8accuq {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.557 11.595a1.8 1.8 0 0 1 1.747 1.365a.353.353 0 0 1-.345.44H14.08a.297.297 0 0 1-.293-.35a1.8 1.8 0 0 1 1.769-1.455");
}

.sytdg2lon {
  fill: var(--svg-color--814f54, #814F54);
  d: path("M21.349 15.79h4.015v2.016h-4.015z");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tc83oubxb {
  stop-color: var(--svg-color--886658, #886658);
}

.tcn1mccqj {
  stop-color: var(--svg-color--885485, #885485);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tw5b7-bqr {
  stop-color: var(--svg-color--6c4a3e, #6C4A3E);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up54513se {
  fill-rule: evenodd;
  d: path("M21.74 15.149a4.2 4.2 0 0 0 .418-1.84c0-.603-.124-1.169-.347-1.684h.007a4 4 0 0 0-.363-.662l-.002-.004a4.2 4.2 0 0 1-.679-2.284v-.013a4.256 4.256 0 0 0-4.255-4.255a.7.7 0 0 1-.587-.3a4.26 4.26 0 0 0-3.46-1.775a4.26 4.26 0 0 0-3.458 1.775a.73.73 0 0 1-.587.3l-.11.001a4.256 4.256 0 0 0-4.145 4.254v.013c0 .81-.235 1.605-.68 2.284l-.002.005a4.26 4.26 0 0 0-.284 4.185a.66.66 0 0 1 0 .587a4.2 4.2 0 0 0-.418 1.815a4.144 4.144 0 0 0 4.15 4.15h11.07a4.144 4.144 0 0 0 4.15-4.15c0-.653-.157-1.266-.418-1.815a.66.66 0 0 1 0-.587M5.928 11.702h-.016l1.546 3.038c.159 3.615 1.57 0 5.015 0s4.948 4.024 5.107.409l1.465-4.123c-.07-1.606-1.233-1.719-1.465-1.719h-4.153A4.98 4.98 0 0 1 9.313 7.15a.34.34 0 0 0-.595.066l-.106.25a2.97 2.97 0 0 1-1.6 1.619q-.035.016-.066.026c-.304.158-1.018.632-1.045 1.855l.013.395z");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vr1_zb_-t {
  fill: var(--svg-color--272528, #272528);
  d: path("M11 12.597c-.342-.602-.863-1.078-1.983-1.078c-.49 0-.963.136-1.383.476c-.347.28-.3.638-.032.773l.717.41c.84-.273 1.77-.31 2.681-.581");
}

.vsq2kybkm {
  stop-color: var(--svg-color--7d4b55, #7D4B55);
  stop-opacity: 0;
}

.vtr03nb2t {
  d: path("M6.455 14.716a1.385 1.385 0 1 0 0-2.77a1.385 1.385 0 0 0 0 2.77");
}

.weadzoqrn {
  stop-color: var(--svg-color--8d67cd, #8D67CD);
  stop-opacity: 0;
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.xb9bedrcg {
  fill-rule: evenodd;
  d: path("M25.66 14.017c-.328.036-.77.085-1.597.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.247c.917-.103 1.759-.207 2.234-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.493.05");
}

.xbmh90b2p {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M5.935 5.607c.73-.773 2.11-.774 2.748-.658l.51 1.664c-.325-.05-.616.065-.86.303c-.579 1.625-2.566 2.522-3.488 2.767c-.191-1.924.14-3.07 1.09-4.076");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xy2mpdbhe {
  stop-color: var(--svg-color--6c4da8, #6C4DA8);
  stop-opacity: 0;
}

.y_oq21bme {
  stop-color: var(--svg-color--917568, #917568);
  stop-opacity: 0;
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.yc1hzye0g {
  d: path("M18.699 14.716a1.385 1.385 0 1 0 0-2.77a1.385 1.385 0 0 0 0 2.77");
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yk_3_lmdp {
  stop-color: var(--svg-color--7c5a4c, #7C5A4C);
}

.yl-lr5bah {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.085 10.27c-.416-.1-1.45-.05-2.142.445");
}

.yr6rbcbly {
  cx: 9.309px;
  cy: 12.437px;
  rx: 0.502px;
  ry: 0.254px;
}

.yxiddbz_j {
  d: path("M11.695 3.283C10.234 2.96 8.922 4.418 8.77 4.958c1.356 4.572 4.789 4.322 8.177 3.945c2.028-.225 2.248.7 2.421 1.146c0-5.072-4.313-6.024-7.637-6.758z");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z6y2fcbkg {
  d: path("M9.656 11.945a1.15 1.15 0 0 0-1.11 1.455h2.225q.04-.149.041-.303a1.16 1.16 0 0 0-1.156-1.152");
}

.za99d-bah {
  d: path("M16.315 12.945a1.1 1.1 0 0 0-.298-.597l-.335.368l.15.294z");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zwfwru8ot {
  stop-color: var(--svg-color--6c4046, #6C4046);
}

.zxu2ysp1r {
  d: path("M21.106 17.548a.25.25 0 0 1 .25-.25h4.093a.25.25 0 0 1 .25.25v1.64h-4.593z");
}

</style>
