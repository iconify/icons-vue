<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si_2wxbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si_2wxbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:qrcode" /></template>
