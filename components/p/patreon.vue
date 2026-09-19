<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9ma6qbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9ma6qbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:patreon" /></template>
