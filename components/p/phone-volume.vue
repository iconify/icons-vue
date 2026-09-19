<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw20a1b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zw20a1b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:phone-volume" /></template>
