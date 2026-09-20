<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u59rcgy1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u59rcgy1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spotify-solid" /></template>
