<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-8jss4sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e-8jss4sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tank" /></template>
