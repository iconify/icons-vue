<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukalqnb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ukalqnb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:solar-panel-solid" /></template>
