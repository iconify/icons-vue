<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f40r4ef-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f40r4ef-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:notification" /></template>
