<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm1dldagq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm1dldagq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:photo-album-2-fill" /></template>
