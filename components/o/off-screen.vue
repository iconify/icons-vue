<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6p-n4b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e6p-n4b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:off-screen" /></template>
