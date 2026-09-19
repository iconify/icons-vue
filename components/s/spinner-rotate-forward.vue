<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c29gppbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="c29gppbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:spinner-rotate-forward" /></template>
