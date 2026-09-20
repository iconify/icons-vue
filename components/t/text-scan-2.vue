<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5_yaifwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5_yaifwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-scan-2" /></template>
