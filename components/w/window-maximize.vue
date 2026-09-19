<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m63kvxbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m63kvxbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:window-maximize" /></template>
