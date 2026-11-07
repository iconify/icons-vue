<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbf_yzbjl.css';
import '../../css/p/p3f1qdw5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbf_yzbjl"/><path class="p3f1qdw5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-2-bold" /></template>
