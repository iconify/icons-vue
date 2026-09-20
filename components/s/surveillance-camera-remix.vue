<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz9qcwbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kz9qcwbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:surveillance-camera-remix" /></template>
