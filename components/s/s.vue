<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydq3irb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ydq3irb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:s" /></template>
