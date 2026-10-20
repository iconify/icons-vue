<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh9bfhbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eh9bfhbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tree-trunk" /></template>
