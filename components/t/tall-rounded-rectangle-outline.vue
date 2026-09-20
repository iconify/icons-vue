<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd1hsxbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dd1hsxbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tall-rounded-rectangle-outline" /></template>
