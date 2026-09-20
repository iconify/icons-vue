<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdfezzbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdfezzbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:tifi" /></template>
