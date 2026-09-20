<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb06wxbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kb06wxbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-qr-solid" /></template>
