<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0jt62teq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o0jt62teq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:row-height-l-outline" /></template>
