<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ady5bhbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ady5bhbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tag-star" /></template>
