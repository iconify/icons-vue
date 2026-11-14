<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbb-admfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:social-media-manager" /></template>
<style>
.vbb-admfj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.125 1.75h-6.25q-2.123 0-3.624 1.501T1.75 6.875v6.25q0 2.123 1.501 3.624t3.624 1.501h4.63q-.005-.123-.005-.25v-3q0-3.5 3.5-3.5h3.25V6.875q0-2.123-1.501-3.624T13.125 1.75M9.47 14.03l-3-3Q4.439 9 6.47 6.97q.841-.841 2.03-.841q.82 0 1.474.399q1.778-1.337 3.556.442q2.031 2.03 0 4.06l-3 3q-.105.106-.243.163T10 14.25t-.287-.057t-.243-.163M15 12.75h5q2.25 0 2.25 2.25v3q0 2.25-2.25 2.25h-2.218l-1.788 1.564q-.112.099-.254.146q-.141.048-.29.038t-.282-.076t-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-1.007q-2-.122-2-2.243v-3q0-2.25 2.25-2.25m0 1.5q-.75 0-.75.75v3q0 .75.75.75h.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.097l.756-.661q.103-.09.23-.138q.128-.048.264-.048H20q.75 0 .75-.75v-3q0-.75-.75-.75zm1.749 2.499q.578-.578.934-1.249H15.5v2q.142 0 .283.02q.512-.317.966-.771");
}

</style>
