<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tulanhcad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tulanhcad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:weibo" /></template>
