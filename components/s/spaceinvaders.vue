<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8isedb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="w8isedb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:spaceinvaders" /></template>
