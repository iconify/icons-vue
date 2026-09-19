<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0mrpe_tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e0mrpe_tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:woman" /></template>
