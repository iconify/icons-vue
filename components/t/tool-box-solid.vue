<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d516btmhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d516btmhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tool-box-solid" /></template>
