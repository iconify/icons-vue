<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-dvm-v0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-dvm-v0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ruler-combine" /></template>
