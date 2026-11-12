<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0g7ckb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z0g7ckb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-paper-light" /></template>
