<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/j4kl21b2v.css';
import '../../css/c/ce22cyb5j.css';
import '../../css/s/sqw8o7bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="j4kl21b2v"/><path class="ce22cyb5j"/><rect class="sqw8o7bkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:workflow" /></template>
