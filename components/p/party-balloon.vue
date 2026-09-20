<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pos-wvb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pos-wvb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:party-balloon" /></template>
