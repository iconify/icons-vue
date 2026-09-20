<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3hjwxbca.css';
import '../../css/o/o71oribfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g3hjwxbca"/><path class="o71oribfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mozilla-monitor-dark" /></template>
