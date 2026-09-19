<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#f975idbd)"><circle fill="url(#f975id0)" class="uchjg6bzz"/></g><g filter="url(#f975idbe)"><circle fill="url(#f975idbr)" class="xidifjy9q"/></g><g filter="url(#f975idbf)"><circle fill="url(#f975idbs)" class="jr4v0ukgt"/><circle fill="url(#f975id1)" class="jr4v0ukgt"/></g><g filter="url(#f975idbg)"><circle class="qyjw7-0zy"/><circle fill="url(#f975id2)" class="yiqosdblp"/><circle fill="url(#f975id3)" class="yiqosdblp"/></g><path fill="url(#f975idbt)" class="g2i_i4xjf"/><path fill="url(#f975id4)" class="g2i_i4xjf"/><path fill="url(#f975idbu)" class="g2i_i4xjf"/><path fill="url(#f975id5)" class="g2i_i4xjf"/><path fill="url(#f975id6)" class="g2i_i4xjf"/><path fill="url(#f975id7)" class="g2i_i4xjf"/><g filter="url(#f975idbh)"><path class="x2xf-c9hj"/></g><g filter="url(#f975idbi)"><path class="w0rs-3b8j"/><path fill="url(#f975idbv)" class="px_573nlv"/><path fill="url(#f975idbw)" class="px_573nlv"/><path fill="url(#f975idbx)" class="px_573nlv"/></g><path stroke="url(#f975idby)" class="lrujm9bib"/><g filter="url(#f975idbj)"><path class="iw_nvbbot"/></g><g filter="url(#f975idbk)"><path class="h1fy1vbrb"/></g><path class="b6l3cf9pv"/><path fill="url(#f975id8)" class="dvdi_0mte"/><path class="vun_f_b1g"/><g filter="url(#f975idbl)"><path class="ixgckfzug"/><path fill="url(#f975id9)" class="wxmecd6-s"/></g><g filter="url(#f975idbm)"><path fill="url(#f975idbz)" class="y01fd9bap"/></g><path class="iy-lxtbwg"/><path fill="url(#f975ida)" class="u55u-0b4m"/><path class="lf10uubwu"/><g filter="url(#f975idbn)"><path fill="url(#f975idc0)" class="m9q5wwbfu"/></g><g filter="url(#f975idbo)"><ellipse transform="rotate(-27.914 11.367 16.986)" class="j2g_c5b-q"/><ellipse fill="url(#f975idb)" transform="rotate(-27.914 11.367 16.986)" class="p1g-jpb-t"/></g><g filter="url(#f975idbp)"><path stroke="url(#f975idc1)" class="zk2ex8jhu"/></g><g filter="url(#f975idbq)"><path stroke="url(#f975idc2)" class="wb0uqbbzd"/></g><path class="rf-_flbmk"/><path fill="url(#f975idc)" class="a5i1kuj7c"/><path fill="url(#f975idd)" class="coyn1nb7m"/><path fill="url(#f975ide)" class="h5ltaluah"/><path fill="url(#f975idf)" class="pglbsdbvr"/><path fill="url(#f975idg)" class="jnm8_mb_z"/><path fill="url(#f975idh)" class="jhuu-edco"/><path fill="url(#f975idi)" class="zhxd5zb8u"/><path fill="url(#f975idj)" class="yry3ztbut"/><path fill="url(#f975idk)" class="c5_ol8bjh"/><path fill="url(#f975idl)" class="v8a7dt81c"/><path fill="url(#f975idm)" class="bf0rmc-1l"/><path fill="url(#f975idn)" class="yvy42ib-k"/><path fill="url(#f975ido)" class="kmw42bjwn"/><path fill="url(#f975idp)" class="dhq9j25jd"/><path fill="url(#f975idq)" class="j9v4grv9o"/><path fill="url(#f975idr)" class="pqxqhbcxf"/><path fill="url(#f975ids)" class="iam3n-bgk"/><path fill="url(#f975idt)" class="v2no4h1wv"/><path fill="url(#f975idu)" class="dlapr5yrz"/><path fill="url(#f975idv)" class="zv65uvq-p"/><path fill="url(#f975idw)" class="ieslakbcn"/><circle fill="url(#f975idx)" class="daeuyr99u"/><path fill="url(#f975idy)" class="aujie4ucq"/><path fill="url(#f975idz)" class="ys_ne_6os"/><path fill="url(#f975id10)" class="vms4etbtb"/><path fill="url(#f975id11)" class="qdsj2fbbv"/><path fill="url(#f975id12)" class="ihoit7b7z"/><path fill="url(#f975id13)" class="xgp9fbc0s"/><path fill="url(#f975id14)" class="r9tu_7jps"/><ellipse fill="url(#f975id15)" transform="rotate(46.894 9.195 3.27)" class="ik-2hub9b"/><path fill="url(#f975id16)" class="q__c000km"/><path fill="url(#f975id17)" class="c7m5vwvei"/><path fill="url(#f975id18)" class="mj47_jb0h"/><path fill="url(#f975id19)" class="l3e87gbvo"/><path fill="url(#f975id1a)" class="eunszr3ix"/><path fill="url(#f975id1b)" class="bdgkthbrm"/><path fill="url(#f975id1c)" class="ufry78bci"/><ellipse fill="url(#f975id1d)" transform="rotate(46.894 10.524 2.662)" class="vmkpn34ef"/><path fill="url(#f975id1e)" class="tes8b00ay"/><path fill="url(#f975id1f)" class="ojwcfntba"/><path fill="url(#f975id1g)" class="nlyb9eb_c"/><path fill="url(#f975id1h)" class="atxkpcagh"/><path fill="url(#f975id1i)" class="d-uusg05r"/><path fill="url(#f975id1j)" class="z2ichlbax"/><path fill="url(#f975id1k)" class="hhzd_hb6q"/><ellipse fill="url(#f975id1l)" transform="rotate(46.894 11.974 2.692)" class="iy07wrbce"/><path fill="url(#f975id1m)" class="dz47eqb5s"/><path fill="url(#f975id1n)" class="kihletipm"/><path fill="url(#f975id1o)" class="nue0inbrw"/><path fill="url(#f975id1p)" class="h029u5oce"/><path fill="url(#f975id1q)" class="vta1uoi-x"/><path fill="url(#f975id1r)" class="urdyp6bqk"/><path fill="url(#f975id1s)" class="iw5sgrd8w"/><ellipse fill="url(#f975id1t)" transform="rotate(46.894 16.023 2.38)" class="zn4-kxbxl"/><path fill="url(#f975id1u)" class="ircbonbtw"/><path fill="url(#f975id1v)" class="e3xwhhb3b"/><path fill="url(#f975id1w)" class="efw1r88ah"/><path fill="url(#f975id1x)" class="d66mdjtrd"/><path fill="url(#f975id1y)" class="wb5bpab4s"/><path fill="url(#f975id1z)" class="rss8m4tyn"/><path fill="url(#f975id20)" class="inejkeqqd"/><ellipse fill="url(#f975id21)" transform="scale(-1 1) rotate(46.894 -9.033 -14.38)" class="gzzab_b6l"/><path fill="url(#f975id22)" class="g69qbdccm"/><path fill="url(#f975id23)" class="qv9p0cc_s"/><path fill="url(#f975id24)" class="fym4ola-r"/><path fill="url(#f975id25)" class="bkf58e6tk"/><path fill="url(#f975id26)" class="o9_8muxkx"/><path fill="url(#f975id27)" class="mbt8yvvir"/><path fill="url(#f975id28)" class="y2c92-b8u"/><path fill="url(#f975id29)" class="h-69yhbju"/><path fill="url(#f975id2a)" class="j00tezb1v"/><path fill="url(#f975id2b)" class="xucpd1msa"/><path fill="url(#f975id2c)" class="g8nombgea"/><path fill="url(#f975id2d)" class="jzqwpshkk"/><path fill="url(#f975id2e)" class="ilhy8qqeu"/><path fill="url(#f975id2f)" class="h8usfgb8s"/><path fill="url(#f975id2g)" class="ujei-z_bf"/><path fill="url(#f975id2h)" class="gn5u78erv"/><path fill="url(#f975id2i)" class="ze9vjjbqg"/><path fill="url(#f975id2j)" class="yjvovl2wb"/><path fill="url(#f975id2k)" class="xo-qyacxm"/><path fill="url(#f975id2l)" class="n3-xgacnn"/><path fill="url(#f975id2m)" class="auk7h9blb"/><path fill="url(#f975id2n)" class="rtugd8bpy"/><path fill="url(#f975id2o)" class="ko2v0wbvh"/><path fill="url(#f975id2p)" class="cnx048bao"/><path fill="url(#f975id2q)" class="mqucaq90i"/><path fill="url(#f975id2r)" class="rwj933nnd"/><path fill="url(#f975id2s)" class="g-2tuvdba"/><path fill="url(#f975id2t)" class="tuv68lbej"/><ellipse fill="url(#f975id2u)" transform="rotate(46.894 14.2 2.692)" class="r8h8wpb-s"/><path fill="url(#f975id2v)" class="kqg2r0bml"/><path fill="url(#f975id2w)" class="hakx81bzy"/><path fill="url(#f975id2x)" class="ciw3q8r5v"/><path fill="url(#f975id2y)" class="w7yf-ibvl"/><path fill="url(#f975id2z)" class="fkiyofdzi"/><path fill="url(#f975id30)" class="h-53bgbhr"/><path fill="url(#f975id31)" class="wmj3chl3j"/><path fill="url(#f975id32)" class="i1sh50bbh"/><path fill="url(#f975id33)" class="opco-p70b"/><path fill="url(#f975id34)" class="a-h85_8bc"/><path fill="url(#f975id35)" class="l6_3ttz0u"/><path fill="url(#f975id36)" class="x6-kod9qi"/><path fill="url(#f975id37)" class="omxkqibvg"/><path fill="url(#f975id38)" class="vt9qo491m"/><path fill="url(#f975id39)" class="wrwbke1-r"/><path fill="url(#f975id3a)" class="kz5ewicny"/><path fill="url(#f975id3b)" class="m1yyx4b6e"/><path fill="url(#f975id3c)" class="c9vrwsbhf"/><path fill="url(#f975id3d)" class="mh7dsob_w"/><path fill="url(#f975id3e)" class="nm0d54e1y"/><circle fill="url(#f975id3f)" class="wt09nzbjh"/><path fill="url(#f975id3g)" class="baabe40zf"/><path fill="url(#f975id3h)" class="tl-mjkmkv"/><path fill="url(#f975id3i)" class="bxiy47bnf"/><path fill="url(#f975id3j)" class="l0nxg5bwa"/><path fill="url(#f975id3k)" class="x3_jbxb2y"/><path fill="url(#f975id3l)" class="j-x2blwpt"/><path fill="url(#f975id3m)" class="uqmydze1z"/><path fill="url(#f975id3n)" class="um8zr3bpg"/><path fill="url(#f975id3o)" class="gxw5tpz-p"/><path fill="url(#f975id3p)" class="g6-7prbgs"/><path fill="url(#f975id3q)" class="tv139eb_k"/><path fill="url(#f975id3r)" class="ykmr5z71n"/><path fill="url(#f975id3s)" class="hyifb8vyk"/><path fill="url(#f975id3t)" class="qzat3us2f"/><path fill="url(#f975id3u)" class="d2hq1p0ee"/><path fill="url(#f975id3v)" class="enpb9_68e"/><path fill="url(#f975id3w)" class="bepdx4gdr"/><path fill="url(#f975id3x)" class="e0zahybqs"/><path fill="url(#f975id3y)" class="w-leh1bmv"/><path fill="url(#f975id3z)" class="c-wgctb2w"/><path fill="url(#f975id40)" class="jpwroko7g"/><path fill="url(#f975id41)" class="no0ed4ozf"/><path fill="url(#f975id42)" class="vbi3h0biu"/><path fill="url(#f975id43)" class="p-j0vyb7q"/><path fill="url(#f975id44)" class="mmjjjimgi"/><path fill="url(#f975id45)" class="a1sib3b5q"/><path fill="url(#f975id46)" class="ctlqqkb6m"/><path fill="url(#f975id47)" class="g57utsram"/><path fill="url(#f975id48)" class="qkaciqlvj"/><path fill="url(#f975id49)" class="xbdu3-7ha"/><path fill="url(#f975id4a)" class="gt18rvbma"/><path fill="url(#f975id4b)" class="f0iqddcpu"/><path fill="url(#f975id4c)" class="ulea8ebhm"/><path fill="url(#f975id4d)" class="s3bqmqb0n"/><path fill="url(#f975id4e)" class="hw4_s7biu"/><path fill="url(#f975id4f)" class="db7hm60ne"/><path fill="url(#f975id4g)" class="l5797lb4n"/><path fill="url(#f975id4h)" class="n849-9bwe"/><path fill="url(#f975id4i)" class="zg44glb_b"/><path fill="url(#f975id4j)" class="a55m8e_nc"/><path fill="url(#f975id4k)" class="o64f5oboe"/><path fill="url(#f975id4l)" class="lgtzzmb0f"/><path fill="url(#f975id4m)" class="fwwl4e3wr"/><path fill="url(#f975id4n)" class="bf_gkifky"/><path fill="url(#f975id4o)" class="nmgej89kf"/><path fill="url(#f975id4p)" class="g8h3861of"/><path fill="url(#f975id4q)" class="v_7qidbaj"/><path fill="url(#f975id4r)" class="jn5bz-oly"/><path fill="url(#f975id4s)" class="ip3y-pbpf"/><path fill="url(#f975id4t)" class="s7txgibet"/><path fill="url(#f975id4u)" class="qflcowbjd"/><path fill="url(#f975id4v)" class="wjb1uhbwo"/><path fill="url(#f975id4w)" class="utipq7b0b"/><path fill="url(#f975id4x)" class="pyn4-9mft"/><path fill="url(#f975id4y)" class="gcjgmggiz"/><path fill="url(#f975id4z)" class="uvtg8hq0x"/><path fill="url(#f975id50)" class="gwy949bqg"/><path fill="url(#f975id51)" class="pwlfp16tp"/><path fill="url(#f975id52)" class="wfkmq3byh"/><path fill="url(#f975id53)" class="p65pf0bkg"/><path fill="url(#f975id54)" class="jxh8klb7x"/><path fill="url(#f975id55)" class="wzsuubcxb"/><path fill="url(#f975id56)" class="zi_qf35ij"/><path fill="url(#f975id57)" class="n685z9b8y"/><path fill="url(#f975id58)" class="e8un3-1or"/><path fill="url(#f975id59)" class="c5ry__b1p"/><path fill="url(#f975id5a)" class="jpr_kccyq"/><path fill="url(#f975id5b)" class="d3shv8osz"/><path fill="url(#f975id5c)" class="bvdw2yd7r"/><path fill="url(#f975id5d)" class="qk5_l3bpc"/><path fill="url(#f975id5e)" class="hemc1bbwq"/><path fill="url(#f975id5f)" class="ugz5pohnc"/><path fill="url(#f975id5g)" class="tqnhqjb6g"/><path fill="url(#f975id5h)" class="qhpjxobad"/><path fill="url(#f975id5i)" class="vmd3iubtm"/><path fill="url(#f975id5j)" class="vw2czvbjq"/><path fill="url(#f975id5k)" class="aacym8d0c"/><path fill="url(#f975id5l)" class="ropbovbic"/><path fill="url(#f975id5m)" class="prc7rtbwy"/><path fill="url(#f975id5n)" class="juyrjmb_u"/><path fill="url(#f975id5o)" class="qjdsqhtxh"/><path fill="url(#f975id5p)" class="g8ng4ub5p"/><path fill="url(#f975id5q)" class="i17j05cba"/><path fill="url(#f975id5r)" class="f_m-xrb0p"/><path fill="url(#f975id5s)" class="v9c4cgbhh"/><path fill="url(#f975id5t)" class="s-hrk22ri"/><path fill="url(#f975id5u)" class="tun6z81hv"/><path fill="url(#f975id5v)" class="y2l25ovzu"/><path fill="url(#f975id5w)" class="nfbwzfh6y"/><path fill="url(#f975id5x)" class="x12agwr7v"/><path fill="url(#f975id5y)" class="cybjr2min"/><path fill="url(#f975id5z)" class="namp4mb9x"/><path fill="url(#f975id60)" class="a4wwz57ns"/><path fill="url(#f975id61)" class="mhtidt27u"/><path fill="url(#f975id62)" class="wu9llru8x"/><path fill="url(#f975id63)" class="xvq3ckway"/><path fill="url(#f975id64)" class="wcgql7bkv"/><path fill="url(#f975id65)" class="bc-m_schn"/><path fill="url(#f975id66)" class="w21w9zi9u"/><path fill="url(#f975id67)" class="jkdbopbiq"/><path fill="url(#f975id68)" class="vvq9babrb"/><path fill="url(#f975id69)" class="j_e7ycxwk"/><path fill="url(#f975id6a)" class="i057kv2sc"/><path fill="url(#f975id6b)" class="qtrlt_g5u"/><path fill="url(#f975id6c)" class="sc2dwxmvr"/><path fill="url(#f975id6d)" class="uxguh0bbm"/><path fill="url(#f975id6e)" class="sh2q0kb3d"/><path fill="url(#f975id6f)" class="xstjivg-n"/><path fill="url(#f975id6g)" class="t7j_vi8an"/><path fill="url(#f975id6h)" class="jynvt1blk"/><path fill="url(#f975id6i)" class="hoxx4qb0c"/><path fill="url(#f975id6j)" class="d_3p_5bmw"/><path fill="url(#f975id6k)" class="nr6tk6bwq"/><path fill="url(#f975id6l)" class="n3xs1gb_f"/><path fill="url(#f975id6m)" class="v6g6ftb9d"/><path fill="url(#f975id6n)" class="gg3m-ccqn"/><path fill="url(#f975id6o)" class="dhfc9fbya"/><path fill="url(#f975id6p)" class="i-hjf1bhe"/><path fill="url(#f975id6q)" class="c272z_bvq"/><path fill="url(#f975id6r)" class="yo_n73dwc"/><path fill="url(#f975id6s)" class="ovb-inlsf"/><path fill="url(#f975id6t)" class="pj4sl46-r"/><path fill="url(#f975id6u)" class="gh1_qnu_h"/><ellipse fill="url(#f975id6v)" transform="rotate(40.114 12.211 3.642)" class="cf-nu_c0o"/><path fill="url(#f975id6w)" class="zcl392bgg"/><path fill="url(#f975id6x)" class="oxdjsnp6a"/><path fill="url(#f975id6y)" class="u6_rgsbxk"/><path fill="url(#f975id6z)" class="s96438ujh"/><path fill="url(#f975id70)" class="oxy_xhbca"/><path fill="url(#f975id71)" class="d0xmf00ty"/><path fill="url(#f975id72)" class="knh2dl9nl"/><path fill="url(#f975id73)" clip-rule="evenodd" class="l9hthccmu"/><path fill="url(#f975id74)" class="goknvdham"/><path fill="url(#f975id75)" class="qlwlh0fhk"/><path fill="url(#f975id76)" class="mr3x8bcoq"/><path fill="url(#f975id77)" class="hxvo6nkrx"/><path fill="url(#f975id78)" class="v5ghnvq8t"/><path fill="url(#f975id79)" class="vk714r9cb"/><path fill="url(#f975id7a)" class="h05ur_b5g"/><path fill="url(#f975id7b)" class="so6ggsb_z"/><path fill="url(#f975id7c)" class="h93axsbui"/><path fill="url(#f975id7d)" class="v413-6lxs"/><path fill="url(#f975id7e)" class="xkmwj-65w"/><path fill="url(#f975id7f)" class="ne_ihi2nh"/><path fill="url(#f975id7g)" class="h06mln5vl"/><path fill="url(#f975id7h)" class="q-7-kre2s"/><path fill="url(#f975id7i)" class="z613zdw_j"/><path fill="url(#f975id7j)" class="p9php6kcu"/><path fill="url(#f975id7k)" class="pldenwbvr"/><path fill="url(#f975id7l)" class="fwzlmgbnn"/><path fill="url(#f975id7m)" class="u832i7sin"/><path fill="url(#f975id7n)" class="mawzxkvil"/><path fill="url(#f975id7o)" class="uxdgxwwgw"/><path fill="url(#f975id7p)" class="nwdkllbxq"/><path fill="url(#f975id7q)" class="dwceu1nxh"/><path fill="url(#f975id7r)" class="wbuy9zv7y"/><path fill="url(#f975id7s)" class="a30le0b1i"/><path fill="url(#f975id7t)" class="brekr5pfn"/><path fill="url(#f975id7u)" class="ii77fulqy"/><path fill="url(#f975id7v)" class="d65n58bni"/><path fill="url(#f975id7w)" class="na4-79jps"/><path fill="url(#f975id7x)" class="fekfogg3l"/><path fill="url(#f975id7y)" class="q8ct3fs0x"/><path fill="url(#f975id7z)" class="wzgxhab_f"/><path fill="url(#f975id80)" class="uwnpv4bpr"/><path fill="url(#f975id81)" class="xg239kbdk"/><path fill="url(#f975id82)" class="x_mqa2bqv"/><path fill="url(#f975id83)" class="m31b3_vwm"/><path fill="url(#f975id84)" class="gxngfta-o"/><path fill="url(#f975id85)" class="knhvp8bxb"/><path fill="url(#f975id86)" class="gzv9xexwk"/><path fill="url(#f975id87)" class="chf6oxp2l"/><path fill="url(#f975id88)" class="n517djb-j"/><path fill="url(#f975id89)" class="te3h9abkf"/><path fill="url(#f975id8a)" class="ivwpoe7fc"/><path fill="url(#f975id8b)" class="u_in95b_f"/><path fill="url(#f975id8c)" class="ehixovtvr"/><path fill="url(#f975id8d)" class="nkfumcb8m"/><path fill="url(#f975id8e)" class="gi8fu2bxl"/><path fill="url(#f975id8f)" class="qqnyqzw3g"/><path fill="url(#f975id8g)" class="kbdgkn7fg"/><path fill="url(#f975id8h)" class="byxip0b8c"/><path fill="url(#f975id8i)" class="jd9pj3b3q"/><path fill="url(#f975id8j)" class="cm6w2xb7s"/><path fill="url(#f975id8k)" class="j1dapkb_s"/><path fill="url(#f975id8l)" class="sssp2rbtv"/><path fill="url(#f975id8m)" class="mpfdrhb6t"/><path fill="url(#f975id8n)" class="dekw5j1eb"/><path fill="url(#f975id8o)" class="gke_yzgbl"/><path fill="url(#f975id8p)" class="f9nl86h_t"/><path fill="url(#f975id8q)" class="zio7rbbdg"/><path fill="url(#f975id8r)" class="tf8twm7te"/><path fill="url(#f975id8s)" class="pabs_sbwe"/><path fill="url(#f975id8t)" class="p3z5ozbbj"/><path fill="url(#f975id8u)" class="g4b5g7bln"/><path fill="url(#f975id8v)" class="hvzqp6bsv"/><path fill="url(#f975id8w)" class="ecoyd1dhh"/><path fill="url(#f975id8x)" class="hijuj2b3f"/><path fill="url(#f975id8y)" class="srhlmdbqx"/><path fill="url(#f975id8z)" class="cfq28cjgl"/><path fill="url(#f975id90)" class="jqc0yrb_o"/><path fill="url(#f975id91)" class="vakul_mok"/><path fill="url(#f975id92)" class="vn9r6cbiq"/><path fill="url(#f975id93)" class="oyb4hqvkg"/><path fill="url(#f975id94)" class="xn7zw8b3s"/><path fill="url(#f975id95)" class="j34jzlb1p"/><path fill="url(#f975id96)" class="opjfhbcxc"/><path fill="url(#f975id97)" class="g0djkcbml"/><path fill="url(#f975id98)" class="och9wxgnu"/><path fill="url(#f975id99)" class="vz8zmbbms"/><path fill="url(#f975id9a)" class="wbsf4nbws"/><path fill="url(#f975id9b)" class="dx9ojm79q"/><path fill="url(#f975id9c)" class="lfkmfybci"/><path fill="url(#f975id9d)" class="dqj1tqbue"/><ellipse fill="url(#f975id9e)" transform="rotate(21.646 13.181 4.666)" class="iokohibue"/><path fill="url(#f975id9f)" class="r-90x2rqr"/><path fill="url(#f975id9g)" class="goeq79b8a"/><path fill="url(#f975id9h)" class="fyzrg1mbc"/><path fill="url(#f975id9i)" class="rm4vinbaq"/><path fill="url(#f975id9j)" class="ivpy-diyv"/><path fill="url(#f975id9k)" class="mg4ogkbne"/><ellipse fill="url(#f975id9l)" transform="rotate(39.338 16 4.265)" class="hbgmt9qwx"/><path fill="url(#f975id9m)" class="nkqo8zsap"/><path fill="url(#f975id9n)" class="xlph5rbrw"/><path fill="url(#f975id9o)" class="w27ucebkj"/><path fill="url(#f975id9p)" class="vlrfhp1-h"/><path fill="url(#f975id9q)" class="p0milabxh"/><path fill="url(#f975id9r)" class="n4lj9hd-i"/><path fill="url(#f975id9s)" class="hlzj_l28s"/><circle fill="url(#f975id9t)" class="dni3hdb2l"/><path fill="url(#f975id9u)" class="e77z8gb7a"/><path fill="url(#f975id9v)" class="vfbr2pb4n"/><path fill="url(#f975id9w)" class="q5-d1o17a"/><path fill="url(#f975id9x)" class="tdkvgvbrv"/><path fill="url(#f975id9y)" class="ay5kyxbjb"/><path fill="url(#f975id9z)" class="g7fsp6bcq"/><path fill="url(#f975ida0)" class="ca8tm4bmu"/><path fill="url(#f975ida1)" class="ge-pa6b3z"/><path fill="url(#f975ida2)" class="a228lp2it"/><path fill="url(#f975ida3)" class="ark48u8aj"/><path fill="url(#f975ida4)" class="v1j_e9tbd"/><path fill="url(#f975ida5)" class="d-12igb3j"/><path fill="url(#f975ida6)" class="knmcy5b0k"/><path fill="url(#f975ida7)" class="c95kz21hb"/><circle fill="url(#f975ida8)" class="r9argyb8r"/><path fill="url(#f975ida9)" class="nkhktmb-q"/><path fill="url(#f975idaa)" class="j3j_8besh"/><path fill="url(#f975idab)" class="uf-ketbzf"/><path fill="url(#f975idac)" class="q-sol0bxm"/><path fill="url(#f975idad)" class="s7b6inb1j"/><path fill="url(#f975idae)" class="gyxy_5-dg"/><path fill="url(#f975idaf)" class="si1-qzoqv"/><path fill="url(#f975idag)" class="nxhdkhcqq"/><path fill="url(#f975idah)" class="mp71g_bih"/><path fill="url(#f975idai)" class="uo4w231ko"/><path fill="url(#f975idaj)" class="wovkv07mg"/><path fill="url(#f975idak)" class="h310odbes"/><path fill="url(#f975idal)" class="lubncxb5i"/><path fill="url(#f975idam)" class="n83aecb-e"/><path fill="url(#f975idan)" class="eos0x8blt"/><path fill="url(#f975idao)" class="pgkj3lg9r"/><path fill="url(#f975idap)" class="xrj-5j3dw"/><path fill="url(#f975idaq)" class="eb25llg0t"/><path fill="url(#f975idar)" class="e9luk_bdd"/><path fill="url(#f975idas)" class="m8g_7_muo"/><ellipse fill="url(#f975idat)" transform="rotate(32.19 26.437 7.214)" class="v1-92dbdc"/><path fill="url(#f975idau)" class="vj_ad1bzt"/><path fill="url(#f975idav)" class="kla98c7et"/><path fill="url(#f975idaw)" class="vlxo6wwfe"/><path fill="url(#f975idax)" class="wymcc9bpj"/><path fill="url(#f975iday)" class="sd5vsfuhv"/><path fill="url(#f975idaz)" class="u7as4g6sb"/><path fill="url(#f975idb0)" class="q6qh4lb2f"/><path fill="url(#f975idb1)" class="zrm1_cb8k"/><path fill="url(#f975idb2)" class="p28rgwnvv"/><path fill="url(#f975idb3)" class="pjop0htdk"/><path fill="url(#f975idb4)" class="uqwrzcbdl"/><path fill="url(#f975idb5)" class="g1-f58biz"/><path fill="url(#f975idb6)" class="yqq3e723a"/><circle fill="url(#f975idb7)" class="cow9uybav"/><path fill="url(#f975idb8)" class="bp0_2abkw"/><path fill="url(#f975idb9)" class="hzqzbj9rf"/><path fill="url(#f975idba)" class="h-53emb2c"/><path fill="url(#f975idbb)" class="h_1rewmtj"/><path fill="url(#f975idbc)" class="xuafvdbgc"/><defs><radialGradient id="f975id0" cx="0" cy="0" r="1" gradientTransform="matrix(3.29962 0 0 5.77437 3.917 18.448)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="f975id1" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 40.395 -30.416) scale(1.92285 2.19469)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="f975id2" cx="0" cy="0" r="1" gradientTransform="matrix(1.5442 -2.8402 1.66239 .90382 24.866 19.992)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="f975id3" cx="0" cy="0" r="1" gradientTransform="matrix(.48754 .48257 -.62212 .62851 24.943 18.449)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="f975id4" cx="0" cy="0" r="1" gradientTransform="scale(27.5404 20.0629) rotate(90 .003 .61)" gradientUnits="userSpaceOnUse"><stop offset=".635" class="er8tzqbbl"/><stop offset=".928" class="uwv4pp46h"/></radialGradient><radialGradient id="f975id5" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.45767 3.02482 0 20.395 16.058)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="f975id6" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.61521 3.25225 0 11.824 15.995)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="f975id7" cx="0" cy="0" r="1" gradientTransform="rotate(-90 20.253 4.129) scale(17.25)" gradientUnits="userSpaceOnUse"><stop offset=".848" class="lrlki_zex"/><stop offset="1" class="fny1fvqvu"/></radialGradient><radialGradient id="f975id8" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.52515 -2.42592 0 20.08 17.166)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="f975id9" cx="0" cy="0" r="1" gradientTransform="matrix(-.43597 -.5618 .77347 -.60022 19.651 17.324)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="f975ida" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.52523 -2.42604 0 11.877 17.166)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="f975idb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01454 -.9288 1.11645 -.01748 11.339 17.578)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="f975idc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39952 .58558 -.86318 -.58891 19.024 7.616)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idd" cx="0" cy="0" r="1" gradientTransform="matrix(-.43804 .5724 -.87468 -.66937 19.188 7.29)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ide" cx="0" cy="0" r="1" gradientTransform="rotate(130.589 8.068 7.816) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idf" cx="0" cy="0" r="1" gradientTransform="matrix(-.44346 .5015 -.78797 -.69677 19.199 6.069)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idg" cx="0" cy="0" r="1" gradientTransform="rotate(127.607 8.242 7.366) scale(.68217 1.0442)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idh" cx="0" cy="0" r="1" gradientTransform="matrix(-.31164 .61797 -.78668 -.39673 19.188 4.623)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idi" cx="0" cy="0" r="1" gradientTransform="matrix(-.32744 .54542 -.76209 -.4575 19.753 4.267)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idj" cx="0" cy="0" r="1" gradientTransform="matrix(.32443 .6303 -.92909 .47822 14.46 5.657)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idk" cx="0" cy="0" r="1" gradientTransform="matrix(.36428 .62194 -.9504 .55665 14.338 5.313)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idl" cx="0" cy="0" r="1" gradientTransform="rotate(56.479 2.705 15.743) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idm" cx="0" cy="0" r="1" gradientTransform="matrix(.37837 .55226 -.86773 .5945 14.477 4.1)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idn" cx="0" cy="0" r="1" gradientTransform="matrix(.34663 .58754 -.89935 .53058 14.658 3.38)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ido" cx="0" cy="0" r="1" gradientTransform="matrix(.23324 .65162 -.82951 .29691 14.665 2.666)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idp" cx="0" cy="0" r="1" gradientTransform="matrix(.25784 .58157 -.8126 .36027 14.149 2.244)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idq" cx="0" cy="0" r="1" gradientTransform="matrix(-.26933 .48838 -.65389 -.3606 18.982 5.681)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idr" cx="0" cy="0" r="1" gradientTransform="matrix(-.38841 .74917 -.96927 -.50253 19.495 5.442)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ids" cx="0" cy="0" r="1" gradientTransform="matrix(-.36602 .73137 -.9268 -.46383 19.8 5.084)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idt" cx="0" cy="0" r="1" gradientTransform="matrix(-.36009 .70192 -.9026 -.46304 20.147 4.712)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idu" cx="0" cy="0" r="1" gradientTransform="matrix(-.36719 .60937 -.85292 -.51395 20.463 4.261)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idv" cx="0" cy="0" r="1" gradientTransform="matrix(-.38943 .522 -.79215 -.59096 20.52 3.621)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idw" cx="0" cy="0" r="1" gradientTransform="matrix(-.33144 .56044 -.7775 -.45981 20.413 2.819)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idx" cx="0" cy="0" r="1" gradientTransform="matrix(-.13851 .2262 -.31896 -.1953 20.562 2.597)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idy" cx="0" cy="0" r="1" gradientTransform="matrix(-.40708 .08847 -.13531 -.62258 9.058 6.853)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idz" cx="0" cy="0" r="1" gradientTransform="matrix(-.60483 .19319 -.30507 -.9551 9.363 6.568)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id10" cx="0" cy="0" r="1" gradientTransform="matrix(-.62956 .2341 -.3705 -.99642 9.475 6.087)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id11" cx="0" cy="0" r="1" gradientTransform="matrix(-.62015 .25324 -.39943 -.97815 9.533 5.547)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id12" cx="0" cy="0" r="1" gradientTransform="matrix(-.5992 .22422 -.35484 -.94825 9.431 4.97)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id13" cx="0" cy="0" r="1" gradientTransform="matrix(-.5426 .17864 -.2824 -.85778 9.234 4.373)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id14" cx="0" cy="0" r="1" gradientTransform="rotate(154.731 4.21 2.872) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id15" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 3.843 3.9) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id16" cx="0" cy="0" r="1" gradientTransform="matrix(-.40708 .08847 -.13531 -.62258 10.389 6.244)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id17" cx="0" cy="0" r="1" gradientTransform="matrix(-.60483 .19319 -.30507 -.9551 10.692 5.96)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id18" cx="0" cy="0" r="1" gradientTransform="matrix(-.62956 .2341 -.3705 -.99642 10.805 5.479)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id19" cx="0" cy="0" r="1" gradientTransform="matrix(-.62015 .25324 -.39943 -.97815 10.861 4.938)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1a" cx="0" cy="0" r="1" gradientTransform="rotate(159.484 4.986 3.154) scale(.63977 1.01247)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.5426 .17864 -.2824 -.85778 10.563 3.764)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1c" cx="0" cy="0" r="1" gradientTransform="rotate(154.731 4.943 2.717) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1d" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 4.658 3.925) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1e" cx="0" cy="0" r="1" gradientTransform="matrix(-.40708 .08847 -.13531 -.62258 11.838 6.274)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1f" cx="0" cy="0" r="1" gradientTransform="matrix(-.60483 .19319 -.30507 -.9551 12.142 5.99)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1g" cx="0" cy="0" r="1" gradientTransform="matrix(-.62956 .2341 -.3705 -.99642 12.255 5.509)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1h" cx="0" cy="0" r="1" gradientTransform="matrix(-.62015 .25324 -.39943 -.97815 12.311 4.967)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1i" cx="0" cy="0" r="1" gradientTransform="rotate(159.484 5.708 3.3) scale(.63977 1.01247)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1j" cx="0" cy="0" r="1" gradientTransform="matrix(-.5426 .17864 -.2824 -.85778 12.013 3.794)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1k" cx="0" cy="0" r="1" gradientTransform="rotate(154.731 5.665 2.894) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1l" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 5.376 4.298) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1m" cx="0" cy="0" r="1" gradientTransform="matrix(-.40708 .08847 -.13531 -.62258 15.887 5.964)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1n" cx="0" cy="0" r="1" gradientTransform="matrix(-.60483 .19319 -.30507 -.9551 16.192 5.678)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1o" cx="0" cy="0" r="1" gradientTransform="matrix(-.62956 .2341 -.3705 -.99642 16.304 5.197)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1p" cx="0" cy="0" r="1" gradientTransform="matrix(-.62015 .25324 -.39943 -.97815 16.36 4.656)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1q" cx="0" cy="0" r="1" gradientTransform="rotate(159.484 7.76 3.511) scale(.63977 1.01247)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1r" cx="0" cy="0" r="1" gradientTransform="matrix(-.5426 .17864 -.2824 -.85778 16.062 3.483)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1s" cx="0" cy="0" r="1" gradientTransform="rotate(154.731 7.724 3.192) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1t" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 7.477 5.142) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1u" cx="0" cy="0" r="1" gradientTransform="matrix(.40708 .0885 -.13533 .62256 13.495 5.624)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1v" cx="0" cy="0" r="1" gradientTransform="matrix(.60483 .19319 -.30506 .9551 13.191 5.34)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1w" cx="0" cy="0" r="1" gradientTransform="matrix(.62956 .23409 -.3705 .99642 13.079 4.858)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1x" cx="0" cy="0" r="1" gradientTransform="matrix(.62014 .25326 -.39945 .97814 13.022 4.317)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1y" cx="0" cy="0" r="1" gradientTransform="matrix(.5992 .22422 -.35484 .94825 13.123 3.74)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id1z" cx="0" cy="0" r="1" gradientTransform="matrix(.5426 .17864 -.2824 .85778 13.32 3.144)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id20" cx="0" cy="0" r="1" gradientTransform="rotate(25.269 1.206 30.91) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id21" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 .15 .202) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id22" cx="0" cy="0" r="1" gradientTransform="matrix(-.40708 .08847 -.13531 -.62258 12.933 5.803)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id23" cx="0" cy="0" r="1" gradientTransform="matrix(-.60483 .19319 -.30507 -.9551 13.237 5.519)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id24" cx="0" cy="0" r="1" gradientTransform="matrix(-.62956 .2341 -.3705 -.99642 13.35 5.037)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id25" cx="0" cy="0" r="1" gradientTransform="matrix(-.62015 .25324 -.39943 -.97815 13.407 4.496)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id26" cx="0" cy="0" r="1" gradientTransform="rotate(158.745 6.289 3.203) scale(.64842 1.02511)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id27" cx="0" cy="0" r="1" gradientTransform="matrix(-.5426 .17864 -.2824 -.85778 13.108 3.323)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id28" cx="0" cy="0" r="1" gradientTransform="rotate(154.731 6.265 2.781) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id29" cx="0" cy="0" r="1" gradientTransform="matrix(.413 .05446 -.0833 .63163 18.056 5.79)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2a" cx="0" cy="0" r="1" gradientTransform="matrix(.61876 .1424 -.22486 .97709 17.727 5.53)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2b" cx="0" cy="0" r="1" gradientTransform="matrix(.6468 .18113 -.28668 1.02369 17.577 5.06)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2c" cx="0" cy="0" r="1" gradientTransform="matrix(.639 .201 -.31705 1.00787 17.476 4.527)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2d" cx="0" cy="0" r="1" gradientTransform="matrix(.6217 .1842 -.2912 .98288 17.522 3.932)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2e" cx="0" cy="0" r="1" gradientTransform="matrix(.55554 .13307 -.21037 .87823 17.676 3.333)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2f" cx="0" cy="0" r="1" gradientTransform="rotate(20.517 1.524 49.962) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2g" cx="0" cy="0" r="1" gradientTransform="matrix(.413 .05446 -.0833 .63163 22.08 6.468)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2h" cx="0" cy="0" r="1" gradientTransform="matrix(.61876 .14241 -.22489 .97708 21.753 6.21)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2i" cx="0" cy="0" r="1" gradientTransform="matrix(.6468 .18113 -.28668 1.02369 21.602 5.739)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2j" cx="0" cy="0" r="1" gradientTransform="matrix(.639 .201 -.31705 1.00787 21.5 5.205)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2k" cx="0" cy="0" r="1" gradientTransform="matrix(.6217 .1842 -.2912 .98288 21.546 4.61)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2l" cx="0" cy="0" r="1" gradientTransform="matrix(.55554 .13307 -.21037 .87823 21.7 4.01)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2m" cx="0" cy="0" r="1" gradientTransform="rotate(20.517 1.663 61.419) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2n" cx="0" cy="0" r="1" gradientTransform="matrix(-.40708 .08847 -.13531 -.62258 14.064 6.275)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2o" cx="0" cy="0" r="1" gradientTransform="matrix(-.60483 .19319 -.30507 -.9551 14.368 5.99)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2p" cx="0" cy="0" r="1" gradientTransform="matrix(-.62956 .2341 -.3705 -.99642 14.48 5.509)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2q" cx="0" cy="0" r="1" gradientTransform="matrix(-.62015 .25324 -.39943 -.97815 14.535 4.967)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2r" cx="0" cy="0" r="1" gradientTransform="rotate(159.484 6.82 3.502) scale(.63977 1.01247)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2s" cx="0" cy="0" r="1" gradientTransform="matrix(-.5426 .17864 -.2824 -.85778 14.239 3.794)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2t" cx="0" cy="0" r="1" gradientTransform="rotate(154.731 6.778 3.144) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2u" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 6.488 4.848) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2v" cx="0" cy="0" r="1" gradientTransform="matrix(-.64812 .04016 -.06357 -1.02583 7.913 7.41)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2w" cx="0" cy="0" r="1" gradientTransform="matrix(-.58947 0 0 -.92891 8 6.698)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2x" cx="0" cy="0" r="1" gradientTransform="matrix(-.59441 .087 -.13532 -.9245 8.191 6.047)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2y" cx="0" cy="0" r="1" gradientTransform="matrix(-.6851 .1951 -.27787 -.97574 8.256 5.499)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id2z" cx="0" cy="0" r="1" gradientTransform="matrix(-.63847 .10243 -.15841 -.98746 8.013 4.947)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id30" cx="0" cy="0" r="1" gradientTransform="rotate(166.845 3.863 2.67) scale(.60377 .89583)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id31" cx="0" cy="0" r="1" gradientTransform="matrix(-.27925 .04309 -.0668 -.433 8.409 4.173)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id32" cx="0" cy="0" r="1" gradientTransform="rotate(168.435 12.31 7.438) scale(.54682 .86518)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id33" cx="0" cy="0" r="1" gradientTransform="rotate(166.738 12.33 7.355) scale(.71421 1.12573)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id34" cx="0" cy="0" r="1" gradientTransform="rotate(167.816 12.466 6.928) scale(.71015 1.12249)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id35" cx="0" cy="0" r="1" gradientTransform="matrix(-.60384 .11284 -.17864 -.95596 26.376 10.547)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id36" cx="0" cy="0" r="1" gradientTransform="rotate(174.004 13.047 5.727) scale(.54218 .84738)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id37" cx="0" cy="0" r="1" gradientTransform="matrix(-.5622 .21215 -.3152 -.8353 26.611 9.447)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id38" cx="0" cy="0" r="1" gradientTransform="rotate(151.381 11.966 7.89) scale(.49173 .6291)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id39" cx="0" cy="0" r="1" gradientTransform="matrix(-.30114 .7201 -.81154 -.33937 25.031 11.136)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3a" cx="0" cy="0" r="1" gradientTransform="rotate(117.687 9.46 13.21) scale(.78603 1.02398)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.41616 .60822 -.89749 -.61409 25.875 10.56)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.42674 .56487 -.8602 -.64986 25.986 9.868)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.37541 .6428 -.88632 -.51764 25.937 9.118)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3e" cx="0" cy="0" r="1" gradientTransform="matrix(-.3151 .61683 -.7912 -.40419 26.227 8.351)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3f" cx="0" cy="0" r="1" gradientTransform="matrix(-.15941 .26034 -.3671 -.22479 26.507 8.33)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3g" cx="0" cy="0" r="1" gradientTransform="matrix(.2605 .65929 -.97183 .384 20.762 6.941)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3h" cx="0" cy="0" r="1" gradientTransform="rotate(65.318 5.2 19.42) scale(.72077 1.10142)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3i" cx="0" cy="0" r="1" gradientTransform="matrix(.32415 .61364 -.95998 .5071 20.725 6.07)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3j" cx="0" cy="0" r="1" gradientTransform="matrix(.3219 .58698 -.92227 .50578 20.933 5.392)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3k" cx="0" cy="0" r="1" gradientTransform="matrix(.28682 .61894 -.94742 .43904 21.184 4.695)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3l" cx="0" cy="0" r="1" gradientTransform="matrix(.16765 .6715 -.85481 .21342 21.263 3.984)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3m" cx="0" cy="0" r="1" gradientTransform="matrix(.19905 .60422 -.84424 .27813 20.79 3.514)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3n" cx="0" cy="0" r="1" gradientTransform="matrix(.2605 .65929 -.97183 .384 23.833 8.405)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3o" cx="0" cy="0" r="1" gradientTransform="matrix(.30098 .65492 -1.0008 .45993 23.745 8.05)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3p" cx="0" cy="0" r="1" gradientTransform="matrix(.32415 .61364 -.95998 .5071 23.796 7.535)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3q" cx="0" cy="0" r="1" gradientTransform="matrix(.3219 .58698 -.92227 .50578 24.004 6.856)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3r" cx="0" cy="0" r="1" gradientTransform="matrix(.28682 .61894 -.94742 .43904 24.255 6.159)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3s" cx="0" cy="0" r="1" gradientTransform="matrix(.16765 .6715 -.85481 .21342 24.333 5.448)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3t" cx="0" cy="0" r="1" gradientTransform="matrix(.19905 .60422 -.84424 .27813 23.86 4.977)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3u" cx="0" cy="0" r="1" gradientTransform="matrix(-.41353 .57578 -.84873 -.60956 15.11 6.201)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3v" cx="0" cy="0" r="1" gradientTransform="matrix(-.45172 .56166 -.85828 -.69027 15.28 5.88)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3w" cx="0" cy="0" r="1" gradientTransform="rotate(131.972 6.484 6.104) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3x" cx="0" cy="0" r="1" gradientTransform="matrix(-.45543 .49066 -.77094 -.71557 15.321 4.657)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3y" cx="0" cy="0" r="1" gradientTransform="matrix(-.42921 .53022 -.81161 -.657 15.248 3.92)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id3z" cx="0" cy="0" r="1" gradientTransform="matrix(-.32647 .61027 -.77686 -.4156 15.345 3.212)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id40" cx="0" cy="0" r="1" gradientTransform="rotate(122.361 7.17 5.815) scale(.63616 .88887)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id41" cx="0" cy="0" r="1" gradientTransform="matrix(-.41353 .57578 -.84873 -.60956 18.826 6.172)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id42" cx="0" cy="0" r="1" gradientTransform="matrix(-.45172 .56166 -.85828 -.69027 18.997 5.851)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id43" cx="0" cy="0" r="1" gradientTransform="rotate(131.972 8.348 6.918) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id44" cx="0" cy="0" r="1" gradientTransform="matrix(-.45543 .49066 -.77094 -.71557 19.038 4.63)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id45" cx="0" cy="0" r="1" gradientTransform="matrix(-.42921 .53022 -.81161 -.657 18.965 3.892)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id46" cx="0" cy="0" r="1" gradientTransform="matrix(-.32647 .61027 -.77686 -.4156 19.062 3.185)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id47" cx="0" cy="0" r="1" gradientTransform="rotate(122.361 9.035 6.823) scale(.63616 .88887)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id48" cx="0" cy="0" r="1" gradientTransform="matrix(.32443 .6303 -.92909 .47822 16.817 5.86)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id49" cx="0" cy="0" r="1" gradientTransform="matrix(.36428 .62194 -.9504 .55665 16.695 5.515)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4a" cx="0" cy="0" r="1" gradientTransform="rotate(56.479 3.695 18.039) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4b" cx="0" cy="0" r="1" gradientTransform="matrix(.37837 .55226 -.86773 .5945 16.834 4.301)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4c" cx="0" cy="0" r="1" gradientTransform="matrix(.34663 .58754 -.89935 .53058 17.014 3.582)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4d" cx="0" cy="0" r="1" gradientTransform="matrix(.23324 .65162 -.82951 .29691 17.022 2.868)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4e" cx="0" cy="0" r="1" gradientTransform="matrix(.25784 .58157 -.8126 .36027 16.506 2.447)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4f" cx="0" cy="0" r="1" gradientTransform="matrix(.15953 .6907 -1.01814 .23515 22.216 7.284)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4g" cx="0" cy="0" r="1" gradientTransform="matrix(.2002 .69241 -1.05808 .30593 22.182 6.92)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4h" cx="0" cy="0" r="1" gradientTransform="matrix(.22926 .65504 -1.02474 .35866 22.308 6.417)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4i" cx="0" cy="0" r="1" gradientTransform="matrix(.231 .62833 -.98725 .36295 22.615 5.778)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4j" cx="0" cy="0" r="1" gradientTransform="matrix(.19155 .65473 -1.00219 .29321 22.967 5.125)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4k" cx="0" cy="0" r="1" gradientTransform="matrix(.06589 .68896 -.87705 .08388 23.15 4.435)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4l" cx="0" cy="0" r="1" gradientTransform="matrix(.10696 .6271 -.87622 .14944 22.753 3.9)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4m" cx="0" cy="0" r="1" gradientTransform="matrix(-.37427 .60204 -.88743 -.5517 25.308 9.619)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4n" cx="0" cy="0" r="1" gradientTransform="matrix(-.4133 .5905 -.90235 -.63158 25.457 9.286)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4o" cx="0" cy="0" r="1" gradientTransform="rotate(128.153 10.62 10.582) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4p" cx="0" cy="0" r="1" gradientTransform="matrix(-.42173 .5199 -.81689 -.66264 25.416 8.064)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4q" cx="0" cy="0" r="1" gradientTransform="matrix(-.39294 .55763 -.85357 -.60148 25.295 7.333)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4r" cx="0" cy="0" r="1" gradientTransform="matrix(-.2851 .63066 -.80283 -.36293 25.345 6.62)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4s" cx="0" cy="0" r="1" gradientTransform="matrix(-.30396 .55885 -.78085 -.4247 25.894 6.242)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4t" cx="0" cy="0" r="1" gradientTransform="matrix(-.37427 .60204 -.88743 -.5517 24.916 8.9)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4u" cx="0" cy="0" r="1" gradientTransform="matrix(-.4133 .5905 -.90235 -.63158 25.066 8.567)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4v" cx="0" cy="0" r="1" gradientTransform="matrix(-.42873 .54574 -.85375 -.6707 25.11 8.05)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4w" cx="0" cy="0" r="1" gradientTransform="rotate(129.048 10.763 9.635) scale(.66945 1.05185)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4x" cx="0" cy="0" r="1" gradientTransform="matrix(-.39294 .55763 -.85357 -.60148 24.903 6.614)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4y" cx="0" cy="0" r="1" gradientTransform="matrix(-.2851 .63066 -.80283 -.36293 24.953 5.901)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id4z" cx="0" cy="0" r="1" gradientTransform="matrix(-.30396 .55885 -.78085 -.4247 25.502 5.523)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id50" cx="0" cy="0" r="1" gradientTransform="matrix(.20135 .6797 -1.0019 .2968 25.938 10.152)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id51" cx="0" cy="0" r="1" gradientTransform="matrix(.24206 .67891 -1.03745 .3699 25.882 9.79)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id52" cx="0" cy="0" r="1" gradientTransform="matrix(.26879 .63984 -1.00096 .42049 25.977 9.28)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id53" cx="0" cy="0" r="1" gradientTransform="matrix(.2689 .61307 -.96327 .42249 26.245 8.624)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id54" cx="0" cy="0" r="1" gradientTransform="matrix(.23113 .64182 -.98244 .35379 26.556 7.95)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id55" cx="0" cy="0" r="1" gradientTransform="matrix(.10779 .68366 -.8703 .13721 26.697 7.25)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id56" cx="0" cy="0" r="1" gradientTransform="matrix(.145 .61941 -.86547 .2026 26.268 6.74)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id57" cx="0" cy="0" r="1" gradientTransform="matrix(.62866 .52185 -.80326 .96766 11.127 6.509)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id58" cx="0" cy="0" r="1" gradientTransform="matrix(.56897 .4723 -.72698 .8758 10.982 6.026)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id59" cx="0" cy="0" r="1" gradientTransform="matrix(.56251 .31869 -.50097 .88425 10.838 5.44)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5a" cx="0" cy="0" r="1" gradientTransform="matrix(.5842 .35335 -.55833 .92308 10.953 4.7)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5b" cx="0" cy="0" r="1" gradientTransform="matrix(.53986 .51894 -.76245 .7932 11.094 3.814)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5c" cx="0" cy="0" r="1" gradientTransform="matrix(.39246 .53328 -.63302 .46586 10.961 3.197)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.57137 .48177 -.74156 -.87947 9.764 6.508)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5e" cx="0" cy="0" r="1" gradientTransform="matrix(-.51712 .43601 -.67114 -.79598 9.893 6.065)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5f" cx="0" cy="0" r="1" gradientTransform="matrix(-.5123 .29547 -.46447 -.8053 10.021 5.528)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5g" cx="0" cy="0" r="1" gradientTransform="rotate(148.391 4.269 3.828) scale(.62453 .98682)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5h" cx="0" cy="0" r="1" gradientTransform="matrix(-.49016 .47848 -.703 -.72017 9.775 4.042)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5i" cx="0" cy="0" r="1" gradientTransform="matrix(-.35523 .49056 -.5823 -.42167 9.893 3.478)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5j" cx="0" cy="0" r="1" gradientTransform="matrix(-.57137 .48177 -.74156 -.87947 16.529 6.275)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5k" cx="0" cy="0" r="1" gradientTransform="matrix(-.51712 .43601 -.67114 -.79598 16.657 5.833)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5l" cx="0" cy="0" r="1" gradientTransform="matrix(-.5123 .29547 -.46447 -.8053 16.785 5.295)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5m" cx="0" cy="0" r="1" gradientTransform="rotate(148.391 7.684 4.67) scale(.62453 .98682)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5n" cx="0" cy="0" r="1" gradientTransform="matrix(-.49016 .47848 -.703 -.72017 16.54 3.81)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5o" cx="0" cy="0" r="1" gradientTransform="matrix(-.35523 .49056 -.5823 -.42167 16.657 3.245)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5p" cx="0" cy="0" r="1" gradientTransform="matrix(.05666 .67537 -.77618 .06512 8.418 7.328)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5q" cx="0" cy="0" r="1" gradientTransform="matrix(.08211 .68595 -.73348 .0878 8.853 7.004)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5r" cx="0" cy="0" r="1" gradientTransform="matrix(.03562 .65312 -.79087 .04313 9.215 6.541)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5s" cx="0" cy="0" r="1" gradientTransform="rotate(91.792 1.732 7.47) scale(.63066 .86225)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5t" cx="0" cy="0" r="1" gradientTransform="matrix(-.06836 .58614 -.86885 -.10134 9.002 5.41)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5u" cx="0" cy="0" r="1" gradientTransform="matrix(.01333 .65549 -.83752 .01703 8.624 4.817)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5v" cx="0" cy="0" r="1" gradientTransform="rotate(84.134 1.865 6.9) scale(.47176 .52262)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5w" cx="0" cy="0" r="1" gradientTransform="matrix(.05666 .67537 -.77618 .06512 13.51 6.503)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5x" cx="0" cy="0" r="1" gradientTransform="matrix(.08211 .68595 -.73348 .0878 13.944 6.18)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5y" cx="0" cy="0" r="1" gradientTransform="matrix(.03562 .65312 -.79087 .04313 14.308 5.716)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id5z" cx="0" cy="0" r="1" gradientTransform="rotate(91.792 4.678 9.525) scale(.63066 .86225)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id60" cx="0" cy="0" r="1" gradientTransform="matrix(-.06836 .58614 -.86885 -.10134 14.094 4.585)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id61" cx="0" cy="0" r="1" gradientTransform="matrix(.01333 .65549 -.83752 .01703 13.716 3.992)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id62" cx="0" cy="0" r="1" gradientTransform="rotate(84.134 4.868 9.31) scale(.47176 .52262)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id63" cx="0" cy="0" r="1" gradientTransform="matrix(-.60306 .24084 -.3812 -.9545 7.782 8.283)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id64" cx="0" cy="0" r="1" gradientTransform="matrix(-.55926 .1863 -.29358 -.8813 7.766 7.62)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id65" cx="0" cy="0" r="1" gradientTransform="rotate(156.92 3.214 4.286) scale(.56077 .8858)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id66" cx="0" cy="0" r="1" gradientTransform="rotate(145.88 2.828 4.38) scale(.71235 1.01454)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id67" cx="0" cy="0" r="1" gradientTransform="matrix(-.5744 .29697 -.4593 -.88838 7.221 5.97)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id68" cx="0" cy="0" r="1" gradientTransform="matrix(-.51545 .31441 -.4665 -.76477 7.255 5.374)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id69" cx="0" cy="0" r="1" gradientTransform="matrix(-.25177 .12826 -.19887 -.39038 7.355 5.11)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6a" cx="0" cy="0" r="1" gradientTransform="matrix(-.60771 .22884 -.3622 -.96187 6.822 8.967)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.56284 .17518 -.27605 -.88694 6.704 8.244)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.5426 .25782 -.401 -.84393 6.687 7.583)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.59753 .3878 -.55232 -.85102 6.588 7.04)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6e" cx="0" cy="0" r="1" gradientTransform="rotate(153.798 2.33 4.013) scale(.64663 1.00009)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6f" cx="0" cy="0" r="1" gradientTransform="rotate(149.754 2.31 3.837) scale(.60378 .89581)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6g" cx="0" cy="0" r="1" gradientTransform="matrix(-.25426 .12324 -.19109 -.39425 6.344 5.728)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6h" cx="0" cy="0" r="1" gradientTransform="matrix(.60305 .24084 -.3812 .9545 16.88 6.96)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6i" cx="0" cy="0" r="1" gradientTransform="matrix(.55926 .1863 -.29359 .8813 16.896 6.298)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6j" cx="0" cy="0" r="1" gradientTransform="matrix(.51588 .21983 -.34725 .8149 16.811 5.647)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6k" cx="0" cy="0" r="1" gradientTransform="matrix(.58972 .39959 -.5691 .8399 17.036 5.096)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6l" cx="0" cy="0" r="1" gradientTransform="matrix(.5744 .29697 -.4593 .88839 17.44 4.648)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6m" cx="0" cy="0" r="1" gradientTransform="matrix(.51545 .3144 -.46649 .76478 17.406 4.052)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6n" cx="0" cy="0" r="1" gradientTransform="matrix(.25177 .12827 -.19888 .39037 17.307 3.789)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6o" cx="0" cy="0" r="1" gradientTransform="matrix(-.39378 .13594 -.2079 -.60223 12.5 7.216)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6p" cx="0" cy="0" r="1" gradientTransform="matrix(-.5778 .26324 -.41569 -.9124 12.768 6.897)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6q" cx="0" cy="0" r="1" gradientTransform="rotate(152.824 5.637 4.753) scale(.67167 1.06308)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6r" cx="0" cy="0" r="1" gradientTransform="rotate(151.005 5.65 4.588) scale(.66986 1.05656)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6s" cx="0" cy="0" r="1" gradientTransform="matrix(-.56853 .2934 -.4643 -.89973 12.647 5.302)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6t" cx="0" cy="0" r="1" gradientTransform="matrix(-.51771 .24146 -.38171 -.81843 12.38 4.732)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6u" cx="0" cy="0" r="1" gradientTransform="rotate(147.95 5.574 3.785) scale(.56289 .87465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6v" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 5.26 4.832) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6w" cx="0" cy="0" r="1" gradientTransform="matrix(.39952 .58558 -.86318 .58891 15.036 7.433)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6x" cx="0" cy="0" r="1" gradientTransform="rotate(52.574 .242 18.608) scale(.72077 1.10142)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6y" cx="0" cy="0" r="1" gradientTransform="rotate(49.411 .24 19.389) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id6z" cx="0" cy="0" r="1" gradientTransform="matrix(.44345 .5015 -.78798 .69676 14.862 5.885)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id70" cx="0" cy="0" r="1" gradientTransform="matrix(.4163 .54042 -.82723 .63722 14.952 5.149)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id71" cx="0" cy="0" r="1" gradientTransform="matrix(.31165 .61797 -.78667 .39673 14.872 4.439)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id72" cx="0" cy="0" r="1" gradientTransform="matrix(.32744 .54542 -.76209 .4575 14.307 4.084)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id73" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.5093 22.8681 0 16.238 7.258)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="b_qopxbfd"/><stop offset=".826" class="ii-90fbqe"/></radialGradient><radialGradient id="f975id74" cx="0" cy="0" r="1" gradientTransform="matrix(.64879 -.02746 .04346 1.02688 6.89 11.744)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id75" cx="0" cy="0" r="1" gradientTransform="matrix(.58649 -.05925 .09337 .9242 6.634 11.132)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id76" cx="0" cy="0" r="1" gradientTransform="matrix(.56066 -.0109 .0172 .88563 6.29 10.574)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id77" cx="0" cy="0" r="1" gradientTransform="matrix(.70168 .1228 -.1749 .99935 6.27 9.979)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id78" cx="0" cy="0" r="1" gradientTransform="matrix(.64566 .03548 -.05488 .99858 6.454 9.405)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id79" cx="0" cy="0" r="1" gradientTransform="matrix(.59903 .07555 -.1121 .88878 6.179 8.875)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7a" cx="0" cy="0" r="1" gradientTransform="matrix(.28222 .01381 -.02142 .4376 5.98 8.676)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.1539 .40088 -.42469 -.16304 6.457 15.905)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7c" cx="0" cy="0" r="1" gradientTransform="rotate(123.287 -.996 9.654) scale(.24934 .3622)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.18176 .40293 -.47819 -.2157 6.539 14.695)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7e" cx="0" cy="0" r="1" gradientTransform="matrix(-.215 .36633 -.50634 -.29717 6.468 15.32)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7f" cx="0" cy="0" r="1" gradientTransform="rotate(124.512 -.754 9.088) scale(.30762 .45474)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7g" cx="0" cy="0" r="1" gradientTransform="matrix(-.31463 .41795 -.63585 -.47866 6.431 14.09)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7h" cx="0" cy="0" r="1" gradientTransform="matrix(-.1783 .35084 -.44866 -.22801 6.785 13.788)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7i" cx="0" cy="0" r="1" gradientTransform="matrix(-.2428 .23573 -.37302 -.3842 6.194 13.694)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7j" cx="0" cy="0" r="1" gradientTransform="matrix(-.41027 .51646 -.79642 -.63266 6.561 13.086)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7k" cx="0" cy="0" r="1" gradientTransform="matrix(-.29056 .42827 -.63 -.42742 6.315 12.508)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7l" cx="0" cy="0" r="1" gradientTransform="matrix(-.27644 .34089 -.52803 -.4282 7.296 12.879)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7m" cx="0" cy="0" r="1" gradientTransform="matrix(-.38595 .51407 -.7815 -.58673 7.164 12.434)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7n" cx="0" cy="0" r="1" gradientTransform="matrix(-.35939 .35022 -.55426 -.56877 6.603 12.018)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7o" cx="0" cy="0" r="1" gradientTransform="matrix(-.1484 .29217 -.37349 -.1897 6.286 11.498)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7p" cx="0" cy="0" r="1" gradientTransform="matrix(-.21942 .4538 -.5631 -.27227 7.865 11.806)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7q" cx="0" cy="0" r="1" gradientTransform="matrix(-.42223 .55169 -.84306 -.64522 7.424 11.565)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7r" cx="0" cy="0" r="1" gradientTransform="matrix(-.39796 .51637 -.7905 -.60924 6.981 11.063)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7s" cx="0" cy="0" r="1" gradientTransform="matrix(-.34616 .46018 -.69994 -.52653 6.855 10.425)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7t" cx="0" cy="0" r="1" gradientTransform="rotate(123.98 1.579 7.25) scale(.47899 .70288)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7u" cx="0" cy="0" r="1" gradientTransform="matrix(-.38195 .47633 -.73607 -.59023 8.311 9.452)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7v" cx="0" cy="0" r="1" gradientTransform="matrix(-.40699 .47543 -.74365 -.6366 7.878 9.077)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7w" cx="0" cy="0" r="1" gradientTransform="matrix(-.40964 .43828 -.69228 -.64703 7.288 8.68)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7x" cx="0" cy="0" r="1" gradientTransform="rotate(126.214 1.388 5.748) scale(.61356 .92602)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7y" cx="0" cy="0" r="1" gradientTransform="matrix(-.2412 .55515 -.64241 -.27912 6.811 7.327)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id7z" cx="0" cy="0" r="1" gradientTransform="matrix(-.16981 .43608 -.46687 -.1818 7.066 6.877)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id80" cx="0" cy="0" r="1" gradientTransform="rotate(123.98 1.016 7.04) scale(.47899 .70288)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id81" cx="0" cy="0" r="1" gradientTransform="matrix(-.38195 .47633 -.73607 -.59023 7.26 9.593)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id82" cx="0" cy="0" r="1" gradientTransform="matrix(-.40699 .47543 -.74365 -.6366 6.83 9.218)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id83" cx="0" cy="0" r="1" gradientTransform="matrix(-.40964 .43828 -.69228 -.64703 6.239 8.82)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id84" cx="0" cy="0" r="1" gradientTransform="rotate(126.214 .828 5.552) scale(.61356 .92602)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id85" cx="0" cy="0" r="1" gradientTransform="matrix(-.2412 .55515 -.64241 -.27912 5.761 7.468)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id86" cx="0" cy="0" r="1" gradientTransform="matrix(-.16981 .43608 -.46687 -.1818 6.016 7.017)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id87" cx="0" cy="0" r="1" gradientTransform="matrix(-.45424 .15197 -.223 -.66657 6.343 12.964)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id88" cx="0" cy="0" r="1" gradientTransform="matrix(-.59228 .14573 -.22507 -.91474 6.544 12.439)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id89" cx="0" cy="0" r="1" gradientTransform="matrix(-.61235 .1292 -.2021 -.95783 6.43 11.877)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8a" cx="0" cy="0" r="1" gradientTransform="matrix(-.59184 .09812 -.15497 -.93481 6.205 11.201)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.589 .17184 -.25934 -.88896 6.252 10.412)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8c" cx="0" cy="0" r="1" gradientTransform="rotate(151.005 2.052 5.778) scale(.60528 .70043)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.40028 .24244 -.25955 -.42854 7.125 9.636)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8e" cx="0" cy="0" r="1" gradientTransform="rotate(121.922 1.167 7.619) scale(.70638 1.00376)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8f" cx="0" cy="0" r="1" gradientTransform="matrix(-.3897 .46817 -.72886 -.6067 7.966 10.46)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8g" cx="0" cy="0" r="1" gradientTransform="rotate(131.085 1.534 6.735) scale(.57137 .8961)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8h" cx="0" cy="0" r="1" gradientTransform="rotate(127.624 1.07 6.599) scale(.64728 .99094)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8i" cx="0" cy="0" r="1" gradientTransform="matrix(-.34548 .36461 -.57639 -.54615 6.16 9.65)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8j" cx="0" cy="0" r="1" gradientTransform="matrix(-.19278 .35876 -.47363 -.25451 5.914 9.18)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8k" cx="0" cy="0" r="1" gradientTransform="rotate(134.405 3.14 6.364) scale(.64937 1.0278)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8l" cx="0" cy="0" r="1" gradientTransform="rotate(137.751 3.26 5.842) scale(.58947 .92891)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8m" cx="0" cy="0" r="1" gradientTransform="matrix(-.38312 .40949 -.64683 -.60519 9.416 7.345)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8n" cx="0" cy="0" r="1" gradientTransform="matrix(-.37807 .60374 -.85986 -.53845 8.987 6.931)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8o" cx="0" cy="0" r="1" gradientTransform="rotate(128.836 2.618 5.362) scale(.64663 1.00009)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8p" cx="0" cy="0" r="1" gradientTransform="matrix(-.34452 .49583 -.73566 -.51117 8.227 6.126)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8q" cx="0" cy="0" r="1" gradientTransform="rotate(129.179 2.718 4.873) scale(.28256 .43811)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8r" cx="0" cy="0" r="1" gradientTransform="matrix(-.4 .36998 -.58395 -.63134 10.967 8.229)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8s" cx="0" cy="0" r="1" gradientTransform="matrix(-.4808 .52815 -.83245 -.75781 10.735 7.642)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8t" cx="0" cy="0" r="1" gradientTransform="matrix(-.48786 .51606 -.8157 -.77112 10.465 7.078)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8u" cx="0" cy="0" r="1" gradientTransform="matrix(-.43431 .43443 -.68776 -.68757 10.387 6.5)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8v" cx="0" cy="0" r="1" gradientTransform="matrix(-.41277 .35153 -.54942 -.64513 10.313 5.96)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8w" cx="0" cy="0" r="1" gradientTransform="rotate(124.902 3.555 5.328) scale(.60089 .89281)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8x" cx="0" cy="0" r="1" gradientTransform="matrix(-.2229 .4383 -.56075 -.28517 9.456 5.364)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8y" cx="0" cy="0" r="1" gradientTransform="rotate(130.91 4.932 6.898) scale(.73062 1.14487)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id8z" cx="0" cy="0" r="1" gradientTransform="matrix(-.47614 .5818 -.90288 -.73889 13.268 6.851)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id90" cx="0" cy="0" r="1" gradientTransform="matrix(-.40348 .69097 -.95266 -.5563 13.382 6.083)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id91" cx="0" cy="0" r="1" gradientTransform="rotate(128.24 4.107 6.861) scale(.74737 1.15038)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id92" cx="0" cy="0" r="1" gradientTransform="matrix(-.41868 .53126 -.81774 -.64445 12.075 7.423)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id93" cx="0" cy="0" r="1" gradientTransform="matrix(-.44226 .39262 -.61718 -.69522 12.092 6.87)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id94" cx="0" cy="0" r="1" gradientTransform="matrix(-.45502 .42777 -.67593 -.71898 11.848 6.23)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id95" cx="0" cy="0" r="1" gradientTransform="matrix(-.38371 .56742 -.83368 -.56377 11.552 5.465)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id96" cx="0" cy="0" r="1" gradientTransform="rotate(114.287 4.198 6.175) scale(.60567 .71895)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id97" cx="0" cy="0" r="1" gradientTransform="matrix(-.33045 .25366 -.38795 -.50538 14.587 7.965)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id98" cx="0" cy="0" r="1" gradientTransform="matrix(-.46465 .43271 -.6833 -.73373 14.742 7.578)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id99" cx="0" cy="0" r="1" gradientTransform="rotate(134.356 5.826 6.627) scale(.67167 1.06308)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9a" cx="0" cy="0" r="1" gradientTransform="matrix(-.45288 .49357 -.7785 -.71432 14.457 6.58)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.44631 .45838 -.7254 -.70631 14.119 6.101)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.41457 .39301 -.6213 -.65538 13.687 5.647)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.35791 .43445 -.67507 -.55615 13.397 5.009)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9e" cx="0" cy="0" r="1" gradientTransform="rotate(127.419 5.492 5.583) scale(.33962 .51894)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9f" cx="0" cy="0" r="1" gradientTransform="matrix(.61835 .2919 -.46093 .97645 15.896 7.659)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9g" cx="0" cy="0" r="1" gradientTransform="rotate(28.417 -6.14 34.843) scale(.72943 1.1539)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9h" cx="0" cy="0" r="1" gradientTransform="matrix(.65214 .3957 -.62051 1.02267 15.878 6.52)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9i" cx="0" cy="0" r="1" gradientTransform="rotate(151.928 7.49 5.034) scale(.65253 1.03266)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9j" cx="0" cy="0" r="1" gradientTransform="matrix(-.52466 .2534 -.40058 -.8294 16.188 5.374)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9k" cx="0" cy="0" r="1" gradientTransform="rotate(147.176 7.365 4.704) scale(.57411 .89209)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9l" cx="0" cy="0" r="1" gradientTransform="matrix(-.21048 .2751 -.42037 -.32162 16.083 4.213)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9m" cx="0" cy="0" r="1" gradientTransform="matrix(-.26933 .48838 -.65389 -.3606 17.252 7.62)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9n" cx="0" cy="0" r="1" gradientTransform="matrix(-.38841 .74917 -.96927 -.50253 17.765 7.381)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9o" cx="0" cy="0" r="1" gradientTransform="rotate(116.586 6.865 9.093) scale(.81785 1.03639)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9p" cx="0" cy="0" r="1" gradientTransform="matrix(-.36009 .70192 -.9026 -.46304 18.416 6.65)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9q" cx="0" cy="0" r="1" gradientTransform="matrix(-.36719 .60937 -.85292 -.51395 18.733 6.2)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9r" cx="0" cy="0" r="1" gradientTransform="matrix(-.38943 .522 -.79215 -.59096 18.789 5.56)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9s" cx="0" cy="0" r="1" gradientTransform="matrix(-.33144 .56044 -.7775 -.45981 18.683 4.758)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9t" cx="0" cy="0" r="1" gradientTransform="matrix(-.13851 .2262 -.31896 -.1953 18.832 4.535)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9u" cx="0" cy="0" r="1" gradientTransform="matrix(-.39952 .58558 -.86318 -.58891 20.092 7.936)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9v" cx="0" cy="0" r="1" gradientTransform="matrix(-.43804 .5724 -.87468 -.66937 20.256 7.61)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9w" cx="0" cy="0" r="1" gradientTransform="rotate(130.589 8.529 8.222) scale(.694 1.08569)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9x" cx="0" cy="0" r="1" gradientTransform="matrix(-.44346 .5015 -.78797 -.69677 20.266 6.387)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9y" cx="0" cy="0" r="1" gradientTransform="rotate(127.607 8.698 7.79) scale(.68217 1.0442)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975id9z" cx="0" cy="0" r="1" gradientTransform="matrix(-.31164 .61797 -.78668 -.39673 20.256 4.941)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida0" cx="0" cy="0" r="1" gradientTransform="matrix(-.32744 .54542 -.76209 -.4575 20.82 4.587)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida1" cx="0" cy="0" r="1" gradientTransform="rotate(119.752 8.29 10.263) scale(.77449 1.0565)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida2" cx="0" cy="0" r="1" gradientTransform="matrix(-.39243 .68052 -.93245 -.5377 21.609 7.915)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida3" cx="0" cy="0" r="1" gradientTransform="rotate(122.156 8.85 9.79) scale(.77138 1.10048)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida4" cx="0" cy="0" r="1" gradientTransform="rotate(125.683 9.259 9.047) scale(.72164 1.08257)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida5" cx="0" cy="0" r="1" gradientTransform="matrix(-.36761 .65023 -.88202 -.49866 22.06 6.096)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida6" cx="0" cy="0" r="1" gradientTransform="rotate(112.82 9.36 10.113) scale(.68462 .77491)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida7" cx="0" cy="0" r="1" gradientTransform="matrix(-.3235 .49929 -.72142 -.46742 22.978 5.094)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida8" cx="0" cy="0" r="1" gradientTransform="rotate(121.48 8.447 15.055) scale(.33416 .47119)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975ida9" cx="0" cy="0" r="1" gradientTransform="matrix(-.25622 .4883 -.6361 -.33378 25.768 15.043)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idaa" cx="0" cy="0" r="1" gradientTransform="matrix(-.24652 .48446 -.62 -.31548 25.98 13.761)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idab" cx="0" cy="0" r="1" gradientTransform="matrix(-.22611 .5132 -.59953 -.26415 25.634 14.248)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idac" cx="0" cy="0" r="1" gradientTransform="rotate(115.912 9.04 14.432) scale(.40516 .50424)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idad" cx="0" cy="0" r="1" gradientTransform="rotate(110.005 7.964 15.609) scale(.66379 .67563)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idae" cx="0" cy="0" r="1" gradientTransform="matrix(-.24423 .55783 -.64891 -.28411 25.808 13.024)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idaf" cx="0" cy="0" r="1" gradientTransform="matrix(-.21504 .55242 -.59127 -.23016 25.099 12.867)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idag" cx="0" cy="0" r="1" gradientTransform="matrix(-.2965 .54452 -.72408 -.39428 25.344 12.436)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idah" cx="0" cy="0" r="1" gradientTransform="matrix(-.32607 .48411 -.71022 -.47836 25.947 12.113)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idai" cx="0" cy="0" r="1" gradientTransform="matrix(-.1559 .31067 -.3943 -.19786 26.169 12.24)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idaj" cx="0" cy="0" r="1" gradientTransform="matrix(-.23809 .62772 -.65904 -.24996 24.64 11.59)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idak" cx="0" cy="0" r="1" gradientTransform="matrix(-.24831 .62058 -.6777 -.27117 25.237 11.431)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idal" cx="0" cy="0" r="1" gradientTransform="matrix(-.29458 .65172 -.77447 -.35006 25.62 10.768)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idam" cx="0" cy="0" r="1" gradientTransform="rotate(108.969 9.208 14.26) scale(.49097 .47787)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idan" cx="0" cy="0" r="1" gradientTransform="matrix(-.26729 .67156 -.73056 -.29077 24.295 10.425)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idao" cx="0" cy="0" r="1" gradientTransform="matrix(-.23124 .67189 -.65464 -.2253 24.825 10)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idap" cx="0" cy="0" r="1" gradientTransform="matrix(-.2496 .58684 -.66922 -.28463 25.302 9.457)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idaq" cx="0" cy="0" r="1" gradientTransform="matrix(-.29069 .57374 -.73237 -.37106 25.5 8.685)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idar" cx="0" cy="0" r="1" gradientTransform="rotate(118.244 10.504 11.655) scale(.78095 1.0308)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idas" cx="0" cy="0" r="1" gradientTransform="matrix(-.31615 .64312 -.80618 -.3963 26.185 7.186)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idat" cx="0" cy="0" r="1" gradientTransform="rotate(115.611 10.997 11.918) scale(.35713 .44074)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idau" cx="0" cy="0" r="1" gradientTransform="matrix(-.2678 .62259 -.71553 -.30777 23.55 9.37)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idav" cx="0" cy="0" r="1" gradientTransform="matrix(-.25032 .6439 -.68852 -.26767 24.085 9.288)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idaw" cx="0" cy="0" r="1" gradientTransform="matrix(-.2759 .59305 -.71813 -.3341 24.624 9.051)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idax" cx="0" cy="0" r="1" gradientTransform="matrix(-.31402 .54692 -.74776 -.42934 24.924 8.567)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975iday" cx="0" cy="0" r="1" gradientTransform="rotate(124.723 10.402 10.513) scale(.59011 .87474)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idaz" cx="0" cy="0" r="1" gradientTransform="matrix(-.29669 .58465 -.747 -.37908 24.913 7.251)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb0" cx="0" cy="0" r="1" gradientTransform="rotate(112.204 10.25 11.815) scale(.47176 .52262)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb1" cx="0" cy="0" r="1" gradientTransform="matrix(-.30114 .7201 -.81154 -.33937 22.561 8.554)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb2" cx="0" cy="0" r="1" gradientTransform="rotate(117.687 9.006 11.174) scale(.78603 1.02398)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb3" cx="0" cy="0" r="1" gradientTransform="matrix(-.41616 .60822 -.89749 -.61409 23.406 7.98)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb4" cx="0" cy="0" r="1" gradientTransform="matrix(-.42674 .56487 -.8602 -.64986 23.517 7.287)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb5" cx="0" cy="0" r="1" gradientTransform="matrix(-.3754 .6428 -.88632 -.51764 23.468 6.539)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb6" cx="0" cy="0" r="1" gradientTransform="matrix(-.3151 .61683 -.7912 -.40419 23.758 5.771)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb7" cx="0" cy="0" r="1" gradientTransform="matrix(-.15941 .26034 -.3671 -.22479 24.04 5.751)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb8" cx="0" cy="0" r="1" gradientTransform="matrix(-.28186 .55807 -.71106 -.35913 8.837 8.727)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idb9" cx="0" cy="0" r="1" gradientTransform="matrix(-.38813 .42988 -.67702 -.61126 8.375 8.52)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idba" cx="0" cy="0" r="1" gradientTransform="matrix(-.3659 .33394 -.52647 -.57684 8.175 7.931)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.38493 .38254 -.6056 -.60937 7.645 7.443)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><radialGradient id="f975idbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.19045 .25663 -.38886 -.28858 7.174 7.23)" gradientUnits="userSpaceOnUse"><stop class="opdlrynpx"/><stop offset=".749" class="traxwhbec"/><stop offset="1" class="egya017pd"/></radialGradient><filter id="f975idbd" width="6.478" height="6.278" x="3.917" y="15.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19963"/></filter><filter id="f975idbe" width="4.742" height="4.742" x="4.685" y="16.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".25"/></filter><filter id="f975idbf" width="6.528" height="6.528" x="21.805" y="15.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19963"/></filter><filter id="f975idbg" width="4.742" height="4.742" x="22.573" y="16.077" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".25"/></filter><filter id="f975idbh" width="4.809" height="6.541" x="13.129" y="16.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".375"/></filter><filter id="f975idbi" width="4.029" height="5.541" x="13.969" y="17.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".125"/></filter><filter id="f975idbj" width="5.383" height="3.169" x="18.206" y="11.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19963"/></filter><filter id="f975idbk" width="5.383" height="3.169" x="8.527" y="11.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19963"/></filter><filter id="f975idbl" width="1.303" height="1.133" x="18.788" y="16.427" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".05"/></filter><filter id="f975idbm" width="1.323" height="1.365" x="20.455" y="16.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".1"/></filter><filter id="f975idbn" width="1.502" height="1.603" x="12.104" y="16.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".1"/></filter><filter id="f975idbo" width="1.54" height="1.148" x="10.597" y="16.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".05"/></filter><filter id="f975idbp" width="4.727" height="2.061" x="18.48" y="12.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".25"/></filter><filter id="f975idbq" width="4.874" height="2.168" x="8.667" y="12.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19963" stdDeviation=".25"/></filter><linearGradient id="f975idbr" x1="7.056" x2="5.851" y1="18.972" y2="18.972" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="f975idbs" x1="26.987" x2="25.448" y1="16.396" y2="21.165" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="f975idbt" x1="23.572" x2="9.213" y1="19.18" y2="21.32" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="f975idbu" x1="5.838" x2="10.186" y1="24.25" y2="23.683" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="f975idbv" x1="14.358" x2="16.122" y1="20.42" y2="20.42" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="f975idbw" x1="17.748" x2="15.819" y1="21.026" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="f975idbx" x1="16.349" x2="16.349" y1="22.422" y2="21.345" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="f975idby" x1="14.033" x2="14.851" y1="25.459" y2="24.166" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="f975idbz" x1="21.543" x2="20.953" y1="17.267" y2="17.631" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="f975idc0" x1="13.275" x2="12.685" y1="17.267" y2="17.631" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="f975idc1" x1="21.572" x2="20.782" y1="13.244" y2="11.63" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="f975idc2" x1="11.598" x2="9.362" y1="13.004" y2="12.066" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-curly-hair-medium-light" /></template>
<style>
.a-h85_8bc {
  d: path("M25.292 10.592c.084-.185.292-.277.385-.3c.034.213.204.49.435.644a.97.97 0 0 0 .433.164c.15.146.02.364-.084.411c-.171.091-.48.197-.821-.051c-.342-.248-.454-.638-.348-.868Z");
}

