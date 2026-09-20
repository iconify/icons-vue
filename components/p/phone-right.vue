<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_zlrubeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h_zlrubeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-right" /></template>
