<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx3xu4_0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yx3xu4_0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-bug2" /></template>
