<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orkh5bv4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orkh5bv4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:siren-off-sharp" /></template>
