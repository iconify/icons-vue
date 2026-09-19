<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRGXSCe)" class="e5ucantjx"/><path fill="url(#iWZJNMd)" class="a6yq75bbi"/><g filter="url(#iFEmiQc)"><path fill="url(#iKfqD1c)" class="omftgvbac"/><path fill="url(#ibwhnLd)" class="omftgvbac"/></g><path fill="url(#ii9qJ2d)" class="omftgvbac"/><path fill="url(#iDHIzhh)" class="omftgvbac"/><path fill="url(#ikSfxHb)" class="omftgvbac"/><path fill="url(#itL9FCe)" class="omftgvbac"/><path fill="url(#iRi9WmP)" class="omftgvbac"/><path fill="url(#iaAtd8d)" class="omftgvbac"/><path fill="url(#ilGgcXb)" class="omftgvbac"/><path fill="url(#i2pknVQ)" class="omftgvbac"/><path fill="url(#itYEl5d)" class="omftgvbac"/><g filter="url(#i64DWNe)"><path class="s0h6qabck"/></g><g filter="url(#itvQy7c)"><path class="borgxdbwo"/><path fill="url(#ifjSJAb)" class="e-zb_sb0t"/><path fill="url(#i7GD6rc)" class="e-zb_sb0t"/><path fill="url(#iTdlyoe)" class="e-zb_sb0t"/><path fill="url(#iDNZR3c)" class="e-zb_sb0t"/><path fill="url(#iHmLzzc)" class="e-zb_sb0t"/></g><g filter="url(#i00lVrd)"><path fill="url(#i2JGPPe)" class="bnbr98b0b"/><path fill="url(#iis1rNe)" class="bnbr98b0b"/><path fill="url(#iwFl61c)" class="bnbr98b0b"/><path fill="url(#imH7lJe)" class="bnbr98b0b"/><path fill="url(#iwKjjbe)" class="bnbr98b0b"/></g><g filter="url(#iCSrTgd)"><path class="nfsucybzx"/><path fill="url(#iJzhn7b)" class="rbbulnz3l"/><path fill="url(#idTEcbc)" class="rbbulnz3l"/></g><g filter="url(#iwCRgad)"><path class="y2jvwtu2p"/><path fill="url(#iGcOwfz)" class="t-faq4izi"/><path fill="url(#iS6wYvs)" class="t-faq4izi"/><path fill="url(#iemtF7c)" class="t-faq4izi"/></g><path class="utrmehb1k"/><path fill="url(#iPjnENe)" class="cswzjcx6u"/><path class="iitgd8bac"/><g filter="url(#icWBHke)"><path class="dodqfog5q"/><path fill="url(#i9QUMfK)" class="nsn8oes0z"/></g><g filter="url(#ihspnVd)"><path fill="url(#iKnUjve)" class="t0_upib5g"/></g><path class="ub8ckabiz"/><path fill="url(#iOPziAb)" class="fqu12ubrd"/><path class="ebo5c_0lf"/><g filter="url(#iKkXY1b)"><path fill="url(#i7aVE8b)" class="q5hvggldb"/></g><g filter="url(#iPXf1Jb)"><ellipse transform="rotate(-27.914 12.844 12.236)" class="z-qcyfbze"/><ellipse fill="url(#i8Ldsle)" transform="rotate(-27.914 12.844 12.236)" class="a3xscqbym"/></g><path fill="url(#iW5kB7c)" class="nl8aomm7e"/><path fill="url(#izcS6Rs)" class="nl8aomm7e"/><path fill="url(#iLe9YTb)" class="nl8aomm7e"/><path fill="url(#iImWKWb)" class="nl8aomm7e"/><path fill="url(#iLz0JOc)" class="l3e-mtbcj"/><path fill="url(#iEqOrJe)" class="l3e-mtbcj"/><g filter="url(#ie0P6nc)"><path fill="url(#iK1brXd)" class="blgscebjs"/></g><g filter="url(#iKg2VPc)"><path fill="url(#i3NB70c)" class="tmrtimg7x"/></g><g filter="url(#imsMnUP)"><path class="irc4pbbkk"/></g><g filter="url(#iKt4nLb)"><path class="vzkeadcof"/></g><g filter="url(#iiIfaTc)"><path stroke="url(#i3SkKVc)" class="gspwrdz1o"/></g><g filter="url(#irdz7jb)"><path stroke="url(#i4h3Cxd)" class="wq0eljlkx"/></g><path class="q9rihsbeb"/><path class="w73iq3bud"/><path fill="url(#iY2ScGe)" class="akki1obxr"/><path fill="url(#inirSwb)" class="akki1obxr"/><path fill="url(#ikeLGbe)" class="u4cp3820t"/><path fill="url(#ihqOLGc)" class="cuomu7bqz"/><path fill="url(#iRbdh4d)" class="cuomu7bqz"/><path fill="url(#i16tupc)" class="cuomu7bqz"/><path fill="url(#isBeo5c)" class="cuomu7bqz"/><path fill="url(#izAvOPb)" class="cuomu7bqz"/><path fill="url(#igdf08b)" class="cuomu7bqz"/><path fill="url(#iiwVwQd)" class="twmiqpbxq"/><path fill="url(#iDDcgbe)" class="v3eonib4h"/><path fill="url(#iwGAPQd)" class="v3eonib4h"/><path fill="url(#ixh7Cge)" class="v3eonib4h"/><path fill="url(#izO4CNd)" class="e3jco7qba"/><path fill="url(#iPP7OVB)" class="e3jco7qba"/><path fill="url(#i6hX5pW)" class="e3jco7qba"/><path fill="url(#ibl5Mkb)" class="i4fzwzbpd"/><path fill="url(#i9YoUJe)" class="i4fzwzbpd"/><path fill="url(#i9s8Vrd)" class="vzu9-mfnh"/><path fill="url(#iGXBICc)" class="vzu9-mfnh"/><path fill="url(#imvXkcb)" class="vzu9-mfnh"/><path fill="url(#iLtmjHc)" class="vzu9-mfnh"/><g filter="url(#igL8fTc)"><path fill="url(#iOOpJcd)" class="cw3sn1brq"/><path fill="url(#im3V8ac)" class="cw3sn1brq"/></g><path fill="url(#i5gvXQZ)" class="cw3sn1brq"/><g filter="url(#iaVVT6b)"><path fill="url(#ibBQOYc)" class="j_0xl5h8m"/></g><defs><radialGradient id="iRGXSCe" cx="0" cy="0" r="1" gradientTransform="matrix(.96166 2.5937 -3.08112 1.14238 22.1 14.564)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iWZJNMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.89623 .59596 -1.83857 5.85 8.217 15.194)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iKfqD1c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04271 0 0 -10.6895 19.601 13.355)" gradientUnits="userSpaceOnUse"><stop class="xva86cc4j"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ibwhnLd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23876 3.7026 -3.0568 -1.84827 19.112 6.96)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iDHIzhh" cx="0" cy="0" r="1" gradientTransform="rotate(94.704 6.36 11.182)scale(16.0095 13.2578)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="f0o-9fbtc"/><stop offset="1" class="otf1mnoto"/></radialGradient><radialGradient id="ikSfxHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.47484 1.82511 0 19.138 11.669)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="itL9FCe" cx="0" cy="0" r="1" gradientTransform="matrix(.00505 -1.4054 1.5294 .0055 13.041 11.729)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="iRi9WmP" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.971 7.634)scale(10.9332 27.9288)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iaAtd8d" cx="0" cy="0" r="1" gradientTransform="rotate(-40.741 16.893 -4.87)scale(5.73919 1.69526)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="ilGgcXb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.184 15.327)scale(3.2216 1.28781)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i2pknVQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11939 -2.1489 0 13.15 12.719)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="itYEl5d" cx="0" cy="0" r="1" gradientTransform="rotate(-62.819 20.907 -2.156)scale(5.06494 5.40943)" gradientUnits="userSpaceOnUse"><stop class="k7n-rzhyc"/><stop offset="1" class="kdpo-_boq"/></radialGradient><radialGradient id="i7GD6rc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3135 -.9853 0 16.594 15.124)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iDNZR3c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17313 .96336 -1.5482 -3.49239 16.743 14.392)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iis1rNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.49678 11.3718 0 9.279 9.64)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="p2s973_gj"/><stop offset="1" class="p6dlq8bal"/></radialGradient><radialGradient id="iwFl61c" cx="0" cy="0" r="1" gradientTransform="matrix(.14646 -3.22688 5.7174 .2595 22.238 11.323)" gradientUnits="userSpaceOnUse"><stop class="gpki0lbqt"/><stop offset="1" class="jxp-9c9su"/></radialGradient><radialGradient id="imH7lJe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53199 -2.0541 1.50781 -2.59266 20.015 3.081)" gradientUnits="userSpaceOnUse"><stop class="g6v8l_bkd"/><stop offset="1" class="gs7m3x8bv"/></radialGradient><radialGradient id="iwKjjbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.16245 1.89434 -4.3864 2.69168 14.832 1.217)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="ptziuobjj"/><stop offset="1" class="irfbnmbhq"/></radialGradient><radialGradient id="iJzhn7b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.82692 0 0 -1.04918 16.32 4.119)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="idTEcbc" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.84 -3.592)scale(7.74003 8.57516)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iGcOwfz" cx="0" cy="0" r="1" gradientTransform="matrix(3.92791 0 0 1.53575 20.38 5.252)" gradientUnits="userSpaceOnUse"><stop class="wkq1lrbro"/><stop offset="1" class="ay2ml8bfu"/></radialGradient><radialGradient id="iS6wYvs" cx="0" cy="0" r="1" gradientTransform="matrix(3.80008 -3.40113 6.2266 6.95698 19.378 9.153)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="iemtF7c" cx="0" cy="0" r="1" gradientTransform="matrix(4.14224 .93003 -.38939 1.73427 18.27 6.814)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iPjnENe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04198 -1.65739 0 18.798 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i9QUMfK" cx="0" cy="0" r="1" gradientTransform="matrix(-.29785 -.38382 .52843 -.41007 18.504 12.467)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOPziAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04204 -1.65748 0 13.193 12.36)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8Ldsle" cx="0" cy="0" r="1" gradientTransform="matrix(-.00994 -.63455 .76277 -.01194 12.825 12.642)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="izcS6Rs" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 2.921 20.555)scale(2.99201 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iLe9YTb" cx="0" cy="0" r="1" gradientTransform="matrix(1.01175 -1.38847 1.16382 .84805 22.388 12.895)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iImWKWb" cx="0" cy="0" r="1" gradientTransform="rotate(-69.263 20.763 -9.755)scale(2.12915 2.84485)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iEqOrJe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12971 0 0 -2.37799 9.682 13.019)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iK1brXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17705 .20204 -.20716 -1.20684 9.745 13.023)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="iY2ScGe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.445)" gradientUnits="userSpaceOnUse"><stop class="prd44wbso"/><stop offset="1" class="c5khawelw"/></radialGradient><radialGradient id="inirSwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.227)" gradientUnits="userSpaceOnUse"><stop class="u1hhhxbfd"/><stop offset="1" class="cl_cdxbgs"/></radialGradient><radialGradient id="ikeLGbe" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 1.25 -2.6929 5.58776 8.406 17.32)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="sy-f5ccgl"/><stop offset="1" class="i26rr_0fw"/></radialGradient><radialGradient id="ihqOLGc" cx="0" cy="0" r="1" gradientTransform="matrix(17.51082 8.75543 -2.15289 4.30577 13.551 19.209)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="v3bwo4btz"/><stop offset="1" class="kd1_xhb_o"/></radialGradient><radialGradient id="iRbdh4d" cx="0" cy="0" r="1" gradientTransform="rotate(159.944 11.543 15.187)scale(2.90693 2.17455)" gradientUnits="userSpaceOnUse"><stop class="cq9p23brg"/><stop offset="1" class="cwmsguygo"/></radialGradient><radialGradient id="i16tupc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11963 5.31578 -8.32746 -1.75396 14.245 17.692)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="w58mn6r_g"/><stop offset="1" class="xrn2z6b6u"/></radialGradient><radialGradient id="izAvOPb" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.455 -3.07)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="mq0gl8bsz"/><stop offset="1" class="w-vsz3bnm"/></radialGradient><radialGradient id="iiwVwQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 .6475 -1.4343 -3.32276 24.094 18.195)" gradientUnits="userSpaceOnUse"><stop class="qxiqgebpn"/><stop offset="1" class="m_8hwoksz"/></radialGradient><radialGradient id="iDDcgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.883)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="jbd_cz55y"/><stop offset="1" class="m7o64xbbx"/></radialGradient><radialGradient id="izO4CNd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11719 1.02344 -.40322 -.83413 29.122 17.469)" gradientUnits="userSpaceOnUse"><stop class="gi9rlrtiz"/><stop offset=".615" class="v4bxf0bxm"/></radialGradient><radialGradient id="ibl5Mkb" cx="0" cy="0" r="1" gradientTransform="matrix(1.74664 .85478 -1.17534 2.40165 3.176 17.648)" gradientUnits="userSpaceOnUse"><stop class="o6yqkabjh"/><stop offset=".697" class="iuvvk27wi"/></radialGradient><radialGradient id="i9YoUJe" cx="0" cy="0" r="1" gradientTransform="rotate(162.607 1.083 8.97)scale(.89785 1.70016)" gradientUnits="userSpaceOnUse"><stop class="e-dsjlbgb"/><stop offset="1" class="e4hi5lpxu"/></radialGradient><radialGradient id="i9s8Vrd" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.294 6.356)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="il1-__z0c"/><stop offset="1" class="bw58smb4a"/></radialGradient><radialGradient id="iGXBICc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 .59376 -.2045 -.35517 30.161 13.225)" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="egju40ogk"/></radialGradient><radialGradient id="iLtmjHc" cx="0" cy="0" r="1" gradientTransform="rotate(-25.641 56.32 -43.992)scale(2.59977 2.78402)" gradientUnits="userSpaceOnUse"><stop class="c64g55i6x"/><stop offset="1" class="ej8zfjbhh"/></radialGradient><radialGradient id="im3V8ac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.288)" gradientUnits="userSpaceOnUse"><stop class="jdjo_xq8q"/><stop offset="1" class="s3mfozy-p"/></radialGradient><radialGradient id="i5gvXQZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.00475 -.26214 .85754 3.28688 4.382 18.192)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="mhzmsi1xs"/><stop offset="1" class="wbpqeub1g"/></radialGradient><linearGradient id="ii9qJ2d" x1="22.619" x2="19.371" y1="15.52" y2="15.52" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ifjSJAb" x1="17.072" x2="15.995" y1="14.243" y2="14.288" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iTdlyoe" x1="15.995" x2="15.995" y1="15.706" y2="15.109" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="iHmLzzc" x1="15.995" x2="15.995" y1="12.232" y2="12.934" gradientUnits="userSpaceOnUse"><stop class="bl4x47bvc"/><stop offset="1" class="nv0opqb4i"/></linearGradient><linearGradient id="i2JGPPe" x1="24.795" x2="9.881" y1="6.082" y2="6.082" gradientUnits="userSpaceOnUse"><stop class="ej5y0weeq"/><stop offset="1" class="fj0i7pb1f"/></linearGradient><linearGradient id="iKnUjve" x1="19.798" x2="19.394" y1="12.429" y2="12.678" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7aVE8b" x1="14.148" x2="13.745" y1="12.428" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iW5kB7c" x1="24.261" x2="22.711" y1="12.282" y2="15.077" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iLz0JOc" x1="8.482" x2="10.355" y1="13.185" y2="13.022" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="i3NB70c" x1="22.975" x2="22.975" y1="11.796" y2="14.241" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="i3SkKVc" x1="13.921" x2="11.175" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bl_6lzkvy"/><stop offset="1" class="g9zuepbcp"/></linearGradient><linearGradient id="i4h3Cxd" x1="18.178" x2="20.924" y1="9.208" y2="9.928" gradientUnits="userSpaceOnUse"><stop offset=".333" class="bl_6lzkvy"/><stop offset="1" class="g9zuepbcp"/></linearGradient><linearGradient id="isBeo5c" x1="9.156" x2="10.344" y1="18.508" y2="18.883" gradientUnits="userSpaceOnUse"><stop class="psrrqcksv"/><stop offset="1" class="rbkr51v-c"/></linearGradient><linearGradient id="igdf08b" x1="17.406" x2="17.906" y1="26.977" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="gd1of5hxe"/><stop offset="1" class="v1z821b6o"/></linearGradient><linearGradient id="iwGAPQd" x1="14.83" x2="14.461" y1="26.816" y2="25.927" gradientUnits="userSpaceOnUse"><stop class="q9mg64b4e"/><stop offset="1" class="vzmhuwavr"/></linearGradient><linearGradient id="ixh7Cge" x1="22.827" x2="21.613" y1="18.819" y2="19.382" gradientUnits="userSpaceOnUse"><stop class="smo9u60ba"/><stop offset="1" class="ktas3sbvn"/></linearGradient><linearGradient id="iPP7OVB" x1="27.52" x2="26.84" y1="19.664" y2="18.102" gradientUnits="userSpaceOnUse"><stop class="u8owb3akc"/><stop offset="1" class="yutka0byn"/></linearGradient><linearGradient id="i6hX5pW" x1="26.75" x2="27.494" y1="17.398" y2="18.158" gradientUnits="userSpaceOnUse"><stop offset=".353" class="r80e5wbfg"/><stop offset="1" class="n7xbqubtn"/></linearGradient><linearGradient id="imvXkcb" x1="25.489" x2="25.997" y1="14.289" y2="15.189" gradientUnits="userSpaceOnUse"><stop class="beeyfebmi"/><stop offset="1" class="uhgt8fd7p"/></linearGradient><linearGradient id="iOOpJcd" x1="8" x2="5.5" y1="15.758" y2="19.524" gradientUnits="userSpaceOnUse"><stop offset=".206" class="g9lwhpb_s"/><stop offset="1" class="f96e_t8ap"/></linearGradient><linearGradient id="ibBQOYc" x1="29.179" x2="24.036" y1="14.953" y2="17.82" gradientUnits="userSpaceOnUse"><stop class="ffwswni4j"/><stop offset="1" class="zcueg9l3v"/></linearGradient><filter id="iFEmiQc" width="14.126" height="16.05" x="9.492" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24800"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24800" result="effect2_innerShadow_3987_24800"/></filter><filter id="i64DWNe" width="4.411" height="5.725" x="13.524" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".5"/></filter><filter id="itvQy7c" width="2.811" height="4.125" x="14.59" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".1"/></filter><filter id="i00lVrd" width="16.532" height="10.59" x="7.729" y="1.492" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24800"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24800" result="effect2_innerShadow_3987_24800"/></filter><filter id="iCSrTgd" width="8.814" height="8.053" x="8.006" y="2.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24800"/><feGaussianBlur result="effect2_foregroundBlur_3987_24800" stdDeviation=".25"/></filter><filter id="iwCRgad" width="9.096" height="7.796" x="15.543" y="3.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.152941 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24800"/><feGaussianBlur result="effect2_foregroundBlur_3987_24800" stdDeviation=".25"/></filter><filter id="icWBHke" width=".954" height=".837" x="17.883" y="11.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".05"/></filter><filter id="ihspnVd" width="1.033" height="1.061" x="18.99" y="11.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".1"/></filter><filter id="iKkXY1b" width="1.153" height="1.222" x="13.284" y="11.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".1"/></filter><filter id="iPXf1Jb" width="1.116" height=".848" x="12.286" y="11.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".05"/></filter><filter id="ie0P6nc" width="1.565" height="2.914" x="8.318" y="11.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".125"/></filter><filter id="iKg2VPc" width="2.216" height="3.444" x="21.867" y="11.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".25"/></filter><filter id="imsMnUP" width="2.884" height="1.34" x="11.376" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.133333 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24800"/></filter><filter id="iKt4nLb" width="2.884" height="1.34" x="17.939" y="8.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.133333 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24800"/></filter><filter id="iiIfaTc" width="2.717" height="1.234" x="11.486" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".125"/></filter><filter id="irdz7jb" width="2.717" height="1.234" x="17.896" y="8.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".125"/></filter><filter id="igL8fTc" width="7.3" height="8.016" x="2" y="12.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.356863 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24800"/></filter><filter id="iaVVT6b" width="5.538" height="5.423" x="24.159" y="13.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24800" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-no-medium" /></template>
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

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.akki1obxr {
  d: path("M25.5 30.008h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.ay2ml8bfu {
  stop-color: var(--svg-color--6b4e4e, #6B4E4E);
  stop-opacity: 0;
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.beeyfebmi {
  stop-color: var(--svg-color--8e6d54, #8E6D54);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bl_6lzkvy {
  stop-color: var(--svg-color--5a4344, #5A4344);
}

.bl4x47bvc {
  stop-color: var(--svg-color--a4786e, #A4786E);
}

.blgscebjs {
  d: path("M9.526 11.817a1.228 1.228 0 0 0 .107 2.413q-.069-1.206-.107-2.413");
}

.bnbr98b0b {
  d: path("M22.23 4.823c.66.228 1.253.69 1.628 1.35a3.04 3.04 0 0 1-.136 3.245a2 2 0 0 0-.348 1.123v1.526a2.2 2.2 0 0 0-.856-.345l.1-2.063a1.86 1.86 0 0 0-1.77-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34l.028 1.976c-.326.048-.655.155-.913.336v-1.541c0-.4-.123-.792-.348-1.123a3.07 3.07 0 0 1-.184-3.141a3 3 0 0 1 1.67-1.447a3.44 3.44 0 0 0 1.777-1.426a2.99 2.99 0 0 1 2.534-1.412c.416 0 .81.09 1.179.241c.49.214 1.042.214 1.532 0a3 3 0 0 1 1.172-.24c1.083 0 2.03.585 2.554 1.453a3.24 3.24 0 0 0 1.737 1.377");
}

.borgxdbwo {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.504 12.458l-.683 2.361c-.139.486.196.972.67.972H16.5c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.829-.524-.982 0");
}

.bw58smb4a {
  stop-color: var(--svg-color--a17a65, #A17A65);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c5khawelw {
  stop-color: var(--svg-color--ff9540, #FF9540);
  stop-opacity: 0;
}

.c64g55i6x {
  stop-color: var(--svg-color--a9656c, #A9656C);
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl_cdxbgs {
  stop-color: var(--svg-color--e2632d, #E2632D);
  stop-opacity: 0;
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

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.dodqfog5q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.e-dsjlbgb {
  stop-color: var(--svg-color--6b4237, #6B4237);
}

.e-zb_sb0t {
  d: path("m15.504 12.458l-.683 2.361c-.139.486.196.972.67.972H16.5c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.829-.524-.982 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3jco7qba {
  d: path("M24.75 19.811a.885.885 0 0 1 .35-1.203l2.609-1.428a.899.899 0 1 1 .856 1.581l-2.621 1.404a.885.885 0 0 1-1.194-.354");
}

.e4hi5lpxu {
  stop-color: var(--svg-color--6b4237, #6B4237);
  stop-opacity: 0;
}

.e5ucantjx {
  d: path("M22.239 14.96c.43-.014.833-.16 1.161-.396v1.195a2.79 2.79 0 0 1-1.722 2.593c.219-.465.37-.973.444-1.515z");
}

.ebo5c_0lf {
  fill: var(--svg-color--000, #000);
  d: path("M13.847 12.893a.654.654 0 0 0-.657-.657a.654.654 0 0 0-.583.959h1.162a.65.65 0 0 0 .078-.302");
}

.egju40ogk {
  stop-color: var(--svg-color--cca68c, #CCA68C);
  stop-opacity: 0;
}

.ej5y0weeq {
  stop-color: var(--svg-color--6f514d, #6F514D);
}

.ej8zfjbhh {
  stop-color: var(--svg-color--a9656c, #A9656C);
  stop-opacity: 0;
}

.f0o-9fbtc {
  stop-color: var(--svg-color--985682, #985682);
  stop-opacity: 0;
}

.f96e_t8ap {
  stop-color: var(--svg-color--8f575b, #8F575B);
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.ffwswni4j {
  stop-color: var(--svg-color--c29a88, #C29A88);
}

.fj0i7pb1f {
  stop-color: var(--svg-color--523d3b, #523D3B);
}

.fqu12ubrd {
  d: path("M13.19 11.747a1.146 1.146 0 0 0-1.104 1.448H14.3q.04-.147.041-.302a1.154 1.154 0 0 0-1.15-1.147");
}

.ft5dv1b6b {
  fill: none;
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g6v8l_bkd {
  stop-color: var(--svg-color--563937, #563937);
}

.g9lwhpb_s {
  stop-color: var(--svg-color--bb9373, #BB9373);
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.g9zuepbcp {
  stop-color: var(--svg-color--5a4344, #5A4344);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gd1of5hxe {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
}

.gi9rlrtiz {
  stop-color: var(--svg-color--cca58e, #CCA58E);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gpki0lbqt {
  stop-color: var(--svg-color--473033, #473033);
}

.gs7m3x8bv {
  stop-color: var(--svg-color--563937, #563937);
  stop-opacity: 0;
}

.gspwrdz1o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.836 9.76l2.017-.534");
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.i26rr_0fw {
  stop-color: var(--svg-color--b9321e, #B9321E);
}

.i4fzwzbpd {
  d: path("M7.152 19.747c.236-.43.228-.904-.201-1.14L4.342 17.18a.899.899 0 1 0-.856 1.581l2.622 1.404c.427.229.81.007 1.044-.418");
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.iitgd8bac {
  fill: var(--svg-color--000, #000);
  d: path("M18.144 12.893c0-.365.291-.657.656-.657a.654.654 0 0 1 .584.959h-1.162a.6.6 0 0 1-.078-.302");
}

.il1-__z0c {
  stop-color: var(--svg-color--a37f67, #A37F67);
}

.irc4pbbkk {
  fill: var(--svg-color--482d2c, #482D2C);
  d: path("M11.388 9.94a.35.35 0 0 1 .25-.426l2.086-.542a.349.349 0 1 1 .175.675l-2.086.542a.35.35 0 0 1-.425-.249");
}

.irfbnmbhq {
  stop-color: var(--svg-color--654f4c, #654F4C);
  stop-opacity: 0;
}

.iuvvk27wi {
  stop-color: var(--svg-color--874f5d, #874F5D);
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.j_0xl5h8m {
  d: path("M26.653 15.73c.527-.847 1.795-1.665 2.462-1.988a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.196c-2.06 1.273-1.875 1.785-2.645 3.097c-.355.604-1.177 1.112-1.556 1.284l-.474-.899c.53-.28 1.462-.711 2.094-1.725");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jdjo_xq8q {
  stop-color: var(--svg-color--c49a85, #C49A85);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jxp-9c9su {
  stop-color: var(--svg-color--473033, #473033);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k7n-rzhyc {
  stop-color: var(--svg-color--9d5e44, #9D5E44);
}

.kd1_xhb_o {
  stop-color: var(--svg-color--ff4c31, #FF4C31);
}

.kdpo-_boq {
  stop-color: var(--svg-color--9d5e44, #9D5E44);
  stop-opacity: 0;
}

.ktas3sbvn {
  stop-color: var(--svg-color--ffa842, #FFA842);
  stop-opacity: 0;
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.l3e-mtbcj {
  d: path("M9.513 10.96a2.08 2.08 0 0 0-1.784 2.053c0 1.103.864 2.005 1.953 2.063a101 101 0 0 1-.17-4.115");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m_8hwoksz {
  stop-color: var(--svg-color--f54617, #F54617);
}

.m7o64xbbx {
  stop-color: var(--svg-color--ff4923, #FF4923);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mhzmsi1xs {
  stop-color: var(--svg-color--996f67, #996F67);
}

.mq0gl8bsz {
  stop-color: var(--svg-color--e4764e, #E4764E);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.n7xbqubtn {
  stop-color: var(--svg-color--8c644c, #8C644C);
  stop-opacity: 0;
}

.nfsucybzx {
  fill: var(--svg-color--533634, #533634);
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.nl8aomm7e {
  d: path("M22.316 15.077q.129-2.05.237-4.099a2.067 2.067 0 0 1-.237 4.099");
}

.nsn8oes0z {
  d: path("M18.716 11.989c.081.11-.09.242-.283.387c-.194.146-.338.248-.42.138s.01-.315.203-.46c.195-.145.418-.174.5-.065");
}

.nv0opqb4i {
  stop-color: var(--svg-color--a4786e, #A4786E);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o6yqkabjh {
  stop-color: var(--svg-color--9b7667, #9B7667);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.omftgvbac {
  d: path("M9.798 16.906a5.03 5.03 0 0 0 4.99 4.374h2.424a5.03 5.03 0 0 0 4.99-4.374c.152-2.42.304-4.829.417-7.247a1.86 1.86 0 0 0-1.771-1.84h-1.799a3.11 3.11 0 0 1-2.84-1.852a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34c0 2.39.15 4.74.306 7.136");
}

.otf1mnoto {
  stop-color: var(--svg-color--985682, #985682);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.p2s973_gj {
  stop-color: var(--svg-color--53403e, #53403E);
}

.p6dlq8bal {
  stop-color: var(--svg-color--53403e, #53403E);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prd44wbso {
  stop-color: var(--svg-color--ff9540, #FF9540);
}

.psrrqcksv {
  stop-color: var(--svg-color--ff730a, #FF730A);
}

.ptziuobjj {
  stop-color: var(--svg-color--654f4c, #654F4C);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q5hvggldb {
  d: path("M14.237 12.758c0-.37-.3-.617-.382-.692l-.37.358l.227.464z");
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q9mg64b4e {
  stop-color: var(--svg-color--f35e74, #F35E74);
}

.q9rihsbeb {
  fill: var(--svg-color--88014d, #88014D);
  d: path("M15.989 19.458c.791 0 1.433-.688 1.433-1.537c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxiqgebpn {
  stop-color: var(--svg-color--ff6732, #FF6732);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r80e5wbfg {
  stop-color: var(--svg-color--8c644c, #8C644C);
}

.rbbulnz3l {
  d: path("M16.294 6.143a3 3 0 0 1-.085-.176a.85.85 0 0 0-.79-.537h-1.635c-2.37 0-4.292 1.942-4.292 4.34v.353c-.436-.333-.986-1.033-.986-2.168c0-1.376 1.004-2.072 1.645-2.516c.18-.125.332-.23.425-.325l.128-.135c.448-.476 1.248-1.324 2.645-1.695a7.2 7.2 0 0 1 2.167-.203c.472.026.805.434.805.907v2.137z");
}

.rbkr51v-c {
  stop-color: var(--svg-color--ff730a, #FF730A);
  stop-opacity: 0;
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s0h6qabck {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.37 12.689l-.815 2.36c-.139.486.196.972.67.972h1.009c.474 0 .808-.493.669-.972l-.683-2.36c-.146-.524-.696-.524-.85 0");
}

.s3mfozy-p {
  stop-color: var(--svg-color--c49a85, #C49A85);
  stop-opacity: 0;
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.smo9u60ba {
  stop-color: var(--svg-color--ffa842, #FFA842);
}

.sy-f5ccgl {
  stop-color: var(--svg-color--e76b2f, #E76B2F);
}

.t-faq4izi {
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.t0_upib5g {
  d: path("M19.823 12.744a1.1 1.1 0 0 0-.298-.596l-.335.367l.151.294z");
}

.tmrtimg7x {
  d: path("M22.367 14.24q.076-1.221.142-2.444a1.227 1.227 0 0 1-.142 2.445");
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

.u8owb3akc {
  stop-color: var(--svg-color--a86e75, #A86E75);
}

.ub8ckabiz {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.924 11.398c-.838 0-1.547.578-1.74 1.36a.352.352 0 0 0 .344.437h2.866a.296.296 0 0 0 .291-.35a1.8 1.8 0 0 0-1.76-1.447");
}

.uhgt8fd7p {
  stop-color: var(--svg-color--8e6d54, #8E6D54);
  stop-opacity: 0;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.utrmehb1k {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.066 11.398c.839 0 1.547.578 1.74 1.36a.352.352 0 0 1-.344.437h-2.865a.296.296 0 0 1-.292-.35a1.795 1.795 0 0 1 1.76-1.447");
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v1z821b6o {
  stop-color: var(--svg-color--eb4e66, #EB4E66);
  stop-opacity: 0;
}

.v3bwo4btz {
  stop-color: var(--svg-color--ff7132, #FF7132);
}

.v3eonib4h {
  d: path("M20.44 16.106L5.033 23.28a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.705l15.407-7.182c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v4bxf0bxm {
  stop-color: var(--svg-color--b89377, #B89377);
}

.vzkeadcof {
  fill: var(--svg-color--482d2c, #482D2C);
  d: path("M20.711 9.94a.35.35 0 0 0-.25-.426l-2.086-.542a.349.349 0 1 0-.175.675l2.086.542a.35.35 0 0 0 .425-.249");
}

.vzmhuwavr {
  stop-color: var(--svg-color--f35e74, #F35E74);
  stop-opacity: 0;
}

.vzu9-mfnh {
  d: path("m23 16.078l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
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

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.wbpqeub1g {
  stop-color: var(--svg-color--996f67, #996F67);
  stop-opacity: 0;
}

.wkq1lrbro {
  stop-color: var(--svg-color--6b4e4e, #6B4E4E);
}

.wq0eljlkx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.263 9.76l-2.017-.534");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xrn2z6b6u {
  stop-color: var(--svg-color--ff8c11, #FF8C11);
  stop-opacity: 0;
}

.xva86cc4j {
  stop-color: var(--svg-color--c19172, #C19172);
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.y2jvwtu2p {
  fill: var(--svg-color--563936, #563936);
  d: path("m22.69 10.474l-.038-.811c-.014-.98-.824-1.79-1.805-1.83H19.05a3.11 3.11 0 0 1-2.728-1.619s-.16-.372-.258-.96c-.165-.989.75-1.717 1.74-1.554c1.354.222 3.024.66 4.218 1.438c2.24 1.462 1.848 4.095.669 5.336");
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.yutka0byn {
  stop-color: var(--svg-color--a86e75, #A86E75);
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

.zcueg9l3v {
  stop-color: var(--svg-color--c29a88, #C29A88);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
