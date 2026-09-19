<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__oynb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q__oynb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:table-cells-row-unlock" /></template>
