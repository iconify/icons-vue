<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyu6w7b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyu6w7b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:map-marker" /></template>
