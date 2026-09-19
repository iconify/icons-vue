<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh4v3y2lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gh4v3y2lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:one" /></template>
