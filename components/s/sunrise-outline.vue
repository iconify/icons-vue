<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx-i8_b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx-i8_b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sunrise-outline" /></template>
