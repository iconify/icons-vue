<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btt16zbsb.css';
import '../../css/y/yov2mac9k.css';
import '../../css/n/nknwp425q.css';
import '../../css/b/bzswhqb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="btt16zbsb"/><path class="yov2mac9k"/><path class="nknwp425q"/><path class="bzswhqb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:marine-warning" /></template>
