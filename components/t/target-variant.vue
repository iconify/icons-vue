<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra-cxab0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra-cxab0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:target-variant" /></template>
