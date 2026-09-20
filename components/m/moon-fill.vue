<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt5q8rs1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt5q8rs1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-fill" /></template>
