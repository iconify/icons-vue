<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljt5rwruv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ljt5rwruv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-circle-fill-20" /></template>
