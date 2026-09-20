<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n721h4qhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n721h4qhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-down-filled" /></template>
