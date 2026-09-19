<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn683-7jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tn683-7jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:markdown" /></template>
