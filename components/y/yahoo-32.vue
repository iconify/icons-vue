<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa26vbb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="xa26vbb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:yahoo-32" /></template>
