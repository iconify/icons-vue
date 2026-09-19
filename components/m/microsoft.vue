<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjci2bbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bjci2bbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:microsoft" /></template>
