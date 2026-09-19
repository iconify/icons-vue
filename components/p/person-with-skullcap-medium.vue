<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ia9Webe)" class="p_724ab8t"/><path fill="url(#irCi4WB)" class="p_724ab8t"/><path fill="url(#ijvYU6B)" class="p_724ab8t"/><path fill="url(#iCeSz8c)" class="p_724ab8t"/><path fill="url(#i1NFRqc)" class="p_724ab8t"/><g filter="url(#iEYdpxc)"><path clip-rule="evenodd" class="v5btvcb0v"/></g><g filter="url(#ic3lttc)"><path fill="url(#indAmXc)" clip-rule="evenodd" class="bawi2s24b"/></g><path fill="url(#ijXp7eb)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#i0IeUxe)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#ilWvGXi)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#ilJCyKe)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#iOjxwGc)" class="fkmdvohxo"/><g filter="url(#ilCkwmd)"><path fill="url(#iaGUASb)" class="ueof-5erp"/><path fill="url(#ivmCv7k)" class="ueof-5erp"/></g><g filter="url(#i9RFRic)"><path fill="url(#iRLbapc)" class="w6cz6mbua"/><path fill="url(#ihU2gsd)" class="w6cz6mbua"/></g><g filter="url(#iLxxBeb)"><path fill="url(#iRsBRvd)" class="r9mk9fsgi"/><path fill="url(#iSmDDWb)" class="r9mk9fsgi"/></g><g filter="url(#iC9Xqnc)"><circle fill="url(#i5C1sUb)" class="ik_eribja"/></g><circle fill="url(#iZ6advd)" class="ik_eribja"/><g filter="url(#iS5XZ2c)"><circle fill="url(#ibalpqc)" class="cg29a6xaw"/></g><g filter="url(#iFPGdtc)"><circle fill="url(#iz6Cdld)" class="g93nmoo9i"/><circle fill="url(#igtTgZc)" class="g93nmoo9i"/></g><g filter="url(#iDtcifd)"><circle class="g2wrjrr1o"/><circle fill="url(#i8QJYCb)" class="n4wrjwb8k"/><circle fill="url(#id0WU0c)" class="n4wrjwb8k"/></g><g filter="url(#ijOSjce)"><path fill="url(#iQrOr2n)" class="ensiw1ixy"/><path fill="url(#iaZwwkR)" class="ensiw1ixy"/><path fill="url(#izv31gR)" class="ensiw1ixy"/></g><path fill="url(#iM0nOvE)" class="ensiw1ixy"/><path fill="url(#imXmcsb)" class="ensiw1ixy"/><path fill="url(#idirvfc)" class="ensiw1ixy"/><path fill="url(#i2TrADk)" class="ensiw1ixy"/><g filter="url(#iBVNi7d)"><path class="dhcni3rkj"/></g><g filter="url(#iMMal2c)"><path class="x2l_wpj7x"/><path fill="url(#iU9W63W)" class="x1dqzuy2a"/><path fill="url(#iuvVOed)" class="x1dqzuy2a"/><path fill="url(#ivyoGmd)" class="x1dqzuy2a"/><path fill="url(#i3QMjZd)" class="x1dqzuy2a"/></g><g filter="url(#iqq0awi)"><path fill="url(#ign2yJr)" class="t84zge7ff"/></g><g filter="url(#ifLxWXC)"><path stroke="url(#i9pKZqc)" class="egaq5nsrr"/></g><path class="ii6hwcc3q"/><g filter="url(#i7oMv9i)"><path class="n_tl7ctma"/><path fill="url(#iCPiBJc)" class="wd0xv8hpc"/></g><g filter="url(#iY9P4tb)"><path class="vuqnyfb3e"/><path fill="url(#igWhZjb)" class="yht0l9bsd"/></g><path class="nbts9pbct"/><path fill="url(#iQmqWIe)" class="ncde33bjl"/><path class="q65jk5bvz"/><g filter="url(#iuWEe7c)"><path class="h37b7dbug"/><path fill="url(#iqW2kpc)" class="tthz2gk0i"/></g><g filter="url(#iTLhRce)"><path fill="url(#i7R2hfd)" class="hri3i4j0q"/></g><path class="vumiwwb6n"/><path fill="url(#ia8CJkq)" class="ea-2kmr9x"/><path class="l4ywfrb3v"/><g filter="url(#iaZGj2K)"><path fill="url(#iuwiX9b)" class="ppjuqodvu"/></g><g filter="url(#iNbnXYc)"><ellipse transform="rotate(-27.914 13.251 10.907)" class="bubh-iaub"/><ellipse fill="url(#ie7l7Po)" transform="rotate(-27.914 13.251 10.907)" class="pntb3v1uv"/></g><g filter="url(#iqrdQmc)"><path stroke="url(#iUuogFc)" class="ipkuzubaq"/></g><g filter="url(#iVtWmRm)"><path stroke="url(#irdRwAc)" class="uwvxxacpc"/></g><g filter="url(#idUbTDb)"><path class="k9pijk0ah"/></g><g filter="url(#ilQ5Ked)"><path class="bxspdccut"/></g><path fill="url(#ihDTzUw)" class="iyuzhi6lo"/><path fill="url(#ioUfsNe)" class="iyuzhi6lo"/><path fill="url(#iFtRiue)" class="i3bomv7id"/><path fill="url(#i6LDHme)" class="i3bomv7id"/><path fill="url(#igHcgRd)" class="i3bomv7id"/><path fill="url(#iMJenyb)" class="y84c-zb8a"/><path fill="url(#i3NGTdb)" class="y84c-zb8a"/><g filter="url(#iStxq0b)"><path fill="url(#imAdgbc)" class="le-n4cbjm"/></g><path fill="url(#iijJyAe)" class="ghjm-f--q"/><path fill="url(#i0DcXHb)" class="l1dhji-tq"/><path fill="url(#iiHAMcc)" class="l1dhji-tq"/><path fill="url(#igCsxuc)" class="l1dhji-tq"/><path fill="url(#i3CFgGb)" class="l1dhji-tq"/><g filter="url(#iXGxkEe)"><path class="jo3_jzbbd"/></g><g filter="url(#iBO8dcb)"><path fill="url(#id3X3Oc)" class="f732de1pg"/><path fill="url(#iL4UwDe)" class="f732de1pg"/></g><defs><radialGradient id="irCi4WB" cx="0" cy="0" r="1" gradientTransform="matrix(-3.9375 0 0 -14.75 24.04 28.388)" gradientUnits="userSpaceOnUse"><stop class="nc2yi90jd"/><stop offset="1" class="x0qyerbek"/></radialGradient><radialGradient id="ijvYU6B" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.53125 -15.795 0 13.603 15.45)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="vsn-65dkv"/><stop offset="1" class="dr4byj-pv"/></radialGradient><radialGradient id="ijXp7eb" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 2.79687 -2.17043 1.06703 13.26 18.888)" gradientUnits="userSpaceOnUse"><stop class="pbwfqxbhw"/><stop offset=".726" class="su33dtg0a"/></radialGradient><radialGradient id="ilWvGXi" cx="0" cy="0" r="1" gradientTransform="matrix(2.30035 0 0 .39063 15.99 24.013)" gradientUnits="userSpaceOnUse"><stop class="wzjvs5_gw"/><stop offset="1" class="k06it9j6t"/></radialGradient><radialGradient id="ilJCyKe" cx="0" cy="0" r="1" gradientTransform="matrix(2.34723 0 0 .39859 15.99 26.982)" gradientUnits="userSpaceOnUse"><stop class="wzjvs5_gw"/><stop offset="1" class="k06it9j6t"/></radialGradient><radialGradient id="iOjxwGc" cx="0" cy="0" r="1" gradientTransform="rotate(-137.428 13.033 6.878)scale(4.7527 9.93354)" gradientUnits="userSpaceOnUse"><stop class="nnakm0bzg"/><stop offset="1" class="i0cjp-bjb"/></radialGradient><radialGradient id="ivmCv7k" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08728 0 0 -.59375 17.087 23.394)" gradientUnits="userSpaceOnUse"><stop class="vzmlz-b3e"/><stop offset="1" class="pmtz18b1m"/></radialGradient><radialGradient id="ihU2gsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08728 0 0 -.59375 17.087 26.344)" gradientUnits="userSpaceOnUse"><stop class="vzmlz-b3e"/><stop offset="1" class="pmtz18b1m"/></radialGradient><radialGradient id="iSmDDWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08728 0 0 -.59375 17.087 29.294)" gradientUnits="userSpaceOnUse"><stop class="vzmlz-b3e"/><stop offset="1" class="pmtz18b1m"/></radialGradient><radialGradient id="i5C1sUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.95038 0 0 3.41319 8.848 11.77)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iZ6advd" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.9 4.026)scale(1.84133)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="igtTgZc" cx="0" cy="0" r="1" gradientTransform="matrix(.9188 -.66903 .76362 1.0487 21.69 11.476)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i8QJYCb" cx="0" cy="0" r="1" gradientTransform="matrix(.91276 -1.67883 .98263 .53425 21.23 12.683)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="id0WU0c" cx="0" cy="0" r="1" gradientTransform="matrix(.28818 .28525 -.36773 .3715 21.277 11.77)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iaZwwkR" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45271 1.78795 0 18.588 10.357)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="izv31gR" cx="0" cy="0" r="1" gradientTransform="scale(1.89922 1.52721)rotate(-90 7 -.12)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="idirvfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.02972 -11.9005 0 15.748 10.066)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="d6hcrxbnw"/><stop offset=".981" class="ipk1pybgg"/></radialGradient><radialGradient id="i3QMjZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21884 -.70307 0 16.344 13.556)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iCPiBJc" cx="0" cy="0" r="1" gradientTransform="matrix(.1158 -.67048 1.98356 .3426 18.695 9.454)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="igWhZjb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 12.1 -2.976)scale(.68041 2.01304)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iQmqWIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9015 -1.43394 0 18.402 11.013)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iqW2kpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2577 -.33208 .45719 -.35479 18.148 11.108)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ia8CJkq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90155 -1.43402 0 13.553 11.012)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ie7l7Po" cx="0" cy="0" r="1" gradientTransform="matrix(-.0086 -.549 .65993 -.01033 13.235 11.257)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihDTzUw" cx="0" cy="0" r="1" gradientTransform="rotate(-132.749 10.772 -1.558)scale(5.06414 4.42603)" gradientUnits="userSpaceOnUse"><stop class="s8zg0sozp"/><stop offset="1" class="y-b78pbjp"/></radialGradient><radialGradient id="ioUfsNe" cx="0" cy="0" r="1" gradientTransform="rotate(-105.658 10.416 -3.31)scale(4.28399 11.4844)" gradientUnits="userSpaceOnUse"><stop offset=".704" class="c0d08q5pa"/><stop offset="1" class="o653nqbma"/></radialGradient><radialGradient id="iFtRiue" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 -8.2678 2.61371 .59275 5.353 30)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="z-cidv2vh"/><stop offset="1" class="xr6flvbof"/></radialGradient><radialGradient id="igHcgRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.01779 .46875 0 7.79 30)" gradientUnits="userSpaceOnUse"><stop class="q6eft0bey"/><stop offset="1" class="pgebwjbzh"/></radialGradient><radialGradient id="iMJenyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6563 -8.51778 1.79785 -.3496 26.447 30)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="cfzz63bjc"/><stop offset="1" class="c7n196bnp"/></radialGradient><radialGradient id="i3NGTdb" cx="0" cy="0" r="1" gradientTransform="matrix(.55858 0 0 11.598 23.93 30)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x46zv8bqj"/><stop offset="1" class="h-78cmokj"/></radialGradient><radialGradient id="id3X3Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16967 .60157 -.68916 -1.33998 16.96 6.067)" gradientUnits="userSpaceOnUse"><stop class="fnqzb7fjl"/><stop offset="1" class="wh9qglb-y"/></radialGradient><radialGradient id="iL4UwDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.56716 -1.70963 0 16 5.872)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="r8lozhiei"/><stop offset="1" class="ibp4-fbiv"/></radialGradient><linearGradient id="ia9Webe" x1="16" x2="16" y1="17.759" y2="30" gradientUnits="userSpaceOnUse"><stop class="gmeez-00x"/><stop offset="1" class="jn75igb9t"/></linearGradient><linearGradient id="iCeSz8c" x1="8.072" x2="8.173" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="cdb8aqbla"/><stop offset="1" class="vl0vrwboz"/></linearGradient><linearGradient id="i1NFRqc" x1="23.97" x2="23.775" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".16" class="pr-umdqbw"/><stop offset="1" class="yvxubnx_l"/></linearGradient><linearGradient id="indAmXc" x1="15.99" x2="15.99" y1="18.919" y2="30" gradientUnits="userSpaceOnUse"><stop class="cxlbh0b3y"/><stop offset="1" class="ew4g_q7fo"/></linearGradient><linearGradient id="i0IeUxe" x1="12.08" x2="12.337" y1="19.256" y2="19.256" gradientUnits="userSpaceOnUse"><stop offset=".157" class="evin7izob"/><stop offset="1" class="pdkp-sp8r"/></linearGradient><linearGradient id="iaGUASb" x1="16" x2="16" y1="24.099" y2="23.269" gradientUnits="userSpaceOnUse"><stop class="czn49vv7g"/><stop offset="1" class="w35ommbhj"/></linearGradient><linearGradient id="iRLbapc" x1="16" x2="16" y1="27.05" y2="26.219" gradientUnits="userSpaceOnUse"><stop class="czn49vv7g"/><stop offset="1" class="w35ommbhj"/></linearGradient><linearGradient id="iRsBRvd" x1="16" x2="16" y1="30" y2="29.169" gradientUnits="userSpaceOnUse"><stop class="czn49vv7g"/><stop offset="1" class="w35ommbhj"/></linearGradient><linearGradient id="ibalpqc" x1="10.703" x2="9.991" y1="12.08" y2="12.08" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iz6Cdld" x1="22.484" x2="21.574" y1="10.557" y2="13.376" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iQrOr2n" x1="20.466" x2="11.978" y1="12.203" y2="13.468" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iM0nOvE" x1="10.568" x2="12.317" y1="15.018" y2="14.825" gradientUnits="userSpaceOnUse"><stop offset=".156" class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="imXmcsb" x1="21.608" x2="20.319" y1="14.264" y2="14.147" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="i2TrADk" x1="15.931" x2="15.931" y1="7.393" y2="8.893" gradientUnits="userSpaceOnUse"><stop offset=".125" class="kj97tfbcz"/><stop offset="1" class="pv43u6e8n"/></linearGradient><linearGradient id="iU9W63W" x1="15.02" x2="16.063" y1="12.936" y2="12.936" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iuvVOed" x1="17.023" x2="15.883" y1="13.294" y2="13.278" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="ivyoGmd" x1="16.197" x2="16.197" y1="14.119" y2="13.482" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="ign2yJr" x1="15.98" x2="15.98" y1="10.958" y2="12.448" gradientUnits="userSpaceOnUse"><stop class="z8xhvx0ce"/><stop offset="1" class="bw-9gcbey"/></linearGradient><linearGradient id="i9pKZqc" x1="14.828" x2="15.311" y1="15.915" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="i7R2hfd" x1="19.266" x2="18.918" y1="11.073" y2="11.288" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuwiX9b" x1="14.379" x2="14.031" y1="11.073" y2="11.288" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUuogFc" x1="19.284" x2="18.817" y1="8.695" y2="7.741" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="irdRwAc" x1="13.388" x2="12.066" y1="8.552" y2="7.998" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i6LDHme" x1="8.07" x2="6.009" y1="29.545" y2="29.545" gradientUnits="userSpaceOnUse"><stop class="ecvjpibkc"/><stop offset="1" class="r0c1q-bfc"/></linearGradient><linearGradient id="imAdgbc" x1="17.836" x2="14.069" y1="4.134" y2="4.134" gradientUnits="userSpaceOnUse"><stop class="bjcdqbftc"/><stop offset="1" class="v7hu212ki"/></linearGradient><linearGradient id="iijJyAe" x1="16" x2="16" y1="5.281" y2="2.419" gradientUnits="userSpaceOnUse"><stop class="r5-syo3hw"/><stop offset="1" class="ks7296big"/></linearGradient><linearGradient id="i0DcXHb" x1="21.29" x2="15.228" y1="7.169" y2="7.169" gradientUnits="userSpaceOnUse"><stop class="zveuazben"/><stop offset="1" class="pgl0cnbpu"/></linearGradient><linearGradient id="iiHAMcc" x1="8.733" x2="13.54" y1="6.669" y2="6.669" gradientUnits="userSpaceOnUse"><stop class="zchv5y5ol"/><stop offset="1" class="oe75a7bgm"/></linearGradient><linearGradient id="igCsxuc" x1="16" x2="16" y1="8" y2="7.482" gradientUnits="userSpaceOnUse"><stop class="z5x2mc9xh"/><stop offset="1" class="t_df9tb_q"/></linearGradient><linearGradient id="i3CFgGb" x1="16" x2="16" y1="4.873" y2="5.451" gradientUnits="userSpaceOnUse"><stop class="gaadbc7ca"/><stop offset="1" class="hprgdjbtv"/></linearGradient><filter id="iEYdpxc" width="8.32" height="12.289" x="11.83" y="17.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".125"/></filter><filter id="ic3lttc" width="8.12" height="13.49" x="11.93" y="16.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.533333 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3273" result="effect2_innerShadow_4002_3273"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.533333 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3273" result="effect3_innerShadow_4002_3273"/></filter><filter id="ilCkwmd" width="2.44" height="1.1" x="14.78" y="23.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="i9RFRic" width="2.44" height="1.1" x="14.78" y="26.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iLxxBeb" width="2.44" height="1.1" x="14.78" y="29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iC9Xqnc" width="3.911" height="3.711" x="8.848" y="9.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iS5XZ2c" width="3.212" height="3.212" x="9.098" y="10.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".25"/></filter><filter id="iFPGdtc" width="3.961" height="3.961" x="19.421" y="9.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iDtcifd" width="3.212" height="3.212" x="19.671" y="10.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".25"/></filter><filter id="ijOSjce" width="12.04" height="13.518" x="9.911" y="5.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iBVNi7d" width="3.456" height="4.48" x="13.987" y="10.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".375"/></filter><filter id="iMMal2c" width="2.586" height="3.48" x="14.687" y="10.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".125"/></filter><filter id="iqq0awi" width="2.586" height="3.48" x="14.687" y="10.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".125"/></filter><filter id="ifLxWXC" width="3.976" height="1.592" x="13.992" y="14.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".05"/></filter><filter id="i7oMv9i" width="3.284" height="2.037" x="17.294" y="7.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iY9P4tb" width="3.284" height="2.037" x="11.573" y="7.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iuWEe7c" width=".852" height=".752" x="17.597" y="10.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".05"/></filter><filter id="iTLhRce" width=".946" height=".971" x="18.542" y="10.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".1"/></filter><filter id="iaZGj2K" width="1.052" height="1.111" x="13.605" y="10.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".1"/></filter><filter id="iNbnXYc" width=".992" height=".761" x="12.755" y="10.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".05"/></filter><filter id="iqrdQmc" width="3.305" height="1.729" x="17.201" y="7.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".25"/></filter><filter id="iVtWmRm" width="3.392" height="1.792" x="11.4" y="7.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".25"/></filter><filter id="idUbTDb" width="2.54" height="4.59" x="8.62" y="6.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.0745098 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="ilQ5Ked" width="2.403" height="4.58" x="20.82" y="6.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.0862745 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter><filter id="iStxq0b" width="5.021" height="3.505" x="13.489" y="1.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".075"/></filter><filter id="iXGxkEe" width="2.42" height="2.42" x="14.72" y="5.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3273" stdDeviation=".125"/></filter><filter id="iBO8dcb" width="1.97" height="1.97" x="15.04" y="5.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.631373 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3273"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-skullcap-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bawi2s24b {
  fill-rule: evenodd;
  d: path("M12.08 19.42v-2.66h7.82v2.66c0 1.29-1.05 2.34-2.34 2.34h-.81c-.14 0-.25.11-.25.25V30h-1v-7.99c0-.14-.11-.25-.25-.25h-.83c-1.29 0-2.34-1.05-2.34-2.34m2.35 1.34h3.14c.74 0 1.34-.6 1.35-1.34v-1.66h-5.83v1.66c0 .74.6 1.34 1.34 1.34");
}

