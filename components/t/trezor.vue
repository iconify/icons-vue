<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh_miccqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh_miccqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:trezor" /></template>
