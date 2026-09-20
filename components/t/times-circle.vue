<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8q7hs45s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8q7hs45s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:times-circle" /></template>
