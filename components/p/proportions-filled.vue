<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6bd0e58x.css';
import '../../css/i/ikrljqbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6bd0e58x"/><path class="ikrljqbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:proportions-filled" /></template>
