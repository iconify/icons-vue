<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljmd1i_bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljmd1i_bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phylum" /></template>
