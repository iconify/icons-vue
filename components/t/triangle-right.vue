<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imgoe2enx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imgoe2enx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:triangle-right" /></template>
