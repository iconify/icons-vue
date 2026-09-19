<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kee_ltbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="kee_ltbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:up-circle" /></template>
