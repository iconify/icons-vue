<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adelsmf5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adelsmf5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:phone-lock-fill" /></template>
