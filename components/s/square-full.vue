<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9jgx7bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9jgx7bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:square-full" /></template>
