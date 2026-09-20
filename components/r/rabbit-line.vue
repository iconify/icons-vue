<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0w3pxcur.css';
import '../../css/h/h0rooab0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0w3pxcur"/><path class="h0rooab0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rabbit-line" /></template>
