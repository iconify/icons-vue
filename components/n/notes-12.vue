<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv77kib4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pv77kib4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:notes-12" /></template>
