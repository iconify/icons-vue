<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx3fe_t0r.css';
import '../../css/r/rj_m6ufoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kx3fe_t0r"/><path class="rj_m6ufoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-bold-duotone" /></template>
