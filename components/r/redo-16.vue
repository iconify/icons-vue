<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj23f-m4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uj23f-m4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:redo-16" /></template>
