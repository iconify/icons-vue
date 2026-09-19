<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z26as7v5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z26as7v5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pantone-outline" /></template>
