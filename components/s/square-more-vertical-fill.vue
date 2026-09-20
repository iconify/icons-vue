<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjx3ab04x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjx3ab04x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-more-vertical-fill" /></template>
