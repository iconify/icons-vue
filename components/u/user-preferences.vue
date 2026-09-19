<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7sr6ubzr.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/z/z-d7g1b-g.css';
import '../../css/h/hclqxqegg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><g class="d2kvgvbvc"><path class="z-d7g1b-g"/><path class="hclqxqegg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:user-preferences" /></template>
