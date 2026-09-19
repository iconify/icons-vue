<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn3wbh0ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":330,"height":512};
const content = `<path class="sn3wbh0ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:solidity" /></template>
