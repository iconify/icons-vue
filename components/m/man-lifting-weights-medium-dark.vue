<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZ35Bxe)" transform="rotate(-27.486 8.007 7.135)" class="uiynf4b0r"/><path fill="url(#iaZu6zc)" transform="rotate(-27.486 8.007 7.135)" class="uiynf4b0r"/><path fill="url(#iaEKXHc)" transform="rotate(-27.486 8.007 7.135)" class="uiynf4b0r"/><path fill="url(#i4GPCZd)" transform="rotate(-27.486 8.007 7.135)" class="uiynf4b0r"/><path fill="url(#imdZvZc)" transform="scale(-1 1)rotate(-27.486 2.294 53.834)" class="pnmas4b0d"/><path fill="url(#iev7Igb)" transform="scale(-1 1)rotate(-27.486 2.294 53.834)" class="pnmas4b0d"/><path fill="url(#iJSh9Rd)" transform="scale(-1 1)rotate(-27.486 2.294 53.834)" class="pnmas4b0d"/><path fill="url(#icTlMSc)" transform="scale(-1 1)rotate(-27.486 2.294 53.834)" class="pnmas4b0d"/><g filter="url(#iaGynPd)"><path fill="url(#iUCBLee)" class="mrtnubb3p"/><path fill="url(#i7W4F9T)" class="mrtnubb3p"/><path fill="url(#i32NrCd)" class="mrtnubb3p"/><path fill="url(#iCt8tXf)" class="mrtnubb3p"/></g><g filter="url(#ieByrvV)"><rect fill="url(#isbeScw)" class="f1dha-bpp"/><rect fill="url(#iYos2mA)" class="f1dha-bpp"/></g><g filter="url(#iEImYoc)"><path stroke="url(#izpOwpd)" class="lrf8ycbwa"/></g><path fill="url(#iummDrc)" class="timdh8g1l"/><path fill="url(#icwgbLH)" class="timdh8g1l"/><path fill="url(#iuRA0Bd)" class="ix5lz_wyd"/><path fill="url(#iipLawc)" class="ix5lz_wyd"/><path fill="url(#iBhtSwf)" class="h0ogc3b6u"/><path fill="url(#iXOvAkh)" class="h0ogc3b6u"/><path fill="url(#id091ub)" class="j6kgr8bmv"/><path fill="url(#iTXBJzn)" class="j6kgr8bmv"/><circle fill="url(#iGPcbiU)" class="aakz0bx-o"/><circle fill="url(#irOc30c)" class="aakz0bx-o"/><path fill="url(#ir3kxOb)" class="zen1j3nse"/><path fill="url(#iomk4dd)" class="zen1j3nse"/><path fill="url(#i2iWSWc)" class="ey9ssybcm"/><path fill="url(#iDmT38d)" class="ey9ssybcm"/><path fill="url(#isolz4b)" class="uy-b_jbkp"/><path fill="url(#iBAsgfb)" class="uy-b_jbkp"/><path fill="url(#i5RPKzb)" class="j4icr1g-b"/><path fill="url(#iF5E3Fb)" class="j4icr1g-b"/><circle fill="url(#ibvUIjc)" transform="matrix(-1 0 0 1 21.67 7.284)" class="e4y-1lbum"/><circle fill="url(#iLZeLcY)" transform="matrix(-1 0 0 1 21.67 7.284)" class="e4y-1lbum"/><g filter="url(#ikoWrSd)"><path fill="url(#iin6DJd)" class="cho6q6jli"/><path fill="url(#iQvSfyt)" class="cho6q6jli"/><path fill="url(#iMVZzQd)" class="cho6q6jli"/></g><g filter="url(#i5DZikc)"><path fill="url(#ifoFebe)" class="jo2vldbkj"/><path fill="url(#iFtvC0b)" class="jo2vldbkj"/><path fill="url(#is5317d)" class="jo2vldbkj"/></g><g filter="url(#iw2x2md)"><path fill="url(#i451Foe)" class="diz3dk14f"/><path fill="url(#isIEicd)" class="diz3dk14f"/></g><g filter="url(#igR727b)"><path fill="url(#iL50ywb)" class="f7dtqob8f"/><path fill="url(#iFdmQru)" class="f7dtqob8f"/><path fill="url(#ihlitnc)" class="f7dtqob8f"/></g><g filter="url(#i41Xnce)"><path fill="url(#ihO7u6i)" class="lgnb04bhp"/><path fill="url(#iEDLp8b)" class="lgnb04bhp"/></g><g filter="url(#iv7gdsr)"><path fill="url(#i6GZMCb)" class="slzndd6vb"/></g><g filter="url(#iLGoVvs)"><path fill="url(#iKDUHqd)" class="zka8snbuo"/><path fill="url(#i0xtMJt)" class="zka8snbuo"/></g><g filter="url(#iuEjTqb)"><path fill="url(#iZtJxve)" class="pr8-z2b3y"/></g><g filter="url(#i6ieEBc)"><path fill="url(#izi4ewe)" class="b9bnemb3z"/></g><g filter="url(#iDB2OFe)"><path fill="url(#ijsKl3c)" class="lnf674b0h"/><path fill="url(#i1szLFa)" class="lnf674b0h"/></g><g filter="url(#iw4bZJd)"><path fill="url(#i3O7n5c)" class="bj07kd04r"/></g><g filter="url(#isUDzEn)"><circle fill="url(#iVlcviX)" class="v5fxumbup"/></g><g filter="url(#iTNwFvb)"><circle fill="url(#izcEuhd)" class="z89m61ndy"/></g><g filter="url(#iLzTZMb)"><circle fill="url(#ijHxojd)" class="pk34a-btb"/><circle fill="url(#iO2pLNb)" class="pk34a-btb"/></g><g filter="url(#iREMa7c)"><circle class="vqjt84b9q"/><circle fill="url(#igp9hmc)" class="kq0zgozqx"/><circle fill="url(#iyqB7Hd)" class="kq0zgozqx"/></g><g filter="url(#iIC6Ikb)"><path fill="url(#iH3FJbc)" class="jjdz7n0hf"/><path fill="url(#iKcT13d)" class="jjdz7n0hf"/><path fill="url(#iMlaq4b)" class="jjdz7n0hf"/></g><path fill="url(#iyRFiRc)" class="mc012eb8j"/><path fill="url(#iya9Y5N)" class="mc012eb8j"/><path fill="url(#ihtMyjY)" class="mc012eb8j"/><g filter="url(#iyBcmwO)"><path fill="url(#iwXYqsc)" class="vy82ggxcw"/></g><g filter="url(#ifzjnJc)"><path class="ib3-eabyf"/><path fill="url(#ievjN8L)" class="sxtwc4v0n"/><path fill="url(#i3nWR6c)" class="sxtwc4v0n"/><path fill="url(#iQ7Mruc)" class="sxtwc4v0n"/><path fill="url(#iH7yVfe)" class="sxtwc4v0n"/></g><g filter="url(#ikoDc1d)"><path class="f883njbew"/></g><g filter="url(#ix3qmwb)"><path class="yp0derb1r"/><path fill="url(#i8RpXtd)" class="w317cxbhz"/><path fill="url(#i71nflI)" class="w317cxbhz"/><path fill="url(#iLrXpMb)" class="w317cxbhz"/><path fill="url(#i67CEbe)" class="w317cxbhz"/></g><path stroke="url(#iSfUQIn)" class="g5m2tpbua"/><path class="o3ags8bfr"/><path fill="url(#iV0UtCZ)" class="u8djmyolf"/><path class="z6dva1ujr"/><g filter="url(#iaqbrcc)"><path class="bs-boo0ln"/><path fill="url(#i0zAdXc)" class="vyy2yi9lp"/></g><g filter="url(#izdNaMd)"><path fill="url(#iRHlFRb)" class="a41x-7k6s"/></g><path class="kn4mnxbqu"/><path fill="url(#iP3EeDc)" class="qhgoq_w9f"/><path class="r981kx0se"/><g filter="url(#iwfd0Kt)"><path fill="url(#inVHfba)" class="buln1blfu"/></g><g filter="url(#i7xnmle)"><ellipse transform="rotate(-27.914 15.12 13.226)" class="wr3tf456n"/><ellipse fill="url(#iuu12Cb)" transform="rotate(-27.914 15.12 13.226)" class="x2yt-r-7b"/></g><g filter="url(#iLHE6hd)"><path class="cowze856x"/><path fill="url(#iQoDKyx)" class="l1_ky_bto"/></g><g filter="url(#i7kTjte)"><path stroke="url(#ioItjnc)" class="xzfe3gq7a"/></g><g filter="url(#igTX2ac)"><path class="yg2iljbpo"/><path fill="url(#ihPXDqc)" class="s_-l0fbyh"/></g><g filter="url(#iqlyMfc)"><path stroke="url(#iaoLC7c)" class="lftvhgbwh"/></g><g filter="url(#iiZeOld)"><path stroke="url(#iOlFnOe)" class="st5m78bwy"/></g><defs><radialGradient id="iZ35Bxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00154 4.75464 -1.08171 -.00035 10.088 11.213)" gradientUnits="userSpaceOnUse"><stop class="qc5umhbsx"/><stop offset="1" class="ps5p_xb2b"/></radialGradient><radialGradient id="iaEKXHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67067 1.2891 -1.1832 -.61557 10.312 8.053)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="tuvsor_7r"/><stop offset="1" class="s_t4keb-b"/></radialGradient><radialGradient id="i4GPCZd" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.502 6.97)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="dlijzhe6z"/><stop offset="1" class="rcswokzqh"/></radialGradient><radialGradient id="imdZvZc" cx="0" cy="0" r="1" gradientTransform="rotate(87.787 -1.122 2.973)scale(4.85666 1.64346)" gradientUnits="userSpaceOnUse"><stop class="xz64_6yvi"/><stop offset="1" class="y8dp0hbvk"/></radialGradient><radialGradient id="iJSh9Rd" cx="0" cy="0" r="1" gradientTransform="rotate(127.793 1.116 1.093)scale(1.67845 1.54056)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="suv_43jhc"/><stop offset="1" class="lqtoipbqj"/></radialGradient><radialGradient id="icTlMSc" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="ghoayzsjh"/><stop offset="1" class="iglonxb_v"/></radialGradient><radialGradient id="iUCBLee" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.647 22.23)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="iCt8tXf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 18.21 22.23)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="isbeScw" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 18.053 5.98)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="iYos2mA" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 9.233 6.558)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="iummDrc" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 4.123 3.22)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="icwgbLH" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.354 6.566)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="iuRA0Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 9.135 6.16)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="iipLawc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 9.049 6.597)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="iBhtSwf" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.162 3.267)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="iXOvAkh" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.45 6.604)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="id091ub" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.818 3.263)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ujo-xtz9c"/><stop offset="1" class="s0g9yis6b"/></radialGradient><radialGradient id="iTXBJzn" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.766 6.645)" gradientUnits="userSpaceOnUse"><stop class="jpyi06dtg"/><stop offset="1" class="d9_0_ybyb"/></radialGradient><radialGradient id="iGPcbiU" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 3.759 6.305)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="cvatkobbr"/><stop offset=".91" class="ydv5mwxxd"/></radialGradient><radialGradient id="irOc30c" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 3.688 6.437)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="op745bcjt"/><stop offset="1" class="n5tde31zi"/></radialGradient><radialGradient id="ir3kxOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.49 6.18)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="iomk4dd" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.287 10.586)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="i2iWSWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.814 6.16)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="iDmT38d" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.881 10.62)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="isolz4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.395 6.179)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="iBAsgfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.364 6.482)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="i5RPKzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 23.097 6.18)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="tox4m5q8h"/><stop offset="1" class="hg2aihb7u"/></radialGradient><radialGradient id="iF5E3Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 23.064 6.511)" gradientUnits="userSpaceOnUse"><stop class="ob61f_0qn"/><stop offset="1" class="xr8cplx4f"/></radialGradient><radialGradient id="ibvUIjc" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="bmte3bbwj"/><stop offset=".91" class="wvhi0ab5z"/></radialGradient><radialGradient id="iLZeLcY" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 .276 .232)scale(.31867 .23988)" gradientUnits="userSpaceOnUse"><stop class="kk6l23w0e"/><stop offset="1" class="sh5_80x3i"/></radialGradient><radialGradient id="iin6DJd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.584 19.042)" gradientUnits="userSpaceOnUse"><stop class="cnpza7b-j"/><stop offset="1" class="qcugcqlkb"/></radialGradient><radialGradient id="iQvSfyt" cx="0" cy="0" r="1" gradientTransform="rotate(111.28 2.902 12.683)scale(2.73303 3.08168)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="my3wtvo7r"/><stop offset="1" class="yi8xsxb7e"/></radialGradient><radialGradient id="iMVZzQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 20.097 21.54)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="xjez76bam"/><stop offset="1" class="fc_42m6ea"/></radialGradient><radialGradient id="ifoFebe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.772 6.772)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="i451Foe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.565 6.772)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iL50ywb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.346 6.772)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iFdmQru" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 3.045 7.167)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="ihO7u6i" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.71 6.772)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iEDLp8b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.46 7.167)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i0xtMJt" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.227 12.304)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iZtJxve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.678 28.276)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="i1szLFa" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.798 15.523)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="i3O7n5c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.99 28.823)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="iVlcviX" cx="0" cy="0" r="1" gradientTransform="matrix(.84282 0 0 1.47494 13.218 13.298)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iO2pLNb" cx="0" cy="0" r="1" gradientTransform="matrix(.39705 -.28911 .32998 .45318 18.767 13.17)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="igp9hmc" cx="0" cy="0" r="1" gradientTransform="matrix(.39443 -.72547 .42462 .23086 18.569 13.692)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iyqB7Hd" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -6.874 29.25)scale(.17522 .22588)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iKcT13d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62776 .77263 0 17.427 12.687)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iMlaq4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.65995 .8207 0 15.238 12.752)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="ihtMyjY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.24878 -5.76749 0 16.155 12.446)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="ievjN8L" cx="0" cy="0" r="1" gradientTransform="matrix(.38317 -1.41999 .68372 .1845 18.387 11.326)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="i3nWR6c" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -105.33 196.876)scale(1.84474 .9919)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iQ7Mruc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .80647 -1.24899 0 16.3 9.167)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iH7yVfe" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 25.614 -13.955)scale(1.83033 2.86752)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="i67CEbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .09457 -.30382 0 16.435 14.27)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iV0UtCZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38957 -.61965 0 17.346 13.271)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i0zAdXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11136 -.1435 .19757 -.15331 17.237 13.312)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iP3EeDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38959 -.61968 0 15.25 13.271)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iuu12Cb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00371 -.23724 .28518 -.00446 15.113 13.377)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQoDKyx" cx="0" cy="0" r="1" gradientTransform="rotate(-108.94 13.278 .018)scale(.29402 .86986)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="ihPXDqc" cx="0" cy="0" r="1" gradientTransform="matrix(.09543 -.2781 .82275 .28233 15.057 12.582)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><filter id="iaGynPd" width="9.5" height="4.284" x="11.444" y="21.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="ieByrvV" width="27.875" height="1.225" x="2.334" y="6.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iEImYoc" width="27.781" height=".75" x="2.295" y="6.315" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".125"/></filter><filter id="ikoWrSd" width="10.708" height="10.353" x="11.075" y="12.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.490196 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="i5DZikc" width="1.93" height="8.989" x="5.311" y="2.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iw2x2md" width="1.93" height="8.989" x="25.264" y="2.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="igR727b" width="1.93" height="5.973" x="3.381" y="3.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="i41Xnce" width="1.93" height="5.973" x="27.194" y="3.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iv7gdsr" width="3.719" height="6.065" x="9.162" y="23.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.313726 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23313" result="effect2_innerShadow_3987_23313"/></filter><filter id="iLGoVvs" width="4.477" height="4.023" x="8.787" y="19.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iuEjTqb" width="4.833" height="2.114" x="7.311" y="28.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="i6ieEBc" width="3.719" height="5.564" x="20.194" y="23.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.313726 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23313" result="effect2_innerShadow_3987_23313"/></filter><filter id="iDB2OFe" width="4.477" height="4.023" x="19.811" y="19.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iw4bZJd" width="4.833" height="2.114" x="20.431" y="28.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="isUDzEn" width="1.804" height="1.604" x="13.218" y="12.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iTNwFvb" width="1.956" height="1.956" x="13.041" y="12.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".25"/></filter><filter id="iLzTZMb" width="1.854" height="1.854" x="17.787" y="12.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iREMa7c" width="1.956" height="1.956" x="17.611" y="12.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".25"/></filter><filter id="iIC6Ikb" width="4.982" height="5.927" x="13.823" y="10.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iyBcmwO" width="4.039" height="3.473" x="15.381" y="9.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".5"/></filter><filter id="ifzjnJc" width="6.052" height="4.063" x="13.274" y="8.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="ikoDc1d" width="2.345" height="2.788" x="15.013" y="12.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".375"/></filter><filter id="ix3qmwb" width="1.101" height="1.488" x="15.727" y="13.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".05"/></filter><filter id="iaqbrcc" width=".382" height=".338" x="16.992" y="13.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".025"/></filter><filter id="izdNaMd" width=".336" height=".347" x="17.443" y="13.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".025"/></filter><filter id="iwfd0Kt" width=".382" height=".407" x="15.31" y="13.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".025"/></filter><filter id="i7xnmle" width=".442" height=".342" x="14.9" y="13.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".025"/></filter><filter id="iLHE6hd" width="1.549" height="1.147" x="16.87" y="11.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="i7kTjte" width="1.321" height=".72" x="16.836" y="11.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".075"/></filter><filter id="igTX2ac" width="1.549" height="1.147" x="14.458" y="11.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23313"/></filter><filter id="iqlyMfc" width="1.321" height=".72" x="14.471" y="11.939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".075"/></filter><filter id="iiZeOld" width=".874" height="1.48" x="13.624" y="10.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23313" stdDeviation=".125"/></filter><linearGradient id="iaZu6zc" x1="7.435" x2="8.556" y1="8.234" y2="8.38" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ord38lb5d"/><stop offset="1" class="lagcd8brb"/></linearGradient><linearGradient id="iev7Igb" x1="-.572" x2=".549" y1="1.099" y2="1.245" gradientUnits="userSpaceOnUse"><stop offset=".136" class="pdrq0-vxx"/><stop offset="1" class="tldk1ryzb"/></linearGradient><linearGradient id="i7W4F9T" x1="20.584" x2="18.053" y1="25.542" y2="25.105" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i32NrCd" x1="11.897" x2="14.709" y1="25.636" y2="24.542" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="izpOwpd" x1="2.67" x2="30.139" y1="7.69" y2="7.69" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iFtvC0b" x1="5.311" x2="6.803" y1="7.761" y2="7.761" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="is5317d" x1="5.311" x2="5.584" y1="7.632" y2="7.632" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="isIEicd" x1="25.264" x2="26.459" y1="6.772" y2="6.772" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="ihlitnc" x1="3.229" x2="3.723" y1="6.772" y2="6.772" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="i6GZMCb" x1="12.146" x2="9.724" y1="26.109" y2="26.109" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ykol_yz-a"/><stop offset="1" class="d19y5jbcp"/></linearGradient><linearGradient id="iKDUHqd" x1="12.764" x2="8.787" y1="22.058" y2="22.058" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="izi4ewe" x1="23.412" x2="21.02" y1="25.49" y2="25.49" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ykol_yz-a"/><stop offset="1" class="d19y5jbcp"/></linearGradient><linearGradient id="ijsKl3c" x1="19.811" x2="23.787" y1="22.058" y2="22.058" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="izcEuhd" x1="14.019" x2="13.712" y1="13.432" y2="13.432" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="ijHxojd" x1="19.11" x2="18.717" y1="12.774" y2="13.992" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iH3FJbc" x1="18.238" x2="14.571" y1="13.485" y2="14.032" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="iyRFiRc" x1="13.709" x2="14.612" y1="14.78" y2="14.748" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iya9Y5N" x1="18.636" x2="18.129" y1="14.377" y2="14.329" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iwXYqsc" x1="16.044" x2="19.956" y1="12.052" y2="10.651" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="i8RpXtd" x1="15.863" x2="16.313" y1="14.002" y2="14.002" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="i71nflI" x1="16.729" x2="16.236" y1="14.157" y2="14.15" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iLrXpMb" x1="16.371" x2="16.371" y1="14.513" y2="14.238" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iSfUQIn" x1="15.802" x2="16.011" y1="15.309" y2="14.979" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iRHlFRb" x1="17.72" x2="17.569" y1="13.297" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inVHfba" x1="15.608" x2="15.457" y1="13.297" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ioItjnc" x1="17.636" x2="17.26" y1="12.172" y2="11.908" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iaoLC7c" x1="14.992" x2="15.367" y1="12.172" y2="11.908" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iOlFnOe" x1="14.061" x2="14.061" y1="10.94" y2="11.976" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-lifting-weights-medium-dark" /></template>
<style>
.a41x-7k6s {
  d: path("M17.729 13.415a.4.4 0 0 0-.111-.223l-.125.137l.056.11z");
}

.aakz0bx-o {
  cx: 10.858px;
  cy: 7.284px;
  r: 0.398px;
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.b9bnemb3z {
  d: path("m22.94 28.733l.472-5.464h-3.218l.477 5.464z");
}

.bj07kd04r {
  d: path("M25.264 29.814v.376H20.63v-1.914h2.352c.383.377 1.215.73 1.836.942c.398.168.445.442.445.596");
}

.bmte3bbwj {
  stop-color: var(--svg-color--75574d, #75574D);
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.bs-boo0ln {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.316 13.133c.03.04-.033.09-.106.145c-.072.054-.126.092-.157.051c-.03-.04.004-.117.076-.172c.073-.054.157-.065.187-.024");
}

.buln1blfu {
  d: path("M15.641 13.42c0-.138-.112-.23-.143-.258l-.138.134l.085.173z");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cho6q6jli {
  d: path("m11.22 13.31l2.396-1.12l2.578 3.399l2.468-3.563l2.73 1.318a.25.25 0 0 1 .113.34l-1.194 2.304a1 1 0 0 0-.112.48l.12 5.762h-7.985v-5.788a1 1 0 0 0-.098-.433L11.1 13.645a.25.25 0 0 1 .12-.335");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnpza7b-j {
  stop-color: var(--svg-color--4baeff, #4BAEFF);
}

.cowze856x {
  fill: var(--svg-color--352827, #352827);
  d: path("M17.962 12.02h-.002l-.003-.001l-.007-.001a1 1 0 0 0-.09-.01a1.36 1.36 0 0 0-.89.286a.256.256 0 0 0 .313.406a.85.85 0 0 1 .547-.18q.023 0 .032.003h.004a.256.256 0 0 0 .096-.503");
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cvatkobbr {
  stop-color: var(--svg-color--826255, #826255);
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d19y5jbcp {
  stop-color: var(--svg-color--855958, #855958);
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d9_0_ybyb {
  stop-color: var(--svg-color--8e7570, #8E7570);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.diz3dk14f {
  d: path("M27.194 3.178a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.dlijzhe6z {
  stop-color: var(--svg-color--623c31, #623C31);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4y-1lbum {
  r: 0.398px;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ey9ssybcm {
  d: path("M24.095 5.911a.422.422 0 1 0-.843-.033v.585a.4.4 0 0 0 .798.03z");
}

.f1dha-bpp {
  width: 27.875px;
  height: 1.025px;
  x: 2.334px;
  y: 6.259px;
  rx: 0.2px;
}

.f7dtqob8f {
  d: path("M3.381 4.686a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.f883njbew {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m16.168 13.45l-.394.817c-.049.167.068.335.234.335h.354c.166 0 .284-.17.235-.335l-.24-.817c-.05-.18-.135-.18-.19 0");
}

.fc_42m6ea {
  stop-color: var(--svg-color--3a9cef, #3A9CEF);
  stop-opacity: 0;
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g5m2tpbua {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.658 14.82c.185.096.406.151.642.151c.238 0 .457-.055.642-.152a.124.124 0 0 1 .147.024a.12.12 0 0 1 .013.149m-1.444-.173l1.402.145m-1.402-.145a.12.12 0 0 0-.147.025a.116.116 0 0 0-.013.148m.16-.173l-.118.145m1.562.028l-.042-.028m.042.028l-.042-.028m.042.028a.96.96 0 0 1-.802.428a.96.96 0 0 1-.802-.428m1.562-.028a.91.91 0 0 1-.76.406a.91.91 0 0 1-.76-.406m-.042.028l.042-.028m-.042.028l.042-.028");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.ghoayzsjh {
  stop-color: var(--svg-color--754c3c, #754C3C);
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h0ogc3b6u {
  d: path("M9.864 5.91a.401.401 0 1 1 .802-.014v.575a.391.391 0 0 1-.782.013z");
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hg2aihb7u {
  stop-color: var(--svg-color--6a3f41, #6A3F41);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.ib3-eabyf {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m18.614 10.187l.206.102c.361.18.567.59.49 1.025l-.283 1.46c-.026.15-.125.252-.275.256h-.009s.026-.435.052-.691c.02-.209-.016-.272-.206-.462a.6.6 0 0 1-.18-.41v-.094a.28.28 0 0 0-.207-.256c-.309-.077-.953-.205-1.88-.205c-.928 0-1.572.128-1.881.205a.25.25 0 0 0-.206.256v.095a.5.5 0 0 1-.18.41l-.078.076c-.103.077-.154.23-.154.359c.025.282.051.691.051.691h-.023a.304.304 0 0 1-.286-.256l-.283-1.46a.98.98 0 0 1 .515-.999l.206-.102c.129-.077.258-.18.386-.282l.464-.487a.94.94 0 0 1 1.056-.153c.258.077.542.077.8 0a1.16 1.16 0 0 1 1.133.256l.386.384c.103.128.232.205.386.282");
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.iglonxb_v {
  stop-color: var(--svg-color--754c3c, #754C3C);
  stop-opacity: 0;
}

.ix5lz_wyd {
  d: path("M8.432 5.911a.422.422 0 1 1 .844-.033v.585a.4.4 0 0 1-.799.03z");
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j4icr1g-b {
  d: path("M23.38 5.872a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.016z");
}

.j6kgr8bmv {
  d: path("M9.147 5.872a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.822.016z");
}

.jjdz7n0hf {
  d: path("M13.85 13.004h.024s-.026-.41-.051-.691c0-.128.051-.282.154-.359l.078-.077a.5.5 0 0 0 .18-.41v-.41a.25.25 0 0 1 .206-.255c.31-.077.953-.205 1.88-.205c.928 0 1.572.128 1.881.205a.28.28 0 0 1 .206.256v.41a.6.6 0 0 0 .18.41c.242.168.227.261.207.46c-.026.257-.052.692-.052.692h.009l-.128 1.901c-.077.85-.745 1.442-1.542 1.442H15.54c-.822 0-1.464-.592-1.541-1.442z");
}

.jo2vldbkj {
  d: path("M5.31 3.178a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.jpyi06dtg {
  stop-color: var(--svg-color--8e7570, #8E7570);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.kk6l23w0e {
  stop-color: var(--svg-color--886f6a, #886F6A);
}

.kn4mnxbqu {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.15 12.912a.67.67 0 0 0-.65.508a.132.132 0 0 0 .129.164H15.7a.11.11 0 0 0 .11-.13a.67.67 0 0 0-.66-.542");
}

.kq0zgozqx {
  cx: 18.589px;
  cy: 13.298px;
  r: 0.478px;
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l1_ky_bto {
  d: path("M17.962 12.02h-.002l-.003-.001l-.007-.001a1 1 0 0 0-.09-.01a1.36 1.36 0 0 0-.89.286a.256.256 0 0 0 .313.406a.85.85 0 0 1 .547-.18q.023 0 .032.003h.004a.256.256 0 0 0 .096-.503");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lagcd8brb {
  stop-color: var(--svg-color--562f3a, #562F3A);
  stop-opacity: 0;
}

.lftvhgbwh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.567 12.434c-.164-.13-.522-.315-.871-.26");
}

.lgnb04bhp {
  d: path("M29.123 4.686a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lnf674b0h {
  d: path("M23.787 21.35a1.988 1.988 0 0 0-3.976 0v1.686c0 .193.157.35.35.35h3.276a.35.35 0 0 0 .35-.35z");
}

.lqtoipbqj {
  stop-color: var(--svg-color--68423f, #68423F);
  stop-opacity: 0;
}

.lrf8ycbwa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.67 6.69h27.031");
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc012eb8j {
  d: path("M13.823 12.313c0-.128.051-.282.154-.359l.078-.077a.5.5 0 0 0 .18-.41v-.41a.25.25 0 0 1 .206-.255c.31-.077.953-.205 1.88-.205c.928 0 1.572.128 1.881.205a.28.28 0 0 1 .206.256v.41a.6.6 0 0 0 .18.41c.242.168.227.261.207.46c-.026.257-.052.692-.052.692h.009l-.128 1.901c-.077.85-.745 1.442-1.542 1.442H15.54c-.822 0-1.464-.592-1.541-1.442c-.067-.872-.097-1.747-.176-2.618");
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mrtnubb3p {
  d: path("M16.272 26.214c-2.363 0-4.203-.719-4.828-1.078V22.23h9.5v3.015c-.573.323-2.31.969-4.672.969");
}

.my3wtvo7r {
  stop-color: var(--svg-color--2161bb, #2161BB);
}

.n5tde31zi {
  stop-color: var(--svg-color--947870, #947870);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.o3ags8bfr {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.447 12.912a.67.67 0 0 1 .65.508a.132.132 0 0 1-.128.164h-1.072a.11.11 0 0 1-.109-.13a.67.67 0 0 1 .659-.542");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.ob61f_0qn {
  stop-color: var(--svg-color--886b66, #886B66);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.op745bcjt {
  stop-color: var(--svg-color--947870, #947870);
}

.ord38lb5d {
  stop-color: var(--svg-color--49252f, #49252F);
}

.pdrq0-vxx {
  stop-color: var(--svg-color--46212d, #46212D);
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pk34a-btb {
  cx: 18.588px;
  cy: 13.298px;
  r: 0.802px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pr8-z2b3y {
  d: path("M7.31 29.814v.376h4.634v-1.914H9.592c-.383.377-1.215.73-1.836.942c-.398.168-.445.442-.445.596");
}

.ps5p_xb2b {
  stop-color: var(--svg-color--7c4f4e, #7C4F4E);
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qc5umhbsx {
  stop-color: var(--svg-color--9e7970, #9E7970);
}

.qcugcqlkb {
  stop-color: var(--svg-color--2e82d2, #2E82D2);
}

.qhgoq_w9f {
  d: path("M15.25 13.042a.43.43 0 0 0-.413.542h.828a.43.43 0 0 0-.415-.542");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r981kx0se {
  fill: var(--svg-color--000, #000);
  d: path("M15.495 13.471a.244.244 0 0 0-.245-.245a.244.244 0 0 0-.218.358h.434a.24.24 0 0 0 .03-.113");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rcswokzqh {
  stop-color: var(--svg-color--623c31, #623C31);
  stop-opacity: 0;
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.s_-l0fbyh {
  d: path("M14.666 12.02h.002l.002-.001l.008-.001a1 1 0 0 1 .09-.01a1.36 1.36 0 0 1 .89.286a.256.256 0 0 1-.313.406a.85.85 0 0 0-.548-.18l-.031.003h-.005a.256.256 0 0 1-.095-.503");
}

.s_t4keb-b {
  stop-color: var(--svg-color--795a5b, #795A5B);
  stop-opacity: 0;
}

.s0g9yis6b {
  stop-color: var(--svg-color--62383a, #62383A);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.sh5_80x3i {
  stop-color: var(--svg-color--886f6a, #886F6A);
  stop-opacity: 0;
}

.slzndd6vb {
  d: path("m9.675 29.162l-.513-5.893h3.22l-.534 5.965z");
}

.st5m78bwy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M14.123 10.987v.431c-.004.072-.034.231-.124.299");
}

.suv_43jhc {
  stop-color: var(--svg-color--532a2a, #532A2A);
}

.sxtwc4v0n {
  d: path("m18.614 10.187l.206.102c.361.18.567.59.49 1.025l-.283 1.46c-.026.15-.125.252-.275.256h-.009s.026-.435.052-.691c.02-.209-.016-.272-.206-.462a.6.6 0 0 1-.18-.41v-.094a.28.28 0 0 0-.207-.256c-.309-.077-.953-.205-1.88-.205c-.928 0-1.572.128-1.881.205a.25.25 0 0 0-.206.256v.095a.5.5 0 0 1-.18.41l-.078.076c-.103.077-.154.23-.154.359c.025.282.051.691.051.691h-.023a.304.304 0 0 1-.286-.256l-.283-1.46a.98.98 0 0 1 .515-.999l.206-.102c.129-.077.258-.18.386-.282l.464-.487a.94.94 0 0 1 1.056-.153c.258.077.542.077.8 0a1.16 1.16 0 0 1 1.133.256l.386.384c.103.128.232.205.386.282");
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.timdh8g1l {
  d: path("M7.773 5.993a.399.399 0 1 1 .796-.033v.46a.38.38 0 0 1-.758.032z");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tldk1ryzb {
  stop-color: var(--svg-color--613e45, #613E45);
  stop-opacity: 0;
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tox4m5q8h {
  stop-color: var(--svg-color--816457, #816457);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tuvsor_7r {
  stop-color: var(--svg-color--5a2e30, #5A2E30);
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u8djmyolf {
  d: path("M17.348 13.043a.43.43 0 0 1 .412.541h-.827a.43.43 0 0 1 .415-.541");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.uiynf4b0r {
  d: path("M8.007 7.135h2.46v7.269h-2.46z");
}

.ujo-xtz9c {
  stop-color: var(--svg-color--82665a, #82665A);
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uy-b_jbkp {
  d: path("M22.663 5.91a.401.401 0 1 0-.802-.014v.575a.391.391 0 0 0 .783.013z");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v5fxumbup {
  cx: 14.02px;
  cy: 13.298px;
  r: 0.802px;
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vqjt84b9q {
  cx: 18.589px;
  cy: 13.298px;
  r: 0.478px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.vy82ggxcw {
  d: path("m18.203 10.597l-1.478.492a.503.503 0 0 0 .226.976l1.47-.197z");
}

.vyy2yi9lp {
  d: path("M17.316 13.133c.03.04-.033.09-.106.145c-.072.054-.126.092-.157.051c-.03-.04.004-.117.076-.172c.073-.054.157-.065.187-.024");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w317cxbhz {
  d: path("m16.094 13.361l-.255.816a.26.26 0 0 0 .25.336h.378a.26.26 0 0 0 .25-.336l-.256-.816c-.054-.18-.31-.18-.367 0");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wr3tf456n {
  cx: 15.121px;
  cy: 13.226px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.187px;
  ry: 0.095px;
}

.wvhi0ab5z {
  stop-color: var(--svg-color--6d3e45, #6D3E45);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x2yt-r-7b {
  cx: 15.121px;
  cy: 13.226px;
  rx: 0.187px;
  ry: 0.095px;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xjez76bam {
  stop-color: var(--svg-color--1071cb, #1071CB);
}

.xr8cplx4f {
  stop-color: var(--svg-color--886b66, #886B66);
  stop-opacity: 0;
}

.xz64_6yvi {
  stop-color: var(--svg-color--845e5b, #845E5B);
}

.xzfe3gq7a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.06 12.434c.165-.13.523-.315.872-.26");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y8dp0hbvk {
  stop-color: var(--svg-color--815651, #815651);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ydv5mwxxd {
  stop-color: var(--svg-color--683842, #683842);
}

.yg2iljbpo {
  fill: var(--svg-color--352827, #352827);
  d: path("M14.666 12.02h.002l.002-.001l.008-.001a1 1 0 0 1 .09-.01a1.36 1.36 0 0 1 .89.286a.256.256 0 0 1-.313.406a.85.85 0 0 0-.548-.18l-.031.003h-.005a.256.256 0 0 1-.095-.503");
}

.yi8xsxb7e {
  stop-color: var(--svg-color--3770bc, #3770BC);
  stop-opacity: 0;
}

.ykol_yz-a {
  stop-color: var(--svg-color--9d6f6b, #9D6F6B);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yp0derb1r {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m16.094 13.361l-.255.816a.26.26 0 0 0 .25.336h.378a.26.26 0 0 0 .25-.336l-.256-.816c-.054-.18-.31-.18-.367 0");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z6dva1ujr {
  fill: var(--svg-color--000, #000);
  d: path("M17.102 13.471c0-.136.11-.245.245-.245a.244.244 0 0 1 .219.358h-.435a.2.2 0 0 1-.029-.113");
}

.z89m61ndy {
  cx: 14.019px;
  cy: 13.298px;
  r: 0.478px;
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zen1j3nse {
  d: path("M24.755 5.993a.399.399 0 1 0-.796-.033v.46a.38.38 0 0 0 .757.032z");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zka8snbuo {
  d: path("M8.787 21.35a1.988 1.988 0 1 1 3.977 0v1.686a.35.35 0 0 1-.35.35H9.137a.35.35 0 0 1-.35-.35z");
}

</style>
