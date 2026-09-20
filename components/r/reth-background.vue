<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path clip-rule="evenodd" class="rpmv0-b-z"/><path fill="url(#SVGqNnwucSa)" clip-rule="evenodd" class="qj7nlabpp"/><path clip-rule="evenodd" class="par8abc2n"/><path clip-rule="evenodd" class="kmp7zs9dj"/><path fill="url(#SVGLqcIRdlg)" class="efeft5p8d"/><path clip-rule="evenodd" class="a6a8vh8nt"/><path fill="url(#SVGTKJMjeQX)" class="kw8421byq"/><path fill="url(#SVGSEHwUpOe)" class="q-dnrcbjz"/><path fill="url(#SVGttbwDdid)" class="iw1c6mb5o"/><path fill="url(#SVGI2txrcXi)" class="qxzg9rpvt"/><path fill="url(#SVGXxCl1dlX)" class="afu7obc-n"/><path fill="url(#SVGvkkSWdCz)" class="q7sqd6pnm"/><path fill="url(#SVGq5uJPOFK)" class="c_qh55j3z"/><path fill="url(#SVGL7amuetd)" class="nw-kgsxkt"/><path fill="url(#SVG6rXNcbUz)" class="zwr0lzbxv"/><path fill="url(#SVG7VgBHe7D)" class="fjn194esq"/><path fill="url(#SVGKr0RnbFV)" class="eilhgf7zx"/><path class="dzlxnlbuf"/><path class="dvz29acky"/><path class="h0lf4kbjp"/><path class="apiwogb_j"/><path class="x7kg5nwsi"/><path fill="url(#SVGTXm1Xc5G)" class="v13f_kb4w"/></g><defs><linearGradient id="SVGqNnwucSa" x1="11.737" x2="11.737" y1="3.742" y2="19.742" gradientUnits="userSpaceOnUse"><stop class="gq9xn01ji"/><stop offset=".3" class="v1jyzci4m"/><stop offset=".7" class="hv4npjfgx"/><stop offset="1" class="tdf9axzpj"/></linearGradient><linearGradient id="SVGLqcIRdlg" x1="7.807" x2="15.321" y1="5.367" y2="19.221" gradientUnits="userSpaceOnUse"><stop class="cx0hsrbhp"/><stop offset="1" class="sy75bsbjq"/></linearGradient><linearGradient id="SVGTKJMjeQX" x1="15.547" x2="1.253" y1="6.493" y2="18.224" gradientUnits="userSpaceOnUse"><stop class="r0g1zf_9a"/><stop offset=".95" class="ji6429byj"/></linearGradient><linearGradient id="SVGSEHwUpOe" x1="19.286" x2="12.006" y1="5.074" y2="14.632" gradientUnits="userSpaceOnUse"><stop class="no6rv2ber"/><stop offset=".95" class="ln3lonb6h"/></linearGradient><linearGradient id="SVGttbwDdid" x1="7.969" x2="8.486" y1="12.046" y2="15.472" gradientUnits="userSpaceOnUse"><stop class="nsabh775t"/><stop offset=".95" class="ofjokpbtz"/></linearGradient><linearGradient id="SVGI2txrcXi" x1="11.43" x2="19.06" y1="12.157" y2="8.135" gradientUnits="userSpaceOnUse"><stop class="nsabh775t"/><stop offset=".4" class="ihb-bebsy"/><stop offset=".64" class="hvfzhchqy"/><stop offset=".95" class="yeqfabxni"/></linearGradient><linearGradient id="SVGXxCl1dlX" x1="8.201" x2="22.433" y1="6.587" y2="18.689" gradientUnits="userSpaceOnUse"><stop class="r0g1zf_9a"/><stop offset=".95" class="ji6429byj"/></linearGradient><linearGradient id="SVGvkkSWdCz" x1="4.369" x2="11.688" y1="5.211" y2="14.931" gradientUnits="userSpaceOnUse"><stop class="no6rv2ber"/><stop offset=".95" class="ln3lonb6h"/></linearGradient><linearGradient id="SVGq5uJPOFK" x1="15.392" x2="14.877" y1="12.092" y2="15.556" gradientUnits="userSpaceOnUse"><stop class="nsabh775t"/><stop offset=".95" class="ofjokpbtz"/></linearGradient><linearGradient id="SVGL7amuetd" x1="12.402" x2="4.654" y1="12.308" y2="8.154" gradientUnits="userSpaceOnUse"><stop class="nsabh775t"/><stop offset=".4" class="ihb-bebsy"/><stop offset=".64" class="hvfzhchqy"/><stop offset=".95" class="yeqfabxni"/></linearGradient><linearGradient id="SVG6rXNcbUz" x1="14.496" x2="10.008" y1="4.365" y2="20.951" gradientUnits="userSpaceOnUse"><stop class="sn332yd3w"/><stop offset=".3" class="h1ql3_tya"/><stop offset=".66" class="e_gjpjbgc"/><stop offset="1" class="l8t11kb4v"/></linearGradient><linearGradient id="SVG7VgBHe7D" x1="14.279" x2="9.402" y1="4.365" y2="20.713" gradientUnits="userSpaceOnUse"><stop class="sn332yd3w"/><stop offset=".3" class="h1ql3_tya"/><stop offset=".66" class="e_gjpjbgc"/><stop offset="1" class="l8t11kb4v"/></linearGradient><linearGradient id="SVGKr0RnbFV" x1="16.224" x2="11.605" y1="4.365" y2="20.873" gradientUnits="userSpaceOnUse"><stop class="sn332yd3w"/><stop offset=".3" class="h1ql3_tya"/><stop offset=".66" class="e_gjpjbgc"/><stop offset="1" class="l8t11kb4v"/></linearGradient><linearGradient id="SVGTXm1Xc5G" x1="8.603" x2="6.961" y1="10.268" y2="13.552" gradientUnits="userSpaceOnUse"><stop class="guvp-bbvy"/><stop offset=".48" class="dsqll7qko"/><stop offset="1" class="i1hl6dp0g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:reth-background" /></template>
<style>
.a6a8vh8nt {
  fill: var(--svg-color--7c734d, #7c734d);
  fill-rule: evenodd;
  d: path("M11.623 7.03c-.084-.07-.404-.193-.945-.14c-.678.07-1.836.762-1.765 2c.019.31.094.573.197.8a.4.4 0 0 1-.127.027l-.136.005c-.24.01-.598.028-.541-.141c.051-.165.155-.07.202 0c.066-.07.16-.25 0-.414c-.165-.165-.428.023-.541.141c-.094-.047-.301-.099-.41.066s.095.343.203.414c-.066.16-.132.494.141.55c.268.057.334-.07.334-.14c-.09-.02-.259-.095-.202-.203c.066-.141.136-.207.273-.07l.127.155c.103.141.226.301.414.395c.216.113.725.141.95.141v-.14l.132.07l.07-.07a2.4 2.4 0 0 1-.714-.768c.315-.16.767-.381 1.054-.334c.329.056.498.113.54.141l.071-.282a2 2 0 0 0-.545-.066c-.189 0-.551.174-.871.33l-.292.136a1.6 1.6 0 0 1-.188-.744c0-.094.023-.273.132-.273c.136 0 .273.066.202.141a1 1 0 0 1-.202.132c.066.094.23.264.339.207a1.6 1.6 0 0 0 .244-.207c.193-.183.438-.414.565-.414c.207 0 .207.282.07.282a.3.3 0 0 1-.202-.075c.024.07.094.207.203.207c.14 0 .273-.136.273-.343s-.203-.414-.471-.414c0-.024-.047-.066-.207-.066c-.165 0-.339.183-.41.273c-.014-.047-.108-.123-.338-.066c.094-.236.367-.706.748-.763c.188-.023.339 0 .447.024c.16.033.23.047.23-.16c.292-.175.615-.292.951-.344zM9.157 9.774c-.075.038-.136.07-.174.08c-.164.056-.433.023-.546 0c.095.094.33.32.546.485c.189.14.537.122.74.085a1.8 1.8 0 0 1-.566-.65m3.285-2.8c.09-.066.405-.188.946-.141c.678.075 1.835.762 1.765 2.004a2.1 2.1 0 0 1-.198.796a.4.4 0 0 0 .132.028l.132.005c.24.014.597.028.546-.141c-.057-.165-.16-.071-.208 0c-.065-.071-.16-.25 0-.415c.165-.164.433.024.546.142c.09-.047.297-.1.405.065s-.094.344-.202.415c.066.16.136.494-.137.55s-.339-.066-.339-.141c.095-.019.26-.094.203-.202c-.066-.142-.137-.207-.268-.071a1 1 0 0 0-.128.155c-.103.142-.225.302-.418.396c-.217.113-.72.14-.946.14v-.14l-.141.07l-.066-.07c.193-.123.503-.396.715-.763c-.315-.164-.767-.386-1.054-.339c-.325.057-.494.118-.541.142l-.066-.283a2 2 0 0 1 .54-.066c.19 0 .556.175.872.33c.103.047.207.094.291.141c.118-.226.193-.47.193-.744c0-.094-.028-.277-.136-.277c-.137 0-.268.07-.203.141c.057.052.16.113.203.136c-.066.095-.23.26-.339.208a2 2 0 0 1-.245-.212c-.193-.184-.437-.41-.564-.41c-.207 0-.207.273-.071.273a.33.33 0 0 0 .202-.066c-.023.066-.094.207-.202.207c-.136 0-.273-.14-.273-.348s.202-.41.475-.41c0-.023.043-.07.203-.07c.164 0 .338.184.41.273c.018-.047.107-.122.338-.066c-.094-.23-.367-.706-.748-.757c-.189-.029-.34 0-.447.018c-.16.033-.23.048-.23-.16a2.6 2.6 0 0 0-.947-.343m2.47 2.748q.108.058.175.08c.16.052.423.024.541 0c-.094.094-.33.316-.541.48c-.193.146-.537.127-.744.085a1.8 1.8 0 0 0 .565-.645zM10.34 12.82c-.137.367-.542 1.092-1.083 1.035a.8.8 0 0 1-.41-.17v-.037H8.8a1.84 1.84 0 0 1-.494-.828a4 4 0 0 0-.367 1.355a1.53 1.53 0 0 1-.523-.56l-.122.061c.094.188.301.452.64.659c-.01.65.221 1.29.979 1.586c1.412.55 2.17.047 2.376-.273c-.113.094-.367.245-.475.136c-.141-.14-.202-.277 0-.484l-.202-.344c-.16.047-.49.085-.546-.141c-.052-.216.07-.457.14-.546c-.206.066-.587.259-.48.48l.203.278c-.047.047-.108.178 0 .343a.31.31 0 0 0 .339.141c-.047.09-.052.302.273.41c-.047.047-.202.141-.47.141c-.274 0-.754-.555-.951-.828c-.273 0-.941-.203-1.017-.81c.344.165.8.264 1.365.189l.254-.033l-.24-.1a1.3 1.3 0 0 1-.4-.281a.86.86 0 0 1-.221-.415a.7.7 0 0 0 .39.142c.476 0 .951-.283 1.083-1.106zm-1.633.851a1.8 1.8 0 0 1-.405-.508s-.235.532-.216 1.101c.287.15.663.255 1.134.236a1.4 1.4 0 0 1-.236-.207a.94.94 0 0 1-.277-.622m4.955-.78c.136.366.541 1.086 1.082 1.035a.8.8 0 0 0 .41-.175v-.033h.047c.268-.235.433-.611.494-.828c.165.339.33.843.367 1.356c.273-.189.447-.405.522-.56l.123.06a1.76 1.76 0 0 1-.64.66c.01.649-.221 1.289-.98 1.586c-1.41.55-2.168.047-2.376-.278c.113.094.367.25.476.141c.14-.141.202-.278 0-.485l.202-.343c.16.047.49.08.546-.141c.052-.217-.07-.457-.141-.551c.207.07.588.264.48.485l-.203.273c.047.047.109.183 0 .348a.3.3 0 0 1-.338.136c.047.094.051.301-.273.415c.047.047.202.14.47.14c.273 0 .753-.555.95-.832c.274 0 .942-.203 1.017-.805c-.343.165-.8.259-1.364.188l-.255-.037l.24-.095c.104-.046.269-.14.4-.282a.86.86 0 0 0 .222-.414a.7.7 0 0 1-.391.141c-.475 0-.95-.282-1.082-1.106zm1.628.846c.18-.15.325-.348.405-.503c0 0 .235.527.216 1.101c-.287.15-.663.254-1.134.23c.08-.051.165-.122.236-.202a.94.94 0 0 0 .282-.62z");
}

.afu7obc-n {
  d: path("m13.647 9.646l1.492 2.212l-2.904-1.27z");
}

.apiwogb_j {
  fill: var(--svg-color--e3f7f3, #e3f7f3);
  d: path("M11.999 16.985v-.749l.47.749z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.c_qh55j3z {
  d: path("M12.235 10.354V7.06l1.177 2.353z");
}

.cx0hsrbhp {
  stop-color: var(--svg-color--58453d, #58453d);
}

.dsqll7qko {
  stop-color: var(--svg-color--b6f2fa, #b6f2fa);
}

.dvz29acky {
  fill: var(--svg-color--e3f7f3, #e3f7f3);
  d: path("M11.999 7.102v-.748l.47.748z");
}

.dzlxnlbuf {
  fill: var(--svg-color--21f0ee, #21f0ee);
  d: path("m11.528 7.102l.47-.748v.748z");
}

.e_gjpjbgc {
  stop-color: var(--svg-color--bce9f5, #bce9f5);
}

.efeft5p8d {
  d: path("M12 17.648a5.647 5.647 0 1 0 0-11.294a5.647 5.647 0 0 0 0 11.294");
}

.eilhgf7zx {
  d: path("M14.118 10.117H11.83l-.146.753c.07-.056.376-.282.55-.282c.179 0 .236.16.236.282v2.094c0 .18-.189.377-.236.447h1.412c-.118-.117-.235-.371-.235-.47v-2.094c0-.024.06-.26.235-.26c.179 0 .273.227.325.283z");
}

.fjn194esq {
  d: path("M15.483 10.117h-1.271c.113 0 .141.301.141.447v2.47a.58.58 0 0 1-.141.377h1.27a.42.42 0 0 1-.188-.3v-1.112h.941v1.111c0 .184-.14.25-.188.301h1.27c-.14 0-.14-.197-.14-.3v-2.542c0-.24.094-.4.14-.452H16.02c.15 0 .221.301.216.447v.965h-.94v-.965c0-.117.14-.348.188-.447");
}

.ft5dv1b6b {
  fill: none;
}

.gq9xn01ji {
  stop-color: var(--svg-color--b0a494, #b0a494);
}

.guvp-bbvy {
  stop-color: var(--svg-color--f0f2f6, #f0f2f6);
}

.h0lf4kbjp {
  fill: var(--svg-color--21f0ee, #21f0ee);
  d: path("M11.999 7.102h-.47l.47.663zm.47 0H12v.663zm-.94 9.882l.47-.748v.748z");
}

.h1ql3_tya {
  stop-color: var(--svg-color--f4f4f3, #f4f4f3);
}

.hv4npjfgx {
  stop-color: var(--svg-color--492b21, #492b21);
}

.hvfzhchqy {
  stop-color: var(--svg-color--9fc4ed, #9fc4ed);
}

.i1hl6dp0g {
  stop-color: var(--svg-color--4e89c9, #4e89c9);
}

.ihb-bebsy {
  stop-color: var(--svg-color--453d51, #453d51);
}

.iw1c6mb5o {
  d: path("M11.765 10.354V7.06L10.59 9.413z");
}

.ji6429byj {
  stop-color: var(--svg-color--4f5665, #4f5665);
}

.kmp7zs9dj {
  fill: var(--svg-color--f3f7f9, #f3f7f9);
  fill-rule: evenodd;
  d: path("M11.968 17.826a5.856 5.856 0 0 0 5.859-5.86A5.857 5.857 0 0 0 7.825 7.825a5.859 5.859 0 0 0 4.143 10.002m0 .14a6 6 0 1 0 0-11.998a6 6 0 0 0 0 11.999");
}

.kw8421byq {
  d: path("m10.353 9.646l-1.497 2.175l2.909-1.233z");
}

.l8t11kb4v {
  stop-color: var(--svg-color--5283b8, #5283b8);
}

.ln3lonb6h {
  stop-color: var(--svg-color--5a5a70, #5a5a70);
}

.no6rv2ber {
  stop-color: var(--svg-color--666c76, #666c76);
}

.nsabh775t {
  stop-color: var(--svg-color--95a4c2, #95a4c2);
}

.nw-kgsxkt {
  d: path("m12.235 14.589l2.904-1.454l-2.904 4.042z");
}

.ofjokpbtz {
  stop-color: var(--svg-color--73788c, #73788c);
}

.par8abc2n {
  fill: var(--svg-color--04eef0, #04eef0);
  fill-rule: evenodd;
  d: path("M12 17.975a5.978 5.978 0 0 0 4.227-10.202a5.98 5.98 0 0 0-8.453 0a5.976 5.976 0 0 0 4.227 10.202m0 .141A6.118 6.118 0 1 0 12 5.88a6.118 6.118 0 0 0 0 12.236");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-dnrcbjz {
  d: path("m11.765 10.823l-3.059 1.35l3.059 1.944z");
}

.q7sqd6pnm {
  d: path("m12.235 10.823l3.06 1.388l-3.06 1.906z");
}

.qj7nlabpp {
  fill-rule: evenodd;
  d: path("M12.005 18.593a6.592 6.592 0 1 0 0-13.184a6.592 6.592 0 0 0 0 13.184m0 .701a7.294 7.294 0 1 0 0-14.587a7.294 7.294 0 0 0 0 14.587");
}

.qxzg9rpvt {
  d: path("m11.765 14.588l-2.909-1.491l2.909 4.08z");
}

.r0g1zf_9a {
  stop-color: var(--svg-color--7e93cd, #7e93cd);
}

.rpmv0-b-z {
  fill: var(--svg-color--04eef0, #04eef0);
  fill-rule: evenodd;
  d: path("M12 19.53A7.49 7.49 0 0 0 19.53 12A7.49 7.49 0 0 0 12 4.47A7.49 7.49 0 0 0 4.47 12A7.49 7.49 0 0 0 12 19.53m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.sn332yd3w {
  stop-color: var(--svg-color--f7f9f5, #f7f9f5);
}

.sy75bsbjq {
  stop-color: var(--svg-color--3b2a23, #3b2a23);
}

.tdf9axzpj {
  stop-color: var(--svg-color--301d17, #301d17);
}

.v13f_kb4w {
  d: path("M6.683 10.117h1.764c.353 0 .73.282.73.941c0 .66-.33.782-.518.782l.988 1.571h-.81c-.084-.023-.305-.164-.53-.522a17 17 0 0 0-.344-.522l-.198-.302v1.045a.8.8 0 0 0 .226.301H6.683c.047-.075.14-.235.14-.3v-2.693c0-.103-.027-.3-.14-.3m1.082.522v1.12c.188-.047.602-.235.602-.597c0-.447-.39-.518-.602-.518z");
}

.v1jyzci4m {
  stop-color: var(--svg-color--5e473c, #5e473c);
}

.x7kg5nwsi {
  fill: var(--svg-color--21f0ee, #21f0ee);
  d: path("M12 16.984h-.471l.47.663zm.47 0H12v.663zm-1.647-7.572h-.47v.47h.47zm2.824 0h-.471v.47h.47zm-1.177 5.412l-.47-.47l-.471.47l.47.47z");
}

.yeqfabxni {
  stop-color: var(--svg-color--7087cb, #7087cb);
}

.zwr0lzbxv {
  d: path("M11.558 10.117h-1.91c.235 0 .235.264.235.362v2.697c0 .118-.09.188-.16.235h1.981l.296-.706c-.117.18-.376.212-.47.236h-.706v-.942h.56c.118 0 .146.08.146.128v-.598h-.706v-.941h.442c.174 0 .268.127.292.202z");
}

</style>
