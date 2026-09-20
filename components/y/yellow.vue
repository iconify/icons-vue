<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdc4_i2ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdc4_i2ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:yellow" /></template>
