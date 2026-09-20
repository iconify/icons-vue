<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnfu2ibyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vnfu2ibyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:separation-vertical-16" /></template>
