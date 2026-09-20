<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6bmqdbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g6bmqdbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-heavy-six-point-asterisk" /></template>
