<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHW5UBd)"><path fill="url(#iuuJMbJ)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#iZPqlCe)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#iNFDDsc)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#iA7jwyc)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#iPBbApc)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#i1VG66K)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#iiqZ7Fd)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#i0tFuwe)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#i3MT22d)" clip-rule="evenodd" class="q49fgob7w"/><path fill="url(#i01IEse)" clip-rule="evenodd" class="q49fgob7w"/></g><g filter="url(#ieJLxNd)"><path fill="url(#ihDnvud)" class="grow--b1c"/></g><g filter="url(#iDftzXc)"><path fill="url(#if39fZd)" class="p7bzucc6e"/><path fill="url(#iJhvd2c)" class="p7bzucc6e"/></g><g filter="url(#iOCGeYc)"><path class="ykm9rpb0r"/><path fill="url(#iMbPiYc)" class="q26cnlbgb"/></g><g filter="url(#im4o00d)"><path class="koy-u3bgn"/><path fill="url(#iIWpHlk)" class="y1k99cbut"/></g><g filter="url(#ii3lY8q)"><path fill="url(#is4zZ3k)" class="jjrs4kbef"/><path fill="url(#iliDA7d)" class="jjrs4kbef"/><path fill="url(#iR9dY8b)" class="jjrs4kbef"/><path fill="url(#i0cbX9b)" class="jjrs4kbef"/><path fill="url(#ivQk5bc)" class="jjrs4kbef"/><path fill="url(#isyPD0t)" class="jjrs4kbef"/><path fill="url(#iooDzxc)" class="jjrs4kbef"/></g><path fill="url(#iS2HT8c)" class="jg9u_i68n"/><path fill="url(#iPo08Gb)" class="jg9u_i68n"/><g filter="url(#ipKfdsc)"><path class="zgmmbubkv"/></g><g filter="url(#ixb0Dwe)"><path class="ala82t2kb"/><path fill="url(#iCTNCOd)" class="cticybbod"/><path fill="url(#izo8bKb)" class="cticybbod"/><path fill="url(#iogKXbc)" class="cticybbod"/></g><path fill="url(#ic5ermc)" class="cticybbod"/><path fill="url(#i8JPTRb)" class="cticybbod"/><path stroke="url(#iyU7XPa)" class="ep3_tmbwv"/><g filter="url(#iz3ovLb)"><path class="c0eok9bem"/></g><g filter="url(#idsV5jd)"><path class="swd1rjbjr"/></g><g filter="url(#ilMsCsK)"><path class="bedcd9e0u"/></g><g filter="url(#iNtYqib)"><path clip-rule="evenodd" class="e2ppuwbaj"/></g><path class="h_5j3bb1p"/><path fill="url(#iXSjlDe)" class="sbzc-bn5k"/><path class="r3hbhdw-f"/><g filter="url(#i2WpEde)"><path class="ekg0t0dlc"/><path fill="url(#iqJsblY)" class="kgqw1ph8y"/></g><g filter="url(#iKX5aie)"><path fill="url(#ihgLMKo)" class="hbci2ni0w"/></g><path class="nzx14xbtd"/><path fill="url(#iDEPBLd)" class="uxlt0_g1q"/><path class="b-ez61u_v"/><g filter="url(#iEfeHfb)"><path fill="url(#itm9chc)" class="v0ygmbl2a"/></g><g filter="url(#ih7vmJe)"><ellipse transform="rotate(-27.914 13.547 9.85)" class="qwpmb2k3w"/><ellipse fill="url(#iuiyo9b)" transform="rotate(-27.914 13.547 9.85)" class="j8gttpghw"/></g><g filter="url(#iKIFcje)"><path class="xk6qt1bcc"/></g><g filter="url(#iLN1veb)"><path class="tc-no7lwd"/></g><g filter="url(#iuopOBd)"><path fill="url(#ixvHGEd)" class="gdingfbtj"/><path fill="url(#iuuKv5b)" class="gdingfbtj"/></g><g filter="url(#iNBG3ee)"><path fill="url(#iBK8Gkc)" class="m1njczbli"/><path fill="url(#i9MN09b)" class="m1njczbli"/><path fill="url(#iU5yxZb)" class="m1njczbli"/></g><g filter="url(#ilJFuvc)"><path stroke="url(#iTLvMKd)" class="lx8jo5m8f"/></g><path fill="url(#ix0aLxe)" class="xqtb5_5bv"/><path fill="url(#iFopWnc)" class="rvk_1d23p"/><path fill="url(#iVAG8qd)" class="a1q-0ubvc"/><path fill="url(#ikYlYte)" class="a1q-0ubvc"/><path class="isqcshn9a"/><path fill="url(#iT9WgNb)" class="pt1lol2at"/><path fill="url(#ig3eBJb)" class="pt1lol2at"/><path fill="url(#iYHxild)" class="sddnkbbus"/><path fill="url(#ixi72Gc)" class="hhcul-bgm"/><g filter="url(#ihrNEWc)"><path fill="url(#iEop8sb)" class="mrzjujb4t"/><path fill="url(#iF1gVqc)" class="mrzjujb4t"/><path fill="url(#ioaqHwe)" class="mrzjujb4t"/><path fill="url(#i5fpt3d)" class="mrzjujb4t"/><path fill="url(#iJKzsvb)" class="mrzjujb4t"/><path fill="url(#i868E7b)" class="mrzjujb4t"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="iZPqlCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.74318 -3.62044 8.25485 3.97456 20.693 16.363)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iNFDDsc" cx="0" cy="0" r="1" gradientTransform="rotate(109.074 3.282 11.613)scale(5.77873 5.40927)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iA7jwyc" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.16 8.864)scale(3.98975 4.91117)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iPBbApc" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.778 8.284)scale(1.78101 1.61886)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="i1VG66K" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 6.357 3.993)scale(2.38706 3.50899)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iiqZ7Fd" cx="0" cy="0" r="1" gradientTransform="matrix(2.16229 3.16788 -5.52839 3.77349 12.162 2.97)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="i0tFuwe" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.694 7.127)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="i3MT22d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.51 9.692)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="i01IEse" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15113 1.34089 -2.13644 -5.02072 23.241 12.474)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="if39fZd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 10.983)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iJhvd2c" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 21.062 8.762)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iMbPiYc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.412 -52.13)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iIWpHlk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 11.334 10.544)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="is4zZ3k" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.86 10.006)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iliDA7d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.9 10.704)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iR9dY8b" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.82 16.789)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i0cbX9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.4375 -10.082 0 16 9.719)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="r-0u0fxly"/><stop offset=".879" class="h6c53qbay"/></radialGradient><radialGradient id="ivQk5bc" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.905 6.727)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="isyPD0t" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 18.301 9.588)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iooDzxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.082 9.675)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iS2HT8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.096 11.075)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iPo08Gb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 4.21875 -8.71783 2.38933 13.5 4.5)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iCTNCOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.785 11.802)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i8JPTRb" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.31 8.332)scale(1.57489 2.10944)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iXSjlDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.947)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iqJsblY" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 10.03)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iDEPBLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.947)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iuiyo9b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.77 -1.578)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixvHGEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.93486 2.6818 -5.32876 3.84458 10.043 4.295)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iuuKv5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87735 2.48068 -1.9455 -1.47233 13.285 4.53)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="iBK8Gkc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11195 4.39145 -6.24446 -3.00311 17.911 2.619)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="i9MN09b" cx="0" cy="0" r="1" gradientTransform="matrix(-.8568 3.20722 -5.72497 -1.5294 18.313 3.792)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iU5yxZb" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.368 -.458)scale(7.21046 6.45439)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iVAG8qd" cx="0" cy="0" r="1" gradientTransform="matrix(2.80769 -1.3591 1.47615 3.04949 2.748 29.984)" gradientUnits="userSpaceOnUse"><stop offset=".406" class="x5wyh_bgu"/><stop offset="1" class="g7fsacmcm"/></radialGradient><radialGradient id="ikYlYte" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.976)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="o8q58hjtm"/><stop offset=".927" class="j270wbcuh"/></radialGradient><radialGradient id="iT9WgNb" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.084)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="ghofubbuk"/><stop offset="1" class="ijn59htws"/></radialGradient><radialGradient id="iF1gVqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.032)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="i868E7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.625)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="iuuJMbJ" x1="20.693" x2="13.888" y1="3.591" y2="16.195" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="ihDnvud" x1="9.705" x2="12.665" y1="10.631" y2="10.631" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="izo8bKb" x1="14.954" x2="15.808" y1="11.819" y2="11.924" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iogKXbc" x1="16" x2="16" y1="12.674" y2="12.063" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ic5ermc" x1="16.078" x2="16.078" y1="12.648" y2="12.508" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="iyU7XPa" x1="15.271" x2="15.724" y1="14.151" y2="13.279" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="ihgLMKo" x1="18.96" x2="18.646" y1="10" y2="10.194" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itm9chc" x1="14.562" x2="14.248" y1="10" y2="10.194" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iTLvMKd" x1="13.109" x2="13.654" y1="4.345" y2="5.619" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="ix0aLxe" x1="8.815" x2="23.191" y1="15.283" y2="15.283" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iFopWnc" x1="8.815" x2="23.191" y1="15.253" y2="15.253" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ig3eBJb" x1="26.607" x2="27.302" y1="28.803" y2="28.803" gradientUnits="userSpaceOnUse"><stop class="ilfv4xrsc"/><stop offset="1" class="q1cl32x8o"/><stop offset="1" class="zhzbpu8km"/></linearGradient><linearGradient id="iYHxild" x1="10.918" x2="1.428" y1="23.968" y2="24.009" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ixi72Gc" x1="22.998" x2="28.652" y1="23.985" y2="23.985" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iEop8sb" x1="7.493" x2="11.284" y1="19.719" y2="30.77" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="ioaqHwe" x1="16" x2="16" y1="15.984" y2="17.344" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="i5fpt3d" x1="5" x2="6.055" y1="24.219" y2="24.219" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="iJKzsvb" x1="27" x2="25.524" y1="25.157" y2="25.157" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="iHW5UBd" width="15.268" height="15.768" x="8.491" y="1.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="ieJLxNd" width="3.368" height="3.468" x="9.705" y="8.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="iDftzXc" width="3.218" height="3.468" x="19.218" y="8.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="iOCGeYc" width="3.148" height="3.148" x="19.253" y="8.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".25"/></filter><filter id="im4o00d" width="2.948" height="2.948" x="9.86" y="9.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".2"/></filter><filter id="ii3lY8q" width="10.191" height="11.127" x="10.905" y="5.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="ipKfdsc" width="2.877" height="3.682" x="14.399" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".25"/></filter><filter id="ixb0Dwe" width="2.377" height="3.182" x="14.812" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".125"/></filter><filter id="iz3ovLb" width="3.001" height="1.285" x="16.942" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="idsV5jd" width="3.001" height="1.285" x="12.057" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="ilMsCsK" width="2.453" height="1.091" x="12.192" y="7.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="iNtYqib" width="2.453" height="1.091" x="17.609" y="7.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter><filter id="i2WpEde" width=".787" height=".696" x="17.448" y="9.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".05"/></filter><filter id="iKX5aie" width=".891" height=".913" x="18.288" y="9.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".1"/></filter><filter id="iEfeHfb" width=".986" height="1.04" x="13.845" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".1"/></filter><filter id="ih7vmJe" width=".913" height=".705" x="13.09" y="9.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".05"/></filter><filter id="iKIFcje" width="2.661" height="1.378" x="17.44" y="7.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".2"/></filter><filter id="iLN1veb" width="2.661" height="1.378" x="11.988" y="7.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".2"/></filter><filter id="iuopOBd" width="4.287" height="5.25" x="9.741" y="3.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".25"/></filter><filter id="iNBG3ee" width="8.914" height="5.78" x="12.683" y="2.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".125"/></filter><filter id="ilJFuvc" width="1.145" height="2.31" x="12.809" y="3.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1181" stdDeviation=".1"/></filter><filter id="ihrNEWc" width="22" height="14.1" x="5" y="15.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1181"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-technologist-medium-light" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a1q-0ubvc {
  d: path("M8.329 29.985q.004-.081.004-.163a3.138 3.138 0 1 0-6.271.163z");
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.ala82t2kb {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.618 10.182l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.645-.376-.764 0");
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

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.b-ez61u_v {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.362a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bedcd9e0u {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.602 8.766l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.181z");
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.c0eok9bem {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.142 9.974c.266-.466.67-.835 1.538-.835c.38 0 .747.105 1.072.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cticybbod {
  d: path("m15.618 10.182l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.645-.376-.764 0");
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e2ppuwbaj {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m19.732 8.308l-.138.23za.268.268 0 0 1-.276.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.ekg0t0dlc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.119 9.658c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.ep3_tmbwv {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.602 13.066a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.247a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.246-.04a3 3 0 0 1-1.399.338a3 3 0 0 1-1.398-.339Z");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.ft5dv1b6b {
  fill: none;
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.g7fsacmcm {
  stop-color: var(--svg-color--c29173, #C29173);
}

.gdingfbtj {
  d: path("M11.106 4.53c.62-.554 1.517-.56 2.02-.47l.402 1.29c-.257-.038-.486.051-.679.235c-.453 1.677-2.162 1.425-2.498 2.682c-.15-1.492-.318-2.782.755-3.738");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghofubbuk {
  stop-color: var(--svg-color--fec6a9, #FEC6A9);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.grow--b1c {
  d: path("M11.314 12.153a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h_5j3bb1p {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.198c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h6c53qbay {
  stop-color: var(--svg-color--bd7188, #BD7188);
}

.hbci2ni0w {
  d: path("M18.98 10.244a.84.84 0 0 0-.232-.462l-.26.285l.117.228z");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hhcul-bgm {
  d: path("M23 17.994v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.ijn59htws {
  stop-color: var(--svg-color--fec6a9, #FEC6A9);
  stop-opacity: 0;
}

.ilfv4xrsc {
  stop-color: var(--svg-color--dfb290, #DFB290);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.isqcshn9a {
  fill: var(--svg-color--f2bd98, #F2BD98);
  d: path("M29.938 29.985q.005-.081.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j270wbcuh {
  stop-color: var(--svg-color--fbbf9f, #FBBF9F);
}

.j8gttpghw {
  cx: 13.547px;
  cy: 9.851px;
  rx: 0.39px;
  ry: 0.197px;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jg9u_i68n {
  d: path("M10.913 9.28h.012l-.01-.264l-.01-.306c.02-.95.574-1.317.81-1.44q.023-.007.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.234l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.685z");
}

.jjrs4kbef {
  d: path("m10.915 9.016l-.01-.306c.02-.95.574-1.317.81-1.44q.023-.007.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.234l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.685z");
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kgqw1ph8y {
  d: path("M18.119 9.658c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.koy-u3bgn {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.334 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lx8jo5m8f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 4.002c.023.243.235 1.156.545 1.71");
}

.m1njczbli {
  d: path("M15.397 2.753c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.276 6.537 2.984c1.572-.175 1.743.542 1.877.888c-.436-4.056-3.369-4.676-5.95-5.246");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mrzjujb4t {
  d: path("M26.03 15.984H5.97a.97.97 0 0 0-.97.97v13.03h22v-13.03a.97.97 0 0 0-.97-.97");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.nzx14xbtd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.61 9.198c-.654 0-1.206.45-1.356 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o8q58hjtm {
  stop-color: var(--svg-color--fbbf9f, #FBBF9F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p7bzucc6e {
  d: path("M20.827 12.153a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pt1lol2at {
  d: path("M29.938 29.985q.005-.081.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.q1cl32x8o {
  stop-color: var(--svg-color--b38f78, #B38F78);
  stop-opacity: 0;
}

.q26cnlbgb {
  d: path("M20.827 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.q49fgob7w {
  fill-rule: evenodd;
  d: path("M23.185 11.953c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 2.015a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.232q-.043 0-.085.002a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.194a2.3 2.3 0 0 1-1.292 1.276c-.236.122-.79.49-.81 1.438l.01.307z");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwpmb2k3w {
  cx: 13.547px;
  cy: 9.851px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.r-0u0fxly {
  stop-color: var(--svg-color--d59692, #D59692);
  stop-opacity: 0;
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.r3hbhdw-f {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.362c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rvk_1d23p {
  d: path("M16.025 15.253h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.sbzc-bn5k {
  d: path("M18.184 9.47a.892.892 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.sddnkbbus {
  d: path("M8.98 17.984a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.swd1rjbjr {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.858 9.974c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tc-no7lwd {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.17c-.323-.078-1.125-.038-1.661.345");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.uxlt0_g1q {
  d: path("M13.816 9.47a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v0ygmbl2a {
  d: path("M14.631 10.257c0-.288-.234-.48-.298-.539l-.288.28l.178.36z");
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.x5wyh_bgu {
  stop-color: var(--svg-color--e2ac90, #E2AC90);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xk6qt1bcc {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.17c.322-.078 1.124-.038 1.66.345");
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.xqtb5_5bv {
  d: path("M16.355 15.253c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.y1k99cbut {
  d: path("M11.334 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ykm9rpb0r {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M20.827 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zgmmbubkv {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.608 10.32l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.613 0");
}

.zhzbpu8km {
  stop-color: var(--svg-color--dfb290, #DFB290);
  stop-opacity: 0;
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
