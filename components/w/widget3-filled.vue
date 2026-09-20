<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueu0rgbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ueu0rgbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget3-filled" /></template>
