<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfzvn7btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfzvn7btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pot-fill" /></template>
