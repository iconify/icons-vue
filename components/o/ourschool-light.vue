<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwhay-qcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwhay-qcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ourschool-light" /></template>
