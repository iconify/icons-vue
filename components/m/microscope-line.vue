<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1cj90bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1cj90bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:microscope-line" /></template>
