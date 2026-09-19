<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzonc9brq.css';
import '../../css/h/h2ks3p8yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wzonc9brq"/><path class="h2ks3p8yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:monitor" /></template>
