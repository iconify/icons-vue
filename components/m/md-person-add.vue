<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaur_9bvy.css';
import '../../css/f/f46yzabqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aaur_9bvy"/><path class="f46yzabqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-person-add" /></template>
