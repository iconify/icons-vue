<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk-9l5boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="kk-9l5boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:yen-sign" /></template>
