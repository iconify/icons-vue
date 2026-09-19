<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iQwTgcd)"><path fill="url(#iaUsmrb)" class="f1jw_ab3w"/><path fill="url(#iTDnx1x)" class="f1jw_ab3w"/></g><path class="b_qv5du4s"/><path fill="url(#i6KAjab)" class="faisxaclj"/><path fill="url(#i2gSgbe)" class="faisxaclj"/><path fill="url(#idcBZkt)" class="faisxaclj"/><path fill="url(#iiLw8Vb)" class="faisxaclj"/><path fill="url(#iAIO9Yd)" class="faisxaclj"/><path fill="url(#isZrtzc)" class="faisxaclj"/><path fill="url(#iJkm9gA)" class="d_-1b_bzw"/><path fill="url(#ih3vBxb)" class="d_-1b_bzw"/><path fill="url(#iov0n7a)" class="d_-1b_bzw"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#i4dn0Mr)" class="vylrb5bvm"/><path fill="url(#iWkx0Sd)" class="ix8bgh62p"/><g filter="url(#iuUm22E)"><path fill="url(#ibgFUYd)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iYgYbde)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iSuBe6b)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iak8rNL)" clip-rule="evenodd" class="zdsg9r3jo"/></g><path fill="url(#iU4Plhc)" class="v-7fbqiwn"/><path fill="url(#ifQNUod)" class="v-7fbqiwn"/><g filter="url(#iw7Y9eM)"><path fill="url(#icL13gd)" class="v-7fbqiwn"/><path fill="url(#i1P7Cub)" class="v-7fbqiwn"/></g><g filter="url(#ipn9lhd)"><circle fill="url(#ihpO77c)" class="jbixgesah"/></g><g filter="url(#iw6m88d)"><circle fill="url(#iJJLXUc)" class="l3kcz_nzf"/></g><g filter="url(#iTrkUCd)"><circle fill="url(#iE0FGBe)" class="uvhdvfbmh"/><circle fill="url(#iKqSGBe)" class="uvhdvfbmh"/></g><g filter="url(#iJyEAfe)"><circle class="rjs32bbuf"/><circle fill="url(#i7gCUDe)" class="tvi46ubab"/><circle fill="url(#iLNifTq)" class="tvi46ubab"/></g><g filter="url(#i96oHme)"><path fill="url(#iOaNRLs)" class="doeo988yi"/><path fill="url(#imUbCle)" class="doeo988yi"/></g><path fill="url(#izKlsRd)" class="doeo988yi"/><path fill="url(#iIUQbrb)" class="doeo988yi"/><path fill="url(#i9O6Phd)" class="doeo988yi"/><path fill="url(#idFhqPt)" class="doeo988yi"/><g filter="url(#i3yxFSb)"><path class="ivivk9iqw"/></g><g filter="url(#in5cBoT)"><path class="e5yed958z"/><path fill="url(#iTHjMBe)" class="m_elr2b5x"/><path fill="url(#iN3vr9A)" class="m_elr2b5x"/><path fill="url(#iQQp4Wy)" class="m_elr2b5x"/><path fill="url(#i8FhJCe)" class="m_elr2b5x"/></g><path stroke="url(#iPkfzMd)" class="se4g5bczs"/><g filter="url(#i2odJUb)"><path class="bl75b1bnm"/><path fill="url(#iobw5kd)" class="xm1do5bfv"/></g><g filter="url(#izCSV1d)"><path class="to5wyljfl"/><path fill="url(#inTRi8c)" class="bznzecbwh"/></g><path class="rveytubia"/><path fill="url(#iFnxCHe)" class="g3fj60b8y"/><path class="dr3hwgbeb"/><g filter="url(#izAqRNe)"><path class="ml6mrxhys"/><path fill="url(#iTGmnvJ)" class="bm7maubtm"/></g><g filter="url(#iQNfTUc)"><path fill="url(#ij1JdQc)" class="ssb7y629c"/></g><path class="sbdphpbog"/><path fill="url(#iuEIRrc)" class="qkcxz_bcq"/><path class="gcbgjmd6q"/><g filter="url(#isjhD6b)"><path fill="url(#il2j6Ac)" class="m_t8iw6rg"/></g><g filter="url(#izbfMAc)"><ellipse transform="rotate(-27.914 11.987 10.023)" class="xweobbcdr"/><ellipse fill="url(#i3XHD5d)" transform="rotate(-27.914 11.987 10.023)" class="hzlw7-kex"/></g><path fill="url(#iHZvJfc)" class="hgn0v4h0b"/><path fill="url(#ilxTFMd)" class="hgn0v4h0b"/><path fill="url(#izHz1gd)" class="hgn0v4h0b"/><path fill="url(#iFF74De)" class="hgn0v4h0b"/><path fill="url(#ia6hdgb)" class="hgn0v4h0b"/><path class="d6l_zva3n"/><path fill="url(#inGX0Oc)" class="u_wc6ubhb"/><path fill="url(#iiH6veK)" class="u_wc6ubhb"/><path fill="url(#iI4mEsd)" class="u_wc6ubhb"/><path fill="url(#iN2yeVc)" class="u_wc6ubhb"/><path fill="url(#i1i1Lbq)" class="m94o2m2wq"/><path fill="url(#izpcbVd)" class="m94o2m2wq"/><path fill="url(#iZ6eZGb)" class="m94o2m2wq"/><path fill="url(#ibPujte)" class="m94o2m2wq"/><path fill="url(#i6qz0xW)" class="m94o2m2wq"/><path fill="url(#iMEPogb)" class="w_8w8wqmn"/><path fill="url(#iutMDkb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#iZebmAe)"><path fill="url(#iKGw4kt)" class="recb7tbvt"/><path fill="url(#iyoBo3i)" class="recb7tbvt"/></g><g filter="url(#iCiVgbc)"><path fill="url(#iatOxCb)" class="n4s-q-b8n"/><path fill="url(#iQy6vPz)" class="n4s-q-b8n"/></g><path fill="url(#iqw3Vdd)" class="n4s-q-b8n"/><path fill="url(#iZmNjZb)" class="n4s-q-b8n"/><g filter="url(#ioSFeEc)"><path fill="url(#i5b1ojc)" class="rys9ifzwf"/><path fill="url(#ifSfzbe)" class="rys9ifzwf"/><path fill="url(#ih6dC9c)" class="rys9ifzwf"/></g><g filter="url(#iccKiBe)"><path fill="url(#ibijqYb)" class="sqzh_k23r"/><path fill="url(#iyoK4Kd)" class="sqzh_k23r"/><path fill="url(#iJhoPse)" class="sqzh_k23r"/></g><g filter="url(#iXV3Uob)"><path fill="url(#i9kTuLc)" class="uf71gn07a"/></g><g filter="url(#iJ4ulMb)"><path stroke="url(#i2bdjSd)" class="cj_ualb6i"/></g><g filter="url(#i0d0THe)"><path class="cd1yj8bur"/></g><path fill="url(#i0RrKOF)" class="h5lc9ib4p"/><path fill="url(#iVMDejt)" class="gdgw88t-a"/><defs><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iAIO9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="iov0n7a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="i4dn0Mr" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.973)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="iYgYbde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.066)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iSuBe6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.19 16.067)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iak8rNL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -2.20052 0 13.3 16.854)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="z1374kqmn"/><stop offset="1" class="t3ca9xlms"/></radialGradient><radialGradient id="ifQNUod" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.993 16.065)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i1P7Cub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82813 -3.16462 0 14.8 16.87)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="poqt_ebqs"/><stop offset="1" class="yl696wcmm"/></radialGradient><radialGradient id="ihpO77c" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.02 10.802)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iKqSGBe" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 19.587 10.537)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="i7gCUDe" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.173 11.624)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iLNifTq" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.215 10.802)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iOaNRLs" cx="0" cy="0" r="1" gradientTransform="matrix(-6.1875 .78123 -.95905 -7.59593 17.097 11.932)" gradientUnits="userSpaceOnUse"><stop class="i04au6bby"/><stop offset="1" class="prkeaabuo"/></radialGradient><radialGradient id="imUbCle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 16.793 9.529)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="i9O6Phd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40614 -12.2237 0 14.113 9.026)" gradientUnits="userSpaceOnUse"><stop offset=".736" class="lovqddcsn"/><stop offset="1" class="k36fjzbua"/></radialGradient><radialGradient id="idFhqPt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31823 -8.125 11.19087 -1.81565 15.417 15.213)" gradientUnits="userSpaceOnUse"><stop offset=".601" class="fozpwu1wx"/><stop offset=".977" class="rjb-s4e0o"/></radialGradient><radialGradient id="i8FhJCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 14.772 12.41)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iobw5kd" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 16.89 8.613)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="inTRi8c" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 10.982 -2.663)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iFnxCHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 16.625 10.119)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iTGmnvJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 16.397 10.203)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuEIRrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 12.258 10.119)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3XHD5d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.075 -.724)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iFF74De" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.098)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iN2yeVc" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.768 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iutMDkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iQy6vPz" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.636)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iqw3Vdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.395)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iZmNjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.332)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iyoK4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.504)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="i0RrKOF" cx="0" cy="0" r="1" gradientTransform="rotate(-88.046 9.496 .427)scale(2.97829 .2991)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="o4001ccri"/><stop offset="1" class="ldoh6m8qh"/></radialGradient><radialGradient id="iVMDejt" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 -1.90641 .64964 .15441 19.878 9.879)" gradientUnits="userSpaceOnUse"><stop class="g6vlzzbhl"/><stop offset="1" class="ug2jj9grv"/></radialGradient><linearGradient id="iaUsmrb" x1="14.587" x2="14.587" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iTDnx1x" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iWkx0Sd" x1="15.654" x2="15.654" y1="15.025" y2="21.362" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ibgFUYd" x1="11.238" x2="13.128" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="ggy1amtma"/><stop offset="1" class="ctz7grpzo"/></linearGradient><linearGradient id="iU4Plhc" x1="13.277" x2="13.489" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iJJLXUc" x1="9.692" x2="9.051" y1="11.081" y2="11.081" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iE0FGBe" x1="20.302" x2="19.482" y1="9.709" y2="12.248" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="izKlsRd" x1="9.517" x2="10.883" y1="13.932" y2="13.822" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iIUQbrb" x1="19.497" x2="18.43" y1="12.994" y2="12.963" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iTHjMBe" x1="13.579" x2="14.518" y1="11.851" y2="11.851" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iN3vr9A" x1="15.384" x2="14.357" y1="12.174" y2="12.159" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iQQp4Wy" x1="14.639" x2="14.639" y1="12.917" y2="12.344" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iPkfzMd" x1="13.406" x2="13.842" y1="14.534" y2="13.846" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ij1JdQc" x1="17.404" x2="17.09" y1="10.173" y2="10.366" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="il2j6Ac" x1="13.002" x2="12.688" y1="10.173" y2="10.366" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilxTFMd" x1="10.646" x2="16.989" y1="6.723" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="iiH6veK" x1="14.592" x2="14.592" y1="30.316" y2="28.723" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iI4mEsd" x1="14.592" x2="14.592" y1="26.173" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i1i1Lbq" x1="14.582" x2="14.582" y1="6.972" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iMEPogb" x1="14.582" x2="14.582" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="iatOxCb" x1="22.021" x2="18.333" y1="16.754" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="i2bdjSd" x1="18.689" x2="20.193" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="iQwTgcd" width="17.197" height="11.9" x="5.989" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="iuUm22E" width="6.88" height="3.666" x="11.157" y="15.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="iw7Y9eM" width="4.97" height="3.828" x="13.277" y="15.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="ipn9lhd" width="3.542" height="3.342" x="8.021" y="9.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="iw6m88d" width="2.992" height="2.992" x="8.196" y="9.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".25"/></filter><filter id="iTrkUCd" width="3.592" height="3.592" x="17.543" y="8.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="iJyEAfe" width="2.992" height="2.992" x="17.718" y="9.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".25"/></filter><filter id="i96oHme" width="10.429" height="12.189" x="9.231" y="5.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="i3yxFSb" width="3.262" height="4.184" x="12.574" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".375"/></filter><filter id="in5cBoT" width="2.379" height="3.184" x="13.255" y="9.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".125"/></filter><filter id="i2odJUb" width="2.982" height="1.874" x="15.628" y="7.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="izCSV1d" width="2.982" height="1.874" x="10.475" y="7.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="izAqRNe" width=".787" height=".697" x="15.891" y="9.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".05"/></filter><filter id="iQNfTUc" width=".892" height=".914" x="16.731" y="9.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".1"/></filter><filter id="isjhD6b" width=".987" height="1.041" x="12.285" y="9.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".1"/></filter><filter id="izbfMAc" width=".914" height=".705" x="11.53" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".05"/></filter><filter id="iZebmAe" width="5.52" height="4.05" x="11.827" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2609" result="effect2_innerShadow_4002_2609"/></filter><filter id="iCiVgbc" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2609" result="effect2_innerShadow_4002_2609"/></filter><filter id="ioSFeEc" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2609" result="effect2_innerShadow_4002_2609"/></filter><filter id="iccKiBe" width="4.557" height="7.476" x="23.816" y="17.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2609"/></filter><filter id="iXV3Uob" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2609"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2609" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2609"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2609" result="effect3_innerShadow_4002_2609"/></filter><filter id="iJ4ulMb" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".125"/></filter><filter id="i0d0THe" width="2.769" height="7.081" x="18.396" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2609" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-firefighter-medium-dark" /></template>
<style>
.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.b_qv5du4s {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bl75b1bnm {
  fill: var(--svg-color--352827, #352827);
  d: path("M18.168 7.976h-.002l-.002-.002l-.004-.004l-.012-.01a2 2 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.494-.16a.534.534 0 1 0 .166 1.056c.398-.063.717.01.935.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .68-.825");
}

.bm7maubtm {
  d: path("M16.562 9.83c.063.085-.07.19-.221.302c-.151.113-.263.193-.327.108s.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.bznzecbwh {
  d: path("m10.667 7.977l.002-.002l.002-.001l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21c.36-.143.873-.257 1.494-.16a.534.534 0 0 1-.166 1.056a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.824");
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cd1yj8bur {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.629c0-.2 1.146-4.105 1.719-6.032");
}

.cj_ualb6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.546 17.972l-1.08 3.968");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctz7grpzo {
  stop-color: var(--svg-color--be2450, #BE2450);
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d_-1b_bzw {
  d: path("M7.607 29.972V17.971a10.98 10.98 0 0 0-4.02 8.501v3.5z");
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d6l_zva3n {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.deg-o6bbc {
  stop-color: var(--svg-color--f94d70, #F94D70);
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.doeo988yi {
  d: path("M9.281 8.749c0-.267-.149-1.008.066-1.169l.418.261c.268-.213.375-.534.375-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.215.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.46.545.43.961c-.125 1.74-.235 3.605-.356 5.403c-.16 1.772-1.553 3.006-3.213 3.006H12.86c-1.713 0-3.052-1.234-3.213-3.006c-.14-1.826-.367-3.578-.367-5.456");
}

.dr3hwgbeb {
  fill: var(--svg-color--000, #000);
  d: path("M16.116 10.535a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5yed958z {
  fill: var(--svg-color--7d5149, #7D5149);
  d: path("m14.062 10.516l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f1jw_ab3w {
  d: path("M22.174 7.972H7.152c-.395.32-.78 1.337-1.163 1.657v1.343c0 4.69 3.854 8.5 8.598 8.5s8.598-3.81 8.598-8.5V9.63c-.354-.42-.687-1.207-1.011-1.657");
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.faisxaclj {
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fozpwu1wx {
  stop-color: var(--svg-color--693a4b, #693A4B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g3fj60b8y {
  d: path("M16.627 9.642a.893.893 0 0 1 .861 1.128h-1.725a.897.897 0 0 1 .865-1.128");
}

.g6vlzzbhl {
  stop-color: var(--svg-color--272324, #272324);
}

.gcbgjmd6q {
  fill: var(--svg-color--000, #000);
  d: path("M12.768 10.535a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.235");
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gdgw88t-a {
  d: path("M19.358 7.972h1.148l.085.002a24 24 0 0 1-.432 1.772c-.112.356-.455.457-.601.465c.016-.32.045-1.097.045-1.553c0-.356-.13-.574-.245-.686");
}

.ggy1amtma {
  stop-color: var(--svg-color--d53260, #D53260);
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h5lc9ib4p {
  d: path("M9.566 7.972h-.908q-.16 0-.321.02c.098.497.322 1.42.428 1.754a.67.67 0 0 0 .578.469c-.016-.32-.022-1.1-.022-1.557c0-.356.13-.574.245-.686");
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hgn0v4h0b {
  d: path("M20.885 7.333H8.29v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.hzlw7-kex {
  cx: 11.987px;
  cy: 10.023px;
  rx: 0.39px;
  ry: 0.197px;
}

.i04au6bby {
  stop-color: var(--svg-color--95675a, #95675A);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.ivivk9iqw {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m14.169 10.68l-.822 1.7c-.101.35.143.7.49.7h.737c.346 0 .59-.355.489-.7l-.5-1.7c-.106-.377-.282-.377-.394 0");
}

.ix8bgh62p {
  d: path("M13.277 15.972v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.jbixgesah {
  cx: 9.692px;
  cy: 10.802px;
  r: 1.671px;
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k36fjzbua {
  stop-color: var(--svg-color--772e41, #772E41);
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
}

.kmg6h4b5x {
  stop-color: var(--svg-color--bd585d, #BD585D);
  stop-opacity: 0;
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
}

.ks1omcbjp {
  stop-color: var(--svg-color--be324c, #BE324C);
}

.ku_tac4_z {
  stop-color: var(--svg-color--c93271, #C93271);
  stop-opacity: 0;
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l3kcz_nzf {
  cx: 9.692px;
  cy: 10.802px;
  r: 0.996px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldoh6m8qh {
  stop-color: var(--svg-color--10070e, #10070E);
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lovqddcsn {
  stop-color: var(--svg-color--7b4455, #7B4455);
  stop-opacity: 0;
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m_elr2b5x {
  d: path("m14.062 10.516l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.m_t8iw6rg {
  d: path("M13.072 10.43c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m94o2m2wq {
  d: path("M8.659 7.972h11.846c.95 0 1.99.485 1.99 2.68h.69V9.347c0-1.43-.847-2.375-2.456-2.375H8.435c-1.609 0-2.456.946-2.456 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.ml6mrxhys {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.562 9.83c.063.085-.07.19-.221.302c-.151.113-.263.193-.327.108s.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n4s-q-b8n {
  d: path("m22.636 16.137l-1.38-.368a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o4001ccri {
  stop-color: var(--svg-color--362b29, #362B29);
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poqt_ebqs {
  stop-color: var(--svg-color--98072e, #98072E);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.prkeaabuo {
  stop-color: var(--svg-color--734b49, #734B49);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.qkcxz_bcq {
  d: path("M12.256 9.642a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.recb7tbvt {
  d: path("M17.247 6.972h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.rjb-s4e0o {
  stop-color: var(--svg-color--592f2f, #592F2F);
}

.rjs32bbuf {
  cx: 19.214px;
  cy: 10.802px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.rveytubia {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.834 9.37c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34H15.69a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rys9ifzwf {
  d: path("m20.012 16.732l4.416 1.16a3.57 3.57 0 0 0 2.071-.053l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.62.983 4.235s-1.732 2.765-2.98 3.034c-.084.02-.348.046-.505-.158l-.142-.14a3.5 3.5 0 0 0-1.745-1.11L18.57 22.55a.61.61 0 0 1-.43-.779l1.25-4.675c.045-.22.37-.43.622-.364");
}

.rz-l4sb2t {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
}

.rzbfz4btw {
  stop-color: var(--svg-color--b3576b, #B3576B);
  stop-opacity: 0;
}

.s2qawgbpe {
  stop-color: var(--svg-color--b78426, #B78426);
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.sbdphpbog {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.049 9.37c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272A1.4 1.4 0 0 0 12.05 9.37");
}

.se4g5bczs {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.08 13.562c.395.205.864.323 1.364.323c.505 0 .97-.118 1.363-.323h.001a.204.204 0 0 1 .241.04a.19.19 0 0 1 .021.24m-2.99-.28l2.949.253m-2.948-.253a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24m.262-.281l-.221.253m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.869a1.95 1.95 0 0 1-1.626-.869m3.21-.028a1.89 1.89 0 0 1-1.584.847c-.665 0-1.25-.339-1.584-.847m-.042.028l.042-.028m-.042.028l.042-.028");
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.sqzh_k23r {
  d: path("M25.649 18.01a3.5 3.5 0 0 0 .85-.17l.148-.055c.179-.063.401-.054.555.107c1.071 1.125 1.43 2.621.983 4.236s-1.732 2.764-2.98 3.033c-.084.02-.348.046-.505-.157l-.142-.14a3.5 3.5 0 0 0-.642-.589c1.567-.052 2.817-1.084 3.203-2.529c.39-1.469-.236-3.003-1.472-3.735z");
}

.ssb7y629c {
  d: path("M17.423 10.417a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.t3ca9xlms {
  stop-color: var(--svg-color--9b0831, #9B0831);
  stop-opacity: 0;
}

.tbz0q_48a {
  stop-color: var(--svg-color--dd365e, #DD365E);
  stop-opacity: 0;
}

.tc4y5tbfa {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
}

.tcape2laf {
  stop-color: var(--svg-color--edb63d, #EDB63D);
}

.to5wyljfl {
  fill: var(--svg-color--352827, #352827);
  d: path("m10.667 7.977l.002-.002l.002-.001l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.062.241-.14.42-.21c.36-.143.873-.257 1.494-.16a.534.534 0 0 1-.166 1.056a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.68-.824");
}

.tvi46ubab {
  cx: 19.214px;
  cy: 10.802px;
  r: 0.996px;
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u_wc6ubhb {
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uf71gn07a {
  d: path("M13.304 4.91c0-.154.183-.232.293-.126l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.179-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.129.129 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.052z");
}

.ug2jj9grv {
  stop-color: var(--svg-color--160508, #160508);
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.uvhdvfbmh {
  cx: 19.214px;
  cy: 10.802px;
  r: 1.671px;
}

.v-7fbqiwn {
  d: path("M13.277 16.934v1.699c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.018");
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vylrb5bvm {
  d: path("M21.577 17.982v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.w_8w8wqmn {
  d: path("M15.167 19.605h-1.17v6.57h1.17z");
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xm1do5bfv {
  d: path("M18.168 7.976h-.002l-.002-.002l-.004-.004l-.012-.01a2 2 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.494-.16a.534.534 0 1 0 .166 1.056c.398-.063.717.01.935.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .68-.825");
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xweobbcdr {
  cx: 11.987px;
  cy: 10.023px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.yl696wcmm {
  stop-color: var(--svg-color--98072e, #98072E);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z1374kqmn {
  stop-color: var(--svg-color--9b0831, #9B0831);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zdsg9r3jo {
  fill-rule: evenodd;
  d: path("M11.157 16.066v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zhmn0cciw {
  stop-color: var(--svg-color--a11339, #A11339);
}

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

</style>
