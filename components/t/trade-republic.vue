<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqzfx8bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqzfx8bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:trade-republic" /></template>
