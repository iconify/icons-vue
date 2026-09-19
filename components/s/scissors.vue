<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6k5j8bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n6k5j8bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:scissors" /></template>
