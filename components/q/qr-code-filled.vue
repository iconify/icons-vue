<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzv543hpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xzv543hpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:qr-code-filled" /></template>
