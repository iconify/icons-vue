<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtwn89bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qtwn89bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-silence-outline" /></template>
