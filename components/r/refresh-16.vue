<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6_e7pqol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6_e7pqol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:refresh-16" /></template>
