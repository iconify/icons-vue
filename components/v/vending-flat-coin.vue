<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfvyi0osq.css';
import '../../css/u/uo31dmb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sfvyi0osq"/><path class="uo31dmb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vending-flat-coin" /></template>
