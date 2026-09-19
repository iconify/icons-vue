<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_hwkqtbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="v_hwkqtbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:x" /></template>
