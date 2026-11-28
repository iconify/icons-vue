<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkjq270wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkjq270wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mug-heart" /></template>
