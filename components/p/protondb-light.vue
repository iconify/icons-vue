<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jolbf1bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jolbf1bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:protondb-light" /></template>
