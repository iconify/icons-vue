<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2rn8_e7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2rn8_e7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-warning-03" /></template>
