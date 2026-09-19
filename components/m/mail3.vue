<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edlr2ix5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="edlr2ix5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:mail3" /></template>
