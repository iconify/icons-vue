<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy9s2vbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qy9s2vbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:notestasks" /></template>
