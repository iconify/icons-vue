<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjh4w04bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjh4w04bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:retract-shrink-arrow" /></template>
