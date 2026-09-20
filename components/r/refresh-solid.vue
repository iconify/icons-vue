<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brxx-opev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brxx-opev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:refresh-solid" /></template>
