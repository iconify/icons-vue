<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2vb22kcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2vb22kcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:user-check-solid" /></template>
