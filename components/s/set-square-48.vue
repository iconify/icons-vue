<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz73jtbrx.css';
import '../../css/j/j8m18acze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jz73jtbrx"/><path class="j8m18acze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:set-square-48" /></template>
