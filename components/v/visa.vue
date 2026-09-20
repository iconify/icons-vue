<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ule2qfbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ule2qfbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:visa" /></template>
