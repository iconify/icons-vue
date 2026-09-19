<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#i9lGIGd)" transform="rotate(26.961 19.37 13.47)" class="b1ysgbbus"/><g filter="url(#i5um97d)"><path class="u9h3-mbda"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#iaOH70c)"><path fill="url(#i0yZFVd)" class="sepv3nkwr"/></g><path fill="url(#itYc30S)" class="b1yazzwzl"/><path fill="url(#i4AzWsY)" class="b1yazzwzl"/><path fill="url(#iCUMoEc)" class="of70meq1k"/><path fill="url(#idv3syc)" class="of70meq1k"/><g filter="url(#irQU5dc)"><path fill="url(#iiLGrnb)" class="ga-j-qbpm"/><path fill="url(#irBCE5b)" class="ga-j-qbpm"/><path fill="url(#iOuH9yc)" class="ga-j-qbpm"/></g><g filter="url(#iuGh0Dc)"><path fill="url(#ihTfWPe)" class="vuejbwbij"/><path fill="url(#ieA83vb)" class="vuejbwbij"/></g><path fill="url(#i0488Ae)" class="qexsyge6i"/><path fill="url(#iWGq1Cd)" class="qexsyge6i"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="thhwo06ax"/><path fill="url(#iB3O36Y)" class="ginv3dbis"/><path fill="url(#i2oUhlc)" class="ginv3dbis"/><path fill="url(#iLGf6rd)" class="ginv3dbis"/><g filter="url(#iapGDOc)"><path class="sa73rem9k"/><path fill="url(#ipRtVxG)" class="j88k0lalk"/><path fill="url(#ix89MNd)" class="j88k0lalk"/><path fill="url(#iXt88Ec)" class="j88k0lalk"/></g><g filter="url(#i35Fdzb)"><path fill="url(#iTF2f9h)" class="dc-w_nb2z"/><path fill="url(#iDFUiOc)" class="dc-w_nb2z"/></g><g filter="url(#i6yLU5c)"><path fill="url(#i4iFAyd)" class="xcwnd6bms"/><path fill="url(#iOQGJ1x)" class="xcwnd6bms"/></g><g filter="url(#i8UkwAJ)"><path fill="url(#ikZpzfd)" clip-rule="evenodd" class="y_4pajl7d"/></g><path class="n6nx14b2o"/><path fill="url(#iUb69tc)" class="eikeckbha"/><path fill="url(#iChZRWc)" class="eikeckbha"/><path clip-rule="evenodd" class="d0rf-bclq"/><path fill="url(#iUcCxIc)" clip-rule="evenodd" class="x99s9tbej"/><path clip-rule="evenodd" class="tyifp67am"/><path fill="url(#i00icHe)" clip-rule="evenodd" class="y8eztfbsi"/><path clip-rule="evenodd" class="nypbhiwdj"/><path fill="url(#iuop6Pe)" clip-rule="evenodd" class="t7cma5ywk"/><path clip-rule="evenodd" class="x41u_8htb"/><path fill="url(#ikyprXc)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#itvErnc)" clip-rule="evenodd" class="s4af_bb4s"/><g filter="url(#ijjqwHb)"><path fill="url(#i40rhfb)" class="p3ru7q3ze"/><path fill="url(#iBXH0lc)" class="p3ru7q3ze"/></g><path fill="url(#iPJ2hNc)" class="p3ru7q3ze"/><path fill="url(#io3Gp0b)" clip-rule="evenodd" class="y_4pajl7d"/><path fill="url(#iFCiToc)" class="e8url2b2d"/><path fill="url(#ieyxEyF)" class="gf8f_nbce"/><g filter="url(#i0mAwac)"><path fill="url(#iYAnmZb)" class="k95s_gw4y"/><path fill="url(#iuRranc)" class="k95s_gw4y"/></g><path fill="url(#iCtK4Tb)" class="k95s_gw4y"/><path fill="url(#isn83Me)" class="k95s_gw4y"/><path fill="url(#iIuCAQe)" class="k95s_gw4y"/><path fill="url(#i9Ikorb)" class="k95s_gw4y"/><path fill="url(#iph1pHe)" class="k95s_gw4y"/><path fill="url(#ibrSidb)" class="k95s_gw4y"/><path fill="url(#iCcWgcc)" class="k95s_gw4y"/><g filter="url(#iDp6Xdb)"><path class="p6119bugx"/></g><g filter="url(#iLQSicc)"><path class="de_il1bzv"/><path fill="url(#iN03VNc)" class="foc28jt6s"/><path fill="url(#iDa48ub)" class="foc28jt6s"/><path fill="url(#iqNmcjc)" class="foc28jt6s"/><path fill="url(#iA3DFWb)" class="foc28jt6s"/><path fill="url(#iIGxZYb)" class="foc28jt6s"/></g><g filter="url(#isnrRMb)"><path stroke="url(#irUDrGe)" class="lsrfvnidr"/></g><path fill="url(#ivLF4Md)" class="xl4mq2hgp"/><g filter="url(#icRpiLc)"><path fill="url(#ijdsEzb)" class="hamh28b7y"/><path fill="url(#ipLaB1d)" class="hamh28b7y"/><path fill="url(#i1kuC8A)" class="hamh28b7y"/><path fill="url(#ijZGuyc)" class="hamh28b7y"/><path fill="url(#i4jJjng)" class="hamh28b7y"/></g><g filter="url(#i9QdW1d)"><path class="a9yb0e-0a"/></g><g filter="url(#ijQSLld)"><path class="d8wby4b-y"/></g><g filter="url(#if3bgKo)"><path class="m5n7b5bgb"/><path fill="url(#iIvPa7d)" class="bs0oihbbi"/><path fill="url(#i9eIABd)" class="bs0oihbbi"/></g><g filter="url(#ibLFPse)"><path class="u2ovxwd8u"/><path fill="url(#iWImkpd)" class="hchubu2zj"/><path fill="url(#if5Vdoe)" class="hchubu2zj"/></g><path class="w9-_xu44h"/><path fill="url(#ir0WpPr)" class="c34r-9bhf"/><path class="lp2ezsb6v"/><g filter="url(#ikgp3Hc)"><path class="gtxr20bwp"/><path fill="url(#iNch9Cc)" class="ldbx8j51t"/></g><g filter="url(#iFQYNjb)"><path fill="url(#iJGsdCd)" class="f_8xksb1u"/></g><path class="otia29bau"/><path fill="url(#iHqJtpb)" class="zcct6xbge"/><path class="ufg006bqx"/><g filter="url(#idp9twe)"><path fill="url(#i3hsl3d)" class="qw-vb9mpp"/></g><g filter="url(#iOHlEwc)"><ellipse transform="rotate(-27.914 11.755 5.656)" class="zg25x4bdi"/><ellipse fill="url(#iTeSQre)" transform="rotate(-27.914 11.755 5.656)" class="e-6sy8b_x"/></g><path fill="url(#i62Jwwe)" class="ct3ec-4si"/><path fill="url(#isUdQZb)" class="ct3ec-4si"/><path fill="url(#iRmopie)" class="ct3ec-4si"/><path fill="url(#iCV4upc)" class="ct3ec-4si"/><path fill="url(#iP68vkb)" class="rmbmyac5b"/><path fill="url(#ii9MGyb)" class="rmbmyac5b"/><g filter="url(#izRXC8b)"><path fill="url(#iNM0UOc)" class="zjn6842jg"/></g><g filter="url(#iHAeUfd)"><path fill="url(#iiNKPDd)" class="to70vgv3l"/></g><g filter="url(#ijQxUqc)"><path class="i4g04rb9n"/></g><path fill="url(#iKwvaae)" class="swkdpwiwa"/><path fill="url(#ibe4MHY)" class="swkdpwiwa"/><path fill="url(#iH2gfWY)" class="swkdpwiwa"/><path fill="url(#i0EF3bc)" class="swkdpwiwa"/><g filter="url(#ikscDeu)"><path class="vyhwsac2j"/></g><g filter="url(#iUtSLnd)"><path class="j9f4fjdso"/><path fill="url(#ikDRoLc)" class="hpxf53bap"/></g><defs><radialGradient id="i9lGIGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="bpjbo-5wq"/><stop offset="1" class="fpwanpawi"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="itYc30S" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="i1ugtm59q"/><stop offset="1" class="jcizzuyvv"/></radialGradient><radialGradient id="i4AzWsY" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ita7_2enr"/><stop offset="1" class="xau3og86r"/></radialGradient><radialGradient id="iiLGrnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="gr7jnieaq"/><stop offset="1" class="fni059bsf"/></radialGradient><radialGradient id="irBCE5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="r24pfmh2j"/><stop offset="1" class="jat2c8bpf"/></radialGradient><radialGradient id="iOuH9yc" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="yzedoqb0u"/><stop offset="1" class="f4147fa0n"/></radialGradient><radialGradient id="i0488Ae" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="vinvwq12a"/><stop offset="1" class="aaj8m1ghv"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="iTF2f9h" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="l277r0b8m"/><stop offset="1" class="m1km_jo3a"/></radialGradient><radialGradient id="ikZpzfd" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="ibqq90als"/><stop offset="1" class="enjwdpbad"/></radialGradient><radialGradient id="iUb69tc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="qudtebbqf"/><stop offset="1" class="qle5g2bis"/></radialGradient><radialGradient id="iChZRWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="ew_xbgbtk"/><stop offset=".945" class="za46tubip"/></radialGradient><radialGradient id="iUcCxIc" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="i00icHe" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="iuop6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="ikyprXc" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="itvErnc" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="o9doel8cg"/><stop offset="1" class="b5xboq-mx"/></radialGradient><radialGradient id="i40rhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.479)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="j--7hbfuf"/><stop offset=".81" class="zozrgybxd"/></radialGradient><radialGradient id="iBXH0lc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8437 -6.87502 1.8572 -.49805 18.024 16.393)" gradientUnits="userSpaceOnUse"><stop class="wsjf7pm3j"/><stop offset="1" class="u1162e6xa"/></radialGradient><radialGradient id="iPJ2hNc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.271 8.996)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="x0hdn9b5y"/><stop offset="1" class="eziwjdbdq"/></radialGradient><radialGradient id="io3Gp0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.897 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="y2teulbve"/><stop offset="1" class="rrpkz-bur"/></radialGradient><radialGradient id="iFCiToc" cx="0" cy="0" r="1" gradientTransform="matrix(.33868 .91347 -1.08513 .40233 15.014 6.539)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="ieyxEyF" cx="0" cy="0" r="1" gradientTransform="matrix(.66783 .20989 -.64752 2.06028 10.125 6.76)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iYAnmZb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36463 0 0 -4.18301 14.134 6.113)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iuRranc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 5.892 5.867)scale(1.52384 1.25805)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="isn83Me" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.93355 6.26879 0 12.856 9.47)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="iIuCAQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.51941 .64278 0 13.97 5.52)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="i9Ikorb" cx="0" cy="0" r="1" gradientTransform="matrix(.00178 -.49496 .53863 .00193 11.824 5.54)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="iph1pHe" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 7.105 3.507)scale(3.8505 9.83611)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="ibrSidb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53144 -1.31916 .38966 .45236 9.792 4.877)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iCcWgcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10614 1.12962 -.45156 -.04243 15.373 4.794)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iDa48ub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .11041 -.347 0 13.075 6.729)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iA3DFWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.68804 .31546 -.50697 -1.10573 13.128 6.471)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ivLF4Md" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 22.99 -23.309)scale(1.09976 4.42463)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ipLaB1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.5837 4.00499 0 10.499 4.805)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i1kuC8A" cx="0" cy="0" r="1" gradientTransform="matrix(.05158 -1.13646 2.01359 .0914 15.063 5.398)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ijZGuyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06693 -.70172 .5151 -.78318 14.722 2.56)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="i4jJjng" cx="0" cy="0" r="1" gradientTransform="matrix(.3038 .54198 -1.25495 .70347 12.455 1.84)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iIvPa7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.9956 0 0 -.3695 12.979 2.86)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i9eIABd" cx="0" cy="0" r="1" gradientTransform="matrix(1.45564 -2.30473 2.5534 1.6127 10.408 4.643)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iWImkpd" cx="0" cy="0" r="1" gradientTransform="rotate(-43.614 12.758 -15.271)scale(1.67351 3.06377)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="if5Vdoe" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -26.806 119.18)scale(1.47922 .61932)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ir0WpPr" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36697 -.5837 0 13.851 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iNch9Cc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.279 -.498)scale(.17111 .23556)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHqJtpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36699 -.58374 0 11.877 5.699)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iTeSQre" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22348 .26863 -.0042 11.748 5.798)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isUdQZb" cx="0" cy="0" r="1" gradientTransform="matrix(.2843 1.01466 -.96807 .27125 14.953 5.705)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iRmopie" cx="0" cy="0" r="1" gradientTransform="matrix(.35633 -.489 .40988 .29867 15.116 5.952)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iCV4upc" cx="0" cy="0" r="1" gradientTransform="matrix(.2655 -.70128 .937 .35475 15.167 6.03)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="ii9MGyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75005 0 0 -.83754 10.64 5.995)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iNM0UOc" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 5.065 3.451)scale(.4206 .43124)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iKwvaae" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.333 3.733)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="i0EF3bc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.16 3.2)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><filter id="i5um97d" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="iaOH70c" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="irQU5dc" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.32549 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="iuGh0Dc" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="iapGDOc" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="i35Fdzb" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.231373 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="i6yLU5c" width="2.689" height="5.353" x="25.224" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="i8UkwAJ" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.298039 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.203922 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23226" result="effect2_innerShadow_3987_23226"/></filter><filter id="ijjqwHb" width="7.636" height="9.986" x="11.582" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.215686 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="i0mAwac" width="5.623" height="5.782" x="10.574" y="3.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23226" result="effect2_innerShadow_3987_23226"/></filter><filter id="iDp6Xdb" width="2.79" height="3.312" x="11.405" y="4.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".5"/></filter><filter id="iLQSicc" width="1.049" height="1.512" x="12.34" y="5.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".05"/></filter><filter id="isnrRMb" width="1.756" height=".785" x="11.986" y="7.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".05"/></filter><filter id="icRpiLc" width="5.822" height="4.054" x="9.953" y="1.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23226" result="effect2_innerShadow_3987_23226"/></filter><filter id="i9QdW1d" width="1.113" height=".648" x="13.583" y="4.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="ijQSLld" width="1.113" height=".641" x="11.205" y="4.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><filter id="if3bgKo" width="3.252" height="2.965" x="9.977" y="2.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/><feGaussianBlur result="effect2_foregroundBlur_3987_23226" stdDeviation=".125"/></filter><filter id="ibLFPse" width="3.058" height="2.813" x="12.729" y="2.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".125"/></filter><filter id="ikgp3Hc" width=".465" height=".424" x="13.464" y="5.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".05"/></filter><filter id="iFQYNjb" width=".622" height=".632" x="13.789" y="5.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".1"/></filter><filter id="idp9twe" width=".665" height=".69" x="11.78" y="5.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".1"/></filter><filter id="iOHlEwc" width=".523" height=".428" x="11.493" y="5.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".05"/></filter><filter id="izRXC8b" width=".875" height="1.35" x="9.977" y="5.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".125"/></filter><filter id="iHAeUfd" width="1.428" height="1.861" x="14.6" y="5.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".25"/></filter><filter id="ijQxUqc" width="3.203" height="2.181" x="12.851" y="2.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".375"/></filter><filter id="ikscDeu" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23226" stdDeviation=".25"/></filter><filter id="iUtSLnd" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23226"/></filter><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iWGq1Cd" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="d5idi46tx"/><stop offset="1" class="cf_a3cr-i"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="iDFUiOc" x1="26.313" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="g7p406nqv"/><stop offset="1" class="r52adsb8o"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="i4iFAyd" x1="27.532" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="iCtK4Tb" x1="15.197" x2="14.053" y1="6.876" y2="6.876" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iN03VNc" x1="13.243" x2="12.864" y1="6.418" y2="6.434" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iqNmcjc" x1="12.864" x2="12.864" y1="6.934" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iIGxZYb" x1="12.864" x2="12.864" y1="5.71" y2="5.957" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="irUDrGe" x1="12.321" x2="12.465" y1="7.644" y2="7.267" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ijdsEzb" x1="15.963" x2="10.711" y1="3.552" y2="3.552" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iJGsdCd" x1="14.203" x2="14.061" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3hsl3d" x1="12.214" x2="12.072" y1="5.723" y2="5.811" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i62Jwwe" x1="15.775" x2="15.229" y1="5.735" y2="6.72" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iP68vkb" x1="10.218" x2="10.878" y1="6.054" y2="5.996" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iiNKPDd" x1="15.314" x2="15.314" y1="5.563" y2="6.424" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="ibe4MHY" x1="9.716" x2="13.427" y1="3.92" y2="3.92" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iH2gfWY" x1="13.49" x2="13.49" y1="4.264" y2="4.147" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bouncing-ball-medium-dark" /></template>
<style>
.a9yb0e-0a {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M14.552 4.765a.8.8 0 0 0-.31-.186c-.138-.043-.31-.055-.55-.025a.125.125 0 0 0 .031.249c.218-.027.351-.013.443.016c.09.028.15.074.221.136a.125.125 0 0 0 .165-.19");
}

