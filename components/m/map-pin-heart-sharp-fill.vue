<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esrqwyb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esrqwyb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-heart-sharp-fill" /></template>
