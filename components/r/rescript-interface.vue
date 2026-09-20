<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvu1ubcpn.css';
import '../../css/p/po8pqxbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bvu1ubcpn"/><path class="po8pqxbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rescript-interface" /></template>