.bjcdqbftc {
  stop-color: var(--svg-color--d62a46, #D62A46);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bubh-iaub {
  cx: 13.251px;
  cy: 10.907px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.433px;
  ry: 0.219px;
}

.bw-9gcbey {
  stop-color: var(--svg-color--ab8071, #AB8071);
  stop-opacity: 0;
}

.bxspdccut {
  fill: var(--svg-color--463536, #463536);
  d: path("M20.82 6.48v.93c0 .38.16.74.44.99l.22.2c.24.22.37.53.35.86c-.04.63-.11 1.6-.11 1.6c.34-.02.63-.27.69-.61L22.93 7c.03-.17.05-.35.04-.52z");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c0d08q5pa {
  stop-color: var(--svg-color--d14752, #D14752);
  stop-opacity: 0;
}

.c7n196bnp {
  stop-color: var(--svg-color--e4526b, #E4526B);
}

.cdb8aqbla {
  stop-color: var(--svg-color--d5345b, #D5345B);
}

.cfzz63bjc {
  stop-color: var(--svg-color--ff5783, #FF5783);
}

.cg29a6xaw {
  cx: 10.703px;
  cy: 11.771px;
  r: 1.106px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cxlbh0b3y {
  stop-color: var(--svg-color--ffa730, #FFA730);
}

.czn49vv7g {
  stop-color: var(--svg-color--482566, #482566);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d6hcrxbnw {
  stop-color: var(--svg-color--975d6e, #975D6E);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dhcni3rkj {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.674 11.635l-.911 1.889c-.113.388.158.777.542.777h.82c.384 0 .655-.395.542-.777l-.554-1.89c-.118-.418-.314-.418-.439 0");
}

.dr4byj-pv {
  stop-color: var(--svg-color--c33d4a, #C33D4A);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.ea-2kmr9x {
  d: path("M13.55 10.482a.992.992 0 0 0-.955 1.253h1.916q.035-.127.036-.261a1 1 0 0 0-.996-.992");
}

.ecvjpibkc {
  stop-color: var(--svg-color--bc314f, #BC314F);
}

.egaq5nsrr {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.98 15.25a3.34 3.34 0 0 1-1.54-.365c-.151-.078-.315.094-.22.232c.373.564 1.022.94 1.76.94c.739 0 1.387-.376 1.76-.94c.096-.144-.068-.31-.22-.232c-.446.232-.97.365-1.54.365Z");
}

.ensiw1ixy {
  d: path("M10.083 9.268c0-.297-.323-1.176-.085-1.354l.18-.177c.297-.238.39-.38.39-.735l.633-.416a.58.58 0 0 1 .477-.593c.716-.177 2.206-.474 4.352-.474s3.637.297 4.352.474c.239.06.477.297.477.593l.174.588c0 .356.179.712.417.949c.558.39.523.606.477 1.067c-.2 1.99-.434 4.363-.568 6.36c-.179 1.967-1.725 3.337-3.568 3.337h-3.568c-1.903 0-3.39-1.37-3.568-3.337c-.156-2.028-.388-4.27-.572-6.282");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.evin7izob {
  stop-color: var(--svg-color--db9e53, #DB9E53);
}

.ew4g_q7fo {
  stop-color: var(--svg-color--ffa748, #FFA748);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f732de1pg {
  d: path("M16 7.44a.96.96 0 1 0 0-1.92a.96.96 0 0 0 0 1.92");
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fkmdvohxo {
  d: path("M17.57 20.76h-3.14c-.74 0-1.34-.6-1.34-1.34v-1.66h5.83v1.66c-.01.74-.61 1.34-1.35 1.34");
}

.fnqzb7fjl {
  stop-color: var(--svg-color--ffdb5a, #FFDB5A);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g2wrjrr1o {
  cx: 21.277px;
  cy: 11.771px;
  r: 1.106px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.g93nmoo9i {
  cx: 21.276px;
  cy: 11.77px;
  r: 1.855px;
}

.gaadbc7ca {
  stop-color: var(--svg-color--493d55, #493D55);
}

.ghjm-f--q {
  d: path("M16 2c-.699 0-1.814.851-2.254 3.281h4.508C17.814 2.851 16.698 2 16 2");
}

.gmeez-00x {
  stop-color: var(--svg-color--ea3662, #EA3662);
}

.h-78cmokj {
  stop-color: var(--svg-color--e3205c, #E3205C);
  stop-opacity: 0;
}

.h37b7dbug {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.331 10.693c.071.094-.077.21-.244.335c-.168.126-.293.214-.364.12c-.07-.095.009-.274.176-.399c.168-.126.362-.15.432-.056");
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hprgdjbtv {
  stop-color: var(--svg-color--493d55, #493D55);
  stop-opacity: 0;
}

.hri3i4j0q {
  d: path("M19.288 11.344a.93.93 0 0 0-.258-.514l-.288.317l.13.253z");
}

.i0cjp-bjb {
  stop-color: var(--svg-color--2d1728, #2D1728);
}

.i3bomv7id {
  d: path("M8.07 30v-9.392A12.44 12.44 0 0 0 3.54 30z");
}

.ibp4-fbiv {
  stop-color: var(--svg-color--e0803f, #E0803F);
}

.ii6hwcc3q {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.98 15.25a3.34 3.34 0 0 1-1.54-.365c-.151-.078-.315.094-.22.232c.373.564 1.022.94 1.76.94c.739 0 1.387-.376 1.76-.94c.096-.144-.068-.31-.22-.232c-.446.232-.97.365-1.54.365");
}

.ik_eribja {
  cx: 10.703px;
  cy: 11.77px;
  r: 1.855px;
}

.ipk1pybgg {
  stop-color: var(--svg-color--924f59, #924F59);
}

.ipkuzubaq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.826 8.587c.478-.083 1.41-.06 2.055.443");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.iyuzhi6lo {
  d: path("M22.97 7.2H9.03l.2-.52a7.238 7.238 0 0 1 13.54 0z");
}

.jn75igb9t {
  stop-color: var(--svg-color--fc3c78, #FC3C78);
}

.jo3_jzbbd {
  fill: var(--svg-color--3f2950, #3F2950);
  d: path("M15.93 7.514a.96.96 0 1 0 0-1.92a.96.96 0 0 0 0 1.92");
}

.k06it9j6t {
  stop-color: var(--svg-color--ae5a24, #AE5A24);
  stop-opacity: 0;
}

.k9pijk0ah {
  fill: var(--svg-color--4c3b39, #4C3B39);
  d: path("M9.02 6.48c0 .17.01.34.04.52l.51 3.46c.06.34.36.6.71.61c0 0-.07-.98-.11-1.61c-.02-.34.11-.66.35-.87l.2-.19c.28-.25.44-.61.44-.99v-.93z");
}

.kj97tfbcz {
  stop-color: var(--svg-color--7e4e57, #7E4E57);
}

.ks7296big {
  stop-color: var(--svg-color--499065, #499065);
}

.l1dhji-tq {
  d: path("M22.59 8H9.41c-.41 0-.73-.36-.67-.77l.24-1.69c.05-.33.33-.58.67-.58h12.7c.33 0 .62.25.67.58l.24 1.69c.06.41-.26.77-.67.77");
}

.l4ywfrb3v {
  fill: var(--svg-color--000, #000);
  d: path("M14.119 11.474a.566.566 0 0 0-.568-.568a.566.566 0 0 0-.505.83h1.005a.56.56 0 0 0 .068-.262");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.le-n4cbjm {
  d: path("M16 2.076c-.732 0-1.9.832-2.36 3.205h4.72C17.9 2.908 16.733 2.076 16 2.076");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n_tl7ctma {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m20.114 8.748l-.001-.001l-.002-.002l-.005-.004l-.014-.01a2 2 0 0 0-.172-.12a3 3 0 0 0-.466-.235a3.15 3.15 0 0 0-1.66-.175a.593.593 0 1 0 .186 1.171c.442-.07.796.012 1.038.108a1.7 1.7 0 0 1 .342.184a.593.593 0 0 0 .754-.916");
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n4wrjwb8k {
  cx: 21.277px;
  cy: 11.771px;
  r: 1.106px;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nbts9pbct {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.634 10.18c.726 0 1.339.5 1.506 1.177c.05.194-.1.379-.298.379h-2.479a.256.256 0 0 1-.252-.303a1.55 1.55 0 0 1 1.523-1.253");
}

.nc2yi90jd {
  stop-color: var(--svg-color--ff5e85, #FF5E85);
}

.ncde33bjl {
  d: path("M18.404 10.483a.992.992 0 0 1 .956 1.253h-1.916a.996.996 0 0 1 .96-1.253");
}

.nnakm0bzg {
  stop-color: var(--svg-color--4e3b4e, #4E3B4E);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o653nqbma {
  stop-color: var(--svg-color--d14752, #D14752);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe75a7bgm {
  stop-color: var(--svg-color--493f55, #493F55);
  stop-opacity: 0;
}

.p_724ab8t {
  d: path("M28.46 30c-.12-6.78-5.65-12.24-12.46-12.24S3.66 23.22 3.54 30z");
}

.pbwfqxbhw {
  stop-color: var(--svg-color--b66913, #B66913);
}

.pdkp-sp8r {
  stop-color: var(--svg-color--db9e53, #DB9E53);
  stop-opacity: 0;
}

.pgebwjbzh {
  stop-color: var(--svg-color--c03c64, #C03C64);
  stop-opacity: 0;
}

.pgl0cnbpu {
  stop-color: var(--svg-color--4b3a5d, #4B3A5D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmtz18b1m {
  stop-color: var(--svg-color--5e5065, #5E5065);
  stop-opacity: 0;
}

.pntb3v1uv {
  cx: 13.251px;
  cy: 10.907px;
  rx: 0.433px;
  ry: 0.219px;
}

.ppjuqodvu {
  d: path("M14.457 11.358c0-.32-.261-.534-.331-.599l-.32.31l.196.402z");
}

.pr-umdqbw {
  stop-color: var(--svg-color--fd3b6f, #FD3B6F);
}

.pv43u6e8n {
  stop-color: var(--svg-color--7e4e57, #7E4E57);
  stop-opacity: 0;
}

.q65jk5bvz {
  fill: var(--svg-color--000, #000);
  d: path("M17.836 11.474c0-.316.253-.568.568-.568a.566.566 0 0 1 .505.83h-1.005a.5.5 0 0 1-.068-.262");
}

.q6eft0bey {
  stop-color: var(--svg-color--c03c64, #C03C64);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r0c1q-bfc {
  stop-color: var(--svg-color--bc314f, #BC314F);
  stop-opacity: 0;
}

.r5-syo3hw {
  stop-color: var(--svg-color--3b9c62, #3B9C62);
}

.r8lozhiei {
  stop-color: var(--svg-color--fab13f, #FAB13F);
  stop-opacity: 0;
}

.r9mk9fsgi {
  d: path("M14.78 29.5c0-.28.22-.5.5-.5h1.44c.28 0 .5.22.5.5s-.22.5-.5.5h-1.44c-.28 0-.5-.22-.5-.5");
}

.s8zg0sozp {
  stop-color: var(--svg-color--ff4c7c, #FF4C7C);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.su33dtg0a {
  stop-color: var(--svg-color--b66913, #B66913);
  stop-opacity: 0;
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t_df9tb_q {
  stop-color: var(--svg-color--512f64, #512F64);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t84zge7ff {
  d: path("m15.556 11.272l-.591 1.889a.6.6 0 0 0 .579.777h.873c.41 0 .7-.395.579-.777l-.59-1.89c-.127-.418-.718-.418-.85 0");
}

.tthz2gk0i {
  d: path("M18.331 10.693c.071.094-.077.21-.244.335c-.168.126-.293.214-.364.12c-.07-.095.009-.274.176-.399c.168-.126.362-.15.432-.056");
}

.ueof-5erp {
  d: path("M14.78 23.6c0-.28.22-.5.5-.5h1.44c.28 0 .5.22.5.5s-.22.5-.5.5h-1.44c-.28 0-.5-.22-.5-.5");
}

.uwvxxacpc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.025 9.163c.364-.322 1.157-.66 2.142-.503");
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v5btvcb0v {
  fill: var(--svg-color--e0244f, #E0244F);
  fill-rule: evenodd;
  d: path("m12.08 19.565l1.01-.799l4.732.185l2.078.614c0 1.243-1.05 2.254-2.34 2.254h-.81c-.14 0-.25.106-.25.241v7.696h-1V22.06c0-.135-.11-.24-.25-.24h-.83c-1.29 0-2.34-1.012-2.34-2.255m2.35 1.291h3.14c.74 0 1.34-.578 1.35-1.29v-1.6h-5.83v1.6c0 .712.6 1.29 1.34 1.29");
}

.v7hu212ki {
  stop-color: var(--svg-color--e2526d, #E2526D);
}

.vl0vrwboz {
  stop-color: var(--svg-color--d5345b, #D5345B);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vsn-65dkv {
  stop-color: var(--svg-color--c33d4a, #C33D4A);
}

.vumiwwb6n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.32 10.18c-.725 0-1.338.5-1.505 1.177c-.05.194.1.379.298.379h2.479a.256.256 0 0 0 .252-.302a1.56 1.56 0 0 0-1.523-1.254");
}

.vuqnyfb3e {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m11.786 8.748l.002-.002l.005-.004l.013-.01a2 2 0 0 1 .173-.12a3 3 0 0 1 .466-.235a3.15 3.15 0 0 1 1.659-.175a.593.593 0 1 1-.185 1.171a1.96 1.96 0 0 0-1.038.108a1.7 1.7 0 0 0-.342.184a.593.593 0 0 1-.755-.916");
}

.vzmlz-b3e {
  stop-color: var(--svg-color--5e5065, #5E5065);
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w35ommbhj {
  stop-color: var(--svg-color--46384c, #46384C);
}

.w6cz6mbua {
  d: path("M14.78 26.55c0-.28.22-.5.5-.5h1.44c.28 0 .5.22.5.5s-.22.5-.5.5h-1.44c-.28 0-.5-.22-.5-.5");
}

.wd0xv8hpc {
  d: path("m20.114 8.748l-.001-.001l-.002-.002l-.005-.004l-.014-.01a2 2 0 0 0-.172-.12a3 3 0 0 0-.466-.235a3.15 3.15 0 0 0-1.66-.175a.593.593 0 1 0 .186 1.171c.442-.07.796.012 1.038.108a1.7 1.7 0 0 1 .342.184a.593.593 0 0 0 .754-.916");
}

.wh9qglb-y {
  stop-color: var(--svg-color--f6ac3f, #F6AC3F);
}

.wzjvs5_gw {
  stop-color: var(--svg-color--ae5a24, #AE5A24);
}

.x0qyerbek {
  stop-color: var(--svg-color--ff5e85, #FF5E85);
  stop-opacity: 0;
}

.x1dqzuy2a {
  d: path("m15.556 11.453l-.591 1.89a.6.6 0 0 0 .579.776h.873a.6.6 0 0 0 .579-.777l-.59-1.889c-.127-.418-.718-.418-.85 0");
}

.x2l_wpj7x {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.556 11.453l-.591 1.89a.6.6 0 0 0 .579.776h.873a.6.6 0 0 0 .579-.777l-.59-1.889c-.127-.418-.718-.418-.85 0");
}

.x46zv8bqj {
  stop-color: var(--svg-color--e3205c, #E3205C);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xr6flvbof {
  stop-color: var(--svg-color--cd4d63, #CD4D63);
}

.y-b78pbjp {
  stop-color: var(--svg-color--d6384d, #D6384D);
}

.y84c-zb8a {
  d: path("M23.93 30v-9.392A12.44 12.44 0 0 1 28.46 30z");
}

.yht0l9bsd {
  d: path("m11.786 8.748l.002-.002l.005-.004l.013-.01a2 2 0 0 1 .173-.12a3 3 0 0 1 .466-.235a3.15 3.15 0 0 1 1.659-.175a.593.593 0 1 1-.185 1.171a1.96 1.96 0 0 0-1.038.108a1.7 1.7 0 0 0-.342.184a.593.593 0 0 1-.755-.916");
}

.yvxubnx_l {
  stop-color: var(--svg-color--fd3b6f, #FD3B6F);
  stop-opacity: 0;
}

.z-cidv2vh {
  stop-color: var(--svg-color--ed396d, #ED396D);
}

.z5x2mc9xh {
  stop-color: var(--svg-color--512f64, #512F64);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.z8xhvx0ce {
  stop-color: var(--svg-color--ab8071, #AB8071);
}

.zchv5y5ol {
  stop-color: var(--svg-color--615f64, #615F64);
}

.zveuazben {
  stop-color: var(--svg-color--69597a, #69597A);
}

</style>
