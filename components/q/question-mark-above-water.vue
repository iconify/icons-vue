<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9uildkbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c9uildkbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:question-mark-above-water" /></template>
