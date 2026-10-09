<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrjlwqjtj.css';
import '../../css/a/au4v49w_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jrjlwqjtj"/><path class="au4v49w_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-high-20-bold" /></template>
