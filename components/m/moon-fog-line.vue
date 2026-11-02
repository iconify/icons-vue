<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4w406dss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4w406dss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-fog-line" /></template>
