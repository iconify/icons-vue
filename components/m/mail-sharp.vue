<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-0us7bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-0us7bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-sharp" /></template>
