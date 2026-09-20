<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2oe2d-ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n2oe2d-ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:redhat" /></template>
