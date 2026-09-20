<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/komxfdcuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="komxfdcuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-4k-box" /></template>
