<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n819e5urp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n819e5urp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-track-2-outline" /></template>
