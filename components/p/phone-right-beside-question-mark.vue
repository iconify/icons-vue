<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoqn4k-mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yoqn4k-mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-right-beside-question-mark" /></template>
