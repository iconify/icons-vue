<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5s6svbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5s6svbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:p-i-diagram" /></template>
