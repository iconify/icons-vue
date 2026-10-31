<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_vpf-b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m_vpf-b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-up-right-20-solid" /></template>
