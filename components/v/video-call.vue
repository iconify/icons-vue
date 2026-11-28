<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksvw4dbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksvw4dbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:video-call" /></template>
