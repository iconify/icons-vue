<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5kx_xpqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5kx_xpqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:web-grid-alt" /></template>