.a1sib3b5q {
  d: path("M18.16 3.777c.05-.23.263-.3.363-.307c.228.29.442.303.679.387c.236.084.267.237.224.412a.423.423 0 0 1-.17.25a2.653 2.653 0 0 1-.522-.08c-.33-.093-.635-.374-.574-.662Z");
}

.a228lp2it {
  d: path("M20.842 7.959c-.006-.35.144-.521.22-.563c.093.494.707.724 1.003.777a.485.485 0 0 1-.563.516c-.246-.039-.652-.293-.66-.73Z");
}

.a30le0b1i {
  d: path("M6.53 10.81c-.388-.234-.378-.527-.325-.644c.017-.063.154-.156.567-.028c.515.16.5.477.476.606c-.023.129-.234.36-.718.066Z");
}

.a4wwz57ns {
  d: path("M13.698 5.09c-.278-.21-.283-.473-.25-.579c.225.182.467.18.65.007c.182-.172.492-.072.46.233c-.032.305-.512.6-.86.339Z");
}

.a55m8e_nc {
  d: path("M23.753 5.33c.044-.232-.126-.38-.216-.424c-.322.18-.525.11-.775.096c-.25-.014-.339.115-.366.293a.422.422 0 0 0 .06.296c.126.045.313.101.512.128c.34.04.731-.1.785-.39Z");
}

