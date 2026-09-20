<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2ru59beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sofi" /></template>
<style>
.n2ru59beu {
  fill: var(--svg-color--a950fe, #a950fe);
  fill-rule: evenodd;
  d: path("m12 3l-9 9l9 9l9-9zm2.035 3.77L12.04 4.78l-7.23 7.23l4.4 4.4l4.01-4.005l.76.76l-4.01 4.005l2.02 2.02l7.23-7.23l-4.4-4.4l-4.035 4.03l-.785-.785z");
}

</style>
