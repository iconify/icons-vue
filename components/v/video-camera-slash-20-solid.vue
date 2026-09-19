<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpy4myw3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tpy4myw3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:video-camera-slash-20-solid" /></template>
