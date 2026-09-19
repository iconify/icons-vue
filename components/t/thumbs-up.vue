<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs23i3x1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gs23i3x1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:thumbs-up" /></template>
