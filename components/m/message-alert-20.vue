<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itmoa867s.css';
import '../../css/e/e5jh2b8fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itmoa867s"/><path class="e5jh2b8fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-alert-20" /></template>
