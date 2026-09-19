<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek7nqvbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ek7nqvbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:tiktok" /></template>
