<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyt1yyrwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyt1yyrwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-close-round" /></template>
