<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c88zfpbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c88zfpbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:screw-machine-round-top" /></template>
