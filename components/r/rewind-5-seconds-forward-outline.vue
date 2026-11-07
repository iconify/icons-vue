<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s567sdlaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s567sdlaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-5-seconds-forward-outline" /></template>
