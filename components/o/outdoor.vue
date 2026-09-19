<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ug1wb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j7ug1wb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:outdoor" /></template>
