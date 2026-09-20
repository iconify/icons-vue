<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur_1lrlwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ur_1lrlwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-v-over-water" /></template>
