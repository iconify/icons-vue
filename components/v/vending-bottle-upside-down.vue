<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ysgrd8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b4ysgrd8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:vending-bottle-upside-down" /></template>
