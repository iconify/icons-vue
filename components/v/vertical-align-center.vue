<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjpn_9bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xjpn_9bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:vertical-align-center" /></template>
