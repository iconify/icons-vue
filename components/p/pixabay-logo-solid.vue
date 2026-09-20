<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py0o4xekj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py0o4xekj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:pixabay-logo-solid" /></template>
