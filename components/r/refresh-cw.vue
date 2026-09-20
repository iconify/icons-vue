<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3dtuh8zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3dtuh8zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:refresh-cw" /></template>
