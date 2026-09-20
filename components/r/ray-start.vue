<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at84-bcot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at84-bcot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ray-start" /></template>
