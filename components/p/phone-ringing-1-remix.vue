<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpqtypbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fpqtypbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-ringing-1-remix" /></template>
