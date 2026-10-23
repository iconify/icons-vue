<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jol61g51n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jol61g51n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:utility-pole" /></template>
