<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4ozfu2_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="w4ozfu2_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:yandex-rect" /></template>
