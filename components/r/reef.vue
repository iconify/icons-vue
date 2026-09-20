<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsdw_21te.css';
import '../../css/i/ihcr3ob1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsdw_21te"/><path class="ihcr3ob1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:reef" /></template>
