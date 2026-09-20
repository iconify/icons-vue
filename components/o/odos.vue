<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezvi_qpnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezvi_qpnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:odos" /></template>
