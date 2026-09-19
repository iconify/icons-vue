<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryquvccfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryquvccfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:x-line-top" /></template>
