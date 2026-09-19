<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryrdczeve.css';
import '../../css/h/hsnx_9cta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ryrdczeve"/><path class="duoicon-primary-layer hsnx_9cta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:slideshow" /></template>
