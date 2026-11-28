<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxlu7jkul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxlu7jkul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:terminal" /></template>
