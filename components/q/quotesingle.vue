<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7f_7yuah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":94,"height":723};
const content = `<path class="r7f_7yuah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:quotesingle" /></template>