.aaj8m1ghv {
  stop-color: var(--svg-color--7d4d5e, #7D4D5E);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b1yazzwzl {
  d: path("m11 20.604l.673-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.977-.969c.326-.86 1.06-2.837 1.391-3.875s.81-1.646 1.008-1.82");
}

.b1ysgbbus {
  width: 0.659px;
  height: 1.111px;
  x: 19.37px;
  y: 13.469px;
  rx: 0.33px;
}

.b5xboq-mx {
  stop-color: var(--svg-color--835a58, #835A58);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bpjbo-5wq {
  stop-color: var(--svg-color--6f423e, #6F423E);
}

.bs0oihbbi {
  d: path("M12.97 3.573q-.017-.03-.03-.062a.3.3 0 0 0-.279-.189h-.576a1.52 1.52 0 0 0-1.511 1.528v.125c-.154-.117-.347-.364-.347-.763c0-.485.353-.73.579-.887c.064-.044.117-.08.15-.114L11 3.163c.158-.167.44-.466.931-.597q.12-.03.239-.048c.468-.07.808.349.808.822v.227z");
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c34r-9bhf {
  d: path("M13.852 5.483a.404.404 0 0 1 .39.51h-.78a.405.405 0 0 1 .39-.51");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cf_a3cr-i {
  stop-color: var(--svg-color--7e4d5f, #7E4D5F);
  stop-opacity: 0;
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ct3ec-4si {
  d: path("M15.09 6.72q.046-.722.084-1.444a.728.728 0 0 1-.084 1.444");
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.d0rf-bclq {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.d5idi46tx {
  stop-color: var(--svg-color--7e4d5f, #7E4D5F);
}

.d8wby4b-y {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M11.321 4.716q.062-.038.174-.085c.148-.058.36-.108.613-.077a.125.125 0 1 1-.03.249a1 1 0 0 0-.662.15l-.007.006h-.002a.125.125 0 0 1-.153-.198z");
}

.dc-w_nb2z {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.277-.293c-.162.01-.507-.055-.594-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.568.194a.53.53 0 0 1-.625-.246c-.766-1.312-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.255");
}

.de_il1bzv {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m12.691 5.79l-.24.831c-.05.171.069.343.235.343h.356c.167 0 .284-.174.236-.343l-.24-.831c-.052-.184-.293-.184-.347 0");
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e-6sy8b_x {
  cx: 11.755px;
  cy: 5.656px;
  rx: 0.176px;
  ry: 0.089px;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.e8url2b2d {
  d: path("M15.063 6.679a.74.74 0 0 0 .409-.14v.421c0 .404-.24.764-.606.913q.116-.246.156-.533z");
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.eikeckbha {
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.enjwdpbad {
  stop-color: var(--svg-color--79574b, #79574B);
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ew_xbgbtk {
  stop-color: var(--svg-color--8e695d, #8E695D);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.eziwjdbdq {
  stop-color: var(--svg-color--ff8524, #FF8524);
  stop-opacity: 0;
}

.f_8xksb1u {
  d: path("M14.212 5.834a.4.4 0 0 0-.105-.21l-.118.13l.053.103z");
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.f4147fa0n {
  stop-color: var(--svg-color--ff7447, #FF7447);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fni059bsf {
  stop-color: var(--svg-color--ff6b3f, #FF6B3F);
}

.foc28jt6s {
  d: path("m12.691 5.79l-.24.831c-.05.171.069.343.235.343h.356c.167 0 .284-.174.236-.343l-.24-.831c-.052-.184-.293-.184-.347 0");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.fpwanpawi {
  stop-color: var(--svg-color--703536, #703536);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.g7p406nqv {
  stop-color: var(--svg-color--d0431b, #D0431B);
}

.ga-j-qbpm {
  d: path("m9.12 25.79l.482.61a.27.27 0 0 0 .399.06c.12-.109.433-.272.71-.06c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.104-.165.353-.202.473-.049");
}

.gf8f_nbce {
  d: path("M10.665 6.679a.74.74 0 0 1-.409-.14v.421c0 .404.24.764.607.913a1.9 1.9 0 0 1-.157-.533z");
}

.ginv3dbis {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gr7jnieaq {
  stop-color: var(--svg-color--ff6b38, #FF6B38);
}

.gtxr20bwp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.822 5.568c.03.039-.03.086-.1.137c-.068.05-.118.087-.147.048s.003-.11.072-.162c.068-.05.147-.061.175-.023");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hamh28b7y {
  d: path("M15.06 3.109c.233.08.441.242.573.475c.211.371.18.815-.048 1.143a.7.7 0 0 0-.122.395v.538a.8.8 0 0 0-.302-.122l.036-.726a.656.656 0 0 0-.624-.648h-.633c-.432 0-.823-.255-1-.653a.3.3 0 0 0-.279-.189h-.576a1.52 1.52 0 0 0-1.511 1.529l.014.695a.8.8 0 0 0-.326.12v-.544a.7.7 0 0 0-.122-.395a1.08 1.08 0 0 1-.065-1.106a1.06 1.06 0 0 1 .588-.51c.259-.092.48-.267.626-.502a1.05 1.05 0 0 1 1.307-.413a.67.67 0 0 0 .54 0a1.05 1.05 0 0 1 1.312.427c.14.23.358.398.612.486");
}

.hchubu2zj {
  d: path("m15.222 5.05l-.013-.285a.664.664 0 0 0-.636-.644h-.633c-.402 0-.77-.22-.961-.57c0 0 .326-.936.863-.8c.38.098.784.244 1.103.452c.789.515.692 1.411.277 1.848");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpxf53bap {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.i1ugtm59q {
  stop-color: var(--svg-color--8e625f, #8E625F);
}

.i4g04rb9n {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M14.76 3.553h-.94a.218.218 0 1 1 .034-.435c.245.04.569.094.786.147c.491.122.627.361.665.532a.69.69 0 0 0-.544-.244");
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibqq90als {
  stop-color: var(--svg-color--7c5554, #7C5554);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ita7_2enr {
  stop-color: var(--svg-color--774359, #774359);
  stop-opacity: 0;
}

.j--7hbfuf {
  stop-color: var(--svg-color--ff9128, #FF9128);
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.j88k0lalk {
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.j9f4fjdso {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056c.167.063.314.137.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.096-.855c-.34-.803-.92-1.49-1.734-2.009a4 4 0 0 0-.741-.378");
}

.jat2c8bpf {
  stop-color: var(--svg-color--ff7049, #FF7049);
  stop-opacity: 0;
}

.jcizzuyvv {
  stop-color: var(--svg-color--734840, #734840);
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k95s_gw4y {
  d: path("M10.682 7.364a1.77 1.77 0 0 0 1.757 1.54h.854c.89 0 1.64-.657 1.757-1.54c.053-.852.107-1.7.147-2.552a.656.656 0 0 0-.624-.648h-.633c-.432 0-.823-.255-1-.653a.3.3 0 0 0-.279-.189h-.576a1.52 1.52 0 0 0-1.511 1.528c0 .842.052 1.67.108 2.514");
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.l277r0b8m {
  stop-color: var(--svg-color--ff6836, #FF6836);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.ldbx8j51t {
  d: path("M13.822 5.568c.03.039-.03.086-.1.137c-.068.05-.118.087-.147.048s.003-.11.072-.162c.068-.05.147-.061.175-.023");
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lp2ezsb6v {
  fill: var(--svg-color--000, #000);
  d: path("M13.621 5.887a.23.23 0 0 1 .231-.231a.23.23 0 0 1 .206.337h-.41a.2.2 0 0 1-.027-.106");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lsrfvnidr {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.864 7.423a1.36 1.36 0 0 1-.626-.148c-.062-.032-.129.038-.09.094c.152.23.415.383.716.383c.3 0 .565-.153.716-.383c.04-.058-.027-.126-.09-.094a1.35 1.35 0 0 1-.626.148Z");
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m1km_jo3a {
  stop-color: var(--svg-color--ff5a36, #FF5A36);
}

.m5n7b5bgb {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("M12.97 3.573q-.017-.03-.03-.062a.3.3 0 0 0-.279-.189h-.576a1.52 1.52 0 0 0-1.511 1.528v.125c-.154-.117-.347-.364-.347-.763c0-.485.353-.73.579-.887c.064-.044.117-.08.15-.114L11 3.163c.158-.167.44-.466.931-.597q.12-.03.239-.048c.468-.07.808.349.808.822v.227z");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.n6nx14b2o {
  fill: var(--svg-color--9f7b71, #9F7B71);
  d: path("M11.657 11.705c-.238-1.5.143-2.745.383-3.125c.293-.606.987-.804 1.296-.828h2.438c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.nypbhiwdj {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o9doel8cg {
  stop-color: var(--svg-color--93736e, #93736E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of70meq1k {
  d: path("m11.432 25.15l-.853 2.118l-1.977-.969c.176-.463.47-1.25.755-2.041z");
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.otia29bau {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.783 5.36a.63.63 0 0 0-.613.48c-.02.078.04.153.12.153h1.01a.104.104 0 0 0 .103-.123a.634.634 0 0 0-.62-.51");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p3ru7q3ze {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.48 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.014-2.232.227-2.794");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p6119bugx {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m12.683 5.879l-.268.831c-.045.171.064.342.22.342h.33c.156 0 .265-.174.22-.342l-.224-.831c-.048-.185-.228-.185-.278 0");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.qexsyge6i {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.561 2.437-4.773 2.527");
}

.qle5g2bis {
  stop-color: var(--svg-color--683733, #683733);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qudtebbqf {
  stop-color: var(--svg-color--683733, #683733);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw-vb9mpp {
  d: path("M12.245 5.84c0-.131-.106-.218-.135-.244l-.13.126l.08.163z");
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r24pfmh2j {
  stop-color: var(--svg-color--ff7049, #FF7049);
}

.r52adsb8o {
  stop-color: var(--svg-color--d0431b, #D0431B);
  stop-opacity: 0;
}

.r6n7exbot {
  stop-color: var(--svg-color--7d4348, #7D4348);
  stop-opacity: 0;
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rmbmyac5b {
  d: path("M10.582 5.27a.728.728 0 0 0 .058 1.45q-.043-.724-.058-1.45");
}

.rrpkz-bur {
  stop-color: var(--svg-color--805e51, #805E51);
  stop-opacity: 0;
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s4af_bb4s {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.913 1.13a.415.415 0 1 1-.602-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s6non86-m {
  stop-color: var(--svg-color--7d4348, #7D4348);
}

.sa73rem9k {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.265-.61h5.149c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.892 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sepv3nkwr {
  d: path("M5.527 16.647c.013.613.238 1.167.598 1.588l.897-.892q.093.085.176.178l-.9.895a2.23 2.23 0 0 0 1.586.621q.014.123.017.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765c.422.461.689 1.08.714 1.761a3 3 0 0 1-.25-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.666.65l.778-.773l-1.758-1.918q.088-.09.184-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.671-1.784q.127.005.25.02");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.swkdpwiwa {
  d: path("M9.716 3.302a.1.1 0 0 1 .1-.1h5.925a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.816a.1.1 0 0 1-.1-.1z");
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.t7cma5ywk {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87c.398-.272.941-.49 1.589-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.078.313");
}

.thhwo06ax {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.156-3.015c.378.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .148.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.to70vgv3l {
  d: path("m15.1 6.424l.05-.861a.432.432 0 0 1-.05.86");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.tyifp67am {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.u1162e6xa {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
  stop-opacity: 0;
}

.u2ovxwd8u {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m15.222 5.05l-.013-.285a.664.664 0 0 0-.636-.644h-.633c-.402 0-.77-.22-.961-.57c0 0 .326-.936.863-.8c.38.098.784.244 1.103.452c.789.515.692 1.411.277 1.848");
}

.u9h3-mbda {
  fill: var(--svg-color--876054, #876054);
  d: path("M15.216 10.026q.558-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.15.383c-.125.312-.24.6-.288.801c-.06.258.098.433.404.437a.18.18 0 0 1 .14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .244-.017a.2.2 0 0 1 .172.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.148-.001.346-.008");
}

.ufg006bqx {
  fill: var(--svg-color--000, #000);
  d: path("M12.108 5.887a.23.23 0 0 0-.232-.231a.23.23 0 0 0-.205.337h.409a.23.23 0 0 0 .027-.106");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vinvwq12a {
  stop-color: var(--svg-color--825853, #825853);
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vuejbwbij {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.106-.425l.106-.164a.15.15 0 0 1 .2-.05z");
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vyhwsac2j {
  fill: var(--svg-color--9c776f, #9C776F);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.782-.383c.906 1.672.953 2.774.734 3.618z");
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.w9-_xu44h {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.946 5.36a.63.63 0 0 1 .612.48a.124.124 0 0 1-.12.153h-1.01a.104.104 0 0 1-.103-.123a.63.63 0 0 1 .62-.51");
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wsjf7pm3j {
  stop-color: var(--svg-color--ff6e44, #FF6E44);
}

.x0hdn9b5y {
  stop-color: var(--svg-color--ffa61d, #FFA61D);
}

.x41u_8htb {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.x99s9tbej {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.696-.451c.391-.605 1.214-.814 2.135-.657a.415.415 0 1 1-.14.819");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xau3og86r {
  stop-color: var(--svg-color--774359, #774359);
}

.xcwnd6bms {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.907 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.187-.085z");
}

.xl4mq2hgp {
  d: path("M12.864 7.423a1.36 1.36 0 0 1-.626-.148c-.062-.032-.129.038-.09.094c.152.23.415.383.716.383c.3 0 .565-.153.716-.383c.04-.058-.027-.126-.09-.094a1.35 1.35 0 0 1-.626.148");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y_4pajl7d {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.768.435-1.654.656-2.381.773c-.257.041-.503.07-.729.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.y2teulbve {
  stop-color: var(--svg-color--805e51, #805E51);
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.y8eztfbsi {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 1 1-.042.829a2.03 2.03 0 0 0-1.12.27");
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.yzedoqb0u {
  stop-color: var(--svg-color--ff7447, #FF7447);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.za46tubip {
  stop-color: var(--svg-color--8e695d, #8E695D);
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zcct6xbge {
  d: path("M11.876 5.483a.404.404 0 0 0-.389.51h.78a.406.406 0 0 0-.39-.51");
}

.zg25x4bdi {
  cx: 11.755px;
  cy: 5.656px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.zjn6842jg {
  d: path("M10.564 5.571a.432.432 0 0 0 .038.85a35 35 0 0 1-.038-.85");
}

.zozrgybxd {
  stop-color: var(--svg-color--ed5722, #ED5722);
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

</style>
