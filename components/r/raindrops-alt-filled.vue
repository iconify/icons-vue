<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpqk98bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpqk98bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:raindrops-alt-filled" /></template>
