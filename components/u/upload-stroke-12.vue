<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf-49vp4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tf-49vp4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:upload-stroke-12" /></template>
