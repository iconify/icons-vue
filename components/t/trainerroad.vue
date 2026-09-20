<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puy3aguoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puy3aguoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trainerroad" /></template>
