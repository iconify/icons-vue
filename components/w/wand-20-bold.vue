<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5gnfjbdr.css';
import '../../css/l/lj6h3gwfe.css';
import '../../css/c/c1mb_dbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b5gnfjbdr"/><path class="lj6h3gwfe"/><path class="c1mb_dbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wand-20-bold" /></template>
