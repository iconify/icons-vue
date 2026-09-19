<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewfvsjl4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ewfvsjl4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:warning" /></template>
