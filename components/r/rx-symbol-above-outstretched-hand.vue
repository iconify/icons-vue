<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu67n8t-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fu67n8t-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rx-symbol-above-outstretched-hand" /></template>
