<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uejxkl2qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uejxkl2qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:microscope-fill" /></template>
