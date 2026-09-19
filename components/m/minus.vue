<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt694xk1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="qt694xk1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:minus" /></template>
