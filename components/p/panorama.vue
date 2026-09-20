<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmj-enboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kmj-enboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:panorama" /></template>
