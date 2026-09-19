<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/low_q9xkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="low_q9xkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:three-slashes" /></template>
