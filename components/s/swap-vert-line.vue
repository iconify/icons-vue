<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieb6cgzbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieb6cgzbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:swap-vert-line" /></template>
