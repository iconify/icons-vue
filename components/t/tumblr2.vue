<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1mms8b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i1mms8b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:tumblr2" /></template>
