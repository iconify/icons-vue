<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl9u7obry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jl9u7obry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rescript" /></template>
