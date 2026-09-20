<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utsk9mbdc.css';
import '../../css/a/a1wz2fbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="utsk9mbdc"/><path class="a1wz2fbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-photo-image" /></template>
