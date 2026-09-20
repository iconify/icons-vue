<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww373s-as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww373s-as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:transaction-minus-filled" /></template>
