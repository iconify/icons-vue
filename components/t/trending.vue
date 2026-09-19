<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhtlb8kso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhtlb8kso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:trending" /></template>
