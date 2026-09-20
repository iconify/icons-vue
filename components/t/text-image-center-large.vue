<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac5gbxdnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ac5gbxdnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:text-image-center-large" /></template>
