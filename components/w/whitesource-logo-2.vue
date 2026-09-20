<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nco9tjboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nco9tjboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:whitesource-logo-2" /></template>
