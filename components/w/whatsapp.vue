<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew6x_87ns.css';
import '../../css/l/lfj5m2b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew6x_87ns"/><path class="lfj5m2b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:whatsapp" /></template>
