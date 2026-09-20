<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jew7w5bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jew7w5bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-baht" /></template>
