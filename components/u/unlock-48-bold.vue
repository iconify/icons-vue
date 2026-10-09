<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jviohsbmh.css';
import '../../css/u/uh531ccly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jviohsbmh"/><path class="uh531ccly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:unlock-48-bold" /></template>
