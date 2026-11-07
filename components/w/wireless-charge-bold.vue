<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmr5y1isy.css';
import '../../css/i/i_u1m3bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fmr5y1isy"/><path class="i_u1m3bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wireless-charge-bold" /></template>
