<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pytlxacqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pytlxacqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:repeat-one-fill" /></template>
