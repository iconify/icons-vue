<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9p4n1_lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y9p4n1_lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-cleaning-20" /></template>
