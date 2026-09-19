<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cetnc8bas.css';
import '../../css/d/d2kx6_b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cetnc8bas"/><path class="d2kx6_b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-information" /></template>
