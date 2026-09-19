<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdkvtgb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gdkvtgb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:removesign" /></template>
