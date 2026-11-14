<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm64gebbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pop-up-book" /></template>
<style>
.hm64gebbr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m17.25 13.065l3.587-.797q.146-.033.293-.007t.273.106t.211.203t.118.267q.018.081.018.163v6.5q0 .064-.011.126q-.01.063-.031.123q-.022.06-.052.115q-.031.056-.071.105q-.04.05-.087.092q-.048.042-.102.076t-.112.057q-.059.024-.121.038l-8.999 2h-.001q-.081.018-.163.018t-.163-.018h-.001l-8.999-2q-.062-.014-.121-.038t-.112-.057q-.054-.034-.102-.076t-.087-.092t-.071-.105t-.052-.115t-.031-.123q-.011-.062-.011-.126V13q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 12.25q.082 0 .163.018l3.587.797V8.5q0-.149.057-.287t.163-.243l4.499-4.5h.001q.105-.106.243-.163T12 3.25l.036.001q.14.007.268.063q.127.057.226.156h.001l4.499 4.5q.106.105.163.243t.057.287zm-6-7.254l-3 3v4.587l3 .667zm1.5 8.254l3-.667V8.811l-3-3z");
}

</style>
