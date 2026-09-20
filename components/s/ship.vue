<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixm8i3f1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ixm8i3f1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ship" /></template>
