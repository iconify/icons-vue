<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3u6ksb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3u6ksb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:satellite-dish" /></template>
