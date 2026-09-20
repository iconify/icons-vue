<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qteu-bb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qteu-bb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reqable" /></template>
