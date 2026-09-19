<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGWxTad)" class="zc-f-9brb"/><path fill="url(#iHkfsDj)" class="zc-f-9brb"/><path fill="url(#i4RbFmb)" class="uibod9iog"/><path fill="url(#ijuXFfe)" class="uibod9iog"/><path fill="url(#iu5SRib)" class="uibod9iog"/><path fill="url(#izKyfmU)" class="uibod9iog"/><path fill="url(#iLlrIAc)" class="uibod9iog"/><g filter="url(#iC1msQe)"><path class="mpq5lo67x"/></g><path fill="url(#i2ZNCHe)" class="wc7nkpb0l"/><path fill="url(#iWSsrtb)" class="wc7nkpb0l"/><path fill="url(#iKQcC2T)" class="wc7nkpb0l"/><g filter="url(#iGsgffd)"><path fill="url(#i3cTngW)" class="ykamxebfw"/></g><g filter="url(#iNvpDGd)"><path fill="url(#iwJ0O2d)" clip-rule="evenodd" class="fds-dcb0v"/></g><g filter="url(#iwEntae)"><path stroke="url(#iy9hUke)" class="u-fg__1du"/></g><path fill="url(#imWNUcc)" class="uoxd91b1d"/><path fill="url(#imF0zSt)" class="uoxd91b1d"/><path fill="url(#iqX0bLX)" class="uoxd91b1d"/><g filter="url(#isX1dEe)"><path fill="url(#icNN4Me)" class="v-d17ibdo"/></g><g filter="url(#iXe9kEb)"><path fill="url(#ic8da3c)" class="wj0mlh2zf"/></g><path fill="url(#i1fbTxe)" class="lh_u67i7m"/><path fill="url(#i2Bsloe)" class="kj6_v_bcj"/><path fill="url(#iYFPPRc)" class="kj6_v_bcj"/><path fill="url(#iwdD9Bb)" class="kj6_v_bcj"/><path fill="url(#i3Wib9e)" transform="rotate(7.73 23.58 11.147)" class="hd8wo08tw"/><g filter="url(#iDwyEze)"><path fill="url(#iIcTEvb)" class="co4bfsb5q"/><path fill="url(#iJFmqMZ)" class="co4bfsb5q"/></g><path fill="url(#iZJw1Wd)" clip-rule="evenodd" class="l93y0_bwl"/><path fill="url(#iHi48ve)" clip-rule="evenodd" class="es3szkb0k"/><path fill="url(#iSKCTfe)" clip-rule="evenodd" class="es3szkb0k"/><path clip-rule="evenodd" class="qb45c0b-c"/><path class="qeq07qpmb"/><path class="vog6yz9od"/><g filter="url(#iaNDryc)"><path class="g8p48yskx"/><path fill="url(#iVG45Sc)" class="xqxuq-xjg"/><path fill="url(#iRgRUmZ)" class="xqxuq-xjg"/></g><path class="ytt1qgcwz"/><path fill="url(#itN78Fb)" class="yf020ibhs"/><path fill="url(#infEVie)" class="yf020ibhs"/><path fill="url(#i14bnac)" class="yf020ibhs"/><path fill="url(#iX0xKjd)" class="yf020ibhs"/><path fill="url(#i1IfPCd)" class="cy9x0xbgt"/><path class="yq13lcw9n"/><g filter="url(#igTQi6d)"><path fill="url(#iU4Vylb)" class="epv-5jcjg"/></g><circle class="ykmpn7zhk"/><path fill="url(#idxRsgc)" class="yh-w8967l"/><path fill="url(#iYkNc5b)" class="yh-w8967l"/><path fill="url(#iGcIgac)" class="yh-w8967l"/><path fill="url(#iUiHGRd)" class="yh-w8967l"/><path fill="url(#iYBzybe)" class="yh-w8967l"/><path fill="url(#iPnIHkd)" class="yh-w8967l"/><g filter="url(#ijmdNWQ)"><path class="kgzj_-blh"/><path fill="url(#ir28JBg)" class="y46-xrqts"/><path fill="url(#iflaA0K)" class="y46-xrqts"/><path fill="url(#i44CwPe)" class="y46-xrqts"/></g><g filter="url(#iLOundU)"><path class="iml2itbkj"/><path fill="url(#iYXTDTn)" class="ix10lh32j"/></g><g filter="url(#iV1hFEc)"><path class="hv340qbrc"/><path fill="url(#i9l7Dac)" class="h2nvb2ccs"/><path fill="url(#i77cdae)" class="h2nvb2ccs"/><path fill="url(#iYICODd)" class="h2nvb2ccs"/></g><g filter="url(#icXfgDE)"><path class="n-u-grbvu"/><path fill="url(#i9l7Dac)" class="h2nvb2ccs"/><path fill="url(#i77cdae)" class="h2nvb2ccs"/><path fill="url(#iYICODd)" class="h2nvb2ccs"/></g><g filter="url(#izdbRBl)"><path class="szhbybbvy"/><path fill="url(#iis9YOe)" class="d0ty2fboq"/></g><path fill="url(#it3OOxR)" clip-rule="evenodd" class="opb1hfbbp"/><path fill="url(#izJcZCc)" clip-rule="evenodd" class="opb1hfbbp"/><path fill="url(#iuRnGzc)" clip-rule="evenodd" class="opb1hfbbp"/><path class="azywd8bvq"/><path fill="url(#icT8Kdd)" class="klgba534k"/><path fill="url(#i7j20Hd)" class="klgba534k"/><path class="dxbpnp-bn"/><path fill="url(#iDrPu1c)" class="r8y7g2b2p"/><path class="xyo-n6z6q"/><path fill="url(#iHdHfft)" class="y6rkm6ymi"/><path class="iskci_y1t"/><path fill="url(#idrQHga)" class="xbvu9swce"/><circle fill="url(#iRqvuTd)" class="mqrfyebuj"/><path clip-rule="evenodd" class="hwv52_bwz"/><path fill="url(#iigb6Sb)" clip-rule="evenodd" class="hd-2_za_h"/><path fill="url(#iuNO3ve)" clip-rule="evenodd" class="hd-2_za_h"/><path fill="url(#ilyR7ld)" clip-rule="evenodd" class="hd-2_za_h"/><g filter="url(#iteXire)"><path fill="url(#i9fZT1d)" class="lxc0z-bpa"/></g><g filter="url(#iKvpT1C)"><path fill="url(#iFihXQd)" class="a8nozcttu"/></g><path class="vx0oygb1e"/><path fill="url(#idEmDvd)" class="cv1qbzc4z"/><g filter="url(#inuooWc)"><path clip-rule="evenodd" class="mj3w5pbgk"/></g><path fill="url(#isHon3F)" class="ps9gn5b-q"/><path fill="url(#i88Jlzc)" class="ps9gn5b-q"/><path fill="url(#iY9pPwc)" class="ps9gn5b-q"/><path fill="url(#il8PPBb)" class="tucuq6b1f"/><path fill="url(#iLKCLbd)" class="tucuq6b1f"/><path fill="url(#iy7uuIb)" class="tucuq6b1f"/><path class="taqga237j"/><path class="tpapubc1q"/><g filter="url(#i0NCDEd)"><path class="i44-tm-sm"/></g><defs><radialGradient id="iGWxTad" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.356 28.844)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="iu5SRib" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 -2.65615 5.18207 .60968 9.887 22)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="izKyfmU" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.04 10.792)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iLlrIAc" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.762 21.72)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="iKQcC2T" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.408 5.43)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="iwJ0O2d" cx="0" cy="0" r="1" gradientTransform="rotate(66.687 4.36 19.092)scale(6.35158 4.4947)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="badkpl7qo"/><stop offset="1" class="ub4gkwbqs"/></radialGradient><radialGradient id="imF0zSt" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.205 8.882)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="icNN4Me" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 13.012 7.72)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="i1fbTxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10714 .67871 -.5326 -.08407 22.83 8.396)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="rmde5nb5w"/><stop offset="1" class="ssteeukew"/></radialGradient><radialGradient id="iYFPPRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.403 21.922)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iwdD9Bb" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.325 19.442)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="i3Wib9e" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.889 12.216)" gradientUnits="userSpaceOnUse"><stop class="j87a-3bwo"/><stop offset="1" class="nyvttvana"/></radialGradient><radialGradient id="iIcTEvb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 23.013 9.016)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="wxvya8bby"/><stop offset="1" class="nw3tffbft"/></radialGradient><radialGradient id="iJFmqMZ" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.167 12.107)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="hkrw9zb9x"/><stop offset="1" class="y10o-cb6t"/></radialGradient><radialGradient id="iSKCTfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.86 19.813)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="iRgRUmZ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.495 22.292)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="aq34itsgr"/><stop offset="1" class="wkohq15sf"/></radialGradient><radialGradient id="itN78Fb" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.198 10.092)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="infEVie" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.78 13.413)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="iX0xKjd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.95 28.532)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="iU4Vylb" cx="0" cy="0" r="1" gradientTransform="rotate(174.089 13.277 6.193)scale(2.24975 3.24434)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="qoooiwn0b"/><stop offset="1" class="j8qj9ibbi"/></radialGradient><radialGradient id="iYkNc5b" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.01 11.872)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="u005aj31u"/><stop offset="1" class="mg4rwjbbx"/></radialGradient><radialGradient id="iGcIgac" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.7 12.016)" gradientUnits="userSpaceOnUse"><stop class="mq4z99xlk"/><stop offset="1" class="l-wqt88hf"/></radialGradient><radialGradient id="iUiHGRd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.92138 1.06381 -.61436 -1.10962 22.637 14.452)" gradientUnits="userSpaceOnUse"><stop class="ojet8cb1m"/><stop offset="1" class="sc-4z3bze"/></radialGradient><radialGradient id="iYBzybe" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.356 15.547)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="x3_nmbc0c"/><stop offset="1" class="zfzerzb4h"/></radialGradient><radialGradient id="iPnIHkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57812 .45313 -.91434 -1.16656 25.422 12.718)" gradientUnits="userSpaceOnUse"><stop class="ycpxb2wjj"/><stop offset="1" class="yp3ph2bir"/></radialGradient><radialGradient id="ir28JBg" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.544 22.063)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iflaA0K" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 20.09 19.938)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="i44CwPe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.965 19.86)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="i9l7Dac" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.45 18.125)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="iYICODd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.153 17.47)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iis9YOe" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.387 19.626)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="iuRnGzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.81 16.422)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="icT8Kdd" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.83 7.026)" gradientUnits="userSpaceOnUse"><stop class="i02ics1qx"/><stop offset="1" class="azks9xb_x"/></radialGradient><radialGradient id="i7j20Hd" cx="0" cy="0" r="1" gradientTransform="matrix(.8086 -.23047 .16066 .56368 19.565 7.818)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="jbayx8bzd"/><stop offset="1" class="dul4klr9i"/></radialGradient><radialGradient id="iRqvuTd" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.3 18.914)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="wz0_kgbfy"/><stop offset="1" class="gj5nw8evx"/></radialGradient><radialGradient id="ilyR7ld" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.801 9.922)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="i9fZT1d" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.56 10.062)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iFihXQd" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.512 8.625)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="isHon3F" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.49 7.03)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="i88Jlzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.59 19.876)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="iY9pPwc" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -2.238 19.943)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="il8PPBb" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.205 16.293)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="xcafsktgp"/><stop offset="1" class="x0t8b2bhw"/></radialGradient><radialGradient id="iy7uuIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.97442 .66902 -.77403 -1.12736 24.407 13)" gradientUnits="userSpaceOnUse"><stop class="yjh8oi0bq"/><stop offset="1" class="cshe_hl2j"/></radialGradient><linearGradient id="iHkfsDj" x1="11.287" x2="11.287" y1="30.391" y2="29.096" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="i4RbFmb" x1="5.169" x2="6.325" y1="17.969" y2="21.25" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="ijuXFfe" x1="5.669" x2="6.012" y1="17.969" y2="18.938" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="i2ZNCHe" x1="13.262" x2="11.419" y1="2.282" y2="15.407" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="iWSsrtb" x1="2.45" x2="12.981" y1="18.157" y2="14.001" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="i3cTngW" x1="14.118" x2="16.719" y1="11.108" y2="15.626" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="iy9hUke" x1="19.33" x2="21.303" y1="8.137" y2="11.082" gradientUnits="userSpaceOnUse"><stop class="kgi-7abbs"/><stop offset="1" class="y-pro3zdm"/></linearGradient><linearGradient id="imWNUcc" x1="4.356" x2="6.731" y1="5.688" y2="13.969" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="iqX0bLX" x1="5.637" x2="5.356" y1="14.579" y2="13.579" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="ic8da3c" x1="19.425" x2="20.784" y1="11.39" y2="16.05" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="i2Bsloe" x1="24.95" x2="26.356" y1="20.735" y2="20.735" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="iZJw1Wd" x1="24.724" x2="24.45" y1="18.997" y2="18.997" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="iHi48ve" x1="26.34" x2="24.324" y1="20.275" y2="19.438" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="iVG45Sc" x1="22.588" x2="21.188" y1="25.818" y2="26.453" gradientUnits="userSpaceOnUse"><stop class="hfhn00bef"/><stop offset="1" class="tj1qz4fpy"/></linearGradient><linearGradient id="i14bnac" x1="23.11" x2="23.005" y1="28.356" y2="28.274" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="i1IfPCd" x1="23.508" x2="23.755" y1="8.68" y2="8.243" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="idxRsgc" x1="24.731" x2="22.544" y1="16.25" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="n_z8kdbjp"/><stop offset="1" class="pcd65pbuz"/></linearGradient><linearGradient id="iYXTDTn" x1="14.026" x2="14.651" y1="17.292" y2="18.291" gradientUnits="userSpaceOnUse"><stop class="k6xronnnf"/><stop offset="1" class="t6iizsz3u"/></linearGradient><linearGradient id="i77cdae" x1="19.981" x2="20.95" y1="20.54" y2="17.563" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="it3OOxR" x1="22.952" x2="22.952" y1="17.125" y2="18.563" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="izJcZCc" x1="24.145" x2="24.376" y1="18.653" y2="18.208" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="iDrPu1c" x1="15.466" x2="15.605" y1="12.149" y2="11.981" gradientUnits="userSpaceOnUse"><stop offset=".002" class="g2xlp42mi"/><stop offset="1" class="u8kfeooih"/></linearGradient><linearGradient id="iHdHfft" x1="15.674" x2="15.842" y1="11.72" y2="11.518" gradientUnits="userSpaceOnUse"><stop offset=".002" class="g2xlp42mi"/><stop offset="1" class="u8kfeooih"/></linearGradient><linearGradient id="idrQHga" x1="15.94" x2="16.126" y1="11.324" y2="11.097" gradientUnits="userSpaceOnUse"><stop offset=".002" class="g2xlp42mi"/><stop offset="1" class="u8kfeooih"/></linearGradient><linearGradient id="iigb6Sb" x1="24.794" x2="24.473" y1="10.276" y2="10.032" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iuNO3ve" x1="23.34" x2="23.778" y1="10.829" y2="11.118" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="idEmDvd" x1="16.358" x2="16.548" y1="11.096" y2="10.9" gradientUnits="userSpaceOnUse"><stop offset=".002" class="g2xlp42mi"/><stop offset="1" class="u8kfeooih"/></linearGradient><linearGradient id="iLKCLbd" x1="23.059" x2="22.934" y1="15.157" y2="14.235" gradientUnits="userSpaceOnUse"><stop class="b2cvh2xce"/><stop offset="1" class="s4ygnfbfl"/></linearGradient><filter id="iC1msQe" width="8.743" height="7.346" x="1.805" y="23.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_859" result="effect2_innerShadow_4002_859"/></filter><filter id="iGsgffd" width="4.276" height="5.599" x="13.194" y="9.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_859" stdDeviation=".375"/></filter><filter id="iNvpDGd" width="6.514" height="7.799" x="17.997" y="6.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.541176 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="iwEntae" width="2.679" height="4.12" x="18.865" y="7.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_859" stdDeviation=".15"/></filter><filter id="isX1dEe" width="3.479" height="7.738" x="13.769" y="2.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="iXe9kEb" width="2.822" height="15.029" x="19.135" y="2.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="iDwyEze" width="4.68" height="4.407" x="21.841" y="7.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.301961 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.486275 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_859" result="effect2_innerShadow_4002_859"/></filter><filter id="iaNDryc" width="5.316" height="9.197" x="18.605" y="20.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.509804 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="igTQi6d" width="2.864" height="4.018" x="24.407" y="8.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.0862745 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="ijmdNWQ" width="5.527" height="3.544" x="18.813" y="18.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="iLOundU" width="9.577" height="5.489" x="9.494" y="15.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.337255 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="iV1hFEc" width="6.672" height="5.002" x="17.981" y="15.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="icXfgDE" width="6.922" height="5.002" x="17.981" y="15.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="izdbRBl" width="2.568" height="3.646" x="9.471" y="17.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="iteXire" width="4.913" height="4.647" x="23.235" y="5.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="iKvpT1C" width="1.588" height="1.361" x="24.897" y="7.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="inuooWc" width="6.514" height="4.796" x="15.458" y="10.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.380392 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_859"/></filter><filter id="i0NCDEd" width="3.862" height="3.738" x="15.977" y="10.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_859" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-climbing-medium" /></template>
<style>
.a8nozcttu {
  d: path("M24.96 7.834a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.aq34itsgr {
  stop-color: var(--svg-color--96626e, #96626E);
}

.azks9xb_x {
  stop-color: var(--svg-color--b89784, #B89784);
  stop-opacity: 0;
}

.azywd8bvq {
  fill: var(--svg-color--af8f76, #AF8F76);
  d: path("M20.333 7.32c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b2cvh2xce {
  stop-color: var(--svg-color--5a3e95, #5A3E95);
}

.badkpl7qo {
  stop-color: var(--svg-color--9b7165, #9B7165);
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.co4bfsb5q {
  d: path("M22.16 9.868c.278-.875.951-1.815 1.212-2.188l2.898 1.867l-.593 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.cshe_hl2j {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
  stop-opacity: 0;
}

.cv1qbzc4z {
  d: path("M15.614 10.361a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.cy9x0xbgt {
  d: path("m23.679 8.788l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.d0ty2fboq {
  d: path("m11.989 20.45l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.dul4klr9i {
  stop-color: var(--svg-color--905b57, #905B57);
  stop-opacity: 0;
}

.dxbpnp-bn {
  fill: var(--svg-color--a17869, #A17869);
  d: path("M14.814 11.64a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.epv-5jcjg {
  d: path("m24.496 10.991l.445-1.156l.508-.758l1.672 1.32c-.052.086-.136.373-.055.829c.102.57-.14.968-.273 1.156s-.813.883-1.758.258c-.756-.5-.675-1.308-.54-1.649");
}

.es3szkb0k {
  fill-rule: evenodd;
  d: path("M24.335 19.404a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.fds-dcb0v {
  fill-rule: evenodd;
  d: path("M23.513 14.206c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.869z");
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
}

.ft5dv1b6b {
  fill: none;
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.g2xlp42mi {
  stop-color: var(--svg-color--9e6a6d, #9E6A6D);
}

.g8p48yskx {
  fill: var(--svg-color--a67377, #A67377);
  d: path("m19.044 21.391l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.gj5nw8evx {
  stop-color: var(--svg-color--915666, #915666);
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.h2nvb2ccs {
  d: path("m20.942 16.82l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.hd-2_za_h {
  fill-rule: evenodd;
  d: path("M25.563 8.886a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32L25.21 8.92a.25.25 0 0 1 .352-.033");
}

.hd8wo08tw {
  d: path("M23.581 11.147h1.905v1.844h-1.905z");
}

.hfhn00bef {
  stop-color: var(--svg-color--c29b87, #C29B87);
}

.hkrw9zb9x {
  stop-color: var(--svg-color--734c58, #734C58);
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.hv340qbrc {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.942 16.82l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.hwv52_bwz {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.563 8.886a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32L25.21 8.92a.25.25 0 0 1 .352-.033");
}

.i02ics1qx {
  stop-color: var(--svg-color--b89784, #B89784);
}

.i44-tm-sm {
  stroke: var(--svg-color--bb957f, #BB957F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m16.627 11.482l2.562 2.437");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.iml2itbkj {
  fill: var(--svg-color--9f7767, #9F7767);
  d: path("m18.274 15.801l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.iskci_y1t {
  fill: var(--svg-color--a17869, #A17869);
  d: path("M15.041 10.592a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.ix10lh32j {
  d: path("m18.274 15.801l.797.32l-.836 2.25l-.834-.519a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.j87a-3bwo {
  stop-color: var(--svg-color--ab7970, #AB7970);
}

.j8qj9ibbi {
  stop-color: var(--svg-color--442636, #442636);
}

.jbayx8bzd {
  stop-color: var(--svg-color--804d4b, #804D4B);
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k6xronnnf {
  stop-color: var(--svg-color--a3816f, #A3816F);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kgi-7abbs {
  stop-color: var(--svg-color--a98374, #A98374);
}

.kgzj_-blh {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.313 21.104l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.kj6_v_bcj {
  d: path("m24.45 19.442l1.906.63v.73a.953.953 0 1 1-1.906 0z");
}

.klgba534k {
  d: path("M20.333 7.32c.003.395-.166.71-.25.817l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l-wqt88hf {
  stop-color: var(--svg-color--6d4e68, #6D4E68);
  stop-opacity: 0;
}

.l93y0_bwl {
  fill-rule: evenodd;
  d: path("M24.524 18.355c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.lh_u67i7m {
  d: path("M22.301 8.68c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.lxc0z-bpa {
  d: path("m26.96 10.452l-3.63-2.696a.22.22 0 0 1-.067-.288a4.8 4.8 0 0 1 .654-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.mg4rwjbbx {
  stop-color: var(--svg-color--8a6dc0, #8A6DC0);
  stop-opacity: 0;
}

.mj3w5pbgk {
  fill: var(--svg-color--a6806a, #A6806A);
  fill-rule: evenodd;
  d: path("M18.113 14.635L15.458 12.2l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mpq5lo67x {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.205 23.446v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.523c-.065-.141-.186-.451-.371-.924l-.285-.725c-.322-.816-.953-1.219-1.437-1.422z");
}

.mq4z99xlk {
  stop-color: var(--svg-color--6d4e68, #6D4E68);
}

.mqrfyebuj {
  cx: 25.297px;
  cy: 9.737px;
  r: 0.559px;
}

.mr6mdpt1g {
  stop-color: var(--svg-color--716170, #716170);
}

.msti5wbjw {
  stop-color: var(--svg-color--8c7786, #8C7786);
}

.mwbu5sbnw {
  stop-color: var(--svg-color--4a4476, #4A4476);
}

.mzz_2wq-t {
  stop-color: var(--svg-color--c2bfc5, #C2BFC5);
}

.n_3yhnb8a {
  stop-color: var(--svg-color--958e9b, #958E9B);
  stop-opacity: 0;
}

.n_z8kdbjp {
  stop-color: var(--svg-color--8663c2, #8663C2);
}

.n-u-grbvu {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.942 16.82l.195-.437l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nkzm4gb5h {
  stop-color: var(--svg-color--a297ad, #A297AD);
}

.nmynr_cvx {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nuwcoob-p {
  stop-color: var(--svg-color--a49ba8, #A49BA8);
  stop-opacity: 0;
}

.nw3tffbft {
  stop-color: var(--svg-color--9e7071, #9E7071);
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.nyvttvana {
  stop-color: var(--svg-color--935c58, #935C58);
}

.ojet8cb1m {
  stop-color: var(--svg-color--4c3384, #4C3384);
}

.opb1hfbbp {
  fill-rule: evenodd;
  d: path("M20.92 16.188a.25.25 0 0 1 .342-.092l3.629 2.09a.25.25 0 1 1-.25.433l-3.628-2.09a.25.25 0 0 1-.092-.34");
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pcd65pbuz {
  stop-color: var(--svg-color--7753a0, #7753A0);
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.ps9gn5b-q {
  d: path("M20.944 16.816c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.qb45c0b-c {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M22.526 9.586a.1.1 0 0 1 .139-.029c.085.056.25.103.52.041a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qeq07qpmb {
  fill: var(--svg-color--1b131c, #1B131C);
  d: path("M24.234 8.777a.7.7 0 0 0-.223-.45c-.009.272-.167.4-.094.515c.096.15.33.117.317-.065");
}

.qoooiwn0b {
  stop-color: var(--svg-color--5c4141, #5C4141);
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.r8y7g2b2p {
  d: path("M14.814 11.64a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.rmde5nb5w {
  stop-color: var(--svg-color--967866, #967866);
}

.s4ygnfbfl {
  stop-color: var(--svg-color--7850b4, #7850B4);
  stop-opacity: 0;
}

.sc-4z3bze {
  stop-color: var(--svg-color--634b8b, #634B8B);
  stop-opacity: 0;
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.ssteeukew {
  stop-color: var(--svg-color--996f64, #996F64);
}

.szhbybbvy {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.989 20.45l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.t6iizsz3u {
  stop-color: var(--svg-color--a3816f, #A3816F);
  stop-opacity: 0;
}

.taqga237j {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.629 10.408l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.tj1qz4fpy {
  stop-color: var(--svg-color--aa7b78, #AA7B78);
  stop-opacity: 0;
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tpapubc1q {
  fill: var(--svg-color--a7806b, #A7806B);
  d: path("m16.629 10.408l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tucuq6b1f {
  d: path("m21.369 15.43l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.tvjmrrbpc {
  stop-color: var(--svg-color--5e505b, #5E505B);
}

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.u-fg__1du {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.415 8.24c.07.492.482 1.784 1.58 3.02");
}

.u005aj31u {
  stop-color: var(--svg-color--9480c2, #9480C2);
}

.u8kfeooih {
  stop-color: var(--svg-color--9e6a6d, #9E6A6D);
  stop-opacity: 0;
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.uibod9iog {
  d: path("M9.44 17.385a.93.93 0 0 1 .457-.698l-7.692 2.651V22c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.uoxd91b1d {
  d: path("M10.07 2.446c.55 1.054 1.37 2.957 1.849 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.446z");
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.v-d17ibdo {
  d: path("M13.789 2.402c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.vog6yz9od {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.653 8.196c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.vx0oygb1e {
  fill: var(--svg-color--a17869, #A17869);
  d: path("M15.614 10.361a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wc7nkpb0l {
  d: path("M14.652 15.126L2.205 19.488V2.446H18.15c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.wj0mlh2zf {
  d: path("M19.135 2.446v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.446z");
}

.wkohq15sf {
  stop-color: var(--svg-color--9b6b73, #9B6B73);
  stop-opacity: 0;
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.wxvya8bby {
  stop-color: var(--svg-color--967465, #967465);
}

.wz0_kgbfy {
  stop-color: var(--svg-color--967371, #967371);
}

.x0t8b2bhw {
  stop-color: var(--svg-color--7b53b7, #7B53B7);
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x3_nmbc0c {
  stop-color: var(--svg-color--877d9d, #877D9D);
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xbvu9swce {
  d: path("M15.041 10.592a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.xcafsktgp {
  stop-color: var(--svg-color--8e6bb9, #8E6BB9);
}

.xqxuq-xjg {
  d: path("m19.044 21.391l.39-.406l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.127-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203a448 448 0 0 1-2.75-3.945c-.613-.9-.167-1.636.133-1.89");
}

.xyo-n6z6q {
  fill: var(--svg-color--a17869, #A17869);
  d: path("M14.89 11.107a.28.28 0 0 1 .367-.42l1.5 1.31l-.368.42z");
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y-pro3zdm {
  stop-color: var(--svg-color--a98374, #A98374);
  stop-opacity: 0;
}

.y10o-cb6t {
  stop-color: var(--svg-color--734c58, #734C58);
  stop-opacity: 0;
}

.y46-xrqts {
  d: path("m19.313 21.104l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.y6rkm6ymi {
  d: path("M14.89 11.107a.28.28 0 0 1 .367-.42l1.5 1.31l-.368.42z");
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.ycpxb2wjj {
  stop-color: var(--svg-color--412949, #412949);
}

.yf020ibhs {
  d: path("m22.889 26.595l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.yh-w8967l {
  d: path("m22.473 13.344l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.102-1.765c-.316-.172-1.025-.28-1.398-.16s-.73.663-.883 1.09");
}

.yjh8oi0bq {
  stop-color: var(--svg-color--9e83ce, #9E83CE);
}

.ykamxebfw {
  d: path("m16.719 12.7l-.06.426c-.113.802-.39 1.194-.87 1.488l-.857-1.286L13.986 12a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .292-.433l-.024-.033a.28.28 0 1 1 .455-.323l.106.146a.28.28 0 0 1 .5-.223l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.ykmpn7zhk {
  cx: 23.613px;
  cy: 8.324px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.yp3ph2bir {
  stop-color: var(--svg-color--765890, #765890);
  stop-opacity: 0;
}

.yq13lcw9n {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.521 8.684l.053-.07c.073-.12.081-.25.018-.288c-.062-.038-.173.028-.246.148l-.035.071z");
}

.ytt1qgcwz {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.889 26.595l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.zc-f-9brb {
  d: path("M2.205 30.391v-8.953l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.113 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.556l5 4.753z");
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zfzerzb4h {
  stop-color: var(--svg-color--877d9d, #877D9D);
  stop-opacity: 0;
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

</style>
