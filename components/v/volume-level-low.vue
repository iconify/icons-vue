<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv5_69tgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rv5_69tgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-level-low" /></template>
