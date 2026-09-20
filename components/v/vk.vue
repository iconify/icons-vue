<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmm02yz3c.css';
import '../../css/m/mc6ws4xxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmm02yz3c"/><path class="mc6ws4xxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:vk" /></template>
