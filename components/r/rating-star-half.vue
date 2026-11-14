<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhi28z1gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rating-star-half" /></template>
<style>
.lhi28z1gv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 4.573q-.828.262-1.251 1.162l-.971 2.06q-.176.372-.585.424l-2.258.288q-1.392.176-1.826 1.51q-.433 1.334.588 2.295l1.66 1.561q.3.282.223.686l-.425 2.238q-.262 1.378.873 2.202q1.134.825 2.364.15l1.997-1.096q.091-.05.183-.075q-.061-.014-.118-.039q-.058-.025-.11-.059q-.053-.034-.099-.076t-.085-.091t-.069-.104t-.05-.114t-.031-.121t-.01-.124zm.928 13.405q.092.025.183.075l1.998 1.097q1.229.674 2.363-.151q1.135-.824.873-2.202l-.425-2.238q-.077-.404.223-.686l1.66-1.561q1.021-.961.588-2.295q-.434-1.334-1.825-1.51l-2.26-.288q-.408-.052-.584-.424l-.97-2.059l-.001-.001q-.423-.9-1.251-1.162V17.25q0 .063-.01.124q-.011.062-.031.121q-.021.059-.05.114t-.069.104q-.039.049-.085.091t-.099.076t-.11.059t-.118.039");
}

</style>
