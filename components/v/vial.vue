<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd3i9yb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd3i9yb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:vial" /></template>
