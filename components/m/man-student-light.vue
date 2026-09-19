<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qfn_ae0cx"/><path fill="url(#imDmqfe)" class="e_-14kbim"/><path fill="url(#i5IAWCc)" class="e_-14kbim"/><path fill="url(#i8nKFrd)" class="vt-w_nb-g"/><path fill="url(#i0bNGBx)" class="vt-w_nb-g"/><path fill="url(#i6S4QUc)" class="vt-w_nb-g"/><path fill="url(#iElkAcc)" class="vt-w_nb-g"/><path fill="url(#ik3YJdk)" class="vt-w_nb-g"/><path fill="url(#iEWD7Wl)" class="vt-w_nb-g"/><g filter="url(#iaG8ZlJ)"><path class="s2xi8xyxr"/></g><path fill="url(#iPOcyrd)" class="ovyv25b2j"/><path fill="url(#iluvxLq)" class="ovyv25b2j"/><path fill="url(#iTHyI2c)" class="ovyv25b2j"/><path fill="url(#i2hZSSc)" class="oec827bxy"/><path fill="url(#iYJWQyM)" class="oec827bxy"/><path fill="url(#ifkayYX)" class="f2tozsboj"/><path fill="url(#iOCHW3Y)" class="f2tozsboj"/><g filter="url(#ikhowBd)"><path stroke="url(#ihwxKDT)" class="cs5yzeu6f"/></g><path fill="url(#imqfWwd)" class="kfjevfb3k"/><path fill="url(#iDPWmye)" class="kfjevfb3k"/><path fill="url(#io3LuAc)" class="kfjevfb3k"/><path fill="url(#icdU9Qd)" class="kfjevfb3k"/><path fill="url(#i8TU3vR)" class="kfjevfb3k"/><path fill="url(#i4CrRfe)" class="dxo74tmwv"/><path fill="url(#ijUTMZd)" class="dxo74tmwv"/><path fill="url(#izFGpjA)" class="dxo74tmwv"/><path fill="url(#idv5hFd)" class="w4ocpbrxd"/><path fill="url(#irtLC3b)" class="w4ocpbrxd"/><g filter="url(#i8AHfxa)"><path fill="url(#i9eNmcn)" class="yiuervbll"/><path fill="url(#i9eNmcn)" class="zxq7dbccz"/><path fill="url(#i9eNmcn)" class="qfxbx3cjf"/></g><g filter="url(#itkXoab)"><circle fill="url(#iC587Jd)" class="ktcx2obhy"/></g><g filter="url(#iR21htb)"><circle fill="url(#i55eDdd)" class="pat90_bjv"/></g><g filter="url(#iZTGTrn)"><circle fill="url(#iDy9Cte)" class="ik8ezkb9r"/><circle fill="url(#iRBWibc)" class="ik8ezkb9r"/></g><g filter="url(#iXrGh7b)"><circle class="qt1vmib3n"/><circle fill="url(#ixK7mad)" class="dv8akibyd"/><circle fill="url(#iDnTLub)" class="dv8akibyd"/></g><g filter="url(#iNVHhKj)"><path fill="url(#ii0tEKc)" class="x297jzbsg"/><path fill="url(#iXytGYd)" class="x297jzbsg"/><path fill="url(#iBxg1se)" class="x297jzbsg"/><path fill="url(#ibrROoc)" class="x297jzbsg"/><path fill="url(#iwzUYCb)" class="x297jzbsg"/><path fill="url(#ij0aBPd)" class="x297jzbsg"/><path fill="url(#iroqEge)" class="x297jzbsg"/></g><g filter="url(#iNpWB0b)"><path fill="url(#iAcZXZb)" class="c26sc4-zy"/></g><g filter="url(#ihVcqcc)"><path class="b-y4tsbyy"/><path fill="url(#i2l3j1b)" class="l8g46cbmh"/><path fill="url(#iuA5Mzc)" class="l8g46cbmh"/><path fill="url(#i59N8Qc)" class="l8g46cbmh"/><path fill="url(#iKcxopd)" class="l8g46cbmh"/></g><g filter="url(#ilExZrb)"><path class="hi61i3bij"/></g><g filter="url(#iF35Juc)"><path class="nxyt6pb9q"/><path fill="url(#iGQSBZb)" class="cz8kxbc2y"/><path fill="url(#iCo55VI)" class="cz8kxbc2y"/><path fill="url(#ieB6Eid)" class="cz8kxbc2y"/><path fill="url(#iFIiqkb)" class="cz8kxbc2y"/></g><path fill="url(#iUiVScc)" class="cz8kxbc2y"/><path stroke="url(#iOE0GZZ)" class="w62xr981d"/><g filter="url(#ivFzVub)"><path class="yk8_82b8k"/></g><g filter="url(#inXMPUc)"><path class="j1de6q96a"/></g><path class="cuf-nibdd"/><path fill="url(#igUpJ0d)" class="rvs-fx34k"/><path class="hserl_rix"/><g filter="url(#isS8vFb)"><path class="xd8rdyque"/><path fill="url(#iTMjOCD)" class="j5sfpcb2g"/></g><g filter="url(#ikskGMb)"><path fill="url(#i4cltUd)" class="tda92yahp"/></g><path class="utizqs14z"/><path fill="url(#iRkjcEd)" class="pqe_a5b5o"/><path class="us0c-kboq"/><g filter="url(#iRoS2oT)"><path fill="url(#iaPmGNc)" class="nz1efumjm"/></g><g filter="url(#ihn8Nse)"><ellipse transform="rotate(-27.914 13.997 9.878)" class="cn14v0bbf"/><ellipse fill="url(#i9V9pje)" transform="rotate(-27.914 13.997 9.878)" class="a6tkkqb3c"/></g><g filter="url(#i4alq1c)"><path stroke="url(#i2X7W7V)" class="g1do5wbqy"/></g><g filter="url(#i7sQaQe)"><path stroke="url(#igxLspc)" class="tpu8y077f"/></g><g filter="url(#iSZSqHe)"><path stroke="url(#iBpBavb)" class="quuac1umh"/></g><g filter="url(#iBemVUd)"><path fill="url(#iGoJpKc)" class="twkees47c"/><path fill="url(#iwfrm6c)" class="twkees47c"/></g><path fill="url(#iwcwdwd)" class="xm8n21beo"/><path fill="url(#iGAIzbV)" class="xm8n21beo"/><path fill="url(#iOUGCbc)" class="xm8n21beo"/><defs><radialGradient id="imDmqfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.782 23.104)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="i5IAWCc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.188 21.448)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="i8nKFrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.488 21.338)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="i0bNGBx" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.48 16.885)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="i6S4QUc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.063 15.541)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iElkAcc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.813 15.307)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="ik3YJdk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.48 23.604)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iEWD7Wl" cx="0" cy="0" r="1" gradientTransform="rotate(85.281 -.114 16.005)scale(4.21461 7.75523)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="w7sh5cjwf"/><stop offset="1" class="ddl9sxmqm"/></radialGradient><radialGradient id="iPOcyrd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.784 18.209)" gradientUnits="userSpaceOnUse"><stop class="maef1bbsj"/><stop offset="1" class="ws5zlibzm"/><stop offset="1" class="rchayobux"/></radialGradient><radialGradient id="iluvxLq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.466 16.975)" gradientUnits="userSpaceOnUse"><stop class="dr7jm_b-p"/><stop offset="1" class="eths-3bvt"/></radialGradient><radialGradient id="iTHyI2c" cx="0" cy="0" r="1" gradientTransform="rotate(90 .967 15.5)scale(4.5407 4.26182)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="im04-mb9w"/><stop offset="1" class="wg5q2jt7g"/></radialGradient><radialGradient id="iYJWQyM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.055 11.657)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="ifkayYX" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.313 12.028)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iOCHW3Y" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.976 12.42)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iDPWmye" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.353 8.555)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="io3LuAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.813 13.096)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="i8TU3vR" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.813 16.885)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="i4CrRfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.485 29.984)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="ijUTMZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.25 29.984)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="idv5hFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.592 29.984)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="irtLC3b" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.54 23.145)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iC587Jd" cx="0" cy="0" r="1" gradientTransform="matrix(1.76824 0 0 3.09444 10.005 10.661)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iRBWibc" cx="0" cy="0" r="1" gradientTransform="matrix(.833 -.60656 .6923 .95077 21.648 10.394)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="ixK7mad" cx="0" cy="0" r="1" gradientTransform="matrix(.82754 -1.52204 .89086 .48436 21.23 11.489)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iDnTLub" cx="0" cy="0" r="1" gradientTransform="matrix(.26127 .25861 -.33339 .3368 21.273 10.661)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iXytGYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.83214 -11.9892 0 16.5 8.722)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="kogaa5ysr"/><stop offset="1" class="urp926bgm"/></radialGradient><radialGradient id="iwzUYCb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31704 1.62098 0 18.835 9.38)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="ij0aBPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40147 1.74285 0 14.242 9.346)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="iroqEge" cx="0" cy="0" r="1" gradientTransform="rotate(86.463 5.663 11.051)scale(2.53447 7.1978)" gradientUnits="userSpaceOnUse"><stop offset=".514" class="nxbhqbigk"/><stop offset="1" class="tko-bub4h"/></radialGradient><radialGradient id="i2l3j1b" cx="0" cy="0" r="1" gradientTransform="matrix(.8039 -2.97915 1.10477 .29811 20.85 6.523)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iuA5Mzc" cx="0" cy="0" r="1" gradientTransform="matrix(3.85399 .35466 -.1907 2.07226 19.194 4.75)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i59N8Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.69197 -2.62039 0 16.471 1.994)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iKcxopd" cx="0" cy="0" r="1" gradientTransform="matrix(3.09737 -2.26984 3.5561 4.85257 9.973 8.864)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iFIiqkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .1984 -.63741 0 16.8 12.28)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="igUpJ0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81732 -1.30003 0 18.667 9.974)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iTMjOCD" cx="0" cy="0" r="1" gradientTransform="matrix(-.23363 -.30107 .4145 -.32165 18.437 10.059)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRkjcEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81736 -1.3001 0 14.27 9.974)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i9V9pje" cx="0" cy="0" r="1" gradientTransform="matrix(-.0078 -.49773 .5983 -.00937 13.982 10.195)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGoJpKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6666 -3.56716 3.98507 -.7447 19.009 5.868)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iwfrm6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.97411 -7.12707 0 16.415 2.858)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iGAIzbV" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.22 2.385)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iOUGCbc" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.25 3.01)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><linearGradient id="i2hZSSc" x1="24.17" x2="25.356" y1="8.931" y2="8.931" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="ihwxKDT" x1="25.416" x2="25.416" y1="3.698" y2="11.465" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="imqfWwd" x1="25.965" x2="23.645" y1="14.795" y2="14.795" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="icdU9Qd" x1="23.764" x2="24.639" y1="14.475" y2="14.654" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="izFGpjA" x1="9.395" x2="8.969" y1="28.053" y2="28.053" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="i9eNmcn" x1="16.48" x2="16.48" y1="29.854" y2="23.42" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="i55eDdd" x1="11.687" x2="11.042" y1="10.942" y2="10.942" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iDy9Cte" x1="22.368" x2="21.543" y1="9.561" y2="12.117" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="ii0tEKc" x1="20.538" x2="12.843" y1="11.054" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="ydq0kpc8x"/><stop offset="1" class="e-sxlzbkb"/></linearGradient><linearGradient id="iBxg1se" x1="10.786" x2="14.17" y1="12.593" y2="12.707" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="ibrROoc" x1="11.034" x2="12.93" y1="13.77" y2="13.703" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iAcZXZb" x1="16.134" x2="24.34" y1="8.362" y2="5.424" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iGQSBZb" x1="15.6" x2="16.546" y1="11.718" y2="11.718" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iCo55VI" x1="17.417" x2="16.383" y1="12.043" y2="12.028" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ieB6Eid" x1="16.667" x2="16.667" y1="12.791" y2="12.213" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iUiVScc" x1="16.598" x2="16.598" y1="12.833" y2="12.664" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="iOE0GZZ" x1="15.426" x2="15.864" y1="14.418" y2="13.726" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="i4cltUd" x1="19.45" x2="19.134" y1="10.028" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaPmGNc" x1="15.02" x2="14.704" y1="10.028" y2="10.223" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2X7W7V" x1="19.466" x2="19.043" y1="7.872" y2="7.007" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="igxLspc" x1="14.121" x2="12.923" y1="7.744" y2="7.241" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iBpBavb" x1="11.774" x2="11.774" y1="5.714" y2="7.887" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iwcwdwd" x1="18.25" x2="16.969" y1="3.947" y2="-.428" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient><filter id="iaG8ZlJ" width="5.32" height="9.564" x="13.806" y="9.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".2"/></filter><filter id="ikhowBd" width=".65" height="8.268" x="24.591" y="3.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".125"/></filter><filter id="i8AHfxa" width="8.964" height="6.734" x="11.998" y="23.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".075"/></filter><filter id="itkXoab" width="3.564" height="3.364" x="10.005" y="8.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1596"/></filter><filter id="iR21htb" width="3.005" height="3.005" x="10.185" y="9.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".25"/></filter><filter id="iZTGTrn" width="3.614" height="3.614" x="19.591" y="8.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1596"/></filter><filter id="iXrGh7b" width="3.005" height="3.005" x="19.77" y="9.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".25"/></filter><filter id="iNVHhKj" width="10.453" height="12.37" x="11.274" y="4.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1596"/></filter><filter id="iNpWB0b" width="8.278" height="7.09" x="14.841" y="3.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation="1"/></filter><filter id="ihVcqcc" width="12.698" height="8.605" x="10.122" y="1.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1596"/></filter><filter id="ilExZrb" width="3.273" height="4.202" x="14.594" y="9.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".375"/></filter><filter id="iF35Juc" width="2.391" height="3.202" x="15.276" y="9.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".125"/></filter><filter id="ivFzVub" width="3" height="1.884" x="17.662" y="6.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1596"/></filter><filter id="inXMPUc" width="3.001" height="1.884" x="12.475" y="6.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1596"/></filter><filter id="isS8vFb" width=".791" height=".7" x="17.928" y="9.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".05"/></filter><filter id="ikskGMb" width=".895" height=".917" x="18.775" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".1"/></filter><filter id="iRoS2oT" width=".991" height="1.045" x="14.299" y="9.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".1"/></filter><filter id="ihn8Nse" width=".918" height=".708" x="13.538" y="9.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".05"/></filter><filter id="i4alq1c" width="2.564" height="1.135" x="17.794" y="7.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".125"/></filter><filter id="i7sQaQe" width="2.642" height="1.192" x="12.535" y="7.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".125"/></filter><filter id="iSZSqHe" width="1.01" height="2.281" x="11.269" y="5.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1596" stdDeviation=".125"/></filter><filter id="iBemVUd" width="12.135" height="2.935" x="10.406" y="3.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1596"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-student-light" /></template>
<style>
.a6tkkqb3c {
  cx: 13.997px;
  cy: 9.878px;
  rx: 0.393px;
  ry: 0.199px;
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b-y4tsbyy {
  fill: var(--svg-color--242324, #242324);
  d: path("m21.327 4.134l.432.215c.757.376 1.19 1.236 1.027 2.15l-.594 3.063c-.053.316-.263.529-.577.537h-.018s.054-.914.108-1.451c.044-.436-.032-.57-.432-.967c-.216-.215-.379-.538-.379-.86v-.86c0-.269-.216-.484-.432-.537c-.649-.162-2-.43-3.945-.43c-1.946 0-3.297.268-3.946.43a.524.524 0 0 0-.432.537v.86c0 .322-.109.645-.379.86l-.162.16c-.216.162-.324.485-.324.753c.054.591.108 1.451.108 1.451l-.05-.001a.64.64 0 0 1-.599-.536l-.594-3.063c-.108-.86.324-1.72 1.08-2.096l.433-.215c.27-.161.54-.376.81-.591l.974-1.021c.594-.538 1.459-.699 2.216-.323c.54.161 1.135.161 1.675 0c.81-.269 1.73-.054 2.378.538l.811.806c.216.268.487.43.81.59");
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
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

.c26sc4-zy {
  d: path("m20.663 5.31l-3.1 1.033a1.055 1.055 0 0 0 .473 2.047l3.083-.413z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.cn14v0bbf {
  cx: 13.997px;
  cy: 9.878px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.393px;
  ry: 0.199px;
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cs5yzeu6f {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.916 3.698v7.767");
}

.cuf-nibdd {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.877 9.22c.658 0 1.214.453 1.365 1.066a.276.276 0 0 1-.27.344h-2.247a.232.232 0 0 1-.23-.274a1.41 1.41 0 0 1 1.382-1.136");
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.cz8kxbc2y {
  d: path("m16.086 10.374l-.535 1.712a.543.543 0 0 0 .524.705h.792a.545.545 0 0 0 .525-.705l-.536-1.712c-.114-.38-.65-.38-.77 0");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.ddl9sxmqm {
  stop-color: var(--svg-color--1c1026, #1C1026);
  stop-opacity: 0;
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dr7jm_b-p {
  stop-color: var(--svg-color--b0797e, #B0797E);
}

.dv8akibyd {
  cx: 21.273px;
  cy: 10.661px;
  r: 1.003px;
}

.dxo74tmwv {
  d: path("M9.25 29.984V18.198a10.97 10.97 0 0 0-3.765 8.286v3.5z");
}

.e_-14kbim {
  d: path("M16.485 15.484c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.e-sxlzbkb {
  stop-color: var(--svg-color--daa594, #DAA594);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eths-3bvt {
  stop-color: var(--svg-color--b0797e, #B0797E);
  stop-opacity: 0;
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f2tozsboj {
  d: path("M24.413 11.633a.837.837 0 1 0 .8 0z");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g1do5wbqy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.144 7.775c.434-.076 1.279-.054 1.864.4");
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hi61i3bij {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m16.194 10.538l-.827 1.713c-.102.352.143.704.492.704h.743c.348 0 .594-.357.492-.704l-.503-1.713c-.107-.38-.285-.38-.397 0");
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hserl_rix {
  fill: var(--svg-color--000, #000);
  d: path("M18.154 10.393c0-.287.229-.515.515-.515a.513.513 0 0 1 .457.752h-.91a.47.47 0 0 1-.062-.237");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.ik8ezkb9r {
  cx: 21.273px;
  cy: 10.661px;
  r: 1.682px;
}

.im04-mb9w {
  stop-color: var(--svg-color--b5836a, #B5836A);
  stop-opacity: 0;
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j1de6q96a {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.669 7.92h.002l.001-.002l.005-.004l.012-.01l.036-.027q.045-.033.12-.08c.1-.063.243-.142.423-.213a2.86 2.86 0 0 1 1.504-.16a.538.538 0 0 1-.168 1.063a1.8 1.8 0 0 0-.94.097a1.5 1.5 0 0 0-.311.167a.538.538 0 0 1-.684-.83");
}

.j5sfpcb2g {
  d: path("M18.603 9.684c.064.085-.07.19-.222.304c-.153.113-.265.194-.33.108c-.064-.086.008-.248.16-.361c.152-.114.328-.137.392-.051");
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kfjevfb3k {
  d: path("m23.96 13.594l-.517 2.239a.45.45 0 0 0 .445.551h1.863a.45.45 0 0 0 .43-.557l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.kogaa5ysr {
  stop-color: var(--svg-color--cd9695, #CD9695);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.ktcx2obhy {
  cx: 11.687px;
  cy: 10.661px;
  r: 1.682px;
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l8g46cbmh {
  d: path("m21.327 4.134l.432.215c.757.376 1.19 1.236 1.027 2.15l-.594 3.063c-.053.316-.263.529-.577.537h-.018s.054-.914.108-1.451c.044-.436-.032-.57-.432-.967c-.216-.215-.379-.538-.379-.86v-.86c0-.269-.216-.484-.432-.537c-.649-.162-2-.43-3.945-.43c-1.946 0-3.297.268-3.946.43a.524.524 0 0 0-.432.537v.86c0 .322-.109.645-.379.86l-.162.16c-.216.162-.324.485-.324.753c.054.591.108 1.451.108 1.451l-.05-.001a.64.64 0 0 1-.599-.536l-.594-3.063c-.108-.86.324-1.72 1.08-2.096l.433-.215c.27-.161.54-.376.81-.591l.974-1.021c.594-.538 1.459-.699 2.216-.323c.54.161 1.135.161 1.675 0c.81-.269 1.73-.054 2.378.538l.811.806c.216.268.487.43.81.59");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.maef1bbsj {
  stop-color: var(--svg-color--cd9e8e, #CD9E8E);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nxbhqbigk {
  stop-color: var(--svg-color--c1887b, #C1887B);
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.nxyt6pb9q {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m16.086 10.374l-.535 1.712a.543.543 0 0 0 .524.705h.792a.545.545 0 0 0 .525-.705l-.536-1.712c-.114-.38-.65-.38-.77 0");
}

.nz1efumjm {
  d: path("M15.09 10.287c0-.29-.237-.484-.3-.543l-.291.281l.179.364z");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oec827bxy {
  d: path("M25.213 11.657V2.794h-.8v8.863z");
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.ovyv25b2j {
  d: path("M16.186 18.855c.063.043.17.08.28.083a.56.56 0 0 0 .28-.083c1.017-.697 1.78-1.39 1.78-2.587v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.587");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.pat90_bjv {
  cx: 11.687px;
  cy: 10.661px;
  r: 1.003px;
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.pqe_a5b5o {
  d: path("M14.268 9.493a.9.9 0 0 0-.866 1.136h1.737a1 1 0 0 0 .033-.236a.905.905 0 0 0-.904-.9");
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qfn_ae0cx {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.485 15.484c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.qfxbx3cjf {
  d: path("M20.12 23.76c0-.187.155-.34.346-.34s.346.153.346.34v6.094h-.691z");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qt1vmib3n {
  cx: 21.273px;
  cy: 10.661px;
  r: 1.003px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.quuac1umh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.904 5.813v.905c-.008.15-.071.484-.26.626");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rchayobux {
  stop-color: var(--svg-color--b78273, #B78273);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rvs-fx34k {
  d: path("M18.669 9.493a.9.9 0 0 1 .866 1.136h-1.737a.903.903 0 0 1 .87-1.136");
}

.s2xi8xyxr {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.186 18.855c.063.043.17.08.28.083a.56.56 0 0 0 .28-.083c1.017-.697 1.78-1.39 1.78-2.587v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.587Z");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tda92yahp {
  d: path("M19.47 10.274a.85.85 0 0 0-.234-.466l-.261.287l.118.23z");
}

.tko-bub4h {
  stop-color: var(--svg-color--c1887b, #C1887B);
  stop-opacity: 0;
}

.tpu8y077f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.885 8.297c.33-.291 1.05-.598 1.942-.456");
}

.twkees47c {
  d: path("M10.406 5.118L11.5 3.244l9.845-.11l1.196 1.974c-4.664 1.61-10.045.745-12.135.01");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.urp926bgm {
  stop-color: var(--svg-color--ab7277, #AB7277);
}

.us0c-kboq {
  fill: var(--svg-color--000, #000);
  d: path("M14.783 10.393a.513.513 0 0 0-.515-.515a.513.513 0 0 0-.457.752h.911a.5.5 0 0 0 .061-.237");
}

.utizqs14z {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.06 9.22c-.658 0-1.214.453-1.365 1.066a.276.276 0 0 0 .27.343h2.248a.23.23 0 0 0 .228-.273a1.41 1.41 0 0 0-1.381-1.137");
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vt-w_nb-g {
  d: path("M23.5 18.084a.24.24 0 0 0-.058-.29c-1.856-1.603-4.346-2.487-6.954-2.487s-5.113.893-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.015 7.013-4.614");
}

.w4ocpbrxd {
  d: path("M23.71 29.984V18.198a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.w62xr981d {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.099 13.44a3 3 0 0 0 1.372.325a2.96 2.96 0 0 0 1.373-.325a.204.204 0 0 1 .243.04a.19.19 0 0 1 .02.242M15.1 13.44l2.967.255M15.1 13.44a.204.204 0 0 0-.244.042a.19.19 0 0 0-.02.24m.264-.282l-.223.255m3.232.027l-.042-.027m.042.027l-.042-.027m.042.027c-.346.525-.95.875-1.637.875s-1.29-.35-1.636-.874m3.231-.028a1.91 1.91 0 0 1-1.595.852c-.67 0-1.257-.34-1.595-.852m-.041.028l.041-.028m-.041.028l.041-.028");
}

.w7sh5cjwf {
  stop-color: var(--svg-color--1c1026, #1C1026);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wg5q2jt7g {
  stop-color: var(--svg-color--b5836a, #B5836A);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.ws5zlibzm {
  stop-color: var(--svg-color--a56d67, #A56D67);
}

.x297jzbsg {
  d: path("M11.274 8.595c0-.27.108-.592.324-.753l.162-.161c.27-.215.379-.537.379-.86v-.86c0-.268.162-.483.432-.537c.649-.161 2-.43 3.946-.43c1.945 0 3.297.269 3.945.43c.216.054.433.269.433.537v.86c0 .323.162.645.378.86c.506.354.474.55.432.967c-.054.538-.108 1.451-.108 1.451h.018l-.267 3.989c-.162 1.783-1.564 3.025-3.235 3.025h-3.235c-1.725 0-3.073-1.242-3.235-3.025c-.14-1.83-.202-3.666-.37-5.493");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xd8rdyque {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.603 9.684c.064.085-.07.19-.222.304c-.153.113-.265.194-.33.108c-.064-.086.008-.248.16-.361c.152-.114.328-.137.392-.051");
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xm8n21beo {
  d: path("M24.423 3.594H8.453c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.ydq0kpc8x {
  stop-color: var(--svg-color--ffdac0, #FFDAC0);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yiuervbll {
  d: path("M12.148 23.76c0-.187.155-.34.346-.34s.345.153.345.34v6.094h-.691z");
}

.yk8_82b8k {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M20.22 7.92h-.002l-.002-.002l-.005-.004l-.012-.01l-.036-.027q-.045-.033-.12-.08a2.6 2.6 0 0 0-.423-.213a2.86 2.86 0 0 0-1.504-.16a.538.538 0 0 0 .168 1.063c.4-.063.722.01.941.097a1.5 1.5 0 0 1 .31.167a.538.538 0 0 0 .684-.83");
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxq7dbccz {
  d: path("M16.134 23.76c0-.187.155-.34.346-.34s.346.153.346.34v6.094h-.692z");
}

</style>
