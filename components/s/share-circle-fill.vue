<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsp8lu-gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsp8lu-gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-circle-fill" /></template>
