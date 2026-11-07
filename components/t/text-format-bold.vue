<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkqq6fire.css';
import '../../css/u/ulrix6h0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkqq6fire"/><path class="ulrix6h0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-format-bold" /></template>
