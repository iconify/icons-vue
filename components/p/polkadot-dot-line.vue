<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvdwicxgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvdwicxgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polkadot-dot-line" /></template>
