<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk_6lline.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_6lline"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:swatch-line" /></template>
