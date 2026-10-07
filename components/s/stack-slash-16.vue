<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooaogza-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ooaogza-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stack-slash-16" /></template>
