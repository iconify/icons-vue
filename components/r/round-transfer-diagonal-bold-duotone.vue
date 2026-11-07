<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntj_g2bxu.css';
import '../../css/f/fg5sr67vv.css';
import '../../css/e/exa1j-bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntj_g2bxu"/><path class="fg5sr67vv"/><path class="exa1j-bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-transfer-diagonal-bold-duotone" /></template>
