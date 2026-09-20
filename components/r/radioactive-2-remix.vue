<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9v3s6lts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q9v3s6lts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:radioactive-2-remix" /></template>
