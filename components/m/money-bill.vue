<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anr0_ixlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anr0_ixlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:money-bill" /></template>
