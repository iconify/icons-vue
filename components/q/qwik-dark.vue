<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c60-6kb4c.css';
import '../../css/z/ziz-v20vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c60-6kb4c"/><path class="ziz-v20vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qwik-dark" /></template>
