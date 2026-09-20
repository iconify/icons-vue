<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk6-1wqqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lk6-1wqqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:switch-outline" /></template>
