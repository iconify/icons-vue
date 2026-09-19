<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p66n0forz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p66n0forz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:outlet" /></template>
