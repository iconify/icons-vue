<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t21kzacmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t21kzacmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qrcode-line" /></template>
