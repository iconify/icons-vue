<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG6aMCGecB)" class="mgumy1b7g"/><path fill="url(#SVGeKkRCdCu)" class="woxwkkb3d"/><path fill="url(#SVG3MNZkc2o)" class="s04k3mb2a"/><path fill="url(#SVGXa2mCbbh)" class="hmadrzbpp"/><path fill="url(#SVGLJZWgeqN)" class="cek-lckbv"/><path fill="url(#SVGHmsCIc1S)" class="o7vlolb8j"/><path fill="url(#SVGnjjqmeYe)" class="kegd1xb-o"/><path fill="url(#SVGqSDpEbUi)" class="jqsuxkbba"/><path fill="url(#SVGhtetubdI)" class="ss5x8rumn"/><path fill="url(#SVGg2p8E7OL)" class="ww47cubwh"/><path fill="url(#SVGKIp20bsj)" class="q32lyn9dm"/><path fill="url(#SVGI8jLTdia)" class="as9djwb1c"/><path fill="url(#SVGYFixMdDs)" class="xxkzupb3l"/><path fill="url(#SVGAOXSDdCP)" class="pnfw-pbva"/><path fill="url(#SVGOvBDHdUI)" class="yimrx5bzs"/><defs><linearGradient id="SVG6aMCGecB" x1="10.407" x2="10.407" y1="6.818" y2="4.335" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".07" class="yi4nh_lsa"/><stop offset=".35" class="v26knx77k"/><stop offset=".6" class="o7fmrupzg"/><stop offset=".83" class="mau_2wn0d"/><stop offset=".99" class="fot6-kuzk"/></linearGradient><linearGradient id="SVGeKkRCdCu" x1="13.594" x2="13.594" y1="6.925" y2="4.291" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".07" class="yi4nh_lsa"/><stop offset=".35" class="v26knx77k"/><stop offset=".6" class="o7fmrupzg"/><stop offset=".83" class="mau_2wn0d"/><stop offset=".99" class="fot6-kuzk"/></linearGradient><linearGradient id="SVG3MNZkc2o" x1="6.486" x2="10.883" y1="6.252" y2="3.584" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".23" class="x2yhn4b5g"/><stop offset=".53" class="afzcutzat"/><stop offset=".79" class="glev2oems"/><stop offset=".99" class="r__y4nmfe"/></linearGradient><linearGradient id="SVGXa2mCbbh" x1="17.545" x2="13.431" y1="6.141" y2="3.823" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".23" class="x2yhn4b5g"/><stop offset=".53" class="afzcutzat"/><stop offset=".79" class="glev2oems"/><stop offset=".99" class="r__y4nmfe"/></linearGradient><linearGradient id="SVGLJZWgeqN" x1="8.26" x2="6.091" y1="15.874" y2="17.147" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".07" class="yi4nh_lsa"/><stop offset=".35" class="v26knx77k"/><stop offset=".6" class="o7fmrupzg"/><stop offset=".83" class="mau_2wn0d"/><stop offset=".99" class="fot6-kuzk"/></linearGradient><linearGradient id="SVGHmsCIc1S" x1="6.76" x2="4.459" y1="13.107" y2="14.457" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".07" class="yi4nh_lsa"/><stop offset=".35" class="v26knx77k"/><stop offset=".6" class="o7fmrupzg"/><stop offset=".83" class="mau_2wn0d"/><stop offset=".99" class="fot6-kuzk"/></linearGradient><linearGradient id="SVGnjjqmeYe" x1="9.721" x2="5.247" y1="19.495" y2="16.953" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".23" class="x2yhn4b5g"/><stop offset=".53" class="afzcutzat"/><stop offset=".79" class="glev2oems"/><stop offset=".99" class="r__y4nmfe"/></linearGradient><linearGradient id="SVGqSDpEbUi" x1="4.094" x2="4.175" y1="10.134" y2="14.795" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".23" class="x2yhn4b5g"/><stop offset=".53" class="afzcutzat"/><stop offset=".79" class="glev2oems"/><stop offset=".99" class="r__y4nmfe"/></linearGradient><linearGradient id="SVGhtetubdI" x1="17.334" x2="19.503" y1="13.16" y2="14.433" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".07" class="yi4nh_lsa"/><stop offset=".35" class="v26knx77k"/><stop offset=".6" class="o7fmrupzg"/><stop offset=".83" class="mau_2wn0d"/><stop offset=".99" class="fot6-kuzk"/></linearGradient><linearGradient id="SVGg2p8E7OL" x1="15.646" x2="17.947" y1="15.82" y2="17.171" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".07" class="yi4nh_lsa"/><stop offset=".35" class="v26knx77k"/><stop offset=".6" class="o7fmrupzg"/><stop offset=".83" class="mau_2wn0d"/><stop offset=".99" class="fot6-kuzk"/></linearGradient><linearGradient id="SVGKIp20bsj" x1="19.793" x2="19.864" y1="10.105" y2="15.184" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".23" class="x2yhn4b5g"/><stop offset=".53" class="afzcutzat"/><stop offset=".79" class="glev2oems"/><stop offset=".99" class="r__y4nmfe"/></linearGradient><linearGradient id="SVGI8jLTdia" x1="14.362" x2="18.388" y1="19.577" y2="17.115" gradientUnits="userSpaceOnUse"><stop class="m-bwhrbif"/><stop offset=".23" class="x2yhn4b5g"/><stop offset=".53" class="afzcutzat"/><stop offset=".79" class="glev2oems"/><stop offset=".99" class="r__y4nmfe"/></linearGradient><radialGradient id="SVGYFixMdDs" cx="0" cy="0" r="1" gradientTransform="matrix(11.2006 0 0 26.772 11.934 18.746)" gradientUnits="userSpaceOnUse"><stop class="wf5xx0bzb"/><stop offset=".25" class="th7sv__6h"/><stop offset=".66" class="vp0njctrd"/><stop offset="1" class="rt0sd_34d"/></radialGradient><radialGradient id="SVGAOXSDdCP" cx="0" cy="0" r="1" gradientTransform="rotate(224.69 11.345 1.852)scale(13.7034 15.8224)" gradientUnits="userSpaceOnUse"><stop class="wf5xx0bzb"/><stop offset=".25" class="th7sv__6h"/><stop offset=".66" class="vp0njctrd"/><stop offset="1" class="rt0sd_34d"/></radialGradient><radialGradient id="SVGOvBDHdUI" cx="0" cy="0" r="1" gradientTransform="rotate(120.421 3.289 10.54)scale(8.92494 8.99965)" gradientUnits="userSpaceOnUse"><stop class="wf5xx0bzb"/><stop offset=".25" class="th7sv__6h"/><stop offset=".66" class="vp0njctrd"/><stop offset="1" class="rt0sd_34d"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nahmii" /></template>
<style>
.afzcutzat {
  stop-color: var(--svg-color--c5348a, #c5348a);
}

.as9djwb1c {
  d: path("M14.115 20.084v-.91l2.934-1.665l.797-.455c.424-.242.424-.636 0-.877l.652.37c.38.216.605.575.605.962c0 .388-.226.746-.605.962l-3.633 2.063c-.414.221-.75.024-.75-.45");
}

.cek-lckbv {
  d: path("m6.046 17.115l.797.454l1.826-1.037a.78.78 0 0 0 .375-.469a.76.76 0 0 0-.282-.82a.8.8 0 0 0-.587-.15a.8.8 0 0 0-.291.102l-1.838 1.042c-.423.241-.424.636 0 .878");
}

.fot6-kuzk {
  stop-color: var(--svg-color--2c338a, #2c338a);
}

.ft5dv1b6b {
  fill: none;
}

.glev2oems {
  stop-color: var(--svg-color--d6388b, #d6388b);
}

.hmadrzbpp {
  d: path("m18.114 6.097l-.8.455l-2.934-1.666l-.8-.452c-.425-.24-.77-.042-.77.44v-.742c0-.43.203-.803.543-.996s.77-.18 1.15.035l3.632 2.062c.403.242.397.627-.02.864");
}

.jqsuxkbba {
  d: path("m3.77 9.67l.8.455v3.332l.003.907c0 .482.349.679.773.437l-.652.371c-.379.215-.808.228-1.149.035S3 14.642 3 14.21v-4.125c.01-.465.353-.652.77-.416");
}

.kegd1xb-o {
  d: path("M9.885 20.084v-.91L6.951 17.51l-.796-.455c-.424-.242-.424-.636 0-.877l-.652.37c-.38.216-.605.575-.606.962c0 .388.227.746.606.962l3.632 2.061c.415.223.75.026.75-.448");
}

.m-bwhrbif {
  stop-color: var(--svg-color--902784, #902784);
}

.mau_2wn0d {
  stop-color: var(--svg-color--32328a, #32328a);
}

.mgumy1b7g {
  d: path("m10.42 4.313l-.8.452v2.073c.006.2.09.392.238.532a.793.793 0 0 0 1.095 0a.77.77 0 0 0 .238-.532V4.753c.002-.482-.346-.68-.77-.44");
}

.o7fmrupzg {
  stop-color: var(--svg-color--433089, #433089);
}

.o7vlolb8j {
  d: path("m4.466 14.424l-.002-.905l1.825-1.038a.797.797 0 0 1 1.074.283a.76.76 0 0 1 .078.586a.78.78 0 0 1-.366.47l-1.837 1.042c-.423.24-.771.044-.772-.438");
}

.pnfw-pbva {
  d: path("M3 9.492v.715c.01-.466.353-.653.77-.416l4.353 2.472c.44.25.853.705 1.156 1.223s.5 1.096.5 1.595v4.942c0 .475-.337.67-.751.448l.63.358c.378.215.808.228 1.148.035c.34-.194.544-.566.544-.996v-4.787c0-.773-.267-1.613-.704-2.358l-.006-.01l-.006-.01c-.437-.744-1.044-1.392-1.725-1.777L4.692 8.531c-.378-.215-.808-.228-1.148-.034c-.34.193-.544.564-.544.995");
}

.q32lyn9dm {
  d: path("m20.23 9.67l-.8.455v3.332l-.003.907c0 .482-.349.679-.773.437l.652.371c.379.215.808.228 1.148.035c.341-.193.544-.565.544-.996v-4.125c-.01-.465-.35-.652-.768-.416");
}

.r__y4nmfe {
  stop-color: var(--svg-color--dc398c, #dc398c);
}

.rt0sd_34d {
  stop-color: var(--svg-color--0e67ab, #0e67ab);
}

.s04k3mb2a {
  d: path("m5.885 6.097l.8.455L9.62 4.886l.8-.452c.425-.24.773-.042.773.44v-.742c0-.43-.204-.803-.544-.996s-.77-.18-1.15.035L5.867 5.233c-.404.242-.398.627.02.864");
}

.ss5x8rumn {
  d: path("m19.534 14.424l.003-.905l-1.826-1.037a.795.795 0 0 0-1.08.28a.766.766 0 0 0 .294 1.058l1.838 1.043c.422.24.77.043.771-.44");
}

.th7sv__6h {
  stop-color: var(--svg-color--029ad6, #029ad6);
}

.v26knx77k {
  stop-color: var(--svg-color--5e2d87, #5e2d87);
}

.vp0njctrd {
  stop-color: var(--svg-color--0880c0, #0880c0);
}

.wf5xx0bzb {
  stop-color: var(--svg-color--00a3de, #00a3de);
}

.woxwkkb3d {
  d: path("m13.58 4.313l.8.452v2.073a.77.77 0 0 1-.237.532a.793.793 0 0 1-1.096 0a.77.77 0 0 1-.237-.532V4.753c0-.482.345-.68.77-.44");
}

.ww47cubwh {
  d: path("m17.954 17.115l-.797.455l-1.826-1.037a.78.78 0 0 1-.375-.47a.76.76 0 0 1 .281-.82a.79.79 0 0 1 .88-.048l1.837 1.043c.423.24.423.635 0 .877");
}

.x2yhn4b5g {
  stop-color: var(--svg-color--aa2d87, #aa2d87);
}

.xxkzupb3l {
  d: path("m18.657 5.53l-.63-.357c.404.242.398.627-.019.863l-4.353 2.471c-.44.25-1.048.374-1.655.372s-1.215-.122-1.655-.372l-4.352-2.47c-.418-.237-.423-.622-.019-.864l-.63.357c-.38.215-.606.575-.606.962s.226.746.605.962L9.56 9.847c.682.386 1.555.58 2.43.58h.023c.875 0 1.749-.194 2.43-.58l4.216-2.393c.38-.216.605-.575.605-.962c0-.388-.228-.747-.607-.962");
}

.yi4nh_lsa {
  stop-color: var(--svg-color--842885, #842885);
}

.yimrx5bzs {
  d: path("m14.343 20.829l.63-.358c-.415.224-.751.027-.751-.448v-4.942c0-.5.194-1.078.5-1.595c.304-.517.715-.974 1.155-1.224l4.353-2.471c.417-.237.759-.05.77.415v-.714c0-.43-.203-.802-.544-.995c-.34-.194-.77-.18-1.148.034l-4.217 2.395c-.681.386-1.287 1.034-1.725 1.777l-.005.01l-.006.01c-.437.744-.704 1.585-.704 2.357v4.788c0 .43.203.802.544.996c.34.193.77.18 1.148-.035");
}

</style>
