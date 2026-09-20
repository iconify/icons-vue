<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgiie_btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgiie_btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:wheel-barrow" /></template>
