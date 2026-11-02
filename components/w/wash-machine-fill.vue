<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywvr6nbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywvr6nbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wash-machine-fill" /></template>
