<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYyHL3b)" class="wbesghbsc"/><path fill="url(#iD3CQuV)" class="wbesghbsc"/><path fill="url(#i0eGEHc)" class="wbesghbsc"/><path fill="url(#iJjEEfb)" class="wbesghbsc"/><rect fill="url(#iPvLewb)" class="k0u_jiclw"/><rect fill="url(#iyWgbSb)" class="k0u_jiclw"/><path class="ys9d3layu"/><path fill="url(#i3c3xTk)" class="sbavx8t0s"/><path fill="url(#iEVQuac)" class="sbavx8t0s"/><path fill="url(#iDoCfjd)" class="sbavx8t0s"/><path clip-rule="evenodd" class="akci4zb7z"/><path fill="url(#ivCpyZd)" clip-rule="evenodd" class="cd6y0ggyz"/><path fill="url(#i8YNODd)" clip-rule="evenodd" class="cd6y0ggyz"/><path fill="url(#iy9UPyX)" clip-rule="evenodd" class="cd6y0ggyz"/><path clip-rule="evenodd" class="q3e9cwb1a"/><path fill="url(#io09jVc)" clip-rule="evenodd" class="vk8hrsbvs"/><path fill="url(#iwDkCUk)" clip-rule="evenodd" class="vk8hrsbvs"/><path fill="url(#iZzhQ0l)" clip-rule="evenodd" class="vk8hrsbvs"/><path clip-rule="evenodd" class="miur4tfgq"/><path fill="url(#ivng8xb)" clip-rule="evenodd" class="vgm-gsbgf"/><path fill="url(#iArt9cJ)" clip-rule="evenodd" class="vgm-gsbgf"/><path fill="url(#iwMpbKd)" clip-rule="evenodd" class="vgm-gsbgf"/><g filter="url(#is8P0ge)"><path clip-rule="evenodd" class="ka5d3-29r"/><path fill="url(#i16TEKd)" clip-rule="evenodd" class="p2203fooq"/><path fill="url(#i0rYhed)" clip-rule="evenodd" class="p2203fooq"/><path fill="url(#iwjhwyb)" clip-rule="evenodd" class="p2203fooq"/></g><g filter="url(#in99rLc)"><path class="ulg9ftbzs"/><path fill="url(#itbCo4c)" class="re1obfd9f"/><path fill="url(#iZme9td)" class="re1obfd9f"/><path fill="url(#i5QAbyd)" class="re1obfd9f"/><path fill="url(#i1WdfqD)" class="re1obfd9f"/></g><path fill="url(#ihypGoc)" class="qf76irbfe"/><path fill="url(#izn9Vgc)" class="qf76irbfe"/><g filter="url(#is7eCJb)"><path fill="url(#ikre9Ie)" class="dvtg4zf3u"/><path fill="url(#iugpZyb)" class="dvtg4zf3u"/><path fill="url(#iDMogTY)" class="dvtg4zf3u"/><path fill="url(#iGP7qrn)" class="dvtg4zf3u"/></g><g filter="url(#izkHvUb)"><circle fill="url(#ia4tCYc)" class="d05hunb3c"/></g><g filter="url(#i2xWrAZ)"><circle fill="url(#ip2HDxe)" class="t7om_ld0m"/></g><g filter="url(#i4Gjeob)"><circle fill="url(#ikxEXeO)" class="p0pnfrbyb"/><circle fill="url(#i8ll50c)" class="p0pnfrbyb"/></g><g filter="url(#iAxzk0c)"><circle class="yojcmql5k"/><circle fill="url(#i97OuQd)" class="ap6mombgy"/><circle fill="url(#iUqDDOc)" class="ap6mombgy"/></g><g filter="url(#iheTyNQ)"><path fill="url(#i1n91Sb)" class="n8922ibmm"/><path fill="url(#iTeVv9d)" class="n8922ibmm"/><path fill="url(#i750Pmc)" class="n8922ibmm"/><path fill="url(#i23TcNc)" class="n8922ibmm"/><path fill="url(#ihiExAb)" class="n8922ibmm"/><path fill="url(#iR6Ii3Y)" class="n8922ibmm"/></g><g filter="url(#iUeKNtb)"><path fill="url(#i0u2oCd)" class="r0vtrtydy"/></g><g filter="url(#iCSV1ke)"><path class="d2flzhb9p"/><path fill="url(#iljLccd)" class="oa9vj7bih"/><path fill="url(#iNMUyld)" class="oa9vj7bih"/><path fill="url(#ikalsSj)" class="oa9vj7bih"/><path fill="url(#iZ5uxwd)" class="oa9vj7bih"/></g><g filter="url(#i96DLde)"><path class="w5p9zpbvs"/></g><g filter="url(#inGdtub)"><path class="hcbyhn69b"/><path fill="url(#iPqV6xe)" class="g0zv3gb-j"/><path fill="url(#iFtaJac)" class="g0zv3gb-j"/><path fill="url(#iOmnk2b)" class="g0zv3gb-j"/><path fill="url(#iyCcXTb)" class="g0zv3gb-j"/></g><path fill="url(#iQUjTdb)" class="g0zv3gb-j"/><path stroke="url(#iUAhque)" class="euaip6hzi"/><g filter="url(#iSFmY7d)"><path class="e-o325bgq"/></g><g filter="url(#iLkmmRx)"><path class="us66zbxft"/></g><path class="tghtbpmsh"/><path fill="url(#itNzrWc)" class="q8_rfeb-c"/><path class="vs53x_brk"/><g filter="url(#i4WIUIW)"><path class="fli-fjbrs"/><path fill="url(#immoSXb)" class="umqrm-bir"/></g><g filter="url(#iGD2ajd)"><path fill="url(#ijKN1Le)" class="dyr3-nbvz"/></g><path class="leug58nxp"/><path fill="url(#iF96KYd)" class="yev9el_pf"/><path class="a6k3pwbhe"/><g filter="url(#iu24v3b)"><path fill="url(#i5JBUte)" class="upligxbem"/></g><g filter="url(#iqdDYCe)"><ellipse transform="rotate(-27.914 9.263 12.17)" class="jqxyimlwc"/><ellipse fill="url(#isDnO5c)" transform="rotate(-27.914 9.263 12.17)" class="q0x-4q4wr"/></g><g filter="url(#ihmRiEc)"><path stroke="url(#irY1egd)" class="izn6r5hxy"/></g><g filter="url(#il7KIIe)"><path stroke="url(#iklAEze)" class="xv5cmou-l"/></g><g filter="url(#iSvkoBd)"><path stroke="url(#iplWr4c)" class="h2oc2jbms"/></g><defs><radialGradient id="iD3CQuV" cx="0" cy="0" r="1" gradientTransform="rotate(-128.9 17.805 9.737)scale(14.3752 17.7454)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="qttx_q5hd"/><stop offset="1" class="jj70p7yrg"/></radialGradient><radialGradient id="i0eGEHc" cx="0" cy="0" r="1" gradientTransform="rotate(80.311 -6.022 15.957)scale(6.49895 15.3845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y57vb-6vx"/><stop offset="1" class="k_v_c_b6y"/></radialGradient><radialGradient id="iJjEEfb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91897 -8.2177 4.4235 -2.64783 21.14 29.738)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="htrw0pbkw"/><stop offset="1" class="hsbr_ca-x"/></radialGradient><radialGradient id="iPvLewb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.21875 -4.41943 0 12.394 20.895)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="fbf66108l"/><stop offset="1" class="m2a4dvbzi"/></radialGradient><radialGradient id="iyWgbSb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 4.378 -5.06565 2.3503 11.38 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="zhvue1b_t"/><stop offset=".914" class="rq0vvgb8y"/></radialGradient><radialGradient id="i3c3xTk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14487 1.17029 -.21646 -.21176 23.936 13.361)" gradientUnits="userSpaceOnUse"><stop class="bo9hvcbia"/><stop offset="1" class="oaq7jebib"/></radialGradient><radialGradient id="iEVQuac" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.508 -8.446)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="xi-m2-bbj"/><stop offset="1" class="k6zvonvjc"/></radialGradient><radialGradient id="iDoCfjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10937 .79688 -1.21512 -.16677 23.835 14.919)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="wbqt2qbli"/><stop offset="1" class="dne0v_i-i"/></radialGradient><radialGradient id="ivCpyZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.69262 .16923 -.21445 -.87773 29.638 14.425)" gradientUnits="userSpaceOnUse"><stop class="mndo9dbtd"/><stop offset="1" class="v_r0ckpor"/></radialGradient><radialGradient id="iy9UPyX" cx="0" cy="0" r="1" gradientTransform="matrix(.06006 .3203 -3.15066 .59077 27.177 13.904)" gradientUnits="userSpaceOnUse"><stop class="rw_zxacrw"/><stop offset="1" class="rbdoa8bvc"/></radialGradient><radialGradient id="io09jVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.68924 .16508 -.20552 -.85808 30.216 14.736)" gradientUnits="userSpaceOnUse"><stop class="mndo9dbtd"/><stop offset="1" class="v_r0ckpor"/></radialGradient><radialGradient id="iZzhQ0l" cx="0" cy="0" r="1" gradientTransform="matrix(.04435 .29983 -3.0061 .44465 27.783 14.164)" gradientUnits="userSpaceOnUse"><stop class="rw_zxacrw"/><stop offset="1" class="rbdoa8bvc"/></radialGradient><radialGradient id="ivng8xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69149 .15913 -.19118 -.83072 29.934 15.198)" gradientUnits="userSpaceOnUse"><stop class="mndo9dbtd"/><stop offset="1" class="v_r0ckpor"/></radialGradient><radialGradient id="iwMpbKd" cx="0" cy="0" r="1" gradientTransform="matrix(.0445 .28907 -3.01051 .46342 27.493 14.645)" gradientUnits="userSpaceOnUse"><stop class="rw_zxacrw"/><stop offset="1" class="rbdoa8bvc"/></radialGradient><radialGradient id="i16TEKd" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.83 9.319)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="i0rYhed" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.688 23.569)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="itbCo4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.96409 .10438 -.11015 -1.0174 29.216 16.002)" gradientUnits="userSpaceOnUse"><stop class="gt1tn_3fh"/><stop offset="1" class="vow3367aq"/></radialGradient><radialGradient id="iZme9td" cx="0" cy="0" r="1" gradientTransform="matrix(.01563 .10937 -1.46562 .20938 27.337 15.465)" gradientUnits="userSpaceOnUse"><stop class="cfjqw6b0c"/><stop offset="1" class="jc2cbvyjw"/><stop offset="1" class="dnevgg8-j"/></radialGradient><radialGradient id="i5QAbyd" cx="0" cy="0" r="1" gradientTransform="rotate(17.232 -40.716 76.879)scale(3.05919 2.83525)" gradientUnits="userSpaceOnUse"><stop class="afpbwtbex"/><stop offset="1" class="oax9jn75q"/></radialGradient><radialGradient id="i1WdfqD" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 .37501 -.25742 -1.71607 26.287 15.2)" gradientUnits="userSpaceOnUse"><stop class="y7cm8rbzs"/><stop offset="1" class="qvei5-bgn"/></radialGradient><radialGradient id="ihypGoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05458 -2.63643 0 24.104 17.65)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="agu36v23f"/><stop offset="1" class="iguvvnbvp"/></radialGradient><radialGradient id="iDMogTY" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 0 0 -.57813 24.721 19.489)" gradientUnits="userSpaceOnUse"><stop class="plpsytzme"/><stop offset="1" class="r1ahmww7a"/></radialGradient><radialGradient id="ia4tCYc" cx="0" cy="0" r="1" gradientTransform="matrix(2.22935 0 0 3.90139 4.23 13.158)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="i8ll50c" cx="0" cy="0" r="1" gradientTransform="matrix(1.05023 -.76473 .87284 1.1987 18.91 12.821)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="i97OuQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.04333 -1.91895 1.12316 .61067 18.384 14.201)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iUqDDOc" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -6.78 28.995)scale(.46348 .59749)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iTeVv9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.1353 -15.1156 0 12.42 10.712)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="xlsr65bou"/><stop offset="1" class="s0nym4b3v"/></radialGradient><radialGradient id="ihiExAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6605 2.04368 0 15.363 11.543)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iR6Ii3Y" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.76694 2.19734 0 9.572 11.5)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iljLccd" cx="0" cy="0" r="1" gradientTransform="matrix(1.01354 -3.75605 1.39286 .37585 17.903 7.941)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iNMUyld" cx="0" cy="0" r="1" gradientTransform="matrix(4.859 .44715 -.24043 2.61266 15.816 5.705)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ikalsSj" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1332 -3.30372 0 12.383 2.23)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iZ5uxwd" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 18.74 -.957)scale(4.84142 7.58492)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iyCcXTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25014 -.80364 0 12.798 15.199)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="itNzrWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03045 -1.63905 0 15.15 12.291)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="immoSXb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.466 2.56)scale(.48046 .66148)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iF96KYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0305 -1.63913 0 9.608 12.291)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="isDnO5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.00983 -.62753 .75432 -.01181 9.244 12.57)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iYyHL3b" x1="12.382" x2="12.382" y1="30.864" y2="25.958" gradientUnits="userSpaceOnUse"><stop class="oeqqncchi"/><stop offset="1" class="rmb_a4bif"/></linearGradient><linearGradient id="i8YNODd" x1="27.641" x2="27.508" y1="15.973" y2="14.716" gradientUnits="userSpaceOnUse"><stop offset=".217" class="sym6onb1o"/><stop offset="1" class="a94kt-bpo"/></linearGradient><linearGradient id="iwDkCUk" x1="28.552" x2="28.101" y1="16.309" y2="15.024" gradientUnits="userSpaceOnUse"><stop offset=".217" class="sym6onb1o"/><stop offset="1" class="a94kt-bpo"/></linearGradient><linearGradient id="iArt9cJ" x1="27.941" x2="27.823" y1="16.652" y2="15.47" gradientUnits="userSpaceOnUse"><stop offset=".217" class="sym6onb1o"/><stop offset="1" class="a94kt-bpo"/></linearGradient><linearGradient id="iwjhwyb" x1="24.588" x2="26.182" y1="17.102" y2="16.79" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="izn9Vgc" x1="23.483" x2="23.483" y1="18.601" y2="18.426" gradientUnits="userSpaceOnUse"><stop offset=".316" class="jydl9dbrr"/><stop offset="1" class="aygc7mb2y"/><stop offset="1" class="h9u6zibfw"/></linearGradient><linearGradient id="ikre9Ie" x1="24.354" x2="24.354" y1="19.665" y2="38.977" gradientUnits="userSpaceOnUse"><stop class="uu1puyblk"/><stop offset=".621" class="je7mxqbyx"/></linearGradient><linearGradient id="iugpZyb" x1="27.768" x2="22.341" y1="29.192" y2="29.192" gradientUnits="userSpaceOnUse"><stop class="kd-yr7fuk"/><stop offset=".458" class="ks-d0_bdl"/><stop offset="1" class="kd-yr7fuk"/></linearGradient><linearGradient id="iGP7qrn" x1="23.312" x2="23.312" y1="18.505" y2="19.54" gradientUnits="userSpaceOnUse"><stop offset=".366" class="m9y_tybxe"/><stop offset="1" class="iq0cs8i_e"/></linearGradient><linearGradient id="ip2HDxe" x1="6.351" x2="5.537" y1="13.512" y2="13.512" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="ikxEXeO" x1="19.817" x2="18.777" y1="11.771" y2="14.993" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="i1n91Sb" x1="17.51" x2="7.808" y1="13.652" y2="15.098" gradientUnits="userSpaceOnUse"><stop class="ydq0kpc8x"/><stop offset="1" class="e-sxlzbkb"/></linearGradient><linearGradient id="i750Pmc" x1="5.214" x2="9.481" y1="15.593" y2="15.738" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="i23TcNc" x1="5.528" x2="7.918" y1="17.078" y2="16.992" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="i0u2oCd" x1="11.707" x2="22.053" y1="9.861" y2="6.157" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iPqV6xe" x1="11.285" x2="12.477" y1="14.49" y2="14.49" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iFtaJac" x1="13.575" x2="12.272" y1="14.9" y2="14.881" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="iOmnk2b" x1="12.63" x2="12.63" y1="15.843" y2="15.115" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iQUjTdb" x1="12.542" x2="12.542" y1="15.896" y2="15.683" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="iUAhque" x1="11.065" x2="11.618" y1="17.895" y2="17.021" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="ijKN1Le" x1="16.139" x2="15.74" y1="12.36" y2="12.605" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5JBUte" x1="10.553" x2="10.154" y1="12.36" y2="12.605" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irY1egd" x1="16.159" x2="15.625" y1="9.642" y2="8.551" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iklAEze" x1="9.42" x2="7.909" y1="9.479" y2="8.846" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iplWr4c" x1="6.46" x2="6.46" y1="6.92" y2="9.66" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><filter id="is8P0ge" width="7.879" height="3.847" x="21.258" y="13.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="in99rLc" width="7.879" height="3.847" x="21.258" y="13.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.67451 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="is7eCJb" width="6.491" height="11.844" x="20.116" y="18.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.541176 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="izkHvUb" width="4.442" height="4.242" x="4.23" y="11.037" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="i2xWrAZ" width="3.528" height="3.528" x="4.587" y="11.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".25"/></filter><filter id="i4Gjeob" width="4.492" height="4.492" x="16.316" y="10.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="iAxzk0c" width="3.528" height="3.528" x="16.672" y="11.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".25"/></filter><filter id="iheTyNQ" width="13.179" height="15.53" x="5.83" y="6.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="iUeKNtb" width="9.394" height="7.896" x="10.598" y="4.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation="1"/></filter><filter id="iCSV1ke" width="16.009" height="10.718" x="4.378" y="1.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="i96DLde" width="3.736" height="4.906" x="10.211" y="11.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".375"/></filter><filter id="inGdtub" width="2.884" height="3.906" x="10.94" y="12.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".125"/></filter><filter id="iSFmY7d" width="3.718" height="2.271" x="13.884" y="8.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="iLkmmRx" width="3.718" height="2.271" x="7.345" y="8.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3803"/></filter><filter id="i4WIUIW" width=".945" height=".83" x="14.245" y="11.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".05"/></filter><filter id="iGD2ajd" width="1.024" height="1.052" x="15.339" y="11.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".1"/></filter><filter id="iu24v3b" width="1.145" height="1.213" x="9.696" y="11.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".1"/></filter><filter id="iqdDYCe" width="1.106" height=".841" x="8.71" y="11.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".05"/></filter><filter id="ihmRiEc" width="3.849" height="2.048" x="13.742" y="8.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".25"/></filter><filter id="il7KIIe" width="3.948" height="2.12" x="7.111" y="8.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".25"/></filter><filter id="iSvkoBd" width="1.078" height="2.68" x="5.921" y="6.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3803" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-tipping-hand-light" /></template>
<style>
.a6k3pwbhe {
  fill: var(--svg-color--000, #000);
  d: path("M10.255 12.819c0-.36-.29-.65-.65-.65a.647.647 0 0 0-.577.949h1.15a.64.64 0 0 0 .076-.299");
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.a94kt-bpo {
  stop-color: var(--svg-color--d79e92, #D79E92);
  stop-opacity: 0;
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
}

.afpbwtbex {
  stop-color: var(--svg-color--e9b091, #E9B091);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.agu36v23f {
  stop-color: var(--svg-color--499cd4, #499CD4);
}

.akci4zb7z {
  fill: var(--svg-color--f1c1a6, #F1C1A6);
  fill-rule: evenodd;
  d: path("M29.625 14.444a.85.85 0 0 1-.69.984c-.147.026-.337.066-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.082.715-.142a.85.85 0 0 1 .985.69");
}

.ap6mombgy {
  cx: 18.436px;
  cy: 13.158px;
  r: 1.264px;
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.aygc7mb2y {
  stop-color: var(--svg-color--327aa5, #327AA5);
  stop-opacity: 0;
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bo9hvcbia {
  stop-color: var(--svg-color--ffd6bb, #FFD6BB);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.cd6y0ggyz {
  fill-rule: evenodd;
  d: path("M29.625 14.444a.85.85 0 0 1-.69.984c-.147.026-.337.066-.562.113c-.653.136-1.594.332-2.606.428a.85.85 0 1 1-.16-1.693c.909-.086 1.678-.246 2.318-.38q.39-.082.715-.142a.85.85 0 0 1 .985.69");
}

.cfjqw6b0c {
  stop-color: var(--svg-color--e9b4a0, #E9B4A0);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d05hunb3c {
  cx: 6.351px;
  cy: 13.158px;
  r: 2.121px;
}

.d2flzhb9p {
  fill: var(--svg-color--242324, #242324);
  d: path("m18.505 4.928l.545.272c.954.474 1.499 1.558 1.294 2.71l-.75 3.862c-.066.399-.33.667-.726.677h-.023s.068-1.152.137-1.83c.055-.55-.041-.717-.546-1.219c-.272-.27-.477-.677-.477-1.084V7.232c0-.339-.272-.61-.545-.677c-.818-.204-2.521-.542-4.974-.542s-4.157.338-4.975.542c-.34.067-.545.338-.545.677v1.084c0 .407-.136.813-.477 1.084l-.204.204c-.273.203-.41.61-.41.948c.069.745.137 1.83.137 1.83q-.031 0-.062-.003a.805.805 0 0 1-.756-.675l-.75-3.862c-.135-1.084.41-2.168 1.364-2.642l.545-.272c.34-.203.681-.474 1.022-.745l1.227-1.287c.75-.678 1.84-.881 2.794-.407a3.74 3.74 0 0 0 2.112 0c1.022-.338 2.18-.067 2.998.678l1.022 1.016c.273.339.614.542 1.023.745");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dne0v_i-i {
  stop-color: var(--svg-color--fdceb3, #FDCEB3);
  stop-opacity: 0;
}

.dnevgg8-j {
  stop-color: var(--svg-color--e9b4a0, #E9B4A0);
  stop-opacity: 0;
}

.dvtg4zf3u {
  d: path("M20.116 19.305a.8.8 0 0 1 .8-.8h4.791a.8.8 0 0 1 .8.8V30.35h-6.39z");
}

.dyr3-nbvz {
  d: path("M16.163 12.67a1.07 1.07 0 0 0-.294-.588l-.33.362l.149.29z");
}

.e-o325bgq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m17.108 9.702l-.002-.001l-.002-.002l-.006-.005l-.015-.012a2 2 0 0 0-.197-.136a3.3 3.3 0 0 0-.533-.268a3.6 3.6 0 0 0-1.896-.201a.678.678 0 0 0 .211 1.34c.506-.08.91.013 1.187.122a2 2 0 0 1 .391.21a.678.678 0 0 0 .862-1.047");
}

.e-sxlzbkb {
  stop-color: var(--svg-color--daa594, #DAA594);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.euaip6hzi {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.646 16.673a.244.244 0 0 0-.291.05a.224.224 0 0 0-.025.287a2.46 2.46 0 0 0 2.053 1.097c.861 0 1.618-.439 2.052-1.097a.23.23 0 0 0-.025-.29a.245.245 0 0 0-.29-.048a3.75 3.75 0 0 1-1.737.412c-.637 0-1.235-.15-1.737-.412Z");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fbf66108l {
  stop-color: var(--svg-color--b88790, #B88790);
}

.fli-fjbrs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.07 11.925c.08.108-.088.24-.28.383s-.334.245-.415.137s.01-.312.201-.456c.192-.143.413-.172.494-.064");
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g0zv3gb-j {
  d: path("m11.897 12.795l-.675 2.16a.685.685 0 0 0 .661.888h.999a.687.687 0 0 0 .661-.889l-.675-2.159c-.145-.478-.82-.478-.971 0");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gt1tn_3fh {
  stop-color: var(--svg-color--ffd3bf, #FFD3BF);
}

.h2oc2jbms {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.624 7.046v1.14c-.01.189-.09.61-.328.79");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.h9u6zibfw {
  stop-color: var(--svg-color--166599, #166599);
  stop-opacity: 0;
}

.hcbyhn69b {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m11.897 12.795l-.675 2.16a.685.685 0 0 0 .661.888h.999a.687.687 0 0 0 .661-.889l-.675-2.159c-.145-.478-.82-.478-.971 0");
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hsbr_ca-x {
  stop-color: var(--svg-color--1b79d5, #1B79D5);
  stop-opacity: 0;
}

.htrw0pbkw {
  stop-color: var(--svg-color--055bde, #055BDE);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.iguvvnbvp {
  stop-color: var(--svg-color--2e76ab, #2E76AB);
}

.iq0cs8i_e {
  stop-color: var(--svg-color--1fa0ec, #1FA0EC);
  stop-opacity: 0;
}

.izn6r5hxy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.492 9.519c.547-.096 1.612-.069 2.35.505");
}

.jc2cbvyjw {
  stop-color: var(--svg-color--886658, #886658);
  stop-opacity: 0;
}

.je7mxqbyx {
  stop-color: var(--svg-color--269eff, #269EFF);
}

.jj70p7yrg {
  stop-color: var(--svg-color--3797ff, #3797FF);
  stop-opacity: 0;
}

.jqxyimlwc {
  cx: 9.263px;
  cy: 12.17px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.495px;
  ry: 0.25px;
}

.jydl9dbrr {
  stop-color: var(--svg-color--166599, #166599);
}

.k_v_c_b6y {
  stop-color: var(--svg-color--2094e3, #2094E3);
  stop-opacity: 0;
}

.k0u_jiclw {
  width: 4.898px;
  height: 6.68px;
  x: 9.944px;
  y: 17.271px;
  rx: 2.449px;
}

.k6zvonvjc {
  stop-color: var(--svg-color--dea689, #DEA689);
}

.ka5d3-29r {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M25.57 14.279c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.247c.917-.103 1.759-.207 2.235-.31a.825.825 0 0 0-.346-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.492.05");
}

.kd-yr7fuk {
  stop-color: var(--svg-color--3ab3ff, #3AB3FF);
  stop-opacity: 0;
}

.ks-d0_bdl {
  stop-color: var(--svg-color--3ab3ff, #3AB3FF);
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.leug58nxp {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.343 11.34c-.83 0-1.53.572-1.721 1.345a.348.348 0 0 0 .34.433h2.834c.18 0 .324-.165.288-.345a1.78 1.78 0 0 0-1.741-1.433");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m2a4dvbzi {
  stop-color: var(--svg-color--d7a49a, #D7A49A);
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m9y_tybxe {
  stop-color: var(--svg-color--1fa0ec, #1FA0EC);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.miur4tfgq {
  fill: var(--svg-color--f1c1a6, #F1C1A6);
  fill-rule: evenodd;
  d: path("M29.932 15.33a.85.85 0 0 1-.772.92c-.322.029-.74.088-1.26.162l-.03.005c-.526.074-1.134.16-1.788.23a.85.85 0 1 1-.182-1.69a50 50 0 0 0 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.mndo9dbtd {
  stop-color: var(--svg-color--ffd4bc, #FFD4BC);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.n8922ibmm {
  d: path("M5.83 10.552c0-.339.136-.745.409-.948l.204-.204c.34-.27.477-.677.477-1.084V7.232c0-.339.205-.61.545-.677c.818-.204 2.522-.542 4.975-.542s4.156.338 4.974.542c.273.067.545.338.545.677v1.084c0 .407.205.813.477 1.084c.638.447.598.693.545 1.22c-.068.677-.136 1.83-.136 1.83l.023-.001l-.338 5.029c-.204 2.248-1.97 3.815-4.078 3.815h-4.078c-2.176 0-3.875-1.567-4.079-3.815c-.177-2.308-.255-4.622-.465-6.926");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.oa9vj7bih {
  d: path("m18.505 4.928l.545.272c.954.474 1.499 1.558 1.294 2.71l-.75 3.862c-.066.399-.33.667-.726.677h-.023s.068-1.152.137-1.83c.055-.55-.041-.717-.546-1.219c-.272-.27-.477-.677-.477-1.084V7.232c0-.339-.272-.61-.545-.677c-.818-.204-2.521-.542-4.974-.542s-4.157.338-4.975.542c-.34.067-.545.338-.545.677v1.084c0 .407-.136.813-.477 1.084l-.204.204c-.273.203-.41.61-.41.948c.069.745.137 1.83.137 1.83q-.031 0-.062-.003a.805.805 0 0 1-.756-.675l-.75-3.862c-.135-1.084.41-2.168 1.364-2.642l.545-.272c.34-.203.681-.474 1.022-.745l1.227-1.287c.75-.678 1.84-.881 2.794-.407a3.74 3.74 0 0 0 2.112 0c1.022-.338 2.18-.067 2.998.678l1.022 1.016c.273.339.614.542 1.023.745");
}

.oaq7jebib {
  stop-color: var(--svg-color--ebb99c, #EBB99C);
}

.oax9jn75q {
  stop-color: var(--svg-color--e9b091, #E9B091);
  stop-opacity: 0;
}

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeqqncchi {
  stop-color: var(--svg-color--2c9cff, #2C9CFF);
}

.p0pnfrbyb {
  cx: 18.436px;
  cy: 13.158px;
  r: 2.121px;
}

.p2203fooq {
  fill-rule: evenodd;
  d: path("M25.57 14.279c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.867-.153 1.175-.25c.243-.077.508-.16.967-.247c.917-.103 1.759-.207 2.235-.31a.825.825 0 0 0-.346-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.492.05");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plpsytzme {
  stop-color: var(--svg-color--48b5ff, #48B5FF);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q0x-4q4wr {
  cx: 9.263px;
  cy: 12.17px;
  rx: 0.495px;
  ry: 0.25px;
}

.q3e9cwb1a {
  fill: var(--svg-color--f1c1a6, #F1C1A6);
  fill-rule: evenodd;
  d: path("M30.203 14.772a.85.85 0 0 1-.689.985q-.18.031-.413.076a30 30 0 0 1-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.097 1.89-.26 2.552-.383l.459-.085a.85.85 0 0 1 .984.69");
}

.q8_rfeb-c {
  d: path("M15.153 11.686a1.134 1.134 0 0 1 1.092 1.432h-2.19a1.138 1.138 0 0 1 1.098-1.432");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qf76irbfe {
  d: path("M21.015 17.81a.25.25 0 0 1 .25-.25h4.093a.25.25 0 0 1 .25.25v1.64h-4.593z");
}

.qttx_q5hd {
  stop-color: var(--svg-color--3797ff, #3797FF);
}

.qvei5-bgn {
  stop-color: var(--svg-color--ffd2b6, #FFD2B6);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0vtrtydy {
  d: path("m17.418 6.013l-3.91 1.303a1.33 1.33 0 0 0 .598 2.58l3.887-.52z");
}

.r1ahmww7a {
  stop-color: var(--svg-color--48b5ff, #48B5FF);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rbdoa8bvc {
  stop-color: var(--svg-color--dda695, #DDA695);
  stop-opacity: 0;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.re1obfd9f {
  d: path("M25.57 14.279c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.874-.095 1.183-.192c.242-.076.5-.218.96-.305c.916-.103 1.758-.207 2.233-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.492.05");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rmb_a4bif {
  stop-color: var(--svg-color--1d8fdf, #1D8FDF);
}

.rq0vvgb8y {
  stop-color: var(--svg-color--d39f86, #D39F86);
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rw_zxacrw {
  stop-color: var(--svg-color--dda695, #DDA695);
}

.s0nym4b3v {
  stop-color: var(--svg-color--a77d91, #A77D91);
}

.sbavx8t0s {
  d: path("M22.03 14.138c-.554.649-.74 1.417-.761 1.758l1.847-.102l.887-1.183c.29-.383.54-1.02-.035-1.442c-.466-.342-.945-.066-1.102.106c-.062.057-.248.245-.836.863");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.sym6onb1o {
  stop-color: var(--svg-color--d79e92, #D79E92);
}

.t7om_ld0m {
  cx: 6.351px;
  cy: 13.158px;
  r: 1.264px;
}

.tghtbpmsh {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.416 11.34c.83 0 1.53.572 1.72 1.345a.348.348 0 0 1-.34.433h-2.833a.292.292 0 0 1-.288-.345a1.775 1.775 0 0 1 1.741-1.433");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ulg9ftbzs {
  fill: var(--svg-color--f4c2ab, #F4C2AB);
  d: path("M25.57 14.279c-.33.036-.77.085-1.598.155l-.229.018c-1.06.083-2.273.178-2.466 1.345c-.2 1.203 1.183 2.142 2.831 1.954c.594-.067.874-.095 1.183-.192c.242-.076.5-.218.96-.305c.916-.103 1.758-.207 2.233-.31a.825.825 0 0 0-.345-1.612c-.37.079-1.053.166-1.874.26l-.203-1.364c-.161.014-.31.03-.492.05");
}

.umqrm-bir {
  d: path("M15.07 11.925c.08.108-.088.24-.28.383s-.334.245-.415.137s.01-.312.201-.456c.192-.143.413-.172.494-.064");
}

.upligxbem {
  d: path("M10.64 12.686c0-.367-.297-.61-.377-.684l-.367.354l.226.459z");
}

.us66zbxft {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m7.589 9.703l.002-.001l.002-.002l.006-.005l.015-.012a2 2 0 0 1 .197-.136c.126-.08.306-.178.533-.268a3.6 3.6 0 0 1 1.896-.201a.678.678 0 0 1-.211 1.34c-.506-.08-.91.013-1.186.122a2 2 0 0 0-.392.21a.678.678 0 0 1-.862-1.046");
}

.uu1puyblk {
  stop-color: var(--svg-color--2595fb, #2595FB);
}

.v_r0ckpor {
  stop-color: var(--svg-color--ffd4bc, #FFD4BC);
  stop-opacity: 0;
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.vgm-gsbgf {
  fill-rule: evenodd;
  d: path("M29.932 15.33a.85.85 0 0 1-.772.92c-.322.029-.74.088-1.26.162l-.03.005c-.526.074-1.134.16-1.788.23a.85.85 0 1 1-.182-1.69a50 50 0 0 0 1.73-.224l.064-.009a26 26 0 0 1 1.317-.167a.85.85 0 0 1 .92.772");
}

.vk8hrsbvs {
  fill-rule: evenodd;
  d: path("M30.203 14.772a.85.85 0 0 1-.689.985q-.18.031-.413.076a30 30 0 0 1-2.733.41a.85.85 0 1 1-.16-1.693c1.02-.097 1.89-.26 2.552-.383l.459-.085a.85.85 0 0 1 .984.69");
}

.vow3367aq {
  stop-color: var(--svg-color--ffd3bf, #FFD3BF);
  stop-opacity: 0;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vs53x_brk {
  fill: var(--svg-color--000, #000);
  d: path("M14.504 12.819c0-.36.289-.65.65-.65a.646.646 0 0 1 .576.949h-1.149a.6.6 0 0 1-.077-.299");
}

.w5p9zpbvs {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m12.033 13.003l-1.042 2.159c-.13.444.18.888.62.888h.936c.44 0 .75-.451.62-.888l-.633-2.16c-.135-.478-.36-.478-.501 0");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wbesghbsc {
  d: path("M12.382 20.298c-5.523 0-10 4.478-10 10v.051h20v-.05c0-5.523-4.477-10-10-10");
}

.wbqt2qbli {
  stop-color: var(--svg-color--fdceb3, #FDCEB3);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xi-m2-bbj {
  stop-color: var(--svg-color--dea689, #DEA689);
  stop-opacity: 0;
}

.xlsr65bou {
  stop-color: var(--svg-color--e0ad9b, #E0AD9B);
  stop-opacity: 0;
}

.xv5cmou-l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.861 10.177c.416-.367 1.324-.754 2.449-.574");
}

.y57vb-6vx {
  stop-color: var(--svg-color--1a74ad, #1A74AD);
}

.y7cm8rbzs {
  stop-color: var(--svg-color--ffd2b6, #FFD2B6);
}

.ydq0kpc8x {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
}

.yev9el_pf {
  d: path("M9.605 11.685a1.134 1.134 0 0 0-1.092 1.433h2.19a1.2 1.2 0 0 0 .04-.299a1.14 1.14 0 0 0-1.138-1.134");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yojcmql5k {
  cx: 18.436px;
  cy: 13.158px;
  r: 1.264px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.ys9d3layu {
  fill: var(--svg-color--eaaf9f, #EAAF9F);
  d: path("M21.258 16.052h4.015v2.016h-4.015z");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zhvue1b_t {
  stop-color: var(--svg-color--d39f86, #D39F86);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
