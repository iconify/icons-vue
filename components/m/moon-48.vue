<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_v4z1q3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_v4z1q3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-48" /></template>
