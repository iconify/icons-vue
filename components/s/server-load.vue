<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky-d3nb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:server-load" /></template>
<style>
.ky-d3nb-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13q0-.221.011-.442q.011-.22.032-.44t.054-.439q.033-.218.076-.435t.097-.431t.118-.426q.064-.211.138-.419t.159-.412t.179-.404q.095-.2.199-.395q.104-.194.217-.384q.114-.189.237-.373t.254-.361q.132-.178.272-.349t.288-.334q.149-.164.305-.32t.32-.305t.334-.288q.171-.14.349-.272q.177-.131.361-.254t.373-.237q.19-.113.384-.217q.195-.104.395-.199q.2-.094.404-.179t.412-.159t.419-.138q.212-.065.426-.118q.214-.054.431-.097t.435-.076t.439-.054t.44-.032Q11.279 4 11.5 4q.368 0 .735.03t.73.09t.72.149t.705.208t.687.264q.337.146.662.32q.325.173.634.372q.31.2.602.424t.565.47q.272.247.524.516q.252.268.481.556t.434.594t.384.628t.331.656t.277.682q.124.346.22.701M11.5 13l.234-.324m1.405-1.946L14.75 8.5m-.25 5h7.25v8.25H14.5Zm0 4h7.25m-5-2h.01m-.01 4.25h.01");
}

</style>
