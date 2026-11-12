<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg10sto-u.css';
import '../../css/c/cczp_s_we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dg10sto-u"/><path class="cczp_s_we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:red-hat-light" /></template>
