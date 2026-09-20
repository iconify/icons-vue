<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-7gf0yzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-7gf0yzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:surprised-face-in-circle-outline" /></template>
