<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyz6b5bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyz6b5bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:meshcore" /></template>
