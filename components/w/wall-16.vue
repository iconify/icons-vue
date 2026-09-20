<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg1yx4lqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qg1yx4lqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wall-16" /></template>
