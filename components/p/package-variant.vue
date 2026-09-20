<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grh1jhbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grh1jhbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-variant" /></template>
