<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohyfmac4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ohyfmac4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sixteenth-notes" /></template>
