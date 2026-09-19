<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g52asd2ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g52asd2ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:stats-bars" /></template>
