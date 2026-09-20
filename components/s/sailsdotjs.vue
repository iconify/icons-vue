<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2k-k1brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2k-k1brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sailsdotjs" /></template>
