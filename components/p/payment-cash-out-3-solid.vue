<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjzmo6ptv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jjzmo6ptv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:payment-cash-out-3-solid" /></template>
