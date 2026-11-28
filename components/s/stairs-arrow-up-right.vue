<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd4u_vyha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd4u_vyha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:stairs-arrow-up-right" /></template>
