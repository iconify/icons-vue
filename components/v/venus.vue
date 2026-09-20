<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro-d8rbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ro-d8rbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:venus" /></template>
