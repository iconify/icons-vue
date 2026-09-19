<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd98dbd-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="nd98dbd-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:taxi" /></template>
