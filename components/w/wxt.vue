<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6hkyfb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6hkyfb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wxt" /></template>
