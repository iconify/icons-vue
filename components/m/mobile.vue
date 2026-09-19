<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es8u0ebhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es8u0ebhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:mobile" /></template>
