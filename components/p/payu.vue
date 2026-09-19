<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn2kokbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="vn2kokbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:payu" /></template>
