<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jverfxb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jverfxb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:video-camera" /></template>
