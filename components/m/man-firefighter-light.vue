<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4stFHb)"><path fill="url(#i4a0pNb)" class="x30l93ibt"/><path fill="url(#iTDnx1x)" class="x30l93ibt"/></g><path class="vwc2t-btp"/><path fill="url(#iqN6V4b)" class="kngw6fbep"/><path fill="url(#i2gSgbe)" class="kngw6fbep"/><path fill="url(#idcBZkt)" class="kngw6fbep"/><path fill="url(#iiLw8Vb)" class="kngw6fbep"/><path fill="url(#ilGajNb)" class="kngw6fbep"/><path fill="url(#isZrtzc)" class="kngw6fbep"/><path fill="url(#iJkm9gA)" class="ajcn8-ycn"/><path fill="url(#ih3vBxb)" class="ajcn8-ycn"/><path fill="url(#i9JMave)" class="ajcn8-ycn"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#iAOYtlU)" class="vylrb5bvm"/><path fill="url(#iI1au3d)" class="d7c3-bbbw"/><g filter="url(#iEkQG5c)"><path fill="url(#ibgFUYd)" clip-rule="evenodd" class="gsztnh71f"/><path fill="url(#irUvMbp)" clip-rule="evenodd" class="gsztnh71f"/><path fill="url(#iSuBe6b)" clip-rule="evenodd" class="gsztnh71f"/><path fill="url(#iak8rNL)" clip-rule="evenodd" class="gsztnh71f"/></g><path fill="url(#iU4Plhc)" class="re3g0rbfm"/><path fill="url(#ivW1LDc)" class="re3g0rbfm"/><g filter="url(#iGAJosa)"><path fill="url(#icL13gd)" class="re3g0rbfm"/><path fill="url(#i1P7Cub)" class="re3g0rbfm"/></g><circle fill="url(#i4ZVNiB)" class="pst71hbtq"/><circle fill="url(#ixAs9rb)" class="pst71hbtq"/><g filter="url(#iSYoEju)"><circle class="ps-ob4bcl"/></g><circle fill="url(#i27ehjE)" class="ht6coabyh"/><circle fill="url(#iLKD9Ud)" class="ht6coabyh"/><g filter="url(#ie8HJbd)"><circle class="n02tg04cz"/></g><g filter="url(#ibLk3ic)"><path fill="url(#im3ubMv)" class="x71f8xalx"/><path fill="url(#iajTsXd)" class="x71f8xalx"/><path fill="url(#iTiB0Pb)" class="x71f8xalx"/><path fill="url(#i7mJvye)" class="x71f8xalx"/><path fill="url(#iWsWmMs)" class="x71f8xalx"/><path fill="url(#ipQ36Mc)" class="x71f8xalx"/><path fill="url(#iLufRgd)" class="x71f8xalx"/></g><g filter="url(#iM7VqJe)"><path class="lz0w9zzwo"/></g><g filter="url(#i5iPbae)"><path class="yqlu5g-5f"/><path fill="url(#iiJ1Mcc)" class="ndnjhkmwh"/><path fill="url(#iys8Csd)" class="ndnjhkmwh"/><path fill="url(#i6gtJad)" class="ndnjhkmwh"/><path fill="url(#iBXWSMM)" class="ndnjhkmwh"/></g><g filter="url(#i6FDbrd)"><path stroke="url(#iQZqK6i)" class="jkldogb0s"/></g><path class="lh7xewbcc"/><g filter="url(#i0M3Dbe)"><path class="vwqp4fbhy"/></g><g filter="url(#irucnbe)"><path class="wuxqmhyhn"/></g><path class="ixlsrrb6n"/><path fill="url(#ixHXbYd)" class="fzrbtudfx"/><path class="h-0o4ebvi"/><g filter="url(#iSmCsmb)"><path class="scue_6bjb"/><path fill="url(#ix0Vpsc)" class="j7loiqitn"/></g><g filter="url(#iYJwv3b)"><path fill="url(#iyyGu7c)" class="in10q2but"/></g><path class="y0ttzg77n"/><path fill="url(#iKBKtrd)" class="q64_sbv3d"/><path class="d8mtf4b8n"/><g filter="url(#iteeGBd)"><path fill="url(#iSnIufZ)" class="n905xpb1j"/></g><g filter="url(#iiEyf2i)"><ellipse transform="rotate(-27.914 12.023 10.006)" class="h7nj23ebg"/><ellipse fill="url(#iM2WeKb)" transform="rotate(-27.914 12.023 10.006)" class="q5fn77b2q"/></g><path fill="url(#iHZvJfc)" class="v5pkyqbhx"/><path fill="url(#ih5nvHe)" class="v5pkyqbhx"/><path fill="url(#izHz1gd)" class="v5pkyqbhx"/><path fill="url(#iEsU6Jd)" class="v5pkyqbhx"/><path fill="url(#ia6hdgb)" class="v5pkyqbhx"/><path class="e3e67-bvh"/><path fill="url(#inGX0Oc)" class="oyh5fnr6n"/><path fill="url(#i9mB5Mc)" class="oyh5fnr6n"/><path fill="url(#iUnDHVd)" class="oyh5fnr6n"/><path fill="url(#iKjUOTb)" class="oyh5fnr6n"/><path fill="url(#ij2mDJd)" class="onmhnc-bl"/><path fill="url(#ij0qnyb)" class="onmhnc-bl"/><path fill="url(#iTdENFb)" class="onmhnc-bl"/><g filter="url(#iWlDvod)"><path fill="url(#iKGw4kt)" class="recb7tbvt"/><path fill="url(#iyoBo3i)" class="recb7tbvt"/></g><g filter="url(#i7WIh3c)"><path fill="url(#ibeddjd)" class="alecchcgl"/><path fill="url(#iO3rDAc)" class="alecchcgl"/></g><path fill="url(#iiVeO6c)" class="alecchcgl"/><path fill="url(#i7W12qd)" class="alecchcgl"/><g filter="url(#i7U7eYF)"><path fill="url(#i5b1ojc)" class="kgad3jlte"/><path fill="url(#ifSfzbe)" class="kgad3jlte"/><path fill="url(#ih6dC9c)" class="kgad3jlte"/></g><g filter="url(#iUcto8g)"><path fill="url(#ibijqYb)" class="f_cylsxoe"/><path fill="url(#iyoK4Kd)" class="f_cylsxoe"/><path fill="url(#iJhoPse)" class="f_cylsxoe"/></g><g filter="url(#imPdf5b)"><path fill="url(#i9kTuLc)" class="o5k1iyb2q"/></g><g filter="url(#iWL2gUq)"><path stroke="url(#i2bdjSd)" class="cj_ualb6i"/></g><g filter="url(#inkDcsc)"><path class="f64lk-nyh"/></g><path fill="url(#i4vVaPd)" class="q99qvquze"/><path fill="url(#iZRvxad)" class="apscd3btu"/><path fill="url(#ivHTDTb)" class="gjvgk9-7y"/><path fill="url(#izpcbVd)" class="gjvgk9-7y"/><path fill="url(#idR7qVz)" class="gjvgk9-7y"/><path fill="url(#ibPujte)" class="gjvgk9-7y"/><path fill="url(#i6qz0xW)" class="gjvgk9-7y"/><defs><radialGradient id="iqN6V4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.943)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="ilGajNb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.723)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="i9JMave" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.973)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iAOYtlU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.972)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="irUvMbp" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.067)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iSuBe6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.19 16.067)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iak8rNL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -2.20052 0 13.3 16.854)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="z1374kqmn"/><stop offset="1" class="t3ca9xlms"/></radialGradient><radialGradient id="ivW1LDc" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.993 16.064)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i1P7Cub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82813 -3.16462 0 14.8 16.87)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="poqt_ebqs"/><stop offset="1" class="yl696wcmm"/></radialGradient><radialGradient id="i4ZVNiB" cx="0" cy="0" r="1" gradientTransform="rotate(71.269 -2.37 10.86)scale(2.87079 5.02391)" gradientUnits="userSpaceOnUse"><stop class="ibl6otm1x"/><stop offset="1" class="maz6vnbfe"/></radialGradient><radialGradient id="ixAs9rb" cx="0" cy="0" r="1" gradientTransform="rotate(132.797 2.484 7.416)scale(1.72485)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="t0fmjbosy"/><stop offset="1" class="c5vdirbqo"/></radialGradient><radialGradient id="iLKD9Ud" cx="0" cy="0" r="1" gradientTransform="rotate(51.668 .307 25.75)scale(1.58714 .71543)" gradientUnits="userSpaceOnUse"><stop class="w3r29wbuy"/><stop offset="1" class="nmjv0ccdq"/></radialGradient><radialGradient id="im3ubMv" cx="0" cy="0" r="1" gradientTransform="rotate(174.766 8.174 6.53)scale(4.11089 5.43193)" gradientUnits="userSpaceOnUse"><stop class="xsc4fpbic"/><stop offset="1" class="tqgh1edwg"/></radialGradient><radialGradient id="iajTsXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02764 8.09374 -10.9868 -1.39497 15.535 9.383)" gradientUnits="userSpaceOnUse"><stop offset=".648" class="q4_8l7b4h"/><stop offset="1" class="n1u43ybln"/></radialGradient><radialGradient id="iWsWmMs" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 16.824 9.512)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="ipQ36Mc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 12.266 9.479)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iLufRgd" cx="0" cy="0" r="1" gradientTransform="rotate(-94.966 15.28 1.3)scale(9.234 12.8832)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="m965m8bpe"/><stop offset="1" class="p4lxhnbhm"/></radialGradient><radialGradient id="iBXWSMM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 14.805 12.39)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="ixHXbYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 16.657 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ix0Vpsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 16.429 10.186)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKBKtrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 12.294 10.101)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iM2WeKb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.084 -.75)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iEsU6Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.097)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iKjUOTb" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.767 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="ij0qnyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.756)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="iTdENFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.828)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iO3rDAc" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.635)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iiVeO6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.394)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="i7W12qd" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.331)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iyoK4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.504)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="i4vVaPd" cx="0" cy="0" r="1" gradientTransform="rotate(-88.046 9.511 .384)scale(2.97829 .2991)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="o4001ccri"/><stop offset="1" class="ldoh6m8qh"/></radialGradient><radialGradient id="iZRvxad" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 -1.90641 .64964 .15441 19.921 9.88)" gradientUnits="userSpaceOnUse"><stop class="g6vlzzbhl"/><stop offset="1" class="ug2jj9grv"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="idR7qVz" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.145)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><linearGradient id="i4a0pNb" x1="14.587" x2="14.587" y1="7.973" y2="19.473" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iTDnx1x" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iI1au3d" x1="15.654" x2="15.654" y1="15.026" y2="21.362" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ibgFUYd" x1="11.238" x2="13.128" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="ggy1amtma"/><stop offset="1" class="ctz7grpzo"/></linearGradient><linearGradient id="iU4Plhc" x1="13.277" x2="13.489" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="i27ehjE" x1="20.711" x2="19.243" y1="10.391" y2="12.453" gradientUnits="userSpaceOnUse"><stop class="x9k51rhux"/><stop offset="1" class="cpy2agbka"/></linearGradient><linearGradient id="iTiB0Pb" x1="8.836" x2="12.194" y1="12.7" y2="12.814" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="i7mJvye" x1="9.083" x2="10.964" y1="13.869" y2="13.802" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iiJ1Mcc" x1="13.614" x2="14.552" y1="11.832" y2="11.832" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iys8Csd" x1="15.416" x2="14.391" y1="12.155" y2="12.14" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="i6gtJad" x1="14.673" x2="14.673" y1="12.897" y2="12.324" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iQZqK6i" x1="13.441" x2="13.876" y1="14.512" y2="13.825" gradientUnits="userSpaceOnUse"><stop class="ndg3-7uvv"/><stop offset=".663" class="uny36og2t"/></linearGradient><linearGradient id="iyyGu7c" x1="17.434" x2="17.121" y1="10.156" y2="10.349" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSnIufZ" x1="13.038" x2="12.724" y1="10.155" y2="10.349" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih5nvHe" x1="10.646" x2="16.989" y1="6.722" y2="6.722" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="i9mB5Mc" x1="14.592" x2="14.592" y1="30.316" y2="28.722" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iUnDHVd" x1="14.592" x2="14.592" y1="26.172" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="ij2mDJd" x1="14.582" x2="14.582" y1="19.605" y2="26.176" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="ibeddjd" x1="22.021" x2="18.333" y1="16.754" y2="29.972" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="i2bdjSd" x1="18.689" x2="20.193" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><linearGradient id="ivHTDTb" x1="14.582" x2="14.582" y1="6.973" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><filter id="i4stFHb" width="17.197" height="11.9" x="5.989" y="7.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/></filter><filter id="iEkQG5c" width="6.88" height="3.666" x="11.157" y="15.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/></filter><filter id="iGAJosa" width="4.97" height="3.828" x="13.277" y="15.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/></filter><filter id="iSYoEju" width="2.642" height="2.642" x="8.409" y="9.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".125"/></filter><filter id="ie8HJbd" width="2.748" height="2.748" x="17.869" y="9.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".125"/></filter><filter id="ibLk3ic" width="10.373" height="12.277" x="9.32" y="5.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/></filter><filter id="iM7VqJe" width="3.26" height="4.181" x="12.609" y="9.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".375"/></filter><filter id="i5iPbae" width="2.377" height="3.181" x="13.29" y="9.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".125"/></filter><filter id="i6FDbrd" width="3.617" height="1.472" x="12.669" y="13.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".05"/></filter><filter id="i0M3Dbe" width="2.979" height="1.873" x="15.66" y="7.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/></filter><filter id="irucnbe" width="2.98" height="1.873" x="10.513" y="7.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/></filter><filter id="iSmCsmb" width=".787" height=".696" x="15.923" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".05"/></filter><filter id="iYJwv3b" width=".891" height=".913" x="16.762" y="9.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".1"/></filter><filter id="iteeGBd" width=".986" height="1.04" x="12.321" y="9.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".1"/></filter><filter id="iiEyf2i" width=".913" height=".704" x="11.566" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".05"/></filter><filter id="iWlDvod" width="5.52" height="4.05" x="11.827" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2618" result="effect2_innerShadow_4002_2618"/></filter><filter id="i7WIh3c" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2618" result="effect2_innerShadow_4002_2618"/></filter><filter id="i7U7eYF" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2618" result="effect2_innerShadow_4002_2618"/></filter><filter id="iUcto8g" width="4.557" height="7.476" x="23.816" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2618"/></filter><filter id="imPdf5b" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2618"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2618" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2618"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2618" result="effect3_innerShadow_4002_2618"/></filter><filter id="iWL2gUq" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".125"/></filter><filter id="inkDcsc" width="2.769" height="7.081" x="18.396" y="23.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2618" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-firefighter-light" /></template>
<style>
.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ajcn8-ycn {
  d: path("M7.607 29.973V17.97a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.alecchcgl {
  d: path("m22.636 16.137l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.211a.53.53 0 0 0-.368-.624");
}

.apscd3btu {
  d: path("M19.401 7.973h1.147l.086.001a24 24 0 0 1-.432 1.772c-.112.356-.498.457-.644.465c.015-.32.087-1.084.087-1.553c0-.356-.13-.573-.244-.685");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c5vdirbqo {
  stop-color: var(--svg-color--d09185, #D09185);
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
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

.cpy2agbka {
  stop-color: var(--svg-color--df9c8b, #DF9C8B);
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

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d7c3-bbbw {
  d: path("M13.277 15.973v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8mtf4b8n {
  fill: var(--svg-color--000, #000);
  d: path("M12.803 10.517a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
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

.e3e67-bvh {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.172H7.607v3.8h13.97z");
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

.f_cylsxoe {
  d: path("M25.649 18.01a3.5 3.5 0 0 0 .85-.171l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.621.983 4.236s-1.732 2.764-2.98 3.033c-.084.02-.348.046-.505-.157l-.142-.14a3.5 3.5 0 0 0-.642-.589c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.734z");
}

.f64lk-nyh {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.629c0-.2 1.146-4.104 1.719-6.031");
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.fzrbtudfx {
  d: path("M16.659 9.625a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.g6vlzzbhl {
  stop-color: var(--svg-color--272324, #272324);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.ggy1amtma {
  stop-color: var(--svg-color--d53260, #D53260);
}

.gjvgk9-7y {
  d: path("M8.659 7.973h11.846c.95 0 1.99.484 1.99 2.68h.69V9.348c0-1.43-.847-2.375-2.456-2.375H8.435c-1.609 0-2.456.945-2.456 2.375v1.305h.69c0-2.196 1.04-2.68 1.99-2.68");
}

.gsztnh71f {
  fill-rule: evenodd;
  d: path("M11.157 16.066v1.587c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.878h-1.896a3.94 3.94 0 0 1-2.496-.885");
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h-0o4ebvi {
  fill: var(--svg-color--000, #000);
  d: path("M16.148 10.517c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h7nj23ebg {
  cx: 12.023px;
  cy: 10.006px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.ht6coabyh {
  cx: 19.243px;
  cy: 10.784px;
  r: 1.669px;
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.ibl6otm1x {
  stop-color: var(--svg-color--a9695d, #A9695D);
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.in10q2but {
  d: path("M17.454 10.4a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.ixlsrrb6n {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.866 9.353c.653 0 1.204.45 1.354 1.059a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.37-1.127");
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j7loiqitn {
  d: path("M16.593 9.813c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jkldogb0s {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.478 13.914c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.918.845 1.583.845s1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.209c-.4.21-.872.329-1.385.329Z");
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.kgad3jlte {
  d: path("m20.012 16.732l4.416 1.16a3.57 3.57 0 0 0 2.071-.053l.148-.054c.179-.063.401-.054.555.107c1.071 1.125 1.43 2.621.983 4.236s-1.732 2.764-2.98 3.033c-.084.02-.348.046-.505-.157l-.142-.14a3.5 3.5 0 0 0-1.745-1.111L18.57 22.55a.61.61 0 0 1-.43-.779l1.25-4.674c.045-.22.37-.43.622-.365");
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

.kngw6fbep {
  d: path("M14.587 15.473c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
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

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
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

.lh7xewbcc {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.478 13.914c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.918.845 1.583.845s1.248-.338 1.583-.846c.086-.13-.06-.279-.198-.209c-.4.21-.872.329-1.385.329");
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

.lz0w9zzwo {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m14.203 10.661l-.82 1.7c-.102.35.142.699.488.699h.737c.345 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m965m8bpe {
  stop-color: var(--svg-color--c78277, #C78277);
  stop-opacity: 0;
}

.maz6vnbfe {
  stop-color: var(--svg-color--cb857a, #CB857A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.n02tg04cz {
  cx: 19.243px;
  cy: 10.784px;
  r: 1.124px;
  fill: var(--svg-color--d29584, #D29584);
}

.n1u43ybln {
  stop-color: var(--svg-color--c37075, #C37075);
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n905xpb1j {
  d: path("M13.107 10.412c0-.288-.234-.48-.298-.538l-.288.278l.177.362z");
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.ndg3-7uvv {
  stop-color: var(--svg-color--ecb3a7, #ECB3A7);
}

.ndnjhkmwh {
  d: path("m14.096 10.498l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.115-.376-.646-.376-.765 0");
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nmjv0ccdq {
  stop-color: var(--svg-color--bc7a66, #BC7A66);
  stop-opacity: 0;
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

.o5k1iyb2q {
  d: path("M13.304 4.91c0-.153.183-.231.293-.125l.155.148a.162.162 0 0 0 .274-.117v-.17c0-.344.179-.665.472-.846l.18-.112a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.133l.096-.079a.129.129 0 0 1 .21.1v.334a1.154 1.154 0 0 1-2.308-.053z");
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

.onmhnc-bl {
  d: path("M15.167 19.606h-1.17v6.57h1.17z");
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.oyh5fnr6n {
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.p4lxhnbhm {
  stop-color: var(--svg-color--c78277, #C78277);
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

.ps-ob4bcl {
  cx: 9.731px;
  cy: 10.784px;
  r: 1.071px;
  fill: var(--svg-color--b87567, #B87567);
}

.pst71hbtq {
  cx: 9.731px;
  cy: 10.784px;
  r: 1.669px;
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q4_8l7b4h {
  stop-color: var(--svg-color--ce918f, #CE918F);
  stop-opacity: 0;
}

.q5fn77b2q {
  cx: 12.023px;
  cy: 10.006px;
  rx: 0.389px;
  ry: 0.197px;
}

.q64_sbv3d {
  d: path("M12.292 9.625a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.q99qvquze {
  d: path("M9.624 7.946h-.907q-.161 0-.322.02c.098.497.322 1.419.428 1.754c.112.356.475.46.621.468c-.015-.32-.065-1.1-.065-1.556c0-.356.13-.574.245-.686");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.re3g0rbfm {
  d: path("M13.277 16.934v1.698c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.017");
}

.recb7tbvt {
  d: path("M17.247 6.972h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
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

.scue_6bjb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.593 9.813c.064.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.t0fmjbosy {
  stop-color: var(--svg-color--d09185, #D09185);
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

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.ug2jj9grv {
  stop-color: var(--svg-color--160508, #160508);
}

.uny36og2t {
  stop-color: var(--svg-color--ecb3a7, #ECB3A7);
  stop-opacity: 0;
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v5pkyqbhx {
  d: path("M20.885 7.332H8.29v-.377c0-2.734 2.01-4.928 5.02-4.928h2.411c3.329 0 5.165 2.194 5.165 4.928z");
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

.vwc2t-btp {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.473c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.vwqp4fbhy {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m18.197 8.064l-.003-.002l-.004-.003l-.012-.01a2 2 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.83 2.83 0 0 0-1.492-.158a.534.534 0 1 0 .166 1.054c.398-.063.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vylrb5bvm {
  d: path("M21.577 17.982v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w3r29wbuy {
  stop-color: var(--svg-color--bc7a66, #BC7A66);
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.wuxqmhyhn {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m10.705 8.064l.002-.002l.005-.003l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.24-.14.42-.211a2.83 2.83 0 0 1 1.492-.158a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.678-.824");
}

.x30l93ibt {
  d: path("M22.174 7.973H7.152c-.395.32-.78 1.336-1.163 1.656v1.344c0 4.69 3.854 8.5 8.598 8.5s8.598-3.81 8.598-8.5V9.629c-.354-.42-.687-1.206-1.011-1.656");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x71f8xalx {
  d: path("M9.32 8.733c0-.403.103-.8.367-1.062c.268-.213.492-.378.492-.698V6.12c0-.267.16-.48.429-.534c.643-.16 1.984-.426 3.915-.426c1.93 0 3.272.266 3.915.426c.215.054.43.267.43.534v.853c0 .32.16.64.375.853c.502.352.47.545.429.96c-.18 1.791-.234 3.601-.355 5.398c-.16 1.77-1.552 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002c-.14-1.816-.2-3.638-.367-5.451");
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.x9k51rhux {
  stop-color: var(--svg-color--dfa89b, #DFA89B);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xsc4fpbic {
  stop-color: var(--svg-color--ffd5bc, #FFD5BC);
}

.y0ttzg77n {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.085 9.353c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.37-1.127");
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

.yqlu5g-5f {
  fill: var(--svg-color--e7ad99, #E7AD99);
  d: path("m14.096 10.498l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.115-.376-.646-.376-.765 0");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z1374kqmn {
  stop-color: var(--svg-color--9b0831, #9B0831);
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
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
