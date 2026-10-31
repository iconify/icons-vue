<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/w/w8cdvmb8r.css';
import '../../css/d/dkv54xjtw.css';
import '../../css/k/kdo4s3bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="w8cdvmb8r wm-shadow"/><path class="dkv54xjtw"/><path class="kdo4s3bdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-retro:scan-search" /></template>
