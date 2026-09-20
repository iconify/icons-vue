<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzx72lvrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzx72lvrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wineglass-2-line" /></template>
