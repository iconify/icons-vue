<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy0brxbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wy0brxbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:percent" /></template>
