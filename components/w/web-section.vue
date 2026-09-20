<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkh03vbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkh03vbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:web-section" /></template>
