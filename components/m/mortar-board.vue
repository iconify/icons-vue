<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwwn-tela.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="nwwn-tela"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mortar-board" /></template>
