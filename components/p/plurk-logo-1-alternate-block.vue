<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0_qcbctw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0_qcbctw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:plurk-logo-1-alternate-block" /></template>
