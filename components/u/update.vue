<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5h75xbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x5h75xbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:update" /></template>
