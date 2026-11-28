<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxc7bbcbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxc7bbcbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:workflow-clock" /></template>
