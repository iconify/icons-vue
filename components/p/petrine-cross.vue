<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4d2-cb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v4d2-cb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:petrine-cross" /></template>
