<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j57f-3ujj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j57f-3ujj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nintendo-wiiu" /></template>
