<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvmol5kye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvmol5kye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shipping-logistic-damaged-package-bold" /></template>
