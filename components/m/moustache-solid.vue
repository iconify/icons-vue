<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx-2j1bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tx-2j1bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:moustache-solid" /></template>
