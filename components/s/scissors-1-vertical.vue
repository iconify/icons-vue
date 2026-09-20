<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-wkcrisg.css';
import '../../css/u/up737eb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="p-wkcrisg"/><path class="up737eb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:scissors-1-vertical" /></template>
