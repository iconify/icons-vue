<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBs2uPd)"><path fill="url(#iFHkt9d)" class="tfj3k4bcj"/><path fill="url(#ibwLg4c)" class="tfj3k4bcj"/><path fill="url(#ioxip8c)" class="tfj3k4bcj"/></g><g filter="url(#i8Kn3nm)"><path fill="url(#iERjKIc)" class="h8hb7bhza"/></g><g filter="url(#iXDqfPc)"><path fill="url(#iDDKeNe)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#ivoLlwc)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#iih45RB)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#iO98Lyl)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#iDll1gc)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#i3o62sb)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#ilWCKPb)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#i0LlVce)" clip-rule="evenodd" class="j3ts32bjq"/></g><path fill="url(#iv3BNkm)" clip-rule="evenodd" class="j3ts32bjq"/><path fill="url(#iNAvXpe)" class="qjef2h85n"/><path fill="url(#iP0WKyc)" class="qjef2h85n"/><path fill="url(#iG72Agd)" class="qjef2h85n"/><path fill="url(#isOfLqE)" class="qjef2h85n"/><g filter="url(#iZWtarc)"><path class="u8wlu-n5q"/></g><g filter="url(#iN3NrUb)"><path class="lf0goq9hd"/></g><g filter="url(#i3Z7nEe)"><path fill="url(#iFyj8fc)" class="s26dal06t"/><path fill="url(#iQY5ItM)" class="s26dal06t"/><path fill="url(#igupTOe)" class="s26dal06t"/></g><g filter="url(#i9wPFTc)"><path fill="url(#iroLhEc)" class="tg4-8em5x"/><path fill="url(#iBsXFEc)" class="tg4-8em5x"/><path fill="url(#iIIPLfc)" class="tg4-8em5x"/></g><g filter="url(#iCmrZVb)"><path fill="url(#i5Ntque)" class="o0g5rab3z"/><path fill="url(#iyU86lc)" class="o0g5rab3z"/><path fill="url(#iBvHXHm)" class="o0g5rab3z"/><path fill="url(#iRYqNzb)" class="o0g5rab3z"/><path fill="url(#iRlgt3c)" class="o0g5rab3z"/></g><path fill="url(#ilql7Ie)" class="jhl6k6khu"/><path fill="url(#iRwGeOc)" class="jhl6k6khu"/><g filter="url(#iidsxxe)"><path class="eohmeqb9f"/></g><g filter="url(#iM3nyKe)"><path fill="url(#ibTWK8c)" class="uyt0qc87c"/><path fill="url(#ipX9eVz)" class="uyt0qc87c"/></g><g filter="url(#ithSx9d)"><path fill="url(#iiyIfla)" class="hp5l62scd"/><path fill="url(#ilu8kKd)" class="hp5l62scd"/></g><circle fill="url(#iVoNTDe)" class="yigqs335m"/><circle fill="url(#iQb4Nxv)" class="yigqs335m"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.389)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.389)" class="movji7bnz"/><circle fill="url(#ii7pBIc)" class="m8iqhkgoz"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.447)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.447)" class="movji7bnz"/><path fill="url(#iG6Zi6b)" class="br0eop3vn"/><g filter="url(#i1BOwYZ)"><path class="o5v1l4bnq"/><path fill="url(#iS8a9Dd)" class="tlk-ld0vx"/><path fill="url(#iK0Kyjb)" class="tlk-ld0vx"/><path fill="url(#iINKoyd)" class="tlk-ld0vx"/><path fill="url(#imn1y9b)" class="tlk-ld0vx"/><path fill="url(#iefVPkb)" class="tlk-ld0vx"/></g><path fill="url(#iJlmx2d)" class="mdp_n0byo"/><g filter="url(#i3HUfHd)"><path class="dy6k1p4mi"/><path fill="url(#ifO4pIc)" class="yw8frwbhp"/><path fill="url(#i7XPfxe)" class="yw8frwbhp"/></g><g filter="url(#isgDaOb)"><path class="lgey91b0v"/><path fill="url(#iLkDMNt)" class="e_qzb5evc"/><path fill="url(#ip5qqbb)" class="e_qzb5evc"/><path fill="url(#iQj7uMb)" class="e_qzb5evc"/><path fill="url(#i6ScMZc)" class="e_qzb5evc"/><path fill="url(#iVeIkkb)" class="e_qzb5evc"/></g><g filter="url(#i2ZvFTd)"><path fill="url(#iyIl2Mq)" clip-rule="evenodd" class="idwarib_r"/></g><g filter="url(#iKvnqrc)"><path class="vpagp4b_p"/></g><g filter="url(#isybhvb)"><path fill="url(#iGv0bfv)" class="hxmtmub0t"/><path fill="url(#iMn3LMe)" class="hxmtmub0t"/></g><g filter="url(#i9SOV3d)"><path stroke="url(#iafllge)" class="l1myvurxm"/></g><g filter="url(#iEgmKVr)"><path stroke="url(#iLZDT7d)" class="t9zmhfbbw"/></g><g filter="url(#iTnxTob)"><path stroke="url(#iACsPRb)" class="y5vrmr8sr"/></g><g filter="url(#iZjIxKb)"><path fill="url(#iDJ7Kze)" class="qgom-qhmr"/></g><g filter="url(#iH7uehc)"><path fill="url(#iiSoDYd)" class="gpn5igb2z"/></g><g filter="url(#i6TurKc)"><path class="u-cbaxb4q"/><path fill="url(#invivPd)" class="p4s127_tq"/></g><g filter="url(#i7HfgZb)"><path class="w2i-g3_jt"/><path fill="url(#ioMXdyc)" class="q453txbzz"/></g><g filter="url(#i59iUxd)"><path fill="url(#ikulgkb)" class="movus2o8x"/><path fill="url(#ieumFKB)" class="movus2o8x"/><path fill="url(#iId4ynd)" class="movus2o8x"/><path fill="url(#i5TBo8M)" class="movus2o8x"/><path fill="url(#i9vHKce)" class="movus2o8x"/><path fill="url(#iAJPIDd)" class="movus2o8x"/><path fill="url(#iVJtvNd)" class="movus2o8x"/></g><path fill="url(#id30NSx)" class="movus2o8x"/><g filter="url(#iB6rB4b)"><path class="aemp2ccag"/></g><g filter="url(#ighR9Ke)"><path fill="url(#iT4dwDe)" class="w8m0hhb6t"/><path fill="url(#iZ7CIgJ)" class="w8m0hhb6t"/><path fill="url(#iknxwVd)" class="w8m0hhb6t"/><path fill="url(#iaorcye)" class="w8m0hhb6t"/></g><g filter="url(#i9NE1Nb)"><path stroke="url(#iAphqxO)" class="n9cxoqbze"/></g><path class="pk0tqmbtk"/><g filter="url(#iZtHPIb)"><path class="awaw99b1e"/></g><g filter="url(#iloNJBR)"><path class="y2zk0tkab"/></g><g filter="url(#ijJ4CGc)"><path class="t9bw5ub6d"/></g><g filter="url(#ii4gDad)"><path clip-rule="evenodd" class="f1juc1bnx"/></g><path class="nziml-cfe"/><path fill="url(#iNTuSdd)" class="qwi-jl2_l"/><path class="pz9jdobqy"/><g filter="url(#ivMgp4b)"><path class="ri_ttvbkz"/><path fill="url(#iypiNwc)" class="hco21ufem"/></g><g filter="url(#iW075be)"><path fill="url(#ipgPENe)" class="dp0qmlbgb"/></g><path class="mkw702b4d"/><path fill="url(#ig3wzre)" class="e4j-5tf5l"/><path class="xp0xkvbfb"/><g filter="url(#iUD5rNN)"><path fill="url(#i7A7MCd)" class="mp-lx4byn"/></g><g filter="url(#iFntxde)"><ellipse transform="rotate(-27.914 13.645 9.912)" class="oeukgyb3c"/><ellipse fill="url(#i2ki6id)" transform="rotate(-27.914 13.645 9.912)" class="rw6h8pbjm"/></g><g filter="url(#i2uo2MN)"><path class="w4690zl3h"/></g><g filter="url(#iUMV2Zd)"><path class="mf4zw5eby"/></g><g filter="url(#ixvAcid)"><path fill="url(#i5QRJHb)" class="uf3-rbb1i"/><path fill="url(#iyviD8c)" class="uf3-rbb1i"/></g><g filter="url(#iZLPZNc)"><path fill="url(#ixfTvWd)" class="uua7qsbmc"/><path fill="url(#iv1Lcbw)" class="uua7qsbmc"/><path fill="url(#ikl0HHe)" class="uua7qsbmc"/></g><g filter="url(#i12qYzg)"><path stroke="url(#isTn1Rc)" class="vg5jb1b9h"/></g><g filter="url(#iZ0xY3k)"><path fill="url(#inL86yd)" clip-rule="evenodd" class="x_6okbcps"/><path fill="url(#i4qyV8k)" clip-rule="evenodd" class="x_6okbcps"/></g><g filter="url(#ipzWb9d)"><path fill="url(#i1o0iOc)" class="kypu63_8v"/></g><defs><radialGradient id="ibwLg4c" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.828 7.01)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="ioxip8c" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.61)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="ivoLlwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.527 12.638)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iih45RB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.188 10.926)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iO98Lyl" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.779 8.489)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iDll1gc" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.55 12.214)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="i3o62sb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.73 7.18)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="ilWCKPb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.607 9.753)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="i0LlVce" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.393 5.936)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iv3BNkm" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.4481 -24.5162 0 16.098 5.056)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="ne8av9bzf"/><stop offset=".975" class="a1kwaqnsi"/></radialGradient><radialGradient id="iNAvXpe" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.154 15.723)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iG72Agd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.986)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="isOfLqE" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.142)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iQY5ItM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.78)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="igupTOe" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.64 14.62)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iBsXFEc" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.763 27.282)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iIIPLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.845)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="i5Ntque" cx="0" cy="0" r="1" gradientTransform="matrix(-7.18754 -5.18744 7.28549 -10.09452 19.012 22.111)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="vj4m2tb3q"/><stop offset="1" class="pcshyrb4c"/></radialGradient><radialGradient id="iyU86lc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82483 2.625 -.91343 -.98296 18.832 16.705)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="ospx9ybif"/><stop offset="1" class="ruijhiham"/></radialGradient><radialGradient id="iBvHXHm" cx="0" cy="0" r="1" gradientTransform="rotate(-136.548 13.54 7.47)scale(8.17891 17.4863)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="huxowdbbh"/><stop offset="1" class="ugfb6lv5r"/></radialGradient><radialGradient id="iRYqNzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.91406 -.74218 .35164 -.43308 22.45 20.697)" gradientUnits="userSpaceOnUse"><stop offset=".33" class="a0lve6l9d"/><stop offset="1" class="g6l_i_bhw"/></radialGradient><radialGradient id="iRlgt3c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.21381 1.92381 -.94056 -2.06016 16.007 15.512)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="g5gls_bky"/><stop offset="1" class="lc_l11bld"/></radialGradient><radialGradient id="ilql7Ie" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.697 35.874)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="ipX9eVz" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.153 4.9)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ilu8kKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.282)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iVoNTDe" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.319 11.79)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iQb4Nxv" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.417 14.585)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="ii7pBIc" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.355 12.645)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iG6Zi6b" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.35 19.355)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="iS8a9Dd" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.272 20.21)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iK0Kyjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.48 22.986)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iINKoyd" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.167 9.211)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="imn1y9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.279 24.783)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iefVPkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.563)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iJlmx2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.782)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="ifO4pIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.689)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="i7XPfxe" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.703)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iLkDMNt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.267)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="ip5qqbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.955)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iyIl2Mq" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.315 16.623)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iGv0bfv" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.387 23.83)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iMn3LMe" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.217)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iiSoDYd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.138 11.044)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="invivPd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.632 -52.372)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="ioMXdyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.432 10.605)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="ikulgkb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.374 7.114)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="ieumFKB" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.998 10.764)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iId4ynd" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.92 16.85)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="i5TBo8M" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.836 9.583)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="i9vHKce" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.726 11.723)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iAJPIDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.4 9.649)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iVJtvNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.18 9.736)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="id30NSx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.194 11.136)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iZ7CIgJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.883 11.863)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iNTuSdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.28 10.008)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iypiNwc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.497 .625)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ig3wzre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.916 10.008)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i2ki6id" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.63 10.226)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5QRJHb" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.831 4.978)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iyviD8c" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.949 4.222)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="ixfTvWd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.89 2.48)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iv1Lcbw" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.895 8.889)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="ikl0HHe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.248 9.364)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="i4qyV8k" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.826 8.67)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iBs2uPd" width="21.944" height="26.818" x="4.962" y="3.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="i8Kn3nm" width="12.631" height="14.916" x="9.484" y="8.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/><feGaussianBlur result="effect2_foregroundBlur_4002_3407" stdDeviation=".05"/></filter><filter id="iXDqfPc" width="15.268" height="15.268" x="8.589" y="1.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="iZWtarc" width="5.874" height="5.537" x="6.993" y="23.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".5"/></filter><filter id="iN3NrUb" width="4.979" height="4.054" x="18.51" y="24.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".5"/></filter><filter id="i3Z7nEe" width="2.973" height="2.006" x="21.47" y="23.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="i9wPFTc" width="3.281" height="2" x="20.468" y="25.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="iCmrZVb" width="13.965" height="11.381" x="9.149" y="12.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.596078 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="iidsxxe" width="10.996" height="6.432" x="11.932" y="21.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".5"/></filter><filter id="iM3nyKe" width="2.973" height="2.006" x="7.658" y="23.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="ithSx9d" width="3.266" height="2" x="8.366" y="25.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="i1BOwYZ" width="6.218" height="6.789" x="8.343" y="19.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3407" result="effect2_innerShadow_4002_3407"/></filter><filter id="i3HUfHd" width="6.218" height="6.639" x="17.574" y="19.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3407" result="effect2_innerShadow_4002_3407"/></filter><filter id="isgDaOb" width="6.702" height="6.417" x="12.683" y="20.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="i2ZvFTd" width="6.703" height="6.517" x="12.633" y="20.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".15"/></filter><filter id="iKvnqrc" width="3.2" height="3.2" x="14.271" y="22.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".25"/></filter><filter id="isybhvb" width="2.35" height="2.35" x="14.893" y="23.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="i9SOV3d" width="1.458" height="2.505" x="15.848" y="20.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".125"/></filter><filter id="iEgmKVr" width="1.723" height="1.924" x="16.94" y="24.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".125"/></filter><filter id="iTnxTob" width="1.368" height="2.217" x="18.104" y="22.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".125"/></filter><filter id="iZjIxKb" width="3.318" height="3.218" x="9.803" y="8.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="iH7uehc" width="3.218" height="3.468" x="19.316" y="8.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="i6TurKc" width="3.148" height="3.148" x="19.351" y="9.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".25"/></filter><filter id="i7HfgZb" width="2.648" height="2.648" x="10.108" y="9.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".125"/></filter><filter id="i59iUxd" width="10.191" height="11.277" x="11.003" y="5.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="iB6rB4b" width="2.877" height="3.682" x="14.497" y="9.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".25"/></filter><filter id="ighR9Ke" width="2.377" height="3.182" x="14.91" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".125"/></filter><filter id="i9NE1Nb" width="3.702" height="1.526" x="14.247" y="12.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".05"/></filter><filter id="iZtHPIb" width="3.001" height="1.286" x="17.04" y="9.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="iloNJBR" width="3.001" height="1.286" x="12.155" y="9.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="ijJ4CGc" width="2.453" height="1.091" x="12.29" y="7.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="ii4gDad" width="2.453" height="1.091" x="17.707" y="7.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="ivMgp4b" width=".786" height=".696" x="17.546" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".05"/></filter><filter id="iW075be" width=".891" height=".913" x="18.386" y="9.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".1"/></filter><filter id="iUD5rNN" width=".986" height="1.04" x="13.943" y="9.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".1"/></filter><filter id="iFntxde" width=".912" height=".704" x="13.188" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".05"/></filter><filter id="i2uo2MN" width="2.261" height=".978" x="17.738" y="7.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".1"/></filter><filter id="iUMV2Zd" width="2.261" height=".978" x="12.286" y="7.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".1"/></filter><filter id="ixvAcid" width="4.985" height="5.213" x="9.391" y="3.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".375"/></filter><filter id="iZLPZNc" width="8.914" height="5.78" x="12.781" y="2.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".125"/></filter><filter id="i12qYzg" width="1.145" height="2.31" x="12.907" y="3.763" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".125"/></filter><filter id="iZ0xY3k" width="15.448" height="4.54" x="8.589" y="2.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3407"/></filter><filter id="ipzWb9d" width="8.285" height="5.027" x="14.004" y="3.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3407" stdDeviation=".5"/></filter><linearGradient id="iFHkt9d" x1="26.906" x2="11.7" y1="11.486" y2="21.486" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iERjKIc" x1="20.7" x2="10.387" y1="17.392" y2="17.392" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iDDKeNe" x1="20.791" x2="13.55" y1="3.652" y2="17.095" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iP0WKyc" x1="14.887" x2="14.887" y1="30.861" y2="29.58" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iFyj8fc" x1="23.649" x2="21.867" y1="25.783" y2="24.373" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iroLhEc" x1="22.95" x2="21.169" y1="27.367" y2="25.673" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iRwGeOc" x1="12.653" x2="13.255" y1="29.252" y2="28.908" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="ibTWK8c" x1="7.856" x2="9.361" y1="24.267" y2="26.087" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iiyIfla" x1="9.062" x2="10.843" y1="27.366" y2="25.681" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="iQj7uMb" x1="14.919" x2="16.7" y1="27.13" y2="22.861" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="i6ScMZc" x1="13.356" x2="16.981" y1="22.892" y2="23.58" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iVeIkkb" x1="17.231" x2="16.325" y1="26.892" y2="25.142" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iafllge" x1="16.477" x2="16.477" y1="20.814" y2="22.822" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iLZDT7d" x1="17.286" x2="18.153" y1="24.869" y2="26.072" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iACsPRb" x1="18.728" x2="18.728" y1="22.4" y2="24.017" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iDJ7Kze" x1="9.803" x2="12.763" y1="10.692" y2="10.692" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iT4dwDe" x1="16.098" x2="16.098" y1="12.643" y2="9.961" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iknxwVd" x1="15.052" x2="15.906" y1="11.88" y2="11.985" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iaorcye" x1="16.098" x2="16.098" y1="12.735" y2="12.124" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iAphqxO" x1="15.369" x2="15.822" y1="14.212" y2="13.34" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ipgPENe" x1="19.058" x2="18.744" y1="10.061" y2="10.254" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7A7MCd" x1="14.659" x2="14.346" y1="10.061" y2="10.254" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="isTn1Rc" x1="13.207" x2="13.752" y1="4.407" y2="5.68" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="inL86yd" x1="20.788" x2="8.85" y1="3.642" y2="7.33" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient><linearGradient id="i1o0iOc" x1="20.633" x2="13.008" y1="7.263" y2="4.982" gradientUnits="userSpaceOnUse"><stop class="rvbk0zbik"/><stop offset="1" class="w-lg43bki"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-veil" /></template>
<style>
.a0lve6l9d {
  stop-color: var(--svg-color--efab25, #EFAB25);
}

.a1kwaqnsi {
  stop-color: var(--svg-color--dd7056, #DD7056);
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.aemp2ccag {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.706 10.382l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.613 0");
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.awaw99b1e {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.24 10.036c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.073.369c.268.217.232.495.024.6l-.556.317c-.652-.211-1.372-.24-2.079-.45");
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.br0eop3vn {
  d: path("m11.186 26.293l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.191-.717.058-.797.238c-.3.82-.081 2.137.085 3.002z");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dp0qmlbgb {
  d: path("M19.077 10.305a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dy6k1p4mi {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.751c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e_qzb5evc {
  d: path("M12.712 23.164c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.058 1.49.728c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e4j-5tf5l {
  d: path("M13.914 9.53a.893.893 0 0 0-.86 1.129h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eohmeqb9f {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.4c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.248-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .028.028.048.055.04l.458-.157q.112-.042.223-.058l.036-.084l1.043.854c.063-.13.19-.198.295-.153c.711.328.494-.417.288.729c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f1juc1bnx {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.83 8.37l-.138.23za.268.268 0 0 1-.276.46l-.005-.003l-.021-.012l-.091-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.529c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.01.006l.002.001z");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g5gls_bky {
  stop-color: var(--svg-color--ee8a27, #EE8A27);
}

.g6l_i_bhw {
  stop-color: var(--svg-color--efab25, #EFAB25);
  stop-opacity: 0;
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gpn5igb2z {
  d: path("M20.926 12.214a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h8hb7bhza {
  d: path("M9.984 15.846c0-4.854 2.694-7.281 6.016-7.281s6.016 2.324 6.016 7.28v7.436H9.984z");
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hco21ufem {
  d: path("M18.216 9.72c.064.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.135.388-.05");
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hp5l62scd {
  d: path("M11.39 25.799c-.678-.6-1.716-.536-2.298.111l-.69.735c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.huxowdbbh {
  stop-color: var(--svg-color--f8a519, #F8A519);
  stop-opacity: 0;
}

.hxmtmub0t {
  d: path("M15.993 25.217a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.idwarib_r {
  fill-rule: evenodd;
  d: path("M13.709 24.326a.913.913 0 0 1-.753-1.107a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.485v-.006q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.56a.3.3 0 0 0 .396.285l.551-.188l.007-.002c.516-.194 1.023.046 1.16.559c.14.532-.183 1.093-.687 1.183l-.466.103a.3.3 0 0 0-.178.469l.312.43l.006.007a.92.92 0 0 1-.172 1.344c-.429.298-1.012.16-1.32-.296l-.316-.422a.3.3 0 0 0-.493.017l-.247.383l-.005.008a.91.91 0 0 1-1.294.33l-.001-.001a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.067z");
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j3ts32bjq {
  fill-rule: evenodd;
  d: path("M23.283 12.015a3.24 3.24 0 0 0 .324-1.427c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.52.52 0 0 1 0-.456m-12.26-2.673h-.012l1.199 2.356c.123 2.802 1.217 0 3.888 0c2.672 0 3.837 3.119 3.96.316l1.136-3.197c-.054-1.244-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195c-.226.56-.656.99-1.19 1.234l-.05.02l-.052.021c-.236.123-.79.49-.81 1.439l.01.306z");
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jhl6k6khu {
  d: path("m13.196 29.923l-2.547-3.837l5.25-3.475l5.828 2.909l-2.922 4.403z");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.kypu63_8v {
  d: path("M21.29 7.42c-.826-2.726-3.536-3.278-6.286-2.938c2.75.214 4.25 1.222 5.125 2.937z");
}

.l1myvurxm {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.017c.324 0 .758.376.758.86v.945");
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lc_l11bld {
  stop-color: var(--svg-color--ffa821, #FFA821);
  stop-opacity: 0;
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lf0goq9hd {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.964c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.651a.11.11 0 0 1 .037-.146z");
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lgey91b0v {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.164c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.058 1.49.728c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m8iqhkgoz {
  cx: 10.18px;
  cy: 21.568px;
  r: 0.762px;
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp_n0byo {
  d: path("m20.799 26.293l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.191.718.058.798.238c.3.82.081 2.137-.085 3.002z");
}

.mf4zw5eby {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.247 8.232c-.323-.078-1.125-.04-1.66.344");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mkw702b4d {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.707 9.259c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.movji7bnz {
  r: 0.762px;
}

.movus2o8x {
  d: path("M11.01 9.342h.013l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.44q.023-.007.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.234l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.123 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.685z");
}

.mp-lx4byn {
  d: path("M14.729 10.318c0-.288-.234-.48-.298-.539l-.288.279l.177.361z");
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n9cxoqbze {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.098 13.516a3 3 0 0 1-1.421-.344c-.14-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.249 0c.089-.136-.062-.293-.203-.22c-.411.22-.896.345-1.422.345Z");
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.ne8av9bzf {
  stop-color: var(--svg-color--dc7620, #DC7620);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nziml-cfe {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.49 9.259c.652 0 1.204.45 1.354 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o0g5rab3z {
  d: path("M9.15 20.456a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.062a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o5v1l4bnq {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.751c-.076-.155-.018-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeukgyb3c {
  cx: 13.645px;
  cy: 9.912px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.ospx9ybif {
  stop-color: var(--svg-color--ffdf48, #FFDF48);
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4s127_tq {
  d: path("M20.925 11.679a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcshyrb4c {
  stop-color: var(--svg-color--ffbe1d, #FFBE1D);
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pk0tqmbtk {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M16.098 13.516a3 3 0 0 1-1.421-.344c-.14-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.249 0c.089-.136-.062-.293-.203-.22c-.411.22-.896.345-1.422.345");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pz9jdobqy {
  fill: var(--svg-color--000, #000);
  d: path("M17.771 10.423c0-.284.227-.51.511-.51a.51.51 0 0 1 .455.745h-.905a.46.46 0 0 1-.06-.235");
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q453txbzz {
  d: path("M11.432 11.679a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qgom-qhmr {
  d: path("M11.413 12.214a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.qjef2h85n {
  d: path("M27 29.924v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.549 5 23.724 5 28.924v1z");
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwi-jl2_l {
  d: path("M18.282 9.53a.893.893 0 0 1 .86 1.129h-1.724a.896.896 0 0 1 .864-1.128");
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.ri_ttvbkz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.216 9.72c.064.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.135.388-.05");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruijhiham {
  stop-color: var(--svg-color--ffdf48, #FFDF48);
  stop-opacity: 0;
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rvbk0zbik {
  stop-color: var(--svg-color--dd882e, #DD882E);
}

.rw6h8pbjm {
  cx: 13.645px;
  cy: 9.912px;
  rx: 0.389px;
  ry: 0.197px;
}

.s26dal06t {
  d: path("M21.48 25.286c.063-.898.843-1.586 1.721-1.535l.99.06c.121 0 .162.157.149.206c-.176.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t9bw5ub6d {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.7 8.827l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.002l.01-.006a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.161c.34-.109.815-.2 1.328-.11a.268.268 0 0 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.t9zmhfbbw {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.783l.907 1.18");
}

.tfj3k4bcj {
  d: path("M5.062 16.423c0-8.812 4.89-13.218 10.922-13.218s10.922 4.218 10.922 13.218v13.5H5.062z");
}

.tg4-8em5x {
  d: path("M20.61 25.799c.678-.6 1.716-.536 2.297.111l.69.735c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tlk-ld0vx {
  d: path("M8.528 22.751c-.076-.155-.018-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u-cbaxb4q {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.925 11.679a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u8wlu-n5q {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.135c.879-.051 1.658.636 1.72 1.534l.009.116c.31.044.61.175.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.763-1.75.834-2.66.271c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.151.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uf3-rbb1i {
  d: path("M11.204 4.59c.621-.552 1.517-.558 2.02-.469l.402 1.291c-.257-.04-.486.05-.679.235c-.456 1.26-2.022 1.955-2.749 2.145c-.15-1.492-.067-2.246 1.006-3.201");
}

.ugfb6lv5r {
  stop-color: var(--svg-color--f8a519, #F8A519);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uua7qsbmc {
  d: path("M15.495 2.814c-1.133-.25-2.347.955-2.464 1.375c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.175 1.743.542 1.877.888c-.436-4.056-3.369-4.676-5.95-5.246");
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.uyt0qc87c {
  d: path("M10.52 25.286c-.063-.898-.843-1.586-1.721-1.535l-.99.06c-.121 0-.162.157-.149.206c.176.967.961 1.703 2 1.633l.768-.097a.11.11 0 0 0 .102-.118z");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vg5jb1b9h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.207 4.063c.023.243.235 1.157.545 1.71");
}

.vj4m2tb3q {
  stop-color: var(--svg-color--ffd336, #FFD336);
}

.vpagp4b_p {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.348a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w-lg43bki {
  stop-color: var(--svg-color--dd882e, #DD882E);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w2i-g3_jt {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.432 11.679a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.w4690zl3h {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.038 8.232c.322-.078 1.125-.04 1.66.344");
}

.w8m0hhb6t {
  d: path("m15.716 10.243l-.531 1.7a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.x_6okbcps {
  fill-rule: evenodd;
  d: path("M16.278 4.355c-3.811 0-5.694 1.656-6.333 2.379a.775.775 0 0 1-1.161-1.027c.881-.996 3.165-2.902 7.494-2.902c4.41 0 6.609 1.914 7.54 2.876a.775.775 0 0 1-1.112 1.079c-.734-.758-2.556-2.405-6.428-2.405");
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xp0xkvbfb {
  fill: var(--svg-color--000, #000);
  d: path("M14.425 10.423a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.904a.5.5 0 0 0 .061-.235");
}

.y2zk0tkab {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.956 10.036c-.265-.467-.668-.836-1.537-.836c-.38 0-.747.106-1.073.369c-.269.217-.233.495-.024.6l.556.317c.652-.211 1.372-.24 2.078-.45");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y5vrmr8sr {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.564c.307.135.83.616.461 1.453");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yigqs335m {
  cx: 9.168px;
  cy: 20.49px;
  r: 0.762px;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yw8frwbhp {
  d: path("M23.457 22.751c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
