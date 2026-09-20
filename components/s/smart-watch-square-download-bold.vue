<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uov_tcc-r.css';
import '../../css/r/rfvufj5tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uov_tcc-r"/><path class="rfvufj5tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smart-watch-square-download-bold" /></template>
