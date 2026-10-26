<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7m-eycyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7m-eycyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:minimize" /></template>
