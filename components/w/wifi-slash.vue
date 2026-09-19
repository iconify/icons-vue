<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_t8mxb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x_t8mxb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:wifi-slash" /></template>
