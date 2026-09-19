<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7m9ovowg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7m9ovowg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-normal-duotone" /></template>
