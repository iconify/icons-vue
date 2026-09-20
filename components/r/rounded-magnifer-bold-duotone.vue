<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcpnkmxdp.css';
import '../../css/t/t4z7qo_ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcpnkmxdp"/><path clip-rule="evenodd" class="t4z7qo_ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-bold-duotone" /></template>
