<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xduc6cb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xduc6cb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:multi-triangular" /></template>
