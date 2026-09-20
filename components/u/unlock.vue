<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa83evjwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa83evjwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:unlock" /></template>
