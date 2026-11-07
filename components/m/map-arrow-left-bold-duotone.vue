<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a553rmbqh.css';
import '../../css/g/ga-aabcqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a553rmbqh"/><path class="ga-aabcqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-left-bold-duotone" /></template>
