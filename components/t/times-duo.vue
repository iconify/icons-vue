<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta8351udl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ta8351udl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:times-duo" /></template>
