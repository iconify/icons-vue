<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5d2v1bhr.css';
import '../../css/y/y59k77qlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5d2v1bhr"/><path class="y59k77qlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tube-guyed-wave-left-wave-right" /></template>
