<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fve4swbro.css';
import '../../css/o/os335z1oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fve4swbro"/><path class="os335z1oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticky-note-20" /></template>
