<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yejv2fbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yejv2fbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:trophy-solid" /></template>
