<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q30b9z0uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q30b9z0uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:truck-check" /></template>
