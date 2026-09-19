<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi240emrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pi240emrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo" /></template>