.a5i1kuj7c {
  d: path("M18.344 7.967c-.173-.28-.088-.674 0-.797c.35.544.839.492 1.04.399c.085.132.186.407 0 .57c-.22.191-.774.258-1.04-.172Z");
}

.aacym8d0c {
  d: path("M15.861 5.694a.95.95 0 0 1 .118-.414c.01.043.093.165.332.303c.24.139.567.176.702.177c.127.078.12.264.065.4c-.056.136-.283.348-.649.245c-.365-.103-.58-.498-.568-.71Z");
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.ark48u8aj {
  d: path("M21.05 7.47a.485.485 0 0 1 .218-.46c.2.218.724.419.96.492c.31.515-.183.855-.546.726c-.363-.129-.601-.441-.633-.758Z");
}

.atxkpcagh {
  d: path("M11.553 5.115c-.124-.163-.096-.383-.067-.472c.542.228.976.129 1.125.05c.079.048.23.189.208.375c-.028.233-.229.45-.555.425a.95.95 0 0 1-.71-.378Z");
}

.aujie4ucq {
  d: path("M8.545 6.829a.341.341 0 0 1 .025-.42c.215.409.647.577.836.61c-.32.211-.712.053-.86-.19Z");
}

.auk7h9blb {
  d: path("M22.293 3.082c-.066-.22-.283-.3-.383-.312c.038.066 0 .266-.162.36c-.162.094-.335.193-.398.365c-.05.138.056.263.115.31c.102-.051.333-.027.518-.12c.185-.094.392-.328.31-.603Z");
}

.ay5kyxbjb {
  d: path("M19.37 5.556c.043-.231.255-.307.355-.316c.234.285.45.293.688.371c.238.078.273.23.234.406a.422.422 0 0 1-.164.254a2.653 2.653 0 0 1-.524-.066c-.332-.086-.644-.36-.59-.649Z");
}

.b_qopxbfd {
  stop-color: var(--svg-color--c5a182, #C5A182);
}

.b6l3cf9pv {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.473 15.758c1.228 0 2.265.847 2.547 1.99a.515.515 0 0 1-.503.641h-4.195a.433.433 0 0 1-.427-.51a2.628 2.628 0 0 1 2.578-2.12Z");
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.baabe40zf {
  d: path("M21.348 7.433c.23-.235.235-.638.176-.777c-.462.453-.927.295-1.102.16c-.113.11-.271.355-.125.556c.17.235.697.422 1.051.061Z");
}

.bc-m_schn {
  d: path("M7.073 7.126c-.063-.106-.031-.194-.007-.225c.527.1.738-.106.812-.167c.074-.061.352-.032.383.263a.422.422 0 0 1-.22.42c-.079-.052-.176-.065-.464-.107a1.377 1.377 0 0 1-.504-.184Z");
}

.bdgkthbrm {
  d: path("M9.765 3.603a.52.52 0 0 1 .245-.355c.144.206.362.249.613.259c.25.01.35.165.376.255a.371.371 0 0 1-.07.33c-.205-.032-.593.031-.79-.036c-.197-.067-.409-.214-.374-.453Z");
}

.bepdx4gdr {
  d: path("M14.48 5.216a.44.44 0 0 1 .136-.27c.02.03.286.151.44.194c.305.086.554.065.64.043c.4.295.11.933-.514.758c-.625-.176-.713-.565-.702-.725Z");
}

.bf_gkifky {
  d: path("M24.619 9.33a.663.663 0 0 1 .04-.447c.323.436.629.454.88.463c.2.007.34-.091.384-.141c.203.538-.244.78-.61.733c-.365-.047-.625-.372-.694-.608Z");
}

.bf0rmc-1l {
  d: path("M15.325 4.236c.074-.214-.08-.38-.166-.437c-.273.198-.565.178-.765.169c-.2-.01-.332.013-.419.172c-.086.158-.08.549.452.516c.531-.032.806-.151.898-.42Z");
}

.bkf58e6tk {
  d: path("M12.648 4.643c-.124-.162-.096-.382-.067-.472c.543.228.976.13 1.125.051c.079.047.23.188.208.375c-.028.233-.23.449-.555.425a.95.95 0 0 1-.71-.379Z");
}

.bp0_2abkw {
  d: path("M8.62 8.869a.489.489 0 0 1-.333.14c-.022.313.241.368.375.356c.465-.168.578-.711.457-.922c-.12-.21-.379-.145-.398-.066c-.02.078.062.34-.102.492Z");
}

.brekr5pfn {
  d: path("M8.71 9.69c-.226.258-.573.305-.72.296c-.109.254 0 .547.329.438c.328-.11.472-.395.465-.544c-.007-.118-.052-.177-.075-.19Z");
}

.bvdw2yd7r {
  d: path("M11.518 3.27c-.049-.377-.38-.51-.54-.53c-.164-.01-.247.052-.233.202c.012.12.13.25.187.3c-.071.028-.216.118-.224.262c.022.267.181.355.333.37c.152.016.539-.132.477-.604Z");
}

.bxiy47bnf {
  d: path("M21.613 6.14a.441.441 0 0 0-.066-.296c-.026.024-.315.077-.475.081a1.405 1.405 0 0 1-.63-.115c-.46.189-.335.878.314.86c.648-.017.829-.373.857-.53Z");
}

.byxip0b8c {
  d: path("M6.297 10.279c-.107-.078-.123-.215-.118-.274c.137-.039.235-.18.329-.324c.144-.222.285-.32.504-.285c.21.034.354.221.398.332c-.34.121-.46.414-.578.55c-.117.138-.403.099-.535 0Z");
}

.c-wgctb2w {
  d: path("M14.837 2.908c.144-.168.38-.18.48-.164c-.04.09-.069.332.044.481c.112.15.247.232.314.266a.394.394 0 0 1-.109.435c-.143-.05-.342-.06-.588-.225c-.246-.166-.322-.582-.141-.793Z");
}

.c272z_bvq {
  d: path("M12.068 6.576c-.172-.203-.12-.477-.071-.588c.05.09.24.291.589.382a.647.647 0 0 0 .673-.204c.039.028.114.123.105.278c-.016.295-.228.447-.513.475c-.285.029-.567-.09-.783-.343Z");
}

.c5_ol8bjh {
  d: path("M15.17 5.426a.663.663 0 0 0-.004-.45c-.357.409-.664.402-.914.391a.516.516 0 0 1-.372-.172c-.246.52.18.798.548.78c.369-.017.654-.32.742-.55Z");
}

.c5ry__b1p {
  d: path("M11.722 5.428c.064-.16.004-.377-.033-.465c-.341.16-.54.09-.944.163c-.404.073-.47.249-.45.45c.021.2.156.42.553.361c.398-.058.795-.31.874-.51Z");
}

.c7m5vwvei {
  d: path("M9.961 5.99c-.178-.26-.056-.532.028-.636c-.001.1.087.346.445.539c.359.193.663.043.77-.056c.047.065.09.405-.264.558c-.352.153-.756-.08-.979-.406Z");
}

.c95kz21hb {
  d: path("M22.752 5.658c-.153.05-.49-.13-.387-.543c.156-.633 1.09-.4.98-.098c-.031.086-.152.117-.242.098c-.09-.02-.148-.067-.129.156c.02.223-.07.336-.222.387Z");
}

.c9vrwsbhf {
  d: path("M25.19 9.64c.072-.178.27-.21.36-.203c.027.211.222.36.605.438c.191.039.433.199.277.476c-.16.283-.668.153-.969-.05c-.3-.204-.363-.438-.273-.66Z");
}

.ca8tm4bmu {
  d: path("M20.592 5.213a.59.59 0 0 1-.394-.704c.103-.444.671-.394.898-.168c.113.113.145.239.05.329c-.093.09-.178.058-.276.023c-.098-.035-.227-.098-.114.035s.145.203.043.336a.373.373 0 0 1-.207.149Z");
}

.cf-nu_c0o {
  cx: 12.211px;
  cy: 3.642px;
  rx: 0.322px;
  ry: 0.257px;
}

.cfq28cjgl {
  d: path("M12.342 6.795c.031-.207.227-.344.32-.387c.278.469.645.426.88.445c.234.02.374.305.206.524c-.168.218-.652.144-.918.039c-.265-.106-.527-.364-.488-.621Z");
}

.chf6oxp2l {
  d: path("M6.715 12.868c-.336.069-.64-.107-.75-.203c-.242.135-.334.434-.007.547c.327.113.615-.025.7-.147c.067-.098.066-.172.057-.197Z");
}

.ciw3q8r5v {
  d: path("M7.43 5.922c-.025-.12.032-.194.064-.216c.47.26.735.131.824.096c.09-.035.344.079.282.37a.422.422 0 0 1-.34.33c-.06-.074-.223-.019-.484-.149a.647.647 0 0 1-.345-.43Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm6w2xb7s {
  d: path("M5.545 9.224c-.037-.187.073-.276.133-.297c.187-.093.328.168.399.262c.07.094.117.277-.07.375c-.25.106-.415-.105-.462-.34Z");
}

.cnx048bao {
  d: path("M13.711 5.588c-.148-.222-.062-.487-.001-.592c.04.095.204.318.54.448a.647.647 0 0 0 .692-.122c.035.032.099.135.071.288c-.05.292-.278.417-.565.412c-.287-.006-.552-.157-.737-.434Z");
}

.cow9uybav {
  cx: 23.976px;
  cy: 5.8px;
  r: 0.248px;
}

.coyn1nb7m {
  d: path("M18.348 7.3a.664.664 0 0 1 .059-.446c.304.449.609.48.859.5c.2.015.344-.077.39-.125c.18.547-.277.77-.64.707c-.363-.063-.61-.399-.668-.637Z");
}

.ctlqqkb6m {
  d: path("M18.553 2.88c.145-.168.38-.18.48-.164c-.04.09-.068.332.044.482c.112.15.247.231.314.265a.394.394 0 0 1-.108.435c-.144-.05-.343-.059-.589-.225c-.246-.166-.322-.582-.141-.793Z");
}

.cybjr2min {
  d: path("M13.835 5.974c-.118-.234-.06-.437-.015-.51l.719.17c.249.169.38.48.095.676c-.286.196-.652-.042-.8-.336Z");
}

.d_3p_5bmw {
  d: path("M17.588 5.804c.063-.106.031-.194.008-.225c-.528.1-.738-.105-.813-.167c-.074-.06-.351-.032-.383.264a.422.422 0 0 0 .22.42c.08-.053.176-.066.465-.108c.23-.034.432-.137.503-.184Z");
}

.d-12igb3j {
  d: path("M21.471 5.7c.122-.098.326-.114.387-.089c.039.145.174.35.347.438c.188.093.286.16.282.414c-.003.203-.215.337-.32.378c-.491-.118-.62-.375-.622-.488c-.234-.16-.277-.488-.074-.652Z");
}

.d-uusg05r {
  d: path("M11.306 4.367c-.018-.146.101-.292.163-.346c.374.133.654.105.869.099c.215-.007.407.144.403.298a.419.419 0 0 1-.126.269c-.175.103-.499.14-.826.055c-.327-.085-.462-.192-.483-.375Z");
}

.d0xmf00ty {
  d: path("M15.388 4.147c-.14-.172-.376-.189-.476-.176c.039.092.06.334-.055.48a.929.929 0 0 1-.32.259a.394.394 0 0 0 .097.437c.145-.047.344-.05.594-.21c.25-.16.336-.575.16-.79Z");
}

.d2hq1p0ee {
  d: path("M14.421 6.536c-.166-.285-.072-.677.02-.797c.336.552.826.512 1.028.423c.083.135.177.412-.013.57c-.224.187-.78.24-1.035-.196Z");
}

.d3shv8osz {
  d: path("M11.912 3.719a.623.623 0 0 0-.404-.477c-.02.314-.402.466-.55.506c-.15.04-.361.09-.284.432c.077.342.572.367.813.267c.24-.1.492-.354.425-.728Z");
}

.d65n58bni {
  d: path("M7.561 8.99a.967.967 0 0 1-.477.18c0 .097 0 .46.477.453c.477-.008.715-.309.773-.453c.06-.145-.023-.383-.246-.442c-.222-.058-.312.098-.527.262Z");
}

.d66mdjtrd {
  d: path("M13.78 4.464c.124-.162.096-.382.067-.472c-.542.228-.976.129-1.125.05c-.079.048-.23.189-.208.375c.028.233.23.45.555.425a.951.951 0 0 0 .711-.378Z");
}

.daeuyr99u {
  cx: 20.508px;
  cy: 2.64px;
  r: 0.216px;
}

.db7hm60ne {
  d: path("M22.721 7.858c.264-.199.328-.597.29-.743c-.524.38-.96.154-1.113-.006c-.128.093-.322.312-.207.531c.134.258.627.522 1.03.218Z");
}

.dekw5j1eb {
  d: path("M8.362 7.521c.112.106.25.11.304.098a.948.948 0 0 0 .692-.508c.14-.273.043-.535-.078-.602a.27.27 0 0 0-.352.067c-.098.113-.043.238-.187.46c-.116.179-.374.216-.489.212c-.01.047-.003.167.11.273Z");
}

.dhfc9fbya {
  d: path("M11.986 7.253a.341.341 0 0 1-.024-.42c.262.38.71.496.901.506c-.293.249-.7.137-.877-.086Z");
}

.dhq9j25jd {
  d: path("M14.299 2.893a.59.59 0 0 0 .478-.65c-.048-.453-.618-.473-.87-.276c-.127.098-.174.218-.092.319c.082.1.171.08.272.057c.102-.023.238-.069.109.05c-.129.117-.169.183-.084.327a.372.372 0 0 0 .187.173Z");
}

.dlapr5yrz {
  d: path("M19.748 4.22c-.018-.226.082-.387.211-.423c.469.54.703.33.898.66c.09.153.008.575-.402.493c-.41-.082-.683-.45-.707-.73Z");
}

.dni3hdb2l {
  cx: 18.778px;
  cy: 4.579px;
  r: 0.216px;
}

.dqj1tqbue {
  d: path("M12.71 5.139c-.054-.224.094-.401.175-.462c0 .076.133.231.32.231c.188 0 .387 0 .528.117c.112.094.083.256.054.325c-.113.008-.3.144-.507.156c-.207.01-.504-.087-.57-.367Z");
}

.dvdi_0mte {
  d: path("M20.084 16.27a1.678 1.678 0 0 1 1.616 2.12h-3.24a1.72 1.72 0 0 1-.062-.443c0-.923.755-1.678 1.686-1.678Z");
}

.dwceu1nxh {
  d: path("M6.817 12.033a.826.826 0 0 1-.217-.518c.133.06.295.072.56-.187c.265-.258.518-.192.632-.114c.114.078.229.343-.048.693c-.277.349-.705.373-.927.126Z");
}

.dx9ojm79q {
  d: path("M13.291 6.467c-.078-.125-.032-.308 0-.383c.395-.04.637-.184.829-.282c.19-.097.43-.043.492.098a.42.42 0 0 1 0 .297c-.114.168-.39.34-.723.402c-.332.063-.5.024-.598-.132Z");
}

.dz47eqb5s {
  d: path("M15.374 5.939a.341.341 0 0 1 .025-.42c.215.408.646.576.835.61c-.32.211-.711.052-.86-.19Z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e0zahybqs {
  d: path("M14.462 4.669c-.041-.223.136-.365.229-.409c.24.237.533.26.732.28c.198.02.326.062.389.232c.062.17-.002.555-.523.444c-.52-.11-.775-.268-.827-.547Z");
}

.e3xwhhb3b {
  d: path("M13.922 5.369c.178-.26.056-.532-.027-.635c0 .099-.088.345-.446.538a.674.674 0 0 1-.77-.056c-.047.065-.09.405.264.558c.353.154.757-.08.979-.405Z");
}

.e77z8gb7a {
  d: path("M19.413 8.287c-.174-.28-.089-.675 0-.797c.35.544.838.492 1.038.398c.086.133.187.407 0 .57c-.218.192-.773.258-1.038-.171Z");
}

.e8un3-1or {
  d: path("M11.851 5.868a1.038 1.038 0 0 0-.131-.452c-.012.048-.1.181-.361.335c-.26.153-.619.196-.766.198c-.138.087-.13.29-.068.438c.063.149.313.379.712.263c.399-.116.629-.55.614-.782Z");
}

.e9luk_bdd {
  d: path("M25.159 7.498c.156-.14.39-.108.472-.086c.035.197.078.294.14.344c.505.4.43.636.321.78c-.096.128-.281.16-.351.169c-.157-.188-.414-.367-.582-.524c-.168-.156-.2-.503 0-.683Z");
}

.eb25llg0t {
  d: path("M25.678 8.642a3.375 3.375 0 0 0-.43-.394l-.246.129l-.07.406l.316.523c.132.035.416.076.5-.043c.106-.148.157-.375-.07-.62Z");
}

.ecoyd1dhh {
  d: path("M9.623 6.025a.434.434 0 0 1-.336-.191c.176-.657.645-.782.836-.743c.192.04.325.301.165.559a.785.785 0 0 1-.665.375Z");
}

.efw1r88ah {
  d: path("M13.848 4.937c.147-.221.062-.487.001-.592c-.04.095-.204.318-.54.449a.647.647 0 0 1-.692-.123c-.035.033-.099.136-.072.289c.051.291.28.417.566.411c.287-.005.552-.157.737-.434Z");
}

.egya017pd {
  stop-color: var(--svg-color--b08c60, #B08C60);
}

.ehixovtvr {
  d: path("M6.13 9.807c-.116.374.14.564.275.63c.416-.098.293-.439.3-.66a.311.311 0 0 1 .186-.286c-.343-.214-.663-.002-.761.316Z");
}

.enpb9_68e {
  d: path("M14.441 5.868a.663.663 0 0 1 .07-.444c.293.457.597.495.847.52a.514.514 0 0 0 .393-.115c.166.551-.296.763-.657.692c-.362-.072-.6-.413-.653-.653Z");
}

.eos0x8blt {
  d: path("M23.866 10.177a.515.515 0 0 1 .55-.253c-.072.409.093.694.184.785c.063.468-.356.586-.574.406a.778.778 0 0 1-.16-.938Z");
}

.er8tzqbbl {
  stop-color: var(--svg-color--c48586, #C48586);
  stop-opacity: 0;
}

.eunszr3ix {
  d: path("M9.855 4.337c-.017-.146.102-.292.164-.346c.373.133.654.105.868.099c.215-.007.407.144.404.298a.418.418 0 0 1-.127.268c-.174.104-.498.141-.825.056c-.327-.085-.462-.192-.484-.375Z");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f_m-xrb0p {
  d: path("M8.742 6.8c-.118-.235-.059-.438-.015-.51l.72.17c.248.168.38.479.094.675c-.285.196-.651-.043-.799-.336Z");
}

.f0iqddcpu {
  d: path("M17.682 4.439c.074-.215-.08-.382-.166-.438c-.273.198-.565.178-.765.169c-.2-.01-.332.014-.419.172c-.087.159-.08.55.452.517c.531-.033.806-.152.898-.42Z");
}

.f9nl86h_t {
  d: path("M7.565 6.08c.04-.194.225-.302.312-.332l.39.27c.231-.005.458.195.317.433c-.14.238-.324.281-.632.215a.488.488 0 0 1-.387-.586Z");
}

.fekfogg3l {
  d: path("M6.14 8.021a.462.462 0 0 1 .253-.375c.2.317.324.297.61.297c.281.05.284.318.25.445a.776.776 0 0 1-.592.2c-.352-.032-.541-.297-.522-.567Z");
}

.fkiyofdzi {
  d: path("M7.284 4.89c-.072-.293.16-.519.285-.596c-.008.125.091.377.353.53c.21.122.384.002.445-.073c.216.17.127.368.056.445c-.133.049-.296.27-.544.23c-.248-.04-.504-.17-.595-.536Z");
}

.fny1fvqvu {
  stop-color: var(--svg-color--b67a64, #B67A64);
}

.ft5dv1b6b {
  fill: none;
}

.fwwl4e3wr {
  d: path("M24.644 9.998c-.186-.273-.118-.67-.034-.796c.373.528.858.456 1.055.354c.091.129.203.398.024.57c-.21.2-.762.29-1.045-.128Z");
}

.fwzlmgbnn {
  d: path("M7.24 13.267c-.29-.028-.443-.189-.484-.265l.77-.383c.191.258.078.683-.285.648Z");
}

.fym4ola-r {
  d: path("M12.58 5.117c-.147-.222-.062-.488 0-.593c.04.095.203.318.539.45a.648.648 0 0 0 .693-.123c.035.032.098.135.07.288c-.05.291-.278.417-.565.411c-.286-.005-.552-.156-.736-.433Z");
}

.fyzrg1mbc {
  d: path("M16.686 6.841c.156-.155.14-.528.121-.628c-.61.166-1.041.035-1.19-.069c-.09.04-.307.21-.31.412c-.002.252.18.562.532.582a1.1 1.1 0 0 0 .847-.297Z");
}

.g-2tuvdba {
  d: path("M13.44 3.633a.52.52 0 0 1 .246-.355c.144.207.362.249.612.259c.25.01.35.165.377.255a.371.371 0 0 1-.07.33c-.205-.032-.593.031-.79-.036c-.198-.067-.41-.214-.374-.453Z");
}

.g0djkcbml {
  d: path("M14.112 8.162a.341.341 0 0 1-.156-.39c.369.277.83.245 1.015.194c-.2.329-.62.352-.86.196Z");
}

.g1-f58biz {
  d: path("M22.788 6.24c.103-.156.303-.193.39-.192c.067.192.216.291.377.346c.16.055.35.133.35.428c0 .238-.194.41-.282.453a1.209 1.209 0 0 1-.335-.117a.49.49 0 0 1-.227-.309c-.29-.144-.402-.414-.273-.61Z");
}

.g2i_i4xjf {
  d: path("M6.285 14.592c0-.502.202-1.104.605-1.404l.303-.301c.504-.401 0-1.31 0-1.91l.706-1.3c0-.5.302-.902.807-1.002c1.21-.3 3.74-1.543 7.371-1.543c3.63 0 6.143 1.242 7.354 1.543c.403.1.807.501.807 1.003l.577 1.4c0 .602.187 1.057.59 1.458c.944.662.424 1.376.345 2.156c-.338 3.368-.44 6.771-.667 10.15c-.302 3.327-2.918 5.646-6.036 5.646H13.01c-3.22 0-5.734-2.319-6.036-5.646c-.264-3.43-.378-6.845-.689-10.25Z");
}

.g4b5g7bln {
  d: path("M9.545 6.463A.453.453 0 0 1 9.6 6.17c.3.23.586.18.84.171c.254-.007.48.13.449.391c-.031.262-.52.336-.86.2c-.34-.137-.453-.321-.484-.47Z");
}

.g57utsram {
  d: path("M19.391 3.463a.59.59 0 0 1-.377-.712c.113-.442.68-.379.902-.147c.11.116.138.242.043.33c-.096.087-.181.054-.278.017c-.097-.038-.224-.104-.114.032c.11.135.14.206.035.337a.372.372 0 0 1-.21.143Z");
}

.g6-7prbgs {
  d: path("M24.683 7.604a.441.441 0 0 0-.065-.296c-.027.024-.315.077-.475.081a1.405 1.405 0 0 1-.63-.114c-.46.188-.335.877.313.86c.65-.018.83-.374.857-.531Z");
}

.g69qbdccm {
  d: path("M12.42 5.78a.341.341 0 0 1 .025-.42c.215.408.646.576.835.609c-.32.212-.712.053-.86-.19Z");
}

.g7fsp6bcq {
  d: path("M19.74 4.65c.141-.172.377-.189.477-.176c-.039.091-.06.334.055.48a.93.93 0 0 0 .32.259a.394.394 0 0 1-.098.437c-.144-.047-.343-.05-.593-.21c-.25-.161-.336-.575-.16-.79Z");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g8h3861of {
  d: path("M24.56 8.133c-.056-.22.11-.374.201-.423c.256.22.55.223.749.23c.2.007.33.04.403.206c.074.164.036.553-.491.478c-.527-.075-.791-.217-.862-.491Z");
}

.g8ng4ub5p {
  d: path("M8.098 6.961a.347.347 0 0 1 .416.066c.352.286.467.734.257.913c-.21.178-.555.056-.726-.207c-.17-.262-.2-.65.053-.772Z");
}

.g8nombgea {
  d: path("M18.243 4.61c.11-.172.065-.389.028-.476c-.521.272-.962.21-1.117.144c-.074.054-.213.206-.176.39c.047.23.266.429.588.378a.95.95 0 0 0 .677-.436Z");
}

.gcjgmggiz {
  d: path("M24.425 5.632c.133-.178.368-.205.469-.196c-.035.093-.047.336.075.478a.93.93 0 0 0 .33.244a.394.394 0 0 1-.078.44c-.147-.04-.346-.035-.602-.185c-.257-.149-.36-.559-.194-.781Z");
}

.ge-pa6b3z {
  d: path("M20.643 7.845c.116-.165.267-.201.328-.199c-.016.513.52.878.79.996c-.106.352-.599.375-.911.098c-.313-.277-.352-.688-.207-.895Z");
}

.gg3m-ccqn {
  d: path("M17.644 3.764a.324.324 0 0 0-.067-.2a.576.576 0 0 0-.438.15c-.096.11.01.294.196.298c.185.003.312-.117.31-.248Z");
}

.gh1_qnu_h {
  d: path("M11.614 3.94c.02-.228.217-.35.313-.381c-.024.072.053.26.23.32c.178.06.367.123.463.278c.077.125-.002.27-.05.326c-.11-.028-.332.041-.531-.014c-.2-.054-.45-.242-.425-.528Z");
}

.gi8fu2bxl {
  d: path("M7.854 11.287a.56.56 0 0 1-.332-.403c.133-.141.463-.466.723-.628c.324-.204.554.18.382.628c-.172.45-.476.536-.773.403Z");
}

.gke_yzgbl {
  d: path("M7.858 7.13c-.25-.168-.23-.492-.188-.632c.079.097.32.219.617.156a.342.342 0 0 0 .282-.352c.275-.018.34.188.34.293c-.067.125-.04.399-.25.536c-.211.136-.489.21-.801 0Z");
}

.gn5u78erv {
  d: path("M22.484 6.178c.156-.274.012-.535-.08-.63c.01.098-.058.35-.4.573c-.34.222-.656.098-.77.008c-.042.069-.057.41.308.534c.364.124.747-.143.942-.485Z");
}

.goeq79b8a {
  d: path("M16.654 7.323c.19-.216.136-.512.086-.633c-.056.096-.263.311-.64.403c-.377.092-.596-.145-.68-.26a.428.428 0 0 0-.16.33c.014.317.24.484.546.518c.307.035.612-.089.848-.358Z");
}

.goknvdham {
  d: path("M7.634 11.51c.029-.335-.243-.53-.382-.585c-.061.36-.502.657-.663.69c-.13.027-.154.122-.15.166c.068.14.097.298.103.36c.56.205 1.056-.211 1.092-.63Z");
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gt18rvbma {
  d: path("M17.584 4.978a.44.44 0 0 0-.095-.288c-.024.026-.305.108-.464.128a1.406 1.406 0 0 1-.64-.052c-.437.233-.245.906.398.825c.644-.082.789-.453.8-.613Z");
}

.gwy949bqg {
  d: path("M26.478 10.693c.25-.214.29-.615.244-.759c-.5.411-.95.213-1.111.062c-.123.1-.303.33-.175.543c.15.25.658.482 1.042.154Z");
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gxngfta-o {
  d: path("M5.09 8.162a.462.462 0 0 1 .253-.375c.199.316.324.297.61.297c.28.05.284.317.25.445a.776.776 0 0 1-.593.2c-.35-.033-.54-.298-.52-.567Z");
}

.gxw5tpz-p {
  d: path("M24.562 8.245a.664.664 0 0 0 .041-.447c-.396.37-.7.334-.948.298a.516.516 0 0 1-.354-.208c-.295.494.101.812.47.83c.367.02.682-.254.791-.473Z");
}

.gyxy_5-dg {
  d: path("M25.94 12.845c-.056-.034-.167-.178-.215-.246l-.395.446c.024.566.422.746.653.53c.23-.214.027-.456 0-.53c-.028-.075.027-.157-.043-.2Z");
}

.gzv9xexwk {
  d: path("M5.686 7.088a.45.45 0 0 0 .188.43c.304-.044.375-.294.324-.493c-.05-.2-.16-.336-.27-.34c-.109-.004-.214.098-.242.403Z");
}

.gzzab_b6l {
  rx: 0.322px;
  ry: 0.257px;
}

.h_1rewmtj {
  d: path("M6.893 7.545c.166.315.454.352.578.332c.075-.163.294-.196.395-.192h.214c.012-.047.07-.387-.238-.5c-.304-.111-.465.078-.637.207a.825.825 0 0 1-.312.153Z");
}

.h-53bgbhr {
  d: path("M7.77 3.913c.16-.116.37-.073.455-.037l.11.462c.173.151.208.451-.056.534c-.264.083-.43-.008-.614-.264a.488.488 0 0 1 .105-.695Z");
}

.h-53emb2c {
  d: path("M7.51 8.123a.427.427 0 0 1-.047-.25c.097-.17.33-.2.434-.196c.061.002.22.003.37 0c.188-.004.364.098.33.36c-.03.209-.231.272-.33.277H7.94c-.2 0-.364-.078-.43-.191Z");
}

.h-69yhbju {
  d: path("M18.566 5.723a.341.341 0 0 0-.06-.416c-.18.425-.597.628-.782.676c.336.185.713-.006.842-.26Z");
}

.h029u5oce {
  d: path("M15.603 4.803c-.124-.162-.097-.383-.067-.472c.542.228.976.129 1.125.05c.078.048.23.189.207.375c-.027.233-.229.45-.554.425a.95.95 0 0 1-.711-.378Z");
}

.h05ur_b5g {
  d: path("M6.279 8.514a.323.323 0 0 0-.144-.155a.576.576 0 0 0-.338.317c-.042.14.13.264.3.191c.171-.072.238-.234.182-.353Z");
}

.h06mln5vl {
  d: path("M5.92 14.369c-.118-.15-.111-.375-.093-.469c.105.063.245.046.451-.074c.24-.14.46.004.51.316c.05.313-.117.402-.242.422c-.125.02-.477-.008-.625-.195Z");
}

.h1fy1vbrb {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m8.888 13.335l.001-.002l.002-.001l.003-.003l.009-.007l.022-.018a3.712 3.712 0 0 1 .291-.202c.188-.117.454-.263.79-.396a5.326 5.326 0 0 1 2.806-.298a1.004 1.004 0 0 1-.313 1.983a3.32 3.32 0 0 0-1.755.181a2.854 2.854 0 0 0-.565.3l-.015.011a1.003 1.003 0 0 1-1.276-1.548Z");
}

.h310odbes {
  d: path("M24.752 11.54a.582.582 0 0 1 .375-.581l.223.242c.004.18.055.312.14.484c.087.172.016.445-.23.457c-.246.012-.496-.144-.508-.601Z");
}

.h5ltaluah {
  d: path("M18.371 6.647a.44.44 0 0 1 .13-.274c.02.029.29.144.445.184c.306.078.554.05.64.027c.407.285.133.93-.496.77c-.629-.16-.726-.547-.719-.707Z");
}

.h8usfgb8s {
  d: path("M18.269 2.404c-.066-.22-.283-.3-.383-.312c.038.066 0 .266-.162.36c-.163.094-.335.193-.398.365c-.05.138.055.263.115.31c.102-.05.332-.027.517-.12c.185-.094.393-.328.31-.603Z");
}

.h93axsbui {
  d: path("M6.265 15.869a.296.296 0 0 1 .062-.242c.1.034.235.053.29.058c.047.1.119.303.019.328c-.125.032-.344 0-.371-.144Z");
}

.hakx81bzy {
  d: path("M7.526 6.855c.273.262.519.313.608.306c.083.006.333-.095.303-.337c-.029-.242-.1-.29-.427-.453a1.657 1.657 0 0 1-.507-.389c-.237.217-.317.545.023.873Z");
}

.hbgmt9qwx {
  cx: 16px;
  cy: 4.265px;
  rx: 0.328px;
  ry: 0.262px;
}

.hemc1bbwq {
  d: path("M9.097 5.927a.95.95 0 0 1 .117-.415c.011.044.093.166.333.304c.24.139.567.175.701.176c.128.078.122.265.066.4c-.056.137-.283.35-.65.246c-.365-.103-.579-.498-.567-.711Z");
}

.hhzd_hb6q {
  d: path("M11.345 2.918c.048-.225.257-.322.356-.342c-.032.068.022.265.191.345c.17.08.35.165.427.331c.062.133-.033.267-.089.317c-.106-.041-.333.002-.525-.076s-.419-.294-.36-.575Z");
}

.hijuj2b3f {
  d: path("M9.15 5.365c.003.087-.024.133-.039.144c-.097.114-.109.18-.07.254c.04.075.164.192.41 0c.246-.191.316-.52.227-.629a.288.288 0 0 0-.364-.066a.318.318 0 0 0-.164.297Z");
}

.hlzj_l28s {
  d: path("M18.224 4.427a.735.735 0 0 1 .598-.058c-.219.058-.277.351-.063.422c.215.07.303.143.31.324c.006.181-.14.255-.2.285c-.172-.05-.23.008-.543-.148c-.313-.157-.41-.63-.102-.825Z");
}

.hoxx4qb0c {
  d: path("M17.305 6.613c-.34.164-.59.135-.673.1c-.08-.02-.286-.193-.183-.414c.104-.22.187-.245.548-.298a1.68 1.68 0 0 0 .603-.21c.158.28.131.616-.295.822Z");
}

.hvzqp6bsv {
  d: path("M9.772 6.29a.437.437 0 0 1-.266-.3c.09.035.223 0 .52-.152c.297-.153.547-.2.68-.075c.132.125.124.375-.102.5c-.227.125-.598.13-.832.028Z");
}

.hw4_s7biu {
  d: path("M16.656 3.095a.59.59 0 0 0 .478-.65c-.048-.453-.618-.473-.871-.276c-.126.098-.173.218-.09.319c.081.1.17.08.27.058h.002c.1-.023.236-.07.108.048c-.129.118-.169.184-.084.328a.372.372 0 0 0 .187.173Z");
}

.hxvo6nkrx {
  d: path("M7.126 9.908a.363.363 0 0 1-.13.292a.948.948 0 0 1-.84.174c-.298-.078-.427-.326-.396-.46a.27.27 0 0 1 .285-.217c.15.003.206.127.468.169c.21.033.41-.134.483-.222c.042.024.127.11.13.264Z");
}

.hyifb8vyk {
  d: path("M24.901 5.278c-.1-.199-.325-.267-.426-.277c.018.098-.014.339-.16.457a.93.93 0 0 1-.369.18a.394.394 0 0 0 0 .449c.15-.014.346.026.625-.075c.28-.101.454-.486.33-.734Z");
}

.hzqzbj9rf {
  d: path("M8.74 8.802c-.112.15-.356.203-.464.211c-.426 0-.621-.21-.652-.41a.898.898 0 0 1 .05-.41h.907c.28.07.3.422.16.61Z");
}

.i-hjf1bhe {
  d: path("M12.046 7.013c-.208-.238-.119-.522-.048-.634c.01.098.128.333.506.482c.379.15.663-.035.757-.146c.055.059.137.391-.195.585c-.333.194-.761.01-1.02-.287Z");
}

.i057kv2sc {
  d: path("M6.046 9.044c-.158-.298.016-.583.122-.689c.198.308.72.408.881.376c.13-.026.189.052.202.094c-.007.155.029.312.047.37c-.436.41-1.054.22-1.252-.151Z");
}

.i17j05cba {
  d: path("M8.426 7.087c-.02-.343.168-.51.264-.552c.149.14.466.453.546.576c.1.155.19.448-.12.587c-.312.14-.664-.181-.69-.61Z");
}

.i1sh50bbh {
  d: path("M25.157 12.053a.567.567 0 0 1 .099-.227c.023.053.132.188.374.304c.24.116.45.01.528-.03l.002-.002c.153.102.13.52-.195.655c-.115.048-.145-.04-.418-.177c-.341-.173-.413-.392-.39-.523Z");
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.iam3n-bgk {
  d: path("M19.1 4.958a.62.62 0 0 1 .363-.43c.018.778.515.97.761.969c.004.3-.222.515-.59.39c-.367-.125-.617-.597-.535-.93Z");
}

.ieslakbcn {
  d: path("M19.954 2.489a.735.735 0 0 1 .598-.059c-.219.059-.278.352-.063.422c.215.07.303.143.31.324c.006.181-.14.255-.2.285c-.172-.05-.23.008-.543-.148c-.313-.156-.41-.63-.102-.824Z");
}

.ihoit7b7z {
  d: path("M8.526 4.945c-.017-.146.102-.291.164-.346c.373.133.654.106.868.099c.215-.007.407.144.404.298a.419.419 0 0 1-.127.269c-.174.103-.498.14-.825.055c-.327-.085-.462-.192-.484-.375Z");
}

.ii-90fbqe {
  stop-color: var(--svg-color--c5a182, #C5A182);
  stop-opacity: 0;
}

.ii77fulqy {
  d: path("M7.58 9.619a.285.285 0 0 0 0 .187l.297.192c.124.005.426-.013.645-.125c.273-.141.293-.54.129-.684c-.107-.094-.255-.11-.3-.094a.77.77 0 0 1-.388.422a.763.763 0 0 1-.383.102Z");
}

.ik-2hub9b {
  cx: 9.195px;
  cy: 3.27px;
  rx: 0.322px;
  ry: 0.257px;
}

.ilhy8qqeu {
  d: path("M18.458 3.106a.52.52 0 0 0-.274-.334c-.127.218-.34.278-.589.309c-.248.03-.335.193-.354.285a.371.371 0 0 0 .097.324c.201-.05.594-.019.785-.102c.19-.083.39-.247.335-.482Z");
}

.inejkeqqd {
  d: path("M13.988 2.267c-.047-.225-.257-.322-.356-.342c.032.069-.022.265-.191.345c-.17.08-.35.165-.427.331c-.062.133.034.267.09.318c.105-.042.332.001.525-.077c.192-.078.418-.293.359-.575Z");
}

.iokohibue {
  cx: 13.181px;
  cy: 4.666px;
  rx: 0.322px;
  ry: 0.257px;
}

.ip3y-pbpf {
  d: path("M25.692 6.876a.59.59 0 0 1-.425-.685c.085-.449.655-.423.89-.206c.118.107.155.232.066.325c-.09.094-.177.067-.276.036c-.1-.031-.231-.088-.112.04c.118.127.153.196.057.333a.372.372 0 0 1-.2.157Z");
}

.ircbonbtw {
  d: path("M14.009 5.6a.341.341 0 0 0-.026-.42c-.215.409-.646.577-.835.61c.32.211.712.053.86-.19Z");
}

.ivpy-diyv {
  d: path("M15.36 5.319a.531.531 0 0 1 .2-.392c.173.189.4.202.653.179c.255-.024.376.12.415.208a.379.379 0 0 1-.026.343c-.232.044-.596.11-.804.07c-.208-.042-.442-.163-.439-.408Z");
}

.ivwpoe7fc {
  d: path("M5.468 11.048c-.029-.204.133-.39.218-.458c.245.336.468.335.657.357c.19.023.386.222.256.507c-.13.284-.503.22-.706.118c-.202-.102-.389-.27-.425-.524Z");
}

.iw_nvbbot {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m22.977 13.334l-.002-.002l-.003-.003l-.009-.007l-.022-.018a3.717 3.717 0 0 0-.291-.202a4.853 4.853 0 0 0-.79-.396a5.326 5.326 0 0 0-2.806-.298a1.004 1.004 0 1 0 .313 1.983a3.32 3.32 0 0 1 1.755.181a2.85 2.85 0 0 1 .565.3l.015.011a1.003 1.003 0 0 0 1.275-1.55Z");
}

.iw5sgrd8w {
  d: path("M15.395 2.606c.047-.225.257-.322.355-.342c-.032.068.022.265.192.345c.17.08.35.165.427.331c.061.133-.034.267-.09.318c-.105-.042-.333.001-.525-.077s-.419-.293-.36-.575Z");
}

.ixgckfzug {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.96 16.624c.12.16-.13.355-.414.567c-.284.212-.495.362-.614.202c-.12-.16.014-.462.298-.674c.284-.212.61-.255.73-.095Z");
}

.iy-lxtbwg {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.483 15.758a2.626 2.626 0 0 0-2.547 1.99a.515.515 0 0 0 .503.641h4.195c.267 0 .48-.244.427-.51a2.634 2.634 0 0 0-2.578-2.12Z");
}

.iy07wrbce {
  cx: 11.974px;
  cy: 2.692px;
  rx: 0.322px;
  ry: 0.257px;
}

.j_e7ycxwk {
  d: path("M7.017 5.086a.323.323 0 0 1 .067-.201a.576.576 0 0 1 .438.15c.096.111-.01.295-.196.299c-.185.003-.311-.117-.309-.248Z");
}

.j-x2blwpt {
  d: path("M21.83 3.814c-.099-.199-.325-.267-.426-.277c.018.098-.014.339-.16.457a.93.93 0 0 1-.368.18a.394.394 0 0 0-.002.449c.152-.014.347.026.626-.075c.28-.101.454-.486.33-.734Z");
}

.j00tezb1v {
  d: path("M18.46 5.5c.155-.274.011-.535-.08-.63c.009.098-.059.35-.4.573c-.34.222-.656.098-.771.008c-.041.069-.056.41.308.534c.365.124.748-.143.943-.485Z");
}

.j1dapkb_s {
  d: path("M9.213 8.97c-.269-.203-.232-.535-.18-.675c.309.195.825.066.958-.032c.106-.078.192-.032.222 0c.06.144.158.271.2.317c-.223.554-.864.644-1.2.39Z");
}

.j2g_c5b-q {
  cx: 11.367px;
  cy: 16.986px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.732px;
  ry: 0.371px;
}

.j34jzlb1p {
  d: path("M10.803 5.537a.57.57 0 0 1 .27-.504c.077.277.449.34.59.347c.14.008.34.012.335.333c-.003.32-.441.437-.675.394c-.235-.043-.508-.223-.52-.57Z");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j3j_8besh {
  d: path("M26.115 13.783a.733.733 0 0 1-.152-.277l-.406-.114c-.121.211-.04.602.098.797c.136.195.492.149.578-.02c.085-.167-.008-.269-.118-.386Z");
}

.j9v4grv9o {
  d: path("M18.47 5.567a.385.385 0 0 1 .31-.258c-.042.49.326.824.515.93c-.711.039-.899-.442-.824-.672Z");
}

.jd9pj3b3q {
  d: path("M5.502 9.81a.475.475 0 0 1 .098-.437c.067.164.23.25.383.117a.429.429 0 0 1 .476-.05a.221.221 0 0 1 .102.183c-.063.18-.27.386-.453.43c-.184.042-.531.011-.606-.243Z");
}

.jhuu-edco {
  d: path("M18.672 4.33c.14-.172.376-.188.477-.175c-.04.09-.061.333.054.48a.929.929 0 0 0 .32.258a.392.392 0 0 1-.097.437c-.144-.047-.344-.05-.594-.21c-.25-.16-.336-.575-.16-.79Z");
}

.jkdbopbiq {
  d: path("M6.512 6.144c-.16-.255-.011-.543.084-.655c.032.121.204.33.501.392a.342.342 0 0 0 .4-.208c.259.094.236.31.192.406c-.111.087-.197.348-.445.388c-.248.04-.532-.004-.732-.323Z");
}

.jn5bz-oly {
  d: path("M24.817 6.35c.133-.177.367-.204.468-.195c-.035.092-.046.336.075.477a.93.93 0 0 0 .331.244a.394.394 0 0 1-.079.442c-.146-.041-.345-.036-.602-.186s-.36-.56-.194-.781Z");
}

.jnm8_mb_z {
  d: path("M18.301 5.237c.044-.232.255-.308.356-.317c.234.285.449.293.687.371c.238.078.274.23.234.407a.423.423 0 0 1-.164.253a2.654 2.654 0 0 1-.523-.066c-.332-.086-.645-.36-.59-.648Z");
}

.jpr_kccyq {
  d: path("M11.689 4.985c.318-.278.206-.644.11-.792c-.348.437-.773.226-.952.203c-.18-.022-.35.018-.43.153c-.08.136-.053.326.101.477c.155.15.773.306 1.17-.041Z");
}

.jpwroko7g {
  d: path("M15.675 3.49a.59.59 0 0 1-.378-.712c.114-.442.681-.378.902-.146c.11.116.14.242.043.33c-.095.087-.18.054-.277.016c-.097-.037-.225-.103-.115.033c.11.135.14.206.035.336a.372.372 0 0 1-.21.144Z");
}

.jqc0yrb_o {
  d: path("M12.596 5.974c.016-.244.249-.38.363-.418c0 .266.13.211.473.39c.344.18.484.731.39.84c-.093.11-.617.145-.882-.058a.815.815 0 0 1-.344-.754Z");
}

.jr4v0ukgt {
  cx: 24.944px;
  cy: 18.448px;
  r: 3.139px;
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.juyrjmb_u {
  d: path("M15.791 3.729a.57.57 0 0 1 .366-.44c.02.288.371.424.508.46c.136.036.33.08.262.393c-.069.313-.52.34-.742.25c-.22-.09-.452-.32-.394-.663Z");
}

.jxh8klb7x {
  d: path("M27.354 8.107c.029-.234-.15-.37-.242-.41c-.31.2-.517.141-.768.143c-.25.001-.33.136-.347.315a.422.422 0 0 0 .078.292c.128.037.319.082.519.097c.342.02.723-.145.76-.437Z");
}

.jynvt1blk {
  d: path("M17.653 7.052c.164-.294-.004-.583-.108-.69c-.204.303-.728.393-.889.358c-.128-.029-.19.048-.203.09a1.23 1.23 0 0 1-.055.37c.428.417 1.05.24 1.255-.128Z");
}

.jzqwpshkk {
  d: path("M18.428 3.845c.005-.148-.125-.283-.191-.332c-.361.164-.637.121-.852.132c-.214.011-.4.216-.383.37a.419.419 0 0 0 .148.256c.182.09.509.1.827-.013c.32-.112.445-.23.451-.413Z");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kbdgkn7fg {
  d: path("M6.914 10.365c-.072-.13.01-.284.062-.34c.323-.394.826-.424.992-.234c.164.187.082.492-.117.492a.781.781 0 0 0-.473.16c-.101.078-.37.093-.464-.078Z");
}

.kihletipm {
  d: path("M15.46 5.707c-.177-.26-.055-.531.028-.634c0 .099.088.345.446.538a.674.674 0 0 0 .77-.056c.046.065.089.405-.264.558c-.353.153-.757-.08-.98-.406Z");
}

.kla98c7et {
  d: path("M23.67 9.162c.144-.313.388-.373.492-.364c.066.194.199.62.211.766c.016.184-.043.485-.383.461c-.34-.023-.5-.473-.32-.863Z");
}

.kmw42bjwn {
  d: path("M15.213 2.44c-.118-.188-.35-.234-.45-.233c.027.095.018.338-.114.47a.93.93 0 0 1-.35.216a.394.394 0 0 0 .043.446c.15-.028.348-.008.615-.136c.268-.128.404-.529.256-.763Z");
}

.knh2dl9nl {
  d: path("M14.536 4.71a.59.59 0 0 0 .395-.703c-.103-.445-.672-.395-.898-.168c-.113.112-.145.238-.051.328c.093.09.18.059.276.023h.001c.098-.035.227-.097.113.035c-.113.133-.144.203-.043.336a.372.372 0 0 0 .207.149Z");
}

.knhvp8bxb {
  d: path("M5.33 7.76c.136.366.455.361.603.332c.27-.332-.035-.528-.164-.707a.311.311 0 0 1-.027-.34c-.402.039-.527.402-.411.715Z");
}

.knmcy5b0k {
  d: path("M21.96 5.029a.6.6 0 0 1 .527-.07c-.18.28-.102.43 0 .582c.101.152.168.273.117.437c-.07.229-.375.2-.613-.074c-.239-.273-.274-.7-.032-.875Z");
}

.ko2v0wbvh {
  d: path("M13.637 6.02c-.178-.26-.056-.532.027-.636c0 .1.088.346.446.539a.674.674 0 0 0 .77-.056c.046.065.09.405-.264.558c-.353.153-.757-.08-.979-.406Z");
}

.kqg2r0bml {
  d: path("M7.15 7.255c-.064-.331.186-.553.319-.622c.098.351.567.601.731.618c.132.013.165.105.166.149a1.213 1.213 0 0 0-.064.368c-.537.263-1.073-.1-1.153-.513Z");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kz5ewicny {
  d: path("M24.85 11.031c-.053-.397.14-.559.242-.59c.264.124.809.45.871.762c.078.39-.148.562-.418.566c-.27.004-.629-.242-.695-.738Z");
}

.l0nxg5bwa {
  d: path("M21.764 5.613c.094-.206-.042-.387-.122-.452c-.291.17-.58.12-.778.092c-.198-.029-.332-.019-.434.13c-.102.15-.134.539.398.559c.532.02.817-.072.936-.33Z");
}

.l3e87gbvo {
  d: path("M10.103 5.084c-.124-.162-.096-.382-.067-.472c.542.228.976.13 1.125.051c.079.048.23.188.208.375c-.028.233-.23.449-.555.425a.95.95 0 0 1-.71-.379Z");
}

.l5797lb4n {
  d: path("M22.96 7.234a.664.664 0 0 0 .108-.436c-.447.308-.743.226-.983.154a.517.517 0 0 1-.318-.259c-.366.444-.021.818.34.892c.361.073.712-.15.854-.351Z");
}

.l6_3ttz0u {
  d: path("M25.703 10.04a.453.453 0 0 1 .21-.21c.119.36.383.479.596.616c.214.137.324.378.15.576c-.174.198-.618-.017-.821-.321c-.203-.305-.193-.52-.135-.661Z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9hthccmu {
  fill-rule: evenodd;
  d: path("M13.14 2.276a.228.228 0 0 0 .17.058a.796.796 0 0 0-.226.162l-.097-.046a.355.355 0 0 1-.2-.297c0-.02-.02-.042-.04-.035a.46.46 0 0 0-.307.329a.447.447 0 0 0 .093.374a.521.521 0 0 0-.223.341a.352.352 0 0 0-.004.064a.649.649 0 0 0-.283-.24a.228.228 0 0 0 .17-.06c.104-.096.09-.28-.032-.41c-.121-.13-.304-.156-.407-.059a.219.219 0 0 0-.065.122c-.103.025-.298.123-.344.339a.677.677 0 0 0-.368-.178a.451.451 0 0 0-.08.002a.214.214 0 0 0-.088.028a.344.344 0 0 0-.098-.284c-.121-.13-.304-.156-.408-.059a.219.219 0 0 0-.065.121c-.102.026-.297.124-.343.34a.428.428 0 0 0-.002.17l-.018.001a.61.61 0 0 0-.395.235a.37.37 0 0 0-.098-.2c-.121-.13-.304-.156-.408-.059a.219.219 0 0 0-.065.122c-.103.025-.298.123-.343.34a.447.447 0 0 0 .093.373a.554.554 0 0 0-.157.163a.56.56 0 0 0-.28-.16l-.002.001c-.088-.035-.293-.075-.45.04a.497.497 0 0 0-.206.383c-.126.079-.352.303-.28.593l.004.014a.496.496 0 0 0-.204-.019l-.001.001c-.095-.006-.302.02-.415.178a.497.497 0 0 0-.076.429a.69.69 0 0 0-.092.15a.585.585 0 0 0-.423-.146c-.095-.008-.303.015-.42.17a.497.497 0 0 0-.083.427c-.097.113-.248.394-.094.65c.086.143.19.232.3.285a.323.323 0 0 0-.008.282a.373.373 0 0 0 .136.17a.222.222 0 0 0 .015.207a.568.568 0 0 0 .06.085c-.108.218-.1.465.122.657c-.096.136-.188.37-.06.614c.198.372.817.56 1.253.152a1.213 1.213 0 0 1-.047-.371c-.013-.042-.073-.12-.202-.094c-.082.016-.256-.001-.434-.063a.66.66 0 0 0 .344-.003a.334.334 0 0 0 .17-.138a.82.82 0 0 0 1.134-.025a1.213 1.213 0 0 1-.054-.37c-.014-.04-.07-.113-.189-.093l.009-.004a.333.333 0 0 0 .165-.139c.18.142.417.18.576.044a.312.312 0 0 0 .104-.22a.37.37 0 0 0 .241-.022c.256-.114.24-.332.171-.492a.395.395 0 0 0 .238-.06c.048.01.096.016.144.018c.395.023.725-.387.567-.656a.548.548 0 0 0 .017-.019c.106.027.22.028.332-.007a.51.51 0 0 0 .028.031c-.17.295.193.74.624.712c.022 0 .043-.003.065-.006c.242-.03.467-.138.617-.3a.35.35 0 0 0 .068.334a.642.642 0 0 0 .494.227a.586.586 0 0 0 .333-.102a.584.584 0 0 0 .253-.078a.483.483 0 0 0 .214-.234c.18.146.421.186.583.049a.313.313 0 0 0 .103-.22a.37.37 0 0 0 .241-.021a.471.471 0 0 0 .082-.047a.43.43 0 0 0 .114.22c-.1.307 0 .51.17.62a.322.322 0 0 0 .104.289c.219.191.773.258 1.039-.172c.166-.268.095-.64.012-.78a.677.677 0 0 0-.075-.333l-.007.01a.53.53 0 0 0 .043-.197c.121.257.422.43.744.448h.014c-.01.11-.035.205-.05.248c.429.417 1.051.24 1.256-.128c.145-.261.029-.518-.072-.648a.481.481 0 0 0 .1-.388c.033 0 .067 0 .1-.005c.09.038.18.05.268.045a.768.768 0 0 0 .088.452c.255.436.811.383 1.035.197a.321.321 0 0 0 .11-.286a.462.462 0 0 0 .14-.128a.467.467 0 0 0 .017.002c.334.048.462-.132.501-.382c.177-.044.28-.2.284-.396a.353.353 0 0 0 .169-.058c-.04.109-.039.261.075.366a.422.422 0 0 1-.027-.013a.418.418 0 0 0-.212.615c-.165.277-.112.498.03.643a.322.322 0 0 0 .037.304c.172.235.698.422 1.052.061c.22-.225.234-.603.183-.757l.004-.015l.006.002a.58.58 0 0 0 .224.03v.002c-.204.249-.185.476-.065.64a.322.322 0 0 0-.01.306c.135.257.628.52 1.031.217c.252-.19.322-.562.294-.722a.677.677 0 0 0 .052-.338l-.01.007a.515.515 0 0 0 .118-.187a.44.44 0 0 0-.02-.302a.141.141 0 0 1-.045.01a.483.483 0 0 0 .293-.206c.11-.17.037-.346-.03-.436c.183-.056.331-.167.374-.327a.348.348 0 0 0 .03.091a.372.372 0 0 0 .169.19a.396.396 0 0 0-.004.445c-.175.046-.226.173-.227.328c0 .144.07.25.104.284c.118.023.287.048.466.05c-.123.006-.237-.011-.331-.025l-.02-.003c-.197-.028-.332-.019-.434.13c-.068.1-.105.308.039.44a.416.416 0 0 1-.027-.012a.418.418 0 0 0-.212.614c-.165.277-.113.498.03.643a.322.322 0 0 0 .037.304c.171.235.698.422 1.052.061c.168-.172.216-.433.206-.616a.52.52 0 0 0 .145.142a.14.14 0 0 1-.039-.024a.44.44 0 0 0-.117.279c0 .053.012.13.052.216l-.008-.01a.677.677 0 0 0-.06.336c-.077.143-.131.518.045.778c.12.177.288.263.457.288a.524.524 0 0 0-.037.167a.352.352 0 0 0-.143.133a.497.497 0 0 0-.406.238c-.2.297.023 1.027.531 1.129c.054.01.102.01.142-.002a.526.526 0 0 0-.03.102c-.023.13.049.35.39.523c.098.05.165.092.216.125c.09.058.128.083.201.053c.287-.12.34-.458.242-.607l.037-.013c.346-.132.369-.373.34-.454a.611.611 0 0 0-.115-.172c.102-.054.224-.266.076-.408a.41.41 0 0 1-.033-.004a.227.227 0 0 0 .148-.074c.174-.198.064-.439-.15-.576a3.324 3.324 0 0 0-.066-.041a.796.796 0 0 0 .246.07c.257.024.405-.178.366-.356c-.03-.14-.18-.233-.403-.287a.797.797 0 0 0 .123-.042c.277-.123.316-.414.18-.554a.6.6 0 0 0-.403-.148a.156.156 0 0 0 .01-.069a.285.285 0 0 0-.187-.243a.225.225 0 0 0-.024-.166a.248.248 0 0 0 .213-.448a.442.442 0 0 0-.14-.154c-.247-.18-.503-.15-.656-.02a.647.647 0 0 0-.259-.048h-.02a1.777 1.777 0 0 1-.331-.035c.177.03.349.035.469.034a.422.422 0 0 0 .153-.26c.027-.154 0-.288-.164-.365a.396.396 0 0 0 .075-.438a.372.372 0 0 0 .2-.157c.096-.137.062-.206-.057-.333c-.103-.112-.017-.083.072-.053l.04.013c.099.03.186.058.276-.036c.09-.093.053-.217-.065-.325c-.229-.21-.774-.241-.882.17a.616.616 0 0 0-.214.028a.408.408 0 0 0-.273-.326c.14-.163.2-.405.113-.58c-.096-.192-.312-.262-.417-.275c-.03-.385-.481-.475-.76-.363a.447.447 0 0 0 .013-.289c-.067-.204-.27-.306-.371-.334c.03-.423-.495-.57-.78-.446a.37.37 0 0 0-.145.105a.546.546 0 0 0-.21-.213a.447.447 0 0 0 .062-.38a.46.46 0 0 0-.334-.303c-.02-.005-.038.018-.036.039a.355.355 0 0 1-.175.312c-.137.079-.28.162-.36.288c-.086-.233-.36-.314-.592-.28c-.017-.15-.105-.218-.295-.282h.006a.216.216 0 0 0 .04-.428a.739.739 0 0 0-.593.06a.406.406 0 0 0-.086.073c-.239-.189-.719-.222-.844.154c-.105-.014-.331.002-.471.165a.429.429 0 0 0-.095.227a.523.523 0 0 0-.251-.323a.447.447 0 0 0 .061-.38a.46.46 0 0 0-.334-.302c-.02-.006-.037.017-.036.038a.355.355 0 0 1-.175.312a2.15 2.15 0 0 0-.201.127a.583.583 0 0 0-.393-.17c-.075-.418-.62-.432-.866-.24a.519.519 0 0 0-.047.041l-.006-.006c-.12-.13-.303-.156-.407-.059a.219.219 0 0 0-.065.122a.466.466 0 0 0-.338.318a.423.423 0 0 0-.093.157a.465.465 0 0 0-.038-.003a.452.452 0 0 0-.056-.3c-.114-.181-.336-.23-.441-.232c-.074-.418-.62-.432-.866-.24a.47.47 0 0 0-.066.061a.517.517 0 0 0-.196-.1a.219.219 0 0 0-.065-.121c-.104-.097-.286-.071-.408.059c-.12.13-.135.313-.031.41Zm-.294 4.113a.662.662 0 0 1-.201-.007a1.067 1.067 0 0 0 .185.008l.016-.001Zm.652-.264a.343.343 0 0 0-.211-.022a.48.48 0 0 0 .034-.105a.578.578 0 0 0 .187-.055a.335.335 0 0 0-.01.182ZM6.381 5.94a.248.248 0 0 0 .06-.025a.466.466 0 0 0 .01.085a.413.413 0 0 0-.07-.06Zm.147.377c.199.107.173.297.13.385a.24.24 0 0 0-.02.017a.317.317 0 0 1 .162-.056a.312.312 0 0 1 .017-.24a.676.676 0 0 1-.27-.226a.238.238 0 0 1-.02.12Zm.385.984a.284.284 0 0 1 .067.033a.69.69 0 0 1 .081-.221l.006.003a.277.277 0 0 1-.017-.037a.568.568 0 0 1-.137.222Zm-.027.697a.367.367 0 0 0 .08-.053a.61.61 0 0 0-.019.08a.792.792 0 0 0-.14-.043c.032-.002.058.001.08.016Zm.51-2.675l.028.019a.306.306 0 0 1 .02-.038a.25.25 0 0 1-.047.019Zm1.036 1.604a.708.708 0 0 0-.004.034l-.005-.003a.262.262 0 0 0 .01-.031Zm.067-.202a.59.59 0 0 0-.061.17a.306.306 0 0 0 0-.07c-.024-.19-.072-.261-.25-.361c.032.007.056.018.072.038c.07-.01.2-.06.28-.185c0 .036.005.072.014.11a.335.335 0 0 0-.055.298Zm.814-3.167a.258.258 0 0 1-.069.005l.032.017a.567.567 0 0 1 .037-.022Zm1.43-.662c0 .014 0 .03.002.046c.011.12.129.25.186.3a.364.364 0 0 0-.047.023a.218.218 0 0 0-.015-.043c-.057-.124-.171-.202-.296-.267a.229.229 0 0 0 .17-.059Zm-.14 1.19l.055-.002l.001.012a2 2 0 0 1-.2-.008l.144-.003Zm14.06 3.59a.559.559 0 0 1-.07.13l.01-.008a.417.417 0 0 1 .01.046a.463.463 0 0 1 .116-.114a.816.816 0 0 1-.066-.054Zm-1.924-3.11a.396.396 0 0 0-.07.438c-.18.02-.25.137-.273.29l-.001.006a.61.61 0 0 0-.069-.136a.398.398 0 0 1-.023.054a.58.58 0 0 0-.008-.406a1.884 1.884 0 0 1-.252.11c.288-.108.403-.223.41-.4c.004-.14-.113-.268-.181-.323a.463.463 0 0 0 .21-.26c.051.038.116.04.187.041h.042c.094.002.185.002.051.074c-.154.083-.208.137-.162.298a.372.372 0 0 0 .14.213Zm-.283 1.025c.113.04.277.09.455.12a1.774 1.774 0 0 1-.326-.075l-.018-.006a1.17 1.17 0 0 0-.12-.03a.568.568 0 0 0-.016-.021a.488.488 0 0 0 .002-.027a.25.25 0 0 0 .023.04Zm1.437-.461a.427.427 0 0 0-.133.133a.365.365 0 0 0-.046-.185c.024 0 .05-.004.076-.007l.042-.006c.093-.013.183-.026.061.065Zm-7.609-2.57a.21.21 0 0 1-.077.081c.06.065.093.134.093.196a.42.42 0 0 1 .068.101a.62.62 0 0 1 .082-.05c-.058-.121-.015-.186.103-.294c.112-.102.024-.08-.068-.058a2.301 2.301 0 0 1-.04.01c-.057.012-.11.025-.161.015Zm.634 1.615v-.003c.046 0 .093-.002.14-.005l.002.002a1.43 1.43 0 0 1-.142.006Zm-1.447.37v-.003l.04.003l.001.007a1.098 1.098 0 0 0-.041-.007Zm.207-.16c.04.012.079.024.117.034a1.627 1.627 0 0 1-.116-.037l-.001.002Zm-3.339-1.03a.494.494 0 0 0 .215.204a.57.57 0 0 0-.058.064a.372.372 0 0 0-.167-.212a.256.256 0 0 0 .01-.056Zm1.91-.37l.013.007l.002-.007h-.015Zm-.065-.582l.012-.01c.112-.103.024-.082-.068-.06a2.525 2.525 0 0 1-.04.01a.829.829 0 0 1-.09.017a.422.422 0 0 1-.011.09a.238.238 0 0 1 .197-.047Zm5.76.833a.552.552 0 0 1-.157-.251a.683.683 0 0 1-.106-.034a2.33 2.33 0 0 1-.04-.016c-.087-.036-.17-.07-.075.048c.11.135.14.206.035.337a.372.372 0 0 1-.21.143a.396.396 0 0 1-.104.432c.158.088.176.223.139.374a.423.423 0 0 1-.17.25a2.717 2.717 0 0 1-.465-.065c.119.035.233.046.328.056l.02.002c.096.01.176.025.24.057a.448.448 0 0 1 .078-.039c.044-.19.21-.305.289-.348c-.004-.166.057-.293.146-.353a.378.378 0 0 1-.133-.293a.398.398 0 0 1 .185-.3Zm-1.486.022a.462.462 0 0 1-.21.263l.044.04a.439.439 0 0 1 .23-.091a.66.66 0 0 1-.064-.212Zm-.178.9c.028.033.06.064.093.092a.46.46 0 0 0-.064.047a.622.622 0 0 0-.029-.138Zm-.024-.03l.007.01c-.055.029-.11.053-.163.075l-.001-.002a.972.972 0 0 0 .157-.082Zm2.62.046a.237.237 0 0 1-.07-.047a.607.607 0 0 1-.246.092a.82.82 0 0 1-.048-.013l.033.013c.102.04.185.072.261.165a.439.439 0 0 1 .07-.21Zm-.013-.582c.014.002.021.007.017.018a.406.406 0 0 0-.017-.018Zm-.44-.16v.003a.841.841 0 0 1-.304-.092a.89.89 0 0 0 .304.09Zm.573 1.836a2.87 2.87 0 0 1-.248-.037a.422.422 0 0 1-.104-.281a.371.371 0 0 1-.087.01c.02.138 0 .248-.03.327c.087-.055.196-.054.337-.034l.019.003l.113.015v-.003Zm.718.43l-.002.002a.73.73 0 0 0 .002-.003Zm-1.546-1.693a1.504 1.504 0 0 1-.046-.04l.012.004c.009.01.02.023.034.036ZM8.512 5.832a.603.603 0 0 1-.022.012c.056.04.106.106.117.2l.004-.009a.759.759 0 0 1-.027-.138a.775.775 0 0 1-.072-.065Zm17.211 6.333Z");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lf10uubwu {
  fill: var(--svg-color--000, #000);
  d: path("M12.833 17.947a.957.957 0 0 0-.96-.961a.957.957 0 0 0-.961.96c0 .161.038.313.106.443h1.7a.953.953 0 0 0 .115-.442Z");
}

.lfkmfybci {
  d: path("M12.897 5.841a.52.52 0 0 1 .07-.425c.218.125.434.07.664-.028c.23-.097.387 0 .45.07c.097.11.098.258.078.329c-.2.058-.524.281-.73.304c-.208.024-.462-.02-.532-.25Z");
}

.lgtzzmb0f {
  d: path("M22.739 4.565a.59.59 0 0 0 .623-.512c.065-.452-.483-.611-.776-.483c-.146.064-.221.17-.166.288c.054.117.145.12.249.122c.104.003.247-.008.093.074c-.154.083-.208.137-.162.298a.372.372 0 0 0 .139.213Z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lrlki_zex {
  stop-color: var(--svg-color--e1ae8c, #E1AE8C);
  stop-opacity: 0;
}

.lrujm9bib {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.402 23.672a.337.337 0 0 0-.403.069a.308.308 0 0 0-.034.396a3.61 3.61 0 0 0 3.018 1.612a3.61 3.61 0 0 0 3.018-1.613a.311.311 0 0 0-.034-.399a.338.338 0 0 0-.402-.066a5.57 5.57 0 0 1-2.582.612a5.6 5.6 0 0 1-2.581-.611Z");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.lubncxb5i {
  d: path("M25.049 10.662c.038-.225.234-.354.328-.39c.066.25.313.507.477.636c.164.129.144.45-.07.558a.408.408 0 0 1-.387 0a.694.694 0 0 1-.047-.23c-.116-.098-.338-.35-.301-.574Z");
}

.m1yyx4b6e {
  d: path("M25.088 10.668c-.087-.31.065-.51.152-.57c.207.174.727.34.962.402c.304.203.132.746-.227.758c-.36.011-.777-.204-.887-.59Z");
}

.m31b3_vwm {
  d: path("M5.561 9.146c-.147-.144-.131-.39-.105-.496c.398.117.574-.02.738-.117c.164-.098.442-.059.512.246s-.266.48-.488.523c-.223.043-.473.024-.657-.156Z");
}

.m8g_7_muo {
  d: path("M26.05 6.697a.6.6 0 0 1 .503.258c-.285.054-.375.316-.27.48c.106.164.07.285 0 .39c-.07.106-.32.208-.574-.155c-.34-.528-.004-.97.34-.973Z");
}

.m9q5wwbfu {
  d: path("M13.406 17.75c0-.543-.441-.904-.56-1.013l-.542.524l.333.68l.769-.191Z");
}

.mawzxkvil {
  d: path("M5.909 12.088a.377.377 0 0 1 .103-.336c.056.02.217.067.483.054c.332-.015.457.172.515.356c.059.183-.132.308-.277.238c-.144-.07-.2-.035-.41-.055c-.211-.02-.371-.05-.414-.258Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbt8yvvir {
  d: path("M12.31 3.162a.52.52 0 0 1 .245-.355c.145.206.363.249.613.259c.25.01.35.165.376.255a.371.371 0 0 1-.07.33c-.205-.032-.593.031-.79-.036c-.197-.067-.409-.214-.374-.453Z");
}

.mg4ogkbne {
  d: path("M15.395 4.578c.018-.234.216-.36.314-.394c-.024.073.057.265.24.323c.182.058.375.12.475.278c.08.126.002.274-.047.333c-.113-.028-.337.046-.542-.007c-.204-.053-.462-.24-.44-.533Z");
}

.mh7dsob_w {
  d: path("M25.256 8.82c.103-.156.304-.193.39-.191c.067.191.217.29.377.345c.16.055.35.133.35.428c0 .239-.194.41-.28.453a1.21 1.21 0 0 1-.337-.117a.49.49 0 0 1-.226-.309c-.29-.144-.403-.414-.274-.609Z");
}

.mhtidt27u {
  d: path("M13.162 4.084a.43.43 0 0 1 .23-.424c.018.274.194.446.39.35a.293.293 0 0 1 .412.148c.049.125.036.401-.321.486c-.358.084-.69-.248-.71-.56Z");
}

.mj47_jb0h {
  d: path("M10.035 5.558c-.147-.222-.062-.487-.001-.593c.04.096.204.319.54.45a.648.648 0 0 0 .692-.123c.036.032.099.135.072.288c-.051.291-.28.417-.566.412c-.287-.006-.552-.157-.737-.434Z");
}

.mmjjjimgi {
  d: path("M18.179 4.641c-.042-.223.135-.365.228-.408c.24.236.533.259.732.279c.199.02.327.063.389.232c.062.17-.002.555-.523.445c-.52-.11-.774-.27-.826-.548Z");
}

.mp71g_bih {
  d: path("M25.971 11.755c.281.047.354.301.356.422c-.09-.066-.278-.082-.356.067c-.078.148-.05.386-.277.422c-.227.035-.445-.348-.367-.57c.078-.223.292-.4.644-.34Z");
}

.mpfdrhb6t {
  d: path("M8.768 7.802c-.1-.072-.107-.165-.098-.203c.524-.12.633-.394.676-.48c.043-.086.309-.172.457.086a.422.422 0 0 1-.031.472c-.094-.015-.188.012-.469.09c-.225.063-.45.05-.535.035Z");
}

.mqucaq90i {
  d: path("M13.779 5.115c-.124-.163-.096-.383-.067-.472c.542.228.976.129 1.125.05c.078.048.23.189.208.375c-.028.233-.23.45-.555.425a.95.95 0 0 1-.711-.378Z");
}

.mr3x8bcoq {
  d: path("M7.064 10.398c.013-.122-.052-.19-.086-.208c-.44.308-.717.206-.81.18c-.092-.025-.333.115-.241.398c.074.226.279.29.372.293c.051-.08.134-.131.38-.288a1.37 1.37 0 0 0 .385-.375Z");
}

.n3-xgacnn {
  d: path("M22.482 3.784a.52.52 0 0 0-.274-.334c-.126.218-.34.278-.588.309c-.249.03-.335.193-.354.285a.371.371 0 0 0 .096.324c.202-.05.594-.019.785-.102c.191-.083.39-.247.335-.482Z");
}

.n3xs1gb_f {
  d: path("M18.15 4.822c.16-.255.01-.543-.084-.655c-.032.121-.205.33-.502.393a.342.342 0 0 1-.4-.208c-.258.093-.236.309-.192.405c.111.087.197.349.445.388c.248.04.532-.004.733-.323Z");
}

.n4lj9hd-i {
  d: path("M18.03 5.474a.4.4 0 0 1 .207-.312c.183.191.37.199.593.23c.223.031.465.2.403.461c-.05.21-.29.29-.403.305a.861.861 0 0 1-.425-.25c-.184-.055-.387-.223-.375-.434Z");
}

.n517djb-j {
  d: path("M6.228 12.277a.764.764 0 0 1-.365-.153c-.189.13-.09.402.004.482c.095.08.346.25.588.293c.302.055.56-.249.518-.463c-.027-.14-.135-.244-.181-.258c-.13.087-.319.14-.564.099Z");
}

.n685z9b8y {
  d: path("M12.104 6.503a.839.839 0 0 0-.252-.65c-.118.45-.347.726-.68.801c-.267.06-.295-.16-.36-.233l-.19.075c-.194.295.176.758.615.73c.44-.029.84-.32.867-.723Z");
}

.n83aecb-e {
  d: path("M25.451 9.912a.596.596 0 0 0-.07.363c.04.178.194.371.266.445c.266-.23.266-.5.164-.668c-.102-.168-.258-.312-.36-.14Z");
}

.n849-9bwe {
  d: path("M23.176 6.618a.44.44 0 0 0-.021-.302c-.03.02-.323.029-.482.01a1.405 1.405 0 0 1-.606-.208c-.483.118-.462.818.182.897c.644.08.876-.245.927-.397Z");
}

.na4-79jps {
  d: path("M6.612 9.005c-.147-.143-.132-.39-.106-.496c.398.118.575-.02.739-.117c.164-.097.441-.058.511.246c.07.305-.265.48-.488.524c-.223.043-.473.023-.656-.157Z");
}

.namp4mb9x {
  d: path("M14.15 5.727a.816.816 0 0 1-.476-.694c.1.048.278.082.585-.015c.306-.097.506.053.557.265a.45.45 0 0 1-.666.444Z");
}

.ne_ihi2nh {
  d: path("M5.968 14.986c-.013-.138.117-.245.183-.281c.125-.086.192-.02.278.086c.086.105.14.3-.032.34c-.172.038-.414.027-.43-.145Z");
}

.nfbwzfh6y {
  d: path("M13.19 6.136a.347.347 0 0 1 .417.066c.351.286.466.734.256.913c-.21.179-.554.056-.726-.206c-.17-.263-.2-.65.054-.773Z");
}

.nkfumcb8m {
  d: path("M6.82 9.491a.45.45 0 0 0-.112.455c.268.152.476-.004.557-.193c.081-.188.077-.364-.007-.433c-.084-.07-.23-.054-.437.171Z");
}

.nkhktmb-q {
  d: path("M25.268 15.19c.006-.292.177-.419.262-.446c.313-.145.496-.046.527.047c.031.093-.016.16-.137.25c-.12.09-.082.054-.043.226c.04.172-.058.313-.245.332c-.188.02-.372-.047-.364-.41Z");
}

.nkqo8zsap {
  d: path("M16.74 7.505a.385.385 0 0 1 .31-.257c-.041.49.326.824.515.93c-.711.038-.899-.442-.824-.673Z");
}

.nlyb9eb_c {
  d: path("M11.486 5.588c-.148-.222-.063-.487-.002-.592c.04.095.204.318.54.448a.648.648 0 0 0 .693-.122c.035.032.098.135.07.288c-.05.292-.278.417-.565.412c-.286-.006-.552-.157-.736-.434Z");
}

.nm0d54e1y {
  d: path("M25.643 8.625c-.029-.091-.064-.32.024-.504c.109-.23.44-.344.757-.113c.317.23.117.504-.023.515a.252.252 0 0 1-.144-.036c.067.068.13.157.124.243c-.012.168-.125.313-.187.328a.64.64 0 0 0-.235-.105a.444.444 0 0 1-.316-.328Z");
}

.nmgej89kf {
  d: path("M24.615 8.678a.44.44 0 0 1 .117-.279c.022.028.296.132.453.165a1.4 1.4 0 0 0 .64 0c.419.267.173.923-.462.79c-.635-.134-.75-.516-.748-.676Z");
}

.no0ed4ozf {
  d: path("M18.137 6.508c-.166-.285-.072-.676.02-.797c.337.552.826.513 1.029.424c.082.135.176.411-.014.57c-.223.186-.78.239-1.035-.197Z");
}

.nr6tk6bwq {
  d: path("M17.847 5.383a.363.363 0 0 1-.24.212a.948.948 0 0 1-.837-.185c-.24-.193-.256-.472-.172-.582a.27.27 0 0 1 .349-.081c.135.064.135.2.357.346c.178.116.429.045.532-.004c.029.038.07.151.01.294Z");
}

.nue0inbrw {
  d: path("M15.535 5.276c-.148-.222-.063-.487-.001-.592c.04.095.204.318.54.449a.648.648 0 0 0 .692-.123c.035.032.098.136.071.288c-.05.292-.279.418-.565.412c-.287-.006-.552-.157-.737-.434Z");
}

.nwdkllbxq {
  d: path("M7.641 12.314c-.125-.044-.183-.217-.205-.281c.191-.402.418-.594.582-.57c.164.023.098.43.023.601c-.074.172-.244.305-.4.25Z");
}

.nxhdkhcqq {
  d: path("M24.772 12.326c.047-.244.191-.305.258-.305l.343.027c.059.305.18.391.278.524c.097.133.011.488-.297.488c-.309 0-.64-.43-.582-.734Z");
}

.o64f5oboe {
  d: path("M23.737 4.35c-.069-.21-.282-.312-.38-.337c.003.1-.065.333-.226.428a.929.929 0 0 1-.392.124a.394.394 0 0 0-.068.443c.152.009.339.078.63.02c.291-.059.522-.414.436-.678Z");
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.o9_8muxkx {
  d: path("M12.4 3.896c-.017-.146.102-.292.164-.346c.373.133.645.068.86.06c.214-.006.415.183.412.337a.42.42 0 0 1-.127.268c-.174.104-.498.141-.825.056c-.327-.085-.462-.192-.484-.375Z");
}

.och9wxgnu {
  d: path("M14.092 7.916c-.272-.16-.277-.457-.246-.586c.042.09.227.275.633.297c.406.021.617-.244.672-.38c.07.04.254.329 0 .618s-.72.25-1.059.05Z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojwcfntba {
  d: path("M11.411 6.02c-.178-.26-.056-.532.028-.636c0 .1.088.346.446.539c.358.193.662.043.769-.056c.047.065.09.405-.263.558c-.353.153-.757-.08-.98-.406Z");
}

.omxkqibvg {
  d: path("M26.015 9.723a.434.434 0 0 1-.169-.347c.516-.442.973-.28 1.11-.14c.135.14.097.431-.181.553a.785.785 0 0 1-.76-.066Z");
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.opco-p70b {
  d: path("M25.116 11.423c.015-.172.158-.293.227-.332c.023.095.146.317.452.447c.305.13.574.032.67-.033c.03.031.094.11.118.175c.029.081.006.322-.34.454c-.346.132-.589.037-.817-.12c-.23-.157-.33-.377-.31-.591Z");
}

.opdlrynpx {
  stop-color: var(--svg-color--ffebc4, #FFEBC4);
}

.opjfhbcxc {
  d: path("M11.069 5.06c-.028-.347.243-.53.383-.578c.144-.04.23 0 .246.137c.012.11-.068.248-.11.304c.07.01.216.064.25.192c.032.242-.093.351-.226.394c-.133.043-.508-.015-.543-.449Z");
}

.ovb-inlsf {
  d: path("M11.745 5.385c-.034-.144.067-.302.122-.364c.386.088.662.028.874-.004c.213-.032.421.095.436.249a.419.419 0 0 1-.094.281c-.16.124-.478.199-.813.153c-.335-.046-.481-.136-.525-.315Z");
}

.oxdjsnp6a {
  d: path("M15.712 7.116a.664.664 0 0 0-.058-.445c-.305.449-.61.48-.86.5a.516.516 0 0 1-.39-.125c-.18.547.277.77.64.707c.364-.063.61-.399.668-.637Z");
}

.oxy_xhbca {
  d: path("M15.76 5.053c-.044-.23-.256-.307-.356-.316c-.235.285-.45.293-.688.371c-.238.078-.273.23-.234.406a.419.419 0 0 0 .164.254c.133-.004.328-.02.523-.066c.332-.086.645-.36.59-.649Z");
}

.oyb4hqvkg {
  d: path("M11.299 7.029c-.088-.131-.076-.336-.059-.422c.336.078.5-.023.876-.035c.375-.012.468.133.488.316c.02.184-.059.406-.426.43c-.367.023-.77-.125-.879-.29Z");
}

.p-j0vyb7q {
  d: path("M18.197 5.189a.44.44 0 0 1 .135-.27c.02.029.287.15.44.194a1.4 1.4 0 0 0 .64.042c.4.295.11.933-.514.758c-.625-.175-.713-.564-.701-.724Z");
}

.p0milabxh {
  d: path("M18.018 6.158c-.018-.225.082-.387.211-.422c.469.539.703.329.898.66c.09.152.008.574-.402.492c-.41-.082-.683-.449-.707-.73Z");
}

.p1g-jpb-t {
  cx: 11.367px;
  cy: 16.986px;
  rx: 0.732px;
  ry: 0.371px;
}

.p28rgwnvv {
  d: path("M22.381 8.45c-.053-.396.14-.558.242-.589c.265.124.809.45.871.762c.079.39-.148.562-.418.566c-.269.004-.628-.242-.695-.738Z");
}

.p3z5ozbbj {
  d: path("M9.518 7.15c-.035-.2.084-.393.148-.465c.149.156.446.29.723.285a.97.97 0 0 0 .45-.109c.206.035.222.289.163.387c-.09.172-.285.433-.707.422c-.422-.012-.734-.27-.777-.52Z");
}

.p65pf0bkg {
  d: path("M27.052 8.917c.113-.197-.007-.39-.081-.462c-.305.145-.589.07-.783.024c-.194-.046-.33-.048-.444.091c-.114.14-.18.525.348.592c.528.067.82 0 .96-.245Z");
}

.p9php6kcu {
  d: path("M5.812 13.29c-.116-.306-.012-.525.054-.597c.122.207.293.29.488.262c.196-.028.696-.149.684.246c-.012.394-.3.453-.477.473c-.175.019-.605 0-.75-.383Z");
}

.pabs_sbwe {
  d: path("M9.842 7.935c-.084-.15-.035-.33 0-.402c.073.065.3.179.625.113a.742.742 0 0 0 .535-.406c.042.009.14.037.196.078c.07.05.187.262-.024.566c-.21.305-.465.364-.742.364c-.277 0-.484-.125-.59-.313Z");
}

.pgkj3lg9r {
  d: path("M24.373 10.17c-.003-.27.088-.45.133-.508c.018-.08.1-.225.278-.156c.178.068.248.255.261.34a.85.85 0 0 0 .028.421c.043.149.046.442-.239.496c-.285.055-.457-.257-.46-.593Z");
}

.pglbsdbvr {
  d: path("M18.34 6.1c-.047-.222.127-.369.219-.414c.246.23.539.246.738.262c.2.015.328.054.395.222c.066.168.011.555-.512.457c-.523-.097-.781-.25-.84-.527Z");
}

.pj4sl46-r {
  d: path("M11.569 4.667a.52.52 0 0 1 .201-.382c.168.188.39.204.64.185c.249-.02.366.122.403.209a.372.372 0 0 1-.03.336c-.207-.008-.585.1-.79.057c-.203-.043-.43-.164-.424-.405Z");
}

.pjop0htdk {
  d: path("M22.62 8.088c-.088-.31.064-.51.152-.57c.206.174.726.34.96.402c.306.203.134.746-.226.757c-.36.012-.777-.203-.887-.59Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pldenwbvr {
  d: path("M5.806 12.76c-.145-.248.018-.512.07-.579c.025.017.15.064.445.114c.367.062.411.566.224.644c-.188.078-.56.129-.74-.18Z");
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pqxqhbcxf {
  d: path("M18.744 5.36c.053-.331.282-.464.39-.488a.96.96 0 0 0 .813.992c-.031.273-.152.48-.508.43c-.355-.051-.762-.52-.695-.934Z");
}

.prc7rtbwy {
  d: path("M16.004 4.885c-.293-.251-.193-.587-.106-.724c.32.398.708.202.872.18c.164-.022.32.014.395.137c.074.123.05.297-.09.436s-.705.286-1.07-.029Z");
}

.pwlfp16tp {
  d: path("M26.678 10.056a.663.663 0 0 0 .08-.442c-.427.335-.726.271-.97.213a.516.516 0 0 1-.334-.238c-.338.466.029.817.394.869c.365.052.702-.193.83-.402Z");
}

.px_573nlv {
  d: path("m15.264 17.912l-.999 3.196a1.014 1.014 0 0 0 .979 1.314h1.478c.694 0 1.183-.667.979-1.314l-1-3.196c-.213-.708-1.212-.708-1.437 0Z");
}

.pyn4-9mft {
  d: path("M24.093 6.553c.034-.233.242-.318.341-.331c.247.275.462.273.703.341c.242.068.283.219.252.396a.422.422 0 0 1-.154.26a2.654 2.654 0 0 1-.525-.043c-.336-.072-.66-.332-.617-.623Z");
}

.q__c000km {
  d: path("M9.874 6.22A.341.341 0 0 1 9.9 5.8c.215.41.646.577.835.61c-.32.212-.712.053-.86-.19Z");
}

.q-7-kre2s {
  d: path("M6.788 14.17a.593.593 0 0 1-.352-.528c.075-.037.257-.115.391-.12c.168-.009.168.296.164.433c-.004.136-.035.293-.203.215Z");
}

.q-sol0bxm {
  d: path("M25.987 13.025c.262-.206.2-.46.136-.563c-.234-.278-.428-.056-.496.09c.022.207.249.401.36.473Z");
}

.q5-d1o17a {
  d: path("M19.44 6.966a.44.44 0 0 1 .129-.273c.02.029.29.144.445.184c.306.078.555.05.64.027c.407.285.133.93-.495.77c-.63-.16-.727-.547-.72-.708Z");
}

.q6qh4lb2f {
  d: path("M24.807 6.646a3.441 3.441 0 0 0-.035.176c-.03.023-.081.112-.047.277c.034.166.145.197.195.192c.247-.063.317-.254.344-.47c.028-.214-.058-.335-.175-.358a.235.235 0 0 0-.282.183Z");
}

.q8ct3fs0x {
  d: path("M6.381 7.619c.135.367.454.362.603.332c.27-.332-.036-.528-.165-.707a.311.311 0 0 1-.027-.34c-.402.039-.526.402-.411.715Z");
}

.qdsj2fbbv {
  d: path("M8.774 5.693c-.124-.162-.096-.382-.067-.472c.542.228.976.129 1.125.05c.079.048.23.189.208.375c-.028.233-.23.45-.555.425a.95.95 0 0 1-.711-.378Z");
}

.qflcowbjd {
  d: path("M24.227 8.612a.663.663 0 0 1 .04-.448c.323.436.63.454.88.463c.2.007.34-.091.385-.141c.203.539-.245.78-.61.733c-.366-.047-.626-.372-.695-.607Z");
}

.qhpjxobad {
  d: path("M9.027 3.962a.57.57 0 0 1 .366-.44c.02.288.371.424.507.46c.137.036.33.08.263.393c-.069.313-.52.34-.742.25c-.22-.09-.453-.32-.394-.663Z");
}

.qjdsqhtxh {
  d: path("M16.148 3.316c.042-.346.345-.47.491-.49c.15-.009.226.047.213.184c-.01.11-.116.23-.168.276c.065.024.198.106.206.238c-.018.244-.162.326-.301.341c-.139.015-.494-.118-.441-.55Z");
}

.qk5_l3bpc {
  d: path("M8.87 6.51a.767.767 0 0 1 .226-.596c.112.41.323.66.628.727c.244.054.269-.15.328-.216l.173.068c.18.268-.154.694-.556.671c-.403-.023-.771-.286-.799-.655Z");
}

.qkaciqlvj {
  d: path("M17.448 6.291c.207-.257.171-.658.098-.79c-.414.496-.892.385-1.08.267c-.101.121-.235.381-.07.566c.194.217.736.351 1.052-.043Z");
}

.qlwlh0fhk {
  d: path("M7.136 11.252c-.243.29-.483.366-.572.368c-.082.014-.34-.06-.337-.303c.004-.244.07-.3.378-.496c.246-.157.411-.358.463-.44c.26.191.373.51.068.87Z");
}

.qqnyqzw3g {
  d: path("M7.373 10.877c-.165-.153-.178-.325-.164-.39c.543-.528.985-.419 1.137-.216c.152.203.05.48-.152.606c-.203.125-.614.191-.82 0Z");
}

.qtrlt_g5u {
  d: path("M6.289 8.55c.337.172.588.148.67.115c.082-.02.29-.188.192-.411c-.099-.223-.182-.248-.542-.308a1.657 1.657 0 0 1-.598-.223c-.164.277-.144.614.278.828Z");
}

.qv9p0cc_s {
  d: path("M12.506 5.548c-.178-.26-.056-.532.028-.635c0 .1.087.346.446.539c.358.193.662.043.769-.056c.047.065.09.405-.263.558c-.353.153-.757-.08-.98-.406Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyjw7-0zy {
  cx: 24.944px;
  cy: 18.448px;
  r: 1.871px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.qzat3us2f {
  d: path("M23.946 5.638a.59.59 0 0 0 .54-.598c-.002-.457-.568-.533-.839-.362c-.135.085-.194.2-.122.309c.072.108.162.096.265.084c.104-.013.243-.046.103.059c-.14.104-.186.166-.116.318a.372.372 0 0 0 .17.19Z");
}

.r-90x2rqr {
  d: path("M16.672 7.794c.227-.253.135-.56.06-.682c-.013.106-.142.356-.552.512c-.41.155-.713-.048-.813-.17c-.06.064-.153.42.202.634c.355.214.82.021 1.103-.294Z");
}

.r8h8wpb-s {
  cx: 14.199px;
  cy: 2.692px;
  rx: 0.322px;
  ry: 0.257px;
}

.r9argyb8r {
  cx: 25.628px;
  cy: 15.769px;
  r: 0.272px;
}

.r9tu_7jps {
  d: path("M8.566 3.496c.047-.225.257-.322.356-.342c-.032.068.022.265.191.345c.17.08.35.165.427.331c.062.133-.034.267-.09.318c-.105-.042-.332.001-.525-.077c-.192-.078-.418-.293-.359-.575Z");
}

.rf-_flbmk {
  fill: var(--svg-color--c19d77, #C19D77);
  d: path("M6.309 7.763v5.188l1.687-2l.157-1.5l1.406-.781l2.281-.313l1.438-.281h2.468c.376-.5 1.407-.5 2.032-.5c.781 0 1.375.187 2.062.5c.688.312 1.75.531 2.782.406c1.03-.125 1.843 1.934 2.578 3.03c.544.81-.506 1.397-.203 1.845l.906-1.437V8.357l-1.438-2l-.375-1.406l-.75-.469l-.718-.781l-1.032.156l-1.156-.594l-1-.625l-.438.625l-.78-.156l-1.126-.187h-1.5l-2.937.343l-4.5.938l-1.125 1.687c-.344-.083-1.044-.2-1.094 0c-.05.2.23 1.334.375 1.875Z");
}

.rm4vinbaq {
  d: path("M15.55 6.048c-.038-.145.063-.308.118-.372c.396.085.675.02.892-.016c.216-.036.43.091.448.247a.427.427 0 0 1-.092.289c-.162.128-.485.209-.827.167c-.342-.043-.493-.133-.54-.315Z");
}

.ropbovbic {
  d: path("M15.976 5.29c-.059-.146-.006-.344.028-.425c.313.145.495.078.864.142c.37.064.433.225.415.409c-.018.183-.14.386-.504.335c-.364-.051-.729-.278-.803-.46Z");
}

.rss8m4tyn {
  d: path("M14.118 2.983a.52.52 0 0 0-.245-.355c-.144.206-.362.248-.612.258c-.25.01-.35.165-.377.255a.368.368 0 0 0 .07.33c.205-.031.593.032.79-.035c.197-.068.409-.215.374-.453Z");
}

.rtugd8bpy {
  d: path("M13.55 6.25a.341.341 0 0 1 .025-.42c.215.41.647.577.836.61c-.32.212-.712.053-.86-.19Z");
}

.rwj933nnd {
  d: path("M13.531 4.367c-.017-.146.102-.292.163-.346c.374.133.654.105.87.099c.214-.007.406.144.403.298a.419.419 0 0 1-.127.269c-.174.103-.498.14-.825.055c-.327-.085-.462-.192-.484-.375Z");
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s-hrk22ri {
  d: path("M8.606 5.915c-.278-.21-.283-.473-.251-.58c.226.182.468.18.65.008s.493-.072.46.233c-.032.305-.511.6-.859.339Z");
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s3bqmqb0n {
  d: path("M17.57 2.642c-.118-.188-.35-.234-.45-.233c.027.095.018.338-.114.47a.93.93 0 0 1-.35.216a.394.394 0 0 0 .043.446c.15-.028.348-.008.615-.136c.268-.128.404-.528.256-.763Z");
}

.s7b6inb1j {
  d: path("M24.979 13.943a1.166 1.166 0 0 1-.063-.492l.461-.461c0 .226.102.46.203.7c.102.237-.003.433-.203.476c-.199.043-.308-.004-.398-.223Z");
}

.s7txgibet {
  d: path("M24.252 9.28c-.185-.274-.117-.67-.034-.797c.373.528.859.456 1.055.354c.091.129.204.399.024.57c-.21.2-.761.29-1.045-.128Z");
}

.s96438ujh {
  d: path("M15.72 5.917c.047-.222-.126-.369-.219-.414c-.246.23-.539.246-.738.261c-.2.016-.328.055-.395.223c-.066.168-.011.555.512.457c.524-.098.781-.25.84-.527Z");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sc2dwxmvr {
  d: path("M5.924 7.687c-.06-.107-.027-.194-.003-.225c.526.111.74-.09.815-.15c.075-.06.353-.026.378.27a.422.422 0 0 1-.227.416c-.079-.054-.22.048-.507 0a.647.647 0 0 1-.456-.31Z");
}

.sd5vsfuhv {
  d: path("M24.38 8.212c-.146-.316-.027-.551.051-.63c.114.267.328.38.57.313c.242-.066.47.168.297.422c-.172.254-.734.29-.918-.105Z");
}

.sh2q0kb3d {
  d: path("M5.48 6.744c-.155-.259 0-.543.097-.653c.03.122.198.333.494.402a.342.342 0 0 0 .403-.2c.257.1.23.314.184.41c-.113.084-.203.344-.452.379c-.249.035-.532-.015-.726-.338Z");
}

.si1-qzoqv {
  d: path("M24.78 13.416c-.184-.435-.077-.827 0-.97c.195 0 .64.466.558.72c-.082.254-.468.457-.558.25Z");
}

.so6ggsb_z {
  d: path("M6.16 15.845c.021-.147.092-.225.124-.246l.348.153c.013.23.005.674-.13.605c-.167-.086-.37-.328-.343-.512Z");
}

.srhlmdbqx {
  d: path("M12.444 7.611c.028-.206.144-.315.199-.344c.4.25.846.211 1.02.16c.324.16.296.477.214.621c-.082.145-.312.356-.793.239c-.48-.117-.675-.418-.64-.676Z");
}

.sssp2rbtv {
  d: path("M9.354 8.427c.378.013.595-.114.656-.18c.065-.05.184-.292 0-.452c-.184-.16-.27-.149-.621-.051a1.657 1.657 0 0 1-.637.05c-.031.32.13.618.602.633Z");
}

.t7j_vi8an {
  d: path("M6.006 5.696a.323.323 0 0 1 .071-.2a.576.576 0 0 1 .435.16c.094.112-.016.294-.201.294c-.186 0-.31-.123-.305-.254Z");
}

.tdkvgvbrv {
  d: path("M19.409 6.42c-.047-.222.126-.369.218-.415c.247.231.54.247.739.262c.199.016.328.055.394.223s.012.555-.512.457c-.523-.098-.78-.25-.84-.527Z");
}

.te3h9abkf {
  d: path("M6.23 11.614a.966.966 0 0 1-.487-.148c-.06.077-.28.366.102.65c.383.284.755.19.89.111c.134-.079.214-.318.073-.5c-.14-.182-.307-.113-.578-.113Z");
}

.tes8b00ay {
  d: path("M11.325 6.25a.341.341 0 0 1 .025-.42c.215.41.646.577.835.61c-.32.212-.712.053-.86-.19Z");
}

.tf8twm7te {
  d: path("M10.233 8.431a.567.567 0 0 1-.047-.242c.05.03.215.08.48.04a.641.641 0 0 0 .457-.282c.185-.003.283.22.309.332a.885.885 0 0 1-.582.363c-.379.051-.563-.09-.617-.21Z");
}

.tl-mjkmkv {
  d: path("M21.492 6.78a.664.664 0 0 0 .04-.446c-.396.37-.7.334-.948.298a.516.516 0 0 1-.353-.208c-.296.493.1.811.469.83c.368.02.682-.254.792-.473Z");
}

.tqnhqjb6g {
  d: path("M9.24 5.118c-.293-.252-.193-.587-.106-.724c.32.397.708.202.872.18c.164-.023.32.014.394.137c.075.123.05.297-.09.436c-.14.138-.704.285-1.07-.03Z");
}

.traxwhbec {
  stop-color: var(--svg-color--dfbf91, #DFBF91);
}

.tun6z81hv {
  d: path("M8.07 4.909a.429.429 0 0 1 .23-.424c.018.274.194.446.39.35a.293.293 0 0 1 .412.148c.048.124.036.401-.322.486c-.357.084-.69-.248-.71-.56Z");
}

.tuv68lbej {
  d: path("M13.57 2.918c.048-.225.258-.322.357-.342c-.032.068.021.265.191.345c.17.08.35.165.427.331c.062.133-.034.267-.09.317c-.105-.041-.333.002-.525-.076s-.418-.294-.36-.575Z");
}

.tv139eb_k {
  d: path("M24.834 7.077c.095-.206-.041-.387-.122-.452c-.29.17-.58.12-.777.092c-.198-.028-.332-.019-.434.13c-.102.15-.134.539.398.559c.532.02.817-.071.935-.33Z");
}

.u_in95b_f {
  d: path("M5.693 9.98a.462.462 0 0 1 .43-.143c-.035.372.076.433.302.607c.193.21.032.424-.073.505a.776.776 0 0 1-.59-.203c-.26-.239-.249-.565-.07-.766Z");
}

.u55u-0b4m {
  d: path("M11.873 16.269a1.678 1.678 0 0 0-1.617 2.12h3.241a1.72 1.72 0 0 0 .061-.442a1.69 1.69 0 0 0-1.685-1.678Z");
}

.u6_rgsbxk {
  d: path("M15.689 6.464a.44.44 0 0 0-.129-.274c-.02.029-.29.144-.445.184c-.307.078-.555.05-.641.027c-.406.285-.133.93.496.77c.63-.16.727-.547.719-.707Z");
}

.u7as4g6sb {
  d: path("M24.381 7.072a.429.429 0 0 1 .402-.266c-.113.25-.039.485.18.492a.293.293 0 0 1 .293.325c-.015.132-.156.37-.512.277c-.355-.094-.492-.543-.363-.828Z");
}

.u832i7sin {
  d: path("M6.448 12.787a.494.494 0 0 1 .035-.45c.331-.415.815-.303 1.015-.195c.278.375 0 .754-.277.836c-.277.082-.672.07-.773-.191Z");
}

.uchjg6bzz {
  cx: 7.056px;
  cy: 18.448px;
  r: 3.139px;
}

.uf-ketbzf {
  d: path("M25.249 14.666c-.075-.178-.06-.44-.043-.547l.37-.262c.102.352.235.434.293.559a.263.263 0 0 1-.152.367c-.18.07-.375.105-.468-.117Z");
}

.ufry78bci {
  d: path("M9.895 2.888c.048-.225.257-.322.356-.342c-.032.068.022.265.191.345c.17.08.35.165.427.33c.062.134-.034.268-.089.318c-.106-.041-.333.002-.525-.076c-.193-.078-.42-.294-.36-.575Z");
}

.ugz5pohnc {
  d: path("M9.212 5.523c-.06-.146-.006-.344.028-.425c.313.144.495.078.864.142c.37.064.433.224.415.408c-.018.184-.14.386-.504.335c-.364-.05-.729-.277-.803-.46Z");
}

.ujei-z_bf {
  d: path("M22.59 6.401a.341.341 0 0 0-.06-.416c-.18.425-.596.628-.782.676c.337.185.714-.006.842-.26Z");
}

.ulea8ebhm {
  d: path("M17.827 3.587c-.015-.235-.215-.337-.314-.358c-.267.254-.482.236-.728.284c-.246.048-.3.195-.282.374a.423.423 0 0 0 .131.272c.133.013.328.021.528-.001c.34-.045.684-.278.665-.571Z");
}

.um8zr3bpg {
  d: path("M24.419 8.897c.23-.235.235-.638.175-.777c-.46.453-.926.295-1.1.16c-.114.11-.272.355-.127.556c.172.235.698.422 1.052.061Z");
}

.uo4w231ko {
  d: path("M26.276 12.552c.103-.084.076-.298.05-.394c-.101-.29-.488-.133-.46.14c.027.274.28.36.41.254Z");
}

.uqmydze1z {
  d: path("M20.875 4.174a.59.59 0 0 0 .54-.598c-.002-.457-.568-.533-.839-.362c-.135.085-.193.2-.122.308c.072.109.162.097.265.085c.104-.013.243-.046.103.059c-.14.104-.185.166-.116.318a.372.372 0 0 0 .17.19Z");
}

.uqwrzcbdl {
  d: path("M22.721 7.06c.072-.178.27-.21.36-.203c.027.211.222.36.605.438c.191.039.433.199.277.476c-.16.283-.668.153-.968-.05c-.301-.204-.364-.438-.274-.66Z");
}

.urdyp6bqk {
  d: path("M15.264 3.322a.52.52 0 0 1 .246-.356c.144.207.362.249.612.259c.25.01.35.165.376.255a.37.37 0 0 1-.069.33c-.205-.032-.593.031-.79-.036c-.198-.067-.41-.214-.375-.452Z");
}

.utipq7b0b {
  d: path("M24.169 7.414c-.057-.22.11-.374.2-.423c.256.22.55.223.75.23c.199.007.33.04.403.206c.073.165.035.553-.492.478c-.527-.075-.791-.216-.861-.491Z");
}

.uvtg8hq0x {
  d: path("M25.3 6.158a.59.59 0 0 1-.424-.686c.084-.449.654-.423.89-.206c.118.108.155.232.065.326c-.09.093-.177.066-.275.035h-.001c-.1-.031-.23-.088-.112.04c.119.128.153.197.057.334a.372.372 0 0 1-.2.157Z");
}

.uwnpv4bpr {
  d: path("M7.66 9.83c-.226.26-.574.306-.72.297c-.109.254 0 .547.329.437c.328-.11.472-.394.464-.543c-.006-.119-.052-.177-.074-.191Z");
}

.uwv4pp46h {
  stop-color: var(--svg-color--b47094, #B47094);
}

.uxdgxwwgw {
  d: path("M6.038 11.404c-.05.1-.045.284-.035.363a.743.743 0 0 0 .452.051c.003-.032.007-.14 0-.246c-.007-.133-.058-.234-.148-.277c-.09-.043-.207-.016-.27.109Z");
}

.uxguh0bbm {
  d: path("M5.772 7.31c.057.144.18.205.235.218c.3.079.598.02.841-.169c.243-.188.265-.467.183-.578a.27.27 0 0 0-.347-.088c-.136.061-.14.197-.364.338c-.18.113-.43.037-.532-.014c-.029.038-.073.15-.016.294Z");
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v_7qidbaj {
  d: path("M24.484 7.272c.034-.233.242-.318.342-.331c.246.274.461.273.703.341c.241.068.283.219.251.396a.422.422 0 0 1-.153.26a2.654 2.654 0 0 1-.526-.043c-.335-.072-.659-.332-.617-.623Z");
}

.v1-92dbdc {
  cx: 26.437px;
  cy: 7.214px;
  rx: 0.241px;
  ry: 0.307px;
}

.v1j_e9tbd {
  d: path("M21.198 6.705c.059-.219.267-.323.363-.348c-.031.207.281.414.594.477c.23.046.458.287.277.52c-.191.245-.668.062-.848-.044c-.18-.105-.46-.332-.386-.605Z");
}

.v2no4h1wv {
  d: path("M19.451 4.56c.034-.216.227-.343.305-.383c0 .082.062.309.261.52c.165.174.416.22.536.234c.043.238-.032.398-.09.465c-.059.066-.219.207-.57.047c-.352-.16-.485-.614-.442-.883Z");
}

.v413-6lxs {
  d: path("M6.206 14.83c-.04-.116-.017-.29 0-.364c.133-.05.413-.126.473-.039c.074.11.14.657-.075.72c-.214.062-.347-.173-.398-.317Z");
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v5ghnvq8t {
  d: path("M7.173 9.272c.042-.298-.213-.5-.345-.562c.02.123-.052.384-.297.563a.342.342 0 0 1-.45-.026c-.197.192-.088.379-.009.449c.138.034.323.237.565.172c.243-.066.484-.222.536-.596Z");
}

.v6g6ftb9d {
  d: path("M17.993 3.742c-.115-.16-.328-.185-.42-.177l-.248.404c-.213.09-.34.364-.114.525c.224.16.41.126.665-.06a.488.488 0 0 0 .117-.692Z");
}

.v8a7dt81c {
  d: path("M15.227 4.775a.44.44 0 0 0-.094-.287c-.025.026-.306.107-.465.128a1.406 1.406 0 0 1-.64-.052c-.437.233-.245.906.399.825c.643-.082.788-.454.8-.614Z");
}

.v9c4cgbhh {
  d: path("M9.057 6.552a.816.816 0 0 1-.476-.694c.101.048.279.082.585-.015c.307-.097.507.053.558.265a.45.45 0 0 1-.667.444Z");
}

.vakul_mok {
  d: path("M11.163 8.064a.767.767 0 0 1 .101-.629c.192.38.45.582.762.586c.25.003.233-.2.277-.277l.184.031c.23.227-.012.711-.41.77c-.399.058-.813-.125-.914-.48Z");
}

.vbi3h0biu {
  d: path("M18.157 5.84a.664.664 0 0 1 .07-.444c.293.457.597.495.847.521c.2.02.345-.068.393-.115c.167.55-.295.762-.657.69c-.362-.07-.6-.412-.653-.652Z");
}

.vfbr2pb4n {
  d: path("M19.416 7.619a.663.663 0 0 1 .059-.446c.305.45.61.48.86.5a.51.51 0 0 0 .39-.125c.18.547-.277.77-.64.707c-.364-.062-.61-.398-.669-.636Z");
}

.vj_ad1bzt {
  d: path("M23.44 8.896c.225.01.318.173.336.254c.176.418.066.867-.203.926c-.27.058-.516-.211-.543-.524c-.027-.312.129-.668.41-.656Z");
}

.vk714r9cb {
  d: path("M6.588 8.352c-.171-.1-.375-.035-.456.01l-.06.47c-.158.17-.161.471.11.526c.271.055.426-.053.583-.327a.488.488 0 0 0-.177-.68Z");
}

.vlrfhp1-h {
  d: path("M17.721 6.498c.034-.215.227-.342.305-.382c0 .082.062.308.262.52c.164.174.415.22.535.234c.043.238-.032.398-.09.464c-.059.067-.219.207-.57.047c-.352-.16-.485-.613-.442-.883Z");
}

.vlxo6wwfe {
  d: path("M24.085 9.056c.006-.262.153-.414.226-.457l.555.489c.14.265.11.601-.235.64c-.343.04-.554-.344-.546-.672Z");
}

.vmd3iubtm {
  d: path("M9.383 3.548c.043-.345.346-.47.492-.489c.15-.009.226.047.213.184c-.01.11-.116.23-.168.276c.065.024.198.105.206.238c-.018.243-.163.325-.301.34c-.14.016-.495-.117-.442-.549Z");
}

.vmkpn34ef {
  cx: 10.524px;
  cy: 2.662px;
  rx: 0.322px;
  ry: 0.257px;
}

.vms4etbtb {
  d: path("M8.706 6.166c-.147-.221-.062-.487-.001-.592c.04.095.204.318.54.449a.647.647 0 0 0 .692-.123c.035.033.099.136.072.289c-.051.29-.28.417-.566.411c-.287-.006-.552-.157-.737-.434Z");
}

.vn9r6cbiq {
  d: path("M11.268 7.448a.951.951 0 0 1 .03-.43c.02.04.125.143.388.23c.262.088.59.058.722.032c.141.05.172.234.145.379c-.027.144-.207.398-.586.37c-.379-.027-.668-.37-.7-.581Z");
}

.vt9qo491m {
  d: path("M25.998 8.911c-.047.074-.096.096-.114.097c-.145.039-.192.087-.201.17c-.01.084.026.25.338.232c.31-.019.554-.25.542-.39a.288.288 0 0 0-.262-.26a.318.318 0 0 0-.303.151Z");
}

.vta1uoi-x {
  d: path("M15.355 4.055c-.017-.146.102-.292.163-.346c.374.133.654.106.869.099c.215-.007.407.144.404.298a.419.419 0 0 1-.127.269c-.174.103-.498.14-.825.055c-.327-.085-.462-.192-.484-.375Z");
}

.vun_f_b1g {
  fill: var(--svg-color--000, #000);
  d: path("M19.123 17.947c0-.534.427-.961.96-.961c.535 0 .962.427.962.96a.96.96 0 0 1-.107.443h-1.7a.87.87 0 0 1-.115-.442Z");
}

.vvq9babrb {
  d: path("M6.668 5.064c.116-.16.328-.185.42-.177l.249.404c.212.09.339.363.114.525c-.225.16-.41.126-.666-.06a.488.488 0 0 1-.117-.692Z");
}

.vw2czvbjq {
  d: path("M15.634 6.277a.768.768 0 0 1 .226-.596c.112.41.323.66.628.728c.245.053.27-.15.328-.216l.173.067c.18.269-.154.694-.556.672c-.402-.023-.77-.287-.799-.655Z");
}

.vz8zmbbms {
  d: path("M13.975 7.494c-.228-.138-.264-.414-.254-.535c.077.069.32.2.68.175a.648.648 0 0 0 .574-.406c.046.014.147.08.188.23c.078.286-.075.497-.337.614c-.261.117-.566.094-.85-.078Z");
}

.w-leh1bmv {
  d: path("M14.444 3.805c.05-.23.262-.301.363-.308c.227.291.442.304.678.388c.237.084.268.237.225.412a.423.423 0 0 1-.17.25a2.653 2.653 0 0 1-.522-.08c-.33-.093-.636-.374-.574-.662Z");
}

.w0rs-3b8j {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.264 17.912l-.999 3.196a1.014 1.014 0 0 0 .979 1.314h1.478c.694 0 1.183-.667.979-1.314l-1-3.196c-.213-.708-1.212-.708-1.437 0Z");
}

.w21w9zi9u {
  d: path("M6.815 6.705c.06.142.184.2.24.212c.3.073.598.008.837-.185s.255-.472.171-.582a.27.27 0 0 0-.348-.081c-.135.064-.136.2-.358.346c-.178.116-.429.045-.532-.005c-.028.04-.07.152-.01.295Z");
}

.w27ucebkj {
  d: path("M17.37 6.896a.62.62 0 0 1 .363-.43c.018.779.515.97.761.97c.004.3-.222.515-.59.39c-.366-.125-.616-.598-.535-.93Z");
}

.w7yf-ibvl {
  d: path("M7.397 5.517a.363.363 0 0 0 .16.277a.948.948 0 0 0 .854.086c.288-.109.39-.369.345-.499a.27.27 0 0 0-.306-.186c-.148.019-.191.148-.448.217c-.205.054-.421-.091-.503-.17c-.04.027-.115.121-.102.275Z");
}

.wb0uqbbzd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.292 14.037c.615-.544 1.959-1.116 3.624-.85");
}

.wb5bpab4s {
  d: path("M14.028 3.717c.017-.147-.102-.292-.164-.347c-.373.133-.654.106-.869.1c-.214-.008-.406.144-.403.297a.42.42 0 0 0 .127.269c.174.103.498.14.825.056c.327-.086.462-.192.484-.375Z");
}

.wbsf4nbws {
  d: path("M13.834 7.037c-.18-.094-.25-.305-.261-.399c.587-.025.937-.3 1.039-.433c.09.009.288.072.347.25c.075.222-.015.504-.32.62a.95.95 0 0 1-.805-.038Z");
}

.wbuy9zv7y {
  d: path("M6.206 11.025a.435.435 0 0 1 .25-.355a.627.627 0 0 0 .558.218c.363-.043.527.301.371.504a.667.667 0 0 1-.734.23c-.297-.093-.465-.34-.445-.597Z");
}

.wcgql7bkv {
  d: path("M7.356 7.934c.341.165.59.136.673.101c.08-.02.287-.194.183-.414c-.103-.221-.186-.245-.547-.298a1.657 1.657 0 0 1-.603-.21c-.158.28-.132.616.294.821Z");
}

.wfkmq3byh {
  d: path("M26.856 9.428a.44.44 0 0 0-.04-.3c-.028.021-.32.048-.48.039a1.405 1.405 0 0 1-.618-.17c-.474.147-.41.844.237.884c.648.04.86-.298.9-.453Z");
}

.wjb1uhbwo {
  d: path("M24.223 7.959a.44.44 0 0 1 .117-.279c.022.028.296.132.453.165c.31.065.556.027.641 0c.418.268.172.923-.463.79s-.749-.516-.748-.676Z");
}

.wmj3chl3j {
  d: path("M8.095 4.043a.323.323 0 0 1 .127-.17a.576.576 0 0 1 .368.28c.057.136-.102.277-.279.222c-.177-.054-.26-.208-.216-.332Z");
}

.wovkv07mg {
  d: path("M24.408 11.205c.16-.113.405-.1.508-.078c-.145.246-.086.328-.12.75c-.036.421-.418.587-.548.261c-.16-.402-.039-.793.16-.933Z");
}

.wrwbke1-r {
  d: path("M24.514 10.824c.16-.238.387-.253.48-.23c.446.492.56 1.46.052 1.359c-.508-.102-.731-.832-.532-1.129Z");
}

.wt09nzbjh {
  cx: 26.445px;
  cy: 8.38px;
  r: 0.248px;
}

.wu9llru8x {
  d: path("M13.338 3.508c.033.114.048.162.052.171c-.015.035-.02.137.09.267c.107.13.22.106.261.077c.188-.17.16-.373.083-.575c-.077-.203-.21-.269-.324-.235a.235.235 0 0 0-.162.295Z");
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.wxmecd6-s {
  d: path("M19.96 16.624c.12.16-.13.355-.414.567c-.284.212-.495.362-.614.202c-.12-.16.014-.462.298-.674c.284-.212.61-.255.73-.095Z");
}

.wymcc9bpj {
  d: path("M24.479 8.986a.815.815 0 0 1-.094-.836c.067.09.207.203.524.262c.316.058.421.285.367.496a.45.45 0 0 1-.797.078Z");
}

.wzgxhab_f {
  d: path("M6.737 6.947a.45.45 0 0 0 .187.43c.305-.043.375-.293.325-.493c-.051-.199-.16-.336-.27-.34c-.11-.003-.215.098-.242.403Z");
}

.wzsuubcxb {
  d: path("M27.278 7.13c-.082-.206-.301-.294-.4-.313c.009.099-.044.336-.2.441a.93.93 0 0 1-.383.148a.394.394 0 0 0-.041.446c.152 0 .343.057.63-.02c.287-.075.495-.443.394-.702Z");
}

.x_mqa2bqv {
  d: path("M6.51 9.13a.967.967 0 0 1-.476.18c0 .098 0 .461.477.453c.476-.007.715-.308.773-.453c.059-.144-.023-.383-.246-.441c-.223-.059-.312.098-.527.262Z");
}

.x12agwr7v {
  d: path("M13.519 6.263c-.02-.344.167-.512.263-.553c.149.14.466.453.547.577c.1.154.19.447-.122.587c-.31.139-.663-.182-.688-.611Z");
}

.x2xf-c9hj {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.466 18.218l-1.543 3.196c-.191.657.268 1.315.918 1.315h1.386c.65 0 1.109-.668.918-1.315l-.937-3.196c-.2-.707-.532-.707-.742 0Z");
}

.x3_jbxb2y {
  d: path("M21.992 4.78c.009-.236-.18-.357-.277-.388c-.291.227-.502.187-.752.21c-.25.024-.318.165-.318.345c0 .144.069.25.104.284c.13.026.324.053.525.05c.343-.01.708-.207.718-.501Z");
}

.x6-kod9qi {
  d: path("M25.987 10.026a.437.437 0 0 1-.049-.398c.054.08.184.126.515.168c.33.042.564.145.602.323c.04.178-.108.38-.366.355c-.258-.025-.566-.231-.702-.448Z");
}

.xbdu3-7ha {
  d: path("M17.527 5.628a.663.663 0 0 0-.004-.45c-.357.409-.663.403-.914.391a.516.516 0 0 1-.372-.172c-.246.52.18.798.548.78c.369-.017.654-.32.742-.55Z");
}

.xg239kbdk {
  d: path("M6.53 9.76a.285.285 0 0 0 0 .187l.297.191c.124.006.426-.012.645-.125c.273-.14.293-.539.129-.683c-.107-.094-.256-.11-.301-.094a.77.77 0 0 1-.387.422a.763.763 0 0 1-.383.101Z");
}

.xgp9fbc0s {
  d: path("M8.436 4.212a.52.52 0 0 1 .245-.355c.144.206.362.248.612.258c.25.01.35.165.377.255a.371.371 0 0 1-.07.33c-.205-.032-.593.032-.79-.036c-.197-.067-.409-.214-.374-.452Z");
}

.xidifjy9q {
  cx: 7.056px;
  cy: 18.448px;
  r: 1.871px;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xkmwj-65w {
  d: path("M6.14 15.486a.556.556 0 0 1-.079-.426a.514.514 0 0 0 .258.067c.156 0 .301-.157.356-.047c.09.23.027.664-.055.66c-.082-.004-.344-.066-.48-.254Z");
}

.xlph5rbrw {
  d: path("M17.014 7.298c.053-.33.283-.463.39-.488a.96.96 0 0 0 .813.992c-.031.274-.152.48-.508.43c-.355-.05-.761-.52-.695-.934Z");
}

.xn7zw8b3s {
  d: path("M11.245 6.627c-.338-.188-.308-.537-.25-.688c.394.324.734.055.89 0c.156-.055.316-.05.414.055c.098.105.11.281 0 .445c-.11.164-.633.422-1.054.188Z");
}

.xo-qyacxm {
  d: path("M22.453 4.523c.005-.148-.126-.283-.192-.332c-.361.164-.637.121-.851.132c-.215.011-.4.216-.384.37a.419.419 0 0 0 .149.256c.182.089.508.1.827-.013c.319-.112.444-.23.45-.413Z");
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrj-5j3dw {
  d: path("M25.038 9.838c-.01-.113-.137-.25-.2-.305c-.096-.347.122-.494.243-.524c.099.063.325.242.437.457c.14.27.067.508-.101.61a.485.485 0 0 1-.38.027a.668.668 0 0 1 0-.265Z");
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xstjivg-n {
  d: path("M5.658 5.668c.118-.159.332-.18.423-.17l.24.41c.211.093.333.37.105.526c-.229.157-.413.118-.665-.072a.488.488 0 0 1-.103-.694Z");
}

.xuafvdbgc {
  d: path("M7.15 7.037a.28.28 0 0 1 .247.215a2.08 2.08 0 0 0-.203.148a.744.744 0 0 1-.223.125l-.168-.215c.208-.173.24-.29.348-.273Z");
}

.xucpd1msa {
  d: path("M18.35 5.076c.129-.233.022-.49-.048-.59c-.032.098-.177.334-.5.492a.647.647 0 0 1-.7-.065c-.033.035-.088.143-.048.293c.075.286.313.393.598.363c.285-.029.537-.202.698-.493Z");
}

.xvq3ckway {
  d: path("M7.008 8.374c-.164-.294.004-.583.109-.69c.203.303.727.393.888.358c.129-.029.19.048.204.09c-.004.155.034.311.054.37c-.428.417-1.05.24-1.255-.128Z");
}

.y01fd9bap {
  d: path("M21.579 17.726a1.58 1.58 0 0 0-.435-.87l-.489.536l.22.43l.704-.096Z");
}

.y2c92-b8u {
  d: path("M12.44 2.447c.048-.225.257-.322.356-.343c-.032.069.022.266.191.346c.17.08.35.165.427.33c.062.133-.034.268-.089.318c-.106-.041-.333.002-.525-.076c-.193-.078-.42-.294-.36-.575Z");
}

.y2l25ovzu {
  d: path("M8.246 4.333c.032.113.048.161.052.171c-.016.035-.02.137.089.267c.108.13.22.105.262.077c.188-.17.16-.373.083-.575c-.077-.203-.21-.27-.324-.235a.235.235 0 0 0-.162.295Z");
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.yiqosdblp {
  cx: 24.944px;
  cy: 18.448px;
  r: 1.871px;
}

.yjvovl2wb {
  d: path("M22.268 5.288c.11-.172.064-.389.027-.476c-.521.272-.961.21-1.116.144c-.075.054-.214.206-.176.39c.047.23.265.429.587.378a.951.951 0 0 0 .678-.436Z");
}

.ykmr5z71n {
  d: path("M25.063 6.244c.009-.236-.181-.356-.277-.387c-.291.226-.503.186-.752.21c-.25.024-.318.164-.319.344c0 .144.07.25.105.284c.13.026.324.054.525.051c.343-.01.708-.208.718-.502Z");
}

.yo_n73dwc {
  d: path("M12.08 6.098c-.143-.147-.141-.369-.122-.461c.565.162.984.013 1.123-.082c.083.037.25.16.25.347c0 .235-.174.473-.5.487a.951.951 0 0 1-.751-.291Z");
}

.yqq3e723a {
  d: path("M23.174 6.045c-.028-.092-.064-.32.024-.504c.11-.23.441-.344.757-.114c.317.23.118.504-.023.516a.252.252 0 0 1-.144-.036c.067.067.13.157.125.243c-.012.168-.125.313-.188.328a.64.64 0 0 0-.234-.105a.444.444 0 0 1-.317-.328Z");
}

.yry3ztbut {
  d: path("M15.091 6.09c.207-.258.171-.66.099-.792c-.415.497-.893.386-1.08.268c-.102.121-.236.38-.07.566c.193.217.735.35 1.051-.043Z");
}

.ys_ne_6os {
  d: path("M8.632 6.598c-.178-.26-.056-.532.027-.635c0 .099.088.345.446.538a.674.674 0 0 0 .77-.056c.047.065.09.405-.264.558c-.353.153-.757-.08-.979-.405Z");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yvy42ib-k {
  d: path("M15.47 3.385c-.015-.235-.215-.337-.314-.358c-.267.254-.482.235-.728.284c-.246.048-.3.195-.282.374a.423.423 0 0 0 .131.272c.133.013.328.021.528-.001c.34-.045.684-.278.665-.571Z");
}

.z2ichlbax {
  d: path("M11.215 3.633a.52.52 0 0 1 .245-.355c.145.207.363.249.613.259c.25.01.35.165.376.255a.371.371 0 0 1-.07.33c-.204-.032-.593.031-.79-.036c-.197-.067-.409-.214-.374-.453Z");
}

.z613zdw_j {
  d: path("M5.73 13.697c.034-.103.193-.15.268-.16c.37-.09.465.11.477.246c.013.137-.11.191-.415.18c-.305-.012-.37-.137-.33-.266Z");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zcl392bgg {
  d: path("M15.716 7.784c.174-.28.089-.675 0-.797c-.35.544-.838.492-1.039.399c-.086.132-.186.407 0 .57c.219.191.773.258 1.04-.172Z");
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.ze9vjjbqg {
  d: path("M22.374 5.754c.13-.233.022-.49-.047-.59c-.032.098-.177.334-.5.492a.647.647 0 0 1-.701-.065c-.033.035-.087.143-.047.293c.075.286.312.393.597.363c.285-.029.537-.202.698-.493Z");
}

.zg44glb_b {
  d: path("M23.403 6.12c.125-.19.016-.39-.053-.466c-.313.126-.592.034-.783-.024c-.191-.058-.326-.068-.448.064c-.123.133-.213.513.31.612c.524.099.819.05.974-.186Z");
}

.zhxd5zb8u {
  d: path("M19.524 4.893a.59.59 0 0 1-.395-.703c.104-.445.672-.395.899-.168c.113.112.144.238.05.328c-.093.09-.179.059-.276.024c-.099-.036-.227-.098-.114.034c.113.133.144.204.043.336a.372.372 0 0 1-.207.149Z");
}

.zi_qf35ij {
  d: path("M26.294 7.405a.59.59 0 0 0 .591-.548c.038-.455-.519-.581-.804-.435c-.142.073-.21.183-.148.297c.061.114.152.11.256.107c.104-.004.246-.024.098.068c-.149.092-.2.15-.144.307a.38.38 0 0 0 .151.205Z");
}

.zio7rbbdg {
  d: path("M7.893 5.959a.323.323 0 0 1-.02-.211a.576.576 0 0 1 .461-.04c.133.063.11.274-.058.352c-.168.078-.333.02-.383-.101Z");
}

.zk2ex8jhu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.105 13.062c.809-.141 2.386-.1 3.478.748");
}

.zn4-kxbxl {
  cx: 16.023px;
  cy: 2.38px;
  rx: 0.322px;
  ry: 0.257px;
}

.zrm1_cb8k {
  d: path("M22.046 8.244c.159-.238.386-.253.48-.23c.445.492.559 1.46.05 1.359c-.507-.102-.73-.832-.53-1.13Z");
}

.zv65uvq-p {
  d: path("M19.76 3.536a.4.4 0 0 1 .207-.313c.183.192.37.2.593.23c.223.032.465.2.403.462c-.05.209-.29.29-.403.304a.862.862 0 0 1-.425-.25c-.184-.054-.387-.222-.375-.433Z");
}

</style>
