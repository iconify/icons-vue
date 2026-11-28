<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkrka85cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkrka85cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:qr-code-x" /></template>
