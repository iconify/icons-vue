<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jktbyzeri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jktbyzeri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:pedestrians" /></template>
