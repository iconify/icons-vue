<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp3xnnb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xp3xnnb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:taco" /></template>
