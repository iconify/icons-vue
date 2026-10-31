<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eto1u3blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eto1u3blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-check-round" /></template>
