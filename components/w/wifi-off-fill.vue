<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjmr10bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjmr10bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wifi-off-fill" /></template>
