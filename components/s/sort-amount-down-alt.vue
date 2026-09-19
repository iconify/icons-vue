<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv815x65j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hv815x65j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-amount-down-alt" /></template>
