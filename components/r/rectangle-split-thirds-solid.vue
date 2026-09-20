<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz75bwb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yz75bwb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:rectangle-split-thirds-solid" /></template>
