<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfchylgou.css';
import '../../css/a/aa6prfb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gfchylgou"/><path class="aa6prfb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:prism-48-bold" /></template>
