<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py9infbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py9infbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rewind-line" /></template>
