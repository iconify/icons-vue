<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbu9kekxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:service-language-support" /></template>
<style>
.gbu9kekxi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-3.25 3.25-3.25h11q3.25 0 3.25 3.25v7.514q-1.217-.764-2.75-.764q-2.175 0-3.712 1.538q-1.266 1.265-1.49 2.962h-1.516l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.755q-3-.123-3-3.245zM14 18q0-4 4-4t4 4t-4 4t-4-4m4-2.5q-.418 0-.487 1.75h.974Q18.418 15.5 18 15.5m-2.433 1.75q.142-.727.585-1.151q-.098.513-.133 1.151zm4.866 0h-.452q-.035-.638-.133-1.151q.443.424.585 1.151m-4.866 1.5h.452q.035.638.133 1.151q-.443-.424-.585-1.151M18 20.5q.418 0 .487-1.75h-.974q.069 1.75.487 1.75m2.433-1.75q-.142.727-.585 1.151q.098-.513.133-1.151z");
}

</style>
