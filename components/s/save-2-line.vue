<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5orysb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5orysb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:save-2-line" /></template>
