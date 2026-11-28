<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpt0x2bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpt0x2bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:signal-medium-solid" /></template>
