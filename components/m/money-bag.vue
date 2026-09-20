<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw-jdgbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw-jdgbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-bag" /></template>
