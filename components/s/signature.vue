<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbbl71bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cbbl71bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:signature" /></template>
