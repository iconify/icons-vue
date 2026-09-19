<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncaoi_bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ncaoi_bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:teeth-open" /></template>
