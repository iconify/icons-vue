<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dta6c0b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dta6c0b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:map-pin" /></template>
