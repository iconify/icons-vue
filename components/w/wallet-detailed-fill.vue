<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov8walbuy.css';
import '../../css/f/fwj4s1b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8walbuy"/><path clip-rule="evenodd" class="fwj4s1b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:wallet-detailed-fill" /></template>
