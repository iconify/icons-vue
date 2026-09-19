<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hod51dubu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hod51dubu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:prism" /></template>
