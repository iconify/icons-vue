<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ousr7gb-s.css';
import '../../css/o/o_v56d7tv.css';
import '../../css/p/plon33w2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ousr7gb-s"/><path class="o_v56d7tv"/><path class="plon33w2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:panel-right" /></template>
