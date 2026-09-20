<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpzcypbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="wpzcypbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:plug-1" /></template>
