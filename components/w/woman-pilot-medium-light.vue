<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBDDC3d)"><path fill="url(#iLNhtDc)" class="g01e3uxve"/><path fill="url(#ih51Yze)" class="g01e3uxve"/><path fill="url(#i1cvapx)" class="g01e3uxve"/><path fill="url(#ia3FEpE)" class="g01e3uxve"/><path fill="url(#izCC7de)" class="g01e3uxve"/><path fill="url(#i03yTbd)" class="g01e3uxve"/><path fill="url(#io0MWwe)" class="g01e3uxve"/><path fill="url(#iXs3qve)" class="g01e3uxve"/></g><path fill="url(#iicL1gc)" class="xxsefzpdq"/><path fill="url(#imzeprd)" class="xxsefzpdq"/><path fill="url(#iKkwVod)" class="b072x2aii"/><path fill="url(#iqdGPbc)" class="b072x2aii"/><path fill="url(#iYnd6Rc)" class="c-tja9bpr"/><path fill="url(#il3aafd)" class="c-tja9bpr"/><path fill="url(#iZQubKe)" class="c-tja9bpr"/><path fill="url(#ir2HP9d)" class="mspkabc6v"/><path fill="url(#ipOd9Xc)" class="mspkabc6v"/><path fill="url(#iVWGzDb)" class="mspkabc6v"/><path fill="url(#i6l3kGc)" class="mspkabc6v"/><g filter="url(#irarQ8b)"><path class="fs1ufx2tc"/></g><path fill="url(#iLaes2w)" class="q9zrzf44o"/><g filter="url(#inWnOnO)"><path class="zvdkucbqp"/></g><g filter="url(#ikni2qb)"><path fill="url(#iMm4Ddd)" class="u0ana6wkh"/><path fill="url(#ideVytc)" class="u0ana6wkh"/><path fill="url(#iNjTTxJ)" class="u0ana6wkh"/></g><path fill="url(#iXFEZTd)" class="u0ana6wkh"/><g filter="url(#iRddWGd)"><path class="l7xshgban"/></g><g filter="url(#i41SaId)"><path fill="url(#itFU7Nd)" class="oc7ftgbyr"/><path fill="url(#ipIpBme)" class="oc7ftgbyr"/></g><path fill="url(#iq5GnHe)" class="gael-ox4b"/><path fill="url(#iCZ4BTb)" class="gael-ox4b"/><path fill="url(#i03SEAe)" class="gael-ox4b"/><path fill="url(#iQwoj1d)" class="gael-ox4b"/><g filter="url(#i7tBVwe)"><path fill="url(#iMNODVc)" class="xbtyokbyc"/></g><path fill="url(#iKiXURf)" class="zpz9k1skg"/><path fill="url(#iS6Udkd)" class="zpz9k1skg"/><path fill="url(#imSWIWd)" class="zpz9k1skg"/><g filter="url(#iYTNIEy)"><path fill="url(#itcJAhc)" class="dwn0mabie"/></g><g filter="url(#iYP8MDh)"><path fill="url(#i0TUfMs)" class="pn55igm3c"/><path fill="url(#iBJAqec)" class="pn55igm3c"/></g><g filter="url(#iSPwRgd)"><path class="o40q_-5ug"/><path fill="url(#iJiukOV)" class="x36oj-bei"/></g><g filter="url(#ipqaSDe)"><path class="djtwwkbgn"/><path fill="url(#igUZKMq)" class="w1q4p_brz"/></g><g filter="url(#iR3uo8d)"><path fill="url(#iZYZ3sU)" class="hn4psdvbk"/><path fill="url(#iVBexXb)" class="hn4psdvbk"/><path fill="url(#iJHNyQb)" class="hn4psdvbk"/><path fill="url(#iN4Wgmb)" class="hn4psdvbk"/><path fill="url(#i87j3Fb)" class="hn4psdvbk"/><path fill="url(#iwJBTYb)" class="hn4psdvbk"/><path fill="url(#iUXnyIb)" class="hn4psdvbk"/></g><path fill="url(#i2sGYhs)" class="gn4skqb-t"/><path fill="url(#iQvEbub)" class="gn4skqb-t"/><path fill="url(#inMqtXl)" class="gn4skqb-t"/><g filter="url(#iq3Lngi)"><path class="qdqbu3foy"/></g><g filter="url(#irslhue)"><path class="pa83i6b5g"/><path fill="url(#i5lIDxi)" class="jgxw3bwkd"/><path fill="url(#iI604Zc)" class="jgxw3bwkd"/><path fill="url(#iUmwnAj)" class="jgxw3bwkd"/><path fill="url(#iBY7RIP)" class="jgxw3bwkd"/></g><path fill="url(#iRYEkfc)" class="jgxw3bwkd"/><path fill="url(#i9P1v7d)" class="jgxw3bwkd"/><g filter="url(#isUFyFy)"><path stroke="url(#ixYgtPe)" class="b139ij3qp"/></g><path class="fl4cs2k0b"/><g filter="url(#iGtFvne)"><path class="sftysbc6w"/></g><g filter="url(#io2LRab)"><path class="d0c7ivbsi"/></g><path class="furhxvbtc"/><path fill="url(#iYQp4Xb)" class="lc25_sb8l"/><path class="j0fxlcbus"/><g filter="url(#i8Vch0b)"><path class="x4dy-wukn"/><path fill="url(#ijJ6Lhs)" class="rhalqdbir"/></g><g filter="url(#iEwsXJd)"><path fill="url(#iNTYZzA)" class="xlxv0lb6s"/></g><path class="l0ug9sc6z"/><path fill="url(#ioShyWb)" class="x75vcsbax"/><path class="pqw4-acyx"/><g filter="url(#iNgQVkm)"><path fill="url(#if5Up5d)" class="bh51932_l"/></g><g filter="url(#iLFqAPe)"><ellipse transform="rotate(-27.914 13.452 10.14)" class="mw25lsb-r"/><ellipse fill="url(#iN474Md)" transform="rotate(-27.914 13.452 10.14)" class="hi8ikbqul"/></g><g filter="url(#iAGGiBb)"><path class="z-ivtrlcx"/></g><g filter="url(#iWUmjcb)"><path fill="url(#iyNkKHc)" class="te18_qled"/></g><path fill="url(#im41Hle)" class="wb9snib6m"/><path fill="url(#iik2bBb)" class="wb9snib6m"/><path fill="url(#iNQcnJd)" class="wb9snib6m"/><g filter="url(#iDv5jYb)"><path fill="url(#iorGERc)" class="ywpgx-8qy"/></g><path fill="url(#iRzB4mc)" class="d43ioubeg"/><path fill="url(#iUbYlyc)" class="d43ioubeg"/><path fill="url(#iEHuhpd)" class="d43ioubeg"/><g filter="url(#igrFkCe)"><path class="ho8k-2bnl"/></g><g filter="url(#ij0dUOc)"><path fill="url(#iNlblBe)" class="wes-0ybwy"/><path fill="url(#i18Wkwz)" class="wes-0ybwy"/></g><g filter="url(#iaZXHRd)"><path fill="url(#iR42Amc)" class="hdde0uvpo"/></g><g filter="url(#isoJVqw)"><path fill="url(#iRal8Sb)" class="yi-thdc0w"/></g><path fill="url(#izWDMkb)" class="yi-thdc0w"/><defs><radialGradient id="ih51Yze" cx="0" cy="0" r="1" gradientTransform="rotate(-127.875 10.325 4.88)scale(4.27566 7.17269)" gradientUnits="userSpaceOnUse"><stop class="cwupdab5x"/><stop offset="1" class="sohhu-65w"/></radialGradient><radialGradient id="i1cvapx" cx="0" cy="0" r="1" gradientTransform="rotate(133.025 3.753 6.922)scale(1.92359 1.15293)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="kznoynbrq"/><stop offset="1" class="c-_i5gubp"/></radialGradient><radialGradient id="ia3FEpE" cx="0" cy="0" r="1" gradientTransform="matrix(3.53126 1.34373 -1.84425 4.8466 19.218 14.713)" gradientUnits="userSpaceOnUse"><stop class="wnyabwblt"/><stop offset="1" class="rqd_yzbvq"/></radialGradient><radialGradient id="izCC7de" cx="0" cy="0" r="1" gradientTransform="rotate(78.279 2.303 16.157)scale(7.69163 15.3623)" gradientUnits="userSpaceOnUse"><stop offset=".606" class="kd6wrzb5p"/><stop offset="1" class="i-1vfkbfj"/></radialGradient><radialGradient id="i03yTbd" cx="0" cy="0" r="1" gradientTransform="rotate(128.491 3.922 6.203)scale(3.31383 1.02553)" gradientUnits="userSpaceOnUse"><stop class="ikhrsbcqh"/><stop offset="1" class="xi881hbjb"/></radialGradient><radialGradient id="io0MWwe" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 1.78125 -1.2422 .76275 22.843 9.057)" gradientUnits="userSpaceOnUse"><stop class="zxq2qqnwl"/><stop offset="1" class="cai1z_bgj"/></radialGradient><radialGradient id="iXs3qve" cx="0" cy="0" r="1" gradientTransform="matrix(.96876 2.03124 -1.00779 .48065 23.312 12.806)" gradientUnits="userSpaceOnUse"><stop class="zxq2qqnwl"/><stop offset="1" class="xdsm3u4ap"/></radialGradient><radialGradient id="imzeprd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.224 24.404)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iKkwVod" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.063 30)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iqdGPbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.13 30)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="iYnd6Rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.615 30)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="iZQubKe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.708 29.637)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ir2HP9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 16 23.056)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="i6l3kGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.255 30.216)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="iLaes2w" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.991 21.044)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ideVytc" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.494 11.9)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iNjTTxJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.295 23.22)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="ipIpBme" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.036 15.868)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="iq5GnHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 16.005 18.69)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="adgho6gps"/><stop offset="1" class="p81iumb5r"/></radialGradient><radialGradient id="iCZ4BTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.24 19.685)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="iQwoj1d" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.60937 -.56235 .41494 19.375 17.468)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="p96-cobfo"/><stop offset="1" class="t_e0v9wgf"/></radialGradient><radialGradient id="iKiXURf" cx="0" cy="0" r="1" gradientTransform="rotate(89.999 -.228 16.204)scale(1.6196 2.56357)" gradientUnits="userSpaceOnUse"><stop class="z49nsqi6j"/><stop offset=".65" class="c05t2qbts"/></radialGradient><radialGradient id="iS6Udkd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68407 1.45873 -1.9297 -3.55068 17.39 16.51)" gradientUnits="userSpaceOnUse"><stop offset=".807" class="le5fkx1yi"/><stop offset="1" class="n2sl6b6xq"/></radialGradient><radialGradient id="imSWIWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51708 1.48792 -.48563 -.49515 18.09 16.218)" gradientUnits="userSpaceOnUse"><stop class="lz0g11bah"/><stop offset="1" class="mp3q3rbts"/></radialGradient><radialGradient id="i0TUfMs" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 19.945 11.273)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iBJAqec" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 20.968 9.052)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iJiukOV" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.175 -51.72)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="igUZKMq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.24 10.834)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iZYZ3sU" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.765 10.296)" gradientUnits="userSpaceOnUse"><stop class="k47z9nben"/><stop offset=".878" class="uaux9jbip"/></radialGradient><radialGradient id="iVBexXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.806 10.993)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iJHNyQb" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.726 17.079)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iN4Wgmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.9858 -9.46968 0 15.906 10.009)" gradientUnits="userSpaceOnUse"><stop offset=".709" class="s663v0ims"/><stop offset=".963" class="urp_6z9xd"/></radialGradient><radialGradient id="i87j3Fb" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.848 6.869)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iwJBTYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.207 9.878)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iUXnyIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 13.987 9.965)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="i2sGYhs" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.001 11.365)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iQvEbub" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.406 4.79)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="inMqtXl" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.78125 -5.0625 0 15.5 8.307)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="w9ql6e5ql"/><stop offset="1" class="vw8xbqzsm"/></radialGradient><radialGradient id="i5lIDxi" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.69 12.092)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i9P1v7d" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.216 8.462)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iYQp4Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.088 10.236)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ijJ6Lhs" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.86 10.32)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioShyWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.723 10.236)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iN474Md" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.865 -1.386)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="im41Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.485 2)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="iik2bBb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.798 4.31)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="iNQcnJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.38 4.747)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iorGERc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.263 -3.831)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iUbYlyc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.099 6.06)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iEHuhpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.099 7.06)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="i18Wkwz" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.675 -1.206)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="iRal8Sb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.583 4.044)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="izWDMkb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.88 4.544)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><filter id="iBDDC3d" width="15.396" height="10.672" x="8.403" y="6.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.768627 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="irarQ8b" width="7.031" height="7.114" x="12.489" y="14.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".5"/></filter><filter id="inWnOnO" width="4.951" height="14.36" x="9.117" y="15.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".5"/></filter><filter id="ikni2qb" width="3.097" height="14.304" x="10.348" y="15.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2468" result="effect2_innerShadow_4002_2468"/></filter><filter id="iRddWGd" width="4.081" height="12.629" x="18.162" y="15.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".5"/></filter><filter id="i41SaId" width="3.042" height="14.156" x="18.465" y="15.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2468" result="effect2_innerShadow_4002_2468"/></filter><filter id="i7tBVwe" width="2.735" height="2.58" x="14.632" y="18.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2468" result="effect2_innerShadow_4002_2468"/></filter><filter id="iYTNIEy" width="3.368" height="3.468" x="9.611" y="9.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="iYP8MDh" width="3.218" height="3.468" x="19.124" y="8.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="iSPwRgd" width="3.148" height="3.148" x="19.159" y="9.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".25"/></filter><filter id="ipqaSDe" width="2.948" height="2.948" x="9.765" y="9.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".2"/></filter><filter id="iR3uo8d" width="10.191" height="11.127" x="10.81" y="5.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="iq3Lngi" width="2.877" height="3.682" x="14.305" y="9.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".25"/></filter><filter id="irslhue" width="2.377" height="3.182" x="14.717" y="9.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".125"/></filter><filter id="isUFyFy" width="3.702" height="1.526" x="14.054" y="13.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".05"/></filter><filter id="iGtFvne" width="3.001" height="1.285" x="16.848" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="io2LRab" width="3.001" height="1.285" x="11.962" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="i8Vch0b" width=".787" height=".696" x="17.354" y="9.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".05"/></filter><filter id="iEwsXJd" width=".891" height=".913" x="18.193" y="9.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".1"/></filter><filter id="iNgQVkm" width=".986" height="1.04" x="13.751" y="9.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".1"/></filter><filter id="iLFqAPe" width=".913" height=".704" x="12.996" y="9.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".05"/></filter><filter id="iAGGiBb" width="3.151" height="1.346" x="20.534" y="19.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".1"/></filter><filter id="iWUmjcb" width="2.881" height="1.03" x="20.734" y="19.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2468" result="effect2_innerShadow_4002_2468"/></filter><filter id="iDv5jYb" width="10.9" height="2.77" x="10.555" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="igrFkCe" width="4.831" height="2.64" x="13.59" y="2.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2468" stdDeviation=".125"/></filter><filter id="ij0dUOc" width="2.293" height="1.21" x="13.861" y="3.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="iaZXHRd" width="2.298" height="1.22" x="15.943" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><filter id="isoJVqw" width="1.63" height="1.63" x="15.295" y="3.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2468"/></filter><linearGradient id="iLNhtDc" x1="20.861" x2="15.593" y1="7.962" y2="17.307" gradientUnits="userSpaceOnUse"><stop class="xw7zzc3vs"/><stop offset="1" class="m3h3i-b3u"/><stop offset="1" class="qa102lblv"/></linearGradient><linearGradient id="iicL1gc" x1="16" x2="16" y1="15.501" y2="30.001" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="il3aafd" x1="9.135" x2="6.943" y1="27.817" y2="27.817" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="ipOd9Xc" x1="16.505" x2="16.505" y1="30.466" y2="28.997" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="iVWGzDb" x1="19.067" x2="17.161" y1="26.56" y2="26.56" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="iMm4Ddd" x1="13.295" x2="13.295" y1="29.372" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iXFEZTd" x1="13.295" x2="13.295" y1="29.69" y2="23.356" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="itFU7Nd" x1="18.715" x2="19.724" y1="20.747" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="i03SEAe" x1="13.583" x2="15.177" y1="16.56" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="ovo1ps97q"/><stop offset="1" class="k5-d0pb7l"/><stop offset="1" class="mrezdm8zl"/></linearGradient><linearGradient id="iMNODVc" x1="15.991" x2="15.991" y1="19.225" y2="20.922" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="itcJAhc" x1="9.611" x2="12.57" y1="10.921" y2="10.921" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iI604Zc" x1="14.859" x2="15.713" y1="12.109" y2="12.214" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iUmwnAj" x1="15.906" x2="15.906" y1="12.964" y2="12.354" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iBY7RIP" x1="15.906" x2="15.906" y1="10.19" y2="11.182" gradientUnits="userSpaceOnUse"><stop class="nllf412fh"/><stop offset="1" class="f8f62lbrq"/></linearGradient><linearGradient id="iRYEkfc" x1="15.984" x2="15.984" y1="12.938" y2="12.798" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="ixYgtPe" x1="15.177" x2="15.629" y1="14.441" y2="13.569" gradientUnits="userSpaceOnUse"><stop class="ls8c0ib2q"/><stop offset="1" class="lfypbjbrm"/></linearGradient><linearGradient id="iNTYZzA" x1="18.866" x2="18.552" y1="10.29" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="if5Up5d" x1="14.467" x2="14.154" y1="10.29" y2="10.484" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyNkKHc" x1="21.084" x2="22.88" y1="20.076" y2="20.711" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="iRzB4mc" x1="17.349" x2="11.13" y1="6.841" y2="6.841" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset=".875" class="ayzgumbov"/></linearGradient><linearGradient id="iNlblBe" x1="16.091" x2="14.513" y1="4.161" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="iR42Amc" x1="18.083" x2="16.597" y1="3.169" y2="4.161" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pilot-medium-light" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.adgho6gps {
  stop-color: var(--svg-color--c9c0d4, #C9C0D4);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b072x2aii {
  d: path("M23.13 18.124V30h3.865v-3.5c0-3.357-1.5-6.36-3.865-8.378");
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.b139ij3qp {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.906 13.745c-.521 0-1.01-.125-1.422-.344c-.14-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345Z");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.bh51932_l {
  d: path("M14.537 10.547c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.c-_i5gubp {
  stop-color: var(--svg-color--cf9f79, #CF9F79);
  stop-opacity: 0;
}

.c-tja9bpr {
  d: path("M8.88 30V18.12a10.97 10.97 0 0 0-3.875 8.38V30z");
}

.c05t2qbts {
  stop-color: var(--svg-color--c7888d, #C7888D);
}

.cai1z_bgj {
  stop-color: var(--svg-color--fff8be, #FFF8BE);
  stop-opacity: 0;
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.cwupdab5x {
  stop-color: var(--svg-color--b57081, #B57081);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d0c7ivbsi {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.764 10.265c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.317c.652-.21 1.372-.239 2.079-.45");
}

.d43ioubeg {
  d: path("M15.955 5.52h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.djtwwkbgn {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.24 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dwn0mabie {
  d: path("M11.22 12.443a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f8f62lbrq {
  stop-color: var(--svg-color--cc9282, #CC9282);
  stop-opacity: 0;
}

.fl4cs2k0b {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.906 13.745c-.521 0-1.01-.125-1.422-.344c-.14-.074-.292.088-.203.219a1.932 1.932 0 0 0 3.25 0c.088-.136-.063-.293-.204-.22c-.411.22-.896.345-1.421.345");
}

.fs1ufx2tc {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M16.005 15.348H13.49v4.74c0 .31.334.49.566.29l1.95-1.67l1.948 1.67c.232.2.567.02.567-.29v-4.74z");
}

.ft5dv1b6b {
  fill: none;
}

.furhxvbtc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.297 9.488c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.341h-2.231a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.127");
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.g01e3uxve {
  d: path("M10.636 6.706h10.68c.092.577.528.994.98 1.425c.285.273.577.552.792.882c.625.958.461 1.953.176 2.937c-.076.264-.072.494 0 .637c.133.32.285.785.285 1.296a3.24 3.24 0 0 1-3.246 3.246H11.65a3.24 3.24 0 0 1-3.246-3.247c0-.51.153-.975.286-1.295c.071-.143.055-.445 0-.637c-.286-.984-.45-1.979.176-2.937c.214-.33.506-.609.792-.882c.452-.431.888-.848.98-1.425");
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.gael-ox4b {
  d: path("M16.005 15.284h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gn4skqb-t {
  d: path("M10.818 9.57h.013l-.01-.264L10.81 9c.02-.95.573-1.317.81-1.44q.023-.007.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.234l.082-.194a.264.264 0 0 1 .46-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.hdde0uvpo {
  d: path("M16.098 4.24h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hi8ikbqul {
  cx: 13.452px;
  cy: 10.141px;
  rx: 0.39px;
  ry: 0.197px;
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hn4psdvbk {
  d: path("M10.82 9.306L10.81 9c.02-.95.574-1.317.81-1.44q.025-.007.052-.02l.05-.02a2.3 2.3 0 0 0 1.19-1.234l.082-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.087 1.135 1.332l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685s-4.86-1.882-4.983-4.685z");
}

.ho8k-2bnl {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.793 4.352h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.005l-.272-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i-1vfkbfj {
  stop-color: var(--svg-color--c28494, #C28494);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.ikhrsbcqh {
  stop-color: var(--svg-color--ecbf98, #ECBF98);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j0fxlcbus {
  fill: var(--svg-color--000, #000);
  d: path("M17.579 10.652c0-.284.227-.511.51-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jgxw3bwkd {
  d: path("m15.523 10.472l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k47z9nben {
  stop-color: var(--svg-color--f8bf98, #F8BF98);
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.kd6wrzb5p {
  stop-color: var(--svg-color--d39192, #D39192);
  stop-opacity: 0;
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kznoynbrq {
  stop-color: var(--svg-color--cf9f79, #CF9F79);
}

.l0ug9sc6z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.515 9.488c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.l7xshgban {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.055 20.479l.444 1.05c.202.26.272.65.178 1.01l-1.295 4.646l-.22-10.446l.09-.183q.507.173.989.423l.98 2.64c.07.19-.04.41-.202.41h-.816c-.187 0-.28.28-.148.45");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lc25_sb8l {
  d: path("M18.09 9.76a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.le5fkx1yi {
  stop-color: var(--svg-color--b87973, #B87973);
  stop-opacity: 0;
}

.lfypbjbrm {
  stop-color: var(--svg-color--daa7a3, #DAA7A3);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.ls8c0ib2q {
  stop-color: var(--svg-color--daa7a3, #DAA7A3);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lz0g11bah {
  stop-color: var(--svg-color--c38f84, #C38F84);
}

.m3h3i-b3u {
  stop-color: var(--svg-color--e09f93, #E09F93);
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mp3q3rbts {
  stop-color: var(--svg-color--c38f84, #C38F84);
  stop-opacity: 0;
}

.mrezdm8zl {
  stop-color: var(--svg-color--4e4852, #4E4852);
  stop-opacity: 0;
}

.mspkabc6v {
  d: path("M18.705 16.11h-5.41V30h5.41z");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mw25lsb-r {
  cx: 13.452px;
  cy: 10.141px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n2sl6b6xq {
  stop-color: var(--svg-color--b87973, #B87973);
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.nllf412fh {
  stop-color: var(--svg-color--cc9282, #CC9282);
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.o40q_-5ug {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.733 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.oc7ftgbyr {
  d: path("m19.865 19.79l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86V15.836l.117.033q.653.173 1.272.423l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.ovo1ps97q {
  stop-color: var(--svg-color--4e4852, #4E4852);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p81iumb5r {
  stop-color: var(--svg-color--6d6675, #6D6675);
}

.p96-cobfo {
  stop-color: var(--svg-color--69646e, #69646E);
}

.pa83i6b5g {
  fill: var(--svg-color--d69f82, #D69F82);
  d: path("m15.523 10.472l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn55igm3c {
  d: path("M20.733 12.443a1.609 1.609 0 1 0 0-3.219a1.609 1.609 0 0 0 0 3.219");
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.pqw4-acyx {
  fill: var(--svg-color--000, #000);
  d: path("M14.233 10.652a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q9zrzf44o {
  d: path("M15.517 21.044a.25.25 0 0 0-.247.212l-1.335 8.745h4.12l-1.33-8.745a.25.25 0 0 0-.247-.212z");
}

.qa102lblv {
  stop-color: var(--svg-color--ecb896, #ECB896);
}

.qdqbu3foy {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.513 10.61l-.684 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.494-.376-.613 0");
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rhalqdbir {
  d: path("M18.024 9.948c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.rqd_yzbvq {
  stop-color: var(--svg-color--fbc0a7, #FBC0A7);
  stop-opacity: 0;
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.s663v0ims {
  stop-color: var(--svg-color--c5808e, #C5808E);
  stop-opacity: 0;
}

.sftysbc6w {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.048 10.265c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.269.217.233.495.024.599l-.555.317c-.652-.21-1.373-.239-2.08-.45");
}

.sohhu-65w {
  stop-color: var(--svg-color--d99890, #D99890);
  stop-opacity: 0;
}

.t_e0v9wgf {
  stop-color: var(--svg-color--69646e, #69646E);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.te18_qled {
  d: path("M23.365 19.78h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.u0ana6wkh {
  d: path("M13.295 15.837q-.691.176-1.345.436l-.035.018l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.uaux9jbip {
  stop-color: var(--svg-color--c88f7f, #C88F7F);
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urp_6z9xd {
  stop-color: var(--svg-color--b4678a, #B4678A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vw8xbqzsm {
  stop-color: var(--svg-color--ae7270, #AE7270);
  stop-opacity: 0;
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w1q4p_brz {
  d: path("M11.24 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.w9ql6e5ql {
  stop-color: var(--svg-color--ae7270, #AE7270);
}

.wb9snib6m {
  d: path("M21.747 3.55c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wes-0ybwy {
  d: path("M16.045 4.24h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wnyabwblt {
  stop-color: var(--svg-color--c78589, #C78589);
}

.x36oj-bei {
  d: path("M20.733 11.908a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.x4dy-wukn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.024 9.948c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358s.325-.136.39-.05");
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.x75vcsbax {
  d: path("M13.721 9.76a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.xbtyokbyc {
  d: path("m14.732 19.661l1.267-1.098l1.268 1.075l-.546 1.265a.24.24 0 0 1-.216.14h-1.022a.24.24 0 0 1-.216-.14z");
}

.xdsm3u4ap {
  stop-color: var(--svg-color--ffd8b2, #FFD8B2);
  stop-opacity: 0;
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xi881hbjb {
  stop-color: var(--svg-color--ecbf98, #ECBF98);
  stop-opacity: 0;
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xlxv0lb6s {
  d: path("M18.885 10.535a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.xw7zzc3vs {
  stop-color: var(--svg-color--ffe7b5, #FFE7B5);
}

.xxsefzpdq {
  d: path("M16.005 15.5c-6.07 0-11 4.92-11 11V30h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yi-thdc0w {
  d: path("M16.085 5.16a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.ywpgx-8qy {
  d: path("M16.005 6.33s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.z-ivtrlcx {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.247 19.836h-.611c-.22 0-.42.13-.516.329c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.33h-.592c-.124 0-.23.09-.239.22c-.01.13.096.25.22.25h.152c.18 0 .18.079.213.15a.34.34 0 0 0 .306.198h.238l.54.13c.133 0 .46-.1.518-.22l.086-.199c.02-.04.057-.06.096-.06h.143c.124 0 .229-.09.238-.219c-.01-.14-.114-.25-.238-.25");
}

.z49nsqi6j {
  stop-color: var(--svg-color--b86d86, #B86D86);
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zpz9k1skg {
  d: path("M15.976 18.503c1.79-.788 1.932-1.316 1.92-1.7v-.99h-3.839v.99c-.013.384.224.97 1.92 1.7");
}

.zvdkucbqp {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.795 16.462c-.46.117-.364.098-.8.271c-.54.783-1.546 2.199-1.85 2.873c-.09.19.05.41.26.41l1.18-.174c.24 0 .35.29.19.45l-1.37 1.196c-.26.26-.36.65-.23 1l2.893 6.334z");
}

.zxq2qqnwl {
  stop-color: var(--svg-color--fff8be, #FFF8BE);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
