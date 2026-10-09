<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zor6y16jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zor6y16jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skateboard-48" /></template>
