<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwec1599h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwec1599h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-italic" /></template>
