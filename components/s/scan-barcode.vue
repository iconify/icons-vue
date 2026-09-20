<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s64ns0bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s64ns0bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-barcode" /></template>
