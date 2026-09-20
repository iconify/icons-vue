<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi16cl6td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oi16cl6td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-square-outline" /></template>
