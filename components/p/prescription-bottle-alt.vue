<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adhe8v3hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="adhe8v3hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:prescription-bottle-alt" /></template>
