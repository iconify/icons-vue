<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6l3rxbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6l3rxbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:strd" /></template>
