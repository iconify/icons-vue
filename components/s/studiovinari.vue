<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn2-7pgaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jn2-7pgaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:studiovinari" /></template>
