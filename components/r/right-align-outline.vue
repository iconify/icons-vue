<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq2klur4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kq2klur4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:right-align-outline" /></template>
