<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p927m4bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p927m4bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:video-camera-solid" /></template>
