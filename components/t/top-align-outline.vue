<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka1cq2b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ka1cq2b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:top-align-outline" /></template>
