<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbk-pdb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gbk-pdb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-car" /></template>
