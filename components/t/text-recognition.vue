<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2w28gbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a2w28gbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-recognition" /></template>
