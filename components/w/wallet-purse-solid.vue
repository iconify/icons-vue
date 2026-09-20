<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1_2fvbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k1_2fvbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wallet-purse-solid" /></template>
