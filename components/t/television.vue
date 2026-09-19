<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaicph7xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="uaicph7xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:television" /></template>
