<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyy8nwb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyy8nwb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-left-duotone-round" /></template>
