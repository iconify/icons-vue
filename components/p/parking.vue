<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sggwcl_gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sggwcl_gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:parking" /></template>
