<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__-3obnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1013};
const content = `<path class="q__-3obnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:technorati" /></template>
