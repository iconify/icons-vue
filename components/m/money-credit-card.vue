<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg778vblv.css';
import '../../css/p/pbnebbk0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jg778vblv"/><path clip-rule="evenodd" class="pbnebbk0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:money-credit-card" /></template>
