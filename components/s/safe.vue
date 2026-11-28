<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5mt7nr3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5mt7nr3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:safe" /></template>
