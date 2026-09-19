<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf467nb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wf467nb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-eye" /></template>
