<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh0ehhbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh0ehhbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:wrench-1" /></template>
