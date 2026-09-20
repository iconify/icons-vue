<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srvpyl1yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="srvpyl1yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:navigation-left-hide" /></template>
