<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg7-xdbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hg7-xdbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pin-16" /></template>
