<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw13ow3ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw13ow3ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:progress-auto" /></template>
