<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks14vpbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ks14vpbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:tongue2" /></template>
