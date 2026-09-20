<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0q_up5ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0q_up5ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:obs-studio-logo-solid" /></template>
