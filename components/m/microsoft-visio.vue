<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yikjj-8fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yikjj-8fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-visio" /></template>
