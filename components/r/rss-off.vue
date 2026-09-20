<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skx0vxbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skx0vxbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rss-off" /></template>
