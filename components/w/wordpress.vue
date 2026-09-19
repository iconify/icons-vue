<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhuwsobbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":995.329,"height":1000};
const content = `<path class="bhuwsobbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:wordpress" /></template>
