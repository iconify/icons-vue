<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5yxcsbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k5yxcsbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:ordered-list" /></template>
