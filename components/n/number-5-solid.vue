<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxo5b6gwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxo5b6gwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-5-solid" /></template>
