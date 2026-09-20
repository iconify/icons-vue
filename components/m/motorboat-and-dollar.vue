<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foxqnjf9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="foxqnjf9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-dollar" /></template>
