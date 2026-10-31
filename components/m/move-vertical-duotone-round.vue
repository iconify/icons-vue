<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clb7lobia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clb7lobia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:move-vertical-duotone-round" /></template>
