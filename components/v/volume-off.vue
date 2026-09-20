<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di-rr7o5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="di-rr7o5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-off" /></template>
