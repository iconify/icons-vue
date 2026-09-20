<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5et7lbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5et7lbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tab-add" /></template>
