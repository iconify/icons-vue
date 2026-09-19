<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i6mmxQb)"><path fill="url(#iXIU87V)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#i4NZ9bb)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#indQfPd)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#iMvrnEa)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#iPouJQd)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#iPjrhDc)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#ijst4rf)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#inOCoqd)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#iwrzOnn)" clip-rule="evenodd" class="tm9wsybrf"/><path fill="url(#iTYoE0h)" clip-rule="evenodd" class="tm9wsybrf"/></g><g filter="url(#iJ7dRPC)"><path fill="url(#inwFO8c)" class="gehjzqbem"/><path fill="url(#ibfv0gb)" class="gehjzqbem"/></g><g filter="url(#ib4ou7c)"><path class="p5prc9btx"/></g><g filter="url(#iISY02T)"><path class="dgb3odblg"/></g><path fill="url(#itSRADc)" class="exvucxbiq"/><path fill="url(#iSbbKnb)" class="exvucxbiq"/><path fill="url(#i1fHkvc)" class="exvucxbiq"/><path fill="url(#iE5g3gb)" class="xc6znrbjq"/><path fill="url(#ioVp6re)" class="xc6znrbjq"/><g filter="url(#iz3a0Cd)"><path fill="url(#iCo4Qkc)" class="vlp0azbmu"/><path fill="url(#ioH3sab)" class="vlp0azbmu"/><path fill="url(#itqYW8b)" class="vlp0azbmu"/></g><path fill="url(#iL6RgQb)" class="vlp0azbmu"/><path fill="url(#ilmGz8c)" class="vlp0azbmu"/><path fill="url(#i2cdaBb)" class="vlp0azbmu"/><g filter="url(#irUQ7de)"><path fill="url(#iPDH77J)" class="v_7iv29di"/></g><g filter="url(#i9DYDbd)"><path class="tlsqvlb-h"/><path fill="url(#ixVJ9ed)" class="si9pdx_tq"/></g><path fill="url(#i07ZYOk)" class="bc14ocbhb"/><path fill="url(#iVcNUqd)" class="bc14ocbhb"/><path fill="url(#iB7Bwsb)" class="l51wizbrd"/><path fill="url(#iSHNXae)" class="jkl2w9b2m"/><path fill="url(#iEB3aZs)" class="jkl2w9b2m"/><path fill="url(#iY6QOvc)" class="jkl2w9b2m"/><path fill="url(#iUYzlEe)" class="ezus362fm"/><g filter="url(#i4tBApb)"><path fill="url(#iGErC6b)" class="dvodlmrev"/></g><g filter="url(#iP3f6Jd)"><path fill="url(#ioTplCc)" class="ipahq80uz"/></g><g filter="url(#iwdPuHb)"><path class="bnmbk2bak"/><path fill="url(#iao1pIc)" class="gwnkbobks"/></g><g filter="url(#ifLQK0d)"><path class="ye9_1e9lc"/><path fill="url(#iQTzdhc)" class="k805m1ibf"/></g><g filter="url(#idCRV3C)"><path fill="url(#ig0mNBx)" class="tta7y0bsf"/><path fill="url(#iYseUqc)" class="tta7y0bsf"/><path fill="url(#izqPn7b)" class="tta7y0bsf"/><path fill="url(#iVk8B3F)" class="tta7y0bsf"/><path fill="url(#ijIoe8V)" class="tta7y0bsf"/><path fill="url(#i6WZ4mj)" class="tta7y0bsf"/><path fill="url(#i7XLwRc)" class="tta7y0bsf"/></g><path fill="url(#iUCWmae)" class="tta7y0bsf"/><g filter="url(#iFtnQyc)"><path class="vo0pp4boh"/></g><g filter="url(#iZWhDtd)"><path fill="url(#i67vQNe)" class="k4m36ubhf"/><path fill="url(#iGYlEae)" class="k4m36ubhf"/><path fill="url(#iDKzkRd)" class="k4m36ubhf"/><path fill="url(#iIWkCwc)" class="k4m36ubhf"/></g><path fill="url(#ipLZwZd)" class="k4m36ubhf"/><path fill="url(#ikcaLWb)" class="k4m36ubhf"/><path stroke="url(#iUZK7td)" class="jd6sgdbgc"/><g filter="url(#iRshy2Y)"><path class="n7z_7vb8n"/></g><g filter="url(#iovkH8d)"><path class="rkd_cludi"/></g><g filter="url(#iAwBGOc)"><path class="l8zvg3bgw"/></g><g filter="url(#inV7XKe)"><path clip-rule="evenodd" class="k47980b8l"/></g><path class="qxb2v1b0l"/><path fill="url(#iigJCSE)" class="p-fyq_ugo"/><path class="s5m4o5b4y"/><g filter="url(#iojYAgc)"><path class="b7pb6h2yx"/><path fill="url(#izYcIEe)" class="t7e_55bck"/></g><g filter="url(#iaoen2d)"><path fill="url(#icFAZKd)" class="no15wbb0w"/></g><path class="iqpcekpgv"/><path fill="url(#iRRsN8d)" class="h5csvdbob"/><path class="syiaie9zn"/><g filter="url(#iRrtDfd)"><path fill="url(#i4MF9mW)" class="o3zwgyjdz"/></g><g filter="url(#iyIwsle)"><ellipse transform="rotate(-27.914 13.531 10.638)" class="oc7zcid3t"/><ellipse fill="url(#i6jUGNd)" transform="rotate(-27.914 13.531 10.638)" class="frd709bmb"/></g><g filter="url(#i4bayod)"><path class="i9_d89eoz"/></g><g filter="url(#iuLUSwd)"><path class="ntn842bmo"/></g><g filter="url(#ifp4XOb)"><path fill="url(#iFTjWcd)" class="kldoqgb-g"/><path fill="url(#in8THCc)" class="kldoqgb-g"/></g><g filter="url(#iljLWZU)"><path fill="url(#iT32KQc)" class="uzsgus-sl"/><path fill="url(#iyy40he)" class="uzsgus-sl"/><path fill="url(#ijvsv3d)" class="uzsgus-sl"/></g><g filter="url(#ih3UGlb)"><path stroke="url(#ihfv5Nd)" class="dxjunq6hh"/></g><defs><radialGradient id="i4NZ9bb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.414 13.364)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="indQfPd" cx="0" cy="0" r="1" gradientTransform="scale(5.8032 5.57099)rotate(90 .17 2.585)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iMvrnEa" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.075 11.652)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iPouJQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.665 9.215)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iPjrhDc" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 2.897 12.484)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="ijst4rf" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.513 7.518)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="inOCoqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.494 10.48)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iwrzOnn" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.747 4.462)scale(4.66215 6.69539)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iTYoE0h" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.28 6.663)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="ibfv0gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4313 6.37009 0 22.995 25.46)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="m5bm-ccxd"/><stop offset="1" class="q8ootib3t"/></radialGradient><radialGradient id="itSRADc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.1215 -4.59696 0 16 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="wdy63qb5p"/><stop offset="1" class="gkzmut59n"/></radialGradient><radialGradient id="iE5g3gb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3135 1.68433 0 25 29.967)" gradientUnits="userSpaceOnUse"><stop class="omh3jbc5e"/><stop offset="1" class="g1k32m_rh"/></radialGradient><radialGradient id="itqYW8b" cx="0" cy="0" r="1" gradientTransform="rotate(126.18 2.71 11.651)scale(2.59394 3.59462)" gradientUnits="userSpaceOnUse"><stop class="i1uneh2yx"/><stop offset="1" class="iw5474bga"/></radialGradient><radialGradient id="ilmGz8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 -.3125 .15357 .53751 11.395 19.724)" gradientUnits="userSpaceOnUse"><stop offset=".241" class="som6k-b6q"/><stop offset="1" class="pc2b66ykc"/></radialGradient><radialGradient id="i07ZYOk" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75 -4.3769 0 16 18.482)" gradientUnits="userSpaceOnUse"><stop offset=".362" class="zr8leoe3h"/><stop offset="1" class="i_25dj3ib"/></radialGradient><radialGradient id="iVcNUqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 6.81546 0 16 20.98)" gradientUnits="userSpaceOnUse"><stop offset=".533" class="po0u5abxc"/><stop offset=".876" class="s80u955fl"/></radialGradient><radialGradient id="iSHNXae" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -3.45478 0 15.982 21.38)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ium-0_blv"/><stop offset=".94" class="s3tb_6b2n"/></radialGradient><radialGradient id="iUYzlEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.48828 -3.72875 0 16.03 17.228)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="n7fzr7bxu"/><stop offset="1" class="rddl0jhjv"/></radialGradient><radialGradient id="ioTplCc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.025 11.77)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iao1pIc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 42.603 -51.693)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iQTzdhc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.319 11.33)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="ig0mNBx" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.238 7.464)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iYseUqc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.885 11.49)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="izqPn7b" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.805 17.576)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iVk8B3F" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.723 10.31)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="ijIoe8V" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.612 12.45)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i6WZ4mj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.286 10.375)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="i7XLwRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.067 10.462)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iUCWmae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.08 11.863)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iGYlEae" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.77 12.59)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="ikcaLWb" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.176 8.723)scale(1.57489 2.10945)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iigJCSE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.167 10.734)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="izYcIEe" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.618 1.016)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRRsN8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.803 10.734)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i6jUGNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.516 10.953)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iFTjWcd" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.604 5.314)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="in8THCc" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.776 4.567)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iT32KQc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.776 3.206)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iyy40he" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.564 9.209)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="ijvsv3d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.135 10.09)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="i6mmxQb" width="15.268" height="15.268" x="8.476" y="2.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="iJ7dRPC" width="22.5" height="14.5" x="5" y="15.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.407843 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="ib4ou7c" width="6.556" height="14.595" x="9.212" y="15.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".5"/></filter><filter id="iISY02T" width="3.95" height="13.362" x="17.96" y="16.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".375"/></filter><filter id="iz3a0Cd" width="2.897" height="14" x="10.503" y="16.057" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.368627 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="irUQ7de" width="2.965" height="2.883" x="14.509" y="18.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0980392 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2091" result="effect2_innerShadow_4002_2091"/></filter><filter id="i9DYDbd" width="2.902" height="14.05" x="18.61" y="16.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.415686 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="i4tBApb" width="3.318" height="3.218" x="9.69" y="9.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="iP3f6Jd" width="3.218" height="3.468" x="19.203" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="iwdPuHb" width="3.148" height="3.148" x="19.238" y="9.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".25"/></filter><filter id="ifLQK0d" width="2.648" height="2.648" x="9.995" y="10.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".125"/></filter><filter id="idCRV3C" width="10.191" height="11.277" x="10.889" y="6.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="iFtnQyc" width="2.877" height="3.682" x="14.384" y="10.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".25"/></filter><filter id="iZWhDtd" width="2.377" height="3.182" x="14.796" y="10.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".125"/></filter><filter id="iRshy2Y" width="3.001" height="1.285" x="16.927" y="9.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="iovkH8d" width="3.001" height="1.285" x="12.042" y="9.926" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="iAwBGOc" width="2.453" height="1.091" x="12.177" y="8.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="inV7XKe" width="2.453" height="1.091" x="17.594" y="8.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2091"/></filter><filter id="iojYAgc" width=".786" height=".696" x="17.433" y="10.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".05"/></filter><filter id="iaoen2d" width=".891" height=".913" x="18.273" y="10.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".1"/></filter><filter id="iRrtDfd" width=".986" height="1.04" x="13.83" y="10.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".1"/></filter><filter id="iyIwsle" width=".912" height=".704" x="13.075" y="10.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".05"/></filter><filter id="i4bayod" width="2.661" height="1.378" x="17.424" y="8.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".2"/></filter><filter id="iuLUSwd" width="2.661" height="1.378" x="11.973" y="8.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".2"/></filter><filter id="ifp4XOb" width="4.985" height="5.214" x="9.277" y="4.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".375"/></filter><filter id="iljLWZU" width="8.914" height="5.78" x="12.668" y="3.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".125"/></filter><filter id="ih3UGlb" width="1.145" height="2.31" x="12.794" y="4.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2091" stdDeviation=".125"/></filter><linearGradient id="iXIU87V" x1="20.678" x2="13.437" y1="4.378" y2="17.821" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="inwFO8c" x1="16" x2="16" y1="16.279" y2="31.217" gradientUnits="userSpaceOnUse"><stop class="aj_3f3bsc"/><stop offset="1" class="wnr_hxb1w"/></linearGradient><linearGradient id="iSbbKnb" x1="18.903" x2="17.059" y1="25.279" y2="25.279" gradientUnits="userSpaceOnUse"><stop class="ugh29hhiz"/><stop offset="1" class="knib4pb5u"/></linearGradient><linearGradient id="i1fHkvc" x1="15.591" x2="15.669" y1="17.826" y2="21.716" gradientUnits="userSpaceOnUse"><stop class="ft2atdbel"/><stop offset="1" class="r8964-bmu"/></linearGradient><linearGradient id="ioVp6re" x1="23" x2="23.744" y1="29.454" y2="29.431" gradientUnits="userSpaceOnUse"><stop offset=".276" class="alwwvg18b"/><stop offset="1" class="r8-nbsf4i"/></linearGradient><linearGradient id="iCo4Qkc" x1="11.902" x2="11.902" y1="16.057" y2="29.957" gradientUnits="userSpaceOnUse"><stop class="f3sse8oum"/><stop offset=".524" class="u_3z34bhk"/></linearGradient><linearGradient id="ioH3sab" x1="13.671" x2="13.05" y1="22.517" y2="22.517" gradientUnits="userSpaceOnUse"><stop class="ihv8a_ggy"/><stop offset="1" class="btkjyionj"/></linearGradient><linearGradient id="iL6RgQb" x1="11.902" x2="12.839" y1="25.933" y2="25.532" gradientUnits="userSpaceOnUse"><stop offset=".196" class="k61ntrncu"/><stop offset="1" class="c8t-c_brq"/></linearGradient><linearGradient id="i2cdaBb" x1="12.223" x2="12.434" y1="16.057" y2="16.459" gradientUnits="userSpaceOnUse"><stop class="po-lo7b_p"/><stop offset="1" class="un5vu3b4v"/></linearGradient><linearGradient id="iPDH77J" x1="15.988" x2="15.988" y1="18.951" y2="20.935" gradientUnits="userSpaceOnUse"><stop offset=".006" class="cv8mglbzi"/><stop offset="1" class="s7ujjhbeb"/></linearGradient><linearGradient id="ixVJ9ed" x1="18.71" x2="20.111" y1="21.564" y2="21.564" gradientUnits="userSpaceOnUse"><stop offset=".093" class="d4aenlb5d"/><stop offset="1" class="zm9c_pbne"/></linearGradient><linearGradient id="iB7Bwsb" x1="9.452" x2="7.02" y1="23.975" y2="23.975" gradientUnits="userSpaceOnUse"><stop class="qv0c6ccxx"/><stop offset="1" class="ox2qw0bwk"/></linearGradient><linearGradient id="iEB3aZs" x1="14.606" x2="14.899" y1="24.837" y2="24.877" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iY6QOvc" x1="17.411" x2="17.012" y1="24.654" y2="24.701" gradientUnits="userSpaceOnUse"><stop class="jybxgogov"/><stop offset="1" class="rop63gbyj"/></linearGradient><linearGradient id="iGErC6b" x1="9.69" x2="12.65" y1="11.418" y2="11.418" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i67vQNe" x1="15.985" x2="15.985" y1="13.369" y2="10.687" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iDKzkRd" x1="14.939" x2="15.793" y1="12.607" y2="12.711" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iIWkCwc" x1="15.985" x2="15.985" y1="13.461" y2="12.851" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="ipLZwZd" x1="16.063" x2="16.063" y1="13.435" y2="13.295" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iUZK7td" x1="15.256" x2="15.709" y1="14.938" y2="14.066" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="icFAZKd" x1="18.945" x2="18.631" y1="10.787" y2="10.98" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4MF9mW" x1="14.546" x2="14.233" y1="10.787" y2="10.981" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihfv5Nd" x1="13.094" x2="13.639" y1="5.132" y2="6.406" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-office-worker" /></template>
<style>
.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.aj_3f3bsc {
  stop-color: var(--svg-color--594e72, #594E72);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.alwwvg18b {
  stop-color: var(--svg-color--504176, #504176);
}

.b7pb6h2yx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.103 10.446c.063.084-.07.188-.22.3c-.151.114-.263.193-.327.108s.007-.245.158-.358s.325-.136.389-.05");
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bc14ocbhb {
  d: path("M16 15.024h-2.71v4.74c0 .31.36.49.61.29l2.1-1.392l2.1 1.392c.25.2.61.02.61-.29v-4.74z");
}

.bnmbk2bak {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.812 12.405a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.btkjyionj {
  stop-color: var(--svg-color--553a63, #553A63);
  stop-opacity: 0;
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c8t-c_brq {
  stop-color: var(--svg-color--594c7d, #594C7D);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cv8mglbzi {
  stop-color: var(--svg-color--5a3859, #5A3859);
}

.d4aenlb5d {
  stop-color: var(--svg-color--5a4c74, #5A4C74);
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dgb3odblg {
  fill: var(--svg-color--493e6a, #493E6A);
  d: path("m20.905 21.149l-1.19-.828a.23.23 0 0 1 .166-.394h.919a.252.252 0 0 0 .227-.358l-1.076-2.29a8 8 0 0 0-.646-.237h-.595v11.862l2.404-6.872a.85.85 0 0 0-.21-.883");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dvodlmrev {
  d: path("M11.3 12.94a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.dxjunq6hh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.094 4.789c.023.243.234 1.156.545 1.71");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.exvucxbiq {
  d: path("M18.71 16.087h-5.42v13.89h5.42z");
}

.ezus362fm {
  d: path("M14.045 16.857c.02.214.205.691.746 1.055c.214.143 1.213.629 1.193.619c.156-.078.807-.299 1.284-.62c.54-.363.725-.84.746-1.054l-1.985-.953z");
}

.f3sse8oum {
  stop-color: var(--svg-color--594b78, #594B78);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.frd709bmb {
  cx: 13.531px;
  cy: 10.638px;
  rx: 0.389px;
  ry: 0.197px;
}

.ft2atdbel {
  stop-color: var(--svg-color--877f93, #877F93);
}

.ft5dv1b6b {
  fill: none;
}

.g1k32m_rh {
  stop-color: var(--svg-color--6d6193, #6D6193);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gehjzqbem {
  d: path("M16 15.468c-6.08 0-11 4.92-11 11v3.5h22v-3.5c0-6.07-4.93-11-11-11");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gkzmut59n {
  stop-color: var(--svg-color--a89cb3, #A89CB3);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gwnkbobks {
  d: path("M20.812 12.405a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h5csvdbob {
  d: path("M13.8 10.257a.892.892 0 0 0-.86 1.127h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.i_25dj3ib {
  stop-color: var(--svg-color--a093a3, #A093A3);
}

.i1uneh2yx {
  stop-color: var(--svg-color--4e3360, #4E3360);
}

.i9_d89eoz {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.925 8.958c.322-.078 1.124-.04 1.66.345");
}

.ihv8a_ggy {
  stop-color: var(--svg-color--553a63, #553A63);
}

.ipahq80uz {
  d: path("M20.812 12.94a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.iqpcekpgv {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.594 9.985c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.ium-0_blv {
  stop-color: var(--svg-color--59416d, #59416D);
}

.iw5474bga {
  stop-color: var(--svg-color--4e3360, #4E3360);
  stop-opacity: 0;
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.jd6sgdbgc {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.587 13.854a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.042c-.405.216-.881.34-1.399.34a3 3 0 0 1-1.398-.34Z");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jkl2w9b2m {
  d: path("M15.505 21.077a.25.25 0 0 0-.247.212l-1.328 8.668h4.11l-1.318-8.667a.25.25 0 0 0-.247-.213z");
}

.jybxgogov {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
}

.k47980b8l {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.717 9.095l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 0 1-.093-.528c.513-.091.988 0 1.328.109a3.3 3.3 0 0 1 .526.22l.033.018l.009.006z");
}

.k4m36ubhf {
  d: path("m15.603 10.97l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.646-.377-.765 0");
}

.k61ntrncu {
  stop-color: var(--svg-color--594c7d, #594C7D);
}

.k805m1ibf {
  d: path("M11.319 12.405a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.kldoqgb-g {
  d: path("M11.09 5.317c.622-.553 1.518-.559 2.02-.47l.403 1.291c-.257-.039-.486.05-.679.235c-.456 1.26-2.022 1.955-2.749 2.145c-.15-1.492-.067-2.246 1.006-3.201");
}

.knib4pb5u {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.l51wizbrd {
  d: path("M7.032 29.968H8.97V18.003a11 11 0 0 0-3.656 5.843a11 11 0 0 0-.304 2.632l.02 3.49z");
}

.l8zvg3bgw {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.587 9.553l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.002l.01-.006a2 2 0 0 1 .148-.077c.098-.046.239-.107.41-.161c.34-.109.815-.2 1.328-.11a.268.268 0 1 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m5bm-ccxd {
  stop-color: var(--svg-color--7b74a6, #7B74A6);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.n7fzr7bxu {
  stop-color: var(--svg-color--dd8931, #DD8931);
}

.n7z_7vb8n {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.127 10.762c.266-.467.67-.836 1.538-.836c.38 0 .746.106 1.072.369c.27.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.079-.45");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.no15wbb0w {
  d: path("M18.964 11.031a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.ntn842bmo {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.134 8.958c-.323-.078-1.125-.04-1.661.345");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o3zwgyjdz {
  d: path("M14.616 11.044c0-.288-.235-.48-.298-.538l-.288.278l.177.361z");
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.oc7zcid3t {
  cx: 13.531px;
  cy: 10.638px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omh3jbc5e {
  stop-color: var(--svg-color--776d9f, #776D9F);
}

.ox2qw0bwk {
  stop-color: var(--svg-color--43395f, #43395F);
  stop-opacity: 0;
}

.p-fyq_ugo {
  d: path("M18.17 10.257a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p5prc9btx {
  fill: var(--svg-color--46375f, #46375F);
  d: path("M13.419 16.816c-.513 0-1.296-.029-1.77.166l-1.38 2.724c-.09.19.06.41.27.41h1.55c.24 0 .35.29.19.45l-1.78 1.343c-.26.26-.36.65-.23 1l2.912 6.5l1.587-1.116l-1.34-11.477z");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pc2b66ykc {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po-lo7b_p {
  stop-color: var(--svg-color--584360, #584360);
}

.po0u5abxc {
  stop-color: var(--svg-color--9d8392, #9D8392);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q8ootib3t {
  stop-color: var(--svg-color--5f5490, #5F5490);
  stop-opacity: 0;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qv0c6ccxx {
  stop-color: var(--svg-color--43395f, #43395F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.qxb2v1b0l {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.376 9.985c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.r8-nbsf4i {
  stop-color: var(--svg-color--504176, #504176);
  stop-opacity: 0;
}

.r8964-bmu {
  stop-color: var(--svg-color--877f93, #877F93);
  stop-opacity: 0;
}

.rddl0jhjv {
  stop-color: var(--svg-color--a85f21, #A85F21);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rkd_cludi {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.843 10.762c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.369c-.269.217-.233.495-.025.6l.556.317c.652-.211 1.373-.24 2.08-.45");
}

.rop63gbyj {
  stop-color: var(--svg-color--2b1b3a, #2B1B3A);
  stop-opacity: 0;
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s3tb_6b2n {
  stop-color: var(--svg-color--3d3247, #3D3247);
}

.s5m4o5b4y {
  fill: var(--svg-color--000, #000);
  d: path("M17.658 11.15c0-.285.227-.512.511-.512a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.s7ujjhbeb {
  stop-color: var(--svg-color--463952, #463952);
}

.s80u955fl {
  stop-color: var(--svg-color--815a72, #815A72);
}

.si9pdx_tq {
  d: path("m21.22 21.088l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.som6k-b6q {
  stop-color: var(--svg-color--4b3b6d, #4B3B6D);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.syiaie9zn {
  fill: var(--svg-color--000, #000);
  d: path("M14.312 11.15a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.t7e_55bck {
  d: path("M18.103 10.446c.063.084-.07.188-.22.3c-.151.114-.263.193-.327.108s.007-.245.158-.358s.325-.136.389-.05");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tlsqvlb-h {
  fill: var(--svg-color--615990, #615990);
  d: path("m21.22 21.088l-1.36-1.33a.262.262 0 0 1 .19-.45h1.05c.21 0 .35-.22.26-.41l-1.23-2.62c-.24-.1-.49-.19-.74-.27h-.68v13.95l2.75-7.86c.12-.36.03-.75-.24-1.01");
}

.tm9wsybrf {
  fill-rule: evenodd;
  d: path("M23.17 12.74c.213-.435.324-.92.324-1.426c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.77V7.71a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233h-.085A3.3 3.3 0 0 0 9.549 7.71v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.52.52 0 0 1 0-.455m-12.26-2.672h-.012l1.199 2.356c.123 2.802 1.217 0 3.888 0s3.836 3.12 3.96.317l1.136-3.198c-.054-1.244-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.241 1.255l-.051.02c-.236.123-.79.49-.81 1.439l.01.306z");
}

.tta7y0bsf {
  d: path("M10.898 10.068h.012l-.01-.265l-.01-.306c.02-.949.574-1.316.81-1.439l.05-.02l.052-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.088 1.135 1.332l-.118 3.074c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.u_3z34bhk {
  stop-color: var(--svg-color--5d5087, #5D5087);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ugh29hhiz {
  stop-color: var(--svg-color--7a6c85, #7A6C85);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.un5vu3b4v {
  stop-color: var(--svg-color--584360, #584360);
  stop-opacity: 0;
}

.uzsgus-sl {
  d: path("M15.382 3.54c-1.133-.25-2.347.956-2.464 1.375c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.175 1.743.542 1.877.888c-.436-4.056-3.37-4.676-5.95-5.246");
}

.v_7iv29di {
  d: path("m16.013 18.295l-1.357 1.275a.15.15 0 0 0-.031.176l.596 1.193a.25.25 0 0 0 .224.139h1.09a.25.25 0 0 0 .224-.14l.6-1.212a.15.15 0 0 0-.032-.175z");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vlp0azbmu {
  d: path("M13.29 16.057h-.85c-.18.06-.36.13-.53.2l-1.27 2.69c-.09.19.06.41.27.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01v-13.9z");
}

.vo0pp4boh {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.592 11.108l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wdy63qb5p {
  stop-color: var(--svg-color--c6bbd1, #C6BBD1);
}

.wnr_hxb1w {
  stop-color: var(--svg-color--594984, #594984);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.xc6znrbjq {
  d: path("M23 17.985v11.982h4v-3.5a10.98 10.98 0 0 0-4-8.482");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ye9_1e9lc {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.319 12.405a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.zm9c_pbne {
  stop-color: var(--svg-color--625a91, #625A91);
  stop-opacity: 0;
}

.zr8leoe3h {
  stop-color: var(--svg-color--cdbed0, #CDBED0);
}

</style>
