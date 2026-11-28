<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro-75n6yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-75n6yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tv-check" /></template>
