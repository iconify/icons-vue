<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3mopsuqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="x3mopsuqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-rain-mix" /></template>
