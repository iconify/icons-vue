<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j57x0ccea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j57x0ccea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play" /></template>
