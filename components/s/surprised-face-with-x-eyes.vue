<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j87ilt-jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j87ilt-jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:surprised-face-with-x-eyes" /></template>
