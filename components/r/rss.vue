<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exm41o2bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="exm41o2bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:rss" /></template>
