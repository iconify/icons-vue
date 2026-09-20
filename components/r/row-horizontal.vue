<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjk79fo0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjk79fo0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:row-horizontal" /></template>
