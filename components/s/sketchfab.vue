<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h87x-4gom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h87x-4gom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sketchfab" /></template>
