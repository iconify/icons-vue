<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6yxyvb3p.css';
import '../../css/l/l32vte6zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6yxyvb3p"/><path class="l32vte6zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:qdrant" /></template>
