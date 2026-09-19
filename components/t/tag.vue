<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq2mk-bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lq2mk-bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:tag" /></template>
