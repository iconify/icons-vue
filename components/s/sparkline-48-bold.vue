<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmtr6bb9i.css';
import '../../css/c/cxqwkvj3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wmtr6bb9i"/><path class="cxqwkvj3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkline-48-bold" /></template>
