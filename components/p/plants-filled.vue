<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx_m0xbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xx_m0xbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plants-filled" /></template>
