<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei_3t-bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei_3t-bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:octagon" /></template>
