<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpt2ttbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpt2ttbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:polaroid-solid" /></template>
