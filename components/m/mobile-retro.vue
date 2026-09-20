<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r99zety3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r99zety3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:mobile-retro" /></template>
