<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhux28btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hhux28btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tom-16" /></template>
