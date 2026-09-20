<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoo8g9amd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yoo8g9amd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:zoom-document-remix" /></template>
