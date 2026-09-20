<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxe710bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxe710bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:motorola" /></template>
