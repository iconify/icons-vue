<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v12dl5b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v12dl5b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:youtube-line" /></template>
