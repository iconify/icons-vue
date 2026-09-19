<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3-_e5b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":674};
const content = `<path class="p3-_e5b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:networksignal" /></template>
