<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg8otqbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yg8otqbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tree" /></template>
