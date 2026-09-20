<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjl27fbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jjl27fbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paperclip" /></template>
