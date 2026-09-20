<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nif7bvbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nif7bvbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:undo-solid" /></template>
