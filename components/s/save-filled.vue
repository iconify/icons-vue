<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mapjoxb2i.css';
import '../../css/n/nbzxfbcpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mapjoxb2i"/><path class="nbzxfbcpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-filled" /></template>
