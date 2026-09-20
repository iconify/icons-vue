<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvy3kqb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yvy3kqb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sosse-dark" /></template>
