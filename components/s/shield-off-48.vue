<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i85qzcn-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i85qzcn-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-off-48" /></template>
