<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_wt-ubrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i_wt-ubrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:swimming-15" /></template>
