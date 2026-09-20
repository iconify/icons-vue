<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saq33obio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="saq33obio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-tag" /></template>
