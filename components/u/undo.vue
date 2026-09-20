<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbxhj-o3i.css';
import '../../css/v/vbqfmsb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbxhj-o3i"/><path class="vbqfmsb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:undo" /></template>
