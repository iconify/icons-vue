<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt1twzbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wt1twzbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:meter-16" /></template>
