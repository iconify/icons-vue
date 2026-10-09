<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cze6f6b6k.css';
import '../../css/u/un6m0jq1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cze6f6b6k"/><path class="un6m0jq1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:presentation-48-bold" /></template>
