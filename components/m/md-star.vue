<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3nt_n9qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3nt_n9qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-star" /></template>
