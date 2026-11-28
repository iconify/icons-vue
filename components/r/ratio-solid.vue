<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crofpbcfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crofpbcfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ratio-solid" /></template>
