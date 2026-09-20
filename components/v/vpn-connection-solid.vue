<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdd_mkcjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gdd_mkcjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:vpn-connection-solid" /></template>
