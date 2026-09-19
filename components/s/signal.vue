<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_ka4sc6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a_ka4sc6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:signal" /></template>
