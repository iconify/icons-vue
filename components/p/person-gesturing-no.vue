<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iKNXgRb)" class="e5ucantjx"/><path fill="url(#ispKzFQ)" class="e5ucantjx"/><path fill="url(#iIV2XKe)" class="a6yq75bbi"/><path fill="url(#iKU2nzb)" class="a6yq75bbi"/><g filter="url(#i1tz0qy)"><path fill="url(#iJHT9qA)" class="omftgvbac"/><path fill="url(#iej63Oe)" class="omftgvbac"/><path fill="url(#iJPjlLd)" class="omftgvbac"/></g><path fill="url(#iVgJHbe)" class="omftgvbac"/><g filter="url(#iRpejld)"><path class="f218l_29x"/></g><g filter="url(#i8Ltfnc)"><path fill="url(#i1pxKbb)" class="ofx_u9bwq"/><path fill="url(#idJPBGc)" class="ofx_u9bwq"/><path fill="url(#iluf7up)" class="ofx_u9bwq"/><path fill="url(#iFT7N7d)" class="ofx_u9bwq"/></g><g filter="url(#iVRKkRb)"><path fill="url(#iFLogMb)" class="dx6yu9cnd"/><path fill="url(#iJdZS0d)" class="dx6yu9cnd"/><path fill="url(#iOFAauc)" class="dx6yu9cnd"/><path fill="url(#i8uREZc)" class="dx6yu9cnd"/><path fill="url(#iQLtuZN)" class="dx6yu9cnd"/></g><g filter="url(#ihMeXed)"><path fill="url(#iQTWI3c)" class="rbbulnz3l"/><path fill="url(#iJ1j01c)" class="rbbulnz3l"/><path fill="url(#iS5NSXb)" class="rbbulnz3l"/></g><g filter="url(#i1qZF1b)"><path fill="url(#ivrrehb)" class="t-faq4izi"/><path fill="url(#iXewY5c)" class="t-faq4izi"/><path fill="url(#iRRhtUd)" class="t-faq4izi"/><path fill="url(#irQy0kb)" class="t-faq4izi"/><path fill="url(#isV5vFc)" class="t-faq4izi"/></g><path class="utrmehb1k"/><path fill="url(#iQ8et0b)" class="cswzjcx6u"/><path class="iitgd8bac"/><g filter="url(#iiVkJGb)"><path class="dodqfog5q"/><path fill="url(#i9QUMfK)" class="nsn8oes0z"/></g><g filter="url(#isIyooc)"><path fill="url(#iKnUjve)" class="t0_upib5g"/></g><path class="ub8ckabiz"/><path fill="url(#ixoNLpp)" class="fqu12ubrd"/><path class="ebo5c_0lf"/><g filter="url(#iNuAy1d)"><path fill="url(#i7aVE8b)" class="q5hvggldb"/></g><g filter="url(#iHnnxSb)"><ellipse transform="rotate(-27.914 12.844 12.236)" class="z-qcyfbze"/><ellipse fill="url(#i8Ldsle)" transform="rotate(-27.914 12.844 12.236)" class="a3xscqbym"/></g><path fill="url(#iGW9MMd)" class="nl8aomm7e"/><path fill="url(#iTuv2Pg)" class="nl8aomm7e"/><path fill="url(#iDVYzIA)" class="nl8aomm7e"/><path fill="url(#iVb0NGd)" class="kxyn74b4t"/><path fill="url(#iy0nTpe)" class="kxyn74b4t"/><g filter="url(#iTse87c)"><path class="ni7x8ub6k"/></g><g filter="url(#ij7q6bf)"><path class="b5gjqgblt"/></g><g filter="url(#iz69Blc)"><path class="p6wren0yi"/></g><g filter="url(#itodgdd)"><path class="ib1gbs4nx"/></g><g filter="url(#ib4FTNp)"><path stroke="url(#i2lvXPc)" class="gspwrdz1o"/></g><g filter="url(#iO9R0Ck)"><path stroke="url(#iEeavxd)" class="wq0eljlkx"/></g><path class="q9rihsbeb"/><path class="w73iq3bud"/><path fill="url(#iY2ScGe)" class="akki1obxr"/><path fill="url(#inirSwb)" class="akki1obxr"/><path fill="url(#iMsUfGe)" class="u4cp3820t"/><path fill="url(#ihqOLGc)" class="cuomu7bqz"/><path fill="url(#iRbdh4d)" class="cuomu7bqz"/><path fill="url(#i16tupc)" class="cuomu7bqz"/><path fill="url(#isBeo5c)" class="cuomu7bqz"/><path fill="url(#izAvOPb)" class="cuomu7bqz"/><path fill="url(#igdf08b)" class="cuomu7bqz"/><path fill="url(#iiwVwQd)" class="twmiqpbxq"/><path fill="url(#iDDcgbe)" class="v3eonib4h"/><path fill="url(#iwGAPQd)" class="v3eonib4h"/><path fill="url(#ixh7Cge)" class="v3eonib4h"/><path fill="url(#iiX2qvd)" class="zpwiheb_q"/><path fill="url(#isVvQHd)" class="zpwiheb_q"/><path fill="url(#irPGQbe)" class="zpwiheb_q"/><path fill="url(#irKow9P)" class="h44m83fgu"/><path fill="url(#iin2ozb)" class="h44m83fgu"/><path fill="url(#i0SEBCX)" class="h44m83fgu"/><path fill="url(#iYP67dc)" class="vzu9-mfnh"/><path fill="url(#iUNis5b)" class="vzu9-mfnh"/><path fill="url(#i7AaP6d)" class="vzu9-mfnh"/><path fill="url(#i8xMrud)" class="vzu9-mfnh"/><g filter="url(#iLDejSb)"><path fill="url(#idiiRye)" class="cw3sn1brq"/><path fill="url(#iOmrTLY)" class="cw3sn1brq"/></g><defs><radialGradient id="iKNXgRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.99022 4.06854 -4.83311 -1.1763 23.12 14.564)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="xitcw8bap"/><stop offset="1" class="v2o3hnbel"/></radialGradient><radialGradient id="ispKzFQ" cx="0" cy="0" r="1" gradientTransform="matrix(.37671 .51664 -.4389 .32002 22.162 14.909)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iIV2XKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.63603 3.44427 -1.56558 .74365 8.87 14.714)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iKU2nzb" cx="0" cy="0" r="1" gradientTransform="matrix(.409 1.28084 -1.12357 .35879 9.72 14.704)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="iJHT9qA" cx="0" cy="0" r="1" gradientTransform="matrix(-8.00181 0 0 -15.9952 20.889 13.355)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iej63Oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.81502 1.72114 0 13.629 11.723)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="jtctlkb6b"/><stop offset="1" class="t-jdupvjc"/></radialGradient><radialGradient id="iJPjlLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.72114 2.22184 0 19.262 11.504)" gradientUnits="userSpaceOnUse"><stop class="qqk1gqbrc"/><stop offset="1" class="hzdlx3ssk"/></radialGradient><radialGradient id="iJdZS0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.66544 8.26625 0 9.279 11.323)" gradientUnits="userSpaceOnUse"><stop class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iOFAauc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.66544 8.26625 0 22.238 11.323)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="i8uREZc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.17618 -1.59297 .84836 -2.2241 21.269 3.262)" gradientUnits="userSpaceOnUse"><stop class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="iQLtuZN" cx="0" cy="0" r="1" gradientTransform="matrix(1.16245 1.89434 -4.3864 2.69168 14.832 1.217)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iQTWI3c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.16578 1.70402 -.47427 -1.43776 16.32 3.07)" gradientUnits="userSpaceOnUse"><stop class="b6ai19bel"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iJ1j01c" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.84 -3.592)scale(7.74003 8.57516)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="iS5NSXb" cx="0" cy="0" r="1" gradientTransform="matrix(3.53775 -1.50951 .6345 1.48702 8.876 5.543)" gradientUnits="userSpaceOnUse"><stop class="b6ai19bel"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="ivrrehb" cx="0" cy="0" r="1" gradientTransform="matrix(4.3484 1.02848 -.39441 1.66757 20.644 4.56)" gradientUnits="userSpaceOnUse"><stop class="da8sh5f1a"/><stop offset="1" class="lguy1wbep"/></radialGradient><radialGradient id="iXewY5c" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 14.307 -1.266)scale(5.49916 3.06684)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iRRhtUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67906 -2.82842 2.02587 -1.20264 21.786 10.088)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="irQy0kb" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 10.815 3.515)scale(6.33753 6.85111)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="isV5vFc" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 8.643 9.683)scale(.51535 2.35612)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="iQ8et0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04198 -1.65739 0 18.798 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i9QUMfK" cx="0" cy="0" r="1" gradientTransform="matrix(-.29785 -.38382 .52843 -.41007 18.504 12.467)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixoNLpp" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04204 -1.65748 0 13.193 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8Ldsle" cx="0" cy="0" r="1" gradientTransform="matrix(-.00994 -.63455 .76277 -.01194 12.825 12.642)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTuv2Pg" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 2.921 20.555)scale(2.99201 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iDVYzIA" cx="0" cy="0" r="1" gradientTransform="matrix(1.01175 -1.38847 1.16382 .84805 22.388 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iy0nTpe" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 -.475 9.995)scale(2.71847 2.67251)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="iY2ScGe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.445)" gradientUnits="userSpaceOnUse"><stop class="prd44wbso"/><stop offset="1" class="c5khawelw"/></radialGradient><radialGradient id="inirSwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.227)" gradientUnits="userSpaceOnUse"><stop class="u1hhhxbfd"/><stop offset="1" class="cl_cdxbgs"/></radialGradient><radialGradient id="iMsUfGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 1.25 -2.6929 5.58776 8.406 17.32)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="vxb86i-rd"/><stop offset="1" class="rowsrjblg"/></radialGradient><radialGradient id="ihqOLGc" cx="0" cy="0" r="1" gradientTransform="matrix(17.51082 8.75543 -2.15289 4.30577 13.551 19.209)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="v3bwo4btz"/><stop offset="1" class="kd1_xhb_o"/></radialGradient><radialGradient id="iRbdh4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.944 11.543 15.187)scale(2.90693 2.17455)" gradientUnits="userSpaceOnUse"><stop class="cq9p23brg"/><stop offset="1" class="cwmsguygo"/></radialGradient><radialGradient id="i16tupc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11963 5.31578 -8.32746 -1.75396 14.245 17.692)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="w58mn6r_g"/><stop offset="1" class="xrn2z6b6u"/></radialGradient><radialGradient id="izAvOPb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.455 -3.07)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="mq0gl8bsz"/><stop offset="1" class="w-vsz3bnm"/></radialGradient><radialGradient id="iiwVwQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 .6475 -1.4343 -3.32276 24.094 18.195)" gradientUnits="userSpaceOnUse"><stop class="qxiqgebpn"/><stop offset="1" class="m_8hwoksz"/></radialGradient><radialGradient id="iDDcgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.883)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="jbd_cz55y"/><stop offset="1" class="m7o64xbbx"/></radialGradient><radialGradient id="iiX2qvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 .75001 -.6198 -1.21376 28.875 17.648)" gradientUnits="userSpaceOnUse"><stop class="x5ozldbku"/><stop offset=".697" class="wwlvfha4h"/></radialGradient><radialGradient id="irKow9P" cx="0" cy="0" r="1" gradientTransform="matrix(1.74664 .85478 -1.17534 2.40165 3.176 17.648)" gradientUnits="userSpaceOnUse"><stop class="xg7pvujwr"/><stop offset=".697" class="gltbvazww"/></radialGradient><radialGradient id="iYP67dc" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.294 6.356)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="di5a24oyc"/><stop offset="1" class="ln7fo96zz"/></radialGradient><radialGradient id="iUNis5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07812 .5625 -.60419 -1.15802 30 13.273)" gradientUnits="userSpaceOnUse"><stop class="y0na07-wu"/><stop offset="1" class="nshtk9bjl"/></radialGradient><radialGradient id="i7AaP6d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49999 1.70314 -.73757 -.64959 28.906 15.898)" gradientUnits="userSpaceOnUse"><stop offset=".282" class="xpv5cjbuo"/><stop offset="1" class="yk9k1_boe"/></radialGradient><linearGradient id="iVgJHbe" x1="22.619" x2="20.388" y1="14.696" y2="14.696" gradientUnits="userSpaceOnUse"><stop class="rf8_ys_es"/><stop offset="1" class="atqmnhbsn"/></linearGradient><linearGradient id="i1pxKbb" x1="15.995" x2="17.093" y1="14.419" y2="14.419" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="idJPBGc" x1="14.617" x2="15.997" y1="14.219" y2="14.296" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iluf7up" x1="15.995" x2="15.995" y1="14.931" y2="16.025" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="iFT7N7d" x1="15.995" x2="15.995" y1="12.045" y2="12.583" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iFLogMb" x1="22.884" x2="9.881" y1="6.082" y2="6.082" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iKnUjve" x1="19.798" x2="19.394" y1="12.429" y2="12.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7aVE8b" x1="14.148" x2="13.745" y1="12.428" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGW9MMd" x1="24.261" x2="22.711" y1="12.282" y2="15.077" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iVb0NGd" x1="8.482" x2="10.355" y1="13.185" y2="13.022" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="i2lvXPc" x1="14.505" x2="11.641" y1="9.06" y2="9.811" gradientUnits="userSpaceOnUse"><stop class="q_stynbcc"/><stop offset="1" class="amxgxcvbx"/></linearGradient><linearGradient id="iEeavxd" x1="17.594" x2="20.458" y1="9.06" y2="9.811" gradientUnits="userSpaceOnUse"><stop class="q_stynbcc"/><stop offset="1" class="amxgxcvbx"/></linearGradient><linearGradient id="isBeo5c" x1="9.156" x2="10.344" y1="18.508" y2="18.883" gradientUnits="userSpaceOnUse"><stop class="psrrqcksv"/><stop offset="1" class="rbkr51v-c"/></linearGradient><linearGradient id="igdf08b" x1="17.406" x2="17.906" y1="26.977" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="gd1of5hxe"/><stop offset="1" class="v1z821b6o"/></linearGradient><linearGradient id="iwGAPQd" x1="14.83" x2="14.461" y1="26.816" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="q9mg64b4e"/><stop offset="1" class="vzmhuwavr"/></linearGradient><linearGradient id="ixh7Cge" x1="22.827" x2="21.613" y1="18.819" y2="19.382" gradientUnits="userSpaceOnUse"><stop class="smo9u60ba"/><stop offset="1" class="ktas3sbvn"/></linearGradient><linearGradient id="isVvQHd" x1="27.945" x2="27.547" y1="19.531" y2="18.683" gradientUnits="userSpaceOnUse"><stop offset=".399" class="fmlt5vcjq"/><stop offset="1" class="jyrqxvbae"/></linearGradient><linearGradient id="irPGQbe" x1="26.75" x2="27.266" y1="17.398" y2="17.977" gradientUnits="userSpaceOnUse"><stop class="jhw3pwb_r"/><stop offset="1" class="q6hso6-yu"/></linearGradient><linearGradient id="iin2ozb" x1="4.106" x2="4.504" y1="19.531" y2="18.683" gradientUnits="userSpaceOnUse"><stop offset=".399" class="x8wetqqbt"/><stop offset="1" class="um2qp2-uc"/></linearGradient><linearGradient id="i0SEBCX" x1="5.301" x2="4.786" y1="17.398" y2="17.977" gradientUnits="userSpaceOnUse"><stop class="esmsrpb1o"/><stop offset="1" class="diy-71qna"/></linearGradient><linearGradient id="i8xMrud" x1="25.489" x2="25.997" y1="14.289" y2="15.189" gradientUnits="userSpaceOnUse"><stop class="r375w-bke"/><stop offset="1" class="nsk7h83lk"/></linearGradient><linearGradient id="idiiRye" x1="8" x2="4.375" y1="15.758" y2="20.008" gradientUnits="userSpaceOnUse"><stop offset=".206" class="y2jmkqeym"/><stop offset="1" class="srr6nlykd"/></linearGradient><linearGradient id="iOmrTLY" x1="6.232" x2="7.245" y1="20.618" y2="18.449" gradientUnits="userSpaceOnUse"><stop class="v69eygbez"/><stop offset="1" class="xg3e-vb_e"/></linearGradient><filter id="i1tz0qy" width="13.876" height="16.05" x="9.492" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24791"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24791" result="effect2_innerShadow_3987_24791"/></filter><filter id="iRpejld" width="4.411" height="5.725" x="13.524" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".5"/></filter><filter id="i8Ltfnc" width="2.611" height="3.925" x="14.69" y="11.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".05"/></filter><filter id="iVRKkRb" width="16.532" height="10.59" x="7.729" y="1.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24791"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24791" result="effect2_innerShadow_3987_24791"/></filter><filter id="ihMeXed" width="8.814" height="8.053" x="8.006" y="2.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.596078 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24791"/><feGaussianBlur result="effect2_foregroundBlur_3987_24791" stdDeviation=".25"/></filter><filter id="i1qZF1b" width="8.596" height="7.796" x="15.543" y="3.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".25"/></filter><filter id="iiVkJGb" width=".954" height=".837" x="17.883" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".05"/></filter><filter id="isIyooc" width="1.033" height="1.061" x="18.99" y="11.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".1"/></filter><filter id="iNuAy1d" width="1.153" height="1.222" x="13.284" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".1"/></filter><filter id="iHnnxSb" width="1.116" height=".848" x="12.286" y="11.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".05"/></filter><filter id="iTse87c" width="1.565" height="2.914" x="8.318" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".125"/></filter><filter id="ij7q6bf" width="1.716" height="2.944" x="22.117" y="11.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".125"/></filter><filter id="iz69Blc" width="2.884" height="1.34" x="11.376" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.219608 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24791"/></filter><filter id="itodgdd" width="2.884" height="1.34" x="17.939" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.219608 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24791"/></filter><filter id="ib4FTNp" width="2.717" height="1.234" x="11.486" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".125"/></filter><filter id="iO9R0Ck" width="2.717" height="1.234" x="17.896" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24791" stdDeviation=".125"/></filter><filter id="iLDejSb" width="7.3" height="8.016" x="2" y="12.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.564706 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24791"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-no" /></template>
<style>
.a3xscqbym {
  cx: 12.844px;
  cy: 12.236px;
  rx: 0.5px;
  ry: 0.253px;
}

.a6yq75bbi {
  d: path("M9.752 14.96a2.1 2.1 0 0 1-1.162-.396v1.195a2.79 2.79 0 0 0 1.722 2.593a5.3 5.3 0 0 1-.444-1.515z");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.akki1obxr {
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.amxgxcvbx {
  stop-color: var(--svg-color--db7e6a, #DB7E6A);
  stop-opacity: 0;
}

.atqmnhbsn {
  stop-color: var(--svg-color--ffda31, #FFDA31);
  stop-opacity: 0;
}

.b5gjqgblt {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M22.367 14.24q.076-1.221.142-2.444a1.227 1.227 0 0 1-.142 2.445");
}

.b6ai19bel {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.c5khawelw {
  stop-color: var(--svg-color--ff9540, #FF9540);
  stop-opacity: 0;
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl_cdxbgs {
  stop-color: var(--svg-color--e2632d, #E2632D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cq9p23brg {
  stop-color: var(--svg-color--ff7d48, #FF7D48);
}

.cswzjcx6u {
  d: path("M18.8 11.747a1.146 1.146 0 0 1 1.105 1.448H17.69a1.15 1.15 0 0 1 1.11-1.448");
}

.cuomu7bqz {
  d: path("m11.56 16.106l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.487a1 1 0 0 1-.483-1.34l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.cw3sn1brq {
  d: path("m9 16.078l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.cwmsguygo {
  stop-color: var(--svg-color--ff7d48, #FF7D48);
  stop-opacity: 0;
}

.da8sh5f1a {
  stop-color: var(--svg-color--ffe137, #FFE137);
}

.di5a24oyc {
  stop-color: var(--svg-color--ffda2a, #FFDA2A);
}

.diy-71qna {
  stop-color: var(--svg-color--c47f1c, #C47F1C);
  stop-opacity: 0;
}

.dodqfog5q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.dx6yu9cnd {
  d: path("M22.23 4.823c.66.228 1.253.69 1.628 1.35a3.04 3.04 0 0 1-.136 3.245a2 2 0 0 0-.348 1.123v1.526a2.2 2.2 0 0 0-.856-.345l.1-2.063a1.86 1.86 0 0 0-1.77-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34l.04 1.974c-.327.048-.667.157-.925.338v-1.541c0-.4-.123-.792-.348-1.123a3.07 3.07 0 0 1-.184-3.141a3 3 0 0 1 1.67-1.447a3.44 3.44 0 0 0 1.777-1.426a2.99 2.99 0 0 1 2.534-1.412c.416 0 .81.09 1.179.241c.49.214 1.042.214 1.532 0a3 3 0 0 1 1.172-.24c1.083 0 2.03.585 2.554 1.453a3.24 3.24 0 0 0 1.737 1.377");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e5ucantjx {
  d: path("M22.239 14.96c.43-.014.833-.16 1.161-.396v1.195a2.79 2.79 0 0 1-1.722 2.593c.219-.465.37-.973.444-1.515z");
}

.ebo5c_0lf {
  fill: var(--svg-color--000, #000);
  d: path("M13.847 12.893a.654.654 0 0 0-.657-.657a.654.654 0 0 0-.583.959h1.162a.65.65 0 0 0 .078-.302");
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.esmsrpb1o {
  stop-color: var(--svg-color--c47f1c, #C47F1C);
}

.f218l_29x {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.37 12.689l-.815 2.36c-.139.486.196.972.67.972h1.009c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.696-.524-.85 0");
}

.fmlt5vcjq {
  stop-color: var(--svg-color--e39546, #E39546);
}

.fqu12ubrd {
  d: path("M13.19 11.747a1.146 1.146 0 0 0-1.104 1.448H14.3q.04-.147.041-.302a1.154 1.154 0 0 0-1.15-1.147");
}

.ft5dv1b6b {
  fill: none;
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.gd1of5hxe {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gltbvazww {
  stop-color: var(--svg-color--df841b, #DF841B);
}

.gspwrdz1o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.76l2.017-.534");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h44m83fgu {
  d: path("M7.301 19.811a.885.885 0 0 0-.35-1.203L4.342 17.18a.899.899 0 1 0-.856 1.58l2.622 1.405A.885.885 0 0 0 7.3 19.81");
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.hzdlx3ssk {
  stop-color: var(--svg-color--ffb80a, #FFB80A);
  stop-opacity: 0;
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ib1gbs4nx {
  fill: var(--svg-color--c75c21, #C75C21);
  d: path("M20.711 9.94a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 0 0-.176.675l2.087.542a.35.35 0 0 0 .425-.249");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.iitgd8bac {
  fill: var(--svg-color--000, #000);
  d: path("M18.144 12.893c0-.365.291-.657.656-.657a.654.654 0 0 1 .584.959h-1.162a.6.6 0 0 1-.078-.302");
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jhw3pwb_r {
  stop-color: var(--svg-color--e9a71b, #E9A71B);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.jtctlkb6b {
  stop-color: var(--svg-color--f7941d, #F7941D);
}

.jyrqxvbae {
  stop-color: var(--svg-color--ffc128, #FFC128);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.kd1_xhb_o {
  stop-color: var(--svg-color--ff4c31, #FF4C31);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.ktas3sbvn {
  stop-color: var(--svg-color--ffa842, #FFA842);
  stop-opacity: 0;
}

.kxyn74b4t {
  d: path("M9.504 10.967a2.067 2.067 0 0 0 .178 4.11a100 100 0 0 1-.178-4.11");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lguy1wbep {
  stop-color: var(--svg-color--ffe137, #FFE137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln7fo96zz {
  stop-color: var(--svg-color--f5a227, #F5A227);
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.m_8hwoksz {
  stop-color: var(--svg-color--f54617, #F54617);
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.m7o64xbbx {
  stop-color: var(--svg-color--ff4923, #FF4923);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mq0gl8bsz {
  stop-color: var(--svg-color--e4764e, #E4764E);
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ni7x8ub6k {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M9.526 11.817a1.228 1.228 0 0 0 .107 2.413a100 100 0 0 1-.107-2.413");
}

.nl8aomm7e {
  d: path("M22.316 15.077q.129-2.05.237-4.099a2.067 2.067 0 0 1-.237 4.099");
}

.nshtk9bjl {
  stop-color: var(--svg-color--ffe032, #FFE032);
  stop-opacity: 0;
}

.nsk7h83lk {
  stop-color: var(--svg-color--eaac25, #EAAC25);
  stop-opacity: 0;
}

.nsn8oes0z {
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofx_u9bwq {
  d: path("m15.504 12.437l-.682 2.361c-.14.486.195.971.668.971h1.01c.474 0 .808-.493.669-.971l-.683-2.361c-.146-.523-.829-.523-.982 0");
}

.omftgvbac {
  d: path("M9.798 16.906a5.03 5.03 0 0 0 4.99 4.374h2.424a5.03 5.03 0 0 0 4.99-4.374c.152-2.42.304-4.829.417-7.247a1.86 1.86 0 0 0-1.771-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34c0 2.39.15 4.74.306 7.136");
}

.p6wren0yi {
  fill: var(--svg-color--c75c21, #C75C21);
  d: path("M11.388 9.94a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 1 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.prd44wbso {
  stop-color: var(--svg-color--ff9540, #FF9540);
}

.psrrqcksv {
  stop-color: var(--svg-color--ff730a, #FF730A);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q_stynbcc {
  stop-color: var(--svg-color--db7e6a, #DB7E6A);
}

.q5hvggldb {
  d: path("M14.237 12.758c0-.37-.3-.617-.382-.692l-.37.358l.227.464z");
}

.q6hso6-yu {
  stop-color: var(--svg-color--e9a71b, #E9A71B);
  stop-opacity: 0;
}

.q9mg64b4e {
  stop-color: var(--svg-color--f35e74, #F35E74);
}

.q9rihsbeb {
  fill: var(--svg-color--88014d, #88014D);
  d: path("M15.989 19.458c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
}

.qqk1gqbrc {
  stop-color: var(--svg-color--ffb80a, #FFB80A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxiqgebpn {
  stop-color: var(--svg-color--ff6732, #FF6732);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r375w-bke {
  stop-color: var(--svg-color--eaac25, #EAAC25);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rbbulnz3l {
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.rbkr51v-c {
  stop-color: var(--svg-color--ff730a, #FF730A);
  stop-opacity: 0;
}

.rf8_ys_es {
  stop-color: var(--svg-color--ffda31, #FFDA31);
}

.rowsrjblg {
  stop-color: var(--svg-color--d93738, #D93738);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.smo9u60ba {
  stop-color: var(--svg-color--ffa842, #FFA842);
}

.srr6nlykd {
  stop-color: var(--svg-color--e9901f, #E9901F);
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.t-faq4izi {
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.t-jdupvjc {
  stop-color: var(--svg-color--f7941d, #F7941D);
  stop-opacity: 0;
}

.t0_upib5g {
  d: path("M19.823 12.744a1.1 1.1 0 0 0-.298-.596l-.335.367l.151.294z");
}

.twmiqpbxq {
  d: path("m25.19 20.578l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.u1hhhxbfd {
  stop-color: var(--svg-color--e2632d, #E2632D);
}

.u4cp3820t {
  d: path("m6.81 20.578l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.ub8ckabiz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.924 11.398c-.838 0-1.547.578-1.74 1.36a.352.352 0 0 0 .344.437h2.866a.296.296 0 0 0 .291-.35a1.8 1.8 0 0 0-1.76-1.447");
}

.um2qp2-uc {
  stop-color: var(--svg-color--cb7831, #CB7831);
  stop-opacity: 0;
}

.utrmehb1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.066 11.398c.839 0 1.547.578 1.74 1.36a.352.352 0 0 1-.344.437h-2.865a.296.296 0 0 1-.292-.35a1.795 1.795 0 0 1 1.76-1.447");
}

.v1z821b6o {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
  stop-opacity: 0;
}

.v2o3hnbel {
  stop-color: var(--svg-color--e4803e, #E4803E);
}

.v3bwo4btz {
  stop-color: var(--svg-color--ff7132, #FF7132);
}

.v3eonib4h {
  d: path("M20.44 16.106L5.033 23.28a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.705l15.407-7.182c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v69eygbez {
  stop-color: var(--svg-color--d97b26, #D97B26);
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vxb86i-rd {
  stop-color: var(--svg-color--ff7130, #FF7130);
}

.vzmhuwavr {
  stop-color: var(--svg-color--f35e74, #F35E74);
  stop-opacity: 0;
}

.vzu9-mfnh {
  d: path("m23 16.078l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.w-vsz3bnm {
  stop-color: var(--svg-color--e4764e, #E4764E);
  stop-opacity: 0;
}

.w58mn6r_g {
  stop-color: var(--svg-color--ff9a32, #FF9A32);
}

.w73iq3bud {
  fill: var(--svg-color--f53b19, #F53B19);
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wq0eljlkx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.76l-2.017-.534");
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwlvfha4h {
  stop-color: var(--svg-color--ffc028, #FFC028);
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x5ozldbku {
  stop-color: var(--svg-color--ffdd32, #FFDD32);
}

.x8wetqqbt {
  stop-color: var(--svg-color--cb7831, #CB7831);
}

.xg3e-vb_e {
  stop-color: var(--svg-color--d97b26, #D97B26);
  stop-opacity: 0;
}

.xg7pvujwr {
  stop-color: var(--svg-color--e79c19, #E79C19);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xpv5cjbuo {
  stop-color: var(--svg-color--e6a736, #E6A736);
}

.xrn2z6b6u {
  stop-color: var(--svg-color--ff8c11, #FF8C11);
  stop-opacity: 0;
}

.y0na07-wu {
  stop-color: var(--svg-color--ffe032, #FFE032);
}

.y2jmkqeym {
  stop-color: var(--svg-color--ffe128, #FFE128);
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yk9k1_boe {
  stop-color: var(--svg-color--e6a736, #E6A736);
  stop-opacity: 0;
}

.z-qcyfbze {
  cx: 12.844px;
  cy: 12.236px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.5px;
  ry: 0.253px;
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zpwiheb_q {
  d: path("M24.75 19.811a.885.885 0 0 1 .35-1.203l2.609-1.428a.899.899 0 1 1 .856 1.58l-2.621 1.405a.885.885 0 0 1-1.194-.354");
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

</style>
