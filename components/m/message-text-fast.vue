<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm43j4xee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm43j4xee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-text-fast" /></template>
