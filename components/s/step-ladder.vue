<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw9cobb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aw9cobb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:step-ladder" /></template>
