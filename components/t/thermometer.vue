<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcmnmhj8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="vcmnmhj8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:thermometer" /></template>
