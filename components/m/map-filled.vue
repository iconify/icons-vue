<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyeinh2ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lyeinh2ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:map-filled" /></template>
