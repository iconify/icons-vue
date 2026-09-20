<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vfysoi1xv"/><path class="jbs0u92hw"/><path class="zj5-kpbeh"/><path class="l1at_dbku"/><path class="iczq0cb_x"/><path class="lc_h1o2lt"/><path class="vykib43iq"/><path class="xmyfwqbyu"/><path class="d1pphqfik"/><path class="vlz-evhuk"/><path class="vowttebqm"/><path class="fus8l09xd"/><path class="fpcbfabvj"/><path class="ig1j9flni"/><path class="erixxj5jh"/><path class="hnjz0olkp"/><path class="qiamhc5wv"/><path class="um9lyob5h"/><path class="ye3z92bnj"/><path class="crl7s9buq"/><path class="tr2pfzbfc"/><path class="saqgz8b6z"/><path class="l3-ibrbyb"/><path class="y_7ft4b_w"/><path class="omuoz_bdj"/><path class="mwdjejb7r"/><path class="aoi5lmbhk"/><path class="rxwu76bxd"/><path class="btjgg9svj"/><path class="syziv7bwn"/><path class="ek8ibwvgm"/><path class="swau86eut"/><path class="g_ch3-byy"/><path class="t41mokbmo"/><path class="odmdambax"/><path class="d2948zbwi"/><path class="orq_8dcbl"/><path class="i8h6ebb3s"/><path class="ncjo046st"/><path class="cmk5tobhi"/><path class="ty1-ks0wo"/><path class="kgw-0vb0t"/><path class="k_zk5el2r"/><path class="z3f_wmz1k"/><path class="lgrp0hb5x"/><path class="ax_11cb7y"/><path class="ceb11acfy"/><path class="vv1cu23ka"/><path class="tck6-x9jh"/><path class="b5k3tbbhz"/><path class="w393iheox"/><path class="sy_-vr-uf"/><path class="s3ggt0-9o"/><path class="op-nx27ch"/><path class="sr6rxj6-r"/><path class="sutfk43ui"/><path class="jo0dzeb4v"/><path class="y45p-no7f"/><path class="pz-wk2bgd"/><path class="z79z5nbnb"/><path class="iqww10bfy"/><path class="ecod-msqt"/><path class="czcxmepiu"/><path class="eiq4icysa"/><path class="jnj8fjb0z"/><path class="vqgh07fig"/><path class="epyq09gnm"/><path class="moimzmpqv"/><path class="j2rifn83j"/><path class="wmivy5lbv"/><path class="x91carhzd"/><path class="hmazegrbt"/><path class="wxngvebht"/><path class="pnziwac9a"/><path class="n4pm8120q"/><path class="br7ebu4zj"/><path class="z5ndmon-p"/><path class="qyuu4d3kl"/><path class="ky0an4x7l"/><path class="wzp94bccf"/><path class="xfhpkcbjd"/><path class="hjmoq4okm"/><path class="icsh4tbuv"/><path class="pjlw5u6os"/><path class="sz-n3obtf"/><path class="q7g35ybkj"/><path class="z8eo16i8s"/><path class="bdurf793h"/><path class="ljsxh8bmf"/><path class="v9kyoob2z"/><path class="ukthf7bne"/><path class="aymr5bcxj"/><path class="q0chrlk_r"/><path class="afgzk6bwd"/><path class="b_2m96wku"/><path class="eybp01aem"/><path class="v_6j5_bzg"/><path class="sebc6kk-q"/><path class="tu1uyvbvd"/><path class="p98t9ibbq"/><path class="sipv73c_l"/><path class="bkf9f0bam"/><path class="vdnjis4zn"/><path class="qc3fyi3gi"/><path class="lym78tbyh"/><path class="o2otmfbbq"/><path class="ambff_bcq"/><path class="v-d4qkcab"/><path class="jmitu6yiz"/><path class="mz8v8eboq"/><path class="h2jwh-viv"/><path class="co6hnlb8y"/><path class="huoilsb8l"/><path class="q3mubewzp"/><path class="ormxxf29e"/><path class="x7mezqhdq"/><path class="x98af8y3s"/><path class="gzd9q0qfo"/><path class="t-2qyzbkw"/><path class="lof2c6q6f"/><path class="g1pmnmb1a"/><path class="k_731ibom"/><path class="c-i2lrl6r"/><path class="wq21gubql"/><path class="ky96unb8t"/><path class="sjclw_nrh"/><path class="gzu4gsbdi"/><path class="jj2qr4bqq"/><path class="s-4kt85on"/><path class="affiinb6i"/><path class="n5n7wkbhk"/><path class="v67jwzbhy"/><path class="fbg6o9bxy"/><path class="n5strjkrd"/><path class="d7kveab1n"/><path class="nc79_zbed"/><path class="eilj8acxh"/><path class="s2dxghmyx"/><path class="ljtm4qynr"/><path class="m1yb67kbq"/><path class="o_bnlu0qx"/><path class="oichb-b-r"/><path class="ctg141b7k"/><path class="yn3y5vsyc"/><path class="oiqigljnh"/><path class="lvc0odbgj"/><path class="a7elocfoc"/><path class="bvt1dp5pv"/><path class="e1ac-l1ai"/><path class="h4gd1crvr"/><path class="yy3mulbls"/><path class="gimk_2-vn"/><path class="agn437hve"/><path class="xphp8vebp"/><path class="ytv_ek9-l"/><path class="vqb81ccfw"/><path class="i3xd4y-2c"/><path class="eo8jmbc5w"/><path class="jqh11ilwk"/><path class="baksrwbwl"/><path class="x7kk72paq"/><path class="e40du1b_x"/><path class="r49fnmt5f"/><path class="eaa9n6b4v"/><path class="b9jzx0xpl"/><path class="ymre0zp_n"/><path class="eopvutc9c"/><path class="pibgdm2so"/><path class="f-kj2cczv"/><path class="tym128b8b"/><path class="cakb76bpk"/><path class="tmcdq12si"/><path class="dss03vbjr"/><path class="siqmc6b9u"/><path class="zh8fepbjd"/><path class="byo_g9ymf"/><path class="ihjx5wb_r"/><path class="rar8gzqvo"/><path class="z-dec2ebb"/><path class="putf54tst"/><path class="bio_c2brc"/><path class="fq4poubzd"/><path class="a0v31ebtj"/><path class="o9rdllb7r"/><path class="ghveeyb4e"/><path class="lb1a8fb2t"/><path clip-rule="evenodd" class="pmoo2c33x"/><path clip-rule="evenodd" class="ayllsv2ed"/><path clip-rule="evenodd" class="wfob4mb9u"/><path clip-rule="evenodd" class="bziz0lbvo"/><path clip-rule="evenodd" class="trj3l7w0f"/><path clip-rule="evenodd" class="ws4q350jk"/><path clip-rule="evenodd" class="o7t329vkd"/><path clip-rule="evenodd" class="scs4eyvza"/><path clip-rule="evenodd" class="q9gcn29mt"/><path clip-rule="evenodd" class="svbyywwfy"/><path clip-rule="evenodd" class="jtqpsxbop"/><path clip-rule="evenodd" class="kvpylabdd"/><path clip-rule="evenodd" class="cvpv-7xhg"/><path clip-rule="evenodd" class="b5bh5eixf"/><path clip-rule="evenodd" class="w_-geeb9v"/><path clip-rule="evenodd" class="s0cgqqbug"/><path clip-rule="evenodd" class="dkhj3dbbk"/><path clip-rule="evenodd" class="zyxuu2b-e"/><path clip-rule="evenodd" class="o6-2mszsw"/><path clip-rule="evenodd" class="h1jfh9bsr"/><path clip-rule="evenodd" class="u1w_w6g3e"/><path clip-rule="evenodd" class="qubwtbcuy"/><path clip-rule="evenodd" class="y09w_ftul"/><path clip-rule="evenodd" class="i7fyy7blg"/><path clip-rule="evenodd" class="jswducbfa"/><path clip-rule="evenodd" class="sd6djzeyn"/><path clip-rule="evenodd" class="ekat1dbzl"/><path clip-rule="evenodd" class="a96ikzble"/><path clip-rule="evenodd" class="glwx5vbjo"/><path clip-rule="evenodd" class="mgk7b213p"/><path clip-rule="evenodd" class="xiz-tacvm"/><path clip-rule="evenodd" class="y5vnbsbku"/><path clip-rule="evenodd" class="dme8r3bvt"/><path clip-rule="evenodd" class="dsbuwc9hp"/><path clip-rule="evenodd" class="vqqtqgbtk"/><path clip-rule="evenodd" class="uph4zcb0e"/><path clip-rule="evenodd" class="qaytl3zjj"/><path clip-rule="evenodd" class="r5bt8lbni"/><path clip-rule="evenodd" class="leodchb_a"/><path clip-rule="evenodd" class="ckceyxb2r"/><path clip-rule="evenodd" class="mqh47cbgi"/><path clip-rule="evenodd" class="e47ejnfei"/><path clip-rule="evenodd" class="jie31jo_r"/><path clip-rule="evenodd" class="omfr0kbpj"/><path clip-rule="evenodd" class="fp791oeap"/><path clip-rule="evenodd" class="ulnl41b9b"/><path clip-rule="evenodd" class="se3iwyb9j"/><path clip-rule="evenodd" class="x6nsc9l_h"/><path clip-rule="evenodd" class="km6z0vb6u"/><path clip-rule="evenodd" class="uwy21lbck"/><path clip-rule="evenodd" class="t7v074pgs"/><path clip-rule="evenodd" class="o3dw4_brw"/><path clip-rule="evenodd" class="ibyi_3u7s"/><path clip-rule="evenodd" class="la36h0b4g"/><path clip-rule="evenodd" class="fpvm38b1h"/><path clip-rule="evenodd" class="b2divgfrt"/><path clip-rule="evenodd" class="jvurh4evr"/><path clip-rule="evenodd" class="x87m27bet"/><path clip-rule="evenodd" class="jybke5b4r"/><path clip-rule="evenodd" class="nz-ismbka"/><path clip-rule="evenodd" class="wkpnuub7v"/><path clip-rule="evenodd" class="stce3abwu"/><path clip-rule="evenodd" class="gi1k-gbkp"/><path clip-rule="evenodd" class="jdgiutijv"/><path clip-rule="evenodd" class="pb8aimbgn"/><path clip-rule="evenodd" class="qyq02kwao"/><path clip-rule="evenodd" class="p376gdbol"/><path clip-rule="evenodd" class="qb7um1ohk"/><path clip-rule="evenodd" class="schgaemdv"/><path clip-rule="evenodd" class="v-wiy-k3s"/><path clip-rule="evenodd" class="c2cenp7op"/><path clip-rule="evenodd" class="afx3l-bib"/><path clip-rule="evenodd" class="w7hbqgiiz"/><path clip-rule="evenodd" class="wrkgoihru"/><path clip-rule="evenodd" class="fb_d10caj"/><path clip-rule="evenodd" class="kbm32ab0g"/><path clip-rule="evenodd" class="ykv54_b7l"/><path clip-rule="evenodd" class="tikmb2bzw"/><path clip-rule="evenodd" class="oga632z0p"/><path clip-rule="evenodd" class="gdqaickxp"/><path clip-rule="evenodd" class="tdp90n2gs"/><path clip-rule="evenodd" class="kvh5v4ajn"/><path clip-rule="evenodd" class="juambp63a"/><path clip-rule="evenodd" class="w5ehjrbph"/><path clip-rule="evenodd" class="oks708buj"/><path clip-rule="evenodd" class="x-h0kx1ld"/><path clip-rule="evenodd" class="d6jz3-6tq"/><path clip-rule="evenodd" class="ilvd1i45x"/><path clip-rule="evenodd" class="rhzcklb5m"/><path clip-rule="evenodd" class="vshpaab4d"/><path clip-rule="evenodd" class="yphiwmb5h"/><path clip-rule="evenodd" class="qeyarhb6o"/><path clip-rule="evenodd" class="u5ljsmbgi"/><path clip-rule="evenodd" class="uign7rkag"/><path clip-rule="evenodd" class="x-d5i6blm"/><path clip-rule="evenodd" class="xnfpfdbiq"/><path clip-rule="evenodd" class="fl8el2c_o"/><path clip-rule="evenodd" class="otgmowbhn"/><path clip-rule="evenodd" class="rhve0sbqw"/><path clip-rule="evenodd" class="k2kmipn8r"/><path clip-rule="evenodd" class="gwnah6zkt"/><path clip-rule="evenodd" class="ojj5bubie"/><path clip-rule="evenodd" class="whdyz6b6v"/><path clip-rule="evenodd" class="dbod5_ceq"/><path clip-rule="evenodd" class="vg7x4n7ns"/><path clip-rule="evenodd" class="if0rohh5u"/><path clip-rule="evenodd" class="t8y6_-6yi"/><path clip-rule="evenodd" class="nhz99er3i"/><path clip-rule="evenodd" class="ypoq-c_3x"/><path clip-rule="evenodd" class="qei088bvc"/><path clip-rule="evenodd" class="sdm_ye1pb"/><path clip-rule="evenodd" class="wk8cmum2x"/><path clip-rule="evenodd" class="y_sr07bjn"/><path clip-rule="evenodd" class="kwc6dobty"/><path clip-rule="evenodd" class="qvhouba6u"/><path clip-rule="evenodd" class="psm6y8a0c"/><path clip-rule="evenodd" class="mhpblzo_x"/><path clip-rule="evenodd" class="j8nzh3tvt"/><path clip-rule="evenodd" class="i0atby0uh"/><path clip-rule="evenodd" class="tprxwacyb"/><path clip-rule="evenodd" class="f855mgbef"/><path clip-rule="evenodd" class="o-c59sbos"/><path clip-rule="evenodd" class="z23ylqbzf"/><path clip-rule="evenodd" class="wuegoqbfe"/><path clip-rule="evenodd" class="rahvrmbqn"/><path clip-rule="evenodd" class="pfu14ij6r"/><path clip-rule="evenodd" class="v48t_da8v"/><path clip-rule="evenodd" class="idpm2x3ul"/><path clip-rule="evenodd" class="qy3f-6bin"/><path clip-rule="evenodd" class="vc9c_cbsy"/><path clip-rule="evenodd" class="mc0pstisx"/><path clip-rule="evenodd" class="nshhojsln"/><path clip-rule="evenodd" class="b0a1ktthc"/><path clip-rule="evenodd" class="k2ma-8tdb"/><path clip-rule="evenodd" class="giliicbzs"/><path clip-rule="evenodd" class="zkf506b0j"/><path clip-rule="evenodd" class="pajvmv7bh"/><path clip-rule="evenodd" class="rnsc-abrr"/><path clip-rule="evenodd" class="u2jg5135p"/><path clip-rule="evenodd" class="qvh3kkh9d"/><path clip-rule="evenodd" class="h8m_4ybch"/><path clip-rule="evenodd" class="vrw2l3g0j"/><path clip-rule="evenodd" class="pid2ybbmy"/><path clip-rule="evenodd" class="xvu5g6bil"/><path clip-rule="evenodd" class="ey5zq05ye"/><path clip-rule="evenodd" class="ark31_j-d"/><path clip-rule="evenodd" class="h5_gi28bt"/><path clip-rule="evenodd" class="dtpx08gdw"/><path clip-rule="evenodd" class="p2ulb8bqq"/><path clip-rule="evenodd" class="s-n4rwbex"/><path clip-rule="evenodd" class="n61ivhbzt"/><path clip-rule="evenodd" class="huzsjubss"/><path clip-rule="evenodd" class="i-m7q6q6j"/><path clip-rule="evenodd" class="p06qsjhti"/><path clip-rule="evenodd" class="q92z20b_u"/><path clip-rule="evenodd" class="v5qgmob_h"/><path clip-rule="evenodd" class="nyta4nb7t"/><path clip-rule="evenodd" class="rmd56ogjy"/><path clip-rule="evenodd" class="v30ut-rsp"/><path clip-rule="evenodd" class="i0uiq-zpt"/><path clip-rule="evenodd" class="fla-ut-ii"/><path clip-rule="evenodd" class="ky1k3sbha"/><path clip-rule="evenodd" class="zyx96-z4y"/><path clip-rule="evenodd" class="sl6z8u2rw"/><path clip-rule="evenodd" class="cqmr9pbnu"/><path clip-rule="evenodd" class="nl27ce-bf"/><path clip-rule="evenodd" class="yvrr_ii0o"/><path clip-rule="evenodd" class="x5tx1qr7u"/><path clip-rule="evenodd" class="qunr_1bkp"/><path clip-rule="evenodd" class="g-fyifbdy"/><path clip-rule="evenodd" class="vgxxbz7ih"/><path clip-rule="evenodd" class="mgnm37jmd"/><path clip-rule="evenodd" class="r9uzwbbcs"/><path clip-rule="evenodd" class="mnubg9bsc"/><path clip-rule="evenodd" class="f2_br5bck"/><path clip-rule="evenodd" class="a_84hrmzg"/><path clip-rule="evenodd" class="gwo5aojch"/><path clip-rule="evenodd" class="nway9h1kv"/><path clip-rule="evenodd" class="fhqd7obtz"/><path clip-rule="evenodd" class="licrn-k7w"/><path clip-rule="evenodd" class="sivg0zwbo"/><path clip-rule="evenodd" class="l_o-f9btf"/><path clip-rule="evenodd" class="klwe4ccwa"/><path clip-rule="evenodd" class="n2wlfmbfk"/><path clip-rule="evenodd" class="kr4drwbxo"/><path clip-rule="evenodd" class="qm-ao_uhv"/><path clip-rule="evenodd" class="znzftmxyk"/><path clip-rule="evenodd" class="f0kt-4bwk"/><path clip-rule="evenodd" class="ugzq3rbnn"/><path clip-rule="evenodd" class="fi9z1wb1g"/><path clip-rule="evenodd" class="ci2h3wbbf"/><path clip-rule="evenodd" class="r9ap17b_m"/><path clip-rule="evenodd" class="g7jd0dk0z"/><path clip-rule="evenodd" class="m9-wywbnq"/><path clip-rule="evenodd" class="s4mbxwb9z"/><path clip-rule="evenodd" class="anni_ybyo"/><path clip-rule="evenodd" class="l5ywv3bfg"/><path clip-rule="evenodd" class="ebat8dt4s"/><path clip-rule="evenodd" class="yq4nn8bim"/><path clip-rule="evenodd" class="imringo3u"/><path clip-rule="evenodd" class="ezlp50aqs"/><path clip-rule="evenodd" class="rorrkqcvp"/><path clip-rule="evenodd" class="zhds1vbgi"/><path clip-rule="evenodd" class="fq10ayqqx"/><path clip-rule="evenodd" class="yjls5qngb"/><path clip-rule="evenodd" class="k_36xlb4g"/><path clip-rule="evenodd" class="s38w7zb3d"/><path clip-rule="evenodd" class="o4khypb4q"/><path clip-rule="evenodd" class="zfnyub_ub"/><path clip-rule="evenodd" class="qevd3o9mp"/><path clip-rule="evenodd" class="a2a3qwnzr"/><path clip-rule="evenodd" class="pplnw6u2v"/><path clip-rule="evenodd" class="s4c_fyvao"/><path clip-rule="evenodd" class="gs2-83wkd"/><path clip-rule="evenodd" class="qj0aiwiax"/><path clip-rule="evenodd" class="tfo08ed-y"/><path clip-rule="evenodd" class="au5q_fbvx"/><path clip-rule="evenodd" class="l9e0uew8q"/><path clip-rule="evenodd" class="zoi2u7b_g"/><path clip-rule="evenodd" class="nhs_92buk"/><path clip-rule="evenodd" class="b_reh1g7i"/><path clip-rule="evenodd" class="b_o7xsdqr"/><path clip-rule="evenodd" class="s8gv6ibpi"/><path clip-rule="evenodd" class="ajfr4bgya"/><path clip-rule="evenodd" class="m2sp0pbdy"/><path clip-rule="evenodd" class="w3dyk7b9i"/><path clip-rule="evenodd" class="lqb5utbfh"/><path clip-rule="evenodd" class="b47vym4to"/><path clip-rule="evenodd" class="vr3roybgd"/><path clip-rule="evenodd" class="nw98hcc0d"/><path clip-rule="evenodd" class="azamjbc3o"/><path clip-rule="evenodd" class="r_91roc1d"/><path clip-rule="evenodd" class="n8fmx8b_m"/><path clip-rule="evenodd" class="hs14ufbpx"/><path clip-rule="evenodd" class="dtrbitbio"/><path clip-rule="evenodd" class="mfcjhk93x"/><path clip-rule="evenodd" class="tl15kqbwi"/><path clip-rule="evenodd" class="n1t83fb2v"/><path clip-rule="evenodd" class="q2g5vacan"/><path clip-rule="evenodd" class="u_10aikjr"/><path clip-rule="evenodd" class="qqxwl7rsb"/><path clip-rule="evenodd" class="kyzg6rbga"/><path clip-rule="evenodd" class="jm0rhs02l"/><path clip-rule="evenodd" class="dk-59wz8v"/><path clip-rule="evenodd" class="csg_mibem"/><path clip-rule="evenodd" class="zepdvodcl"/><path clip-rule="evenodd" class="hs24uacxj"/><path clip-rule="evenodd" class="qkjcdc3ur"/><path clip-rule="evenodd" class="ev4uf98uv"/><path clip-rule="evenodd" class="a51wi0b3a"/><path clip-rule="evenodd" class="okqnlp-or"/><path clip-rule="evenodd" class="hkj4t1u6c"/><path clip-rule="evenodd" class="ecu2q7bpm"/><path clip-rule="evenodd" class="eyhwi4bcp"/><path clip-rule="evenodd" class="hm1f3eg9z"/><path clip-rule="evenodd" class="w77z-8bdo"/><path clip-rule="evenodd" class="pe70w77hz"/><path clip-rule="evenodd" class="s2cq7no3c"/><path clip-rule="evenodd" class="tswse19rn"/><path clip-rule="evenodd" class="qq203hbmr"/><path clip-rule="evenodd" class="mpittkwhi"/><path clip-rule="evenodd" class="eo1_okb4c"/><path clip-rule="evenodd" class="lb7oibbvo"/><path clip-rule="evenodd" class="n-r2y3blv"/><path clip-rule="evenodd" class="ympds1blj"/><path clip-rule="evenodd" class="ymtw_38sy"/><path clip-rule="evenodd" class="ktvgtpbsy"/><path clip-rule="evenodd" class="o2bmuvn7z"/><path clip-rule="evenodd" class="dn96kmbna"/><path clip-rule="evenodd" class="bldaqmb7y"/><path clip-rule="evenodd" class="yast61byh"/><path clip-rule="evenodd" class="pmb16_bud"/><path clip-rule="evenodd" class="yrs9h26yx"/><path clip-rule="evenodd" class="usmfcgbev"/><path clip-rule="evenodd" class="zxl-_3bfr"/><path clip-rule="evenodd" class="y-h0_qbnu"/><path clip-rule="evenodd" class="tsqfsuqex"/><path clip-rule="evenodd" class="f3xqy9bij"/><path clip-rule="evenodd" class="ye0ik5ygl"/><path clip-rule="evenodd" class="em6u7-b2j"/><path clip-rule="evenodd" class="jcek_sb1s"/><path clip-rule="evenodd" class="gf0gvk3bf"/><path clip-rule="evenodd" class="ve401_bwh"/><path clip-rule="evenodd" class="l7ydjqned"/><path clip-rule="evenodd" class="vd7cxu88n"/><path clip-rule="evenodd" class="wv3xxachh"/><path clip-rule="evenodd" class="f-enilymz"/><path clip-rule="evenodd" class="k8suc3uie"/><path clip-rule="evenodd" class="nyj23wb5l"/><path clip-rule="evenodd" class="n87lqc7li"/><path clip-rule="evenodd" class="f3simhb6a"/><path clip-rule="evenodd" class="g2n7a1q1h"/><path clip-rule="evenodd" class="h7gtas8gd"/><path clip-rule="evenodd" class="t0pxxfbgx"/><path clip-rule="evenodd" class="tech0p74h"/><path clip-rule="evenodd" class="tt_kt0bmk"/><path clip-rule="evenodd" class="v47pq1b4b"/><path clip-rule="evenodd" class="dskjicfja"/><path clip-rule="evenodd" class="rtwurzbli"/><path clip-rule="evenodd" class="tf4kajl0o"/><path clip-rule="evenodd" class="rlzeo9b0o"/><path clip-rule="evenodd" class="p8u21o0_d"/><path clip-rule="evenodd" class="y8dbadcsn"/><path clip-rule="evenodd" class="je4x5wzzu"/><path clip-rule="evenodd" class="ykdancbjs"/><path clip-rule="evenodd" class="l_7g_o6ix"/><path clip-rule="evenodd" class="p9q8udrth"/><path clip-rule="evenodd" class="njfguab5u"/><path clip-rule="evenodd" class="dlokk8s7q"/><path clip-rule="evenodd" class="me5uy0u_v"/><path clip-rule="evenodd" class="cnv1o1b0s"/><path clip-rule="evenodd" class="joxg4fb8s"/><path clip-rule="evenodd" class="zyjvqhb4r"/><path clip-rule="evenodd" class="rhstltbom"/><path clip-rule="evenodd" class="q2-mm2bhg"/><path clip-rule="evenodd" class="yiiytzbrf"/><path clip-rule="evenodd" class="u2z27j8cp"/><path clip-rule="evenodd" class="bw_d66bci"/><path clip-rule="evenodd" class="g8ife4b1z"/><path clip-rule="evenodd" class="ipqcobbrn"/><path clip-rule="evenodd" class="mw-nl4y6h"/><path clip-rule="evenodd" class="mnf48zopy"/><path clip-rule="evenodd" class="m12fn3rtc"/><path clip-rule="evenodd" class="d1-36pjav"/><path clip-rule="evenodd" class="x19x-8zqw"/><path clip-rule="evenodd" class="detbz5byy"/><path clip-rule="evenodd" class="ta6llroom"/><path clip-rule="evenodd" class="t47g_rb9f"/><path clip-rule="evenodd" class="lzeayqbcx"/><path clip-rule="evenodd" class="ryzzfoa5q"/><path clip-rule="evenodd" class="xewd2gbpl"/><path clip-rule="evenodd" class="beu6nkzjp"/><path clip-rule="evenodd" class="am_ycibqp"/><path clip-rule="evenodd" class="c80ytfqxg"/><path clip-rule="evenodd" class="zvu2scqtd"/><path clip-rule="evenodd" class="isvdl_xvb"/><path clip-rule="evenodd" class="pt07vpb4g"/><path clip-rule="evenodd" class="yi8a_ccvk"/><path clip-rule="evenodd" class="hd7gu9ngl"/><path clip-rule="evenodd" class="inygyabes"/><path clip-rule="evenodd" class="njf23acfs"/><path clip-rule="evenodd" class="peko-tfeq"/><path clip-rule="evenodd" class="gmyoz9boz"/><path clip-rule="evenodd" class="b9f6r2_wy"/><path clip-rule="evenodd" class="mfadjdb3x"/><path clip-rule="evenodd" class="x2m_v4bra"/><path clip-rule="evenodd" class="o3ys5acen"/><path clip-rule="evenodd" class="jy64fdc7y"/><path clip-rule="evenodd" class="alg3wdbji"/><path clip-rule="evenodd" class="c-prx813i"/><path clip-rule="evenodd" class="qb-cx5zii"/><path clip-rule="evenodd" class="z4rnmacse"/><path clip-rule="evenodd" class="y9hgrzhfa"/><path clip-rule="evenodd" class="dpv6eqbek"/><path clip-rule="evenodd" class="sbetwybrr"/><path clip-rule="evenodd" class="dua6arovl"/><path clip-rule="evenodd" class="sgw__0elo"/><path clip-rule="evenodd" class="lp17yqbes"/><path clip-rule="evenodd" class="h5svexb0w"/><path clip-rule="evenodd" class="dvpbl-bmj"/><path clip-rule="evenodd" class="hw8q4wb2n"/><path clip-rule="evenodd" class="yr4nlgssq"/><path clip-rule="evenodd" class="vxvcbbm3s"/><path clip-rule="evenodd" class="woincyj1b"/><path clip-rule="evenodd" class="ekhddab6a"/><path clip-rule="evenodd" class="n763jcc6m"/><path clip-rule="evenodd" class="v-oj91b5n"/><path clip-rule="evenodd" class="ub3rip0da"/><path clip-rule="evenodd" class="i_u19jbbp"/><path clip-rule="evenodd" class="svp2d2bpm"/><path clip-rule="evenodd" class="elr1r5bho"/><path clip-rule="evenodd" class="o76l24bby"/><path clip-rule="evenodd" class="s1jdotb-c"/><path clip-rule="evenodd" class="i-88xtb5c"/><path clip-rule="evenodd" class="sprpy1bet"/><path clip-rule="evenodd" class="pb8bgacko"/><path clip-rule="evenodd" class="m8bygetzl"/><path clip-rule="evenodd" class="w3vogzboo"/><path clip-rule="evenodd" class="zwpvmocrp"/><path clip-rule="evenodd" class="n4pwgf5jj"/><path clip-rule="evenodd" class="ol2rwjbqc"/><path clip-rule="evenodd" class="c0b8r9j5h"/><path clip-rule="evenodd" class="phvlcxnrd"/><path clip-rule="evenodd" class="gwiu2jeok"/><path clip-rule="evenodd" class="vd3so5bmv"/><path clip-rule="evenodd" class="fk_uxs10t"/><path clip-rule="evenodd" class="aaf5ucmxx"/><path clip-rule="evenodd" class="ewqtpfb9f"/><path clip-rule="evenodd" class="j207lm_3s"/><path clip-rule="evenodd" class="f7f0h6bsr"/><path clip-rule="evenodd" class="n_55og-dr"/><path clip-rule="evenodd" class="ud8fgib8b"/><path clip-rule="evenodd" class="c8kuuhbbi"/><path clip-rule="evenodd" class="mhrzb2b-d"/><path clip-rule="evenodd" class="qsczu9btu"/><path clip-rule="evenodd" class="mqdptmntf"/><path clip-rule="evenodd" class="zggt9ulgm"/><path clip-rule="evenodd" class="kdi-96bhl"/><path clip-rule="evenodd" class="hx5wfibca"/><path clip-rule="evenodd" class="ajpd0eb_v"/><path clip-rule="evenodd" class="x-lj-80lr"/><path clip-rule="evenodd" class="hcf307bho"/><path clip-rule="evenodd" class="f6udpobyg"/><path clip-rule="evenodd" class="opbz2cbmd"/><path clip-rule="evenodd" class="bbzqbebjj"/><path clip-rule="evenodd" class="gz4eqpbnz"/><path clip-rule="evenodd" class="q0-ifn_xb"/><path clip-rule="evenodd" class="k-pngxtkr"/><path clip-rule="evenodd" class="j35w48thc"/><path clip-rule="evenodd" class="hcgi67b0p"/><path clip-rule="evenodd" class="ltpcsvrco"/><path clip-rule="evenodd" class="q-x4x8acu"/><path clip-rule="evenodd" class="zc0pgkbae"/><path clip-rule="evenodd" class="qr_s-o-1i"/><path clip-rule="evenodd" class="a2fibtbel"/><path clip-rule="evenodd" class="de70vob3d"/><path clip-rule="evenodd" class="coo6lkcev"/><path clip-rule="evenodd" class="ysvzg5wob"/><path clip-rule="evenodd" class="gchc1lxbw"/><path clip-rule="evenodd" class="ybmhq6b3e"/><path clip-rule="evenodd" class="gpdamfbob"/><path clip-rule="evenodd" class="oo60gkbfh"/><path clip-rule="evenodd" class="k24gqnbsr"/><path clip-rule="evenodd" class="gpkh8ac6m"/><path clip-rule="evenodd" class="dd4b27c8v"/><path clip-rule="evenodd" class="zop65imip"/><path clip-rule="evenodd" class="lzfaag06g"/><path clip-rule="evenodd" class="vz7zibbft"/><path clip-rule="evenodd" class="n39l4h1_m"/><path clip-rule="evenodd" class="na5sj2b_p"/><path clip-rule="evenodd" class="vhvsdhbgx"/><path clip-rule="evenodd" class="ujnvzhbhz"/><path clip-rule="evenodd" class="ow6dn9ybs"/><path clip-rule="evenodd" class="mdu8wdb-r"/><path clip-rule="evenodd" class="vw8grccll"/><path clip-rule="evenodd" class="khkioc1eh"/><path clip-rule="evenodd" class="w20v3rkws"/><path clip-rule="evenodd" class="uaj2zj-ay"/><path clip-rule="evenodd" class="zzcl__bjq"/><path clip-rule="evenodd" class="cvyos1bdf"/><path clip-rule="evenodd" class="tt6_llbai"/><path clip-rule="evenodd" class="okuplh9zi"/><path clip-rule="evenodd" class="g4c1tzzcg"/><path clip-rule="evenodd" class="ni_jlgbes"/><path clip-rule="evenodd" class="avwne7gul"/><path clip-rule="evenodd" class="xxpazw-fk"/><path clip-rule="evenodd" class="n9iz6kbcd"/><path clip-rule="evenodd" class="m8izatb5n"/><path clip-rule="evenodd" class="f4ehk_n7g"/><path clip-rule="evenodd" class="ta8nfh6-r"/><path clip-rule="evenodd" class="nfb6wpbih"/><path clip-rule="evenodd" class="q5go394ls"/><path clip-rule="evenodd" class="l2t8r7o6z"/><path clip-rule="evenodd" class="l-sx-yb1c"/><path clip-rule="evenodd" class="u9se70hyk"/><path clip-rule="evenodd" class="szd2tczlg"/><path clip-rule="evenodd" class="ojzaetbsx"/><path clip-rule="evenodd" class="z5nywluyn"/><path clip-rule="evenodd" class="los-3imzl"/><path clip-rule="evenodd" class="btim8ybsb"/><path clip-rule="evenodd" class="lj6bo6btp"/><path clip-rule="evenodd" class="d2zqwpq2s"/><path clip-rule="evenodd" class="iehzc7mxi"/><path clip-rule="evenodd" class="uzxpp_b9f"/><path clip-rule="evenodd" class="jes965bwq"/><path clip-rule="evenodd" class="uoju7nb8d"/><path clip-rule="evenodd" class="c-ltngfex"/><path clip-rule="evenodd" class="t3nkx-kih"/><path clip-rule="evenodd" class="ku9axabog"/><path clip-rule="evenodd" class="opoblgcpw"/><path clip-rule="evenodd" class="d19w6hlxx"/><path clip-rule="evenodd" class="ybux_rj3q"/><path clip-rule="evenodd" class="agkvi7b6u"/><path clip-rule="evenodd" class="mef4igbpr"/><path clip-rule="evenodd" class="hd7nw-b2i"/><path clip-rule="evenodd" class="oxq1s_buu"/><path clip-rule="evenodd" class="e77wl8bxk"/><path clip-rule="evenodd" class="gnrp17g6s"/><path clip-rule="evenodd" class="tg0tlc7do"/><path clip-rule="evenodd" class="u7as9ac6j"/><path clip-rule="evenodd" class="wvdluvb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rug" /></template>
<style>
.a_84hrmzg {
  fill: var(--svg-color--888e97, #888e97);
  fill-rule: evenodd;
  d: path("M15.926 14.683h.284v-.285h-.284z");
}

.a0v31ebtj {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M7.215 14.108h.569v-.289h-.569z");
}

.a2a3qwnzr {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M8.746 7.784h.284V7.5h-.284z");
}

.a2fibtbel {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M12.285 14.965h.289v-.284h-.285v.284z");
}

.a51wi0b3a {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M13.82 8.652h.284v-.289h-.285z");
}

.a7elocfoc {
  fill: var(--svg-color--141013, #141013);
  d: path("M15.926 9.32h.284v-.67h-.284z");
}

.a96ikzble {
  fill: var(--svg-color--453f40, #453f40);
  fill-rule: evenodd;
  d: path("m6.35 10.74l.577.014v-.284h-.578z");
}

.aaf5ucmxx {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M7.215 15.544H7.5v-.284h-.285z");
}

.affiinb6i {
  fill: var(--svg-color--453f40, #453f40);
  d: path("M6.638 11.428h.573v-.384h-.569v.379z");
}

.afgzk6bwd {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M12 13.82v-.38h.284v-.289h-.569v.668z");
}

.afx3l-bib {
  fill: var(--svg-color--8ab47f, #8ab47f);
  fill-rule: evenodd;
  d: path("M13.147 5.393h.383v-.285h-.379v.285z");
}

.agkvi7b6u {
  fill: var(--svg-color--4f4b4e, #4f4b4e);
  fill-rule: evenodd;
  d: path("M15.253 10.716h.327l-.038-.246h-.284v.246z");
}

.agn437hve {
  fill: var(--svg-color--383124, #383124);
  d: path("M12.015 18.897h.28v-.289l-.01-.388H12z");
}

.ajfr4bgya {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M12.573 9.893v-.285h-.284v.285zm-1.146 9.578h.284v-.29h-.284z");
}

.ajpd0eb_v {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M5.392 15.833h.284v-.294l-.284.01z");
}

.alg3wdbji {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M11.138 10.183h.284v-.285h-.284zm-1.246.862v-.284h-.284v.284z");
}

.am_ycibqp {
  fill: var(--svg-color--18181c, #18181c);
  fill-rule: evenodd;
  d: path("M5.392 13.436h.289v-.285h-.284v.285z");
}

.ambff_bcq {
  fill: var(--svg-color--7c828a, #7c828a);
  d: path("m14.387 16.255l.294-.02l.284-.018v-.384l-.284-.028l-.294-.024z");
}

.anni_ybyo {
  fill: var(--svg-color--fed541, #fed541);
  fill-rule: evenodd;
  d: path("M14.68 12.862v-.284h-.284v.284zm-.288-.289v-.284h-.285v.284z");
}

.aoi5lmbhk {
  fill: var(--svg-color--28131c, #28131c);
  d: path("m3.952 13.456l.318.02l-.024.639v.284l.284-.005h.284v-.28l-.293.005v-.312l.293.01l-.01-.375h.304v-.294H3.952z");
}

.ark31_j-d {
  fill: var(--svg-color--544558, #544558);
  fill-rule: evenodd;
  d: path("M4.814 14.113v-.299l-.293-.01v.313h.293z");
}

.au5q_fbvx {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M17.362 7.501h.284v-.284h-.284zm.284.284h.29v-.284h-.285v.284zm-2.392-2.392h.285V5.11h-.285zm-1.435-1.53h.284V3.58h-.284zM14.97 5.11h.284v-.29h-.284zm3.35 3.254h.283V8.08h-.284zm-2.393-2.392h.284v-.289h-.284zm2.681 2.681h.284v-.289h-.284zm-4.216-4.12h.29v-.285h-.285v.284zm1.824 1.723h.284v-.284h-.284zM14.681 4.82h.284v-.284h-.284zm-1.819-.957h.284V3.58h-.284z");
}

.avwne7gul {
  fill: var(--svg-color--895b17, #895b17);
  fill-rule: evenodd;
  d: path("M7.5 17.652h.284v-.289l-.284.005z");
}

.ax_11cb7y {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M8.362 16.216h.379v.284h.289v-.284h.289v-.384h-.957z");
}

.ayllsv2ed {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M11.427 12.573H12v-.284h-.573z");
}

.aymr5bcxj {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M8.073 17.363h.957v-.284h-.957z");
}

.azamjbc3o {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M11.138 17.936h.284v-.285h-.284z");
}

.b_2m96wku {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M11.138 18.608v.573h.284v-.956h-.284z");
}

.b_o7xsdqr {
  fill: var(--svg-color--7b8b45, #7b8b45);
  fill-rule: evenodd;
  d: path("M7.784 16.5v-.284H7.5v.284z");
}

.b_reh1g7i {
  fill: var(--svg-color--26653c, #26653c);
  fill-rule: evenodd;
  d: path("M15.253 5.683h.285v-.285h-.285zm2.108 2.103h.284v-.284h-.284z");
}

.b0a1ktthc {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M12.285 15.832H12v.379h.284z");
}

.b2divgfrt {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M8.362 16.5h.379v-.284h-.38z");
}

.b47vym4to {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M13.53 5.393h.29v-.285h-.285v.285z");
}

.b5bh5eixf {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M20.716 10.754H21v-.573h-.284z");
}

.b5k3tbbhz {
  fill: var(--svg-color--141013, #141013);
  d: path("M12.573 7.217h-.284V7.5h.862v-.284h.38v-.29h-.669v.285h-.284z");
}

.b9f6r2_wy {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M18.607 12.284h.285V12h-.285zm-2.68 0h.284V12h-.285z");
}

.b9jzx0xpl {
  fill: var(--svg-color--696e7d, #696e7d);
  d: path("m13.82 15.255l.284.014l.265.01v-.318h-.26l-.285.01v.284z");
}

.baksrwbwl {
  fill: var(--svg-color--18181c, #18181c);
  d: path("M10.181 20.332h.298l-.01-.578h-.288zm-.862-.862l.284.01l.284-.006v-.293H9.32z");
}

.bbzqbebjj {
  fill: var(--svg-color--497383, #497383);
  fill-rule: evenodd;
  d: path("M13.53 5.11h.29v-.285h-.285v.284zm.29.862h.283v-.29h-.284z");
}

.bdurf793h {
  fill: var(--svg-color--6a2620, #6a2620);
  d: path("M9.319 16.218v.568h.284v-.957H9.32z");
}

.beu6nkzjp {
  fill: var(--svg-color--8ab47f, #8ab47f);
  fill-rule: evenodd;
  d: path("M12.862 5.683h.284v-.285h-.284z");
}

.bio_c2brc {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M12.285 14.393v-.574H12v.573z");
}

.bkf9f0bam {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M7.784 17.652v.284l.284.01h.294v-.294h-.284v-.289h-.29l-.004.285z");
}

.bldaqmb7y {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M15.543 12v-.284h-.285V12z");
}

.br7ebu4zj {
  fill: var(--svg-color--333941, #333941);
  d: path("M12.285 8.363v.285h.867v-.569h-.29v.284zm4.215 3.354h1.151v-.289h-1.15z");
}

.btim8ybsb {
  fill: var(--svg-color--357952, #357952);
  fill-rule: evenodd;
  d: path("M17.073 7.784h.285V7.5l-.247-.015l-.038.304z");
}

.btjgg9svj {
  fill: var(--svg-color--2c282a, #2c282a);
  d: path("M5.681 11.039v.398l.957-.01v-.384h.573v-.284h-.284l-.578-.019l-.379.014l-.005.285z");
}

.bvt1dp5pv {
  fill: var(--svg-color--f9a31b, #f9a31b);
  d: path("M11.422 12.284V12h-.663v.284z");
}

.bw_d66bci {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M12.862 4.82h.284v-.285h-.284z");
}

.byo_g9ymf {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M13.53 8.652h.29V8.08h-.285v.569z");
}

.bziz0lbvo {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M7.215 14.97H7.5v-.577h-.285z");
}

.c-i2lrl6r {
  fill: var(--svg-color--909132, #909132);
  d: path("m10.47 19.754l.01.578h.274v-.29l.01-.568l-.294-.004z");
}

.c-ltngfex {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m17.11 7.221l.252-.01v-.283h-.284z");
}

.c-prx813i {
  fill: var(--svg-color--6e9759, #6e9759);
  fill-rule: evenodd;
  d: path("M12.573 5.683h.284v-.285h-.284z");
}

.c0b8r9j5h {
  fill: var(--svg-color--2e3858, #2e3858);
  fill-rule: evenodd;
  d: path("M13.82 4.531h.284v-.284h-.285z");
}

.c2cenp7op {
  fill: var(--svg-color--5b6478, #5b6478);
  fill-rule: evenodd;
  d: path("M14.392 13.82h.289v-.38h-.284v.38z");
}

.c80ytfqxg {
  fill: var(--svg-color--8ab47f, #8ab47f);
  fill-rule: evenodd;
  d: path("M12.862 5.11h.284v-.285h-.284z");
}

.c8kuuhbbi {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M6.354 14.393h.284v-.285h-.284z");
}

.cakb76bpk {
  fill: var(--svg-color--186129, #186129);
  d: path("M7.21 17.073h.579v-.284H7.21z");
}

.ceb11acfy {
  fill: var(--svg-color--141013, #141013);
  d: path("M13.53 7.5v.284h-.668v.29h.957v-.858h-.284v.289z");
}

.ci2h3wbbf {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("M11.427 7.217h.284v-.29h-.284z");
}

.ckceyxb2r {
  fill: var(--svg-color--7c828a, #7c828a);
  fill-rule: evenodd;
  d: path("M13.142 14.393h.388v-.285h-.388z");
}

.cmk5tobhi {
  fill: var(--svg-color--4f4b4e, #4f4b4e);
  d: path("M16.784 10.754h1.819v-.284h-1.82z");
}

.cnv1o1b0s {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M14.97 11.717h.284v-.29h-.284z");
}

.co6hnlb8y {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M13.82 13.436h.861v-.285h-.862z");
}

.coo6lkcev {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M3.952 12.858h.294v-.285h-.284z");
}

.cqmr9pbnu {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M12.568 16.784h.294l-.005-.284h-.298zm-.853.867H12v-.294l-.285-.004z");
}

.crl7s9buq {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M5.681 13.436v.383h.284v.284h.389v-.284h.568v-.663l-1.24-.005z");
}

.csg_mibem {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M18.32 12.863h.284v-.284h-.285z");
}

.ctg141b7k {
  fill: var(--svg-color--e86973, #e86973);
  d: path("M13.147 3.573h.672V3.29h-.673z");
}

.cvpv-7xhg {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M13.82 10.183h.572v-.285h-.573z");
}

.cvyos1bdf {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M5.681 11.043h.284v-.29h-.284z");
}

.czcxmepiu {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M4.814 13.815v.298l.867-.005v-.289h-.284v-.379h-.29v.38z");
}

.d1-36pjav {
  fill: var(--svg-color--70455c, #70455c);
  fill-rule: evenodd;
  d: path("M9.03 17.363h.289v-.284h-.284v.284z");
}

.d19w6hlxx {
  fill: var(--svg-color--656574, #656574);
  fill-rule: evenodd;
  d: path("M14.97 15.832h.284v-.27h-.289v.27z");
}

.d1pphqfik {
  fill: var(--svg-color--333941, #333941);
  d: path("M12 5.108v.284h-.284v.29h-.29v.284h-.284v.289l-.004.956h.284v-.284h.289v-.289L12 6.62h.317v-.393l-.322-.047c.119-.322-.204-.157.294-.209v-.578h.284V4.82h-.284v.285h-.29z");
}

.d2948zbwi {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M16.216 11.428h1.69l-.028-.375l-1.662-.01z");
}

.d2zqwpq2s {
  fill: var(--svg-color--895b17, #895b17);
  fill-rule: evenodd;
  d: path("M13.824 17.08h.284l.005-.285h-.285v.284z");
}

.d6jz3-6tq {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M11.138 10.183v-.285h-.379v.285z");
}

.d7kveab1n {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M18.902 11.044h-.294l-.26.01l.047.378l.497-.004z");
}

.dbod5_ceq {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M20.332 10.182h.379v-.284h-.379zM7.5 9.032h.284v-.38H7.5zm3.254-3.35h.384v-.284h-.38v.284zm9.573 5.362h.384v-.284h-.379v.284zm-4.784-5.65h.379v-.285h-.379zm-1.15-1.147h.288v-.384h-.284v.38zm3.542 3.538h.384v-.284h-.379v.284zm1.246 1.246h.284v-.379h-.284zm-1.535 4.79h.29v-.38h-.285v.38z");
}

.dd4b27c8v {
  fill: var(--svg-color--1d376d, #1d376d);
  fill-rule: evenodd;
  d: path("M9.319 7.784h.284V7.5H9.32z");
}

.de70vob3d {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M9.608 20.044h.284v-.284h-.284z");
}

.detbz5byy {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M12 8.363h.285V8.08H12z");
}

.dk-59wz8v {
  fill: var(--svg-color--357952, #357952);
  fill-rule: evenodd;
  d: path("M18.32 9.893h.284v-.285h-.285z");
}

.dkhj3dbbk {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M15.543 12.573v-.284h-.573v.284z");
}

.dlokk8s7q {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M7.215 15.254H7.5v-.284h-.285z");
}

.dme8r3bvt {
  fill: var(--svg-color--40424f, #40424f);
  fill-rule: evenodd;
  d: path("M13.156 16.216h.37l.004-.384h-.379v.379z");
}

.dn96kmbna {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M15.926 12h.284v-.284h-.284z");
}

.dpv6eqbek {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M12 11.044v-.284h-.285v.284z");
}

.dsbuwc9hp {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M3.573 13.818h.38v-.364l-.38-.02z");
}

.dskjicfja {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M3.573 14.11v-.285H3.29v.284z");
}

.dss03vbjr {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  d: path("M9.03 12h.573v-.284h-.568V12z");
}

.dtpx08gdw {
  fill: var(--svg-color--2e3239, #2e3239);
  fill-rule: evenodd;
  d: path("M7.211 12.024v-.308h-.284v.308z");
}

.dtrbitbio {
  fill: var(--svg-color--6a2620, #6a2620);
  fill-rule: evenodd;
  d: path("M9.608 17.073h.284v-.284h-.284z");
}

.dua6arovl {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M4.246 12.285h.284v-.284h-.284zM19.47 9.32h.284v-.284h-.284zm-9-3.349h.284v-.289h-.284zm3.638-2.108h.284V3.58h-.284zm-2.392.957H12v-.284h-.284zM6.638 9.893h.284V9.61h-.284zm13.405 0h.284V9.61h-.284z");
}

.dvpbl-bmj {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M3.285 13.152h.289v-.289h-.285v.284z");
}

.e1ac-l1ai {
  fill: var(--svg-color--9097af, #9097af);
  d: path("M13.146 14.683h.668v-.285h-.672z");
}

.e40du1b_x {
  fill: var(--svg-color--747a8a, #747a8a);
  d: path("M14.099 14.682h.582v-.285l-.284-.004h-.303l.005.284z");
}

.e47ejnfei {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M5.97 12.573h.393l-.01-.284H5.97z");
}

.e77wl8bxk {
  fill: var(--svg-color--8ab47f, #8ab47f);
  fill-rule: evenodd;
  d: path("m12.318 6.226l.255.028V5.97h-.284z");
}

.eaa9n6b4v {
  fill: var(--svg-color--736e68, #736e68);
  d: path("M6.927 10.755H7.5v-.294l-.573.01z");
}

.ebat8dt4s {
  fill: var(--svg-color--803a46, #803a46);
  fill-rule: evenodd;
  d: path("M8.073 15.833h.289v-.29h-.284v.285z");
}

.ecod-msqt {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M13.152 8.646v.384h.379v-.957h-.38zm-2.397-2.008v.573h.384v-.957h-.38v.384z");
}

.ecu2q7bpm {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M19.47 12h.284v-.284h-.284z");
}

.eilj8acxh {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M5.97 12.862h.668l-.005-.294h-.27l-.393.005z");
}

.eiq4icysa {
  fill: var(--svg-color--141013, #141013);
  d: path("M14.107 8.362h.285v.668h.284v-.957h-.569z");
}

.ek8ibwvgm {
  fill: var(--svg-color--8e732b, #8e732b);
  d: path("M9.892 15.833h.284v.379h.578v.289h.383v-.663h-.388v-.294h-.857z");
}

.ekat1dbzl {
  fill: var(--svg-color--444249, #444249);
  fill-rule: evenodd;
  d: path("M8.068 10.465v.256h.285l.019-.26v-.28h-.299v.284z");
}

.ekhddab6a {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M17.647 7.5h.289v-.284h-.285V7.5zm.961.863h.284v-.285h-.284zM16.216 5.97h.284v-.289h-.284zM14.97 4.82h.284v-.285h-.284z");
}

.elr1r5bho {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M18.892 8.652h.289v-.289h-.284v.285z");
}

.em6u7-b2j {
  fill: var(--svg-color--914a5b, #914a5b);
  fill-rule: evenodd;
  d: path("M6.927 15.254h.284v-.284h-.284z");
}

.eo1_okb4c {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M10.181 6.254h.284V5.97h-.284z");
}

.eo8jmbc5w {
  fill: var(--svg-color--333235, #333235);
  d: path("m7.813 11.035l.26.024l.275.019v-.355h-.284l-.252.042z");
}

.eopvutc9c {
  fill: var(--svg-color--8e732b, #8e732b);
  d: path("M10.754 16.5h-.573v.289h.578V16.5z");
}

.epyq09gnm {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M15.543 10.47h1.24v-.29h-1.24z");
}

.erixxj5jh {
  fill: var(--svg-color--18181c, #18181c);
  d: path("M6.359 12.29v.285h.274l.005.284h-.957v.294l1.246.005H7.5v-.299h-.568v-.284c.042 0 .265.01.289.005c.284-.048.336-.119.46-.308c.127-.19.065.246.108-.275l-.573.024h-.284l-.275-.01l-.005.284h-.289z");
}

.ev4uf98uv {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M14.107 8.652h.285v-.289h-.285z");
}

.ewqtpfb9f {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M15.926 15.545h.284v-.284h-.284zm.858-.862h.289v-.285h-.285v.285z");
}

.ey5zq05ye {
  fill: var(--svg-color--5f8342, #5f8342);
  fill-rule: evenodd;
  d: path("m17.111 7.221l-.038-.293h-.284v.303z");
}

.eybp01aem {
  fill: var(--svg-color--2c555d, #2c555d);
  d: path("M13.147 4.531h.383v.29h.284v-.285l.005-.289h-.673z");
}

.eyhwi4bcp {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M19.18 12h.285v-.284h-.284z");
}

.ezlp50aqs {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M16.784 14.393h.289v-.285h-.285v.285z");
}

.f-enilymz {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.427 20.044h.284v-.284h-.284z");
}

.f-kj2cczv {
  fill: var(--svg-color--7c828a, #7c828a);
  d: path("M13.53 15.254v.284h.284l.005-.284v-.284h-.284v.284z");
}

.f0kt-4bwk {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M7.784 15.833h.29v-.29h-.285v.285z");
}

.f2_br5bck {
  fill: var(--svg-color--692027, #692027);
  fill-rule: evenodd;
  d: path("M6.628 15.828h.299v-.284h-.284z");
}

.f3simhb6a {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.427 8.363h.284V8.08h-.284z");
}

.f3xqy9bij {
  fill: var(--svg-color--803a46, #803a46);
  fill-rule: evenodd;
  d: path("M6.927 14.97v-.29h-.284v.285h.284z");
}

.f4ehk_n7g {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("m7.784 18.225l.284.004v-.284l-.284-.005z");
}

.f6udpobyg {
  fill: var(--svg-color--6a2620, #6a2620);
  fill-rule: evenodd;
  d: path("M8.073 16.784h.284V16.5h-.284z");
}

.f7f0h6bsr {
  fill: var(--svg-color--797981, #797981);
  fill-rule: evenodd;
  d: path("M15.926 14.97h.284v-.284h-.284z");
}

.f855mgbef {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M10.755 20.62h.384v-.288h-.38v.284z");
}

.fb_d10caj {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M19.754 11.428h.284v-.384h-.284z");
}

.fbg6o9bxy {
  fill: var(--svg-color--2c555d, #2c555d);
  d: path("M13.147 5.683v.284h.383v-.569h-.379v.285z");
}

.fhqd7obtz {
  fill: var(--svg-color--645b51, #645b51);
  fill-rule: evenodd;
  d: path("M19.754 10.183h.284v-.285h-.284z");
}

.fi9z1wb1g {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("m7.5 10.188l.284-.005v-.285H7.5z");
}

.fk_uxs10t {
  fill: var(--svg-color--884b17, #884b17);
  fill-rule: evenodd;
  d: path("M7.215 15.833H7.5v-.29h-.285z");
}

.fl8el2c_o {
  fill: var(--svg-color--4a69a9, #4a69a9);
  fill-rule: evenodd;
  d: path("M9.892 9.03v-.379h-.284v.38z");
}

.fla-ut-ii {
  fill: var(--svg-color--523c3e, #523c3e);
  fill-rule: evenodd;
  d: path("m15.918 7.51l.293-.01v-.284h-.284z");
}

.fp791oeap {
  fill: var(--svg-color--357952, #357952);
  fill-rule: evenodd;
  d: path("M15.552 7.51h.365l.01-.298h-.384z");
}

.fpcbfabvj {
  fill: var(--svg-color--357952, #357952);
  d: path("m15.913 8.363l.014.285h.284v.672h-.284v.862h.862v-.284h.568c-.075-.73-.203.147-.284-.578c-.724-.08.152-.208-.573-.284v-.673h-.303l.014-.284h-.298z");
}

.fpvm38b1h {
  fill: var(--svg-color--fed541, #fed541);
  fill-rule: evenodd;
  d: path("M13.147 13.436h.383v-.285h-.379v.285z");
}

.fq10ayqqx {
  fill: var(--svg-color--fed541, #fed541);
  fill-rule: evenodd;
  d: path("M14.97 12.284V12h-.289v.284zM14.681 12v-.284h-.284V12zm-1.53 1.151v-.289h-.289v.284h.284z");
}

.fq4poubzd {
  fill: var(--svg-color--186129, #186129);
  d: path("M6.927 16.784h.284v-.568h-.284z");
}

.ft5dv1b6b {
  fill: none;
}

.fus8l09xd {
  fill: var(--svg-color--692027, #692027);
  d: path("m5.68 14.683l-.572-.005h-.294v.294l.284.004v.284h.284l.01.285h1.246v-.284h.284v-.29h-.284v-.288h-.285v-.285H5.97v.285z");
}

.g_ch3-byy {
  fill: var(--svg-color--736e68, #736e68);
  d: path("m16.215 11.043l1.663.01h.469l-.029-.3h-2.392v.29z");
}

.g-fyifbdy {
  fill: var(--svg-color--692027, #692027);
  fill-rule: evenodd;
  d: path("M9.892 15.254h.293l-.004-.284h-.285v.284z");
}

.g1pmnmb1a {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M9.319 19.183h.862v-.285h-.857v.285z");
}

.g2n7a1q1h {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M8.073 12.863v-.284H7.79v.284z");
}

.g4c1tzzcg {
  fill: var(--svg-color--1d376d, #1d376d);
  fill-rule: evenodd;
  d: path("m8.746 8.354l.284.01v-.285h-.284v.28z");
}

.g7jd0dk0z {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("M16.784 12.573h.289v-.284h-.285v.284z");
}

.g8ife4b1z {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M6.927 17.363v-.284h-.284v.284z");
}

.gchc1lxbw {
  fill: var(--svg-color--1d376d, #1d376d);
  fill-rule: evenodd;
  d: path("M9.03 8.073h.284V7.79H9.03z");
}

.gdqaickxp {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M10.47 13.435h-.289v.384h.284v-.379zM13.146 7.5h.384v-.284h-.379V7.5z");
}

.gf0gvk3bf {
  fill: var(--svg-color--6e9759, #6e9759);
  fill-rule: evenodd;
  d: path("M12.862 5.393h.284v-.285h-.284z");
}

.ghveeyb4e {
  fill: var(--svg-color--141013, #141013);
  d: path("M12.285 8.363h.578V8.08h-.578z");
}

.gi1k-gbkp {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M14.97 16.216h.284v-.384h-.284z");
}

.giliicbzs {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M11.427 16.217h.284v-.38h-.284z");
}

.gimk_2-vn {
  fill: var(--svg-color--141013, #141013);
  d: path("M3.284 13.82v-.669H3v.668z");
}

.glwx5vbjo {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("M19.21 11.043h.544v-.284l-.52.005zm-8.74-2.68v.283h.284v-.511h-.284v.232z");
}

.gmyoz9boz {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M13.82 5.683h.284v-.285h-.285z");
}

.gnrp17g6s {
  fill: var(--svg-color--696e7d, #696e7d);
  fill-rule: evenodd;
  d: path("m14.387 15.78l.294.025v-.261h-.284z");
}

.gpdamfbob {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M5.108 13.147h.284v-.284h-.284z");
}

.gpkh8ac6m {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M12.294 18.897h.284v-.289h-.284z");
}

.gs2-83wkd {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M19.18 9.32h.285v-.285h-.284z");
}

.gwiu2jeok {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M8.746 8.073h.284V7.79h-.284zm.284-.289h.29V7.5h-.285v.284zM6.927 9.892h.284v-.284h-.284z");
}

.gwnah6zkt {
  fill: var(--svg-color--70455c, #70455c);
  fill-rule: evenodd;
  d: path("M5.68 13.82v-.38h-.284v.38z");
}

.gwo5aojch {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M11.427 16.784h.289V16.5h-.29z");
}

.gz4eqpbnz {
  fill: var(--svg-color--55525e, #55525e);
  fill-rule: evenodd;
  d: path("M6.932 11.717h.284v-.29h-.289v.285z");
}

.gzd9q0qfo {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M7.5 15.544h.857v-.284H7.5z");
}

.gzu4gsbdi {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M15.543 7.216h.379v-.578h-.379z");
}

.h1jfh9bsr {
  fill: var(--svg-color--884b17, #884b17);
  fill-rule: evenodd;
  d: path("M10.181 16.5h.573v-.284h-.573z");
}

.h2jwh-viv {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M13.82 8.073h.284v-.857h-.285z");
}

.h4gd1crvr {
  fill: var(--svg-color--141013, #141013);
  d: path("M13.147 3.284h.672V3h-.673z");
}

.h5_gi28bt {
  fill: var(--svg-color--4b557d, #4b557d);
  fill-rule: evenodd;
  d: path("m15.913 8.083l.298-.01l.019-.284h-.313z");
}

.h5svexb0w {
  fill: var(--svg-color--1e2342, #1e2342);
  fill-rule: evenodd;
  d: path("M19.18 9.608h.285V9.32h-.284z");
}

.h7gtas8gd {
  fill: var(--svg-color--26653c, #26653c);
  fill-rule: evenodd;
  d: path("M14.681 5.11h.284v-.285h-.284z");
}

.h8m_4ybch {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("m12.317 6.619l.256.023v-.388l-.256-.028z");
}

.hcf307bho {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M9.892 6.929h.284l.005-.284h-.285v.284z");
}

.hcgi67b0p {
  fill: var(--svg-color--8d4618, #8d4618);
  fill-rule: evenodd;
  d: path("M7.784 10.183h.29v-.285h-.285v.285z");
}

.hd7gu9ngl {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M10.47 14.393h.284v-.285h-.284z");
}

.hd7nw-b2i {
  fill: var(--svg-color--656574, #656574);
  fill-rule: evenodd;
  d: path("M14.397 16.5h.284v-.265l-.294.02z");
}

.hjmoq4okm {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M7.215 13.437v.383h.569v-.379H7.5v-.284h-.285v.284z");
}

.hkj4t1u6c {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M9.608 12h.284v-.284h-.284z");
}

.hm1f3eg9z {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M12.573 14.97h.284v-.29h-.284z");
}

.hmazegrbt {
  fill: var(--svg-color--986f2e, #986f2e);
  d: path("M16.784 12.863h1.15v-.284h-1.146v.284z");
}

.hnjz0olkp {
  fill: var(--svg-color--141013, #141013);
  d: path("M12.285 14.108v.284h.289v.29h.284v.284h-.284l.01.862h.279v-.318h.284v-1.402h.383v-.289h-.956v.284h-.285z");
}

.hs14ufbpx {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M11.427 14.68h-.284v.285h.284z");
}

.hs24uacxj {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M15.253 8.652h.285v-.289h-.285z");
}

.huoilsb8l {
  fill: var(--svg-color--692027, #692027);
  d: path("M9.608 17.652h.862v-.289h-.862z");
}

.huzsjubss {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("M11.715 6.928H12V6.62l-.285.02z");
}

.hw8q4wb2n {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M4.53 12.863h.289v-.284h-.284v.284z");
}

.hx5wfibca {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M14.97 16.5h.284v-.284h-.284zm1.246-1.246h.284v-.284h-.284z");
}

.i_u19jbbp {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M11.138 18.225h.284v-.284h-.284zm5.362-5.362h.284v-.284H16.5z");
}

.i-88xtb5c {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M17.362 14.11h.284v-.29h-.284zm-2.68-9.579h.283v-.284h-.284z");
}

.i-m7q6q6j {
  fill: var(--svg-color--884b17, #884b17);
  fill-rule: evenodd;
  d: path("M6.638 16.5h.284v-.285l-.294-.014z");
}

.i0atby0uh {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M17.362 13.82h.284v-.38h-.284z");
}

.i0uiq-zpt {
  fill: var(--svg-color--8c892a, #8c892a);
  fill-rule: evenodd;
  d: path("M6.35 16.5h.288l-.01-.299H6.35z");
}

.i3xd4y-2c {
  fill: var(--svg-color--797981, #797981);
  d: path("M14.965 15.562h.294l.284-.02v-.283h-.284l-.294-.005z");
}

.i7fyy7blg {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M11.138 15.538h.568l.005-.284h-.569v.284z");
}

.i8h6ebb3s {
  fill: var(--svg-color--692027, #692027);
  d: path("M8.068 18.23h.957l.294-.005h.573v-.285H8.068z");
}

.ibyi_3u7s {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M8.073 16.216h.284l.005-.384h-.284v.379z");
}

.icsh4tbuv {
  fill: var(--svg-color--895b17, #895b17);
  d: path("M10.755 20.043h.384v-.284h.284v-.29l-.284.01h-.375z");
}

.iczq0cb_x {
  fill: var(--svg-color--18181c, #18181c);
  d: path("M12.284 15.829v.379H12v-.374h.284zm-.573-.573v.284h-.957l-.005.298h.389v1.815h.284v-1.815h.284v.38l.005.284l.005.284v.568H12l-.01-.848h.304v.27l.274.005l-.009-.28l.024-.672h-.294v-.862H12v.284h-.289z");
}

.idpm2x3ul {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M13.151 17.94h.38l.004-.289h-.384z");
}

.iehzc7mxi {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("M15.253 15.833h.285v-.29l-.285.02z");
}

.if0rohh5u {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M16.784 6.639h.289v-.38h-.285v.38z");
}

.ig1j9flni {
  fill: var(--svg-color--1b2025, #1b2025);
  d: path("M4.814 12v.294h.294v.568h.573v-.284h.284v-.289h.393l-.01-.284l.304.005l-.005-.303l-1.26-.015l-.284.02v.284h-.284z");
}

.ihjx5wb_r {
  fill: var(--svg-color--f9a31b, #f9a31b);
  d: path("M9.03 10.754h.578v-.284H9.03z");
}

.ilvd1i45x {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M13.151 11.428v-.384h-.289v.379h.284z");
}

.imringo3u {
  fill: var(--svg-color--fed541, #fed541);
  fill-rule: evenodd;
  d: path("M12.862 12.863v-.284h-.284v.284z");
}

.inygyabes {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M13.82 17.652h.284v-.289h-.285z");
}

.ipqcobbrn {
  fill: var(--svg-color--357952, #357952);
  fill-rule: evenodd;
  d: path("M18.607 9.608h.285V9.32h-.285z");
}

.iqww10bfy {
  fill: var(--svg-color--4f4b4e, #4f4b4e);
  d: path("M7.215 10.755v.284H7.5v.388l.284.005l.028-.398v-.27l-.028-.298l-.284-.005v.294z");
}

.isvdl_xvb {
  fill: var(--svg-color--357952, #357952);
  fill-rule: evenodd;
  d: path("M13.82 8.363h.284V8.08h-.285z");
}

.j207lm_3s {
  fill: var(--svg-color--5d8034, #5d8034);
  fill-rule: evenodd;
  d: path("M7.784 16.5h.29v-.284h-.285v.284z");
}

.j2rifn83j {
  fill: var(--svg-color--333941, #333941);
  d: path("m12.313 6.619l-.024.308v.284h.284v-.284h.284v-.673h-.284v.388z");
}

.j35w48thc {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M15.926 15.254h.284v-.284h-.284z");
}

.j8nzh3tvt {
  fill: var(--svg-color--fed541, #fed541);
  fill-rule: evenodd;
  d: path("M10.755 15.544h.384v-.284h-.38z");
}

.jbs0u92hw {
  fill: var(--svg-color--141013, #141013);
  d: path("M10.18 8.652v.957h-.86l-.242.014l-.047.27h-.284v.294h-.38l.005.275h.375v.293h.284v-.284h.578v.284h.573v.285h.284v.388h.289v.284h.384v.29h.284v.283H12v-.284h.284v-.573H12v-.384h-.284v-.284h-.29v-.289h-.284v-.289h-.388v-.284l-.294.005l.01-.294v-.578h.284v-.379h-.284v-.289h-.29z");
}

.jcek_sb1s {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M10.47 11.717v-.29h-.289v.285h.284z");
}

.jdgiutijv {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M12.573 4.247h.284v-.384h-.284zM16.5 6.639h.284V6.26H16.5zm2.392 2.392h.29v-.379h-.285v.38z");
}

.je4x5wzzu {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M9.892 11.043h.289v-.284h-.285v.284zm1.534-.573v-.29h-.284v.285h.284z");
}

.jes965bwq {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m5.104 11.71l.284-.018v-.27h-.284z");
}

.jie31jo_r {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m5.392 11.423l.284.014v-.398h-.284z");
}

.jj2qr4bqq {
  fill: var(--svg-color--18181c, #18181c);
  d: path("M13.151 17.652h.38v-.289l-.006-.284h-.379v.573z");
}

.jm0rhs02l {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M12.285 7.784h.289V7.5h-.285v.284z");
}

.jmitu6yiz {
  fill: var(--svg-color--692027, #692027);
  d: path("M6.638 14.683h.284v.284h.289v-.569h-.569v.285z");
}

.jnj8fjb0z {
  fill: var(--svg-color--692027, #692027);
  d: path("M8.362 17.652h.957v-.289H8.073v.285h.284z");
}

.jo0dzeb4v {
  fill: var(--svg-color--9b9d41, #9b9d41);
  d: path("M14.681 14.683v.284h.284v.289h.29v-.284h.288v-.29h-.284v-.284h-.289v.285z");
}

.joxg4fb8s {
  fill: var(--svg-color--8ab47f, #8ab47f);
  fill-rule: evenodd;
  d: path("M17.073 9.32h.285v-.285h-.285z");
}

.jqh11ilwk {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  d: path("M10.181 8.362h.284l.005-.232v-.37l-.289.03z");
}

.jswducbfa {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("m18.892 9.893l.578-.01v-.275h-.573v.285z");
}

.jtqpsxbop {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M9.608 12.573h.284V12h-.284z");
}

.juambp63a {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M15.543 12.284h.379V12h-.379z");
}

.jvurh4evr {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M7.784 9.03h.29v-.38h-.285v.38zm2.397-2.392h.284v-.38h-.284zm.573-.668h.384v-.29h-.38v.285z");
}

.jy64fdc7y {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M9.608 6.929h.284v-.284h-.284z");
}

.jybke5b4r {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M14.107 4.247h.285v-.384h-.285z");
}

.k_36xlb4g {
  fill: var(--svg-color--fed541, #fed541);
  fill-rule: evenodd;
  d: path("M12.285 14.108h.289v-.289h-.285v.284zm1.245 0h.29v-.289h-.285v.284z");
}

.k_731ibom {
  fill: var(--svg-color--141013, #141013);
  d: path("M15.926 11.715h.284v.284h.285v-.568h-.569z");
}

.k_zk5el2r {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M12.285 13.82h1.245v-.38h-1.24v.38z");
}

.k-pngxtkr {
  fill: var(--svg-color--fed541, #fed541);
  fill-rule: evenodd;
  d: path("M11.715 14.97H12v-.29h-.285z");
}

.k24gqnbsr {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("M16.216 14.97h.284v-.284h-.284z");
}

.k2kmipn8r {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M17.935 13.152h.384v-.289h-.38v.284z");
}

.k2ma-8tdb {
  fill: var(--svg-color--67615a, #67615a);
  fill-rule: evenodd;
  d: path("m8.353 10.722l.393.033v-.294H8.37z");
}

.k8suc3uie {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M5.681 12.863h.284v-.284h-.284z");
}

.kbm32ab0g {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M6.927 13.82h.284v-.38h-.284z");
}

.kdi-96bhl {
  fill: var(--svg-color--26653c, #26653c);
  fill-rule: evenodd;
  d: path("M14.107 4.531h.285v-.284h-.285z");
}

.kgw-0vb0t {
  fill: var(--svg-color--333941, #333941);
  d: path("M12.285 9.61h.289v.283h.573V9.61h-.284v-.578h-.578zm3.642 2.676v.289h.858v-.285h.284v-.289h-.853v.285z");
}

.khkioc1eh {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("m5.108 15.544l-.005-.284h-.284v.284z");
}

.klwe4ccwa {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M4.246 14.682h.284v-.29h-.284z");
}

.km6z0vb6u {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M13.147 15.254h.383v-.284h-.379z");
}

.kr4drwbxo {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M17.073 14.393h.285v-.285h-.285z");
}

.ktvgtpbsy {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M11.427 19.754h.284v-.284h-.284zm.289-.284H12v-.29h-.284z");
}

.ku9axabog {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M14.108 14.96h.26l.024-.28H14.1l.009.285z");
}

.kvh5v4ajn {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M9.892 6.639h.289v-.38h-.285v.38zM12 13.819h.284v-.378h-.285z");
}

.kvpylabdd {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M10.47 9.61h.284v-.58h-.284z");
}

.kwc6dobty {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M10.755 18.893h.384v-.285h-.38v.284z");
}

.ky0an4x7l {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("m12.872 17.956l.284-.014l-.005-.284v-.872h-.289l.01 1.165z");
}

.ky1k3sbha {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("m7.216 10.191l.284-.005v-.293h-.29v.298z");
}

.ky96unb8t {
  fill: var(--svg-color--141013, #141013);
  d: path("m10.186 15.254l.01.284h.558v-.284h-.284v-.284h-.289z");
}

.kyzg6rbga {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M18.607 9.893h.285v-.285h-.285z");
}

.l_7g_o6ix {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M5.392 13.152h.289v-.289h-.284v.284z");
}

.l_o-f9btf {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m7.5 9.315l.284.01V9.03H7.5z");
}

.l-sx-yb1c {
  fill: var(--svg-color--8f8c8d, #8f8c8d);
  fill-rule: evenodd;
  d: path("m18.348 11.053l.26-.009v-.284h-.289z");
}

.l1at_dbku {
  fill: var(--svg-color--2e4a84, #2e4a84);
  d: path("M9.319 7.784v.284l-.285.005v.284h-.682l.01.294v.673h-.578l-.294-.01v.27l1.25.024l.332.014l.052-.303l.19.019l.573-.019v-.284h-.284V8.65h.284V7.5h-.284v.284h-.29z");
}

.l2t8r7o6z {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("m4.819 15.256l.284.005v-.284h-.284v.284zm.289.289h.284l-.005-.284h-.284v.284z");
}

.l3-ibrbyb {
  fill: var(--svg-color--357952, #357952);
  d: path("m16.784 8.638l.578.014v.38h1.246v-.38h-.29v-.289h-1.53v.275z");
}

.l5ywv3bfg {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M4.814 14.677h.294v-.284h-.294z");
}

.l7ydjqned {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.427 10.183h.284v-.285h-.284z");
}

.l9e0uew8q {
  fill: var(--svg-color--26653c, #26653c);
  fill-rule: evenodd;
  d: path("M17.647 8.074h.289v-.285h-.285v.285zm1.245 1.245h.29v-.284h-.285v.284zM14.97 5.393h.284v-.285h-.284z");
}

.la36h0b4g {
  fill: var(--svg-color--b5704a, #b5704a);
  fill-rule: evenodd;
  d: path("m8.371 10.182l.374.004v-.293h-.383z");
}

.lb1a8fb2t {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M9.319 17.363h.573v-.284h-.573z");
}

.lb7oibbvo {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M6.927 15.828h.284v-.284h-.284z");
}

.lc_h1o2lt {
  fill: var(--svg-color--333941, #333941);
  d: path("m18.906 11.043l-.014.38l-.497.004l-.048-.374h-.469l.029.374l.037.284h-.293v.29h-.29v.283h-.283v.29h1.24v-.285h.285V12h.289v-.284h.289v-.29l.028-.383l.029-.28l-.322.015z");
}

.leodchb_a {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M11.138 19.474v-.293h-.379l.005.293z");
}

.lgrp0hb5x {
  fill: var(--svg-color--182a45, #182a45);
  d: path("M7.21 9.893h1.536v-.284L7.49 9.585l-.28.019z");
}

.licrn-k7w {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M8.073 8.652h.293l-.009-.294h-.284z");
}

.lj6bo6btp {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("M14.681 16.5h.284v-.284l-.284.019z");
}

.ljsxh8bmf {
  fill: var(--svg-color--986f2e, #986f2e);
  d: path("M15.543 12.863h.957v-.284h-.957z");
}

.ljtm4qynr {
  fill: var(--svg-color--e86973, #e86973);
  d: path("M3.285 13.82h.289v-.669h-.285v.668z");
}

.lof2c6q6f {
  fill: var(--svg-color--453f40, #453f40);
  d: path("M9.603 19.759h.867v-.29h-.578l-.294.01z");
}

.los-3imzl {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("M17.647 11.717h.293l-.033-.29h-.26z");
}

.lp17yqbes {
  fill: var(--svg-color--b07449, #b07449);
  fill-rule: evenodd;
  d: path("M7.5 15.828h.284v-.284H7.5z");
}

.lqb5utbfh {
  fill: var(--svg-color--692027, #692027);
  fill-rule: evenodd;
  d: path("M10.181 18.225h.284v-.285h-.284z");
}

.ltpcsvrco {
  fill: var(--svg-color--432927, #432927);
  fill-rule: evenodd;
  d: path("M10.181 6.929h.284v-.284h-.284z");
}

.lvc0odbgj {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M10.755 14.108h.672v-.289h-.672z");
}

.lym78tbyh {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M11.427 17.653h.284v-.298l.005-.569h-.29z");
}

.lzeayqbcx {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M9.03 11.717h.289v-.29h-.284v.285z");
}

.lzfaag06g {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M10.18 20.621v-.288h-.283v.284h.284zm3.35-2.685h.289v-.285h-.284v.285zm-4.211 1.819v-.285h-.284v.285zm-.29-.285v-.284l-.283-.005v.285h.284z");
}

.m12fn3rtc {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M7.784 17.363h.29v-.284h-.285v.284z");
}

.m1yb67kbq {
  fill: var(--svg-color--5f8342, #5f8342);
  d: path("M13.147 3.863h.672V3.58h-.673z");
}

.m2sp0pbdy {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M9.319 12.863h.284v-.284H9.32z");
}

.m8bygetzl {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M16.5 6.254h.284V5.97H16.5zm-3.927-2.392h.284v-.284h-.284zm1.246-.289h.284V3.29h-.284zm3.254 3.354h.284v-.284h-.284zm-4.21-3.354h.283V3.29h-.284zm4.788 9.578h.284v-.289h-.284z");
}

.m8izatb5n {
  fill: var(--svg-color--9097af, #9097af);
  fill-rule: evenodd;
  d: path("M13.82 15.543h.284v-.275l-.285-.014z");
}

.m9-wywbnq {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m4.53 12.286l.284.01v-.3l-.284.006zm15.513-2.103h.284v-.285h-.284z");
}

.mc0pstisx {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M5.68 16.217v-.379l-.284-.01v.384h.285zm2.393 2.392v-.379l-.284-.005v.38h.284zm7.47-9.957h.379l-.01-.289h-.37zm-2.681 9.957h.284v-.384h-.28l-.004.38z");
}

.mdu8wdb-r {
  fill: var(--svg-color--383539, #383539);
  fill-rule: evenodd;
  d: path("M16.5 10.754h.284v-.284H16.5z");
}

.me5uy0u_v {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M19.18 11.717h.285v-.29h-.284zm-7.465 8.038H12v-.284h-.285z");
}

.mef4igbpr {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("m14.681 15.805l.284.028v-.27l-.284-.02z");
}

.mfadjdb3x {
  fill: var(--svg-color--8ab47f, #8ab47f);
  fill-rule: evenodd;
  d: path("M12.573 5.97h.284v-.29h-.284z");
}

.mfcjhk93x {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M8.746 12h.284v-.284h-.284z");
}

.mgk7b213p {
  fill: var(--svg-color--9097af, #9097af);
  fill-rule: evenodd;
  d: path("M15.543 13.82h.379v-.38h-.379z");
}

.mgnm37jmd {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M12.285 17.074h.289l-.005-.294h-.28v.294z");
}

.mhpblzo_x {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M15.543 15.544h.38v-.285h-.38zm-11.97-1.436h.38v-.289h-.38z");
}

.mhrzb2b-d {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("m6.927 17.362l.284.005v-.294h-.284z");
}

.mnf48zopy {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M18.32 13.152h.284v-.289h-.285z");
}

.mnubg9bsc {
  fill: var(--svg-color--4f4b4e, #4f4b4e);
  fill-rule: evenodd;
  d: path("M16.21 10.754h.29v-.284h-.29z");
}

.moimzmpqv {
  fill: var(--svg-color--4f4b4e, #4f4b4e);
  d: path("m15.58 11.025l-.037.402h.673v-.383h-.294v-.285l-.341-.042z");
}

.mpittkwhi {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M18.892 12.284h.289V12h-.284v.284z");
}

.mqdptmntf {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M10.181 19.183h.284v-.285h-.284z");
}

.mqh47cbgi {
  fill: var(--svg-color--6d6973, #6d6973);
  fill-rule: evenodd;
  d: path("M7.215 11.428H7.5v-.389h-.285z");
}

.mw-nl4y6h {
  fill: var(--svg-color--661e17, #661e17);
  fill-rule: evenodd;
  d: path("M6.638 16.784h.284V16.5h-.284z");
}

.mwdjejb7r {
  fill: var(--svg-color--141013, #141013);
  d: path("M13.53 12.574v.284h-.38v.293h.38v.285h.288v-.285h.862v-.288h-.284v-.285h-.289v-.289h-.289v.285zm0-2.966h-.38v.284h-.582v.29h1.246v-.285h.284v-.289h.289V9.32h-.569v.285h-.293z");
}

.mz8v8eboq {
  fill: var(--svg-color--141013, #141013);
  d: path("M8.746 15.828h.857v-.284h-.857z");
}

.n_55og-dr {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M12 7.5h.285v-.284H12z");
}

.n-r2y3blv {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M12 19.47h.285v-.29H12z");
}

.n1t83fb2v {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M14.107 9.893h.285v-.285h-.285z");
}

.n2wlfmbfk {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("M12 7.217h.285v-.29H12z");
}

.n39l4h1_m {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M11.427 16.5h.284v-.284h-.284z");
}

.n4pm8120q {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M16.5 13.152h1.146v-.289H16.5z");
}

.n4pwgf5jj {
  fill: var(--svg-color--a4abbc, #a4abbc);
  fill-rule: evenodd;
  d: path("M14.681 14.683h.284v-.285h-.284z");
}

.n5n7wkbhk {
  fill: var(--svg-color--141013, #141013);
  d: path("M10.754 20.621h-.573V21h.573z");
}

.n5strjkrd {
  fill: var(--svg-color--523c3e, #523c3e);
  d: path("m15.543 8.072l.37.01v-.298l.004-.275h-.365l-.009.568z");
}

.n61ivhbzt {
  fill: var(--svg-color--40424f, #40424f);
  fill-rule: evenodd;
  d: path("m6.647 12.01l.285.01v-.304l-.285-.009z");
}

.n763jcc6m {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M20.043 11.044h.284v-.284h-.284z");
}

.n87lqc7li {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("M6.638 17.073h.284v-.284h-.284z");
}

.n8fmx8b_m {
  fill: var(--svg-color--a37c3e, #a37c3e);
  fill-rule: evenodd;
  d: path("M15.253 14.108h.285v-.289h-.285z");
}

.n9iz6kbcd {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M13.82 17.363h.284v-.284h-.28z");
}

.na5sj2b_p {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("m14.397 16.795l.284-.005v-.284h-.284z");
}

.nc79_zbed {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M3.952 13.82v.29l.29.005l.028-.64l-.318-.019z");
}

.ncjo046st {
  fill: var(--svg-color--736e68, #736e68);
  d: path("M16.784 10.47h1.824v-.29h-1.824z");
}

.nfb6wpbih {
  fill: var(--svg-color--2c282a, #2c282a);
  fill-rule: evenodd;
  d: path("m6.647 11.707l.285.01l-.005-.29h-.284v.28z");
}

.nhs_92buk {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M16.784 6.929h.289v-.284h-.285v.284z");
}

.nhz99er3i {
  fill: var(--svg-color--3a722d, #3a722d);
  fill-rule: evenodd;
  d: path("M7.215 16.216H7.5v-.384h-.285z");
}

.ni_jlgbes {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M7.784 13.436v-.285H7.5v.284zm-3.254-.863h.289v-.284h-.284v.284z");
}

.njf23acfs {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M6.638 14.393h.284v-.285h-.284z");
}

.njfguab5u {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M11.427 12.863h-.284v.284h.284z");
}

.nl27ce-bf {
  fill: var(--svg-color--a37c3e, #a37c3e);
  fill-rule: evenodd;
  d: path("m11.138 19.474l.284-.004v-.29h-.284v.3z");
}

.nshhojsln {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m3.573 13.152l.38-.01v-.284h-.38z");
}

.nw98hcc0d {
  fill: var(--svg-color--6e9759, #6e9759);
  fill-rule: evenodd;
  d: path("M14.681 5.11v-.285h-.284v.284z");
}

.nway9h1kv {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M6.638 10.183h.284v-.285h-.284z");
}

.nyj23wb5l {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M11.427 10.47h.284v-.29h-.284z");
}

.nyta4nb7t {
  fill: var(--svg-color--497383, #497383);
  fill-rule: evenodd;
  d: path("m15.552 7.51l-.01-.298h-.284v.284z");
}

.nz-ismbka {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M8.362 8.073h.379V7.79h-.38z");
}

.o_bnlu0qx {
  fill: var(--svg-color--333941, #333941);
  d: path("M12.56 16.502h.297v-.673h-.274z");
}

.o-c59sbos {
  fill: var(--svg-color--656574, #656574);
  fill-rule: evenodd;
  d: path("M17.073 13.82h.285l.004-.38h-.284v.38z");
}

.o2bmuvn7z {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M6.638 17.073v-.284h-.284v.284z");
}

.o2otmfbbq {
  fill: var(--svg-color--18181c, #18181c);
  d: path("M10.181 19.183v.284h.284l.299.01l-.01-.294v-.285h-.284v.285z");
}

.o3dw4_brw {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M12.573 18.61h.284l.015-.38h-.299z");
}

.o3ys5acen {
  fill: var(--svg-color--70455c, #70455c);
  fill-rule: evenodd;
  d: path("M9.608 17.936h.284v-.285h-.284z");
}

.o4khypb4q {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M15.253 10.47h.29v-.29h-.285v.285z");
}

.o6-2mszsw {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M20.043 10.754h.284v-.573h-.284z");
}

.o76l24bby {
  fill: var(--svg-color--3a722d, #3a722d);
  fill-rule: evenodd;
  d: path("M7.784 16.784h.29V16.5h-.285v.284z");
}

.o7t329vkd {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M8.746 15.544h.573v-.284h-.573z");
}

.o9rdllb7r {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M12.285 5.972h.289v-.574h-.285v.569z");
}

.odmdambax {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M10.47 18.893v-.285h-.289v-.383h-.862v.667z");
}

.oga632z0p {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M13.53 9.03h.29v-.379h-.285v.38z");
}

.oichb-b-r {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M12.862 12.863h.668v-.284h-.668z");
}

.oiqigljnh {
  fill: var(--svg-color--b9bffb, #b9bffb);
  d: path("M13.146 10.755h.673v-.284h-.673zm-1.72-1.724h.285v-.668h-.284z");
}

.ojj5bubie {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M7.784 13.82h.29v-.38h-.285v.38zm10.151-.384h.384v-.285h-.379v.285z");
}

.ojzaetbsx {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M6.927 13.437h.284v-.28h-.284v.284z");
}

.okqnlp-or {
  fill: var(--svg-color--405478, #405478);
  fill-rule: evenodd;
  d: path("M9.892 8.652h.289v-.289h-.285v.285z");
}

.oks708buj {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M13.53 13.82h.29v-.38h-.285v.38z");
}

.okuplh9zi {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M3.957 14.392h.284v-.28h-.284v.285z");
}

.ol2rwjbqc {
  fill: var(--svg-color--914a5b, #914a5b);
  fill-rule: evenodd;
  d: path("M6.638 14.683v-.285h-.284v.285z");
}

.omfr0kbpj {
  fill: var(--svg-color--696e7d, #696e7d);
  fill-rule: evenodd;
  d: path("M13.151 14.97h.38v-.29h-.385v.285z");
}

.omuoz_bdj {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  d: path("M13.53 9.03v.29h.862v.572h.29v-.284h.861V9.32h-.862v-.284h-.573v-.384h-.284v.38z");
}

.oo60gkbfh {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M5.68 10.756h.285v-.284h-.284zm-.288.289h.284l.005-.284h-.284v.284zm-1.146 1.814h.284v-.284h-.284zm2.103-2.676h.284l.005-.285h-.284v.285z");
}

.op-nx27ch {
  fill: var(--svg-color--18181c, #18181c);
  d: path("M7.215 11.717h.56l.009.285l.293.004v-.289h.285v-.298l-.285.01l-.293.004l-.284-.005h-.285z");
}

.opbz2cbmd {
  fill: var(--svg-color--432927, #432927);
  fill-rule: evenodd;
  d: path("M9.892 7.217h.284v-.29h-.284z");
}

.opoblgcpw {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m7.21 9.602l.285-.019v-.27l-.284.005z");
}

.ormxxf29e {
  fill: var(--svg-color--909132, #909132);
  d: path("M8.746 16.5v.284h.573v-.568h-.284v.284z");
}

.orq_8dcbl {
  fill: var(--svg-color--141013, #141013);
  d: path("M13.819 13.82h.284v.284h-.568v.289h.857v-.953h-.568v.38z");
}

.otgmowbhn {
  fill: var(--svg-color--692027, #692027);
  fill-rule: evenodd;
  d: path("M8.362 15.828h.379v-.284h-.38z");
}

.ow6dn9ybs {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("m4.819 13.143l.289.004v-.284h-.29v.284z");
}

.oxq1s_buu {
  fill: var(--svg-color--6d6973, #6d6973);
  fill-rule: evenodd;
  d: path("m7.813 10.763l.255-.042v-.251h-.284z");
}

.p06qsjhti {
  fill: var(--svg-color--b8ba65, #b8ba65);
  fill-rule: evenodd;
  d: path("m14.369 14.96l.312.01v-.29h-.284l-.028.285z");
}

.p2ulb8bqq {
  fill: var(--svg-color--4b557d, #4b557d);
  fill-rule: evenodd;
  d: path("M16.5 8.362v-.294l-.284.005l-.02.289z");
}

.p376gdbol {
  fill: var(--svg-color--747a8a, #747a8a);
  fill-rule: evenodd;
  d: path("M15.543 14.108h.379v-.289h-.379z");
}

.p8u21o0_d {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M8.746 13.152h.284v-.289h-.284z");
}

.p98t9ibbq {
  fill: var(--svg-color--357952, #357952);
  d: path("M13.147 4.247h.672v-.384h-.673z");
}

.p9q8udrth {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M11.715 8.363H12V8.08h-.285z");
}

.pajvmv7bh {
  fill: var(--svg-color--736e68, #736e68);
  fill-rule: evenodd;
  d: path("m7.784 11.433l.29-.005v-.374l-.261-.024l-.029.398z");
}

.pb8aimbgn {
  fill: var(--svg-color--a6aa51, #a6aa51);
  fill-rule: evenodd;
  d: path("M8.362 16.784h.379V16.5h-.38z");
}

.pb8bgacko {
  fill: var(--svg-color--797981, #797981);
  fill-rule: evenodd;
  d: path("M16.5 14.393h.284v-.285H16.5z");
}

.pe70w77hz {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M13.53 9.608h.29V9.32h-.285v.285z");
}

.peko-tfeq {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M7.5 17.935v-.284h-.284v.284zM12 7.785h.284V7.5H12zM5.97 16.5v-.284h-.289v.284zm13.211-4.216h.284V12h-.284z");
}

.pfu14ij6r {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M8.357 8.357h.389v-.284h-.384z");
}

.phvlcxnrd {
  fill: var(--svg-color--40424f, #40424f);
  fill-rule: evenodd;
  d: path("M10.47 18.893h.284v-.285h-.284z");
}

.pibgdm2so {
  fill: var(--svg-color--383124, #383124);
  d: path("M12.285 18.225h.587v-.27l-.587-.023z");
}

.pid2ybbmy {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M12 6.928h.285l.033-.308H12z");
}

.pjlw5u6os {
  fill: var(--svg-color--141013, #141013);
  d: path("M7.784 9.03v.294h.583v-.673h-.294v.38h-.289");
}

.pmb16_bud {
  fill: var(--svg-color--914a5b, #914a5b);
  fill-rule: evenodd;
  d: path("M9.319 17.652h.284v-.289H9.32z");
}

.pmoo2c33x {
  fill: var(--svg-color--18181c, #18181c);
  fill-rule: evenodd;
  d: path("M9.892 17.363h.578v-.284h-.578z");
}

.pnziwac9a {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M13.53 12.573h.29v-.284h.283V12h-.284v-.284h-.284v.857z");
}

.pplnw6u2v {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M12 4.82h.284v-.285H12zm-.862.861h.284v-.284h-.284zm-6.892 6.893h.284v-.285h-.284zM19.47 9.608h.284V9.32h-.284z");
}

.psm6y8a0c {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("M15.543 11.717h.379v-.29h-.379z");
}

.pt07vpb4g {
  fill: var(--svg-color--986f2e, #986f2e);
  fill-rule: evenodd;
  d: path("M14.681 14.393h.284v-.285h-.284z");
}

.putf54tst {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  d: path("M12 10.754v-.284h-.573v.284z");
}

.pz-wk2bgd {
  fill: var(--svg-color--4f4b4e, #4f4b4e);
  d: path("M18.607 10.47h1.436v-.285h-.285l-.866.015l-.285-.02z");
}

.q-x4x8acu {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("m9.892 20.329l.284.004v-.289h-.284zm3.642-2.677h.284v-.289h-.284z");
}

.q0-ifn_xb {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M14.681 16.784h.284V16.5h-.284z");
}

.q0chrlk_r {
  fill: var(--svg-color--888e97, #888e97);
  d: path("M15.253 14.393v.289h.285v-.285h.388v-.289h-.668v.285z");
}

.q2-mm2bhg {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M11.138 20.044h.284v-.284h-.284z");
}

.q2g5vacan {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M14.392 11.044h.289v-.284h-.284v.284z");
}

.q3mubewzp {
  fill: var(--svg-color--5d8034, #5d8034);
  d: path("M7.215 16.784h.569V16.5H7.5v-.284h-.285z");
}

.q5go394ls {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m4.814 12l.284-.009v-.284l-.28.005v.284z");
}

.q7g35ybkj {
  fill: var(--svg-color--481c29, #481c29);
  d: path("M5.676 15.838h.294l.663-.01l.005-.284h-.962z");
}

.q92z20b_u {
  fill: var(--svg-color--481c29, #481c29);
  fill-rule: evenodd;
  d: path("M9.892 15.544h.303l-.01-.284h-.293z");
}

.q9gcn29mt {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M14.681 13.436h.573v-.285h-.573z");
}

.qaytl3zjj {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M5.97 16.5h.379v-.3l-.38.01z");
}

.qb-cx5zii {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M12 8.073h.285V7.79H12z");
}

.qb7um1ohk {
  fill: var(--svg-color--884b17, #884b17);
  fill-rule: evenodd;
  d: path("M6.927 16.216h.284v-.384h-.284z");
}

.qc3fyi3gi {
  fill: var(--svg-color--f9a31b, #f9a31b);
  d: path("M12.285 15.827h.298l-.01-.857h-.284v.857z");
}

.qei088bvc {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M10.755 20.333h.384v-.29h-.38v.285z");
}

.qevd3o9mp {
  fill: var(--svg-color--5f8342, #5f8342);
  fill-rule: evenodd;
  d: path("M14.392 4.82h.289v-.285h-.284v.284z");
}

.qeyarhb6o {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M8.362 15.254h.379v-.284h-.38z");
}

.qiamhc5wv {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M17.073 9.32c.08.724.209-.152.285.572l.577.01l.384-.01v-.284h.284V9.32h.29v-.284h-1.53v.284z");
}

.qj0aiwiax {
  fill: var(--svg-color--895b17, #895b17);
  fill-rule: evenodd;
  d: path("M13.535 17.363h.284l.005-.284h-.299z");
}

.qkjcdc3ur {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M19.754 11.044h.284v-.284h-.284zm-1.147 1.819h.285v-.284h-.285z");
}

.qm-ao_uhv {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m6.35 10.465l.283.01v-.294H6.35z");
}

.qq203hbmr {
  fill: var(--svg-color--481c29, #481c29);
  fill-rule: evenodd;
  d: path("M9.319 17.936h.284v-.285H9.32z");
}

.qqxwl7rsb {
  fill: var(--svg-color--914a5b, #914a5b);
  fill-rule: evenodd;
  d: path("M9.892 18.225h.289v-.285h-.285v.285z");
}

.qr_s-o-1i {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M8.746 19.183h.284v-.285h-.284z");
}

.qsczu9btu {
  fill: var(--svg-color--656574, #656574);
  fill-rule: evenodd;
  d: path("M17.362 13.436h.284v-.285h-.284z");
}

.qubwtbcuy {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M5.108 14.677h.568v-.284h-.568z");
}

.qunr_1bkp {
  fill: var(--svg-color--8e732b, #8e732b);
  fill-rule: evenodd;
  d: path("M10.18 16.5v-.283l-.288-.005v.289h.289");
}

.qvh3kkh9d {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M19.18 11.428h.285v-.384h-.256l-.028.379z");
}

.qvhouba6u {
  fill: var(--svg-color--b07449, #b07449);
  fill-rule: evenodd;
  d: path("M7.784 16.216h.29v-.384h-.285v.379z");
}

.qy3f-6bin {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M3.573 12.863h.38l.004-.284h-.379v.284z");
}

.qyq02kwao {
  fill: var(--svg-color--26653c, #26653c);
  fill-rule: evenodd;
  d: path("M17.935 8.362h.384v-.284h-.38v.284zM15.543 5.97h.379v-.29h-.379z");
}

.qyuu4d3kl {
  fill: var(--svg-color--692027, #692027);
  d: path("M4.814 14.393H5.97v-.285h-.29l-.866.005z");
}

.r_91roc1d {
  fill: var(--svg-color--26653c, #26653c);
  fill-rule: evenodd;
  d: path("M16.215 6.254V5.97h-.289v.284zm2.392 2.397v-.29h-.289v.285h.285z");
}

.r49fnmt5f {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M18.32 10.182h.284l.288.018v-.307h-.573z");
}

.r5bt8lbni {
  fill: var(--svg-color--544558, #544558);
  fill-rule: evenodd;
  d: path("m4.814 13.815l.294.004v-.379h-.303z");
}

.r9ap17b_m {
  fill: var(--svg-color--9097af, #9097af);
  fill-rule: evenodd;
  d: path("M13.53 15.833h.29v-.29h-.285v.285z");
}

.r9uzwbbcs {
  fill: var(--svg-color--4b557d, #4b557d);
  fill-rule: evenodd;
  d: path("M13.82 4.82h.284v-.285h-.285z");
}

.rahvrmbqn {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("M8.073 18.609h.284v-.379h-.284zm-2.392-2.392h.284v-.38h-.284z");
}

.rar8gzqvo {
  fill: var(--svg-color--909132, #909132);
  d: path("M6.927 14.393h.284v-.574h-.284z");
}

.rhstltbom {
  fill: var(--svg-color--497383, #497383);
  fill-rule: evenodd;
  d: path("M15.254 7.217v-.29h-.284v.285h.284z");
}

.rhve0sbqw {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M14.392 9.03v-.379h-.285v.38z");
}

.rhzcklb5m {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M8.362 12.284h.379V12h-.38z");
}

.rlzeo9b0o {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M19.47 11.717h.284v-.29h-.284z");
}

.rmd56ogjy {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("m14.681 15.543l.284.019v-.308h-.284z");
}

.rnsc-abrr {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("m10.755 7.76l.384.034V7.5h-.38v.26z");
}

.rorrkqcvp {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M9.608 7.5h.284v-.284h-.284z");
}

.rtwurzbli {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M16.5 14.683h.284v-.285H16.5z");
}

.rxwu76bxd {
  fill: var(--svg-color--141013, #141013);
  d: path("M14.393 11.044v.668h.573v-.284h.289v.284h.284v-.284l.043-.403l-.616.029v-.303l-.284.004v.285h-.284zm-3.638-2.392h.384v.38h-.38v.577h.38v.284h.284v-1.53h-.663v.285z");
}

.ryzzfoa5q {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M18.32 12.573h.284v-.284h-.285z");
}

.s-4kt85on {
  fill: var(--svg-color--e86973, #e86973);
  d: path("M20.328 10.754h.383v-.573h-.379v.573z");
}

.s-n4rwbex {
  fill: var(--svg-color--405478, #405478);
  fill-rule: evenodd;
  d: path("M8.746 9.893h.284l.047-.27l-.331-.015z");
}

.s0cgqqbug {
  fill: var(--svg-color--692027, #692027);
  fill-rule: evenodd;
  d: path("M6.354 14.108h.568v-.289h-.568z");
}

.s1jdotb-c {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M10.754 15.254v-.284h-.284v.284z");
}

.s2cq7no3c {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M8.363 18.893v-.285h-.284v.284z");
}

.s2dxghmyx {
  fill: var(--svg-color--453f40, #453f40);
  d: path("M15.576 11.025v-.308h-.322l-.289.033v.303l.616-.028z");
}

.s38w7zb3d {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M11.427 5.393h.284V5.11h-.284zm.857-.862h.29v-.284h-.285v.284z");
}

.s3ggt0-9o {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M17.073 9.319v-.284h.284V8.65l-.568-.014l-.289.014v.379c.725.08-.152.208.573.289");
}

.s4c_fyvao {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M9.03 7.5h.289v-.284h-.284V7.5z");
}

.s4mbxwb9z {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("M11.138 7.5h.284v-.284h-.284zm.289 10.435h.284v-.284h-.284z");
}

.s8gv6ibpi {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M17.647 13.436h.289v-.285h-.285v.285z");
}

.saqgz8b6z {
  fill: var(--svg-color--884b17, #884b17);
  d: path("M9.608 16.784h.284v.29h1.246v-.57l-.379-.004v.289h-.583v-.29h-.284v-.288h.284v-.379h-.568v.957z");
}

.sbetwybrr {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M9.319 7.5h.284v-.284H9.32z");
}

.schgaemdv {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M15.543 12h.379v-.284h-.379z");
}

.scs4eyvza {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M14.107 8.073h.285V7.5h-.285z");
}

.sd6djzeyn {
  fill: var(--svg-color--454b5a, #454b5a);
  fill-rule: evenodd;
  d: path("M13.82 14.677v.293l.284-.009v-.284l-.01-.284h-.275z");
}

.sdm_ye1pb {
  fill: var(--svg-color--529678, #529678);
  fill-rule: evenodd;
  d: path("M14.392 6.639h.289v-.38h-.284v.38z");
}

.se3iwyb9j {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("M12.285 9.03h.289v-.379h-.285v.38zm.578 0h.284v-.379h-.284z");
}

.sebc6kk-q {
  fill: var(--svg-color--736e68, #736e68);
  d: path("m18.892 10.201l.862-.019v-.284l-.284-.014l-.578.01z");
}

.sgw__0elo {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M18.892 9.608h.289V9.32h-.284v.285z");
}

.sipv73c_l {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  d: path("M15.543 9.32h.379v-.67h-.379z");
}

.siqmc6b9u {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M9.03 17.073h.573v-.284h-.568v.284z");
}

.sivg0zwbo {
  fill: var(--svg-color--523c3e, #523c3e);
  fill-rule: evenodd;
  d: path("M10.181 7.216h.284v-.294h-.284z");
}

.sjclw_nrh {
  fill: var(--svg-color--696e7d, #696e7d);
  d: path("M13.147 15.506v.327h.383v-.573h-.383v.25z");
}

.sl6z8u2rw {
  fill: var(--svg-color--895b17, #895b17);
  fill-rule: evenodd;
  d: path("M6.927 10.186h.284v-.293h-.284z");
}

.sprpy1bet {
  fill: var(--svg-color--6a2620, #6a2620);
  fill-rule: evenodd;
  d: path("M9.608 15.828h.284v-.284h-.284z");
}

.sr6rxj6-r {
  fill: var(--svg-color--2e3858, #2e3858);
  d: path("M16.5 8.362h1.435v-.284h-.862l-.568-.01v.294z");
}

.stce3abwu {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M15.543 5.683h.379v-.285h-.379zm2.392 2.392h.384V7.79h-.38v.284z");
}

.sutfk43ui {
  fill: var(--svg-color--6d748d, #6d748d);
  d: path("M16.5 12h.573v.284h.29V12h.283v-.284H16.5z");
}

.svbyywwfy {
  fill: var(--svg-color--6e9759, #6e9759);
  fill-rule: evenodd;
  d: path("M17.073 8.073h.578V7.79h-.573v.284z");
}

.svp2d2bpm {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M11.427 14.683h.284v-.285h-.284z");
}

.swau86eut {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M13.147 6.926h.672V5.681h-.284v.284h-.389z");
}

.sy_-vr-uf {
  fill: var(--svg-color--454b5a, #454b5a);
  d: path("m14.107 15.543l.005 1.256l.284-.005V16.5l-.009-.246v-.474l.005-.237l-.024-.265l-.26-.01z");
}

.syziv7bwn {
  fill: var(--svg-color--696e7d, #696e7d);
  d: path("m13.53 15.828l-.005.384v.867h.299l.005-.285h.284l-.005-1.25h-.289v.284z");
}

.sz-n3obtf {
  fill: var(--svg-color--986f2e, #986f2e);
  d: path("m12.853 16.5l.01.284h.284l.01-.568l-.005-.384h-.29l-.004.668z");
}

.szd2tczlg {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M9.319 19.754h.284v-.275l-.284-.01z");
}

.t-2qyzbkw {
  fill: var(--svg-color--888e97, #888e97);
  d: path("M15.926 14.108h.858v-.289h-.858z");
}

.t0pxxfbgx {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M12 14.965h.285v-.284H12z");
}

.t3nkx-kih {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("m12.871 18.23l.28-.005v-.285l-.28.015z");
}

.t41mokbmo {
  fill: var(--svg-color--141013, #141013);
  d: path("M8.073 15.256h.284v-.284h.389v.284h.573v-.573c-.725-.081.151-.209-.573-.285v.285h-.678v.573z");
}

.t47g_rb9f {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M18.607 12.573h.285v-.284h-.285z");
}

.t7v074pgs {
  fill: var(--svg-color--b8ba65, #b8ba65);
  fill-rule: evenodd;
  d: path("M5.97 14.393h.379v-.285h-.38z");
}

.t8y6_-6yi {
  fill: var(--svg-color--333941, #333941);
  fill-rule: evenodd;
  d: path("M10.755 7.5h.384v-.284h-.38V7.5z");
}

.ta6llroom {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M14.107 17.363h.285v-.284h-.285z");
}

.ta8nfh6-r {
  fill: var(--svg-color--529678, #529678);
  fill-rule: evenodd;
  d: path("m16.5 8.652l.284-.014v-.275H16.5z");
}

.tck6-x9jh {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M12.573 5.97v.284h.284v.672h.294V5.681h-.289v.284h-.284z");
}

.tdp90n2gs {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M10.755 9.893h.384v-.285h-.38v.285z");
}

.tech0p74h {
  fill: var(--svg-color--357952, #357952);
  fill-rule: evenodd;
  d: path("M12.862 4.531h.284v-.284h-.284z");
}

.tf4kajl0o {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M13.82 10.47h.284v-.29h-.285z");
}

.tfo08ed-y {
  fill: var(--svg-color--5f8342, #5f8342);
  fill-rule: evenodd;
  d: path("M16.784 6.929v-.284H16.5v.284z");
}

.tg0tlc7do {
  fill: var(--svg-color--26653c, #26653c);
  fill-rule: evenodd;
  d: path("m17.11 7.486l.252.014v-.284l-.251.005z");
}

.tikmb2bzw {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M10.755 18.225h.384v-.285h-.38v.285z");
}

.tl15kqbwi {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M19.754 11.717h.284v-.29h-.284z");
}

.tmcdq12si {
  fill: var(--svg-color--2e3858, #2e3858);
  d: path("M13.82 5.11v.284h.284v-.569h-.285zm.288.284h.284v2.108h-.284z");
}

.tprxwacyb {
  fill: var(--svg-color--4a5462, #4a5462);
  fill-rule: evenodd;
  d: path("M12.573 9.03h.284v-.379h-.284z");
}

.tr2pfzbfc {
  fill: var(--svg-color--692027, #692027);
  d: path("M7.216 14.393H7.5v.862h.573v-.573h.673v-.285h-.668v-.289H7.21v.285z");
}

.trj3l7w0f {
  fill: var(--svg-color--481c29, #481c29);
  fill-rule: evenodd;
  d: path("M9.892 17.936h.573v-.284h-.568v.284zm-3.254-2.392h.573v-.284h-.569v.284z");
}

.tsqfsuqex {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M9.319 15.544h.284v-.284H9.32z");
}

.tswse19rn {
  fill: var(--svg-color--6a2620, #6a2620);
  fill-rule: evenodd;
  d: path("M7.784 17.073h.29v-.284h-.285v.284z");
}

.tt_kt0bmk {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.716 5.393H12V5.11h-.284zm.568-.573h.29v-.284h-.285v.284zM12 5.11h.284v-.285H12zm-.862.283h.284V5.11h-.284zm8.616 4.216h.285V9.32h-.285zm-11.97-.957h.29v-.289h-.285v.285zM12 4.532h.284v-.285H12zm-.862 1.44h.284v-.29h-.284zm.289-.863h.284V4.82h-.284zm-7.47 7.466h.284v-.285h-.284zm5.362-5.358h.284v-.289H9.32z");
}

.tt6_llbai {
  fill: var(--svg-color--40424f, #40424f);
  fill-rule: evenodd;
  d: path("m16.216 13.143l.284.01v-.29h-.284z");
}

.tu1uyvbvd {
  fill: var(--svg-color--7c828a, #7c828a);
  d: path("m14.369 15.278l.023.265h.285v-.284l.284-.005l.004-.284h-.284l-.312-.01z");
}

.ty1-ks0wo {
  fill: var(--svg-color--736e68, #736e68);
  d: path("M18.607 11.038h.294l.014-.26l.322-.015l.522-.01h.284v-.283h-1.435z");
}

.tym128b8b {
  fill: var(--svg-color--785744, #785744);
  d: path("M10.465 6.924v.289h.29v-.568h-.285v.284z");
}

.u_10aikjr {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M14.681 9.893h.284v-.285h-.284z");
}

.u1w_w6g3e {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M10.181 20.62h.573v-.288h-.573v.289");
}

.u2jg5135p {
  fill: var(--svg-color--333235, #333235);
  fill-rule: evenodd;
  d: path("M15.543 8.362h.37v-.28l-.37-.009z");
}

.u2z27j8cp {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.427 5.683h.284v-.285h-.284z");
}

.u5ljsmbgi {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M10.755 6.254h.384V5.97h-.38v.284z");
}

.u7as9ac6j {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("m12.318 6.226l-.029-.256c-.497.052-.175-.114-.293.208z");
}

.u9se70hyk {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("M14.107 17.073h.285l.005-.284l-.285.01z");
}

.uaj2zj-ay {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M5.392 15.828v-.284h-.284v.284zm-.573-.573v-.284h-.284v.284zm-.29-3.254h.285l.005-.284h-.284V12zm.29-.284l.284-.005v-.284h-.284z");
}

.ub3rip0da {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M5.681 14.683h.284v-.285h-.284z");
}

.ud8fgib8b {
  fill: var(--svg-color--797981, #797981);
  fill-rule: evenodd;
  d: path("M16.216 14.683h.284v-.285h-.284z");
}

.ugzq3rbnn {
  fill: var(--svg-color--40424f, #40424f);
  fill-rule: evenodd;
  d: path("M5.108 13.44h.284v-.289h-.284z");
}

.uign7rkag {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  fill-rule: evenodd;
  d: path("M13.147 9.608h.383V9.32h-.379v.285z");
}

.ujnvzhbhz {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("m9.608 20.044l-.005-.285H9.32v.285zm-1.824-1.82v-.284H7.5v.285z");
}

.ukthf7bne {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M15.253 6.638h.285V5.68h-.285z");
}

.ulnl41b9b {
  fill: var(--svg-color--b8ba65, #b8ba65);
  fill-rule: evenodd;
  d: path("M10.755 19.183h.384v-.285h-.38v.285z");
}

.um9lyob5h {
  fill: var(--svg-color--333941, #333941);
  d: path("M11.427 7.217V7.5h-.289v.294l-.379-.034h-.289v.37h.284v.232h.673v-.284h.284v-.29h.29v-.861h-.285v.284h-.289z");
}

.uoju7nb8d {
  fill: var(--svg-color--986f2e, #986f2e);
  fill-rule: evenodd;
  d: path("m10.181 7.784l.289-.023V7.5h-.289z");
}

.uph4zcb0e {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("m6.628 16.203l.299.01v-.38l-.299-.004v.38z");
}

.usmfcgbev {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M10.754 12v-.284h-.284V12z");
}

.uwy21lbck {
  fill: var(--svg-color--986f2e, #986f2e);
  fill-rule: evenodd;
  d: path("M15.543 14.683h.379v-.285h-.379z");
}

.uzxpp_b9f {
  fill: var(--svg-color--6e9759, #6e9759);
  fill-rule: evenodd;
  d: path("m16.216 7.5l.27-.013l.014-.275h-.284z");
}

.v_6j5_bzg {
  fill: var(--svg-color--357952, #357952);
  d: path("M13.82 6.927v.284h.284v-.957h-.285z");
}

.v-d4qkcab {
  fill: var(--svg-color--895b17, #895b17);
  d: path("m5.97 16.217l.379-.015h.284v-.379l-.663.014z");
}

.v-oj91b5n {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M17.361 7.216h.284v-.289h-.284zm-1.435-1.535h.284v-.284h-.284zm2.392 2.393h.284v-.285h-.284zm-3.065-2.966h.285v-.284l-.285-.005z");
}

.v-wiy-k3s {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M10.755 12h.384v-.284h-.38V12z");
}

.v30ut-rsp {
  fill: var(--svg-color--2e3239, #2e3239);
  fill-rule: evenodd;
  d: path("m9.892 19.474l.289-.01v-.283h-.29z");
}

.v47pq1b4b {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M13.82 14.108h.284v-.289h-.285z");
}

.v48t_da8v {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M3.957 14.393v-.285h-.38v.285z");
}

.v5qgmob_h {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("m10.46 9.902l.295-.01v-.284h-.285z");
}

.v67jwzbhy {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("M13.147 4.82v.284h.383v-.569h-.379v.284z");
}

.v9kyoob2z {
  fill: var(--svg-color--141013, #141013);
  d: path("M13.151 9.608V9.32h.38v-.284h-.669v.569h.284z");
}

.vc9c_cbsy {
  fill: var(--svg-color--40424f, #40424f);
  fill-rule: evenodd;
  d: path("M17.935 10.183h.384v-.285h-.38v.285z");
}

.vd3so5bmv {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M14.97 10.47h.284v-.29h-.284z");
}

.vd7cxu88n {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M12.285 14.683h.289v-.285h-.285v.285z");
}

.vdnjis4zn {
  fill: var(--svg-color--6d748d, #6d748d);
  d: path("m12 17.354l.284.01v-.285l.005-.303l.005-.27h-.303l.005.852z");
}

.ve401_bwh {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M9.03 12.863h.289v-.284h-.284v.284z");
}

.vfysoi1xv {
  fill: var(--svg-color--141013, #141013);
  d: path("M11.427 14.681v.285h-.284v-.285zm.284 0h-.284v-.284h.284zm-.957-.573v.284h-.284v-.284zm0 0v-.289h.673v.284h-.673zm-.284-.672v.383h-.289v-.379h.284zm.668-.573h.284v.284h-.284zm-.668.573v-.285h-.578v-.288h.862v.573zm2.392-2.392h.284v.378h-.284zm2.108-1.152h-.573v.29h-.29v.284h-.288v.289h-1.53v.284h.284V12h-.284v.284h-.29v.29h-.856v-.285h-.389V12h-.284v-.284h-.289v-.289h-.284v-.383h-.29v-.285H9.03v.285h-.284v-.285l-.393-.038v.356l.009.34l.668.01h.289v.284h.573v.863h-.284v.284h-.29v.293h.574v.285H8.746v.383c.19.02.16.005.407.26l.19.195c.099.076.009.095.265.119v1.146h.284v-.569h.284v-.578h.294v.578h.284v.285h.957v-.574h.573v-.284H12v-.578h-.284v-.668h.568v.285h.862v-.285h-.284v-.288h-.284v-.285h.952v-.867h.289v.29h.284v.284h.289v.289h.289v.284h.573v.293h.284v-.573h-.568v-.289h-.289V12h-.284v-.284h-.29v-.672h.285v-.285h.284v-.289h.294v-.289h.284v-.284h.284v.284h.389V9.32h-.384v.285h-.573z");
}

.vg7x4n7ns {
  fill: var(--svg-color--1e2342, #1e2342);
  fill-rule: evenodd;
  d: path("M13.82 4.247h.284v-.384h-.285z");
}

.vgxxbz7ih {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M13.53 14.971h.29v-.293h-.285v.293z");
}

.vhvsdhbgx {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M11.71 15.254h.285v-.284h-.284z");
}

.vlz-evhuk {
  fill: var(--svg-color--1b2025, #1b2025);
  d: path("M12.284 17.074v.289L12 17.358v.294h-.284v.284h-.29v1.246h.285v-.284h.303L12 18.22h.289v-.284l.587.019l-.01-1.165l-.293-.01l.005.294z");
}

.vowttebqm {
  fill: var(--svg-color--357952, #357952);
  d: path("M14.392 7.5v.573h.289v.957h.573v-.38h-.284v-.582h.573l.01-.568l-.299-.005v-.284h-.284v-.29h-.289v-.283h-.284v.857z");
}

.vqb81ccfw {
  fill: var(--svg-color--383539, #383539);
  d: path("m15.58 10.72l.342.034h.289v-.284h-.668l.038.246z");
}

.vqgh07fig {
  fill: var(--svg-color--141013, #141013);
  d: path("M14.682 9.031v.29h.862v-.669h-.285v.38zm-2.397.578V8.363H12V9.61z");
}

.vqqtqgbtk {
  fill: var(--svg-color--895b17, #895b17);
  fill-rule: evenodd;
  d: path("m3.573 13.435l.38.02v-.313l-.38.01z");
}

.vr3roybgd {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M18.892 12h.289v-.284h-.284V12z");
}

.vrw2l3g0j {
  fill: var(--svg-color--4f4b4e, #4f4b4e);
  fill-rule: evenodd;
  d: path("m8.073 11.428l.289-.01l-.015-.34l-.274-.02z");
}

.vshpaab4d {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M10.181 11.428v-.384h-.284v.379h.284zm2.103 0v-.384H12v.379h.284z");
}

.vv1cu23ka {
  fill: var(--svg-color--2c555d, #2c555d);
  d: path("M14.97 6.64v.284h.284V5.398h-.284z");
}

.vw8grccll {
  fill: var(--svg-color--8c892a, #8c892a);
  fill-rule: evenodd;
  d: path("m4.53 14.682l.284-.005v-.284H4.53z");
}

.vxvcbbm3s {
  fill: var(--svg-color--70455c, #70455c);
  fill-rule: evenodd;
  d: path("M5.681 14.108h.284v-.289h-.284z");
}

.vykib43iq {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  d: path("M11.427 9.031v.862h.284v.29H12v.283h.284v.29h.867v-.285h.668v-.289h-1.246v-.284h-.284v-.289H12V8.363h-.284v.668z");
}

.vz7zibbft {
  fill: var(--svg-color--8c892a, #8c892a);
  fill-rule: evenodd;
  d: path("M9.892 20.044h.284l.005-.284h-.285v.284z");
}

.w_-geeb9v {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M14.681 13.152h.573v-.289h-.573z");
}

.w20v3rkws {
  fill: var(--svg-color--793a80, #793a80);
  fill-rule: evenodd;
  d: path("M7.216 17.651H7.5v-.284h-.29v.284z");
}

.w393iheox {
  fill: var(--svg-color--243752, #243752);
  d: path("M9.892 9.03v.285l-.573.023v.27h.862v-.957h-.284v.38z");
}

.w3dyk7b9i {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M8.073 14.108h.284v-.289h-.284z");
}

.w3vogzboo {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M9.03 10.754h-.284v.284h.284z");
}

.w5ehjrbph {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M15.543 12.574h.379v-.284h-.38zm-9.194 4.211v-.284h-.38v.284zm5.935-12.538h.289v-.384h-.284v.38z");
}

.w77z-8bdo {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.138 20.328h.284v-.284h-.284z");
}

.w7hbqgiiz {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M17.935 12.863h.384v-.284h-.38v.284z");
}

.wfob4mb9u {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("M12.573 5.394h.284v-.569h-.284z");
}

.whdyz6b6v {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M8.362 18.893h.379v-.285h-.38z");
}

.wk8cmum2x {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M15.253 16.217h.285v-.384h-.285zm.29-.389h.378v-.284h-.379z");
}

.wkpnuub7v {
  fill: var(--svg-color--5f8342, #5f8342);
  fill-rule: evenodd;
  d: path("M12.862 4.247h.284v-.384h-.284zM16.5 6.639V6.26h-.284v.38z");
}

.wmivy5lbv {
  fill: var(--svg-color--453f40, #453f40);
  d: path("m5.387 11.692l1.26.014l-.01-.284l-.96.014l-.285-.014v.27z");
}

.woincyj1b {
  fill: var(--svg-color--40424f, #40424f);
  fill-rule: evenodd;
  d: path("M12.573 4.82h.284v-.285h-.284z");
}

.wq21gubql {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M3.948 13.143h.871v-.285h-.866v.285z");
}

.wrkgoihru {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M12.284 11.428h.29v-.384h-.285v.379zm-2.103 0h.284v-.384h-.284z");
}

.ws4q350jk {
  fill: var(--svg-color--357952, #357952);
  fill-rule: evenodd;
  d: path("M15.253 6.929v.284h.285v-.568h-.285z");
}

.wuegoqbfe {
  fill: var(--svg-color--8c892a, #8c892a);
  fill-rule: evenodd;
  d: path("M12.29 18.608h.283v-.379l-.284-.004z");
}

.wv3xxachh {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M13.53 7.217h.29v-.29h-.285v.285z");
}

.wvdluvb0f {
  fill: var(--svg-color--395894, #395894);
  fill-rule: evenodd;
  d: path("m9.077 9.622l.242-.014v-.27l-.19-.019z");
}

.wxngvebht {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  d: path("M12.285 7.784v.29h.578v-.285h.284V7.5h-.569v.284z");
}

.wzp94bccf {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M13.146 16.784v.29l.379.004v-.862h-.37l-.01.578zM9.892 7.5h.573l.005.26h.284v-.544h-.858V7.5z");
}

.x-d5i6blm {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M19.47 11.428h.284v-.384h-.284zm.573 0h.284v-.384h-.284zM8.362 14.393h.379v-.284h-.38zm.383 4.789v-.284h-.383v.284z");
}

.x-h0kx1ld {
  fill: var(--svg-color--69432d, #69432d);
  fill-rule: evenodd;
  d: path("M10.47 6.639h.284v-.38h-.284z");
}

.x-lj-80lr {
  fill: var(--svg-color--b07449, #b07449);
  fill-rule: evenodd;
  d: path("M8.073 16.5h.284v-.284h-.284z");
}

.x19x-8zqw {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M6.35 16.784h.288V16.5h-.284v.284z");
}

.x2m_v4bra {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M12 12.284h.285V12H12z");
}

.x5tx1qr7u {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M8.073 10.183h.298l-.01-.285h-.284v.285z");
}

.x6nsc9l_h {
  fill: var(--svg-color--888e97, #888e97);
  fill-rule: evenodd;
  d: path("M15.543 14.97h.379v-.285l-.379-.004z");
}

.x7kk72paq {
  fill: var(--svg-color--6a2620, #6a2620);
  d: path("M7.21 17.367h.29l.284-.005v-.284l-.573-.005z");
}

.x7mezqhdq {
  fill: var(--svg-color--243752, #243752);
  d: path("M9.892 8.362h.289V7.5h-.285v.862z");
}

.x87m27bet {
  fill: var(--svg-color--5f8342, #5f8342);
  fill-rule: evenodd;
  d: path("M18.607 9.03h.285v-.379h-.285z");
}

.x91carhzd {
  fill: var(--svg-color--441320, #441320);
  d: path("M8.362 18.61h.379v.284h.284v-.663h-.663z");
}

.x98af8y3s {
  fill: var(--svg-color--141013, #141013);
  d: path("M14.97 12.001v.284h.569v-.284h-.285v-.284h-.284zm.284-3.349v-.289h.285V8.08h-.569v.569h.284z");
}

.xewd2gbpl {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M14.97 14.393h.284v-.285h-.284z");
}

.xfhpkcbjd {
  fill: var(--svg-color--6a2620, #6a2620);
  d: path("M10.47 17.363h.284v.285h.384v-.569h-.668z");
}

.xiz-tacvm {
  fill: var(--svg-color--f9a31b, #f9a31b);
  fill-rule: evenodd;
  d: path("M10.755 9.03h.384v-.379h-.38v.38z");
}

.xmyfwqbyu {
  fill: var(--svg-color--747a8a, #747a8a);
  d: path("M14.681 13.435v.384h-.284v.284h.857v-.284h.285v-.379h.388v.379h.857v.284h.29v-.663h.288v-.294H16.5l-.284-.004l-.673.01h-.284v.283z");
}

.xnfpfdbiq {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M13.147 7.784h.383V7.5h-.379v.284z");
}

.xphp8vebp {
  fill: var(--svg-color--6e9759, #6e9759);
  d: path("m17.073 7.784l.038-.299h-.626l-.014.327l.602-.023z");
}

.xvu5g6bil {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("M12.862 15.829h.284v-.317h-.284z");
}

.xxpazw-fk {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("m8.074 8.362l.284-.005v-.284h-.284zm-.858.957H7.5v-.284h-.284zm0 8.332l-.005-.284l-.284-.005v.284h.284zm7.177-.578h.288v-.284h-.284v.284zm-2.108 2.108h.289v-.284h-.285v.284zm7.186-9.298l.284.01v-.285h-.284z");
}

.y_7ft4b_w {
  fill: var(--svg-color--141013, #141013);
  d: path("M8.363 12.284v.29h-.284v.577h.663v-.289h.289v-.284h.289V12h-.574v.284z");
}

.y_sr07bjn {
  fill: var(--svg-color--797981, #797981);
  fill-rule: evenodd;
  d: path("M15.543 15.254h.379v-.284h-.379z");
}

.y-h0_qbnu {
  fill: var(--svg-color--a37c3e, #a37c3e);
  fill-rule: evenodd;
  d: path("M8.746 17.073h.284v-.284h-.284z");
}

.y09w_ftul {
  fill: var(--svg-color--8d6320, #8d6320);
  fill-rule: evenodd;
  d: path("M4.819 12.572v.285h.284v-.56l-.284-.004v.284z");
}

.y45p-no7f {
  fill: var(--svg-color--18181c, #18181c);
  d: path("m6.633 10.474l.294-.004l.573-.01l.284.005h.285l.004-.284H7.5l-.284.01l-.289-.006l-.289-.004v.293z");
}

.y5vnbsbku {
  fill: var(--svg-color--b48c53, #b48c53);
  fill-rule: evenodd;
  d: path("M10.755 18.608h.384v-.383h-.38v.379z");
}

.y8dbadcsn {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.715 10.47H12v-.29h-.285z");
}

.y9hgrzhfa {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M12 11.044h.285v-.284H12z");
}

.yast61byh {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M12 10.754h.285v-.284H12z");
}

.ybmhq6b3e {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M6.927 9.608h.284V9.32h-.284z");
}

.ybux_rj3q {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("m14.965 10.75l.29-.034v-.246h-.285l-.005.284z");
}

.ye0ik5ygl {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M18.893 12.573h.288v-.284h-.284v.284zM4.245 14.681v-.284h-.284v.284z");
}

.ye3z92bnj {
  fill: var(--svg-color--357952, #357952);
  d: path("M14.107 5.393h.285v.862h.284v.383h.293v-1.53h-.572v-.573h-.29zm1.436 1.245h.379v.573h.578l-.015.275h.626v-.265l-.323.01v-.304H16.5v-.284h-.285v-.388h-.289V5.97h-.383z");
}

.yi8a_ccvk {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M12.573 18.892h.284v-.284h-.284zm-.858-10.819H12V7.79h-.285z");
}

.yiiytzbrf {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M15.253 10.183h.285v-.285h-.285z");
}

.yjls5qngb {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M14.681 12h.284v-.284h-.284z");
}

.ykdancbjs {
  fill: var(--svg-color--24242a, #24242a);
  fill-rule: evenodd;
  d: path("M12.573 7.217h.284v-.29h-.284z");
}

.ykv54_b7l {
  fill: var(--svg-color--5f3547, #5f3547);
  fill-rule: evenodd;
  d: path("M10.47 18.608v-.383h-.289v.379h.284z");
}

.ympds1blj {
  fill: var(--svg-color--529678, #529678);
  fill-rule: evenodd;
  d: path("M13.53 5.683h.29v-.285h-.285v.285z");
}

.ymre0zp_n {
  fill: var(--svg-color--4a5462, #4a5462);
  d: path("m7.21 12.02l.57-.024v-.284h-.57z");
}

.ymtw_38sy {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M8.363 14.393v-.285h-.284v.285z");
}

.yn3y5vsyc {
  fill: var(--svg-color--8d6320, #8d6320);
  d: path("M8.073 17.073h.672v-.284h-.667v.284z");
}

.yphiwmb5h {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M8.362 15.544h.379v-.284h-.38z");
}

.ypoq-c_3x {
  fill: var(--svg-color--5d8034, #5d8034);
  fill-rule: evenodd;
  d: path("M7.5 16.216h.284v-.384H7.5z");
}

.yq4nn8bim {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M4.53 14.971h.284v-.293H4.53z");
}

.yr4nlgssq {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M12.573 4.531h.284v-.284h-.284z");
}

.yrs9h26yx {
  fill: var(--svg-color--b9bffb, #b9bffb);
  fill-rule: evenodd;
  d: path("M8.073 12.573h.284v-.284h-.284z");
}

.ysvzg5wob {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M7.5 17.936h.284v-.285H7.5z");
}

.ytv_ek9-l {
  fill: var(--svg-color--24242a, #24242a);
  d: path("m15.543 13.152l.668-.01v-.284h-.668z");
}

.yvrr_ii0o {
  fill: var(--svg-color--6d748d, #6d748d);
  fill-rule: evenodd;
  d: path("m6.354 12.29l.289.005l.01-.284h-.304l.005.284z");
}

.yy3mulbls {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M14.392 11.717v-.673h-.285v.668h.285z");
}

.z-dec2ebb {
  fill: var(--svg-color--fffc40, #fffc40);
  d: path("M10.181 14.97h.284v-.577h-.284z");
}

.z23ylqbzf {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M5.97 10.47h.379v-.29H5.97zm-.862.956h.284v-.383h-.284zm8.038 6.798h.384v-.284h-.379v.284z");
}

.z3f_wmz1k {
  fill: var(--svg-color--18181c, #18181c);
  d: path("M10.47 17.652v.957h.284v-.668h.384v-.289h-.379v-.289h-.289z");
}

.z4rnmacse {
  fill: var(--svg-color--529678, #529678);
  fill-rule: evenodd;
  d: path("M14.97 6.929v-.284h-.289v.284z");
}

.z5ndmon-p {
  fill: var(--svg-color--24242a, #24242a);
  d: path("M16.784 10.183h1.15v-.285h-1.146v.285z");
}

.z5nywluyn {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M12 19.183h.285l.01-.285h-.28z");
}

.z79z5nbnb {
  fill: var(--svg-color--357952, #357952);
  d: path("M15.918 7.784h.312l-.019.289l.29-.005l.572.005v-.284l-.601.023l.014-.327l-.275.015l-.293.009z");
}

.z8eo16i8s {
  fill: var(--svg-color--2b1c25, #2b1c25);
  d: path("M9.03 18.893v.288h.289v-.957l-.29.01v.663zm-.668-.953h.957v-.289h-.957z");
}

.zc0pgkbae {
  fill: var(--svg-color--888e97, #888e97);
  fill-rule: evenodd;
  d: path("M14.392 14.393h.289v-.285h-.284v.285z");
}

.zepdvodcl {
  fill: var(--svg-color--909132, #909132);
  fill-rule: evenodd;
  d: path("M7.784 14.108h.29v-.289h-.285v.284z");
}

.zfnyub_ub {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("M19.754 9.892h.284v-.284h-.284zM9.608 7.216h.284v-.289h-.284zm.862-.961h.284V5.97h-.284zm1.246-1.147H12v-.284l-.284-.005z");
}

.zggt9ulgm {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M16.5 14.97h.284v-.29H16.5z");
}

.zh8fepbjd {
  fill: var(--svg-color--f9a31b, #f9a31b);
  d: path("M12.285 12h.289v-.572h-.285V12z");
}

.zhds1vbgi {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M9.03 19.47h.284l.005-.29h-.29z");
}

.zj5-kpbeh {
  fill: var(--svg-color--e3e6ff, #e3e6ff);
  d: path("M7.785 12.002c-.043.516.019.075-.11.27c-.122.19-.175.26-.459.307h-.284l-.005.285h.578v.293l.284-.004v.284h.285v.384h.284v.284h.388v.289c.725.08-.151.208.573.289v.573h.285v-.862c-.252-.029-.161-.048-.261-.119l-.19-.19c-.246-.26-.217-.246-.407-.264v-.38h1.146v-.288H9.32v-.29h-.284v.285H8.07v-.284h-.284v-.285h.284v-.289h.284v-.288h.388v-.285h.285v-.289l-.663-.01v.3h-.29v.288l-.293-.01z");
}

.zkf506b0j {
  fill: var(--svg-color--e86973, #e86973);
  fill-rule: evenodd;
  d: path("m5.965 10.754l.38-.014v-.275h-.38z");
}

.znzftmxyk {
  fill: var(--svg-color--888e97, #888e97);
  fill-rule: evenodd;
  d: path("M15.253 15.254h.29v-.284h-.285v.284z");
}

.zoi2u7b_g {
  fill: var(--svg-color--bc4a9b, #bc4a9b);
  fill-rule: evenodd;
  d: path("M17.068 14.104h.294v-.285h-.284l-.005.284z");
}

.zop65imip {
  fill: var(--svg-color--661e17, #661e17);
  fill-rule: evenodd;
  d: path("M6.927 17.073h.284v-.284h-.284z");
}

.zvu2scqtd {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M11.427 12.573v-.284h-.284v.284z");
}

.zwpvmocrp {
  fill: var(--svg-color--2c555d, #2c555d);
  fill-rule: evenodd;
  d: path("M13.82 6.254h.284V5.97h-.285z");
}

.zxl-_3bfr {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M4.53 14.97v-.29h-.284v.285h.284zm5.362 5.357v-.284h-.284v.284z");
}

.zyjvqhb4r {
  fill: var(--svg-color--fa6a0a, #fa6a0a);
  fill-rule: evenodd;
  d: path("M10.47 11.717h.284v-.29h-.284z");
}

.zyx96-z4y {
  fill: var(--svg-color--141013, #141013);
  fill-rule: evenodd;
  d: path("M11.716 19.183H12l.014-.285h-.303v.285z");
}

.zyxuu2b-e {
  fill: var(--svg-color--986f2e, #986f2e);
  fill-rule: evenodd;
  d: path("M15.926 14.393h.573v-.285h-.573z");
}

.zzcl__bjq {
  fill: var(--svg-color--fffc40, #fffc40);
  fill-rule: evenodd;
  d: path("M14.681 10.754h.284v-.284h-.284z");
}

</style>
