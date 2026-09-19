<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ieJ6use)"><path fill="url(#iYGsaCe)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iZe9Aoe)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#irCXIUW)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#icTu2PU)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iQNsJGe)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iPkaUQc)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#i6c95ge)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iK0qH7c)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iWWBacd)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iAeG2Ob)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iYvmg2c)" clip-rule="evenodd" class="m1iyf1g2x"/><path fill="url(#iqRoEjd)" clip-rule="evenodd" class="m1iyf1g2x"/></g><g filter="url(#iuqFrac)"><path class="k1f3qcchq"/><path fill="url(#iIlA6Tc)" class="ycwa9eb_e"/><path fill="url(#iYZuy8b)" class="ycwa9eb_e"/></g><rect fill="url(#iBCQGac)" class="iuxb-78iw"/><g filter="url(#ithpije)"><path fill="url(#i3mBgAb)" class="d6vd95iar"/></g><path fill="url(#ik0RJnb)" class="d6vd95iar"/><g filter="url(#iXaQQ0c)"><path fill="url(#ijrDXjb)" class="uk2ncbbma"/><path fill="url(#i98debc)" class="uk2ncbbma"/></g><g filter="url(#iUGjaue)"><path class="b-gakmb8w"/><path fill="url(#ilBfxkd)" class="mu01z6bem"/></g><g filter="url(#izjEGDc)"><path class="oqfljpscw"/><path fill="url(#i2RJiid)" class="bfsgwjb9t"/></g><g filter="url(#iAJZnBc)"><path fill="url(#igSvB4J)" class="yzi21fb4g"/><path fill="url(#ispaMAc)" class="yzi21fb4g"/><path fill="url(#ilxYs3d)" class="yzi21fb4g"/><path fill="url(#ie0DMEq)" class="yzi21fb4g"/><path fill="url(#ihH6Xgq)" class="yzi21fb4g"/><path fill="url(#i7lYZAD)" class="yzi21fb4g"/><path fill="url(#if1SLsb)" class="yzi21fb4g"/><path fill="url(#in5Yvad)" class="yzi21fb4g"/><path fill="url(#i33AIMd)" class="yzi21fb4g"/></g><g filter="url(#ivVSTYb)"><path fill="url(#iqmPstu)" class="uln231kpo"/><path fill="url(#i1AXRne)" class="uln231kpo"/><path fill="url(#iRnfZEc)" class="uln231kpo"/><path fill="url(#i7tI4Ad)" class="uln231kpo"/><path fill="url(#il2PwLb)" class="uln231kpo"/><path fill="url(#igblAQi)" class="uln231kpo"/><path fill="url(#iIIP3kd)" class="uln231kpo"/><path fill="url(#iLsZGed)" class="uln231kpo"/></g><g filter="url(#i6NUZPc)"><path class="z6rkwybog"/></g><g filter="url(#iJoWRre)"><path class="l7tknhp1j"/><path fill="url(#ivc3LQd)" class="smymh0ctp"/><path fill="url(#ihizcmb)" class="smymh0ctp"/><path fill="url(#iBh7sbd)" class="smymh0ctp"/><path fill="url(#iMD86Ao)" class="smymh0ctp"/></g><path fill="url(#isgRyuc)" class="smymh0ctp"/><path fill="url(#io76mKb)" class="smymh0ctp"/><path stroke="url(#isOUTzb)" class="xeu1i8_2e"/><g filter="url(#iggt7Ac)"><path class="ddweocbxr"/></g><g filter="url(#i9zOyUd)"><path class="lsiu18bln"/></g><g filter="url(#iNCrluF)"><path class="tu-obdbxy"/></g><g filter="url(#iOqkIiz)"><path clip-rule="evenodd" class="bfcl5jbvx"/></g><path class="rulxhjbmx"/><path fill="url(#ixLJYPd)" class="s1ezr1uia"/><path class="omsy5rb5f"/><g filter="url(#i73iGMe)"><path class="ykc0ffbbx"/><path fill="url(#icZaN0p)" class="rly45w-8s"/></g><g filter="url(#irmzJnb)"><path fill="url(#iA0Az7c)" class="n_01qtz8z"/></g><path class="espu6yqld"/><path fill="url(#i9XYwfe)" class="uveyjtyye"/><path class="vhj3khb_o"/><g filter="url(#i2KYizc)"><path fill="url(#i9dXWVb)" class="tax50y56a"/></g><g filter="url(#iYRg6Ge)"><ellipse transform="rotate(-27.914 13.28 14.65)" class="lqqqcm7pt"/><ellipse fill="url(#i5vfB2z)" transform="rotate(-27.914 13.28 14.65)" class="iae434d0r"/></g><g filter="url(#iiSu9Zb)"><path class="y941_ef0l"/></g><g filter="url(#iLavYDc)"><path class="tcn3p6j4z"/></g><g filter="url(#iC9yULb)"><path class="g5w7r7bth"/><path fill="url(#iN5H7Hm)" class="c0n_qbjkq"/><path fill="url(#iGPgW6b)" class="c0n_qbjkq"/></g><g filter="url(#iX1FRAc)"><path stroke="url(#ivqFVOb)" class="s1r4eabtu"/></g><g filter="url(#ivGiMYO)"><path class="u6-x52blq"/></g><path fill="url(#iyxuAGd)" class="veix-z38b"/><path fill="url(#iTFLztb)" class="veix-z38b"/><path fill="url(#iRnp8Ge)" class="ygsync4_o"/><path fill="url(#iZdzdac)" class="ygsync4_o"/><path fill="url(#iu11BRc)" class="xg-84-b0v"/><path fill="url(#iwK5rTD)" class="xg-84-b0v"/><path fill="url(#izvkHAb)" class="p49nfmexu"/><path fill="url(#i8iCFbc)" class="p49nfmexu"/><g filter="url(#i8LX4Sb)"><path fill="url(#i7Zcrjd)" class="lnlk8lb5t"/></g><g filter="url(#iI5cCAd)"><path stroke="url(#iRYaePc)" class="yk5l_u5eu"/></g><path stroke="url(#itMzOYc)" class="djebsbcjo"/><path stroke="url(#iBwbe3a)" class="djebsbcjo"/><path stroke="url(#i9l0Tyc)" class="djebsbcjo"/><path stroke="url(#iXyXRRb)" class="w930jqbym"/><path stroke="url(#isp550c)" class="w930jqbym"/><path stroke="url(#iGo6V8I)" class="w930jqbym"/><path stroke="url(#ioxg6Ic)" class="w930jqbym"/><path stroke="url(#iOUBKxc)" class="cvtf9k6wz"/><path stroke="url(#itKlUKc)" class="cvtf9k6wz"/><path stroke="url(#iO64hWd)" class="cvtf9k6wz"/><path stroke="url(#igx9yjK)" class="aj6pj94ss"/><path stroke="url(#i2UTQMb)" class="aj6pj94ss"/><path stroke="url(#iSqUWvd)" class="aj6pj94ss"/><path stroke="url(#isYhsAe)" class="aj6pj94ss"/><path stroke="url(#iJSGV4o)" class="zw6cmm23y"/><path stroke="url(#ixnb1pe)" class="zw6cmm23y"/><path stroke="url(#ilnSumk)" class="zw6cmm23y"/><path stroke="url(#izWOOEe)" class="abd3-ibar"/><path stroke="url(#iQkYKsE)" class="abd3-ibar"/><path stroke="url(#iH9r1yv)" class="abd3-ibar"/><path stroke="url(#i2Z0BUd)" class="abd3-ibar"/><path stroke="url(#inr4rIT)" class="hockzyb4d"/><path stroke="url(#i4dC0dc)" class="hockzyb4d"/><path stroke="url(#iLdLFnc)" class="lgc2wbcpd"/><path stroke="url(#i9GHVpc)" class="lgc2wbcpd"/><path stroke="url(#iCa08Zc)" class="lgc2wbcpd"/><path stroke="url(#ilVYKhe)" class="lgc2wbcpd"/><path fill="url(#ia7dhhe)" class="eim_mrbrv"/><path fill="url(#iH74upe)" class="r_9_ioa3h"/><path fill="url(#i9zuWFb)" class="r_9_ioa3h"/><g filter="url(#iXjvxwb)"><path stroke="url(#igYnr8d)" class="ngb3gwb-q"/></g><g filter="url(#ivjFf4b)"><path stroke="url(#iQbEj7d)" class="gsuhbzbgv"/></g><g filter="url(#iCu13Qb)"><path stroke="url(#iXJuYOS)" class="cpr38db_u"/></g><g filter="url(#iTYX7Yc)"><path stroke="url(#i9PwSOd)" class="h-8-hirxp"/></g><defs><radialGradient id="iZe9Aoe" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 -.138 15.96)scale(5.0989 6.36957)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="irCXIUW" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.446 11.161)scale(3.85551 5.06584)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="icTu2PU" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 1.445 10.458)scale(2.38628 1.83233)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iQNsJGe" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 1.804 9.828)scale(2.7442 1.93304)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iPkaUQc" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 .683 13.254)scale(3.2752 4.54648)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i6c95ge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59812 1.59823 -2.2335 -2.23334 22.467 8.787)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iK0qH7c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.04414 .5947 -1.24018 -4.2629 24.326 14.474)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iWWBacd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.122 .78055 -.9943 -3.97697 23.657 18.265)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iAeG2Ob" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 14.835 -1.712)scale(3.10485 2.45575)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="iYvmg2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.66745 .1749 -.2834 2.70176 9.19 14.434)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iqRoEjd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 16.312 -1.8)scale(4.21084 1.51978)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iIlA6Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50152 -2.48377 3.85176 -3.87929 12.567 11.638)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="t0f6bgits"/><stop offset="1" class="jhe4hqqqz"/></radialGradient><radialGradient id="iYZuy8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6322 -2.0225 3.2754 -2.6433 11.84 10.946)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="pl07djbzg"/><stop offset="1" class="q4yl2z--c"/></radialGradient><radialGradient id="iBCQGac" cx="0" cy="0" r="1" gradientTransform="matrix(3.01446 2.67289 -4.14107 4.67027 14.504 21.8)" gradientUnits="userSpaceOnUse"><stop class="uclw0to3e"/><stop offset=".894" class="hvp7s_s8m"/></radialGradient><radialGradient id="ik0RJnb" cx="0" cy="0" r="1" gradientTransform="rotate(-118.51 10.3 5.517)scale(1.51846 1.72062)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="ijrDXjb" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 46.952 -39.319)scale(3.03143 3.70123)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="i98debc" cx="0" cy="0" r="1" gradientTransform="matrix(1.33804 0 0 .5761 21.482 13.526)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="ilBfxkd" cx="0" cy="0" r="1" gradientTransform="rotate(-4.254 219.665 -273.17)scale(1.6787 1.31228)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i2RJiid" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.45 7.709)scale(1.17079)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="ispaMAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.23667 -6.20284 0 16 20.756)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="w58diel4g"/><stop offset="1" class="v6fmdibat"/></radialGradient><radialGradient id="ilxYs3d" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.96 8.252)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="c74g9abcg"/><stop offset=".435" class="k33dgh0kx"/></radialGradient><radialGradient id="ie0DMEq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.985 14.584)" gradientUnits="userSpaceOnUse"><stop class="yu6zwbb_v"/><stop offset=".821" class="ksxm-h6au"/></radialGradient><radialGradient id="ihH6Xgq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.173 6.772)" gradientUnits="userSpaceOnUse"><stop class="jcr-_pt7q"/><stop offset="1" class="vtkyaex6k"/></radialGradient><radialGradient id="i7lYZAD" cx="0" cy="0" r="1" gradientTransform="rotate(120.342 2.473 5.772)scale(1.39468 3.26296)" gradientUnits="userSpaceOnUse"><stop class="t_fx8fd6d"/><stop offset="1" class="u3wjuqrnp"/></radialGradient><radialGradient id="if1SLsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13764 1.26425 -3.01923 -5.10504 10.375 18.694)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="rn8u6nbre"/><stop offset="1" class="zigbbibav"/></radialGradient><radialGradient id="in5Yvad" cx="0" cy="0" r="1" gradientTransform="rotate(59.077 7.488 25.014)scale(7.31511 1.73016)" gradientUnits="userSpaceOnUse"><stop class="i01-9l3nj"/><stop offset="1" class="jyzgzgaon"/></radialGradient><radialGradient id="i33AIMd" cx="0" cy="0" r="1" gradientTransform="rotate(54.389 5.84 25.868)scale(1.53089 3.55542)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="p2il30bmc"/><stop offset="1" class="pcu2ods2z"/></radialGradient><radialGradient id="iqmPstu" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.959 9.514)scale(7.9405 10.6282)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="i1AXRne" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.435 9.796)scale(2.64105 1.83918)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iRnfZEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42933 -4.35553 5.52636 1.81355 13.603 22.037)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i7tI4Ad" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4244 8.17493 -10.21854 -1.78048 17.135 14.36)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ndb61xwjr"/><stop offset="1" class="l57p2o49o"/></radialGradient><radialGradient id="il2PwLb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.19 9.246)scale(7.80262 13.4337)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="igblAQi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2759 1.56588 0 18.552 14.358)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iIIP3kd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.45523 1.6678 0 13.698 14.104)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iLsZGed" cx="0" cy="0" r="1" gradientTransform="matrix(-.96478 3.57762 -2.86269 -.77198 17.534 11.79)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="ivc3LQd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 15.174 1.645)scale(2.32187 .71558)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iMD86Ao" cx="0" cy="0" r="1" gradientTransform="matrix(-.86415 0 0 -.2416 16.604 17.047)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="io76mKb" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 5.667 10.74)scale(1.84412 2.21635)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="ixLJYPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89954 -1.43081 0 18.42 14.756)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="icZaN0p" cx="0" cy="0" r="1" gradientTransform="matrix(-.25713 -.33135 .4562 -.35401 18.166 14.849)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9XYwfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89954 -1.43082 0 13.58 14.756)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i5vfB2z" cx="0" cy="0" r="1" gradientTransform="matrix(-.00858 -.54778 .65846 -.0103 13.264 14.997)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iN5H7Hm" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3416 4.86897 -7.96048 -3.82838 18.119 6.631)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iGPgW6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.2332 1.51587 -3.2613 -.50173 16.233 7.04)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iyxuAGd" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="p96ugv3bq"/><stop offset="1" class="kaz2mfb2i"/></radialGradient><radialGradient id="iTFLztb" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="oc_nn33wh"/><stop offset="1" class="cxw9pac7i"/></radialGradient><radialGradient id="iRnp8Ge" cx="0" cy="0" r="1" gradientTransform="rotate(151.671 11.428 5.79)scale(3.23829 1.54626)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="fqnyw0bnc"/><stop offset="1" class="yysatcquz"/></radialGradient><radialGradient id="iZdzdac" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.401 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="dg25vhy-y"/><stop offset="1" class="dn15o-0do"/></radialGradient><radialGradient id="iu11BRc" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="b9m3k9r2b"/><stop offset="1" class="mkc39zb9h"/></radialGradient><radialGradient id="iwK5rTD" cx="0" cy="0" r="1" gradientTransform="matrix(.59766 .66937 -3.1595 2.82105 8.731 3.512)" gradientUnits="userSpaceOnUse"><stop class="wyik6iche"/><stop offset="1" class="g2x2jxbfq"/></radialGradient><radialGradient id="izvkHAb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.46 5.257)" gradientUnits="userSpaceOnUse"><stop class="c2k9t5bpp"/><stop offset="1" class="y1r1v2b6d"/></radialGradient><radialGradient id="i8iCFbc" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="h4ehjy6dd"/><stop offset="1" class="bj832jb3d"/></radialGradient><radialGradient id="i7Zcrjd" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.212 16.603)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="x733f4b8w"/><stop offset="1" class="doo06bbod"/></radialGradient><radialGradient id="iBwbe3a" cx="0" cy="0" r="1" gradientTransform="matrix(-.1096 -1.29967 5.61008 -.47306 12.856 3.344)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="i9l0Tyc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.592 7.886 -.066)scale(1.08537 1.14754)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="iGo6V8I" cx="0" cy="0" r="1" gradientTransform="matrix(-3.56426 2.0201 -2.31983 -4.09312 20.913 1.35)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="ioxg6Ic" cx="0" cy="0" r="1" gradientTransform="rotate(-80.888 11.736 -9.666)scale(1.42374 5.9709)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="ow_pc7b8u"/><stop offset=".979" class="d9x2ylwjm"/></radialGradient><radialGradient id="itKlUKc" cx="0" cy="0" r="1" gradientTransform="matrix(.01226 -1.01716 4.43025 .05338 14.082 3.674)" gradientUnits="userSpaceOnUse"><stop offset=".747" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="iO64hWd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.878 8.913 -1.65)scale(1.11775 .93295)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="iSqUWvd" cx="0" cy="0" r="1" gradientTransform="rotate(130.332 9.71 4.88)scale(5.09325 5.91748)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="isYhsAe" cx="0" cy="0" r="1" gradientTransform="matrix(.09206 -1.68795 4.97536 .27136 18.499 4.257)" gradientUnits="userSpaceOnUse"><stop offset=".773" class="dk1glybfm"/><stop offset=".979" class="a0yyvkbzn"/></radialGradient><radialGradient id="ixnb1pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.21324 6.39051 0 13.808 4.618)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="ilnSumk" cx="0" cy="0" r="1" gradientTransform="rotate(-130.37 8.838 -.994)scale(1.0406 .9935)" gradientUnits="userSpaceOnUse"><stop class="k84rzffkc"/><stop offset="1" class="f63cqv7mt"/></radialGradient><radialGradient id="iH9r1yv" cx="0" cy="0" r="1" gradientTransform="rotate(146.114 9.14 4.453)scale(3.02405 3.27841)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="i2Z0BUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13777 3.28035 0 18.35 4.566)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="dk1glybfm"/><stop offset=".979" class="a0yyvkbzn"/></radialGradient><radialGradient id="i4dC0dc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01775 -1.34298 3.63064 -.04798 13.474 5.765)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="re3qjtb0n"/><stop offset="1" class="dvyrp5bps"/></radialGradient><radialGradient id="iCa08Zc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23453 3.00551 -3.33751 -2.48137 19.584 3.08)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="fjos8cb-d"/><stop offset="1" class="e4s700vze"/></radialGradient><radialGradient id="ilVYKhe" cx="0" cy="0" r="1" gradientTransform="matrix(.10954 -1.26306 4.00443 .3473 18.771 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="dk1glybfm"/><stop offset=".829" class="a0yyvkbzn"/></radialGradient><radialGradient id="ia7dhhe" cx="0" cy="0" r="1" gradientTransform="rotate(99.386 9.322 10.144)scale(4.22369 15.0701)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="e9zt1qbrs"/><stop offset="1" class="tenu6ccuh"/></radialGradient><radialGradient id="iH74upe" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="n-vzpx_le"/><stop offset="1" class="g15wokvee"/></radialGradient><radialGradient id="i9zuWFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="ui8aeifuz"/><stop offset="1" class="xok7o2bsm"/></radialGradient><filter id="ieJ6use" width="16.901" height="17.401" x="7.674" y="5.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="iuqFrac" width="4.383" height="4.717" x="9.098" y="7.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".15"/></filter><filter id="ithpije" width="3.718" height="3.568" x="9.021" y="13.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="iXaQQ0c" width="3.568" height="3.818" x="19.568" y="13.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="iUGjaue" width="3.382" height="3.382" x="19.661" y="13.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".25"/></filter><filter id="izjEGDc" width="3.082" height="3.082" x="9.285" y="13.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".175"/></filter><filter id="iAJZnBc" width="28.403" height="24.735" x="2.048" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.25098 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="ivVSTYb" width="11.299" height="12.46" x="10.351" y="9.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="i6NUZPc" width="3.081" height="3.973" x="14.279" y="14.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".25"/></filter><filter id="iJoWRre" width="2.581" height="3.473" x="14.709" y="14.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".125"/></filter><filter id="iggt7Ac" width="3.306" height="1.425" x="17.066" y="13.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="i9zOyUd" width="3.306" height="1.425" x="11.628" y="13.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="iNCrluF" width="2.698" height="1.188" x="11.778" y="12.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="iOqkIiz" width="2.698" height="1.188" x="17.784" y="12.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3723"/></filter><filter id="i73iGMe" width=".851" height=".75" x="17.616" y="14.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".05"/></filter><filter id="irmzJnb" width=".945" height=".969" x="18.558" y="14.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".1"/></filter><filter id="i2KYizc" width="1.05" height="1.11" x="13.632" y="14.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".1"/></filter><filter id="iYRg6Ge" width=".991" height=".759" x="12.785" y="14.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".05"/></filter><filter id="iiSu9Zb" width="3.041" height="1.619" x="17.55" y="12.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".2"/></filter><filter id="iLavYDc" width="3.041" height="1.619" x="11.506" y="12.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".2"/></filter><filter id="iC9yULb" width="9.711" height="6.456" x="12.518" y="6.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".15"/></filter><filter id="iX1FRAc" width="1.204" height="2.496" x="12.495" y="7.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".1"/></filter><filter id="ivGiMYO" width="6.963" height="3.576" x="15.437" y="8.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".375"/></filter><filter id="i8LX4Sb" width="16.188" height="8.656" x="9.173" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".5"/></filter><filter id="iI5cCAd" width="3.994" height="4.556" x="7.973" y="22.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".25"/></filter><filter id="iXjvxwb" width="3.508" height="1.177" x="11.476" y="4.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".125"/></filter><filter id="ivjFf4b" width="4.103" height="1.115" x="11.342" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".125"/></filter><filter id="iCu13Qb" width="4.103" height="1.115" x="11.476" y="2.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".125"/></filter><filter id="iTYX7Yc" width="4.288" height="1.471" x="10.461" y="1.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3723" stdDeviation=".125"/></filter><linearGradient id="iYGsaCe" x1="21.204" x2="14.402" y1="7.709" y2="19.64" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="i3mBgAb" x1="9.021" x2="11.08" y1="15.514" y2="15.514" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="igSvB4J" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="ny7dycfhy"/><stop offset="1" class="xhpdgtb4r"/></linearGradient><linearGradient id="ihizcmb" x1="14.959" x2="16" y1="16.894" y2="16.894" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iBh7sbd" x1="16" x2="16" y1="17.677" y2="16.983" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="isgRyuc" x1="16.087" x2="16.087" y1="17.75" y2="17.596" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="isOUTzb" x1="14.82" x2="15.331" y1="19.343" y2="18.553" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iA0Az7c" x1="19.282" x2="18.934" y1="14.816" y2="15.03" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9dXWVb" x1="14.405" x2="14.057" y1="14.815" y2="15.03" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivqFVOb" x1="12.553" x2="13.096" y1="7.709" y2="9.112" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="iRYaePc" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="zxa4g21za"/><stop offset="1" class="py_i1i4hl"/></linearGradient><linearGradient id="itMzOYc" x1="14.261" x2="10.736" y1="2.588" y2="4.348" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="iXyXRRb" x1="19.032" x2="21.102" y1="2.588" y2="3.034" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="isp550c" x1="16.583" x2="21.672" y1="3.146" y2="3.689" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="iOUBKxc" x1="15.286" x2="12.235" y1="3.297" y2="4.422" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="igx9yjK" x1="18.499" x2="20.126" y1="3.297" y2="3.627" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="i2UTQMb" x1="15.618" x2="20.781" y1="4.277" y2="4.254" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="iJSGV4o" x1="14.956" x2="12.465" y1="4.165" y2="5.276" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="izWOOEe" x1="18.35" x2="19.914" y1="4.165" y2="4.234" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="iQkYKsE" x1="16.317" x2="19.96" y1="4.575" y2="4.546" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="inr4rIT" x1="14.472" x2="11.788" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="mgz6y4bsd"/><stop offset="1" class="zpfboqufv"/></linearGradient><linearGradient id="iLdLFnc" x1="19.589" x2="20.216" y1="5.254" y2="5.381" gradientUnits="userSpaceOnUse"><stop class="i4aahzyol"/><stop offset="1" class="i-v4lm-fq"/></linearGradient><linearGradient id="i9GHVpc" x1="16.849" x2="20.295" y1="5.882" y2="5.868" gradientUnits="userSpaceOnUse"><stop class="jjmtttbid"/><stop offset=".844" class="h-qwb4b2p"/></linearGradient><linearGradient id="igYnr8d" x1="14.651" x2="11.599" y1="5.259" y2="5.98" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="iQbEj7d" x1="15.121" x2="11.6" y1="4.207" y2="5.388" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="iXJuYOS" x1="15.255" x2="11.734" y1="3.221" y2="4.402" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient><linearGradient id="i9PwSOd" x1="14.436" x2="11.189" y1="2.409" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="wjf3cr6ec"/><stop offset="1" class="dz3ns1n_g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-ok-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a0yyvkbzn {
  stop-color: var(--svg-color--a48369, #A48369);
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.aj6pj94ss {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.627c-.43-.11-2.375-.477-3.255-.266");
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b-gakmb8w {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M21.352 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.b9m3k9r2b {
  stop-color: var(--svg-color--ae8671, #AE8671);
}

.bfcl5jbvx {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m20.137 12.94l-.153.254za.297.297 0 0 1-.306.51l-.004-.002a2 2 0 0 0-.126-.065a3 3 0 0 0-.38-.15a2.5 2.5 0 0 0-1.188-.102a.297.297 0 0 1-.103-.585c.569-.1 1.096 0 1.473.12a3.6 3.6 0 0 1 .619.265l.01.006l.003.002z");
}

.bfsgwjb9t {
  d: path("M10.826 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.bj832jb3d {
  stop-color: var(--svg-color--9a7d65, #9A7D65);
  stop-opacity: 0;
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.c0n_qbjkq {
  d: path("M15.331 6.78c-1.256-.277-2.383.976-2.513 1.44c1.166 3.93 4.116 3.715 7.029 3.392c1.744-.194 1.933.6 2.081.985c0-4.36-3.707-5.18-6.565-5.81z");
}

.c2k9t5bpp {
  stop-color: var(--svg-color--c9a083, #C9A083);
}

.c74g9abcg {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpr38db_u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.85 3.48c.46-.173 1.848-.439 3.354-.347");
}

.cvtf9k6wz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.cxw9pac7i {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
  stop-opacity: 0;
}

.d6vd95iar {
  d: path("M10.805 17.202a1.784 1.784 0 1 0 0-3.568a1.784 1.784 0 0 0 0 3.568");
}

.d9x2ylwjm {
  stop-color: var(--svg-color--b99477, #B99477);
}

.ddweocbxr {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.266 14.787c.295-.518.742-.927 1.705-.927c.421 0 .828.117 1.19.41c.297.24.257.548.027.664l-.617.352c-.723-.234-1.522-.266-2.305-.5");
}

.dg25vhy-y {
  stop-color: var(--svg-color--584b8c, #584B8C);
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.dk1glybfm {
  stop-color: var(--svg-color--a48369, #A48369);
  stop-opacity: 0;
}

.dn15o-0do {
  stop-color: var(--svg-color--584b8c, #584B8C);
  stop-opacity: 0;
}

.doo06bbod {
  stop-color: var(--svg-color--9179cd, #9179CD);
  stop-opacity: 0;
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dvyrp5bps {
  stop-color: var(--svg-color--916855, #916855);
}

.dz3ns1n_g {
  stop-color: var(--svg-color--c39d8a, #C39D8A);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4s700vze {
  stop-color: var(--svg-color--764b4b, #764B4B);
}

.e9zt1qbrs {
  stop-color: var(--svg-color--9e6d71, #9E6D71);
  stop-opacity: 0;
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.espu6yqld {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.349 13.926c-.724 0-1.336.499-1.502 1.173a.304.304 0 0 0 .297.378h2.473a.255.255 0 0 0 .252-.301a1.554 1.554 0 0 0-1.52-1.25");
}

.f63cqv7mt {
  stop-color: var(--svg-color--82594c, #82594C);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fjos8cb-d {
  stop-color: var(--svg-color--764b4b, #764B4B);
  stop-opacity: 0;
}

.fqnyw0bnc {
  stop-color: var(--svg-color--8378b6, #8378B6);
}

.ft5dv1b6b {
  fill: none;
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g15wokvee {
  stop-color: var(--svg-color--925a61, #925A61);
  stop-opacity: 0;
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g2x2jxbfq {
  stop-color: var(--svg-color--907664, #907664);
  stop-opacity: 0;
}

.g5w7r7bth {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.331 6.78c-1.256-.277-2.383.976-2.513 1.44c1.166 3.93 4.116 3.715 7.029 3.392c1.744-.194 1.933.6 2.081.985c0-4.36-3.707-5.18-6.565-5.81z");
}

.gsuhbzbgv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.717 4.465c.46-.173 1.847-.438 3.353-.346");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h-8-hirxp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.836 3.08c.433-.236 2.032-.622 3.538-.722");
}

.h-qwb4b2p {
  stop-color: var(--svg-color--947061, #947061);
  stop-opacity: 0;
}

.h4ehjy6dd {
  stop-color: var(--svg-color--9a7d65, #9A7D65);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hockzyb4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.hvp7s_s8m {
  stop-color: var(--svg-color--bb8d80, #BB8D80);
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i-v4lm-fq {
  stop-color: var(--svg-color--99755e, #99755E);
  stop-opacity: 0;
}

.i01-9l3nj {
  stop-color: var(--svg-color--9478d2, #9478D2);
}

.i4aahzyol {
  stop-color: var(--svg-color--99755e, #99755E);
}

.iae434d0r {
  cx: 13.28px;
  cy: 14.65px;
  rx: 0.432px;
  ry: 0.219px;
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jcr-_pt7q {
  stop-color: var(--svg-color--7357b2, #7357B2);
}

.jhe4hqqqz {
  stop-color: var(--svg-color--221a22, #221A22);
}

.jjmtttbid {
  stop-color: var(--svg-color--916b60, #916B60);
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jyzgzgaon {
  stop-color: var(--svg-color--9478d2, #9478D2);
  stop-opacity: 0;
}

.k1f3qcchq {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.38 8.778c.627-.664 1.814-.665 2.362-.566l.439 1.43c-.28-.043-.328 0-.538.204c-.152 1.211-1.526 1.947-3.2 2.436c-.165-1.654.12-2.64.937-3.504");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k33dgh0kx {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
  stop-opacity: 0;
}

.k84rzffkc {
  stop-color: var(--svg-color--82594c, #82594C);
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kaz2mfb2i {
  stop-color: var(--svg-color--4c4181, #4C4181);
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ksxm-h6au {
  stop-color: var(--svg-color--65509d, #65509D);
  stop-opacity: 0;
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l57p2o49o {
  stop-color: var(--svg-color--97577d, #97577D);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7tknhp1j {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.576 15.017l-.59 1.885a.598.598 0 0 0 .578.775h.872a.6.6 0 0 0 .577-.775l-.589-1.885c-.126-.417-.716-.417-.848 0");
}

.lgc2wbcpd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnlk8lb5t {
  d: path("M23.939 27.147c-1.95-1.2-3.037-3.417-3.36-4.157c-5.175 0-9.281 1.97-10.406 6.657H24.36c0-.9-.156-1.938-.421-2.5");
}

.lqqqcm7pt {
  cx: 13.28px;
  cy: 14.65px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.432px;
  ry: 0.219px;
}

.lsiu18bln {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.734 14.787c-.294-.518-.742-.927-1.705-.927c-.421 0-.828.117-1.19.41c-.297.24-.257.548-.026.664l.616.352c.723-.234 1.522-.266 2.305-.5");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m1iyf1g2x {
  fill-rule: evenodd;
  d: path("M23.967 16.98a3.6 3.6 0 0 0 .359-1.581a3.6 3.6 0 0 0-.298-1.448h.006c-.09-.2-.19-.39-.312-.569l-.002-.003a3.6 3.6 0 0 1-.584-1.964v-.01a3.66 3.66 0 0 0-3.658-3.659a.6.6 0 0 1-.505-.258A3.67 3.67 0 0 0 16 5.962a3.67 3.67 0 0 0-2.973 1.526a.63.63 0 0 1-.505.258l-.095.001a3.66 3.66 0 0 0-3.563 3.657v.011a3.6 3.6 0 0 1-.584 1.964l-.002.004a3.66 3.66 0 0 0-.245 3.598a.57.57 0 0 1 0 .505a3.6 3.6 0 0 0-.359 1.56a3.563 3.563 0 0 0 3.568 3.567h9.516a3.563 3.563 0 0 0 3.568-3.568a3.6 3.6 0 0 0-.36-1.56a.57.57 0 0 1 0-.504m-13.594-2.962h-.013l1.329 2.611c.136 3.108 1.349 0 4.31 0c2.963 0 4.254 3.459 4.391.352l1.26-3.545c-.06-1.38-1.06-1.477-1.26-1.477h-3.57c-1.41 0-2.74-.69-3.536-1.855a.292.292 0 0 0-.512.056l-.09.215a2.56 2.56 0 0 1-1.32 1.369q-.027.01-.056.023t-.057.022c-.262.136-.876.543-.899 1.595l.012.34z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mgz6y4bsd {
  stop-color: var(--svg-color--ab8570, #AB8570);
}

.mkc39zb9h {
  stop-color: var(--svg-color--a58268, #A58268);
}

.mu01z6bem {
  d: path("M21.352 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n_01qtz8z {
  d: path("M19.303 15.086a.93.93 0 0 0-.257-.513l-.288.316l.13.253z");
}

.n-vzpx_le {
  stop-color: var(--svg-color--925a61, #925A61);
}

.ndb61xwjr {
  stop-color: var(--svg-color--97577d, #97577D);
  stop-opacity: 0;
}

.ngb3gwb-q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.85 5.561c.392-.173 1.476-.503 2.759-.41");
}

.ny7dycfhy {
  stop-color: var(--svg-color--7767af, #7767AF);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.oc_nn33wh {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.omsy5rb5f {
  fill: var(--svg-color--000, #000);
  d: path("M17.855 15.216c0-.314.252-.566.567-.566a.564.564 0 0 1 .503.827h-1.003a.5.5 0 0 1-.067-.26");
}

.oqfljpscw {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M10.826 16.609a1.19 1.19 0 1 0 0-2.382a1.19 1.19 0 0 0 0 2.382");
}

.ow_pc7b8u {
  stop-color: var(--svg-color--b99477, #B99477);
  stop-opacity: 0;
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p2il30bmc {
  stop-color: var(--svg-color--694eab, #694EAB);
}

.p49nfmexu {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.592-.465.81-.46l.135-.196c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.p96ugv3bq {
  stop-color: var(--svg-color--6d5ea5, #6D5EA5);
}

.pcu2ods2z {
  stop-color: var(--svg-color--694eab, #694EAB);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl07djbzg {
  stop-color: var(--svg-color--554948, #554948);
  stop-opacity: 0;
}

.py_i1i4hl {
  stop-color: var(--svg-color--8477ba, #8477BA);
  stop-opacity: 0;
}

.q4yl2z--c {
  stop-color: var(--svg-color--554948, #554948);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.re3qjtb0n {
  stop-color: var(--svg-color--916855, #916855);
  stop-opacity: 0;
}

.rly45w-8s {
  d: path("M18.349 14.436c.07.094-.077.21-.245.335s-.291.213-.362.119c-.07-.095.008-.273.176-.398s.36-.15.43-.056");
}

.rn8u6nbre {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rulxhjbmx {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.651 13.926c.724 0 1.336.499 1.502 1.173a.304.304 0 0 1-.297.378h-2.473a.255.255 0 0 1-.252-.301a1.55 1.55 0 0 1 1.52-1.25");
}

.s1ezr1uia {
  d: path("M18.422 14.227a.99.99 0 0 1 .953 1.25h-1.911a.993.993 0 0 1 .958-1.25");
}

.s1r4eabtu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.794 8.164c.026.27.26 1.283.604 1.896");
}

.smymh0ctp {
  d: path("m15.576 15.017l-.59 1.885a.598.598 0 0 0 .578.775h.872a.6.6 0 0 0 .577-.775l-.589-1.885c-.126-.417-.716-.417-.848 0");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.t_fx8fd6d {
  stop-color: var(--svg-color--9179c9, #9179C9);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t0f6bgits {
  stop-color: var(--svg-color--221a22, #221A22);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tax50y56a {
  d: path("M14.482 15.1c0-.32-.26-.533-.33-.597l-.32.309l.197.4z");
}

.tcn3p6j4z {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.947 12.787c-.357-.087-1.247-.043-1.841.382");
}

.tenu6ccuh {
  stop-color: var(--svg-color--6a4046, #6A4046);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tu-obdbxy {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.233 13.447l-.005.002a.298.298 0 0 1-.306-.51h.002l.003-.003l.01-.006l.037-.02q.046-.025.128-.065a4 4 0 0 1 .455-.18c.377-.12.904-.22 1.473-.12a.297.297 0 0 1-.103.585c-.443-.078-.867 0-1.189.102a3 3 0 0 0-.505.215");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u3wjuqrnp {
  stop-color: var(--svg-color--9179c9, #9179C9);
  stop-opacity: 0;
}

.u6-x52blq {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.668 10.782l-1.58.29a.763.763 0 1 1-.139-1.512h2.595c1.535 0 2.043 1.547 2.106 2.075a3.49 3.49 0 0 0-2.982-.853");
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uclw0to3e {
  stop-color: var(--svg-color--694348, #694348);
}

.ui8aeifuz {
  stop-color: var(--svg-color--b48376, #B48376);
}

.uk2ncbbma {
  d: path("M21.352 17.202a1.784 1.784 0 1 0 0-3.568a1.784 1.784 0 0 0 0 3.568");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uln231kpo {
  d: path("M10.36 14.018h.013l-.011-.294l-.011-.34c.022-1.052.636-1.46.898-1.595l.057-.022l.057-.023a2.56 2.56 0 0 0 1.318-1.369l.091-.215a.292.292 0 0 1 .512-.056a4.28 4.28 0 0 0 3.536 1.855h3.57c.2 0 1.2.097 1.26 1.477l-.132 3.407c-.137 3.107-2.563 5.194-5.525 5.194s-5.389-2.087-5.525-5.194z");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uveyjtyye {
  d: path("M13.579 14.227a.99.99 0 0 0-.954 1.25h1.912q.034-.126.035-.26a.996.996 0 0 0-.993-.99");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v6fmdibat {
  stop-color: var(--svg-color--312654, #312654);
  stop-opacity: 0;
}

.veix-z38b {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.155 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vhj3khb_o {
  fill: var(--svg-color--000, #000);
  d: path("M14.145 15.216a.564.564 0 0 0-.567-.566a.564.564 0 0 0-.503.827h1.003a.56.56 0 0 0 .067-.26");
}

.vtkyaex6k {
  stop-color: var(--svg-color--7357b2, #7357B2);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w58diel4g {
  stop-color: var(--svg-color--312654, #312654);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wjf3cr6ec {
  stop-color: var(--svg-color--c39d8a, #C39D8A);
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wyik6iche {
  stop-color: var(--svg-color--907664, #907664);
}

.x733f4b8w {
  stop-color: var(--svg-color--9179cd, #9179CD);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xeu1i8_2e {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.447 18.22c.449.239.984.376 1.553.376a3.3 3.3 0 0 0 1.553-.376a.22.22 0 0 1 .267.044a.215.215 0 0 1 .023.27m-3.396-.314l3.354.287m-3.354-.287a.22.22 0 0 0-.268.047a.21.21 0 0 0-.022.268m.29-.315l-.248.287m3.644.027l-.042-.027m.042.027l-.042-.027m.042.027a2.192 2.192 0 0 1-3.686 0m3.644-.027a2.142 2.142 0 0 1-3.602 0m-.042.027v.001l.042-.028m-.042.027l.042-.027");
}

.xg-84-b0v {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.495-.371-.713-.366l-.233-.29c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.xhpdgtb4r {
  stop-color: var(--svg-color--5e4998, #5E4998);
}

.xok7o2bsm {
  stop-color: var(--svg-color--b48376, #B48376);
  stop-opacity: 0;
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y1r1v2b6d {
  stop-color: var(--svg-color--97735c, #97735C);
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y941_ef0l {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.15 12.787c.358-.087 1.247-.043 1.842.382");
}

.ycwa9eb_e {
  d: path("M10.38 8.778c.627-.664 1.814-.665 2.362-.566l.439 1.43c-.28-.043-.328 0-.538.204c-.152 1.211-1.526 1.947-3.2 2.436c-.165-1.654.12-2.64.937-3.504");
}

.ygsync4_o {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.155-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yk5l_u5eu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.ykc0ffbbx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.349 14.436c.07.094-.077.21-.245.335s-.291.213-.362.119c-.07-.095.008-.273.176-.398s.36-.15.43-.056");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yu6zwbb_v {
  stop-color: var(--svg-color--65509d, #65509D);
}

.yysatcquz {
  stop-color: var(--svg-color--3d2f68, #3D2F68);
}

.yzi21fb4g {
  d: path("M6.367 5.28c.269-.07.742.028.945.085L10.5 7.53c.352.415.19.967.055 1.18L8.48 12.221a4.5 4.5 0 0 0-.11 4.382l2.96 5.634a.37.37 0 0 0 .492.152c.115-.057.365-.207.653-.378c.419-.25.916-.547 1.194-.677v.93a2.307 2.307 0 1 0 4.614 0v-.888c.368.187.864.457 1.264.674c.289.158.527.287.63.338a.37.37 0 0 0 .493-.151l2.96-5.634a4.5 4.5 0 0 0-.11-4.382l-2.075-3.512c-.135-.213-.297-.765.055-1.18l3.188-2.164c.203-.057.676-.154.945-.086c.336.086.594.329.812.688c.175.287 1.47 2.48 2.094 3.539c.563.823 1.625 3.088 1.375 5.563c-.1 1.662-.781 3.338-1.11 3.968l-4.132 7.855c-.173.33-.187.719-.08 1.076c.158.529.322 1.28.322 2.022H7.086c0-.743.164-1.493.322-2.022a1.43 1.43 0 0 0-.08-1.076l-4.133-7.855c-.328-.63-1.01-2.306-1.11-3.968c-.25-2.476.813-4.74 1.376-5.563a958 958 0 0 1 2.094-3.54c.218-.358.476-.6.812-.687");
}

.z6rkwybog {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.565 15.17l-.758 1.886a.598.598 0 0 0 .577.775h.872a.6.6 0 0 0 .577-.775l-.589-1.885c-.126-.418-.547-.418-.68 0");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zigbbibav {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
  stop-opacity: 0;
}

.zpfboqufv {
  stop-color: var(--svg-color--ab8570, #AB8570);
  stop-opacity: 0;
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.zxa4g21za {
  stop-color: var(--svg-color--8477ba, #8477BA);
}

</style>
