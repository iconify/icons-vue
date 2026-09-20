<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4j-tabeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4j-tabeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-horizontal-outline" /></template>
