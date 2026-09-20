<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utxo58v5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="utxo58v5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:speech-bubbles" /></template>
