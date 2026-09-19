<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/howt5s-nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="howt5s-nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:text" /></template>
