<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg10sto-u.css';
import '../../css/h/h0ngerbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dg10sto-u"/><path class="h0ngerbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:red-hat-light" /></template>
