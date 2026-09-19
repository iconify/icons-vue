<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#izE6R7Q)"><path fill="url(#iaUsmrb)" class="f1jw_ab3w"/><path fill="url(#iTDnx1x)" class="f1jw_ab3w"/></g><path class="b_qv5du4s"/><path fill="url(#i6KAjab)" class="faisxaclj"/><path fill="url(#i2gSgbe)" class="faisxaclj"/><path fill="url(#idcBZkt)" class="faisxaclj"/><path fill="url(#iiLw8Vb)" class="faisxaclj"/><path fill="url(#iAIO9Yd)" class="faisxaclj"/><path fill="url(#isZrtzc)" class="faisxaclj"/><path fill="url(#iJkm9gA)" class="d_-1b_bzw"/><path fill="url(#ih3vBxb)" class="d_-1b_bzw"/><path fill="url(#iov0n7a)" class="d_-1b_bzw"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#i4dn0Mr)" class="vylrb5bvm"/><path fill="url(#iWkx0Sd)" class="ix8bgh62p"/><g filter="url(#iNfizxd)"><path fill="url(#ibgFUYd)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iYgYbde)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iSuBe6b)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iak8rNL)" clip-rule="evenodd" class="zdsg9r3jo"/></g><path fill="url(#ixIpvFe)" class="re3g0rbfm"/><path fill="url(#ivW1LDc)" class="re3g0rbfm"/><g filter="url(#ifMbzjd)"><path fill="url(#icL13gd)" class="re3g0rbfm"/><path fill="url(#i1P7Cub)" class="re3g0rbfm"/></g><circle fill="url(#i1JaVoe)" class="j4n9hoogk"/><circle fill="url(#iQNFphc)" class="j4n9hoogk"/><circle fill="url(#iv7X5Ob)" class="j4n9hoogk"/><g filter="url(#igFM3NR)"><circle class="myoz5_qsi"/></g><circle fill="url(#iTR5ZAb)" class="pyt0z16nr"/><circle fill="url(#iJCxPce)" class="pyt0z16nr"/><circle fill="url(#iiPnOXc)" class="pyt0z16nr"/><g filter="url(#iwuAz8b)"><circle fill="url(#ic3TiDb)" class="l-30l5gyu"/></g><g filter="url(#iJGZGrc)"><path fill="url(#icb6zZd)" class="khzgs7b6v"/><path fill="url(#iknglqc)" class="khzgs7b6v"/><path fill="url(#ihNg4Kd)" class="khzgs7b6v"/></g><path fill="url(#iEmUibe)" class="khzgs7b6v"/><path fill="url(#i2tOpJe)" class="khzgs7b6v"/><path fill="url(#igZ2Rje)" class="khzgs7b6v"/><path fill="url(#icbMnad)" class="khzgs7b6v"/><g filter="url(#iFbwl3q)"><path class="lbc3xobix"/></g><g filter="url(#iSUWXad)"><path class="hpsx9jb7b"/><path fill="url(#iR8Wpde)" class="dn-rfppum"/><path fill="url(#i14kiAb)" class="dn-rfppum"/><path fill="url(#iYJAcQe)" class="dn-rfppum"/><path fill="url(#iNI0VSb)" class="dn-rfppum"/></g><g filter="url(#iv1buBN)"><path stroke="url(#iLqGRxb)" class="zf4icg1ev"/></g><path class="jkhpueb8t"/><g filter="url(#iJ3kMJd)"><path class="fplq09b-q"/><path fill="url(#iKCmVjv)" class="ds4qf2_ch"/></g><g filter="url(#ijQpKIb)"><path class="w14y3unzw"/><path fill="url(#ihIbT4c)" class="m2kt41vtt"/></g><path class="mvlty6bjw"/><path fill="url(#i8o39Le)" class="miye0lm_p"/><path class="z1mpzsg2r"/><g filter="url(#iO913Ld)"><path class="u4k93zbsa"/><path fill="url(#iKkDQ2g)" class="wogivvbml"/></g><g filter="url(#ihCA7cc)"><path fill="url(#ihISvpc)" class="fahvqlbif"/></g><path class="g8d9jrenw"/><path fill="url(#iihVPhd)" class="wio9g2bfq"/><path class="n5kj5ackx"/><g filter="url(#iWIW1pp)"><path fill="url(#ilnVyQV)" class="b8urgdp0g"/></g><g filter="url(#ijdTqud)"><ellipse transform="rotate(-27.914 11.981 10.03)" class="lhulchboz"/><ellipse fill="url(#iE1kAnc)" transform="rotate(-27.914 11.981 10.03)" class="re3zzabdb"/></g><path fill="url(#iHZvJfc)" class="hgn0v4h0b"/><path fill="url(#ilxTFMd)" class="hgn0v4h0b"/><path fill="url(#izHz1gd)" class="hgn0v4h0b"/><path fill="url(#iFF74De)" class="hgn0v4h0b"/><path fill="url(#ia6hdgb)" class="hgn0v4h0b"/><path class="e3e67-bvh"/><path fill="url(#inGX0Oc)" class="oyh5fnr6n"/><path fill="url(#i9mB5Mc)" class="oyh5fnr6n"/><path fill="url(#iUnDHVd)" class="oyh5fnr6n"/><path fill="url(#iKjUOTb)" class="oyh5fnr6n"/><path fill="url(#i1i1Lbq)" class="m94o2m2wq"/><path fill="url(#izpcbVd)" class="m94o2m2wq"/><path fill="url(#iZ6eZGb)" class="m94o2m2wq"/><path fill="url(#ibPujte)" class="m94o2m2wq"/><path fill="url(#i6qz0xW)" class="m94o2m2wq"/><path fill="url(#iMEPogb)" class="w_8w8wqmn"/><path fill="url(#iutMDkb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#i7jKoUY)"><path fill="url(#iKGw4kt)" class="recb7tbvt"/><path fill="url(#iyoBo3i)" class="recb7tbvt"/></g><g filter="url(#iOPYQQc)"><path fill="url(#i8eYWWc)" class="g9altzzue"/><path fill="url(#iO3rDAc)" class="g9altzzue"/></g><path fill="url(#iiVeO6c)" class="g9altzzue"/><path fill="url(#i7W12qd)" class="g9altzzue"/><g filter="url(#iuFSXJc)"><path fill="url(#i5b1ojc)" class="rys9ifzwf"/><path fill="url(#ifSfzbe)" class="rys9ifzwf"/><path fill="url(#ih6dC9c)" class="rys9ifzwf"/></g><g filter="url(#iH161od)"><path fill="url(#ibijqYb)" class="drnn9_b6l"/><path fill="url(#iDqb5ve)" class="drnn9_b6l"/><path fill="url(#iJhoPse)" class="drnn9_b6l"/></g><g filter="url(#ick3jid)"><path fill="url(#i9kTuLc)" class="uf71gn07a"/></g><g filter="url(#ig4B0mc)"><path stroke="url(#i2bdjSd)" class="cj_ualb6i"/></g><g filter="url(#iBskIxd)"><path class="cd1yj8bur"/></g><path fill="url(#i0RrKOF)" class="mgcnwqpgr"/><path fill="url(#iVMDejt)" class="yu5aht8rs"/><defs><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iAIO9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="iov0n7a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="i4dn0Mr" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.973)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="iYgYbde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.066)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iSuBe6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.19 16.067)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iak8rNL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -2.20052 0 13.3 16.854)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="z1374kqmn"/><stop offset="1" class="t3ca9xlms"/></radialGradient><radialGradient id="ivW1LDc" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.993 16.064)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i1P7Cub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82813 -3.16462 0 14.8 16.87)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="poqt_ebqs"/><stop offset="1" class="yl696wcmm"/></radialGradient><radialGradient id="i1JaVoe" cx="0" cy="0" r="1" gradientTransform="rotate(171.254 4.212 5.843)scale(1.03952 1.28428)" gradientUnits="userSpaceOnUse"><stop offset=".312" class="pborerbxa"/><stop offset="1" class="w0il0xbno"/></radialGradient><radialGradient id="iQNFphc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0327 1.43314 -.62416 -.44976 8.7 9.313)" gradientUnits="userSpaceOnUse"><stop class="gtsom-rnx"/><stop offset="1" class="nraysn6fv"/></radialGradient><radialGradient id="iv7X5Ob" cx="0" cy="0" r="1" gradientTransform="rotate(152.176 3.581 6.572)scale(1.90811 2.11039)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="vtjxnzmhr"/><stop offset="1" class="jptedhboe"/></radialGradient><radialGradient id="iTR5ZAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21875 0 0 -1.67969 20.69 10.931)" gradientUnits="userSpaceOnUse"><stop class="tv4v87meh"/><stop offset="1" class="g1h0vm3cs"/></radialGradient><radialGradient id="iJCxPce" cx="0" cy="0" r="1" gradientTransform="rotate(-96.433 15.397 -2.538)scale(.55783 1.37188)" gradientUnits="userSpaceOnUse"><stop offset=".065" class="qjmwk8bfl"/><stop offset="1" class="scaayqb8z"/></radialGradient><radialGradient id="iiPnOXc" cx="0" cy="0" r="1" gradientTransform="rotate(122.518 7.588 10.31)scale(.87171 3.42983)" gradientUnits="userSpaceOnUse"><stop class="z0p5n7x3a"/><stop offset="1" class="j61i03baq"/></radialGradient><radialGradient id="ic3TiDb" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 0 0 .88063 19.386 10.808)" gradientUnits="userSpaceOnUse"><stop class="p4o9mjvoc"/><stop offset="1" class="msknpebtd"/></radialGradient><radialGradient id="icb6zZd" cx="0" cy="0" r="1" gradientTransform="rotate(172.405 8.238 6.656)scale(6.14768 7.43627)" gradientUnits="userSpaceOnUse"><stop class="akffnubyi"/><stop offset="1" class="ao2503bkc"/></radialGradient><radialGradient id="iknglqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 16.782 9.537)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="ihNg4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 12.225 9.671)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="igZ2Rje" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.21775 -11.5328 0 14.411 11.198)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="mabqwdrbn"/><stop offset=".975" class="ufg9mqbvf"/></radialGradient><radialGradient id="icbMnad" cx="0" cy="0" r="1" gradientTransform="rotate(-99.224 14.62 1.39)scale(8.71274 13.0467)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="dzz64xb1k"/><stop offset=".939" class="pihxqbbra"/></radialGradient><radialGradient id="iNI0VSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 14.764 12.415)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iKCmVjv" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 16.88 8.665)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ihIbT4c" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.011 -2.633)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i8o39Le" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 16.615 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKkDQ2g" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 16.387 10.21)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iihVPhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 12.253 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iE1kAnc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.076 -.717)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iFF74De" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.098)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iKjUOTb" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.767 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iutMDkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iO3rDAc" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.635)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iiVeO6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.394)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="i7W12qd" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.331)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iDqb5ve" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.503)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="i0RrKOF" cx="0" cy="0" r="1" gradientTransform="rotate(-88.046 9.496 .427)scale(2.97829 .2991)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="o4001ccri"/><stop offset="1" class="ldoh6m8qh"/></radialGradient><radialGradient id="iVMDejt" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 -1.90641 .64964 .15441 19.878 9.879)" gradientUnits="userSpaceOnUse"><stop class="g6vlzzbhl"/><stop offset="1" class="ug2jj9grv"/></radialGradient><linearGradient id="iaUsmrb" x1="14.587" x2="14.587" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iTDnx1x" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iWkx0Sd" x1="15.654" x2="15.654" y1="15.025" y2="21.362" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ibgFUYd" x1="11.238" x2="13.128" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="ggy1amtma"/><stop offset="1" class="ctz7grpzo"/></linearGradient><linearGradient id="ixIpvFe" x1="13.277" x2="13.489" y1="18.097" y2="18.097" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iEmUibe" x1="9.036" x2="10.956" y1="13.893" y2="13.824" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="i2tOpJe" x1="19.563" x2="18.428" y1="13.052" y2="12.951" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iR8Wpde" x1="13.572" x2="14.511" y1="11.857" y2="11.857" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="i14kiAb" x1="15.375" x2="14.349" y1="12.179" y2="12.165" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iYJAcQe" x1="14.631" x2="14.631" y1="12.921" y2="12.348" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iLqGRxb" x1="13.4" x2="13.835" y1="14.536" y2="13.849" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ihISvpc" x1="17.393" x2="17.079" y1="10.18" y2="10.373" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilnVyQV" x1="12.996" x2="12.683" y1="10.18" y2="10.373" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilxTFMd" x1="10.646" x2="16.989" y1="6.723" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="i9mB5Mc" x1="14.592" x2="14.592" y1="30.316" y2="28.722" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iUnDHVd" x1="14.592" x2="14.592" y1="26.172" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i1i1Lbq" x1="14.582" x2="14.582" y1="6.972" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iMEPogb" x1="14.582" x2="14.582" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="i8eYWWc" x1="22.021" x2="18.333" y1="16.753" y2="29.972" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="i2bdjSd" x1="18.689" x2="20.193" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="izE6R7Q" width="17.197" height="11.9" x="5.989" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/></filter><filter id="iNfizxd" width="6.88" height="3.666" x="11.157" y="15.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/></filter><filter id="ifMbzjd" width="4.97" height="3.828" x="13.277" y="15.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/></filter><filter id="igFM3NR" width="2.49" height="2.49" x="8.444" y="9.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".125"/></filter><filter id="iwuAz8b" width="2.49" height="2.49" x="17.957" y="9.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".125"/></filter><filter id="iJGZGrc" width="10.584" height="12.177" x="9.279" y="5.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/></filter><filter id="iFbwl3q" width="3.26" height="4.181" x="12.568" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".375"/></filter><filter id="iSUWXad" width="2.377" height="3.181" x="13.248" y="9.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".125"/></filter><filter id="iv1buBN" width="3.617" height="1.472" x="12.628" y="13.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".05"/></filter><filter id="iJ3kMJd" width="2.979" height="1.873" x="15.619" y="7.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/></filter><filter id="ijQpKIb" width="2.98" height="1.873" x="10.471" y="7.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/></filter><filter id="iO913Ld" width=".787" height=".696" x="15.881" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".05"/></filter><filter id="ihCA7cc" width=".891" height=".913" x="16.721" y="9.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".1"/></filter><filter id="iWIW1pp" width=".986" height="1.04" x="12.28" y="9.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".1"/></filter><filter id="ijdTqud" width=".913" height=".704" x="11.525" y="9.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".05"/></filter><filter id="i7jKoUY" width="5.52" height="4.05" x="11.827" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2612" result="effect2_innerShadow_4002_2612"/></filter><filter id="iOPYQQc" width="6.94" height="14.221" x="16.577" y="15.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2612" result="effect2_innerShadow_4002_2612"/></filter><filter id="iuFSXJc" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2612" result="effect2_innerShadow_4002_2612"/></filter><filter id="iH161od" width="4.557" height="7.476" x="23.816" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2612"/></filter><filter id="ick3jid" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2612"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2612" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2612" result="effect3_innerShadow_4002_2612"/></filter><filter id="ig4B0mc" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".125"/></filter><filter id="iBskIxd" width="2.769" height="7.081" x="18.396" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2612" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-firefighter-medium" /></template>
<style>
.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.akffnubyi {
  stop-color: var(--svg-color--c2917d, #C2917D);
}

.ao2503bkc {
  stop-color: var(--svg-color--966966, #966966);
}

.b_qv5du4s {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.b8urgdp0g {
  d: path("M13.066 10.437c0-.288-.235-.48-.298-.539l-.288.279l.177.361z");
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
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

.d_-1b_bzw {
  d: path("M7.607 29.972V17.971a10.98 10.98 0 0 0-4.02 8.501v3.5z");
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
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

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.dn-rfppum {
  d: path("m14.054 10.523l-.53 1.7c-.11.349.15.698.52.698h.786a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.drnn9_b6l {
  d: path("M25.649 18.01a3.5 3.5 0 0 0 .85-.171l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.62.983 4.235s-1.732 2.764-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.735z");
}

.ds4qf2_ch {
  d: path("m18.156 8.03l-.001-.001l-.002-.002l-.005-.004l-.012-.01l-.036-.026a2.6 2.6 0 0 0-.539-.291a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .167 1.055c.398-.063.716.01.933.096a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .678-.824");
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.dzz64xb1k {
  stop-color: var(--svg-color--814953, #814953);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3e67-bvh {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
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

.f1jw_ab3w {
  d: path("M22.174 7.972H7.152c-.395.32-.78 1.337-1.163 1.657v1.343c0 4.69 3.854 8.5 8.598 8.5s8.598-3.81 8.598-8.5V9.63c-.354-.42-.687-1.207-1.011-1.657");
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fahvqlbif {
  d: path("M17.412 10.424a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
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

.fplq09b-q {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m18.156 8.03l-.001-.001l-.002-.002l-.005-.004l-.012-.01l-.036-.026a2.6 2.6 0 0 0-.539-.291a2.83 2.83 0 0 0-1.492-.159a.534.534 0 0 0 .167 1.055c.398-.063.716.01.933.096a1.5 1.5 0 0 1 .309.166a.534.534 0 0 0 .678-.824");
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g1h0vm3cs {
  stop-color: var(--svg-color--a7746c, #A7746C);
}

.g6vlzzbhl {
  stop-color: var(--svg-color--272324, #272324);
}

.g8d9jrenw {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.044 9.378c-.653 0-1.205.45-1.355 1.058c-.044.175.09.34.268.34h2.23a.23.23 0 0 0 .228-.27a1.4 1.4 0 0 0-1.371-1.128");
}

.g9altzzue {
  d: path("m22.636 16.136l-1.38-.368a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.ggy1amtma {
  stop-color: var(--svg-color--d53260, #D53260);
}

.gtsom-rnx {
  stop-color: var(--svg-color--5f322c, #5F322C);
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hgn0v4h0b {
  d: path("M20.885 7.333H8.29v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.hpsx9jb7b {
  fill: var(--svg-color--a3746d, #A3746D);
  d: path("m14.054 10.523l-.53 1.7c-.11.349.15.698.52.698h.786a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
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

.ix8bgh62p {
  d: path("M13.277 15.972v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j4n9hoogk {
  cx: 9.689px;
  cy: 10.808px;
  r: 1.669px;
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j61i03baq {
  stop-color: var(--svg-color--723e32, #723E32);
  stop-opacity: 0;
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jkhpueb8t {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.437 13.938c-.508 0-.985-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.918.845 1.583.845s1.248-.338 1.582-.846c.087-.13-.06-.278-.197-.209c-.401.21-.873.329-1.385.329");
}

.jptedhboe {
  stop-color: var(--svg-color--93635d, #93635D);
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.khzgs7b6v {
  d: path("M9.28 8.757c0-.402.131-.806.395-1.068c.268-.213.462-.371.462-.691v-.854a.52.52 0 0 1 .43-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.271.267 3.915.427c.215.053.43.267.43.533v.854c0 .32.59.314.804.527c.502.352.041.871 0 1.286c-.18 1.79-.235 3.6-.355 5.398c-.16 1.769-1.552 3.002-3.21 3.002h-3.21c-1.713 0-3.05-1.233-3.21-3.002c-.14-1.817-.201-3.638-.367-5.452");
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

.l-30l5gyu {
  cx: 19.202px;
  cy: 10.808px;
  r: 0.995px;
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lbc3xobix {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m14.161 10.686l-.82 1.7c-.102.349.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.376-.283-.376-.395 0");
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

.lhulchboz {
  cx: 11.981px;
  cy: 10.031px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m2kt41vtt {
  d: path("m10.663 8.03l.002-.002l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.679-.824");
}

.m94o2m2wq {
  d: path("M8.659 7.972h11.846c.95 0 1.99.485 1.99 2.68h.69V9.347c0-1.43-.847-2.375-2.456-2.375H8.435c-1.609 0-2.456.946-2.456 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.mabqwdrbn {
  stop-color: var(--svg-color--9c6571, #9C6571);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgcnwqpgr {
  d: path("M9.566 7.972h-.908q-.16 0-.321.02c.098.497.322 1.42.428 1.754c.112.356.475.46.621.469c-.016-.32-.065-1.1-.065-1.557c0-.356.13-.574.245-.686");
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.miye0lm_p {
  d: path("M16.617 9.65a.892.892 0 0 1 .86 1.127h-1.723a.896.896 0 0 1 .864-1.127");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.msknpebtd {
  stop-color: var(--svg-color--8b5d55, #8B5D55);
}

.mvlty6bjw {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.824 9.378c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.27a1.396 1.396 0 0 1 1.37-1.128");
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.myoz5_qsi {
  cx: 9.689px;
  cy: 10.808px;
  r: 0.995px;
  fill: var(--svg-color--6c4141, #6C4141);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n5kj5ackx {
  fill: var(--svg-color--000, #000);
  d: path("M12.762 10.542a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .06-.236");
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nraysn6fv {
  stop-color: var(--svg-color--5f322c, #5F322C);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o4001ccri {
  stop-color: var(--svg-color--362b29, #362B29);
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
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

.oyh5fnr6n {
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.p4o9mjvoc {
  stop-color: var(--svg-color--997164, #997164);
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pborerbxa {
  stop-color: var(--svg-color--6d424c, #6D424C);
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pihxqbbra {
  stop-color: var(--svg-color--814953, #814953);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poqt_ebqs {
  stop-color: var(--svg-color--98072e, #98072E);
}

.pyt0z16nr {
  cx: 19.202px;
  cy: 10.808px;
  r: 1.669px;
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qjmwk8bfl {
  stop-color: var(--svg-color--9d5f60, #9D5F60);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.re3g0rbfm {
  d: path("M13.277 16.934v1.698c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.017");
}

.re3zzabdb {
  cx: 11.981px;
  cy: 10.031px;
  rx: 0.389px;
  ry: 0.197px;
}

.recb7tbvt {
  d: path("M17.247 6.972h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
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

.scaayqb8z {
  stop-color: var(--svg-color--9d5f60, #9D5F60);
  stop-opacity: 0;
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
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

.tv4v87meh {
  stop-color: var(--svg-color--b48b7a, #B48B7A);
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.u4k93zbsa {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.552 9.838c.063.085-.07.189-.22.302c-.152.112-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.uf71gn07a {
  d: path("M13.304 4.91c0-.154.183-.232.293-.126l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.179-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.129.129 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.052z");
}

.ufg9mqbvf {
  stop-color: var(--svg-color--984359, #984359);
}

.ug2jj9grv {
  stop-color: var(--svg-color--160508, #160508);
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
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

.vtjxnzmhr {
  stop-color: var(--svg-color--93635d, #93635D);
  stop-opacity: 0;
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

.w0il0xbno {
  stop-color: var(--svg-color--815456, #815456);
}

.w14y3unzw {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m10.663 8.03l.002-.002l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.679-.824");
}

.wio9g2bfq {
  d: path("M12.25 9.65a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.896-.892");
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wogivvbml {
  d: path("M16.552 9.838c.063.085-.07.189-.22.302c-.152.112-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.389-.051");
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
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

.yu5aht8rs {
  d: path("M19.358 7.972h1.148l.085.002a24 24 0 0 1-.432 1.772c-.112.356-.498.457-.644.465c.016-.32.088-1.085.088-1.553c0-.356-.13-.574-.245-.686");
}

.z0p5n7x3a {
  stop-color: var(--svg-color--723e32, #723E32);
}

.z1374kqmn {
  stop-color: var(--svg-color--9b0831, #9B0831);
}

.z1mpzsg2r {
  fill: var(--svg-color--000, #000);
  d: path("M16.106 10.542c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zdsg9r3jo {
  fill-rule: evenodd;
  d: path("M11.157 16.066v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zf4icg1ev {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.437 13.938c-.508 0-.985-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.918.845 1.583.845s1.248-.338 1.582-.846c.087-.13-.06-.278-.197-.209c-.401.21-.873.329-1.385.329Z");
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
