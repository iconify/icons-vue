<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysujw0_2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ysujw0_2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-down-left-20-solid" /></template>
