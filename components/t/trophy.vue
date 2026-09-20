<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9n0nyb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f9n0nyb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:trophy" /></template>
