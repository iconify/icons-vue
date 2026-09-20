<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xluo-0b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xluo-0b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:pin-filled" /></template>
