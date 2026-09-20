<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":408};
const content = `<path class="cpkneib0c"/><path class="nmrmcua8j"/><path class="u6arn-b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pandas-icon" /></template>
<style>
.cpkneib0c {
  fill: var(--svg-color--130754, #130754);
  d: path("M71.478 24.072h44.504v92.41H71.478zm0 189.825h44.504v92.409H71.478zM0 100.057h44.505v307.175H0zm141.496 190.084H186v92.409h-44.504zm0-189.973H186v92.41h-44.504zM211.496 0H256v307.174h-44.505z");
}

.nmrmcua8j {
  fill: var(--svg-color--ffca00, #ffca00);
  d: path("M71.478 143.454h44.505v43.6H71.478z");
}

.u6arn-b2h {
  fill: var(--svg-color--e70488, #e70488);
  d: path("M141.496 219.55h44.505v43.6h-44.505z");
}

</style>
