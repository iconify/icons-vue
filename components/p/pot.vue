<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e997byv-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e997byv-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pot" /></template>
