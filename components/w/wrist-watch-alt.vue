<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvj1klb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvj1klb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch-alt" /></template>
