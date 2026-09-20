<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reybrkbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="reybrkbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:navigation-arrow-on-solid" /></template>
