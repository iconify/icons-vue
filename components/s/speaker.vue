<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1dt8jrog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":432};
const content = `<path class="v1dt8jrog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:speaker" /></template>
