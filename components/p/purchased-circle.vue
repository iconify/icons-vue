<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5d_gtbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="p5d_gtbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:purchased-circle" /></template>
