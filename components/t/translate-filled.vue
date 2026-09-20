<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guak-rt4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="guak-rt4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:translate-filled" /></template>
