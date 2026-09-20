<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x323-x_4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x323-x_4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:zoom-in" /></template>
