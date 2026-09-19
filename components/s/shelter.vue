<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awlexv-3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awlexv-3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:shelter" /></template>
