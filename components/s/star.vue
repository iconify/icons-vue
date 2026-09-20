<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm3x0j_xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="rm3x0j_xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:star" /></template>
