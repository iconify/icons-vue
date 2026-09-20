<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twtz6dcce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="twtz6dcce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-euro" /></template>
