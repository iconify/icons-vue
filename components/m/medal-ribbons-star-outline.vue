<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3df2w8cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f3df2w8cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-ribbons-star-outline" /></template>
