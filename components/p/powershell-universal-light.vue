<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av4hyxbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="av4hyxbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:powershell-universal-light" /></template>
