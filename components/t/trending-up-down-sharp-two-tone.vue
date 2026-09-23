<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2e8exbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2e8exbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trending-up-down-sharp-two-tone" /></template>
