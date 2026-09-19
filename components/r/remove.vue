<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpa8qabrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="st0 wpa8qabrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:remove" /></template>
