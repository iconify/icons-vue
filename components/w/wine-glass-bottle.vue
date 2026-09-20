<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwuge2bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwuge2bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:wine-glass-bottle" /></template>
