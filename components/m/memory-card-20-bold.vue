<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtth2tkbn.css';
import '../../css/i/ikhqytp8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gtth2tkbn"/><path class="ikhqytp8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-card-20-bold" /></template>
