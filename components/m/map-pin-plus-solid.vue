<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1zd-dmnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1zd-dmnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-plus-solid" /></template>
