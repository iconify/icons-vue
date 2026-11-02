<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq9y-x28s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq9y-x28s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-search-fill" /></template>
