<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js03r1bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="js03r1bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:pie-one-outline" /></template>
