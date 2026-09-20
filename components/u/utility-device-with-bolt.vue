<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0xn476-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t0xn476-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-device-with-bolt" /></template>
