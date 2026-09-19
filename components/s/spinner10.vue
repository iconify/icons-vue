<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eidiw9bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eidiw9bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spinner10" /></template>
