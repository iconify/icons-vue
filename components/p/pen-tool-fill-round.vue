<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frfhp39os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frfhp39os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-fill-round" /></template>
