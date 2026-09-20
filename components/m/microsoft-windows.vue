<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysdzf_bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysdzf_bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:microsoft-windows" /></template>
