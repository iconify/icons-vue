<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k_qjhvpku.css';
import '../../css/g/gwzcxibji.css';
import '../../css/u/u9qv1uges.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k_qjhvpku"/><path class="gwzcxibji"/><path class="u9qv1uges"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-circle-outline" /></template>
