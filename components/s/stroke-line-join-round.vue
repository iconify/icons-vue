<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jksb1yr8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jksb1yr8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stroke-line-join-round" /></template>
