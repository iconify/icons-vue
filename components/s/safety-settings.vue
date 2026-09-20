<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okwkdrbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okwkdrbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:safety-settings" /></template>
