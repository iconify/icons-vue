<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ota9wmgua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ota9wmgua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:smiley" /></template>
