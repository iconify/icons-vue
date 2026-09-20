<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":203};
const content = `<path class="wbuj71s0h"/><path class="gypzmhb9k"/><path class="icqgx4gce"/><path class="ulxw6lfeu"/><path class="izav0dbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:mixmax" /></template>
<style>
.gypzmhb9k {
  fill: var(--svg-color--24235c, #24235c);
  d: path("M102.633.007L0 202.999h50.731L153.364.007z");
}

.icqgx4gce {
  fill: var(--svg-color--e55cff, #e55cff);
  d: path("M102.633 202.999h50.731V.007h-50.731z");
}

.izav0dbej {
  fill: var(--svg-color--e55cff, #e55cff);
  d: path("M204.982 202.999h50.731V.007h-50.731z");
}

.ulxw6lfeu {
  fill: var(--svg-color--24235c, #24235c);
  d: path("M205.27.008L102.635 203h50.73L256 .008z");
}

.wbuj71s0h {
  fill: var(--svg-color--e55cff, #e55cff);
  d: path("M0 202.999h50.731V.007H0z");
}

</style>
