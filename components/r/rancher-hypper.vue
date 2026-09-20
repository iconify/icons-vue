<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_jj5jfvq.css';
import '../../css/l/lrth8l6xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_jj5jfvq"/><path class="lrth8l6xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-hypper" /></template>
