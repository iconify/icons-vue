<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvq-2xblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wvq-2xblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:storage" /></template>
