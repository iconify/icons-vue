<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4j28acah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k4j28acah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-shekel" /></template>
