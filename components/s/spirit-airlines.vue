<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl3jjbtxm.css';
import '../../css/e/ej_-dh--d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl3jjbtxm"/><path class="ej_-dh--d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spirit-airlines" /></template>
