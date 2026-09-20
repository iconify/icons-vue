<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrzh3gbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrzh3gbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:qualys" /></template>
