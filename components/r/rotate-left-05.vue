<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djmzdub0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djmzdub0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-left-05" /></template>
