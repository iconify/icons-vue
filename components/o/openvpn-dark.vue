<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buqa66bjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="buqa66bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openvpn-dark" /></template>
