<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1z_yzfxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k1z_yzfxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mars-stroke-h" /></template>
