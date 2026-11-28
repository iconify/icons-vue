<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrb7py0ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrb7py0ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:moon-star" /></template>
