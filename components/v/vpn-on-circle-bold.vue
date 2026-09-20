<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiz2uy2dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yiz2uy2dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vpn-on-circle-bold" /></template>
