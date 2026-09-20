<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3d5p9bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3d5p9bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:robot-fill" /></template>
