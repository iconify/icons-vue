<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlh-5mb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nlh-5mb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:robot-solid" /></template>
