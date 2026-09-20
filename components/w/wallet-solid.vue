<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byw7okbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="byw7okbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wallet-solid" /></template>
