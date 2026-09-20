<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7rzdrb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7rzdrb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-price-outline" /></template>
