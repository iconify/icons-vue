<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uov-5mbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uov-5mbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:smallorangediamond" /></template>
