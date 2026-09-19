<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqhfcj8qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhfcj8qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:video-camera-slash-solid" /></template>
