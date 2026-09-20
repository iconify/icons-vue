<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-2dukbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i-2dukbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mask-sad-bold" /></template>
