<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ombcu7bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ombcu7bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield-half-filled" /></template>
