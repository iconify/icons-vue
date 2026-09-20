<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbnpjcbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rbnpjcbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-large-outline" /></template>
