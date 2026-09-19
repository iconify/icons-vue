<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2r8k2b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2r8k2b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:map-pin-solid" /></template>
