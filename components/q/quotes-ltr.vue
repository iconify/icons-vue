<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ombo0mbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ombo0mbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:quotes-ltr" /></template>
