<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb7mzeb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb7mzeb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:nut-off" /></template>
