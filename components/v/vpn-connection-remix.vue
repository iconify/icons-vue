<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gduto0bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gduto0bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:vpn-connection-remix" /></template>
