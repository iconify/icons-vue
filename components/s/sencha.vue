<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duv2dac2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duv2dac2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sencha" /></template>
