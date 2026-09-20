<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi7f8tu-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vi7f8tu-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:zip-file-solid" /></template>
