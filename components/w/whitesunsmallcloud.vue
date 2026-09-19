<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03tt64we.css';
import '../../css/g/gocezb5zs.css';
import '../../css/c/cv7o1ybwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="w03tt64we"/><path class="gocezb5zs"/><path class="cv7o1ybwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitesunsmallcloud" /></template>
