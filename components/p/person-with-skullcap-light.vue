<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivBgdMd)" class="p_724ab8t"/><path fill="url(#irCi4WB)" class="p_724ab8t"/><path fill="url(#ijvYU6B)" class="p_724ab8t"/><path fill="url(#iCeSz8c)" class="p_724ab8t"/><path fill="url(#i1NFRqc)" class="p_724ab8t"/><g filter="url(#ioR3Lhb)"><path clip-rule="evenodd" class="td4-ylb3b"/></g><g filter="url(#iSl0zfd)"><path fill="url(#indAmXc)" clip-rule="evenodd" class="bawi2s24b"/></g><path fill="url(#ijXp7eb)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#i0IeUxe)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#ilWvGXi)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#ilJCyKe)" clip-rule="evenodd" class="bawi2s24b"/><path fill="url(#iOjxwGc)" class="fkmdvohxo"/><g filter="url(#i0H9VGe)"><path fill="url(#iIGXkib)" class="ueof-5erp"/><path fill="url(#iP4ePHb)" class="ueof-5erp"/></g><g filter="url(#iRqNUkb)"><path fill="url(#in1ksKu)" class="w6cz6mbua"/><path fill="url(#iS4GdZb)" class="w6cz6mbua"/></g><g filter="url(#ieKh0mb)"><path fill="url(#i7fP0wb)" class="r9mk9fsgi"/><path fill="url(#iHuHSNt)" class="r9mk9fsgi"/></g><path fill="url(#iFtRiue)" class="i3bomv7id"/><path fill="url(#i8I9Kqb)" class="i3bomv7id"/><path fill="url(#igHcgRd)" class="i3bomv7id"/><path fill="url(#iMJenyb)" class="y84c-zb8a"/><path fill="url(#i3NGTdb)" class="y84c-zb8a"/><g filter="url(#isIMzob)"><circle fill="url(#iFqnnNe)" class="rpm92ubuz"/></g><g filter="url(#iVfKbme)"><circle fill="url(#iGIoTud)" class="cg29a6xaw"/></g><g filter="url(#i0HK6je)"><circle fill="url(#iFOn5Ne)" class="ef6ccrb4s"/><circle fill="url(#itemKje)" class="ef6ccrb4s"/></g><g filter="url(#itOHNec)"><circle class="iyrvmvbea"/><circle fill="url(#iElDQ3b)" class="eme14ebhs"/><circle fill="url(#iZIXLZb)" class="eme14ebhs"/></g><g filter="url(#i9prkze)"><path fill="url(#i4ocSbb)" class="lgl8s0brp"/><path fill="url(#iwLdXle)" class="lgl8s0brp"/><path fill="url(#ihYNk8b)" class="lgl8s0brp"/><path fill="url(#itxmnJb)" class="lgl8s0brp"/><path fill="url(#i9IHQad)" class="lgl8s0brp"/></g><path fill="url(#ipdUx3c)" class="lgl8s0brp"/><path fill="url(#iKEupgb)" class="lgl8s0brp"/><g filter="url(#iiNIgfc)"><path class="yt856tfpq"/></g><g filter="url(#i0szLlm)"><path class="r9p5f7xkf"/><path fill="url(#iFOfkxc)" class="ahciifbjx"/><path fill="url(#ile39ne)" class="ahciifbjx"/><path fill="url(#i020MMc)" class="ahciifbjx"/><path fill="url(#i23SKdd)" class="ahciifbjx"/></g><g filter="url(#iVNw2ec)"><path stroke="url(#iEp1dGd)" class="vfpv2h20z"/></g><path class="n4b_67bko"/><g filter="url(#ihzqURd)"><path class="m26px3bad"/></g><g filter="url(#id9oXNG)"><path class="vf8snhbcg"/></g><path class="lzwd5_bie"/><path fill="url(#iQyrdUd)" class="v3k97obpg"/><path class="ydbzq4btt"/><g filter="url(#ivaOdKb)"><path class="c9pwu7abn"/><path fill="url(#ifLcYGc)" class="bzc4wfqar"/></g><g filter="url(#iSblYod)"><path fill="url(#i7R2hfd)" class="jwz4w_b7k"/></g><path class="tub-h5-kh"/><path fill="url(#icwJaXd)" class="ghlk_kb0r"/><path class="nxu86dbfw"/><g filter="url(#iqThNmc)"><path fill="url(#iuwiX9b)" class="o55h-3blp"/></g><g filter="url(#iED470c)"><ellipse transform="rotate(-27.914 13.251 10.907)" class="bubh-iaub"/><ellipse fill="url(#iiqt7ne)" transform="rotate(-27.914 13.251 10.907)" class="pntb3v1uv"/></g><g filter="url(#izsQ12c)"><path stroke="url(#ib0bUQb)" class="nyf3aqbrp"/></g><g filter="url(#iGOcsOc)"><path stroke="url(#iM8WPve)" class="ghzdp7n3n"/></g><g filter="url(#iBvdJwb)"><path class="liw9t7rjp"/></g><g filter="url(#ik7rDxe)"><path class="g8m56cc6j"/></g><path fill="url(#ihDTzUw)" class="iyuzhi6lo"/><path fill="url(#ioUfsNe)" class="iyuzhi6lo"/><g filter="url(#iubixlb)"><path fill="url(#icbj1Ed)" class="le-n4cbjm"/></g><path fill="url(#ipYpQbc)" class="uc-aspg5k"/><path fill="url(#iMyXnTb)" class="l1dhji-tq"/><path fill="url(#i80uA2c)" class="l1dhji-tq"/><path fill="url(#igCsxuc)" class="l1dhji-tq"/><path fill="url(#i3CFgGb)" class="l1dhji-tq"/><g filter="url(#iKQdnTb)"><path class="jo3_jzbbd"/></g><g filter="url(#ij1x8cb)"><path fill="url(#i07EAmb)" class="f732de1pg"/><path fill="url(#iFiRImp)" class="f732de1pg"/></g><defs><radialGradient id="irCi4WB" cx="0" cy="0" r="1" gradientTransform="matrix(-3.9375 0 0 -14.75 24.04 28.388)" gradientUnits="userSpaceOnUse"><stop class="nc2yi90jd"/><stop offset="1" class="x0qyerbek"/></radialGradient><radialGradient id="ijvYU6B" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.53125 -15.795 0 13.603 15.45)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="vsn-65dkv"/><stop offset="1" class="dr4byj-pv"/></radialGradient><radialGradient id="ijXp7eb" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 2.79687 -2.17043 1.06703 13.26 18.888)" gradientUnits="userSpaceOnUse"><stop class="pbwfqxbhw"/><stop offset=".726" class="su33dtg0a"/></radialGradient><radialGradient id="ilWvGXi" cx="0" cy="0" r="1" gradientTransform="matrix(2.30035 0 0 .39063 15.99 24.013)" gradientUnits="userSpaceOnUse"><stop class="wzjvs5_gw"/><stop offset="1" class="k06it9j6t"/></radialGradient><radialGradient id="ilJCyKe" cx="0" cy="0" r="1" gradientTransform="matrix(2.34723 0 0 .39859 15.99 26.982)" gradientUnits="userSpaceOnUse"><stop class="wzjvs5_gw"/><stop offset="1" class="k06it9j6t"/></radialGradient><radialGradient id="iOjxwGc" cx="0" cy="0" r="1" gradientTransform="rotate(-137.428 13.033 6.878)scale(4.7527 9.93354)" gradientUnits="userSpaceOnUse"><stop class="nnakm0bzg"/><stop offset="1" class="i0cjp-bjb"/></radialGradient><radialGradient id="iP4ePHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08728 0 0 -.59375 17.087 23.395)" gradientUnits="userSpaceOnUse"><stop class="vzmlz-b3e"/><stop offset="1" class="pmtz18b1m"/></radialGradient><radialGradient id="iS4GdZb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08728 0 0 -.59375 17.087 26.345)" gradientUnits="userSpaceOnUse"><stop class="vzmlz-b3e"/><stop offset="1" class="pmtz18b1m"/></radialGradient><radialGradient id="iHuHSNt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08728 0 0 -.59375 17.087 29.295)" gradientUnits="userSpaceOnUse"><stop class="vzmlz-b3e"/><stop offset="1" class="pmtz18b1m"/></radialGradient><radialGradient id="iFtRiue" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 -8.2678 2.61371 .59275 5.353 30)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="z-cidv2vh"/><stop offset="1" class="xr6flvbof"/></radialGradient><radialGradient id="igHcgRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.01779 .46875 0 7.79 30)" gradientUnits="userSpaceOnUse"><stop class="q6eft0bey"/><stop offset="1" class="pgebwjbzh"/></radialGradient><radialGradient id="iMJenyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6563 -8.51778 1.79785 -.3496 26.447 30)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="cfzz63bjc"/><stop offset="1" class="c7n196bnp"/></radialGradient><radialGradient id="i3NGTdb" cx="0" cy="0" r="1" gradientTransform="matrix(.55858 0 0 11.598 23.93 30)" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x46zv8bqj"/><stop offset="1" class="h-78cmokj"/></radialGradient><radialGradient id="iFqnnNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.95036 0 0 3.41315 8.848 11.771)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="itemKje" cx="0" cy="0" r="1" gradientTransform="matrix(.9188 -.66903 .76361 1.0487 21.69 11.477)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iElDQ3b" cx="0" cy="0" r="1" gradientTransform="matrix(.91276 -1.67881 .98261 .53424 21.23 12.684)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iZIXLZb" cx="0" cy="0" r="1" gradientTransform="matrix(.28818 .28525 -.36772 .3715 21.277 11.771)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="itxmnJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45269 1.78793 0 18.588 10.358)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="i9IHQad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.54581 1.92236 0 13.522 10.32)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="ipdUx3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.27764 -15.7522 0 16.039 9.61)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="wk0oy9-zi"/><stop offset="1" class="dwbk77sau"/></radialGradient><radialGradient id="i23SKdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .21884 -.70307 0 16.344 13.557)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="iQyrdUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9015 -1.43393 0 18.402 11.013)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ifLcYGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2577 -.33207 .45719 -.35478 18.148 11.107)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icwJaXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90154 -1.434 0 13.553 11.013)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iiqt7ne" cx="0" cy="0" r="1" gradientTransform="matrix(-.0086 -.549 .65992 -.01033 13.235 11.257)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihDTzUw" cx="0" cy="0" r="1" gradientTransform="rotate(-132.749 10.772 -1.558)scale(5.06414 4.42603)" gradientUnits="userSpaceOnUse"><stop class="s8zg0sozp"/><stop offset="1" class="y-b78pbjp"/></radialGradient><radialGradient id="ioUfsNe" cx="0" cy="0" r="1" gradientTransform="rotate(-105.658 10.416 -3.31)scale(4.28399 11.4844)" gradientUnits="userSpaceOnUse"><stop offset=".704" class="c0d08q5pa"/><stop offset="1" class="o653nqbma"/></radialGradient><radialGradient id="i07EAmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16967 .60157 -.68916 -1.33998 16.96 6.068)" gradientUnits="userSpaceOnUse"><stop class="fnqzb7fjl"/><stop offset="1" class="wh9qglb-y"/></radialGradient><radialGradient id="iFiRImp" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.56716 -1.70963 0 16 5.873)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="r8lozhiei"/><stop offset="1" class="ibp4-fbiv"/></radialGradient><linearGradient id="ivBgdMd" x1="16" x2="16" y1="17.76" y2="30" gradientUnits="userSpaceOnUse"><stop class="gmeez-00x"/><stop offset="1" class="jn75igb9t"/></linearGradient><linearGradient id="iCeSz8c" x1="8.072" x2="8.173" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="cdb8aqbla"/><stop offset="1" class="vl0vrwboz"/></linearGradient><linearGradient id="i1NFRqc" x1="23.97" x2="23.775" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".16" class="pr-umdqbw"/><stop offset="1" class="yvxubnx_l"/></linearGradient><linearGradient id="indAmXc" x1="15.99" x2="15.99" y1="18.919" y2="30" gradientUnits="userSpaceOnUse"><stop class="cxlbh0b3y"/><stop offset="1" class="ew4g_q7fo"/></linearGradient><linearGradient id="i0IeUxe" x1="12.08" x2="12.337" y1="19.256" y2="19.256" gradientUnits="userSpaceOnUse"><stop offset=".157" class="evin7izob"/><stop offset="1" class="pdkp-sp8r"/></linearGradient><linearGradient id="iIGXkib" x1="16" x2="16" y1="24.1" y2="23.27" gradientUnits="userSpaceOnUse"><stop class="czn49vv7g"/><stop offset="1" class="w35ommbhj"/></linearGradient><linearGradient id="in1ksKu" x1="16" x2="16" y1="27.05" y2="26.22" gradientUnits="userSpaceOnUse"><stop class="czn49vv7g"/><stop offset="1" class="w35ommbhj"/></linearGradient><linearGradient id="i7fP0wb" x1="16" x2="16" y1="30" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="czn49vv7g"/><stop offset="1" class="w35ommbhj"/></linearGradient><linearGradient id="i8I9Kqb" x1="8.07" x2="6.009" y1="29.544" y2="29.544" gradientUnits="userSpaceOnUse"><stop class="ecvjpibkc"/><stop offset="1" class="r0c1q-bfc"/></linearGradient><linearGradient id="iGIoTud" x1="10.703" x2="9.991" y1="12.081" y2="12.081" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iFOn5Ne" x1="22.484" x2="21.574" y1="10.558" y2="13.377" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="i4ocSbb" x1="20.466" x2="11.978" y1="12.204" y2="13.469" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="iwLdXle" x1="9.709" x2="13.441" y1="13.902" y2="14.028" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="ihYNk8b" x1="9.983" x2="12.074" y1="15.2" y2="15.126" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iKEupgb" x1="16.039" x2="16.039" y1="7.735" y2="9.391" gradientUnits="userSpaceOnUse"><stop class="sspkqpghz"/><stop offset="1" class="flf9rbc7z"/></linearGradient><linearGradient id="iFOfkxc" x1="15.02" x2="16.063" y1="12.937" y2="12.937" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="ile39ne" x1="17.023" x2="15.883" y1="13.295" y2="13.279" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="i020MMc" x1="16.197" x2="16.197" y1="14.12" y2="13.483" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iEp1dGd" x1="14.828" x2="15.311" y1="15.915" y2="15.151" gradientUnits="userSpaceOnUse"><stop class="yz-njx9ds"/><stop offset=".663" class="dl4slsgrs"/></linearGradient><linearGradient id="i7R2hfd" x1="19.266" x2="18.918" y1="11.073" y2="11.288" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuwiX9b" x1="14.379" x2="14.031" y1="11.073" y2="11.288" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ib0bUQb" x1="19.284" x2="18.817" y1="8.695" y2="7.741" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iM8WPve" x1="13.388" x2="12.066" y1="8.553" y2="7.999" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="icbj1Ed" x1="17.836" x2="14.069" y1="4.135" y2="4.135" gradientUnits="userSpaceOnUse"><stop class="bjcdqbftc"/><stop offset="1" class="v7hu212ki"/></linearGradient><linearGradient id="ipYpQbc" x1="16" x2="16" y1="5.281" y2="2.42" gradientUnits="userSpaceOnUse"><stop class="r5-syo3hw"/><stop offset="1" class="ks7296big"/></linearGradient><linearGradient id="iMyXnTb" x1="21.29" x2="15.228" y1="7.17" y2="7.17" gradientUnits="userSpaceOnUse"><stop class="zveuazben"/><stop offset="1" class="pgl0cnbpu"/></linearGradient><linearGradient id="i80uA2c" x1="8.733" x2="13.54" y1="6.67" y2="6.67" gradientUnits="userSpaceOnUse"><stop class="zchv5y5ol"/><stop offset="1" class="oe75a7bgm"/></linearGradient><linearGradient id="igCsxuc" x1="16" x2="16" y1="8" y2="7.482" gradientUnits="userSpaceOnUse"><stop class="z5x2mc9xh"/><stop offset="1" class="t_df9tb_q"/></linearGradient><linearGradient id="i3CFgGb" x1="16" x2="16" y1="4.873" y2="5.451" gradientUnits="userSpaceOnUse"><stop class="gaadbc7ca"/><stop offset="1" class="hprgdjbtv"/></linearGradient><filter id="ioR3Lhb" width="8.32" height="12.289" x="11.83" y="17.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".125"/></filter><filter id="iSl0zfd" width="8.12" height="13.49" x="11.93" y="16.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.533333 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3275" result="effect2_innerShadow_4002_3275"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.533333 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_3275" result="effect3_innerShadow_4002_3275"/></filter><filter id="i0H9VGe" width="2.44" height="1.1" x="14.78" y="23.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="iRqNUkb" width="2.44" height="1.1" x="14.78" y="26.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="ieKh0mb" width="2.44" height="1.1" x="14.78" y="29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="isIMzob" width="3.911" height="3.711" x="8.848" y="9.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="iVfKbme" width="3.212" height="3.212" x="9.097" y="10.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".25"/></filter><filter id="i0HK6je" width="3.961" height="3.961" x="19.421" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="itOHNec" width="3.212" height="3.212" x="19.671" y="10.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".25"/></filter><filter id="i9prkze" width="11.855" height="13.618" x="10.111" y="5.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="iiNIgfc" width="3.456" height="4.48" x="13.987" y="10.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".375"/></filter><filter id="i0szLlm" width="2.586" height="3.48" x="14.687" y="10.89" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".125"/></filter><filter id="iVNw2ec" width="3.976" height="1.592" x="13.992" y="14.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".05"/></filter><filter id="ihzqURd" width="3.284" height="2.037" x="17.294" y="7.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="id9oXNG" width="3.284" height="2.037" x="11.573" y="7.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="ivaOdKb" width=".852" height=".752" x="17.597" y="10.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".05"/></filter><filter id="iSblYod" width=".946" height=".971" x="18.541" y="10.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".1"/></filter><filter id="iqThNmc" width="1.052" height="1.111" x="13.605" y="10.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".1"/></filter><filter id="iED470c" width=".992" height=".761" x="12.755" y="10.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".05"/></filter><filter id="izsQ12c" width="2.805" height="1.229" x="17.451" y="8.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".125"/></filter><filter id="iGOcsOc" width="2.892" height="1.292" x="11.65" y="8.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".125"/></filter><filter id="iBvdJwb" width="2.54" height="4.59" x="8.62" y="6.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.129412 0 0 0 0 0.0431373 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="ik7rDxe" width="2.403" height="4.58" x="20.82" y="6.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.027451 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter><filter id="iubixlb" width="5.021" height="3.505" x="13.489" y="1.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".075"/></filter><filter id="iKQdnTb" width="2.42" height="2.42" x="14.72" y="5.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3275" stdDeviation=".125"/></filter><filter id="ij1x8cb" width="1.97" height="1.97" x="15.04" y="5.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.631373 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3275"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-skullcap-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.ahciifbjx {
  d: path("m15.555 11.454l-.59 1.889a.6.6 0 0 0 .578.777h.874a.6.6 0 0 0 .579-.777l-.59-1.889c-.127-.418-.718-.418-.85 0");
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.bawi2s24b {
  fill-rule: evenodd;
  d: path("M12.08 19.42v-2.66h7.82v2.66c0 1.29-1.05 2.34-2.34 2.34h-.81c-.14 0-.25.11-.25.25V30h-1v-7.99c0-.14-.11-.25-.25-.25h-.83c-1.29 0-2.34-1.05-2.34-2.34m2.35 1.34h3.14c.74 0 1.34-.6 1.35-1.34v-1.66h-5.83v1.66c0 .74.6 1.34 1.34 1.34");
}

.bjcdqbftc {
  stop-color: var(--svg-color--d62a46, #D62A46);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bubh-iaub {
  cx: 13.251px;
  cy: 10.907px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.433px;
  ry: 0.219px;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bzc4wfqar {
  d: path("M18.331 10.693c.07.095-.077.21-.245.335s-.292.214-.363.12c-.07-.095.008-.273.176-.399c.168-.125.361-.15.432-.056");
}

.c0d08q5pa {
  stop-color: var(--svg-color--d14752, #D14752);
  stop-opacity: 0;
}

.c7n196bnp {
  stop-color: var(--svg-color--e4526b, #E4526B);
}

.c9pwu7abn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.331 10.693c.07.095-.077.21-.245.335s-.292.214-.363.12c-.07-.095.008-.273.176-.399c.168-.125.361-.15.432-.056");
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

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cxlbh0b3y {
  stop-color: var(--svg-color--ffa730, #FFA730);
}

.czn49vv7g {
  stop-color: var(--svg-color--482566, #482566);
}

.dl4slsgrs {
  stop-color: var(--svg-color--fdc6b3, #FDC6B3);
  stop-opacity: 0;
}

.dr4byj-pv {
  stop-color: var(--svg-color--c33d4a, #C33D4A);
  stop-opacity: 0;
}

.dwbk77sau {
  stop-color: var(--svg-color--be7278, #BE7278);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ecvjpibkc {
  stop-color: var(--svg-color--bc314f, #BC314F);
}

.ef6ccrb4s {
  cx: 21.277px;
  cy: 11.771px;
  r: 1.855px;
}

.eme14ebhs {
  cx: 21.276px;
  cy: 11.771px;
  r: 1.106px;
}

.evin7izob {
  stop-color: var(--svg-color--db9e53, #DB9E53);
}

.ew4g_q7fo {
  stop-color: var(--svg-color--ffa748, #FFA748);
}

.f732de1pg {
  d: path("M16 7.44a.96.96 0 1 0 0-1.92a.96.96 0 0 0 0 1.92");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fkmdvohxo {
  d: path("M17.57 20.76h-3.14c-.74 0-1.34-.6-1.34-1.34v-1.66h5.83v1.66c-.01.74-.61 1.34-1.35 1.34");
}

.flf9rbc7z {
  stop-color: var(--svg-color--d79f98, #D79F98);
  stop-opacity: 0;
}

.fnqzb7fjl {
  stop-color: var(--svg-color--ffdb5a, #FFDB5A);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g8m56cc6j {
  fill: var(--svg-color--373536, #373536);
  d: path("M20.82 6.48v.93c0 .38.16.74.44.99l.22.2c.24.22.37.53.35.86c-.04.63-.11 1.6-.11 1.6c.34-.02.63-.27.69-.61L22.93 7c.03-.17.05-.35.04-.52z");
}

.gaadbc7ca {
  stop-color: var(--svg-color--493d55, #493D55);
}

.ghlk_kb0r {
  d: path("M13.55 10.483a.992.992 0 0 0-.955 1.253h1.915q.036-.128.037-.261a1 1 0 0 0-.997-.992");
}

.ghzdp7n3n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.025 9.164c.363-.322 1.157-.66 2.142-.503");
}

.gmeez-00x {
  stop-color: var(--svg-color--ea3662, #EA3662);
}

.h-78cmokj {
  stop-color: var(--svg-color--e3205c, #E3205C);
  stop-opacity: 0;
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hprgdjbtv {
  stop-color: var(--svg-color--493d55, #493D55);
  stop-opacity: 0;
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

.iyrvmvbea {
  cx: 21.276px;
  cy: 11.771px;
  r: 1.106px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
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

.jwz4w_b7k {
  d: path("M19.287 11.344a.93.93 0 0 0-.257-.514l-.289.317l.13.254z");
}

.k06it9j6t {
  stop-color: var(--svg-color--ae5a24, #AE5A24);
  stop-opacity: 0;
}

.ks7296big {
  stop-color: var(--svg-color--499065, #499065);
}

.l1dhji-tq {
  d: path("M22.59 8H9.41c-.41 0-.73-.36-.67-.77l.24-1.69c.05-.33.33-.58.67-.58h12.7c.33 0 .62.25.67.58l.24 1.69c.06.41-.26.77-.67.77");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.le-n4cbjm {
  d: path("M16 2.076c-.732 0-1.9.832-2.36 3.205h4.72C17.9 2.908 16.733 2.076 16 2.076");
}

.lgl8s0brp {
  d: path("M10.118 9.491c0-.296-.061-1.088.177-1.265l.179-.178c.298-.237.417-.593.417-.949l.31-.512a.58.58 0 0 1 .477-.593c.716-.178 2.206-.474 4.352-.474s3.637.296 4.352.474c.239.06.477.297.477.593l.19.69c0 .356.178.711.417.949c.558.39.523.606.477 1.067c-.213 2.112-.387 3.32-.584 6.257c-.179 1.967-1.725 3.338-3.568 3.338h-3.568c-1.903 0-3.39-1.37-3.568-3.338c-.155-2.018-.353-4.043-.537-6.059");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.liw9t7rjp {
  fill: var(--svg-color--413835, #413835);
  d: path("M9.02 6.48c0 .17.01.34.04.52l.51 3.46c.06.34.36.6.71.61c0 0-.07-.98-.11-1.61c-.02-.34.11-.66.35-.87l.2-.19c.28-.25.44-.61.44-.99v-.93z");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lzwd5_bie {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.634 10.181c.726 0 1.339.5 1.505 1.177a.304.304 0 0 1-.297.378h-2.48a.256.256 0 0 1-.252-.302a1.55 1.55 0 0 1 1.524-1.253");
}

.m26px3bad {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m20.114 8.748l-.001-.001l-.002-.002l-.005-.004l-.014-.01a2 2 0 0 0-.172-.12a3 3 0 0 0-.466-.234a3.15 3.15 0 0 0-1.66-.176a.593.593 0 0 0 .186 1.172c.442-.07.796.011 1.038.107a1.7 1.7 0 0 1 .333.177l.01.007a.593.593 0 0 0 .753-.916");
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.n4b_67bko {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.98 15.25a3.34 3.34 0 0 1-1.54-.365c-.151-.078-.315.094-.22.232c.373.564 1.021.94 1.76.94s1.387-.376 1.76-.94c.095-.144-.068-.31-.22-.232c-.446.232-.97.365-1.54.365");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc2yi90jd {
  stop-color: var(--svg-color--ff5e85, #FF5E85);
}

.nnakm0bzg {
  stop-color: var(--svg-color--4e3b4e, #4E3B4E);
}

.nxu86dbfw {
  fill: var(--svg-color--000, #000);
  d: path("M14.118 11.475a.566.566 0 0 0-.568-.568a.566.566 0 0 0-.504.83h1.005a.56.56 0 0 0 .067-.262");
}

.nyf3aqbrp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.826 8.588c.478-.084 1.41-.06 2.055.442");
}

.o55h-3blp {
  d: path("M14.457 11.358c0-.32-.261-.534-.332-.598l-.32.31l.197.401z");
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

.pr-umdqbw {
  stop-color: var(--svg-color--fd3b6f, #FD3B6F);
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q6eft0bey {
  stop-color: var(--svg-color--c03c64, #C03C64);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0c1q-bfc {
  stop-color: var(--svg-color--bc314f, #BC314F);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
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

.r9p5f7xkf {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.555 11.454l-.59 1.889a.6.6 0 0 0 .578.777h.874a.6.6 0 0 0 .579-.777l-.59-1.889c-.127-.418-.718-.418-.85 0");
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rpm92ubuz {
  cx: 10.703px;
  cy: 11.771px;
  r: 1.855px;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s8zg0sozp {
  stop-color: var(--svg-color--ff4c7c, #FF4C7C);
}

.sspkqpghz {
  stop-color: var(--svg-color--cc898e, #CC898E);
}

.su33dtg0a {
  stop-color: var(--svg-color--b66913, #B66913);
  stop-opacity: 0;
}

.t_df9tb_q {
  stop-color: var(--svg-color--512f64, #512F64);
  stop-opacity: 0;
}

.td4-ylb3b {
  fill: var(--svg-color--e0244f, #E0244F);
  fill-rule: evenodd;
  d: path("m12.08 19.566l1.01-.8l4.732.185l2.078.615c0 1.242-1.05 2.253-2.34 2.253h-.81c-.14 0-.25.106-.25.241v7.696h-1V22.06c0-.135-.11-.24-.25-.24h-.83c-1.29 0-2.34-1.012-2.34-2.254m2.35 1.29h3.14c.74 0 1.34-.578 1.35-1.29v-1.6h-5.83v1.6c0 .712.6 1.29 1.34 1.29");
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tub-h5-kh {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.32 10.181c-.725 0-1.338.5-1.505 1.177a.304.304 0 0 0 .297.378h2.48a.256.256 0 0 0 .252-.302a1.56 1.56 0 0 0-1.524-1.253");
}

.uc-aspg5k {
  d: path("M16 2c-.699 0-1.814.852-2.254 3.281h4.508C17.814 2.851 16.698 2 16 2");
}

.ueof-5erp {
  d: path("M14.78 23.6c0-.28.22-.5.5-.5h1.44c.28 0 .5.22.5.5s-.22.5-.5.5h-1.44c-.28 0-.5-.22-.5-.5");
}

.v3k97obpg {
  d: path("M18.404 10.483a.992.992 0 0 1 .956 1.253h-1.916a.995.995 0 0 1 .96-1.253");
}

.v7hu212ki {
  stop-color: var(--svg-color--e2526d, #E2526D);
}

.vf8snhbcg {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.786 8.748l.002-.002l.005-.004l.013-.01a2 2 0 0 1 .173-.12c.11-.07.267-.156.466-.234a3.15 3.15 0 0 1 1.659-.176a.593.593 0 1 1-.185 1.172a1.96 1.96 0 0 0-1.038.107a1.7 1.7 0 0 0-.342.184a.593.593 0 0 1-.755-.916");
}

.vfpv2h20z {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.98 15.25a3.34 3.34 0 0 1-1.54-.365c-.151-.078-.315.094-.22.232c.373.564 1.021.94 1.76.94s1.387-.376 1.76-.94c.095-.144-.068-.31-.22-.232c-.446.232-.97.365-1.54.365Z");
}

.vl0vrwboz {
  stop-color: var(--svg-color--d5345b, #D5345B);
  stop-opacity: 0;
}

.vsn-65dkv {
  stop-color: var(--svg-color--c33d4a, #C33D4A);
}

.vzmlz-b3e {
  stop-color: var(--svg-color--5e5065, #5E5065);
}

.w35ommbhj {
  stop-color: var(--svg-color--46384c, #46384C);
}

.w6cz6mbua {
  d: path("M14.78 26.55c0-.28.22-.5.5-.5h1.44c.28 0 .5.22.5.5s-.22.5-.5.5h-1.44c-.28 0-.5-.22-.5-.5");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wh9qglb-y {
  stop-color: var(--svg-color--f6ac3f, #F6AC3F);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wk0oy9-zi {
  stop-color: var(--svg-color--d59a9a, #D59A9A);
  stop-opacity: 0;
}

.wzjvs5_gw {
  stop-color: var(--svg-color--ae5a24, #AE5A24);
}

.x0qyerbek {
  stop-color: var(--svg-color--ff5e85, #FF5E85);
  stop-opacity: 0;
}

.x46zv8bqj {
  stop-color: var(--svg-color--e3205c, #E3205C);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
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

.ydbzq4btt {
  fill: var(--svg-color--000, #000);
  d: path("M17.836 11.475c0-.316.252-.568.568-.568a.566.566 0 0 1 .505.83h-1.005a.5.5 0 0 1-.068-.262");
}

.yt856tfpq {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.674 11.636l-.912 1.889c-.113.388.159.777.543.777h.82c.384 0 .655-.395.542-.777l-.554-1.89c-.119-.418-.314-.418-.439 0");
}

.yvxubnx_l {
  stop-color: var(--svg-color--fd3b6f, #FD3B6F);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.yz-njx9ds {
  stop-color: var(--svg-color--fdc6b3, #FDC6B3);
}

.z-cidv2vh {
  stop-color: var(--svg-color--ed396d, #ED396D);
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z5x2mc9xh {
  stop-color: var(--svg-color--512f64, #512F64);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zchv5y5ol {
  stop-color: var(--svg-color--615f64, #615F64);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zveuazben {
  stop-color: var(--svg-color--69597a, #69597A);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
