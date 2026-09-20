<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwx1dmp2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dwx1dmp2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:severity-info" /></template>
