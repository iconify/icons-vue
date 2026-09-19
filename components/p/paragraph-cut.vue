<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1ugjpbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1ugjpbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:paragraph-cut" /></template>
