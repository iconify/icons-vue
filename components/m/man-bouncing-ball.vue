<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iKZ8Nte)" transform="rotate(26.961 19.37 13.524)" class="pb-ncu9ww"/><g filter="url(#iMcNRTd)"><path class="r6j3kl0sw"/></g><circle fill="url(#i4cE4hd)" class="grir6byuw"/><circle fill="url(#i34Aose)" class="grir6byuw"/><circle fill="url(#iVc3bXd)" class="grir6byuw"/><circle fill="url(#igis1Ob)" class="grir6byuw"/><g filter="url(#iPB8BId)"><path fill="url(#ilTTZHc)" class="jdazbm2re"/></g><path fill="url(#iMxJ9Md)" class="cqz-w1b7i"/><path fill="url(#i37Ivtb)" class="cqz-w1b7i"/><path fill="url(#iIwuKqd)" class="fye85vwtf"/><path fill="url(#inz98xd)" class="fye85vwtf"/><g filter="url(#ivEzajc)"><path fill="url(#iHTdled)" class="gpq1nzcli"/><path fill="url(#iYnzSSO)" class="gpq1nzcli"/><path fill="url(#iuGL51c)" class="gpq1nzcli"/></g><g filter="url(#ij1wzmv)"><path fill="url(#iYdm3Le)" class="oliwcppol"/><path fill="url(#iRqR6Fd)" class="oliwcppol"/></g><path fill="url(#ipP3Trb)" class="sgu9iibyn"/><path fill="url(#imuf1nK)" class="sgu9iibyn"/><path fill="url(#i8znWye)" class="k7f29ob7j"/><path fill="url(#iyYHT4b)" class="k7f29ob7j"/><path fill="url(#ig1gGSb)" class="k7f29ob7j"/><path fill="url(#iVZB6ib)" class="k7f29ob7j"/><path class="ch0turbnc"/><path fill="url(#iziXh3b)" class="oog4fwbby"/><path fill="url(#iNow95b)" class="oog4fwbby"/><path fill="url(#ip0rqdb)" class="oog4fwbby"/><g filter="url(#ixpLCfc)"><path class="zgfxq_wdr"/><path fill="url(#iRzl5sb)" class="hw1s3vbuj"/><path fill="url(#ifyAMbe)" class="hw1s3vbuj"/><path fill="url(#ib7EVkb)" class="hw1s3vbuj"/></g><g filter="url(#iRaew0b)"><path fill="url(#ihGkNze)" class="uhuxi7bft"/><path fill="url(#i9OR8wd)" class="uhuxi7bft"/></g><g filter="url(#iACB6Mc)"><path fill="url(#iSLUPYA)" class="owta28hdj"/><path fill="url(#ig5WTge)" class="owta28hdj"/></g><g filter="url(#iCxWN8d)"><path fill="url(#i4R9lfM)" clip-rule="evenodd" class="itd4dhbxt"/></g><path class="dhjffcbol"/><path fill="url(#ioG7zAe)" class="e_4443q9y"/><path fill="url(#i9lWtTb)" class="e_4443q9y"/><g filter="url(#iupu9me)"><path class="dqwb5fbgf"/><path fill="url(#iFBFewc)" class="gz2sg7q3k"/></g><path fill="url(#ifqaS8c)" clip-rule="evenodd" class="hpi15_2ud"/><path fill="url(#imZR7bn)" clip-rule="evenodd" class="hpi15_2ud"/><path fill="url(#iVEUKjb)" clip-rule="evenodd" class="vaw3u4b-l"/><path fill="url(#iNbvfDe)" clip-rule="evenodd" class="vaw3u4b-l"/><path fill="url(#in3jGFe)" clip-rule="evenodd" class="kmtcs-leg"/><path fill="url(#i8Fofoc)" clip-rule="evenodd" class="kmtcs-leg"/><path clip-rule="evenodd" class="t9n0hyb0d"/><path fill="url(#icl5jnd)" clip-rule="evenodd" class="b2imp9yay"/><path fill="url(#idpsmsp)" clip-rule="evenodd" class="p5-t_7f4e"/><g filter="url(#iOjuE7d)"><path fill="url(#io80Jgb)" class="mnygaklfd"/><path fill="url(#iPtltNd)" class="mnygaklfd"/></g><path fill="url(#iRq380K)" class="mnygaklfd"/><circle fill="url(#iNP1XTc)" class="uajwsdjcx"/><g filter="url(#iqQqD7d)"><circle fill="url(#i6debdc)" class="oemrddbtd"/></g><g filter="url(#i7y4gKd)"><circle fill="url(#iMl5mhL)" class="c7nm-pbio"/><circle fill="url(#imfSn6S)" class="c7nm-pbio"/></g><g filter="url(#iTADtSd)"><circle class="k73ndqugf"/><circle fill="url(#iD4fYxb)" class="nalw3tgao"/><circle fill="url(#ioQpUlo)" class="nalw3tgao"/></g><path fill="url(#iGaUhja)" class="v2saq3dko"/><path fill="url(#iOyqNlb)" class="v2saq3dko"/><path fill="url(#iJPun3d)" class="v2saq3dko"/><path fill="url(#ibql9om)" class="v2saq3dko"/><path fill="url(#iiXyNye)" class="v2saq3dko"/><g filter="url(#iObMmmt)"><path class="jpqqymbzn"/><path fill="url(#iVLP56s)" class="qyflmdrrh"/><path fill="url(#iN6NeOc)" class="qyflmdrrh"/><path fill="url(#iuG0vYb)" class="qyflmdrrh"/><path fill="url(#ivkzDyb)" class="qyflmdrrh"/><path fill="url(#iJxENJb)" class="qyflmdrrh"/><path fill="url(#iSxlAob)" class="qyflmdrrh"/></g><path fill="url(#i28Aode)" class="tlio5k8-n"/><path fill="url(#i5qsqEt)" class="tlio5k8-n"/><path fill="url(#izlaZJe)" class="tlio5k8-n"/><g filter="url(#irgQifd)"><path class="blm1oqbfp"/></g><g filter="url(#ihhvc3c)"><path class="vko9wdbzs"/><path fill="url(#i6Npdtc)" class="j6_w01_5y"/><path fill="url(#iDKeZxa)" class="j6_w01_5y"/><path fill="url(#iug7Nbd)" class="j6_w01_5y"/></g><g filter="url(#iUAI80b)"><path stroke="url(#iJo4kJc)" class="yxuts5vjo"/></g><path class="cobhahb0v"/><path class="ktfv_h4-b"/><path fill="url(#ivxc70b)" class="b5zsqbcnx"/><path class="u3p_p-buj"/><g filter="url(#ij54RKa)"><path class="bs6m-x9-n"/><path fill="url(#iQXeUqt)" class="vx4jfa6qa"/></g><g filter="url(#iNgUJqc)"><path fill="url(#iNMIyze)" class="du2q4r9hx"/></g><path class="uv6qc3t6k"/><path fill="url(#irdoGBY)" class="w5r_v_hxa"/><path class="gvtlfib6o"/><g filter="url(#iallcpd)"><path fill="url(#iJGOSGe)" class="foeq03ccy"/></g><g filter="url(#iG8Pzze)"><ellipse transform="rotate(-27.914 11.711 5.656)" class="mv41sa4hi"/><ellipse fill="url(#i6mbttb)" transform="rotate(-27.914 11.711 5.656)" class="svuy_kj5k"/></g><g filter="url(#idRFuNc)"><path fill="url(#isnmLMn)" clip-rule="evenodd" class="q6mscqhlm"/></g><g filter="url(#iYmE7Nb)"><path class="lhkt5glit"/></g><g filter="url(#i84PSpb)"><path fill="url(#iWqJ8Bc)" clip-rule="evenodd" class="ua8ehlpbi"/></g><g filter="url(#iHaGxOc)"><path class="siy60lb1n"/></g><path fill="url(#io9XFsb)" class="t0gsxdnbf"/><path fill="url(#i0SJanb)" class="t0gsxdnbf"/><path fill="url(#ifI0f7d)" class="t0gsxdnbf"/><path fill="url(#itmgq0b)" class="t0gsxdnbf"/><path fill="url(#iGHLQte)" clip-rule="evenodd" class="itd4dhbxt"/><path fill="url(#ioZNlme)" clip-rule="evenodd" class="itd4dhbxt"/><defs><radialGradient id="iKZ8Nte" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.08)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="e5q41c8fy"/><stop offset="1" class="ld99d_7hf"/></radialGradient><radialGradient id="i34Aose" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.336 18.416)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iVc3bXd" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.31 9.57)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="igis1Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.135)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="ilTTZHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.893)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="iMxJ9Md" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.166)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="hxm-6izwk"/><stop offset="1" class="j-x6w7b4y"/></radialGradient><radialGradient id="i37Ivtb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.76)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="u-m77k52c"/><stop offset=".977" class="nhbmuhbvb"/></radialGradient><radialGradient id="iHTdled" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.655)" gradientUnits="userSpaceOnUse"><stop class="vhhvj2t-s"/><stop offset="1" class="so34edl-m"/></radialGradient><radialGradient id="iYnzSSO" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.61)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="iuGL51c" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.904 22.575)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="ipP3Trb" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.336 12.65)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="a30nnuz6x"/><stop offset="1" class="sg7xbrbid"/></radialGradient><radialGradient id="i8znWye" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.525 12.353)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="ig1gGSb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.172 18.167)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="iVZB6ib" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.862 17.753)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iziXh3b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.885)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="iNow95b" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.197)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="ip0rqdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.807)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="iRzl5sb" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.979)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ifyAMbe" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.714 2.293)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="ib7EVkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.9)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="ihGkNze" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.455 11.567)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="xu1e5_bcz"/><stop offset="1" class="jixz69llq"/></radialGradient><radialGradient id="i4R9lfM" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.979)" gradientUnits="userSpaceOnUse"><stop class="fthz0iw6h"/><stop offset="1" class="doutuqf7h"/></radialGradient><radialGradient id="ioG7zAe" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.104)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="amshv2yws"/><stop offset="1" class="fszi1o-7g"/></radialGradient><radialGradient id="i9lWtTb" cx="0" cy="0" r="1" gradientTransform="rotate(165.718 7.594 5.575)scale(.44339 2.09581)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="qe2iy6u-s"/><stop offset="1" class="b8n9t1b9i"/></radialGradient><radialGradient id="iFBFewc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.3 -14.11)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="xjp952bfc"/><stop offset="1" class="qqpuob36k"/></radialGradient><radialGradient id="imZR7bn" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.213 7.603)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="iNbvfDe" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .796 7.956)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="i8Fofoc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.984)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="icl5jnd" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .693 8.397)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="lcjnzacgs"/><stop offset="1" class="f8fpdnbnw"/></radialGradient><radialGradient id="idpsmsp" cx="0" cy="0" r="1" gradientTransform="rotate(133.831 .435 8.684)scale(1.89522 1.00859)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="zxijwrkla"/><stop offset="1" class="xt8_tkusr"/></radialGradient><radialGradient id="io80Jgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.533)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="uqxno_b8g"/><stop offset=".81" class="d4a71bwtp"/></radialGradient><radialGradient id="iPtltNd" cx="0" cy="0" r="1" gradientTransform="rotate(-104.504 15.38 1.246)scale(8.36833 2.71135)" gradientUnits="userSpaceOnUse"><stop class="g_v4sglua"/><stop offset="1" class="o67susxgp"/></radialGradient><radialGradient id="iRq380K" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.253 9.023)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="ip3ktqbqy"/><stop offset="1" class="whspc9bgn"/></radialGradient><radialGradient id="iNP1XTc" cx="0" cy="0" r="1" gradientTransform="matrix(.80725 0 0 1.4127 9.889 6.014)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="imfSn6S" cx="0" cy="0" r="1" gradientTransform="matrix(.3803 -.27691 .31606 .43405 15.204 5.892)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iD4fYxb" cx="0" cy="0" r="1" gradientTransform="rotate(-61.468 12.882 -9.43)scale(.79092 .46293)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ioQpUlo" cx="0" cy="0" r="1" gradientTransform="rotate(44.709 .205 21.285)scale(.16783 .21635)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iJPun3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.94946 -4.50957 0 13.066 5.282)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="ibql9om" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60127 .74002 0 13.92 5.429)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iiXyNye" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.63981 .79566 0 11.823 5.413)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iVLP56s" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 6.666 4.793)scale(2.57889 4.38563)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iuG0vYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.08487 -.91657 .45014 -.04168 10.938 4.34)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="ivkzDyb" cx="0" cy="0" r="1" gradientTransform="matrix(.39521 -.9046 .73777 .32233 14.785 5.214)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iJxENJb" cx="0" cy="0" r="1" gradientTransform="matrix(.45669 .56667 -.50033 .40322 12.484 2.057)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iSxlAob" cx="0" cy="0" r="1" gradientTransform="matrix(.66747 -1.39642 .48248 .23062 14.767 4.073)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="i28Aode" cx="0" cy="0" r="1" gradientTransform="matrix(.12014 .46687 -.76755 .19752 13.16 2.057)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="i5qsqEt" cx="0" cy="0" r="1" gradientTransform="rotate(55.305 2.896 11.648)scale(.89458 1.86163)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="izlaZJe" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 6.255 3.44)scale(3.63642 4.5502)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iJo4kJc" cx="0" cy="0" r="1" gradientTransform="matrix(.01132 -.28855 .86565 .03395 12.802 7.86)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="ivxc70b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .41607 -.49232 0 13.844 5.854)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iQXeUqt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 8.275 -.495)scale(.17423 .23987)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irdoGBY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .41609 -.49234 0 11.837 5.854)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i6mbttb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 8.707 -2.861)scale(.22759 .27357)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isnmLMn" cx="0" cy="0" r="1" gradientTransform="matrix(.09053 -.37342 .81922 .1986 13.968 5.002)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iWqJ8Bc" cx="0" cy="0" r="1" gradientTransform="matrix(-.09052 -.37341 .81922 -.1986 11.714 5.002)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="io9XFsb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.4 3.916)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="itmgq0b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.227 3.385)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><radialGradient id="iGHLQte" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.896 13.276)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gifgm4i1v"/><stop offset="1" class="jyrqxvbae"/></radialGradient><radialGradient id="ioZNlme" cx="0" cy="0" r="1" gradientTransform="matrix(.625 -.42188 .2738 .40562 6.907 14.276)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="wgpnrcbke"/><stop offset="1" class="knaev-n-x"/></radialGradient><linearGradient id="i4cE4hd" x1="4.743" x2="6.868" y1="19.041" y2="21.166" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iIwuKqd" x1="11.118" x2="8.993" y1="26.354" y2="25.604" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="inz98xd" x1="8.915" x2="10.134" y1="25.354" y2="25.817" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="iYdm3Le" x1="5.181" x2="9.845" y1="27.26" y2="29.791" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iRqR6Fd" x1="7.524" x2="7.466" y1="28.19" y2="28.295" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="imuf1nK" x1="21.97" x2="21.54" y1="21.182" y2="20.408" gradientUnits="userSpaceOnUse"><stop class="rahvf0pdu"/><stop offset="1" class="z2lhmbb7y"/></linearGradient><linearGradient id="iyYHT4b" x1="23.368" x2="23.009" y1="20.463" y2="19.729" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="i9OR8wd" x1="26.314" x2="26.114" y1="18.893" y2="18.979" gradientUnits="userSpaceOnUse"><stop offset=".244" class="jylqepbzd"/><stop offset="1" class="v2dwqfdba"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="iSLUPYA" x1="27.533" x2="25.439" y1="21.203" y2="16.327" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ig5WTge" x1="26.269" x2="26.38" y1="19.022" y2="18.975" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="ifqaS8c" x1="6.061" x2="4.745" y1="13.205" y2="14.701" gradientUnits="userSpaceOnUse"><stop class="g74-q2bdc"/><stop offset="1" class="oimmmv6rh"/></linearGradient><linearGradient id="iVEUKjb" x1="5.959" x2="4.202" y1="13.5" y2="15.172" gradientUnits="userSpaceOnUse"><stop class="g74-q2bdc"/><stop offset="1" class="oimmmv6rh"/></linearGradient><linearGradient id="in3jGFe" x1="5.821" x2="3.962" y1="13.979" y2="15.619" gradientUnits="userSpaceOnUse"><stop class="g74-q2bdc"/><stop offset="1" class="oimmmv6rh"/></linearGradient><linearGradient id="i6debdc" x1="10.656" x2="10.362" y1="6.142" y2="6.142" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iMl5mhL" x1="15.532" x2="15.156" y1="5.511" y2="6.678" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iGaUhja" x1="14.697" x2="11.184" y1="6.193" y2="6.716" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iOyqNlb" x1="10.358" x2="11.422" y1="7.433" y2="7.294" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iN6NeOc" x1="10.604" x2="11.939" y1="5.891" y2="3.519" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="i6Npdtc" x1="12.443" x2="12.875" y1="6.496" y2="6.496" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iDKeZxa" x1="13.273" x2="12.801" y1="6.644" y2="6.638" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iug7Nbd" x1="12.93" x2="12.93" y1="6.986" y2="6.722" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iNMIyze" x1="14.201" x2="14.057" y1="5.725" y2="5.814" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJGOSGe" x1="12.178" x2="12.034" y1="5.725" y2="5.814" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0SJanb" x1="9.782" x2="13.493" y1="4.104" y2="4.104" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="ifI0f7d" x1="13.556" x2="13.556" y1="4.447" y2="4.33" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient><filter id="iMcNRTd" width="7.486" height="8.65" x="14.87" y="7.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.498039 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iPB8BId" width="5.439" height="5.49" x="2.462" y="16.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="ivEzajc" width="6.264" height="4.296" x="4.74" y="25.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.505882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="ij1wzmv" width="5.105" height="3.176" x="4.74" y="26.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="ixpLCfc" width="7.339" height="5.547" x="11.424" y="16.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iRaew0b" width="5.437" height="5.553" x="22.676" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iACB6Mc" width="2.689" height="5.353" x="25.225" y="16.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iCxWN8d" width="8.098" height="6.294" x="5.657" y="8.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.423529 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23222" result="effect2_innerShadow_3987_23222"/></filter><filter id="iupu9me" width="3.404" height="3.248" x="18.396" y="8.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iOjuE7d" width="7.636" height="9.986" x="11.582" y="7.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.34902 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iqQqD7d" width="1.915" height="1.915" x="9.699" y="5.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".25"/></filter><filter id="i7y4gKd" width="1.786" height="1.786" x="14.265" y="4.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iTADtSd" width="1.915" height="1.915" x="14.075" y="5.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".25"/></filter><filter id="iObMmmt" width="5.797" height="3.8" x="9.942" y="1.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23222" result="effect2_innerShadow_3987_23222"/></filter><filter id="irgQifd" width="2.31" height="2.733" x="11.576" y="5.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".375"/></filter><filter id="ihhvc3c" width="1.063" height="1.433" x="12.309" y="5.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".05"/></filter><filter id="iUAI80b" width="1.88" height=".893" x="11.9" y="7.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".05"/></filter><filter id="ij54RKa" width=".47" height=".429" x="13.452" y="5.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".05"/></filter><filter id="iNgUJqc" width=".626" height=".636" x="13.784" y="5.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".1"/></filter><filter id="iallcpd" width=".67" height=".695" x="11.74" y="5.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".1"/></filter><filter id="iG8Pzze" width=".528" height=".432" x="11.447" y="5.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".05"/></filter><filter id="idRFuNc" width="1.197" height=".892" x="13.422" y="4.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iYmE7Nb" width="1.263" height=".708" x="13.388" y="4.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".1"/></filter><filter id="i84PSpb" width="1.197" height=".892" x="11.063" y="4.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23222"/></filter><filter id="iHaGxOc" width="1.263" height=".708" x="11.03" y="4.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23222" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bouncing-ball" /></template>
<style>
.a30nnuz6x {
  stop-color: var(--svg-color--ffc327, #FFC327);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.amshv2yws {
  stop-color: var(--svg-color--da800e, #DA800E);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.b2imp9yay {
  fill-rule: evenodd;
  d: path("M6.293 14.833c-.79-.084-1.136.336-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.025a.415.415 0 0 1-.088.826");
}

.b5zsqbcnx {
  d: path("M13.845 5.48a.41.41 0 0 1 .396.52h-.794a.413.413 0 0 1 .398-.52");
}

.b8n9t1b9i {
  stop-color: var(--svg-color--fed031, #FED031);
  stop-opacity: 0;
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.blm1oqbfp {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m12.714 5.957l-.378.782c-.046.16.066.322.225.322h.339c.16 0 .271-.164.225-.322l-.23-.782c-.049-.173-.13-.173-.181 0");
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bs6m-x9-n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.814 5.567c.03.04-.032.087-.101.139c-.07.052-.121.089-.15.05c-.03-.04.003-.114.072-.166c.07-.052.15-.062.18-.023");
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c7nm-pbio {
  cx: 15.033px;
  cy: 6.014px;
  r: 0.768px;
}

.ch0turbnc {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.713c-1.2-.712-1.919-1.898-2.143-2.453l2.157-3.016c.377.41 1.05 1.397 1.46 2.023a.9.9 0 0 1 .147.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.187");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cobhahb0v {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M12.84 7.453c-.233 0-.452-.055-.637-.15c-.063-.033-.13.038-.09.095a.87.87 0 0 0 .728.39a.87.87 0 0 0 .728-.39c.04-.06-.028-.128-.091-.096a1.4 1.4 0 0 1-.637.151");
}

.cqz-w1b7i {
  d: path("m11.001 20.658l.672-.75l2.336 1.86c-.07.047-.328.208-.797.476c-.644.413-1.029 1.089-1.14 1.375l-1.493 3.703l-1.976-.968c.325-.86 1.059-2.838 1.39-3.875c.331-1.038.81-1.646 1.008-1.82");
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d4a71bwtp {
  stop-color: var(--svg-color--3b8be5, #3B8BE5);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dhjffcbol {
  fill: var(--svg-color--ffde41, #FFDE41);
  d: path("M11.657 11.76c-.237-1.5.143-2.745.383-3.125c.294-.606.987-.805 1.297-.828h2.437c.386.577.634 1.595.744 2.24c.034.203.078.403.145.599c.365 1.064 1.627 4.741 2.14 6.134a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.392c-.423-1.315-.893-3.615-1.107-4.968");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.doutuqf7h {
  stop-color: var(--svg-color--ffb834, #FFB834);
}

.dqwb5fbgf {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.36a.095.095 0 0 0-.107.029c-.44.55-.75 1.567-.821 2.056q.254.093.432.225c.418.266.704.576.875.931c.812-.549 1.637-.802 2.097-.855c-.342-.803-.922-1.491-1.735-2.01a4 4 0 0 0-.741-.377");
}

.du2q4r9hx {
  d: path("M14.21 5.837a.4.4 0 0 0-.106-.213l-.12.131l.054.105z");
}

.e_4443q9y {
  d: path("M11.657 11.76c-.237-1.5.143-2.745.383-3.125c.294-.606.987-.805 1.297-.828h2.437c.386.577.634 1.595.744 2.24c.034.203.078.403.145.599c.365 1.064 1.627 4.741 2.14 6.134a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.392c-.423-1.315-.893-3.615-1.107-4.968");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.e5q41c8fy {
  stop-color: var(--svg-color--ed9827, #ED9827);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f8fpdnbnw {
  stop-color: var(--svg-color--ffc031, #FFC031);
  stop-opacity: 0;
}

.foeq03ccy {
  d: path("M12.21 5.843c0-.133-.108-.222-.137-.248l-.133.128l.082.167z");
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.fszi1o-7g {
  stop-color: var(--svg-color--da800e, #DA800E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fthz0iw6h {
  stop-color: var(--svg-color--ffc12d, #FFC12D);
}

.fye85vwtf {
  d: path("m11.432 25.205l-.853 2.118l-1.976-.97c.175-.462.469-1.25.754-2.04z");
}

.g_v4sglua {
  stop-color: var(--svg-color--5290df, #5290DF);
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g74-q2bdc {
  stop-color: var(--svg-color--ffbf31, #FFBF31);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.gc9u7lbfl {
  stop-color: var(--svg-color--53adfa, #53ADFA);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gifgm4i1v {
  stop-color: var(--svg-color--ffc128, #FFC128);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gpq1nzcli {
  d: path("m9.12 25.844l.483.611a.27.27 0 0 0 .398.059c.121-.108.433-.271.71-.059c.279.213.195.578.118.735l-1.032 2.505a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.505a.53.53 0 0 1 .643-.194c1.414.556 2.194.187 2.545-.07c.143-.106.257-.248.345-.388c.105-.164.353-.201.473-.048");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.grir6byuw {
  cx: 5.18px;
  cy: 19.401px;
  r: 2.721px;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.gvtlfib6o {
  fill: var(--svg-color--000, #000);
  d: path("M12.07 5.891a.234.234 0 0 0-.235-.235a.234.234 0 0 0-.209.344h.417a.23.23 0 0 0 .028-.109");
}

.gz2sg7q3k {
  d: path("M19.324 8.36a.095.095 0 0 0-.107.029c-.44.55-.75 1.567-.821 2.056q.254.093.432.225c.418.266.704.576.875.931c.812-.549 1.637-.802 2.097-.855c-.342-.803-.922-1.491-1.735-2.01a4 4 0 0 0-.741-.377");
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hpi15_2ud {
  fill-rule: evenodd;
  d: path("M6.322 13.74c-.775-.133-1.17.089-1.3.288a.415.415 0 1 1-.697-.45c.392-.606 1.215-.814 2.136-.657a.415.415 0 1 1-.14.818");
}

.hw1s3vbuj {
  d: path("M12.962 17.51c.094-.275.216-.52.266-.61h5.148c.539 1.52-.652 2.926-1.2 3.239c-.978.601-2.891 1.78-3.085 1.898c-.242.149-.512.239-.73.067c-.759-.532-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.699 1.148-1.382 1.265-1.726");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.hxm-6izwk {
  stop-color: var(--svg-color--ffcd30, #FFCD30);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.ip3ktqbqy {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
}

.itd4dhbxt {
  fill-rule: evenodd;
  d: path("m11.974 9.05l.053-.09l1.728 1.007l-.074.126c-.712 1.225-1.57 2.698-3.676 3.892c-.769.435-1.654.656-2.382.773c-.256.04-.502.07-.728.091c-.55.05-.994-.403-.988-.955l.01-1.025c.251.003.784.011 1.39-.086c.617-.099 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.j-x6w7b4y {
  stop-color: var(--svg-color--eda120, #EDA120);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j6_w01_5y {
  d: path("m12.665 5.882l-.244.782c-.05.16.07.322.239.322h.362a.25.25 0 0 0 .24-.322l-.245-.782c-.053-.173-.297-.173-.352 0");
}

.jdazbm2re {
  d: path("M5.527 16.702a2.5 2.5 0 0 0 .599 1.587l.896-.891q.092.085.177.177l-.901.896a2.23 2.23 0 0 0 1.587.621q.013.123.016.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.772l1.754 1.914q-.088.089-.185.168l-1.746-1.905l-.77.764c.422.462.689 1.08.715 1.762a3 3 0 0 1-.251-.018a2.5 2.5 0 0 0-.64-1.567l-.877.871a3 3 0 0 1-.177-.177l.876-.87a2.23 2.23 0 0 0-1.556-.576a3 3 0 0 1-.024-.249l.091-.002c.638 0 1.22.245 1.667.65l.777-.773l-1.757-1.917q.088-.09.183-.17l1.751 1.91l.774-.768a2.77 2.77 0 0 1-.67-1.784q.126.005.25.02");
}

.jixz69llq {
  stop-color: var(--svg-color--3c93f1, #3C93F1);
}

.jpqqymbzn {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m15.057 3.034l.197.098c.346.172.543.564.47.981l-.272 1.399c-.024.144-.12.241-.263.245c.016-.232.031-.606.037-.665c.02-.199-.011-.258-.194-.44a.58.58 0 0 1-.172-.392v-.392a.265.265 0 0 0-.198-.246c-.296-.073-.913.246-1.801.246s-1.505-.32-1.801-.246a.24.24 0 0 0-.198.246v.392a.49.49 0 0 1-.172.393l-.074.073c-.1.074-.149.228-.149.35c.007.072.016.484.027.656a.29.29 0 0 1-.273-.245L9.949 4.09a.94.94 0 0 1 .494-.957c.466-.205.636-.515 1.012-.834a.9.9 0 0 1 1.011-.148c.247.074.518.074.765 0a1.11 1.11 0 0 1 1.086.246l.37.368c.099.122.222.196.37.27");
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.jylqepbzd {
  stop-color: var(--svg-color--4079dd, #4079DD);
}

.jyrqxvbae {
  stop-color: var(--svg-color--ffc128, #FFC128);
  stop-opacity: 0;
}

.k73ndqugf {
  cx: 15.033px;
  cy: 6.014px;
  r: 0.458px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.k7f29ob7j {
  d: path("m22.282 20.918l.03-.016c.636-.339 1.256-.67 1.728-.92l-.727-2.144l-2.087 1.175z");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kmtcs-leg {
  fill-rule: evenodd;
  d: path("M5.125 14.652c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.27.397-.609.78-.87a2.57 2.57 0 0 1 1.588-.457a.415.415 0 0 1-.042.829a1.74 1.74 0 0 0-1.077.313");
}

.knaev-n-x {
  stop-color: var(--svg-color--ffd135, #FFD135);
  stop-opacity: 0;
}

.ktfv_h4-b {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.94 5.355c.3 0 .553.207.622.487A.126.126 0 0 1 14.44 6h-1.026a.106.106 0 0 1-.104-.125a.64.64 0 0 1 .63-.519");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lcjnzacgs {
  stop-color: var(--svg-color--e58f20, #E58F20);
}

.ld99d_7hf {
  stop-color: var(--svg-color--e68e17, #E68E17);
}

.lhkt5glit {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.401 4.934c-.096-.088-.37-.24-.763-.202");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mnygaklfd {
  d: path("M11.884 8.965c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.289.365-.79.438-.954c.695.106.89.274.89.274l.008.012c-.149.277-.4.78-.453.984c-.07.273-.238 1.05.25 1.687c.373.487.812.598 1.233.589c.481 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.316-.893-3.616-1.107-4.97c-.19-1.197.015-2.232.227-2.794");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mv41sa4hi {
  cx: 11.711px;
  cy: 5.656px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.179px;
  ry: 0.091px;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.nalw3tgao {
  cx: 15.033px;
  cy: 6.014px;
  r: 0.458px;
}

.nhbmuhbvb {
  stop-color: var(--svg-color--c98041, #C98041);
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o67susxgp {
  stop-color: var(--svg-color--51b1ff, #51B1FF);
  stop-opacity: 0;
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oemrddbtd {
  cx: 10.656px;
  cy: 6.014px;
  r: 0.458px;
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.oimmmv6rh {
  stop-color: var(--svg-color--e2a433, #E2A433);
}

.oliwcppol {
  d: path("M9.794 29.473a.1.1 0 0 1 .043.125l-.04.097a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.424l.105-.164a.15.15 0 0 1 .2-.05z");
}

.oog4fwbby {
  d: path("M18.292 22.713c-1.2-.712-1.919-1.898-2.143-2.453l2.157-3.016c.377.41 1.05 1.397 1.46 2.023a.9.9 0 0 1 .147.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.187");
}

.owta28hdj {
  d: path("M25.282 16.609a.1.1 0 0 1 .044-.126l.091-.051a.4.4 0 0 1 .566.195l1.908 4.586a.3.3 0 0 1-.18.4l-.184.062a.15.15 0 0 1-.188-.085z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p5-t_7f4e {
  fill-rule: evenodd;
  d: path("M7.132 13.988a.415.415 0 0 1 .118.575a8 8 0 0 1-.912 1.13a.415.415 0 1 1-.603-.57l.005-.005c.16-.17.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pb-ncu9ww {
  width: 0.659px;
  height: 1.111px;
  x: 19.371px;
  y: 13.524px;
  rx: 0.33px;
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q6mscqhlm {
  fill-rule: evenodd;
  d: path("M13.66 4.999c.33-.031.543.098.594.145a.217.217 0 1 0 .295-.319c-.141-.13-.475-.301-.93-.259a.217.217 0 1 0 .04.433");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qe2iy6u-s {
  stop-color: var(--svg-color--fed031, #FED031);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qqpuob36k {
  stop-color: var(--svg-color--c2b1ce, #C2B1CE);
  stop-opacity: 0;
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyflmdrrh {
  d: path("m15.057 3.034l.197.098c.346.172.543.564.47.981l-.272 1.399c-.024.144-.12.241-.263.245c.016-.232.031-.606.037-.665c.02-.199-.011-.258-.194-.44a.58.58 0 0 1-.172-.392v-.392a.265.265 0 0 0-.198-.246c-.296-.073-.913.246-1.801.246s-1.505-.32-1.801-.246a.24.24 0 0 0-.198.246v.392a.49.49 0 0 1-.172.393l-.074.073c-.1.074-.149.228-.149.35c.007.072.016.484.027.656a.29.29 0 0 1-.273-.245L9.949 4.09a.94.94 0 0 1 .494-.957c.466-.205.636-.515 1.012-.834a.9.9 0 0 1 1.011-.148c.247.074.518.074.765 0a1.11 1.11 0 0 1 1.086.246l.37.368c.099.122.222.196.37.27");
}

.r6j3kl0sw {
  fill: var(--svg-color--ffd231, #FFD231);
  d: path("M15.216 10.081q.559-.015 1.474.058c.827.065 1.691.196 2.138.531c.582.371.909.828 1.026 1.371c.133.615.023 1.14-.23 1.801l-.151.383c-.124.312-.24.6-.287.8c-.06.258.098.434.404.438c.054 0 .106.026.14.068a.4.4 0 0 0 .206.147c.082.022.14.016.22.01q.044-.005.1-.008c.047-.002.09.02.117.06a.33.33 0 0 0 .2.145a.45.45 0 0 0 .243-.016a.2.2 0 0 1 .173.02a.6.6 0 0 0 .205.086c.14.02.305-.039.367-.234c.035-.109.08-.298.121-.477c.098-.416.25-.82.25-1.254a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.004v2.25q.147 0 .346-.007");
}

.rahvf0pdu {
  stop-color: var(--svg-color--df9a36, #DF9A36);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sg7xbrbid {
  stop-color: var(--svg-color--df9d34, #DF9D34);
}

.sgu9iibyn {
  d: path("M19.267 22.51c-.213.09-.352.069-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.804-4.56 2.436-4.773 2.527");
}

.siy60lb1n {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.28 4.934c.096-.088.37-.24.763-.202");
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.so34edl-m {
  stop-color: var(--svg-color--3d94fa, #3D94FA);
}

.svuy_kj5k {
  cx: 11.711px;
  cy: 5.656px;
  rx: 0.179px;
  ry: 0.091px;
}

.t0gsxdnbf {
  d: path("M9.782 3.485a.1.1 0 0 1 .1-.1h5.925a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.882a.1.1 0 0 1-.1-.1z");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t9n0hyb0d {
  fill: var(--svg-color--ffbf31, #FFBF31);
  fill-rule: evenodd;
  d: path("M6.293 14.833c-.79-.084-1.136.336-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.025a.415.415 0 0 1-.088.826");
}

.tlio5k8-n {
  d: path("m15.057 3.034l.197.098c.346.172.543.564.47.981l-.272 1.399c-.024.144-.12.241-.263.245c.016-.232.031-.606.037-.665c.02-.199-.011-.258-.194-.44a.58.58 0 0 1-.172-.392v-.392a.265.265 0 0 0-.198-.246c-.296-.073-.984.246-1.872.246s-1.434-.32-1.73-.246a.24.24 0 0 0-.198.246v.392a.49.49 0 0 1-.172.393l-.074.073c-.1.074-.149.228-.149.35c.007.072.016.484.027.656a.29.29 0 0 1-.273-.245L9.949 4.09a.94.94 0 0 1 .494-.957c.466-.205.636-.515 1.012-.834a.9.9 0 0 1 1.011-.148c.247.074.518.074.765 0a1.11 1.11 0 0 1 1.086.246l.37.368c.099.122.222.196.37.27");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u-m77k52c {
  stop-color: var(--svg-color--db9236, #DB9236);
  stop-opacity: 0;
}

.u3p_p-buj {
  fill: var(--svg-color--000, #000);
  d: path("M13.609 5.891c0-.13.104-.235.235-.235a.234.234 0 0 1 .21.343h-.417a.2.2 0 0 1-.028-.108");
}

.ua8ehlpbi {
  fill-rule: evenodd;
  d: path("M12.022 4.999c-.331-.031-.543.098-.595.145a.217.217 0 0 1-.294-.319c.14-.13.474-.301.93-.259a.217.217 0 0 1-.041.433");
}

.uajwsdjcx {
  cx: 10.657px;
  cy: 6.014px;
  r: 0.768px;
}

.uhuxi7bft {
  d: path("M23.563 19.874v-.778a.27.27 0 0 0-.276-.293c-.162.01-.508-.056-.595-.395s.206-.574.363-.649l2.362-1.327a.4.4 0 0 1 .566.195l1.908 4.586a.3.3 0 0 1-.18.399l-.57.195a.53.53 0 0 1-.624-.247c-.766-1.312-1.607-1.505-2.042-1.52a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.256");
}

.uqxno_b8g {
  stop-color: var(--svg-color--3da9fd, #3DA9FD);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.uv6qc3t6k {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.74 5.355c-.3 0-.554.207-.623.487c-.02.08.04.157.123.157h1.026c.065 0 .118-.06.104-.125a.644.644 0 0 0-.63-.519");
}

.v2dwqfdba {
  stop-color: var(--svg-color--4079dd, #4079DD);
  stop-opacity: 0;
}

.v2saq3dko {
  d: path("M10.495 5.732a14 14 0 0 1-.027-.662c0-.123.05-.27.148-.343l.074-.074a.49.49 0 0 0 .173-.393v-.392a.24.24 0 0 1 .197-.246c.296-.073.913-.196 1.801-.196s1.505.123 1.801.196a.265.265 0 0 1 .198.246v.392c0 .148.074.295.173.393c.23.162.216.25.197.442c-.006.059-.025.549-.041.662l-.122 1.82c-.074.815-.714 1.382-1.477 1.382h-1.477c-.788 0-1.403-.567-1.477-1.381z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.vaw3u4b-l {
  fill-rule: evenodd;
  d: path("M5.23 14.16c-.306.178-.45.37-.473.425a.415.415 0 0 1-.768-.315c.12-.29.436-.602.824-.828a2.86 2.86 0 0 1 1.58-.382a.415.415 0 0 1-.042.83a2.03 2.03 0 0 0-1.121.27");
}

.vhhvj2t-s {
  stop-color: var(--svg-color--3e98f5, #3E98F5);
}

.vko9wdbzs {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m12.665 5.882l-.244.782c-.05.16.07.322.239.322h.362a.25.25 0 0 0 .24-.322l-.245-.782c-.053-.173-.297-.173-.352 0");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.vx4jfa6qa {
  d: path("M13.814 5.567c.03.04-.032.087-.101.139c-.07.052-.121.089-.15.05c-.03-.04.003-.114.072-.166c.07-.052.15-.062.18-.023");
}

.w5r_v_hxa {
  d: path("M11.836 5.48a.41.41 0 0 0-.396.52h.794a.414.414 0 0 0-.398-.52");
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wg6epmg7n {
  stop-color: var(--svg-color--53adfa, #53ADFA);
}

.wgpnrcbke {
  stop-color: var(--svg-color--ffd135, #FFD135);
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.whspc9bgn {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
  stop-opacity: 0;
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xjp952bfc {
  stop-color: var(--svg-color--ac799e, #AC799E);
}

.xt8_tkusr {
  stop-color: var(--svg-color--e8992d, #E8992D);
}

.xu1e5_bcz {
  stop-color: var(--svg-color--3c92ef, #3C92EF);
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yxuts5vjo {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.84 7.453c-.233 0-.452-.055-.637-.15c-.063-.033-.13.038-.09.095a.87.87 0 0 0 .728.39a.87.87 0 0 0 .728-.39c.04-.06-.028-.128-.091-.096a1.4 1.4 0 0 1-.637.151Z");
}

.z2lhmbb7y {
  stop-color: var(--svg-color--ffc428, #FFC428);
  stop-opacity: 0;
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zgfxq_wdr {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.51c.094-.275.216-.52.266-.61h5.148c.539 1.52-.652 2.926-1.2 3.239c-.978.601-2.891 1.78-3.085 1.898c-.242.149-.512.239-.73.067c-.759-.532-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.699 1.148-1.382 1.265-1.726");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zxijwrkla {
  stop-color: var(--svg-color--ffd23b, #FFD23B);
}

</style>
