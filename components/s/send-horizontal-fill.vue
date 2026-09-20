<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5syz5bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5syz5bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-horizontal-fill" /></template>
