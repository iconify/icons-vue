<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2xgnhtxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e2xgnhtxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trash-truck" /></template>
