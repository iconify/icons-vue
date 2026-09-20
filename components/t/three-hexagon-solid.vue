<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1mrdubyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1mrdubyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:three-hexagon-solid" /></template>
