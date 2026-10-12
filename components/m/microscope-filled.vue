<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl_5w4b-x.css';
import '../../css/d/dr823obko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl_5w4b-x"/><path class="dr823obko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:microscope-filled" /></template>
