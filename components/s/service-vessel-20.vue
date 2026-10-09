<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y58kh1nko.css';
import '../../css/b/b97oakqpf.css';
import '../../css/y/y8gnmo4cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y58kh1nko"/><path class="b97oakqpf"/><path class="y8gnmo4cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:service-vessel-20" /></template>
