<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnw2i6g0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnw2i6g0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sofa-sharp" /></template>
