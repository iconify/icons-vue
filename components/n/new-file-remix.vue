<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdfs5ecrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdfs5ecrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:new-file-remix" /></template>
