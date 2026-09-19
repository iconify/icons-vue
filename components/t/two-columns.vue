<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrbn-ftbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrbn-ftbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:two-columns" /></template>
