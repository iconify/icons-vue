<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0gy0ob6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s0gy0ob6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:w-outline" /></template>
