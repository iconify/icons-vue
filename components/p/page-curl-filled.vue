<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbilb_8jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sbilb_8jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:page-curl-filled" /></template>
