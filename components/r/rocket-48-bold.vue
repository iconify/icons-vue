<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-7zydo-z.css';
import '../../css/i/ifsbdgx5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i-7zydo-z"/><path class="ifsbdgx5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rocket-48-bold" /></template>
