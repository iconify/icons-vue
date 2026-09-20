<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5aqueb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5aqueb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mouth-fill" /></template>
