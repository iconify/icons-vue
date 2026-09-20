<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncmu2q-rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ncmu2q-rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paragraph-solid" /></template>
