<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoibcycal.css';
import '../../css/r/rewt-b9oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yoibcycal"/><path class="rewt-b9oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:pix" /></template>
