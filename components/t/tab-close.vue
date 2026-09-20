<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elbx3d_mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elbx3d_mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tab-close" /></template>
