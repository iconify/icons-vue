<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2xwtsb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2xwtsb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-cheese" /></template>
