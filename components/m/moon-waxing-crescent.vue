<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bni1lgbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bni1lgbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:moon-waxing-crescent" /></template>
