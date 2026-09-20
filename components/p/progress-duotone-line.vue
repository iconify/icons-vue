<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1zrnrbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h1zrnrbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:progress-duotone-line" /></template>
