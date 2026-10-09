<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1efy3xti.css';
import '../../css/t/t1wq7pbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x1efy3xti"/><path class="t1wq7pbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toaster-48-bold" /></template>
