<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6hevcvfn.css';
import '../../css/t/t3y9293jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6hevcvfn"/><path clip-rule="evenodd" class="t3y9293jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-network-bold-duotone" /></template>
