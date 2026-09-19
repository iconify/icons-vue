<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jajje8bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jajje8bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:noise-filled" /></template>
