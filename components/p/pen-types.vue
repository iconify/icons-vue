<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn1c_rh4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn1c_rh4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-types" /></template>
