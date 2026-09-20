<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3o2nkoei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3o2nkoei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:streaming-logo-solid" /></template>
