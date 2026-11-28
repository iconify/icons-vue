<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy6g12bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy6g12bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:train" /></template>
