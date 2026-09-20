<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm3geac7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm3geac7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:select-all-solid" /></template>
