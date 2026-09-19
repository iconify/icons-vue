<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abgdj92nu.css';
import '../../css/g/ggga5ib7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abgdj92nu"/><path class="ggga5ib7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pull-request" /></template>
