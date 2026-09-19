<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sye23oqlo"/><path fill="url(#i5UuiOd)" class="jy6ok641d"/><path fill="url(#igZMRhX)" class="jy6ok641d"/><path fill="url(#irPMG0c)" class="jttq_8bha"/><path fill="url(#ixjKgZb)" class="jttq_8bha"/><path fill="url(#iZ7JxWc)" class="jttq_8bha"/><path fill="url(#iAqeHDb)" class="jttq_8bha"/><path fill="url(#iJFmQzc)" class="jttq_8bha"/><path fill="url(#iV3ksHe)" class="jttq_8bha"/><g filter="url(#i6veshe)"><path class="y2rfdl13o"/></g><path fill="url(#iS1SCfd)" class="hbxs-snha"/><path fill="url(#iO5FzMy)" class="hbxs-snha"/><path fill="url(#iJ3sIbd)" class="hbxs-snha"/><path fill="url(#iIVhYDe)" class="zir5d7mnb"/><path fill="url(#iFPNdge)" class="zir5d7mnb"/><path fill="url(#ivphHGw)" class="e31pxhlym"/><path fill="url(#i9rxcdd)" class="e31pxhlym"/><g filter="url(#igejpqc)"><path stroke="url(#irvBtxb)" class="nw3vh8b1q"/></g><path fill="url(#i4yeglb)" class="pidc21bno"/><path fill="url(#itOmlYd)" class="pidc21bno"/><path fill="url(#i0d6r3Q)" class="pidc21bno"/><path fill="url(#ifPgpzb)" class="pidc21bno"/><path fill="url(#iMgSQ9d)" class="pidc21bno"/><path fill="url(#irQ9rGb)" class="g6nyp5cod"/><path fill="url(#igTogjb)" class="g6nyp5cod"/><path fill="url(#ipO2wWc)" class="g6nyp5cod"/><path fill="url(#ibcIIhc)" class="zc44g6i5t"/><path fill="url(#ifi71he)" class="zc44g6i5t"/><g filter="url(#iDxDaQd)"><path fill="url(#ivZIhKb)" class="e-8wx7igv"/><path fill="url(#ivZIhKb)" class="mk-ebilcn"/><path fill="url(#ivZIhKb)" class="f8tdzdb_b"/></g><g filter="url(#iqAkrid)"><path class="e3pxyc64d"/></g><g filter="url(#iNNLeic)"><path class="yk5nmbcjo"/></g><g filter="url(#iuJgcDb)"><path class="xjlkc_b_v"/></g><path fill="url(#iTOiCWd)" class="wdy1mcy6m"/><path fill="url(#i3fvqbc)" class="sbdpr0ykf"/><path fill="url(#iIXIg2t)" class="sbdpr0ykf"/><path fill="url(#i3fvqbc)" class="sbdpr0ykf"/><path fill="url(#iIXIg2t)" class="sbdpr0ykf"/><g filter="url(#iEhJPeO)"><path fill="url(#i5I5yCd)" class="f0lstbbgn"/></g><path fill="url(#iQTh8Kb)" class="f0lstbbgn"/><path fill="url(#ihS8JIc)" class="f0lstbbgn"/><path fill="url(#i7zjMPf)" class="f0lstbbgn"/><path fill="url(#ipiYjwc)" class="f0lstbbgn"/><path fill="url(#i68nMub)" class="f0lstbbgn"/><path fill="url(#igShTkd)" class="f0lstbbgn"/><path fill="url(#i0hINqI)" class="f0lstbbgn"/><path fill="url(#izdRkxe)" class="f0lstbbgn"/><path fill="url(#ieyTQ2c)" class="f0lstbbgn"/><g filter="url(#ilAqcbe)"><path class="g_9blquea"/></g><g filter="url(#i4S00Xu)"><path fill="url(#iqq0rhd)" class="oubvucbhx"/><path fill="url(#izXXJrJ)" class="oubvucbhx"/><path fill="url(#ifptCad)" class="oubvucbhx"/><path fill="url(#igJwgQd)" class="oubvucbhx"/></g><path fill="url(#ibkIJtb)" class="oubvucbhx"/><path fill="url(#ipIjNSc)" class="oubvucbhx"/><g filter="url(#iaLMuLe)"><path stroke="url(#iTq5sbe)" class="rn39q9btb"/></g><path fill="url(#iScuedb)" class="sk4mebctt"/><g filter="url(#itwzcQd)"><path fill="url(#ib0f4Ug)" class="v5mp29dzg"/><path fill="url(#itduync)" class="v5mp29dzg"/><path fill="url(#iKI5Xzi)" class="v5mp29dzg"/><path fill="url(#iPDO6Xd)" class="v5mp29dzg"/><path fill="url(#ihAVvwb)" class="v5mp29dzg"/></g><g filter="url(#ivs46dF)"><path class="nwyg8xb_f"/></g><g filter="url(#igal7yd)"><path class="f18nqr03b"/></g><g filter="url(#iE5R22O)"><path fill="url(#i5oAh6Q)" class="wb-8-5qqz"/><path fill="url(#iMnC1qb)" class="wb-8-5qqz"/></g><g filter="url(#ijXf57b)"><path fill="url(#iSyPbCc)" class="axiejbq3o"/><path fill="url(#iBHPjCe)" class="axiejbq3o"/><path fill="url(#i7PpIKd)" class="axiejbq3o"/><path fill="url(#ip3Wzob)" class="axiejbq3o"/><path fill="url(#iXI0RKb)" class="axiejbq3o"/><path fill="url(#iqO8Q2c)" class="axiejbq3o"/></g><path class="kc26x1btz"/><path fill="url(#iP0Qm2d)" class="uupukgc4w"/><path class="g88bp79ft"/><g filter="url(#ijAtsme)"><path class="ys56nu67p"/><path fill="url(#isUrSOd)" class="s9dmi05kq"/></g><g filter="url(#iKqN1Jt)"><path fill="url(#irlisee)" class="q0nockmmu"/></g><path class="djmlklb0p"/><path fill="url(#i0LNOGd)" class="w-ih83bgh"/><path class="j48-ipb0x"/><g filter="url(#iDAwbYb)"><path fill="url(#i2dvtEp)" class="n517dsp4k"/></g><g filter="url(#iWzDEmc)"><ellipse transform="rotate(-27.914 13.778 9.847)" class="jxms23bca"/><ellipse fill="url(#iOI2Ynb)" transform="rotate(-27.914 13.778 9.847)" class="sq_qohdoy"/></g><path fill="url(#iRvi0pc)" class="vle_hobve"/><path fill="url(#it5zaOe)" class="vle_hobve"/><path fill="url(#ilcyQ6Y)" class="vle_hobve"/><path fill="url(#ixPAE0b)" class="ts_9p2bjr"/><path fill="url(#i99I5Nb)" class="ts_9p2bjr"/><g filter="url(#ieKnqge)"><path class="y20--9x0q"/></g><g filter="url(#iaqbgSd)"><path class="brqgc1ept"/></g><g filter="url(#iJnzWId)"><path class="rnj32xbvy"/></g><g filter="url(#inTef6c)"><path class="gknziqb0z"/></g><g filter="url(#iVCrXEb)"><path fill="url(#i6SoBrd)" class="cdfkwik0l"/><path fill="url(#iUp3eUP)" class="cdfkwik0l"/></g><path fill="url(#il3gxcd)" class="arhh_kb4p"/><path fill="url(#iq90Ylz)" class="arhh_kb4p"/><path fill="url(#iV6docb)" class="arhh_kb4p"/><defs><radialGradient id="i5UuiOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.592 23.146)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="igZMRhX" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.998 21.49)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="irPMG0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 15.8584 0 16.298 21.38)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="x3t2hmtbe"/><stop offset="1" class="x4e9_o_2d"/></radialGradient><radialGradient id="ixjKgZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.29 16.927)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iZ7JxWc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.873 15.583)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iAqeHDb" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.623 15.348)" gradientUnits="userSpaceOnUse"><stop offset=".939" class="xuw5xge2n"/><stop offset=".971" class="pwa-xfb8m"/></radialGradient><radialGradient id="iJFmQzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.29 23.645)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iV3ksHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.40625 -5.25876 0 16.29 16.094)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="i8onqub3d"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iS1SCfd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.594 18.25)" gradientUnits="userSpaceOnUse"><stop class="dn_8aox9x"/><stop offset="1" class="ws5zlibzm"/></radialGradient><radialGradient id="iO5FzMy" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.276 17.016)" gradientUnits="userSpaceOnUse"><stop class="etclelb-u"/><stop offset="1" class="syayv9bph"/></radialGradient><radialGradient id="iJ3sIbd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.276 14.575)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="f8avqachq"/><stop offset="1" class="k-u3pqb_i"/></radialGradient><radialGradient id="iFPNdge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.865 11.699)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="ivphHGw" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.123 12.07)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="i9rxcdd" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.785 12.462)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="i0d6r3Q" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.256 8.567)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ifPgpzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.623 16.927)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="yl8yg_b1a"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iMgSQ9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.623 13.138)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="irQ9rGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.295 30.026)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="igTogjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.06 30.026)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="ibcIIhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.402 30.026)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="ifi71he" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.351 23.188)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iTOiCWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.44374 2.89066 -3.43388 -.52713 21.88 11.678)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i3fvqbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.30445 2.74622 -1.24828 .59293 10.609 11.967)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iIXIg2t" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 1.2223 -1.07221 .16106 11.43 11.758)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="i5I5yCd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.35339 0 0 -9.4701 19.165 10.883)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="ihS8JIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61099 13.01246 -10.77593 -.50597 16.95 4.868)" gradientUnits="userSpaceOnUse"><stop offset=".647" class="dqi7sbofo"/><stop offset=".975" class="xk7fdacwa"/></radialGradient><radialGradient id="i7zjMPf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37311 1.69922 0 18.796 9.736)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="ipiYjwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.05946 -1.1299 1.22959 -.0647 13.998 9.596)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i68nMub" cx="0" cy="0" r="1" gradientTransform="matrix(1.2358 0 0 6.28127 11.292 11.277)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="igShTkd" cx="0" cy="0" r="1" gradientTransform="matrix(2.67756 -3.74171 .8475 .60647 10.296 7.81)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="i0hINqI" cx="0" cy="0" r="1" gradientTransform="matrix(-2.47156 -10.48894 11.55388 -2.7225 16.132 15.053)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="izdRkxe" cx="0" cy="0" r="1" gradientTransform="matrix(2.094 .73805 -.44275 1.25617 18.295 5.373)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="ieyTQ2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.37071 -6.06104 0 15.66 4.564)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="ygvurrbde"/><stop offset="1" class="m_vpoocjx"/></radialGradient><radialGradient id="ipIjNSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88373 1.87514 -1.19184 -1.1973 17.334 10.805)" gradientUnits="userSpaceOnUse"><stop offset=".94" class="a860wwbce"/><stop offset="1" class="dm6t8mbjz"/></radialGradient><radialGradient id="iTq5sbe" cx="0" cy="0" r="1" gradientTransform="matrix(.3555 -.63432 1.8459 1.03451 15.136 14.252)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iScuedb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73804 2.96934 0 16.29 14.508)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="itduync" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.71989 6.59091 0 10.935 9.263)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iKI5Xzi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.71989 6.59091 0 21.267 9.263)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iPDO6Xd" cx="0" cy="0" r="1" gradientTransform="rotate(-159.121 10.509 -.47)scale(3.5638 1.89796)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ihAVvwb" cx="0" cy="0" r="1" gradientTransform="matrix(.92685 1.51042 -3.49741 2.14614 15.363 1.206)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i5oAh6Q" cx="0" cy="0" r="1" gradientTransform="matrix(-3.89834 1.40656 -.39148 -1.085 16.55 2.683)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="iMnC1qb" cx="0" cy="0" r="1" gradientTransform="matrix(3.29548 -5.21778 5.78076 3.65106 10.73 7.557)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iSyPbCc" cx="0" cy="0" r="1" gradientTransform="matrix(3.4671 .82006 -.45863 1.93904 19.997 3.87)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iBHPjCe" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 13.244 -1.91)scale(4.38464 2.44528)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="i7PpIKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33876 -2.25518 1.61529 -.9589 20.907 8.279)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="ip3Wzob" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91366 1.17885 -1.27438 -5.31185 21.199 3.751)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iXI0RKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.12015 .39295 -1.7965 -.54931 19.826 3.623)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="iqO8Q2c" cx="0" cy="0" r="1" gradientTransform="rotate(117.979 9.075 7.348)scale(4.35356 11.2266)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iP0Qm2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8308 -1.32149 0 18.524 9.945)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="isUrSOd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.602 .537)scale(.38737 .53332)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0LNOGd" cx="0" cy="0" r="1" gradientTransform="rotate(90 2.055 12)scale(.83085 1.32154)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iOI2Ynb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00792 -.50595 .60818 -.00952 13.763 10.17)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="it5zaOe" cx="0" cy="0" r="1" gradientTransform="matrix(.64364 2.29714 -2.19165 .61409 21.019 9.96)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="ilcyQ6Y" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 21.032 -15.766)scale(1.3698 1.14817)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="i99I5Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71524 -.25084 .2466 -1.68623 11.257 10.618)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><radialGradient id="i6SoBrd" cx="0" cy="0" r="1" gradientTransform="rotate(-100.732 11.912 -4.856)scale(3.6749 8.45124)" gradientUnits="userSpaceOnUse"><stop class="c3tjvjbdr"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iUp3eUP" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99817 -7.31619 0 16.238 2.897)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iq90Ylz" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.03 2.427)" gradientUnits="userSpaceOnUse"><stop class="h02irqbsf"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="iV6docb" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.06 3.052)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="i6veshe" width="5.32" height="9.565" x="13.616" y="10.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".2"/></filter><filter id="igejpqc" width=".65" height="8.268" x="24.401" y="3.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".125"/></filter><filter id="iDxDaQd" width="8.964" height="6.734" x="11.808" y="23.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".075"/></filter><filter id="iqAkrid" width="5.842" height="3.536" x="16.952" y="3.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".5"/></filter><filter id="iNNLeic" width="5.842" height="3.536" x="16.952" y="3.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".5"/></filter><filter id="iuJgcDb" width="5.96" height="3.583" x="17.098" y="3.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".5"/></filter><filter id="iEhJPeO" width="11.216" height="12.838" x="11.105" y="4.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1591"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1591" result="effect2_innerShadow_4002_1591"/></filter><filter id="ilAqcbe" width="3.796" height="4.892" x="14.117" y="9.118" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".5"/></filter><filter id="i4S00Xu" width="2.122" height="3.17" x="15.229" y="9.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".05"/></filter><filter id="iaLMuLe" width="3.796" height="1.598" x="14.392" y="13.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".05"/></filter><filter id="itwzcQd" width="13.182" height="8.267" x="9.699" y="1.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1591"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1591" result="effect2_innerShadow_4002_1591"/></filter><filter id="ivs46dF" width="2.393" height="1.214" x="17.917" y="7.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1591"/></filter><filter id="igal7yd" width="2.393" height="1.199" x="12.535" y="7.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1591"/></filter><filter id="iE5R22O" width="7.23" height="6.624" x="9.819" y="2.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".25"/></filter><filter id="ijXf57b" width="7.009" height="6.368" x="15.877" y="2.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".25"/></filter><filter id="ijAtsme" width=".801" height=".708" x="17.775" y="9.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".05"/></filter><filter id="iKqN1Jt" width=".903" height=".926" x="18.637" y="9.576" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".1"/></filter><filter id="iDAwbYb" width="1" height="1.056" x="14.088" y="9.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".1"/></filter><filter id="iWzDEmc" width=".93" height=".717" x="13.313" y="9.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".05"/></filter><filter id="ieKnqge" width="1.349" height="2.424" x="10.118" y="9.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".125"/></filter><filter id="iaqbgSd" width="1.469" height="2.449" x="21.121" y="9.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".125"/></filter><filter id="iJnzWId" width="2.445" height="1.17" x="12.461" y="7.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".125"/></filter><filter id="inTef6c" width="2.445" height="1.17" x="17.867" y="7.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1591" stdDeviation=".125"/></filter><filter id="iVCrXEb" width="12.586" height="3.001" x="9.977" y="3.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1591"/></filter><linearGradient id="iIVhYDe" x1="23.98" x2="25.166" y1="8.973" y2="8.973" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="irvBtxb" x1="25.226" x2="25.226" y1="3.74" y2="11.507" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="i4yeglb" x1="25.774" x2="23.455" y1="14.837" y2="14.837" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="itOmlYd" x1="23.406" x2="24.469" y1="14.634" y2="14.759" gradientUnits="userSpaceOnUse"><stop class="nnh5vk6mb"/><stop offset="1" class="boxqtwbke"/></linearGradient><linearGradient id="ipO2wWc" x1="9.205" x2="8.779" y1="28.095" y2="28.095" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ivZIhKb" x1="16.29" x2="16.29" y1="29.895" y2="23.462" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="iQTh8Kb" x1="21.571" x2="17.114" y1="12.609" y2="12.609" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iqq0rhd" x1="16.29" x2="17.165" y1="11.732" y2="11.732" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="izXXJrJ" x1="15.191" x2="16.291" y1="11.573" y2="11.633" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ifptCad" x1="16.29" x2="16.29" y1="12.14" y2="13.013" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="igJwgQd" x1="16.29" x2="16.29" y1="9.839" y2="10.268" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="ibkIJtb" x1="16.424" x2="16.424" y1="12.831" y2="12.771" gradientUnits="userSpaceOnUse"><stop class="dm6t8mbjz"/><stop offset="1" class="a860wwbce"/></linearGradient><linearGradient id="ib0f4Ug" x1="21.782" x2="11.415" y1="5.085" y2="5.085" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="irlisee" x1="19.321" x2="19" y1="10" y2="10.198" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2dvtEp" x1="14.817" x2="14.496" y1="10" y2="10.198" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRvi0pc" x1="22.881" x2="21.645" y1="10.028" y2="12.256" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="ixPAE0b" x1="10.3" x2="11.793" y1="10.749" y2="10.618" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient><linearGradient id="il3gxcd" x1="18.06" x2="16.779" y1="3.989" y2="-.386" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:student-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.a860wwbce {
  stop-color: var(--svg-color--c27b78, #C27B78);
  stop-opacity: 0;
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.arhh_kb4p {
  d: path("M24.233 3.636H8.263c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.axiejbq3o {
  d: path("m21.628 8.586l-.03-.646c-.01-.782-.657-1.427-1.439-1.46h-1.434a2.48 2.48 0 0 1-2.175-1.29s-.067-.155-.133-.418c-.246-.972.68-1.713 1.665-1.525c1.006.192 2.161.53 3.012 1.085c1.787 1.165 1.474 3.265.534 4.254");
}

.boxqtwbke {
  stop-color: var(--svg-color--fbb229, #FBB229);
  stop-opacity: 0;
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.brqgc1ept {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M21.371 11.59q.06-.975.113-1.95a.979.979 0 0 1-.113 1.95");
}

.c3tjvjbdr {
  stop-color: var(--svg-color--534d5a, #534D5A);
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.cdfkwik0l {
  d: path("m9.977 5.259l1.21-1.973l10.258-.11l1.117 2.02c-4.664 1.61-10.496.797-12.585.063");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.djmlklb0p {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.842 9.178a1.43 1.43 0 0 0-1.388 1.084a.28.28 0 0 0 .274.35h2.285a.236.236 0 0 0 .233-.279a1.435 1.435 0 0 0-1.404-1.155");
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dm6t8mbjz {
  stop-color: var(--svg-color--c27b78, #C27B78);
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dn_8aox9x {
  stop-color: var(--svg-color--bd8a7b, #BD8A7B);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqi7sbofo {
  stop-color: var(--svg-color--c9937f, #C9937F);
  stop-opacity: 0;
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e-8wx7igv {
  d: path("M11.958 23.802c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.e31pxhlym {
  d: path("M24.223 11.675a.837.837 0 1 0 .8 0z");
}

.e3pxyc64d {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.568 5.152h-2.123a.492.492 0 1 1 .078-.981c.551.088 1.283.21 1.773.331c1.107.275 1.413.814 1.498 1.199a1.54 1.54 0 0 0-1.226-.55");
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.etclelb-u {
  stop-color: var(--svg-color--a76b71, #A76B71);
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f0lstbbgn {
  d: path("M11.35 13.715a4.01 4.01 0 0 0 3.978 3.488h1.932a4.01 4.01 0 0 0 3.98-3.488c.12-1.93.241-3.85.331-5.778A1.484 1.484 0 0 0 20.16 6.47h-1.434a2.48 2.48 0 0 1-2.265-1.477a.68.68 0 0 0-.63-.429h-1.303c-1.89 0-3.422 1.55-3.422 3.46c0 1.906.12 3.78.244 5.69");
}

.f18nqr03b {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M12.797 7.72a2.84 2.84 0 0 1 1.78-.368a.284.284 0 1 1-.068.564a2.27 2.27 0 0 0-1.42.292a1 1 0 0 0-.094.061l-.003.002a.284.284 0 0 1-.347-.449z");
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f8avqachq {
  stop-color: var(--svg-color--a57050, #A57050);
  stop-opacity: 0;
}

.f8tdzdb_b {
  d: path("M19.93 23.802c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.691z");
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g_9blquea {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.849 10.54l-.709 1.695c-.103.387.146.774.499.774h.752c.353 0 .602-.393.498-.774l-.508-1.883c-.11-.417-.418-.23-.532.187");
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.g6nyp5cod {
  d: path("M9.06 30.026V18.24a10.97 10.97 0 0 0-3.765 8.286v3.5z");
}

.g88bp79ft {
  fill: var(--svg-color--000, #000);
  d: path("M18.003 10.37c0-.29.233-.523.524-.523a.52.52 0 0 1 .465.765h-.927a.5.5 0 0 1-.062-.241");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gknziqb0z {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.937 7.96c-.264-.19-.92-.521-1.695-.39");
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h02irqbsf {
  stop-color: var(--svg-color--6a6273, #6A6273);
}

.hbxs-snha {
  d: path("M15.996 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.389 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i8onqub3d {
  stop-color: var(--svg-color--170919, #170919);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.j48-ipb0x {
  fill: var(--svg-color--000, #000);
  d: path("M14.577 10.37a.52.52 0 0 0-.523-.523a.52.52 0 0 0-.466.765h.927a.5.5 0 0 0 .062-.241");
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jttq_8bha {
  d: path("M23.311 18.125a.24.24 0 0 0-.059-.29c-1.856-1.602-4.346-2.486-6.954-2.486s-5.113.893-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.613 7.03 4.613s5.73-2.014 7.013-4.614");
}

.jxms23bca {
  cx: 13.778px;
  cy: 9.847px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.399px;
  ry: 0.202px;
}

.jy6ok641d {
  d: path("M16.295 15.526c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.k-u3pqb_i {
  stop-color: var(--svg-color--a57050, #A57050);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kc26x1btz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.739 9.178a1.43 1.43 0 0 1 1.387 1.084a.28.28 0 0 1-.274.35h-2.285a.236.236 0 0 1-.233-.279a1.43 1.43 0 0 1 1.404-1.155");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m_vpoocjx {
  stop-color: var(--svg-color--a76d60, #A76D60);
  stop-opacity: 0;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mk-ebilcn {
  d: path("M15.944 23.802c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n517dsp4k {
  d: path("M14.889 10.263c0-.295-.24-.492-.306-.552l-.295.286l.182.37z");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nnh5vk6mb {
  stop-color: var(--svg-color--bd9130, #BD9130);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nw3vh8b1q {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.726 3.74v7.767");
}

.nwyg8xb_f {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M20.113 7.832c-.18-.156-.389-.322-.704-.421c-.312-.098-.702-.125-1.242-.059a.284.284 0 1 0 .069.564c.493-.06.794-.029 1.002.036c.203.064.34.168.502.308a.284.284 0 1 0 .373-.428");
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.oubvucbhx {
  d: path("m15.899 10.152l-.545 1.882c-.11.387.156.775.533.775h.806c.377 0 .644-.394.533-.775l-.544-1.882c-.117-.417-.661-.417-.783 0");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.pidc21bno {
  d: path("m23.77 13.636l-.517 2.239a.45.45 0 0 0 .445.55h1.863a.45.45 0 0 0 .43-.556l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
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

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pwa-xfb8m {
  stop-color: var(--svg-color--655f6b, #655F6B);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q0nockmmu {
  d: path("M19.34 10.25a.86.86 0 0 0-.236-.474l-.267.292l.12.234z");
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rn39q9btb {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.906 13.447a.23.23 0 0 0-.276.047a.215.215 0 0 0-.024.275c.357.54.978.9 1.684.9c.707 0 1.328-.36 1.684-.9a.22.22 0 0 0-.024-.277a.23.23 0 0 0-.275-.046c-.4.209-.872.329-1.385.329c-.508 0-.984-.12-1.384-.328Z");
}

.rnj32xbvy {
  stroke: var(--svg-color--b17847, #B17847);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.836 8.007c.263-.189.919-.521 1.695-.39");
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.s9dmi05kq {
  d: path("M18.46 9.65c.064.087-.072.193-.226.309s-.27.197-.335.11s.008-.252.162-.367c.155-.116.333-.14.398-.052");
}

.sbdpr0ykf {
  d: path("M11.312 12.163a1.7 1.7 0 0 1-.926-.316v.954c0 .914.545 1.729 1.373 2.067a4.2 4.2 0 0 1-.354-1.208z");
}

.sk4mebctt {
  d: path("M16.29 13.85a3.1 3.1 0 0 1-1.419-.337c-.14-.071-.29.087-.202.214c.343.52.94.867 1.621.867c.68 0 1.279-.347 1.621-.867c.089-.132-.062-.285-.202-.214c-.41.214-.894.337-1.419.337");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.sq_qohdoy {
  cx: 13.778px;
  cy: 9.847px;
  rx: 0.399px;
  ry: 0.202px;
}

.syayv9bph {
  stop-color: var(--svg-color--a76b71, #A76B71);
  stop-opacity: 0;
}

.sye23oqlo {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.295 15.526c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.ts_9p2bjr {
  d: path("M11.115 8.98a1.648 1.648 0 0 0 .142 3.277a80 80 0 0 1-.142-3.277");
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uupukgc4w {
  d: path("M18.527 9.457a.914.914 0 0 1 .88 1.154h-1.765a.917.917 0 0 1 .885-1.155");
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v5mp29dzg {
  d: path("M21.261 4.08c.527.182 1 .55 1.299 1.077c.477.84.407 1.846-.11 2.587a1.6 1.6 0 0 0-.276.896v1.216a1.8 1.8 0 0 0-.683-.274l.08-1.645a1.484 1.484 0 0 0-1.412-1.467h-1.434a2.48 2.48 0 0 1-2.265-1.477a.68.68 0 0 0-.63-.429h-1.303c-1.89 0-3.422 1.55-3.422 3.46l.032 1.575c-.26.038-.532.125-.738.27v-1.23a1.6 1.6 0 0 0-.277-.895a2.45 2.45 0 0 1-.146-2.504a2.4 2.4 0 0 1 1.33-1.154a2.75 2.75 0 0 0 1.418-1.137c.423-.675 1.167-.847 2.02-.847c.331 0 .646.071.94.192c.39.17.83.17 1.222 0c.288-.12.603-.192.934-.192c.863 0 1.618.188 2.037.88c.315.522.809.901 1.384 1.099");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vle_hobve {
  d: path("M21.33 12.256q.103-1.634.19-3.268a1.648 1.648 0 0 1-.19 3.268");
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.w-ih83bgh {
  d: path("M14.054 9.457a.914.914 0 0 0-.881 1.154h1.765a1 1 0 0 0 .034-.24a.92.92 0 0 0-.918-.914");
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wb-8-5qqz {
  d: path("M16.528 5.133a3 3 0 0 1-.068-.14a.68.68 0 0 0-.63-.429h-1.303c-1.89 0-3.422 1.55-3.422 3.46v.282c-.348-.265-.786-.824-.786-1.728c0-1.098.8-1.652 1.311-2.006c.144-.1.265-.184.339-.26l.102-.107c.358-.38.996-1.056 2.11-1.352a5.6 5.6 0 0 1 1.563-.168c.472.013.806.421.806.894v1.54z");
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wdy1mcy6m {
  d: path("M21.268 12.163a1.7 1.7 0 0 0 .926-.316v.954c0 .914-.544 1.729-1.373 2.067q.263-.558.354-1.208z");
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.ws5zlibzm {
  stop-color: var(--svg-color--a56d67, #A56D67);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.x3t2hmtbe {
  stop-color: var(--svg-color--46404e, #46404E);
}

.x4e9_o_2d {
  stop-color: var(--svg-color--3a3142, #3A3142);
}

.xjlkc_b_v {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.794 5.136h-2.188a.508.508 0 1 1 .081-1.011c.568.09 1.322.216 1.827.342c1.141.283 1.456.838 1.544 1.235a1.6 1.6 0 0 0-1.264-.566");
}

.xk7fdacwa {
  stop-color: var(--svg-color--9a5f67, #9A5F67);
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xuw5xge2n {
  stop-color: var(--svg-color--655f6b, #655F6B);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y20--9x0q {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M11.132 9.657a.979.979 0 0 0 .085 1.924a80 80 0 0 1-.085-1.924");
}

.y2rfdl13o {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.996 18.896c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.389 1.78-2.586v-3.634c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.634c0 1.197.763 1.89 1.78 2.586Z");
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.ygvurrbde {
  stop-color: var(--svg-color--a76d60, #A76D60);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yk5nmbcjo {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.568 5.089h-2.123a.492.492 0 1 1 .078-.981c.551.088 1.283.21 1.773.332c1.107.274 1.413.813 1.498 1.198a1.54 1.54 0 0 0-1.226-.55");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yl8yg_b1a {
  stop-color: var(--svg-color--9b6733, #9B6733);
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.ys56nu67p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.46 9.65c.064.087-.072.193-.226.309s-.27.197-.335.11s.008-.252.162-.367c.155-.116.333-.14.398-.052");
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zc44g6i5t {
  d: path("M23.52 30.026V18.24a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.zir5d7mnb {
  d: path("M25.023 11.699V2.836h-.8v8.863z");
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

</style>
