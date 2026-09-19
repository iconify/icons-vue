<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbkaf_btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbkaf_btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vtm" /></template>
