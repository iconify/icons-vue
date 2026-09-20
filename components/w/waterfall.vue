<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9jx0eb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9jx0eb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:waterfall" /></template>
