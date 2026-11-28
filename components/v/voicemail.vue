<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb62anb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb62anb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:voicemail" /></template>
