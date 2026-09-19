<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s45ra5bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s45ra5bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:smoke-alarm" /></template>
