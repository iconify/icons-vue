<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuzrz4s5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-3};
const content = `<path class="nuzrz4s5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:volume" /></template>
