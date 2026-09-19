<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imm9xWB)"><path fill="url(#i4a0pNb)" class="x30l93ibt"/><path fill="url(#iTDnx1x)" class="x30l93ibt"/></g><path class="vwc2t-btp"/><path fill="url(#i6KAjab)" class="kngw6fbep"/><path fill="url(#i2gSgbe)" class="kngw6fbep"/><path fill="url(#idcBZkt)" class="kngw6fbep"/><path fill="url(#iiLw8Vb)" class="kngw6fbep"/><path fill="url(#ilGajNb)" class="kngw6fbep"/><path fill="url(#isZrtzc)" class="kngw6fbep"/><path fill="url(#iJkm9gA)" class="ajcn8-ycn"/><path fill="url(#ih3vBxb)" class="ajcn8-ycn"/><path fill="url(#i9JMave)" class="ajcn8-ycn"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#iAOYtlU)" class="vylrb5bvm"/><path fill="url(#iWkx0Sd)" class="d7c3-bbbw"/><g filter="url(#iVSbOde)"><path clip-rule="evenodd" class="gt7tt_rsi"/><path fill="url(#irUvMbp)" clip-rule="evenodd" class="tdhq60bqp"/><path fill="url(#iSuBe6b)" clip-rule="evenodd" class="tdhq60bqp"/></g><path fill="url(#iU4Plhc)" class="v-7fbqiwn"/><path fill="url(#ifQNUod)" class="v-7fbqiwn"/><g filter="url(#itnKU2c)"><path fill="url(#icL13gd)" class="v-7fbqiwn"/></g><circle fill="url(#i71SLFS)" class="jbixgesah"/><g filter="url(#iKlKkQb)"><circle class="xb-c7jilg"/></g><circle fill="url(#iMDPaMc)" class="uvhdvfbmh"/><circle fill="url(#idHVJ6c)" class="uvhdvfbmh"/><g filter="url(#in4zCDd)"><circle class="wznbhob5j"/></g><path fill="url(#ixfa7nc)" class="kg_ah4w1q"/><path fill="url(#iqyWshb)" class="kg_ah4w1q"/><path fill="url(#iXQAonb)" class="kg_ah4w1q"/><path fill="url(#iWH2sCb)" class="kg_ah4w1q"/><path fill="url(#ip2OVeN)" class="kg_ah4w1q"/><path fill="url(#i55gyQe)" class="kg_ah4w1q"/><g filter="url(#i6X27Ub)"><path class="ci-yn6b8i"/></g><g filter="url(#iJwsggm)"><path class="lkvpgob_n"/><path fill="url(#ioW7TfY)" class="mumxiu16p"/><path fill="url(#iMloO4c)" class="mumxiu16p"/><path fill="url(#iWa2YyQ)" class="mumxiu16p"/></g><g filter="url(#igJS7Od)"><path stroke="url(#i2C1Kqb)" class="k0j80l38k"/></g><path class="q4ty4rhwj"/><path class="d79i09dfb"/><path fill="url(#iInlggc)" class="v1xeb3neu"/><path class="n-9q5vkqg"/><g filter="url(#ihaEE6c)"><path class="bty98gm6l"/><path fill="url(#ixsn22b)" class="io_ux2bcs"/></g><g filter="url(#iuJDhRb)"><path fill="url(#iBYIHlc)" class="pptca-h0h"/></g><path class="oxf_pl82d"/><path fill="url(#isUuQeb)" class="l_riambzn"/><path class="r_v9oydre"/><g filter="url(#ia6KcTX)"><path fill="url(#ilUvyPc)" class="pa4nvpghp"/></g><g filter="url(#iIMXhpb)"><ellipse transform="rotate(-27.914 11.99 9.96)" class="mszlh36tq"/><ellipse fill="url(#imhJ7YS)" transform="rotate(-27.914 11.99 9.96)" class="w13jybbsq"/></g><path fill="url(#i1DR6hc)" clip-rule="evenodd" class="m1rzdpbiv"/><path fill="url(#iD3o5Ud)" clip-rule="evenodd" class="m1rzdpbiv"/><path fill="url(#i1MCPgd)" clip-rule="evenodd" class="y1f-7o94n"/><path fill="url(#iHZvJfc)" class="v5pkyqbhx"/><path fill="url(#ih5nvHe)" class="v5pkyqbhx"/><path fill="url(#izHz1gd)" class="v5pkyqbhx"/><path fill="url(#iEsU6Jd)" class="v5pkyqbhx"/><path fill="url(#ia6hdgb)" class="v5pkyqbhx"/><path class="d6l_zva3n"/><path fill="url(#inGX0Oc)" class="u_wc6ubhb"/><path fill="url(#iiH6veK)" class="u_wc6ubhb"/><path fill="url(#iUnDHVd)" class="u_wc6ubhb"/><path fill="url(#iN2yeVc)" class="u_wc6ubhb"/><path fill="url(#ivHTDTb)" class="n0jhourch"/><path fill="url(#izpcbVd)" class="n0jhourch"/><path fill="url(#iZ6eZGb)" class="n0jhourch"/><path fill="url(#ibPujte)" class="n0jhourch"/><path fill="url(#i6qz0xW)" class="n0jhourch"/><path fill="url(#ij2mDJd)" class="w_8w8wqmn"/><path fill="url(#ij0qnyb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#i7LoJxc)"><path fill="url(#iKGw4kt)" class="qv2uf3bxt"/><path fill="url(#iyoBo3i)" class="qv2uf3bxt"/></g><g filter="url(#i6UKCWo)"><path fill="url(#ibeddjd)" class="alecchcgl"/><path fill="url(#iO3rDAc)" class="alecchcgl"/></g><path fill="url(#iiVeO6c)" class="alecchcgl"/><path fill="url(#iZmNjZb)" class="alecchcgl"/><g filter="url(#ils9wMe)"><path fill="url(#i5b1ojc)" class="tecr5lbix"/><path fill="url(#ifSfzbe)" class="tecr5lbix"/><path fill="url(#ih6dC9c)" class="tecr5lbix"/></g><g filter="url(#ia4k1CS)"><path fill="url(#ibijqYb)" class="sqzh_k23r"/><path fill="url(#iyoK4Kd)" class="sqzh_k23r"/><path fill="url(#iJhoPse)" class="sqzh_k23r"/></g><g filter="url(#i121Mnd)"><path fill="url(#i9kTuLc)" class="blrgxt24s"/></g><g filter="url(#iYnFRxb)"><path stroke="url(#i2bdjSd)" class="cj_ualb6i"/></g><g filter="url(#izThGeM)"><path class="q0t430bzp"/></g><path fill="url(#i2TQtpc)" class="koh3jd58k"/><path fill="url(#ijWMLJc)" class="koh3jd58k"/><path fill="url(#i2I3Uuc)" class="koh3jd58k"/><path class="i8r5dkbus"/><path fill="url(#ijNsBMn)" class="a5_k978_n"/><path fill="url(#iecOWcY)" class="a5_k978_n"/><defs><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="ilGajNb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.723)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="i9JMave" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.973)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iAOYtlU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.972)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="irUvMbp" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.067)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iSuBe6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.19 16.067)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="ifQNUod" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.993 16.065)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i71SLFS" cx="0" cy="0" r="1" gradientTransform="rotate(86.855 -.678 9.471)scale(2.84821 4.98439)" gradientUnits="userSpaceOnUse"><stop class="g6podkbco"/><stop offset=".536" class="bxkzb2beb"/></radialGradient><radialGradient id="iMDPaMc" cx="0" cy="0" r="1" gradientTransform="rotate(-165.964 10.984 4.233)scale(1.35289 2.75126)" gradientUnits="userSpaceOnUse"><stop class="rd-m2i2bn"/><stop offset=".782" class="ne18elbjn"/></radialGradient><radialGradient id="idHVJ6c" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 -1.501 1.9497 1.5425 19.379 10.802)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="en0j-sbjf"/><stop offset=".961" class="dvj9jyboy"/></radialGradient><radialGradient id="iXQAonb" cx="0" cy="0" r="1" gradientTransform="rotate(91.34 3.037 12.024)scale(8.23663 9.40473)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="l58-idrcp"/><stop offset=".977" class="rqbrdobsx"/></radialGradient><radialGradient id="iWH2sCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 16.793 9.529)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="ip2OVeN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 12.23 9.495)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="i55gyQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.84375 12.7691 0 14.473 15.503)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="xr94fpbjz"/><stop offset="1" class="v-0ghsbuy"/></radialGradient><radialGradient id="i2C1Kqb" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 14.36 14.643)" gradientUnits="userSpaceOnUse"><stop class="vd6lhiblw"/><stop offset="1" class="hhmgxzb0s"/></radialGradient><radialGradient id="iInlggc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 16.628 10.39)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ixsn22b" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 16.399 10.142)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isUuQeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 12.26 10.39)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imhJ7YS" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.045 -.756)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1DR6hc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13281 -.6797 .40929 -.68214 18.003 8.518)" gradientUnits="userSpaceOnUse"><stop class="sm2p8u18a"/><stop offset=".657" class="tluei0bbw"/></radialGradient><radialGradient id="i1MCPgd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3042 -.875 .5993 .89326 10.714 8.715)" gradientUnits="userSpaceOnUse"><stop class="sm2p8u18a"/><stop offset=".604" class="lwjuacbxy"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iEsU6Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.097)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iN2yeVc" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.768 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="ij0qnyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.756)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iO3rDAc" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.635)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iiVeO6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.394)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iZmNjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.332)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iyoK4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.504)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="i2TQtpc" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 1.65625 -1.09255 .2886 8.675 8.894)" gradientUnits="userSpaceOnUse"><stop class="fbj1mms2k"/><stop offset=".734" class="fc74jabcz"/></radialGradient><radialGradient id="ijWMLJc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.146 5.924 3.475)scale(2.10677 3.44117)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="vra7cdb7z"/><stop offset="1" class="gqx1nybrz"/></radialGradient><radialGradient id="i2I3Uuc" cx="0" cy="0" r="1" gradientTransform="rotate(88.843 .425 9.073)scale(1.54719 .39574)" gradientUnits="userSpaceOnUse"><stop class="mcbmpe11u"/><stop offset="1" class="f77xcmb4e"/></radialGradient><radialGradient id="ijNsBMn" cx="0" cy="0" r="1" gradientTransform="matrix(1.83765 -.51563 .7529 2.68328 18.753 8.816)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="p_e5w6-mj"/><stop offset=".993" class="tmkwbhbat"/></radialGradient><radialGradient id="iecOWcY" cx="0" cy="0" r="1" gradientTransform="matrix(-.03907 1.21875 -.3512 -.01126 19.441 8.84)" gradientUnits="userSpaceOnUse"><stop class="esclzxbcw"/><stop offset="1" class="iq7hgmb8a"/></radialGradient><linearGradient id="i4a0pNb" x1="14.587" x2="14.587" y1="7.973" y2="19.473" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iTDnx1x" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iWkx0Sd" x1="15.654" x2="15.654" y1="15.025" y2="21.362" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iU4Plhc" x1="13.277" x2="13.489" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="ixfa7nc" x1="18.484" x2="10.84" y1="11.191" y2="12.331" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iqyWshb" x1="9.043" x2="11.358" y1="13.89" y2="13.588" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="ioW7TfY" x1="13.579" x2="14.518" y1="11.767" y2="11.767" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iMloO4c" x1="15.384" x2="14.357" y1="12.089" y2="12.075" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iWa2YyQ" x1="14.639" x2="14.639" y1="12.832" y2="12.259" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iBYIHlc" x1="17.406" x2="17.092" y1="10.111" y2="10.304" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilUvyPc" x1="13.005" x2="12.691" y1="10.111" y2="10.304" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iD3o5Ud" x1="15.613" x2="16.675" y1="8.379" y2="7.957" gradientUnits="userSpaceOnUse"><stop class="u1t0ebb0v"/><stop offset="1" class="u_-9job_j"/></linearGradient><linearGradient id="ih5nvHe" x1="10.646" x2="16.989" y1="6.722" y2="6.722" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="iiH6veK" x1="14.592" x2="14.592" y1="30.316" y2="28.723" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iUnDHVd" x1="14.592" x2="14.592" y1="26.172" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="ivHTDTb" x1="14.582" x2="14.582" y1="6.973" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="ij2mDJd" x1="14.582" x2="14.582" y1="19.605" y2="26.176" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="ibeddjd" x1="22.021" x2="18.333" y1="16.754" y2="29.972" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="i2bdjSd" x1="18.689" x2="20.193" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="imm9xWB" width="17.197" height="11.9" x="5.989" y="7.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2603"/></filter><filter id="iVSbOde" width="6.88" height="3.666" x="11.157" y="15.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2603"/></filter><filter id="itnKU2c" width="4.97" height="3.828" x="13.277" y="15.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2603"/></filter><filter id="iKlKkQb" width="2.492" height="2.492" x="8.446" y="9.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".125"/></filter><filter id="in4zCDd" width="2.492" height="2.492" x="17.968" y="9.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".125"/></filter><filter id="i6X27Ub" width="3.262" height="4.184" x="12.574" y="9.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".375"/></filter><filter id="iJwsggm" width="2.279" height="3.084" x="13.305" y="9.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".1"/></filter><filter id="igJS7Od" width="3.621" height="1.474" x="12.634" y="13.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".05"/></filter><filter id="ihaEE6c" width=".787" height=".697" x="15.893" y="9.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".05"/></filter><filter id="iuJDhRb" width=".892" height=".914" x="16.734" y="9.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".1"/></filter><filter id="ia6KcTX" width=".987" height="1.041" x="12.288" y="9.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".1"/></filter><filter id="iIMXhpb" width=".914" height=".705" x="11.532" y="9.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".05"/></filter><filter id="i7LoJxc" width="5.52" height="4.05" x="11.827" y="3.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2603"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2603" result="effect2_innerShadow_4002_2603"/></filter><filter id="i6UKCWo" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2603"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2603" result="effect2_innerShadow_4002_2603"/></filter><filter id="ils9wMe" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2603"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2603" result="effect2_innerShadow_4002_2603"/></filter><filter id="ia4k1CS" width="4.557" height="7.476" x="23.816" y="17.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2603"/></filter><filter id="i121Mnd" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2603"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2603" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2603"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2603" result="effect3_innerShadow_4002_2603"/></filter><filter id="iYnFRxb" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".125"/></filter><filter id="izThGeM" width="2.769" height="7.081" x="18.396" y="23.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2603" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-firefighter" /></template>
<style>
.a5_k978_n {
  d: path("M19.358 7.973h1.233a24 24 0 0 1-.432 1.773c-.112.356-.455.457-.601.465c.016-.32.045-1.097.045-1.553c0-.356-.13-.573-.245-.685");
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.ajcn8-ycn {
  d: path("M7.607 29.973V17.97a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.alecchcgl {
  d: path("m22.636 16.137l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.211a.53.53 0 0 0-.368-.624");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.blrgxt24s {
  d: path("M13.304 4.91c0-.153.183-.231.293-.125l.155.148a.162.162 0 0 0 .274-.117v-.17c0-.344.179-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.129.129 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.052z");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.bty98gm6l {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.564 9.768c.064.085-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.086.007-.246.158-.36c.151-.112.326-.135.39-.05");
}

.bxkzb2beb {
  stop-color: var(--svg-color--d3842e, #D3842E);
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.ci-yn6b8i {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.169 10.595l-.822 1.7c-.101.35.143.7.49.7h.737c.346 0 .59-.355.489-.7l-.5-1.7c-.106-.377-.282-.377-.394 0");
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

.d6l_zva3n {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.d79i09dfb {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.837 9.308c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.341h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.129");
}

.d7c3-bbbw {
  d: path("M13.277 15.973v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
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

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dvj9jyboy {
  stop-color: var(--svg-color--c47408, #C47408);
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.en0j-sbjf {
  stop-color: var(--svg-color--c47408, #C47408);
  stop-opacity: 0;
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.esclzxbcw {
  stop-color: var(--svg-color--9b4001, #9B4001);
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f77xcmb4e {
  stop-color: var(--svg-color--933901, #933901);
  stop-opacity: 0;
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fbj1mms2k {
  stop-color: var(--svg-color--bb6d28, #BB6D28);
}

.fc74jabcz {
  stop-color: var(--svg-color--c25f14, #C25F14);
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

.g6podkbco {
  stop-color: var(--svg-color--b25a06, #B25A06);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gqx1nybrz {
  stop-color: var(--svg-color--913a0b, #913A0B);
}

.gt7tt_rsi {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.157 16.067v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.95 3.95 0 0 1-2.488.879h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hhmgxzb0s {
  stop-color: var(--svg-color--ffb334, #FFB334);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.i8r5dkbus {
  fill: var(--svg-color--da8719, #DA8719);
  d: path("M19.358 7.973h1.233a24 24 0 0 1-.432 1.773c-.112.356-.455.457-.601.465c.016-.32.045-1.097.045-1.553c0-.356-.13-.573-.245-.685");
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.io_ux2bcs {
  d: path("M16.564 9.768c.064.085-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.086.007-.246.158-.36c.151-.112.326-.135.39-.05");
}

.iq7hgmb8a {
  stop-color: var(--svg-color--b85a08, #B85A08);
  stop-opacity: 0;
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
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

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k0j80l38k {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.444 13.76c-.508 0-.985-.12-1.386-.328c-.137-.07-.285.084-.198.209c.335.508.919.846 1.584.846s1.25-.338 1.585-.846c.086-.13-.061-.279-.198-.21c-.402.21-.874.33-1.387.33Z");
}

.kg_ah4w1q {
  d: path("M9.34 10.188a30 30 0 0 1-.059-1.44c0-.65.18-.68.445-.944c.268-.213.414-.497.414-.817v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.987-.427 3.92-.427s3.275.267 3.919.427c.215.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.472.546.43.96c-.013.13-.054 1.197-.09 1.442l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.213c-1.714 0-3.053-1.234-3.214-3.006z");
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

.koh3jd58k {
  d: path("M9.566 7.973h-.908q-.16 0-.321.02c.098.497.322 1.418.428 1.753a.67.67 0 0 0 .578.469c-.016-.32-.022-1.1-.022-1.557c0-.356.13-.573.245-.685");
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

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l_riambzn {
  d: path("M12.259 9.58a.893.893 0 0 0-.861 1.128h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
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

.lkvpgob_n {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m14.062 10.431l-.532 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.376-.646-.376-.765 0");
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwjuacbxy {
  stop-color: var(--svg-color--862b2f, #862B2F);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m1rzdpbiv {
  fill-rule: evenodd;
  d: path("M16.226 8.42c.72-.068 1.182.214 1.294.317a.473.473 0 1 0 .641-.695c-.306-.283-1.032-.656-2.023-.564a.473.473 0 1 0 .088.942");
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mcbmpe11u {
  stop-color: var(--svg-color--933901, #933901);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mszlh36tq {
  cx: 11.989px;
  cy: 9.961px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.mumxiu16p {
  d: path("m14.062 10.431l-.532 1.702a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.702c-.114-.376-.646-.376-.765 0");
}

.n-9q5vkqg {
  fill: var(--svg-color--000, #000);
  d: path("M16.118 10.473a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.235");
}

.n0jhourch {
  d: path("M8.659 7.973h11.846c.95 0 1.99.484 1.99 2.68h.69V9.348c0-1.43-.847-2.375-2.456-2.375H8.435c-1.609 0-2.456.945-2.456 2.375v1.304h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.ne18elbjn {
  stop-color: var(--svg-color--ea9337, #EA9337);
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

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
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

.oxf_pl82d {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.052 9.307c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.232a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.p_e5w6-mj {
  stop-color: var(--svg-color--a3460d, #A3460D);
  stop-opacity: 0;
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pa4nvpghp {
  d: path("M13.075 10.367c0-.288-.235-.48-.299-.539l-.288.28l.177.36z");
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

.pptca-h0h {
  d: path("M17.425 10.355a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q0t430bzp {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.629c0-.2 1.146-4.104 1.719-6.032");
}

.q4ty4rhwj {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M14.444 13.76c-.508 0-.985-.12-1.386-.328c-.137-.07-.285.084-.198.209c.335.508.919.846 1.584.846s1.25-.338 1.585-.846c.086-.13-.061-.279-.198-.21c-.402.21-.874.33-1.387.33");
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qv2uf3bxt {
  d: path("M17.247 6.973h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_v9oydre {
  fill: var(--svg-color--000, #000);
  d: path("M12.77 10.472a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.rd-m2i2bn {
  stop-color: var(--svg-color--fdbf39, #FDBF39);
}

.rqbrdobsx {
  stop-color: var(--svg-color--da6647, #DA6647);
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
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

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.sm2p8u18a {
  stop-color: var(--svg-color--9e5243, #9E5243);
}

.sqzh_k23r {
  d: path("M25.649 18.01a3.5 3.5 0 0 0 .85-.17l.148-.055c.179-.063.401-.054.555.107c1.071 1.125 1.43 2.621.983 4.236s-1.732 2.764-2.98 3.033c-.084.02-.348.046-.505-.157l-.142-.14a3.5 3.5 0 0 0-.642-.589c1.567-.052 2.817-1.084 3.203-2.529c.39-1.469-.236-3.003-1.472-3.735z");
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

.tdhq60bqp {
  fill-rule: evenodd;
  d: path("M11.157 16.067v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.95 3.95 0 0 1-2.488.879h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.tecr5lbix {
  d: path("m20.012 16.732l4.416 1.16a3.56 3.56 0 0 0 2.071-.053l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.621.983 4.236s-1.732 2.764-2.98 3.033c-.084.02-.348.046-.505-.157l-.142-.14a3.5 3.5 0 0 0-1.745-1.112L18.57 22.55a.61.61 0 0 1-.43-.779l1.25-4.675c.045-.22.37-.43.622-.364");
}

.tluei0bbw {
  stop-color: var(--svg-color--901d11, #901D11);
}

.tmkwbhbat {
  stop-color: var(--svg-color--a3460d, #A3460D);
}

.u_-9job_j {
  stop-color: var(--svg-color--8c3025, #8C3025);
  stop-opacity: 0;
}

.u_wc6ubhb {
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.u1t0ebb0v {
  stop-color: var(--svg-color--8c3025, #8C3025);
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.uvhdvfbmh {
  cx: 19.214px;
  cy: 10.802px;
  r: 1.671px;
}

.v-0ghsbuy {
  stop-color: var(--svg-color--d6772a, #D6772A);
}

.v-7fbqiwn {
  d: path("M13.277 16.934v1.699c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.018");
}

.v1xeb3neu {
  d: path("M16.63 9.58a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.v5pkyqbhx {
  d: path("M20.885 7.332H8.29v-.377c0-2.734 2.01-4.928 5.02-4.928h2.411c3.329 0 5.165 2.194 5.165 4.928z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vd6lhiblw {
  stop-color: var(--svg-color--ffb334, #FFB334);
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

.vra7cdb7z {
  stop-color: var(--svg-color--913a0b, #913A0B);
  stop-opacity: 0;
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vwc2t-btp {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.473c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
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

.w13jybbsq {
  cx: 11.989px;
  cy: 9.961px;
  rx: 0.39px;
  ry: 0.197px;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.wznbhob5j {
  cx: 19.214px;
  cy: 10.802px;
  r: 0.996px;
  fill: var(--svg-color--e9982b, #E9982B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x30l93ibt {
  d: path("M22.174 7.973H7.152c-.395.32-.78 1.336-1.163 1.656v1.344c0 4.69 3.854 8.5 8.598 8.5s8.598-3.81 8.598-8.5V9.629c-.354-.42-.687-1.206-1.011-1.656");
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xb-c7jilg {
  cx: 9.692px;
  cy: 10.802px;
  r: 0.996px;
  fill: var(--svg-color--d17026, #D17026);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xr94fpbjz {
  stop-color: var(--svg-color--d6772a, #D6772A);
  stop-opacity: 0;
}

.y1f-7o94n {
  fill-rule: evenodd;
  d: path("M12.663 8.42c-.72-.068-1.183.214-1.295.317a.473.473 0 1 1-.64-.695c.306-.283 1.032-.656 2.023-.564a.473.473 0 1 1-.088.942");
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
