<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhdb-55mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zhdb-55mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:undo-16" /></template>
