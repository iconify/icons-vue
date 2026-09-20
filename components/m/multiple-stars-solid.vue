<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wblctf01d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wblctf01d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:multiple-stars-solid" /></template>
