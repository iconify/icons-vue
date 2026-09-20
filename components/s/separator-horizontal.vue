<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htt2-vb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htt2-vb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:separator-horizontal" /></template>
