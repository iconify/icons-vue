<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnl2ysb4i.css';
import '../../css/x/xe8w9nb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fnl2ysb4i"/><path class="xe8w9nb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oscilloscope-20" /></template>
