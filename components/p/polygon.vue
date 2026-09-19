<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8sbembrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8sbembrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:polygon" /></template>
