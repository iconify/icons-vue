<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l97nb-quh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="l97nb-quh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:wifi-0" /></template>
