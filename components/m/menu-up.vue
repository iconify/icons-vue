<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwiiwseqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwiiwseqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:menu-up" /></template>
