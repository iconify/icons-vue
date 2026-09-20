<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fubg32b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fubg32b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:surfboard-fill" /></template>
