<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8l0oobdd.css';
import '../../css/w/wg3u04byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8l0oobdd"/><path class="wg3u04byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shirt" /></template>
