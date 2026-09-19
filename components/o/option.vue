<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmh5s_g6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tmh5s_g6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:option" /></template>
