<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpl6erble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpl6erble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pass-valid-line" /></template>
