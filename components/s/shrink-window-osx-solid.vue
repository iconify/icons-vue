<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er7agu8tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er7agu8tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shrink-window-osx-solid" /></template>
