<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpndxdbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mpndxdbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:quote" /></template>
