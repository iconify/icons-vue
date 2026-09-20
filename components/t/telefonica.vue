<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iej9w3psn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iej9w3psn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:telefonica" /></template>
