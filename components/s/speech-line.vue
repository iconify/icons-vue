<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk9lwgbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk9lwgbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:speech-line" /></template>
