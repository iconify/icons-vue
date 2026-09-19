<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt2gydb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qt2gydb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:shuffle" /></template>
