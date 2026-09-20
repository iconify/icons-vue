<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8mi811tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8mi811tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:trash-sharp" /></template>
