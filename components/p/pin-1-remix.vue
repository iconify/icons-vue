<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncojv-bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ncojv-bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pin-1-remix" /></template>
