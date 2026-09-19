<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-2lw4d3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-2lw4d3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:third-bracket" /></template>
