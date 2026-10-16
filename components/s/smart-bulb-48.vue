<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs-cefb8p.css';
import '../../css/d/dtun6abyq.css';
import '../../css/b/b5u-9mb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bs-cefb8p"/><path class="dtun6abyq"/><path class="b5u-9mb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-bulb-48" /></template>
