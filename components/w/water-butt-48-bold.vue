<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyir5yn6t.css';
import '../../css/j/jtw39nbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lyir5yn6t"/><path class="jtw39nbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-butt-48-bold" /></template>
