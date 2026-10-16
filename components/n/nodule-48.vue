<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu-_06bfk.css';
import '../../css/q/qzu5cgzuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iu-_06bfk"/><path class="qzu5cgzuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nodule-48" /></template>
