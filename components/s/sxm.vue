<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7_n84bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7_n84bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sxm" /></template>
