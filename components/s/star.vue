<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji6w31kzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji6w31kzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:star" /></template>
