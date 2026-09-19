<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djr264bkf.css';
import '../../css/k/kb4k8nblj.css';
import '../../css/c/c0pinfbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djr264bkf"/><path class="kb4k8nblj"/><path class="c0pinfbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:more" /></template>
