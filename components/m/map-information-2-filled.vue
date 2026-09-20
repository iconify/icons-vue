<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiq-_lbxp.css';
import '../../css/j/j0xfjhbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiq-_lbxp"/><path class="j0xfjhbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-information-2-filled" /></template>
