<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohga79bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ohga79bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-group-16-solid" /></template>
