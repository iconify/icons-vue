<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebd8srt4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ebd8srt4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-behind-image" /></template>
