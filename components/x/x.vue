<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iey8yxkye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iey8yxkye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:x" /></template>
