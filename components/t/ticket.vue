<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0wn-wuie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0wn-wuie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ticket" /></template>
