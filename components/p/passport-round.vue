<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajvl-j2_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajvl-j2_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passport-round" /></template>
