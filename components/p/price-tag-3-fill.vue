<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkb3agx2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkb3agx2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:price-tag-3-fill" /></template>
