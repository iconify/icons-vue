<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0w9p_bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j0w9p_bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:yahoo" /></template>
