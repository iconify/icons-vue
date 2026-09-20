<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi3dgx43l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mi3dgx43l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:search" /></template>
