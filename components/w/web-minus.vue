<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f38ss-bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f38ss-bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:web-minus" /></template>
