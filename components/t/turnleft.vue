<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o73s2d9-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o73s2d9-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:turnleft" /></template>
