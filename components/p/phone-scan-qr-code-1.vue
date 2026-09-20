<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv2c330tb.css';
import '../../css/o/of89spbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jv2c330tb"/><path class="of89spbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:phone-scan-qr-code-1" /></template>
