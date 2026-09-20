<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr97u2_pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kr97u2_pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-all-outline" /></template>
