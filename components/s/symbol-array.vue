<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss-p3acfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ss-p3acfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-array" /></template>
