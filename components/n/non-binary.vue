<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhlftk48t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhlftk48t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:non-binary" /></template>
