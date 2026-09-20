<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf0xr6inp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uf0xr6inp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:vpn-connection-solid" /></template>
