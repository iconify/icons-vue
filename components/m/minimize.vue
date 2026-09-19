<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skx7hxbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skx7hxbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:minimize" /></template>
