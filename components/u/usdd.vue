<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iistc1ber.css';
import '../../css/p/pl-clrbxd.css';
import '../../css/i/i4y0aubop.css';
import '../../css/w/wb1puackx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iistc1ber"/><path class="pl-clrbxd"/><path class="i4y0aubop"/><path class="wb1puackx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:usdd" /></template>
