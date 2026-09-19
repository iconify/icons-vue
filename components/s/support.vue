<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7sr6ubzr.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/r/r4dz7fbay.css';
import '../../css/r/reozhcb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><g class="d2kvgvbvc"><path class="r4dz7fbay"/><path class="reozhcb8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:support" /></template>
