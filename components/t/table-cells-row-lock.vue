<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xff8fqbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xff8fqbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:table-cells-row-lock" /></template>
