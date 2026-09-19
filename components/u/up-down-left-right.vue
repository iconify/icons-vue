<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac0dbpb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ac0dbpb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:up-down-left-right" /></template>
